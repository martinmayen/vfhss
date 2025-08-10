# vfhss.org Website

This repository contains the source files for the official website of vfhss.org, hosted and managed through DirectAdmin.

## Project Structure

- `public_html/`: Main directory for web content.
  - `about.html`: About page (12.56 KB).
  - `contact.html`: Contact page (15.16 KB).
  - `csoblog.html`: Blog page (22.22 KB).
  - `editblog.html`: Blog editing page (21.36 KB).
  - `index.html`: Homepage (22.84 KB).
  - `judithblog.html`: Judith's blog page (20.59 KB).
  - `ourwork.html`: Our work page (19.90 KB).
  - `post1.html`: Post 1 page (22.23 KB).
  - `post10.html`: Post 10 page (21.45 KB).
  - `post11.html`: Post 11 page (21.50 KB).
  - `post12.html`: Post 12 page (28.67 KB).
  - `cgi-bin/`: Directory for CGI scripts (permissions: rwxr-xr-x).
  - `css/`: Directory for CSS files (permissions: rwxr-xr-x).
  - `img/`: Directory for image files (permissions: rwxr-xr-x).
  - `imgtest/`: Directory for image test files (permissions: rwxr-xr-x).
  - `js/`: Directory for JavaScript files (permissions: rwxr-xr-x).
  - `lib/`: Directory for library files (permissions: rwxr-xr-x).
  - `martin/`: Directory for Martin-related files (permissions: rwxr-xr-x).
  - `scss/`: Directory for SCSS files (permissions: rwxr-xr-x).

## Permissions
- HTML files: rw-r--r-- (644).
- Directories: rwxr-xr-x (755).

## Getting Started
1. Clone the repository: `git clone <repository-url>`.
2. Navigate to the `public_html` directory.
3. Serve the files using a local web server or upload to the DirectAdmin environment at `vfhss.org:2222`.

## Official Website
Visit the live site at [vfhss.org](https://vfhss.org).

## Notes
- Ensure proper file permissions are maintained when deploying (e.g., 644 for files, 755 for directories).
- Additional configuration may be required in DirectAdmin for CGI scripts in the `cgi-bin` directory.

## Contributing
Feel free to submit issues or pull requests for improvements to the website content or structure.
