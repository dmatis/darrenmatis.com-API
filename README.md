# darrenmatis.com Strapi Application

## Description
A headless CMS for managing the content on my [portfolio website](https://github.com/dmatis/darrenmatis.com)

## To Start

### Set Cloudinary ENV
Login to [Cloudinary account](https://cloudinary.com/console/c-94e57a5a96ccc6cb6dc0ad2c698ac4)\
Export the following ENV variables to the shell using values obtained from Cloudinary account:
| ENV name | ENV value |
| -------- | --------- |
| CLOUDINARY_NAME | Cloud name |
| CLOUDINARY_KEY | API Key |
| CLOUDINARY_SECRET| API Secret |

### Start the Strapi Server
`yarn`\
`yarn develop`\
Go to [localhost:1337/admin](localhost:1337/admin)

## Image Management
Images delivered by Strapi content (ie: Blog posts) are automatically hosted by Cloudinary using the `strapi-provider-upload-cloudinary` package. This ensures that they are correctly linked in the live site.
