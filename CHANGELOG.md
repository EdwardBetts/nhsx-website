# Changelog

## 2.9.0 - 24/03/2020

- Break Information Governance into separate pages

## 2.8.0 - 20/03/2020

- Add further guidance for the Information Governance
- Update package dependencies to latest versions

## 2.7.0 - 16/03/2020

- New Information Governance guidance
- Update package dependencies to latest versions

## 2.6.0 - 04/03/2020

- Add new content on How we work with digital innovators
- Grammatical fixes to the tech plan for health and care page
- Update package dependencies to latest versions
- Create a new page for Information Governance guidance
- Move blog posts to the Key information and tools index page
- Change the file path of the favicons to prevent them caching

## 2.5.0 - 27/02/2020

- Add new tech plan for health and care page content
- Add the NHS digital health technology standard draft

## 2.4.0 - 19/02/2020

- Added guidance about Freedom of Interest requests
- Update package dependencies to latest versions including latest NHS.UK frontend (3.0.3)

## 2.3.0 - 28/01/2020

- Content updates across missions, who are are and Artificial Intelligence pages
- Update package dependencies to latest versions

## 2.2.0 - 13/01/2020

- Simplify the Azure Pipelines CI/CD configuration for a smoother and quicker release process
- Update package dependencies to latest versions
- Use the latest cookie logic and content pages
- Self host the cookie banner and change content to relate to the NHSX website

## 2.1.2 - 17/12/2019

- Update package dependencies to latest versions

## 2.1.1 - 11/11/2019

- Update the leadership team members
- Update content on the Digital Innovation Team
- Update package dependencies to latest versions
- Install the latest version of NHS.UK frontend with new focus styles

## 2.1.0 - 30/10/2019

- New content for Data-driven health and care technology and Artificial Intelligence
- Update package dependencies to latest versions

## 2.0.5 - 15/10/2019

- Content updates to "get involved" and "Apps and tools for patient care"
- Added a pdf report to assets, linked to from get involved

## 2.0.4 - 24/09/2019

- Use the latest version of the NHS.UK frontend library (v2.3.1)
- Update package dependencies to latest versions
- Anonymize IP addresses in Google Analytics
- Implement the latest version of the cookie consent solution
- Remove bottom margin on the hero heading

## 2.0.3 - 19/08/2019

- Add content to support new information governance survey
- Updated the leadership team content
- Update package dependencies to latest versions

## 2.0.2 - 01/07/2019

- Content updates across the website for the 1st July launch
- Use correct value for the manifest display property
- Update to NHS.UK frontend v2.2.0 and use the new favicons
- Update package dependencies to latest versions

## 2.0.1 - 17/06/2019

- Self host the cookie consent solution ([Issue 38](https://github.com/nhsx/nhsx-website/issues/38))
- Add watch task to compile assets when there are any changes ([Issue 40](https://github.com/nhsx/nhsx-website/issues/40))
- Compile CSS before running the SCSS watch task

## 2.0.0 - 17/06/2019

- Changed cookie policy page rules to only accept cookies when settings are changed and saved
- Changed cookie policy page to keep same url when settings save and confirmation banner shows
- Update package dependencies to latest versions
- Use YouTubes privacy-enhanced mode to stop YouTube setting cookies on the website

## 1.1.2 - 12/06/2019

- Import all the NHS.UK frontend library components for future development
- Update package dependencies to latest versions
- Changed title and description of eRedbook to digital red books
- Add code of conduct and contributing guidelines documentation

## 1.1.1 - 17/05/2019

- Update NHSX survey on AI in health and care link text
- Update package dependency lock file to fix outdated dependencies
- Remove innovation and genomics from the teams joining NHSX list

## 1.1.0 - 08/05/2019

- Add content for the NHSX survey on AI in health and care to the designing and building products and services page 
- Update package dependencies to latest versions

## 1.0.3 - 30/04/2019

- Amend heading structure on various pages so there is no jumping from a H1 to a H3
- Add title attribute to iframe video on the homepage
- Selectively import NHS.UK frontend component scss files to reduce the compiled CSS file size

## 1.0.2 - 15/04/2019

- Update package dependencies including latest version (2.1.0) of the NHS.UK frontend
- Add robots.txt and sitemap.xml ([Issue 14](https://github.com/nhsx/nhsx-website/issues/14))

## 1.0.1 - 05/04/2019

- Reorder the asset `preconnect` and remove unneeded `dns-prefetch` ([Issue 9](https://github.com/nhsx/nhsx-website/issues/9))
- Terms and conditions content amendments
- Update the default `BASE_URL` to include `www`
- Added simple Web App Manifest file
- Who we are content amendments

## 1.0.0 - 04/04/2019

:rocket: Release of the NHSX website (https://nhsx.nhs.uk)

## 0.0.6 - 04/04/2019

- Document the default `BASE_URL` environment variable
- Tweak spacing below the video container on Homepage
- Add OGL licence to the footer
- Populated the terms and conditions page content
- Populated the privacy policy page content
- Added Matt Hancock video to homepage

## 0.0.5 - 04/04/2019

- Fix issue with menu navigation item hover focus colour
- Add if statement to prevent errors with missing variables
- Add email address and further content amendments
- Tweak the spacing of the right hand navigation on mobile
- Tweak the spacing between page sections on the homepage
- Streamline the documentation for running the application
- Configure variables to be set with environment variables to avoid code changes
- Content amendments across the website with newly signed off content
- Content amendments to include health and social care
- Tweak the width of the hero on mobile and spacing below
- Add promo to Homepage for blogs and updates promotion
- Populate the policies and key information and tools pages with descriptions and lead text
- Set a base URL for the app for any assets that require a full path
- Update the hero header image to the final version
- Build the assets before running in development mode
- Add open graph meta data and image for social media cards
- Tidy up SCSS code by separating into files and lint the code

## 0.0.4 - 03/04/2019

- Remove unused tests and dependencies
- Fix issue with the cookie success banner link hover colour not being accessible
- Combine the key documents page with the policy, strategy and national programmes page
- Fix issue with Google analytics script not being classed as statistics type
- Populate the cookie policy with cookies we use
- Populate the accessibility statement with approved content
- Use the correct URL for the cookies policy page
- Use the approved Hero header image on the homepage
- Fix invalid HTML and add cookie declaration to the sitemap
- Create a 404 page with some basic content
- Improve the README file with a description and contributing
- Use the NHSX blue for the homepage hero background colour
- Fix the spacing and sizing of typography and components on content pages
- Embed videos within content pages, with responsive styling added
- Add missing main element to the Homepage for the skip link component
- Populate pages with approved content
- Add placeholder Homepage sections for video and get involved
- Use an improved SVG icon for the NHSX logo
- Add hero and promo components with additional NHSX styling to the homepage
- Use the correct CSS spelling color for the NHSX colour variables

## 0.0.3 - 02/04/2019

- Fix issue on Internet Explorer with the NHSX logo being auto width
- Use Google Analytics instead of Adobe Analytics due to the jQuery dependency required by Adobe
- Add placeholder content pages and page descriptions
- Populated the sitemap page with a hotfix for nested list spacing [NHS.UK frontend issue 430](https://github.com/nhsuk/nhsuk-frontend/issues/430)
- Add placeholder page title and description fields to each page
- Add placeholder policy and sitemap pages
- Apply NHSX styling to the Header and Footer components
- Use Header component with a navigation menu
- Import JavaScript modules from NHS.UK frontend package rather than local files
- Move build task dependencies to be devDependencies rather than regular
- Use Webpack to compile JavaScript bundles instead of rollup.js
- Add cookie policy page logic with placeholder cookie declaration page
- Add missing '/' to correct the paths for the CSS/JS files
- Use manual express routes and tidy up BrowserSync config
- Use NHS.UK eslint config
- Include JavaScript for the skip link to function properly
- Add NHS.UK cookie consent banner, for cookie management across NHS.UK

## 0.0.2 - 29/03/2019

- Remove production analytics tracking until go live
- Add pull request templates for contributors
- Use gzip compression to increase the speed of web app

## 0.0.1 - 29/03/2019

- Add Adobe Analytics, our chosen analytics platform, to the different environments
- Setup deployment and CI pipelines in Azure
- Use the NHS.UK frontend library and apply basic NHS.UK template
- Initial application structure and configuration
