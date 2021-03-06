# Change Log

### v3.0.14(May 21, 2021)
* Upgraded boost(1.72.0)
* Excluded a few algorithms(IDEA, RC4, RC5, MD2, MDC2) from openssl.

### v3.0.13(Jun 1, 2020)
* Fixed a bug that `MessageReceived()` event hander doesn't return the latest channel when the channel was just updated.

### v3.0.12(Apr 21, 2020)
* Fixed a bug that `ChannelChanged()` event handler isn't invoked.

### v3.0.11(Mar 3, 2020)
* Added `SBDBaseChannel::SendFileMessage()` to send a file message with binary file data.

### v3.0.10(Feb 24, 2020)
* Supports `dynamic_cast` for `SBDBaseMessage` and `SBDBaseChannel` and subclasses of them.

### v3.0.9(Jan 8, 2020)
* Fixed some bugs of group channel.
* Fixed connection bug.

### v3.0.8(Dec 16, 2019)
* Fixed a bug related to file uploading.

### v3.0.7(Nov 26, 2019)
* Added `ChannelWasHidden()` event.
* Added `HideChannel()` with `allow_auto_unhide` option.
* Renamed the error code.
* Fixed minor bugs.

### v3.0.6(Nov 15, 2019)
* Fixed minor bugs.

### v3.0.5(Nov 5, 2019)
* Fixed build configuration.

### v3.0.4(Oct 21, 2019)
* Fixed the bug with last message in group channel.

### v3.0.3(Aug 29, 2019)
* Fixed typo.
* Fixed the bug which is related to the event.

### v3.0.2(Jan 31, 2019)
* Fixed minor bug.

### v3.0.1(Nov 1, 2017)
* Added methods to upload binary files when sending a file message, updating a current user, creating a channel, and updating a channel.

### v3.0.0(Oct 21, 2017)
* Initial release.
