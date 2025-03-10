# VendorTools Template

This is a basic template that VendorTools projects can be based off of. This template uses GitHub Actions to build and deploy, and contains Java and C++ code. To use this, you'll need to enable GitHub Pages in your repository's settings and set it to deploy from Actions, since that is used to host the Vendordep JSON and Javadoc.

Comments are included in all the files that need to be modified which tell you what to change. The list of files to modify is included below. Any URLs in the format `vendor.github.io` should have `vendor` replaced with your GitHub username, and group IDs should have `com.vendor` replaced with your own domain.

- [ ] `settings.gradle`
- [ ] `build.gradle`
- [ ] `ExampleDependency.json`
- [ ] `.github/workflows/publish.yml`
