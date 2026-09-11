# App-login-screen-in-xamarin

This Xamarin.Forms sample demonstrates how to create a modern and visually appealing authentication experience using Syncfusion controls. The sample includes both **Sign In** and **Log In** screens commonly found in mobile applications. These screens provide users with intuitive account access options while showcasing modern UI design practices for Xamarin.Forms applications.

The application uses a combination of Xamarin.Forms layouts and Syncfusion controls to build a professional authentication workflow. The screens feature attractive background imagery, rounded card layouts, social login buttons, avatar presentation, and input validation controls. The design focuses on simplicity, accessibility, and ease of use, making it suitable for a wide variety of consumer and business applications.

The Sign In page provides a registration and account access experience through email validation and social authentication options. Users can enter their email address and continue the sign-in process using a validated input field powered by Syncfusion's SfMaskedEdit control. Multiple social sign-in options are available, allowing users to continue using popular authentication providers.

The Log In page provides an existing-user authentication experience. It displays user profile information using Syncfusion's SfAvatarView control and allows users to enter their password before continuing. The page is designed to create a personalized experience by presenting account details alongside a secure login interface.

## Features

- Modern mobile authentication user interface.
- Dedicated Sign In and Log In screens.
- Email validation using Syncfusion SfMaskedEdit.
- Social authentication button layouts.
- Profile avatar display using Syncfusion SfAvatarView.
- Clean card-based interface design.
- Responsive layout suitable for different screen sizes.
- Password entry support.
- Account registration prompts.
- Forgot password functionality.
- Professional dark-themed application design.

## Sign In Page

The Sign In page allows users to begin the authentication process through email verification or social login providers. The page includes:

- Welcome message and branding image.
- Email validation field.
- Continue button.
- Facebook login option.
- Google login option.
- Apple login option.
- Sign Up navigation prompt.
- Forgot password option.

The email input field is implemented using Syncfusion's SfMaskedEdit control, ensuring that entered values follow a valid email format.

## Log In Page

The Log In page is designed for returning users. The page displays account information and provides a secure password entry experience.

The page contains:

- Profile image displayed using Syncfusion SfAvatarView.
- User name information.
- Email address information.
- Password entry field.
- Continue button.
- Forgot password option.

This layout creates a personalized login experience while maintaining a clean and modern appearance.

## Authentication Experience

The sample demonstrates common authentication workflows used in modern mobile applications:

1. User opens the application.
2. User chooses to sign in or log in.
3. Email validation ensures proper input format.
4. Social authentication options provide alternative sign-in methods.
5. Returning users can enter their password and continue.
6. Account recovery is available through the forgot password option.

## Syncfusion Controls Used

### SfMaskedEdit

The Syncfusion SfMaskedEdit control is used for validating email address input. By applying a regular expression mask, the control helps ensure that users enter properly formatted email addresses.

Benefits include:

- Email format validation.
- Improved data accuracy.
- Enhanced user experience.
- Reduced validation errors.

### SfButton

Syncfusion SfButton controls are used throughout the authentication workflow to provide visually consistent action buttons.

These buttons are used for:

- Continue actions.
- Social sign-in providers.
- Authentication navigation.

### SfAvatarView

The Syncfusion SfAvatarView control is used on the Log In page to display profile information in a visually attractive format.

Benefits include:

- Personalized user experience.
- Professional profile presentation.
- Modern authentication UI design.

## User Interface Design

The application follows modern authentication screen design principles:

- Full-screen hero image.
- Dark theme styling.
- Rounded cards and containers.
- Consistent spacing and alignment.
- Clear call-to-action buttons.
- Easy navigation between authentication flows.

These design elements help create an engaging and user-friendly experience.

## Requirements

- Visual Studio 2019 or later
- Xamarin.Forms
- Syncfusion Xamarin Buttons
- Syncfusion Xamarin MaskedEdit
- Syncfusion Xamarin AvatarView

## NuGet Packages

```text
Syncfusion.Xamarin.Buttons
Syncfusion.Xamarin.SfMaskedEdit
Syncfusion.Xamarin.Core
```

## Running the Sample

1. Clone or download the repository.
2. Restore all required NuGet packages.
3. Build the Xamarin.Forms solution.
4. Deploy the application to Android, iOS, or UWP.
5. Launch the application.
6. Navigate through the Sign In and Log In screens.
7. Test email validation and authentication workflows.

## Use Cases

This sample can be used as a reference for:

- Mobile authentication screens.
- Sign In and Log In workflows.
- User onboarding experiences.
- Account management applications.
- Social authentication interfaces.
- Enterprise application login systems.
- Xamarin.Forms UI design implementations.

## Conclusion

This sample demonstrates how to build modern Sign In and Log In screens in Xamarin.Forms using Syncfusion controls. By leveraging SfMaskedEdit for input validation, SfButton for user actions, and SfAvatarView for profile presentation, developers can create secure, responsive, and visually appealing authentication experiences for mobile applications.
