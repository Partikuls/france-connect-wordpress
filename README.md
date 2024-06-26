# France Connect Client #
A simple client that provides SSO or opt-in authentication against France Connect, the French Gov OAuth2 Server implementation.

This plugin is a fork of the [OpenID Connect Generic plugin](https://github.com/daggerhart/openid-connect-generic), which allows to authenticate users against a generic OAuth2 Server implementation.

**Contributors:** [daggerhart](https://profiles.wordpress.org/daggerhart/), [tnolte](https://profiles.wordpress.org/tnolte/), [khelil](https://github.com/khelil)<br/>
**Donate link:** http://www.daggerhart.com/  
**Tags:** france connect, security, login, oauth2, openidconnect, apps, authentication, autologin, sso  
**Requires at least:** 5.0  
**Tested up to:** 6.4.3  
**Stable tag:** 3.10.0  
**Requires PHP:** 7.4  
**License:** GPLv2 or later  
**License URI:** http://www.gnu.org/licenses/gpl-2.0.html  

## Description ##

This plugin allows to authenticate users against France Connect OAuth2 API with Authorization Code Flow.

## Installation ##

1. Upload to the `/wp-content/plugins/` directory
1. Activate the plugin
1. Visit Settings > OpenID Connect and configure to meet your needs

## Frequently Asked Questions ##

## Changelog ##

### 1.0.0 ###

* Add Role Mapping in plugin settings
* Implement nonce param management
* Design connexion button
* Change request type to Authorization Code Flow
* Fork from https://github.com/daggerhart/openid-connect-generic