# FedEx Tracking API & Webhooks

Use Track123 to track FedEx shipments through one unified shipment tracking API.

Track123 lets your application register FedEx tracking numbers, retrieve tracking updates, and receive delivery events through webhooks.

- FedEx carrier code: `fedex`

- [Track FedEx packages on Track123](https://www.track123.com/carriers/fedex)

- [FedEx API integration page](https://www.track123.com/carriers/fedex/api)

- [Track123 API documentation](https://docs.track123.com)

> This repository explains how to track FedEx shipments with Track123. It is not official FedEx API documentation.

## FedEx tracking API integration

When your application already knows that a shipment is handled by FedEx, set `courierCode` to `fedex` when registering the tracking number.

Use [Carrier Detection](https://docs.track123.com/reference/detection-courier) when your application does not have an approved carrier code.

Use your own tracking number in the registration request. Track123 does not provide public test tracking numbers in this repository.

## Integration guides

- [FedEx tracking webhook](webhook.md)
- [FedEx tracking statuses](tracking-status.md)
- [FedEx API errors and rate limits](errors-and-rate-limits.md)

## FedEx tracking API resources

- [Register package trackings](https://docs.track123.com/reference/register-package-trackings)
- [Get package trackings](https://docs.track123.com/reference/get-package-trackings)
- [Carrier detection](https://docs.track123.com/reference/detection-courier)

## Track FedEx packages and view FAQs

For shipment lookup, carrier contact information, and customer-facing FAQs, visit [FedEx tracking on Track123](https://www.track123.com/carriers/fedex).

## More Track123 resources

- [All supported carriers](https://www.track123.com/carriers)
- [Track123 developer documentation](https://docs.track123.com)

Carrier names and websites are used only to identify compatible carriers. Track123 is not affiliated with or endorsed by FedEx unless explicitly stated.
