# UI
Assets, boilerplate code, etc. for the Blue Tang design and UI

## How to Use Me

All assets are linked in the header of every website and application:

+ CSS Files: s3.amazonaws.com/wrdsb-ui-assets/{MAJOR VERSION}/master.css
+ JS Files:  s3.amazonaws.com/wrdsb-ui-assets/{MAJOR VERSION}/master.js
+ IMG Files: s3.amazonaws.com/wrdsb-ui-assets/{MAJOR VERSION}/{image file name} (see repo for available images)

### Testing Plan

When there is a major version change, test your code against the next version to ensure your application works with it and apply any required changes to your code before switching. 

To test, in the header file for your application, change the link to {NEXT VERSION} from {MAJOR VERSION} in your test area.

The Web Team will provide details about what changes and what will potentially break in the Software Development Handbook. https://staff.wrdsb.ca/software-development/

### Reporting Issues

Please report any issues when testing to the Web Team by providing the specific error, code, screenshots, etc using the issue queue for this repo. 

## What Uses These Assets?

Currently some .NET applications and all ITS-managed WordPress websites use these assets. We are moving to have all .NET applications, reports, WRDSB Websites use these assets.