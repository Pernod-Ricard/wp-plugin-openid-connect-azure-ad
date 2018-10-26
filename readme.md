## OpenID Connect Azure AD Client

License: GPL 3.0 or later
License URI: https://www.gnu.org/licenses/gpl-3.0.html

A simple client that provides SSO or opt-in authentication against Azure AD.

### Description

This plugin allows to authenticate users against Azure AD with Authorization Code Flow.
Once installed, it can be configured to automatically authenticate users (SSO), or provide a "Login with OpenID Connect"
button on the login form. After consent has been obtained, an existing user is automatically logged into WordPress, while new users are created in WordPress database.

Much of the documentation can be found on the Settings > OpenID Connect Azure AD dashboard page.

### Installation

1. Upload to the `/wp-content/plugins/` directory
1. Activate the plugin
1. Visit Settings > OpenID Connect and configure to meet your needs


### Frequently Asked Questions

**What is the client's Redirect URI?**

For Azure AD, the redirect URI can't contain query string, so the redirect URI is :'https://example.com/wp-admin/openid-connect-authorize'

Replace `example.com` with your domain name and path to WordPress.
