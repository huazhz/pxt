# Extension Release Tests

These release tests apply to an editor that supports GitHub extensions.

## All approved extensions compile

* Open a command prompt with Git and pxt CLI installed
* Run the following command:

```
pxt testghpkgs
```

If you get throttled:

* Login with your PXT token from https://makecode.com/oauth/get-token:

```
pxt login pxt TOKEN
```

* Login with a GitHub token:

```
pxt login github TOKEN
```
