# gw-profile-deployment

* retrieve profiles and custom objects together would get all fields of specified custom objects for specified profiles, then we can modify `<editable>` and `<readable>` in the profiles, and deploy it back after modification.

* retrieve profiles and custom fields together would get the specified fields of specified custom objects for specified profiles, then we can modify `<editable>` and `<readable>` in the profiles, and deploy it back after modification.

* don't use `/` in profile name - there was a profile called `GW Inside/Sales Ops` in the organization, and Ant can't recognize the special character `/`, so I had to change the profile's name to `GW Inside-Sales Ops` first, made the modification, deployed it back, and then change the name back.

* standard profile and their API names

* permission set can use the same method

![standard profiles](https://github.com/jacky1999cn2000/gw-profile-deployment/blob/master/images/profiles.jpg)
