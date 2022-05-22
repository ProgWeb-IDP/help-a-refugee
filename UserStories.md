# User stories

## Administrator
* As an **administrator** I would like to be able to:
   - **See a list of registered volunteers/users/adminstrators**
   - **See a list of volunteer applications**
     - For each application I want to **approve** or **decline** the request
   - **Validate a donation request** made by a volunteer
     - If needed, I want to **approve** any donation request
     - If needed, I want to **decline** any donation request
   - **Add locations**, by providing their **name**
   - **Add volunteer roles**, by providing their **name** and a **short description**
   - **View overview metrics**
     - **Metrics** should be **how many donations** were **made** (fulfilled or not), **how many donation requests** were **made** (approved or not)
     - **Metrics** should be **number of users** and **volunteers**, **number of donations** (**rejected/accepted/collected/delivered/pending**), **number of donation requests** (**rejected/pending/active/completed**), **total resources donated** and **average resources donated per user**

## Volunteer
* As a **volunteer** I would like to be able to:
  - Setup a **profile**, comprised of **first name**, **last name**, **gender**, **phone number**, **country**, **city**, **street**, **address**, **ZIP code**
  - **Create donation requests**, comprised of **resource type, quanityty nedeed** and a **short description**
  - **See** a **summary** of my **donation requests**
    - If needed, I want to **see** more details (**quantity gathered**) about a **donation**
  - **See** the **donations** from any user
    - I want to **see** **tables** for **pending / accepted / collected** donations
    - If needed, I want to **accept** a **pending donation** from a user
    - If needed, I want to **decline** a **pending donation** from a user
    - If needed, I want to **collect** a **accepted donation**
    - I want to **deliver** a **collected donation**

## Normal user
* As a **user** I would like to be able to:
  - Setup a **profile**, comprised of **first name**, **last name**, **gender**, **phone number**, **country**, **city**, **street**, **address**, **ZIP code**
  - **See** any **available** donation requests
  - **Donate** to any **available** donation request
    - I **do not** want to **donate** more than **necessary**
    - I **do not** want to be able to donate if my profile details are incomplete
  - **Apply** to become a **volunteer**, based on a **form** comprised of **role**, **location** and **summarry**
    - I want to **choose** a **role** from a list with current roles
    - I want to **choose** a **location** from a list with current locations
    - If needed, I want to **add** a short description to my **request**
  
