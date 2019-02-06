# 2.0.6
- Now user serializer returns `provider` and `userToken` (if exists).
- Now `updateUserMe` method revokes user's token and creates a new one.
- Now `updateUserMe` method returns the user object serialized.

# 2.0.5
- Add support for filtering user listing by name, provider, email address or role.

# 2.0.4
- Returns `id`, `name` and `photo` user's attributes.

# 2.0.3
- Add name and photo to user data response
- Fix issue with serializing user ids on response

# 2.0.2
- Fix regression on passport-google-plus-token dependency 

# 2.0.1
- Fix regression on passport-google-oauth dependency 

# 2.0.0
- Updated license and authorship info
- Rename npm package to `sd-ct-oauth-plugin`

# 1.8.15
- Fix issue where token was requested but not provided on local login

# 1.8.14
- Add support to per-app default redirect on email confirmation

# 1.8.13
- Fix issues on token generation

# 1.8.12
- Add support for JSON formatted responses on POST /auth/login and GET /auth/login endpoint

# 1.8.11
- Fix bug in rendering login template on auth failure

# 1.8.10
- Improve HTTP error codes on POST /auth/reset-password endpoint responses

# 1.8.9
- Add support for JSON formatted responses on POST /auth/reset-password endpoint
- Add support for JSON formatted responses on POST /auth/sign-up endpoint
- Add `disableEmailSending` configuration setting to disable email sending
- Fix issue where update to sparkpost integration lib prevented emails from being sent

# 1.8.8
- Add support for public user registration by setting `allowPublicRegistration` in the plugin config options

# 1.8.7
- Update dependencies to address security vulnerabilities
