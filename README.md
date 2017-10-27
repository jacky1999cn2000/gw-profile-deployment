# gw-profile-deployment

* retrieve profile and custom object together would get corresponding custom object's FLS for the specified profile, and can modify `<editable>` and `<readable>` in the profile, and deploy it back after modification.

* don't use `/` in profile name - there was a profile called `GW Inside/Sales Ops` in the organization, and Ant can't recognize the special character `/`, so I had to change the profile's name to `GW Inside-Sales Ops` first, made the modification, deployed it back, and then change the name back. 

* standard profile and their API names

![standard profiles](https://github.com/jacky1999cn2000/gw-profile-deployment/blob/master/images/profiles.jpg)
