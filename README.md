# Download ScreenConnect Client

To set up the ScreenConnect Client using the EXE package, follow the steps below. If you're planning to deploy the client organization-wide, consider using the `msiexec` command via the terminal for streamlined installation.

1. Get the appropriate version of the ScreenConnect Client installer for your operating system:

2. Launch the installer by double-clicking on the downloaded file.

3. When the welcome screen appears, select **Next**.

4. Accept the license terms by checking **I accept the terms in the License Agreement**, then proceed by clicking **Next**.

5. Under Installation Scope, select one of these options:

* **Install only for you**: Installs the ScreenConnect Client to a user-specific location, making it accessible only from your account. No admin rights are needed.

* **Install for all users on this machine**: Makes the ScreenConnect Client available to all user profiles on the device. Admin privileges are necessary.

6. Click **Install** to begin the setup.

7. Once the installation finishes, click **Finish**.

8. If the option **Launch ScreenConnect Client when setup exits** is enabled, the application will launch automatically. If not, you can open it manually by searching **ScreenConnect Client** from the Start menu.

Before connecting to remote devices or applications on Windows, ensure the following prerequisites are met:

* An active Internet connection

* A supported Windows version:

  * Windows 11
  * Windows 10
  * Windows Server 2022
  * Windows Server 2019
  * Windows Server 2016

* .NET Framework 4.6.2 or above. On certain Windows 10 and Windows Server 2016 systems, this might require manual installation. For the latest version, visit the .NET Framework download page.

### .NET 8 requirement

Beginning with version 4.0.1.0, the desktop version of ScreenConnect Client requires the .NET 8 runtime. If not already installed, the MSI installer for ScreenConnect Client will automatically download and install it. For systems without .NET 8, ensure they can access the following URLs:

The .NET 8 runtime is essential for delivering the most up-to-date and refined UI experience within the desktop client. Note that even on x64 platforms, the x86 package is necessary due to specific automation components available only in 32-bit mode.

If you encounter errors related to .NET 8 runtime installation, it could be due to connectivity issues with the URLs or unsuccessful installation of one or more runtime packages. In such cases, manually install both runtime versions. Once installed, subsequent versions of ScreenConnect Client will not attempt to re-download the .NET 8 runtime.

### Android

To install the ScreenConnect Client on an Android device, choose one of the following app stores:

* [Portal AppStore](*)
* [Google Play](*)
* [Amazon Appstore for Android](*)

If none of these stores are accessible, or your device lacks Google Mobile Services, you may [manually download ScreenConnect Client for Android](*) and install it yourself. Keep in mind that side-loaded applications do not receive automatic updates or security patches and must be updated manually.

Note: In the People's Republic of China, the Google Play Store is not available. In such cases, use a government-approved Chinese app store to install the ScreenConnect Client app.

### iOS

To set up ScreenConnect Client on iOS, download it directly from the [Apple App Store](*).

### macOS

For macOS systems, install the ScreenConnect Client by visiting [Enroll my Mac](*). This link will trigger the download of the appropriate installer package automatically.

## Sign in to app

There are three supported methods for signing in to the ScreenConnect Client application:

* Authenticate using your school or work email and password.
* Use certificate-based sign-in.
* Log in from another device.

For the most seamless experience, follow your organization's preferred or required authentication method.

### Sign in with school or work account

1. Launch the application and click **Sign In**.
2. Provide your work or school email address and press **Next**.
3. Enter your password and select **Sign In**.
4. The app will verify your credentials. Once authenticated, access to your organization’s features and services will be granted.

### Sign in with certificate

This option appears only if your organization has enabled certificate-based authentication and a valid certificate is available.

1. Open the ScreenConnect Client on your device
2. Input the email address tied to your work or school account and click **Next**
3. Choose Sign in with a certificate.
4. Tap **Continue** to proceed with certificate confirmation.
5. The app will validate the certificate. Once approved, access to your organization’s resources and app features will be provided
