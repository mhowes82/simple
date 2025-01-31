<!-- README template for Marketplaces and Communities, such as GitHub and GitLab. 
Complete all Required sections and Delete any Optional sections you don't need. 
DO NOT CHANGE THE LICENSE SECTION. -->

<!-- The following <picture> element displays the Veracode logo for dark mode or light mode on sites, such as GitHub and GitLab, that support these modes. If the user switches to either mode, the appropriate logo automatically displays.
If you upload this README to a site that only supports dark mode or light mode, but not both, or does not support either mode, the site displays the image defined for the <img> element (required).
If necessary, you can remove or comment-out the <source> elements that do not apply to your site. -->

<picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://docs.veracode.com/img/Veracode_Docs_Logo_Dark_Mode.svg" height="200" width="200">
    <source media="(prefers-color-scheme: light)" srcset="https://docs.veracode.com/img/Veracode_Docs_Logo_Light_Mode.svg" height="200" width="200">
    <img alt="Veracode Logo" src="https://docs.veracode.com/img/Veracode_Docs_Logo_Light_Mode.svg" height="200" width="200">
</picture>


# Name of project
<!-- Required. Replace "Name of project" with the official Veracode product name. If you don't
know the official name for your product, contact the Product Marketing team.

For example: Veracode for GitHub Actions. -->

## Overview
<!-- Required. Describe what this project is and why someone would use it. Begin with the product 
name, be brief, get to the point, and be sure to provide any important information users might need to know.

EXAMPLE: Veracode for GitHub Actions allows you to add Veracode Static Analysis and 
Pipeline Scan to your GitHub development pipeline. You can view any discovered flaws in your code on the Security tab on your GitHub repository. -->

## Before you begin

<!-- Optional. Only include if there are critical/Veracode-specific requirements that prevent
a user from installing or using this product.

EXAMPLE:
You must have [Veracode API credentials](https://docs.veracode.com/r/c_api_credentials3) to access Veracode. -->

## Installation

<!-- // Required. Procedure(s) for installing and configuring this product. If there are several
// installation and/or configuration steps, use a numbered list so that users can more easily 
// follow the sequence. If the installation involves multiple tasks/procedures, use level 3
// headings to group the tasks/procedures. To help users, particularly for something complicated, include screenshots.

For example:
### Clone this repository:

    git clone https://github.com/veracode/veracode-da-scanner-vars-example.git

### Install dependencies:

    cd veracode-da-scanner-vars-example
    pip install -r requirements.txt -->

## Usage

<!-- 
// Required. Explain how to use this product. Ideally, provide one or more commands or workflows 
// for accomplishing one or more goals. The content will vary by product, but could include
// example commands, a list of parameters (required and/or optional), or procedures. Each 
// parameter must include a description with possible values. For procedures, use numbered lists // and screenshots, as appropriate, so that users can more easily and successfully complete the
// workflow.

EXAMPLE:
If you have saved credentials as above you can add a new account-level scanner variable with:

    python veracode-da-scanner-vars.py -k PASSWORD -v 'hzZK2HgBC5@[
    
You can then list the defined variables with:

    python veracode-da-scanner-vars.py -l

Otherwise, you must set these environment variables before running `example.py`:

    export VERACODE_API_KEY_ID=<YOUR_API_KEY_ID>
    export VERACODE_API_KEY_SECRET=<YOUR_API_KEY_SECRET>
    python veracode-da-scanner-vars-example.py -l 
    -->

## Contributing
<!-- Optional. This section is TBD.-->

## License
<!-- Optional. The MIT License for official Veracode products. Only include with either official Veracode products or reusable Veracode code samples.
//The GitHub and GitLab UIs provide options for adding this MIT License.
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

EXAMPLE: -->
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
See the [LICENSE](https://github.com/veracode/.github/blob/main/LICENSE) for details

## Contact
<!-- ONLY include for official Veracode projects/products that our Veracode Community or Support personnel can actually support. DO NOT include for unofficial Veracode projects/products, such as personal projects, that Veracode cannot support.

Visit the [Veracode Community](https://community.veracode.com/). -->
