# Home Assistant Add-on: Wewe RSS

A RSS service for Home Assistant based on Wewe RSS.

## How to use

1. Install the add-on
2. Configure the options:
   - `auth_code`: Service authentication code (required)
   - `feed_mode`: Extract full text content mode (optional)
   - `cron_expression`: Cron expression for scheduled updates (optional)
   - `max_request_per_minute`: API request limit per minute (optional)
   - `server_origin_url`: Public URL when accessing from outside (optional)
3. Start the add-on
4. Access the service at http://your-home-assistant:4000

## Configuration

Example add-on configuration:

```yaml
auth_code: "123456"
feed_mode: "fulltext"
cron_expression: "35 5,17 * * *"
max_request_per_minute: 60
server_origin_url: "http://homeassistant.local:4000"
