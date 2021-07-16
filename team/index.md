---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: chunhiem"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: truonglab"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: k611"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: thanhvien1"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: thanhvien2"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: thanhvien3"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: thanhvien4"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: thanhvien5"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: thanhvien6"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: thanhvien7"
%}{%
  include list.html
  data="members"
  component="portrait"
  filters="role: thanhvien8"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: thanhvien9"
%}
{%
  include list.html
  data="members"
  component="portrait"
  filters="role: thanhvien10"
%}
{:.center}

{% include section.html background="images/banner.jpg" dark=true%}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{%
  include link.html
  icon="fas fa-hands-helping"
  text="Join the Team"
  link="/contact"
  style="button"
%}
{:.center}

{% include section.html %}

## Funding

Our work is made possible by funding from several organizations.
{:.center}

{%
  include gallery.html
  style="square"

  image1="images/funding1.jpg"
  link1="/images/funding1.jpg"
  tooltip1="Cool Foundation"

  image2="images/funding2.jpg"
  link2="/images/funding2.jpg"
  tooltip2="Cool Institute"

  image3="images/funding3.jpg"
  link3="/images/funding3.jpg"
  tooltip3="Cool Initiative"

  image4="images/funding4.jpg"
  link4="/images/funding4.jpg"
  tooltip4="Cool Foundation"

  image5="images/funding9.jpg"
  link5="/images/funding9.jpg"
  tooltip5="Cool Institute"

  image6="images/funding7.jpg"
  link6="images/funding7.jpg"
  tooltip6="Cool Initiative"
%}
