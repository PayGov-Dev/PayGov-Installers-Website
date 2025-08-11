# PayGov POS Installer

This repository contains the PayGov POS Installer files and a modern, responsive website to download different versions of the installer.

## Repository Structure

- **CNAME**: Contains the custom domain for the GitHub Pages site.
- **index.html**: The main webpage for downloading the installers with modern styling.
- **installers-Prod/**: Directory containing production installer files.
- **Installers-Debug/**: Directory containing test/debug installer files.

## Website

The website provides a clean, modern interface with links to download different versions of the PayGov POS Installer. It features:

- **Responsive Design**: Works well on desktop and mobile devices
- **Modern Styling**: Clean, card-based layout with Google Fonts
- **Organized Tables**: Separate sections for Production and Test versions
- **Consistent Formatting**: All release notes presented in bulleted lists

### Current Versions

#### Production Versions
| Version | File | Release Notes |
| ------- | ---- | ------------- |
| v1.0.4  | [PayGovPosInstall-1.0.4.msi](installers-Prod/PayGovPosInstall-1.0.4.msi) | • Implemented retry logic for API calls to improve reliability<br>• Added automatic relogin to EMV device during payment processing |
| v1.0.3  | [PayGovPosInstall-1.0.3.msi](installers-Prod/PayGovPosInstall-1.0.3.msi) | • Make First and Last name not required |
| v1.0.2  | [PayGovPosInstall-1.0.2.msi](installers-Prod/PayGovPosInstall-1.0.2.msi) | • Updated the MerchantE SDK dll. It increases the timeout to 2 minutes when talking to the terminal |
| v1.0.1.1| [PayGovPosInstall-1.0.1.1.msi](installers-Prod/PayGovPosInstall-1.0.1.1.msi) | • Update terminal timeout to 2 minutes |
| v1.0.1  | [PayGovPosInstall-1.0.1.msi](installers-Prod/PayGovPosInstall-1.0.1.msi) | • Added feature to copy order id |
| v1.0.0  | [PayGovPosInstall-1.0.0.msi](installers-Prod/PayGovPosInstall-1.0.0.msi) | • First Version on install |

#### Test Versions
Test versions are available in the `Installers-Debug/` folder with the same version numbers and features as production, but with `-Test` suffix in the filename.

## Custom Domain

The custom domain for the GitHub Pages site is specified in the `CNAME` file: `posinstaller.paygov.us`.

## Features

- **Modern UI**: Clean, professional design with Google Fonts (Roboto)
- **Responsive Layout**: Optimized for both desktop and mobile viewing
- **Card-based Design**: Content presented in a centered container with subtle shadows
- **Consistent Formatting**: All release notes use bulleted lists for easy reading
- **Hover Effects**: Interactive table rows with smooth transitions
- **Accessible Design**: High contrast colors and readable typography

## How to Use

1. Visit the website at `posinstaller.paygov.us` or open the [index.html](index.html) file in a web browser.
2. Choose between Production or Test versions.
3. Click on the desired version link to download the installer.
4. Review the release notes to understand what's new in each version.

## Development

The website uses modern CSS with:
- CSS Grid and Flexbox for layout
- Custom styled bullet points for lists
- Media queries for responsive design
- Box shadows and border radius for modern appearance

## License

This project is licensed under the MIT License.