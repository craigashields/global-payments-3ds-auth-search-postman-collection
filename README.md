<div align="center">

  <h1>Global Payments 3DS Authentication Reporting Postman Collection</h1>
  
  <p>
    The Global Payments 3D Secure 2 solution provides complete flexibility for reporting transaction authentications. The search request returns a summary object allowing you to see a high-level outcome of the authentication. You can then follow the standard Obtain Authentication Data step to get more detail, including the data required for authorization.

  </p>

<!-- Badges -->
<p>
<a href="https://github.com/craigashields/global-payments-3ds-auth-search-postman-collection/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/craigashields/global-payments-3ds-auth-search-postman-collection" alt="contributors" />
</a>
<a href="">
    <img src="https://img.shields.io/github/last-commit/craigashields/global-payments-3ds-auth-search-postman-collection" alt="last update" />
</a>
<a href="https://github.com/craigashields/global-payments-3ds-auth-search-postman-collection/network/members">
    <img src="https://img.shields.io/github/forks/craigashields/global-payments-3ds-auth-search-postman-collection" alt="forks" />
</a>
<a href="https://github.com/craigashields/global-payments-3ds-auth-search-postman-collection/stargazers">
    <img src="https://img.shields.io/github/stars/craigashields/global-payments-3ds-auth-search-postman-collection" alt="stars" />
</a>
<a href="https://github.com/craigashields/global-payments-3ds-auth-search-postman-collection/issues/">
    <img src="https://img.shields.io/github/issues/craigashields/global-payments-3ds-auth-search-postman-collection" alt="open issues" />
</a>
</p>  
<h4>
    <a href="https://github.com/craigashields/global-payments-3ds-auth-search-postman-collection/issues/">Report Bug</a>
  </h4>
</div>

# Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)

## Description

I needed to use these Global Payments APIs for some work I was doing so thought I'd put this up as a quick example of calling the APIs and generating the secure hashes using Postman.

Further information can be found on the Global Payments docs site

- [Generate Hash](https://developer.globalpay.com/api/3d-secure-two#generate-hash)
- [Authentication Reporting](https://developer.globalpay.com/ecommerce/3d-secure-version2/authentication-reporting)

The repo provides a Postman Collection and environment that can be imported into Postman.

## Installation

To download and set up the collection, follow these steps:

1. Select Code -> Download Zip

2. Unzip the folder and you will see 2 `json` files

   - `Global-Payments-Authentication-Reporting.postman_collection.json`

     This file contains the API collection and documentation

   - `Global-Payments-Authentication-Reporting.postman_environment.json`

     This file contains the environment variables

3. Import into Postman

   To import into Postman, select the `import` button in the top left. A dialog will open where
   you can drag and drop the files.

   Once the files have been imported, you will be able to find the environment config in the Environments section
   and the API collection in the Collections section.

## Usage

1. Start by setting the environment variables and making the environment active.
2. Open the collection and run the APIs. The documentation for the APIs can be found against the corresponding sub folder.
