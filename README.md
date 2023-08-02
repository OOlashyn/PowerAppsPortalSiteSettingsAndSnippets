[![SWUbanner](https://raw.githubusercontent.com/vshymanskyy/StandWithUkraine/main/banner-direct.svg)](https://vshymanskyy.github.io/StandWithUkraine)

# Site Settings & Content Snippets for Power Apps Portals
> List of little known and hidden Content Snippets and Site Settings for Power Apps Portals

## Site Settings

- **DateTime/DateFormat** - Change the date time format for display and datetime picker in portal (ex. dd/MM/yyyy)
- **Portal/Lookup/Modal/Grid/PageSize** - controls page size for lookup modal grids (Default: "10")
- **Portal/Lookup/Modal/Size** - control size of lookup modal (Default: "Large". Available value: "Small", "Large")

## Content Snippets

- **Browser Title Suffix** - allows to set title sufix for all pages of your Portal
- **Head/Bottom** - allows to add content to the end of the head tag (useful for setting metadata, etc)
- **Head/Fonts** - allows to add css or link to stylesheet to the head tag
- **Tracking Code** - created by the system when you setup Portal analytics. Contains tracking code define by the user that will be added to the bottom of every page
- **links/logout** - text for standard signout button
- **links/login** - text for standard signin button
- **Account/Nav/SignIn** - text for Sign In page title
- **Portal/Lookup/Modal/Title** - text for lookup modal title (Default: "Lookup Records"). Applies to all lookup modals
- **Portal/Lookup/Modal/PrimaryButtonText** - text for lookup modal primary button (Default: "Select"). Applies to all lookup modals
- **Portal/Lookup/Modal/CancelButtonText** - text for lookup modal cancel button (Default: "Cancel"). Applies to all lookup modals
- **Portal/Lookup/Modal/DismissButtonSrText** - text for lookup modal dismiss button (Default: "Close"). Applies to all lookup modals
- **Portal/Lookup/Modal/RemoveValueButtonText** - text for lookup modal remove value button (Default: "Remove Value"). Applies to all lookup modals
- **Portal/Lookup/Modal/DefaultErrorMessage** - text for lookup modal default error message. Default: 
```html
<p>We are sorry, an error has occurred.</p>
```
Applies to all lookup modals
- **Portal/Lookup/Modal/Grid/LoadingMessage** - text for lookup modal grid loading message. Default: 
```html
<span class='fa fa-spinner fa-spin' aria-hidden='true'></span> Loading...
```
Applies to all lookup modals
- **Portal/Lookup/Modal/Grid/ErrorMessage** - text for lookup modal grid error message. Default:
```html
Error completing request. <span class='details'></span>
```
Applies to all lookup modals
- **Portal/Lookup/Modal/Grid/AccessDeniedMessage** - text for lookup modal grid access denied message (Default: "Access Denied. You do not have permissions to view these records."). Applies to all lookup modals
- **Portal/Lookup/Modal/Grid/EmptyMessage** - text for lookup modal grid empty message (Default: "There are no records to display."). Applies to all lookup modals
- **Portal/Lookup/Modal/Grid/ToggleFilterText** - text for lookup modal grid toggle filter text (Default: "Toggle filter"). Applies to all lookup modals
- **Portal/Lookup/Modal/Grid/Search/PlaceholderText** - text for lookup modal search placeholder (Default: "Search"). Applies to all lookup modals
- **Portal/Lookup/Modal/Grid/Search/TooltipText** - text for lookup modal search tooltip (Default: "To search on partial text, use the asterisk (*) wildcard character"). Applies to all lookup modals
- **CustomerService/Support/SignIn** - text for default sign in message (Default: "Please sign in to open a new case or to view a list of your existing cases.")
- **Account/Nav/Redeem** - text for redeem invitation section of the sign in page (Default: "Redeem invitation")
- **Account/Redeem/InvitationCodeFormHeading** - text for header on Sign up with Invitation Code page (Default: "Sign up with an invitation code") 
- **Account/Redeem/InvitationCodeLabel** - text for Invidation Code of the Redeem Invitation page (Default: "Invitation code")
- **Profile Submit Button Text** - text for submit button on Profile page (Default: "Update")
- **Account/Nav/Register** - text for Register section of the sign in page (Default: "Register")
- **Account/SignIn/PasswordResetLabel** - text for Forgot passowrd button on the local sign in page (Default: "Forgot your password?")
- **Account/SignIn/SignInLocalButtonText** - text for Sign in button on the local sign in page (Default: "Sign In")
- **Account/PasswordReset/EmailLabel** - text for Forgot password screen Email label. (Default: "Email")
- **Account/PasswordReset/EmailInstructionsText** - text for Forgot password screen email instructions text. (Default: "Enter your email address to request a password reset")
-**Account/PasswordReset/ForgotPasswordFormHeading** - text for Forgot password screen form heading. (Default: "Forgot your password?")

## Contribute

Contributions are really welcome! Create a PR with Site Settings/Content Snippets and it will be reviewed and merged if applicable (ie Site Settings/Content Snippets works as described).

## Found an issue

There are two ways to help:

- Submit Pull Request 
- Create an issue

