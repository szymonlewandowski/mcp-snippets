# Marketing Cloud Personalization Event API Sender Snippet

Usually, events in Marketing Cloud Personalization are triggered by the user and defined in the sitemap. But is this the only way to do this? No. You can use Salesforce Event API!

Salesforce Event API provides an endpoint for sending bulks of actions directly to your dataset, with all the details that can be added to the event, such as user ID, catalog details, etc.

## How to run MCP Event API Sender Snippet

MCP Event API Sender Snippet is a 75-line code that allows you to easily send as many events as you want to your dataset. All you need to do is download the .html file, set parameters, and hit the button!

1. Download or copy the code of the `mcp-event-api-sender-snippet.html` file.
2. Open it or paste the code into your code editor.
3. Insert your dataset parameters as `userid`, `account`, `instance`, and `dataset` variable values.
4. Add your actions to the `actions` array.
5. Hit the *Send Event* button.

### Inserting dataset parameters and actions

`userid` - set your userid value, this value will show up as the user id in the event details

`account` - set your organization account name here

`instance` - set your instance name here

`dataset` - set your dataset name here

`actions` - set your actions here as strings, split it with a comma

Check where you can get your parameters here: [How to send additional events in Marketing Cloud Personalization | szymonlewandowski.pl](https://www.szymonlewandowski.pl/blog/marketing-cloud-personalization-send-events-using-sendevent-or-api)
