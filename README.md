# Shopping Preferences

Using the Shopping Preferences Chrome extension, users can set and share their shopping preferences, which allows online retailers to personalize their shopping experience.

## User guide

After installing the Chrome extension, a ![Image of Shopping Preferences button](https://github.com/shaungallagher/shoppingprefs/raw/master/shoppingPrefs-24.png) button will be added to your browser's toolbar.  Clicking the button will open a control panel, where you can set your shopping preferences and some general demographic information.  (Fill in as many or as few of the fields as you wish.  It's all under your control!)

The extension will provide your shopping preferences to online retailers by setting cookies on their site, which expire at the end of your shopping session.

## Retailer guide

You can discover visitors' shopping preferences by checking for the existence of the following cookies:

- `shoppingPrefs-bargainDriven`: a number from 1 to 5, indicating how influenced the user is by bargains and discounts.

- `shoppingPrefs-qualityDriven`: a number from 1 to 5, indicating how influenced the user is by product quality.

- `shoppingPrefs-brandDriven`: a number from 1 to 5, indicating how influenced the user is by name brands.

- `shoppingPrefs-reviewDriven`: a number from 1 to 5, indicating how influenced the user is by customer reviews.

- `shoppingPrefs-age`: a string that contains a user's age or age range.

- `shoppingPrefs-sex`: a string whose value is either "M" for male or "F" for female.

- `shoppingPrefs-income`: a string indicating the user's annual household income, expressed as a range.

- `shoppingPrefs-maritalStatus`: a string indicating the user's marital status.

- `shoppingPrefs-dependents`: a string indicating whether the user has any child or adult dependents.

- `shoppingPrefs-home`: a string indicating whether the user owns or rents their home.
