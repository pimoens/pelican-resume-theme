# Pieter Moens | [Personal Resume](https://resume.pietermoens.be)

Web design using [TailwindCSS](https://tailwindcss.com/)

## Preview

Watch the [Live Preview](https://resume.pietermoens.be)

## Requirements

```
pelican[markdown]>=4.8.0
pelican-tailwindcss>=0.2.0
```

Install and configure pelican-tailwindcss according to the [documentation](https://github.com/pelican-plugins/tailwindcss)

## Usage



## Features

### About me

Personal information including name, location and contact information.

| Variables | Description                             | Required |
|-----------|-----------------------------------------|----------|
| Name      | Full name                               | Y        |
| Location  | Area of residence (e.g. Ghent, Belgium) | N        |
| Birthday  | Date of birth                           | N        |
| Email     | E-mail address                          | N        |
| Phone     | Mobile phone                            | N        |
| Content   | Elevator pitch or personal description  | N        |


### Education

Content section displaying education

| Variables   | Description                                              | Required |
|-------------|----------------------------------------------------------|----------|
| Title       | Title or degree obtained during education                | Y        |
| Institution | Institution (University, College..)                      | Y        |
| Date        | Date on which the degree was obtained (used for sorting) | Y        |
| Start       | Start date                                               | Y        |
| End         | End date                                                 | Y        |
| Content     | Summary of the obtained degree                           | N        |


### Experience

Content section displaying professional experience

| Variables   | Description                                  | Required |
|-------------|----------------------------------------------|----------|
| Title       | Title or degree obtained during education    | Y        |
| Type        | 'Vocational' or 'Miscellaneous'              | Y        |
| Institution | Institution (Company)                        | Y        |
| Date        | Date on which you started (used for sorting) | Y        |
| Start       | Start date                                   | Y        |
| End         | End date                                     | Y        |
| Description | Short description                            | N        | 
| Content     | Summary of the experience                    | N        |


### Publications

Content section used for scientific publications

| Variables | Description                    | Required |
|-----------|--------------------------------|----------|
| Title     | Title of the publication       | Y        |
| Author    | Author of the publication      | Y        |
| Year      | Year of publication            | Y        |
| Journal   | Journal, Conference etc.       | Y        |
| Publisher | Publisher                      | N        |
| DOI       | DOI or link to the publication | Y        |
| Keywords  | Keywords                       | Y        | 
| Content   | Abstract of the publication    | N        |


### Certificates

Content section used for obtained certificates

| Variables    | Description                                          | Required |
|--------------|------------------------------------------------------|----------|
| Title        | Title of the certificate                             | Y        |
| Organization | Organization from which the certificate was obtained | Y        |
| Date         | Date on which the certificate was obtained           | Y        |
| DOI          | DOI or link to the certificate                       | Y        |
| Content      | Description of the certificate                       | N        |


### Skills

Content section to display skills (e.g. languages, programming skills)

| Variables    | Description             | Required |
|--------------|-------------------------|----------|
| Title        | Title of the subsection | Y        |
| Content      | Content                 | Y        |