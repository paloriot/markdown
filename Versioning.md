# Versioning
Your API version has a large impact on your experience with our APIs. Currently, there are three versions available for consumption. You can see your account's current API version in your API settings page.

If you'd like to change your account's API version, please reach out to integration support (api-support@yourcompany.com) for the operation.

Your account's default API version can always be overridden by passing in the `API-Version` header when making an API request.

# Backwards-compatible changes
Flexport considers some changes to be non-breaking and will make those changes without updating the API version. Please follow defensive coding practices in order to ensure stability. We consider the following to be backwards-compatible changes:

- Adding an attribute, resource, or optional parameter.
- Adding a new possible value to an `enum` type attribute.
- Adding new event types. (Webhook listeners will also receive new events)
