# steam-redirector

A simple static site that redirects users to whatever URL is specified after the hash.

## Usage

Navigate to `https://your-domain.com/#<target-url>` and you will be redirected to `<target-url>`.

### Examples

- `https://your-domain.com/#https://psykzz.com` → redirects to `https://psykzz.com`
- `https://your-domain.com/#steam://run/12345` → redirects to `steam://run/12345`

## Use Case

This is designed to be hosted on GitHub Pages to enable opening Steam protocol links through a redirect.