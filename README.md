# PubNub JS SDK Demo Code

## Set up

Be sure to insert your PubNub API Keys in each of the HTML files in this repository.

```javascript
const pubnub = new PubNub({
    publishKey : 'YOUR PUBNUB PUBLISH KEY HERE',
    subscribeKey : 'YOUR PUBNUB SUBSCRIBE KEY HERE'
});
```

PubNub accounts are **free** up to 1 million transactions per month.

<a href="https://admin.pubnub.com/register">
    <img alt="PubNub Signup" src="https://i.imgur.com/og5DDjf.png" width=260 height=97/>
</a>

## Running

Open any of the HTML files in your favorite web browser. No need to run a web server. Use the [file URI scheme](https://en.wikipedia.org/wiki/File_URI_scheme) in your browser's address input to navigate to the HTML file on your computer.

## Videos of This Code in Action

Check out the [PubNub Quickstarts](https://www.pubnub.com/docs/getting-started-guides/pubnub-publish-subscribe?devrel_gh=pubnub-js-quickstart) for video commentary of this code in action.
