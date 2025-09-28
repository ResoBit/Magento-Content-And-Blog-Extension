# ResoBit Content & Blog Extension for Magento 2

## Overview

The ResoBit Content & Blog extension enables a full-featured blog system inside Magento 2. It allows store owners to create, manage, and display blog posts, categories, and tags, enhancing content marketing, SEO, and customer engagement.

---

## Features

- Create and manage blog posts directly from Magento admin.
- Organize posts using categories and tags.
- SEO-friendly URLs and metadata support.
- Responsive blog layouts for all devices.
- Easily integrate related products in posts.
- Extendable block and template system for customization.

---

## Installation

1. Copy the module to `app/code/ResoBit/ContentBlog`.

2. Run Magento commands to enable and install:

``` bash

php bin/magento module:enable ResoBit_ContentBlog
php bin/magento setup:upgrade
php bin/magento cache:flush

```

---

## Usage

- Access blog post creation and management in the Magento Admin panel.
- Use the frontend route `/contentblog/post/view` to display blogs.
- Customize templates and blocks as needed for your theme.

---

## Extensibility

Developers can extend the module by adding:

- Admin UI grids/forms for blog post CRUD.
- Frontend widget blocks for recent posts or categories.
- SEO metadata extensions for enhanced search engine visibility.
- Comment system integration (e.g., Disqus, Facebook).

---

## Support and Feedback

For issues, feature requests, and contributions, please use the GitHub repository issue tracker.

---

## License

Licensed under the Open Software License (OSL 3.0).

---

## Author

ResoBit - Magento 2 Extension Developer

---

Thank you for choosing ResoBit extensions to boost your Magento 2 store.
