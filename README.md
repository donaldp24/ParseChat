## OVERVIEW

ParseChat is a full native iPhone app to create realtime, text based group or private chat with Parse.

![ParseChat](http://relatedcode.com/github/parsechat01.png)
.
![ParseChat](http://relatedcode.com/github/parsechat02.png)
.
![ParseChat](http://relatedcode.com/github/parsechat03.png)

ParseChat is using Parse as backend which is basically free. (Free plan: 20 GB File Storage, 20 GB Database Storage, 2 TB Data Transfer, 30 req/s).

Really easy to setup, just copy/paste the code and use your own chatrooms.

## WHAT'S NEW IN 2.0

- Private chat functionality is added
- Facebook profile picture is grabbed automatically
- JSQMessagesViewController is updated
- ProgressHUD is updated
- AFNetworking is added
- Parse.framework is updated
- FacebookSDK.framework is updated
- ParseFacebookUtils.framework is added (needed by Parse v1.2.21)

## FEATURES

- Live chat between multiple devices
- Group and Private chat functionality
- Multiple chatrooms
- Dynamically add new chatrooms
- Register/Login views
- Facebook login
- Facebook profile picture is grabbed automatically
- Basic Profile view is also included
- Change profile picture possibility
- No backend programming needed
- Automatic online/offline detection and handle
- Copy and paste messages
- Dynamically resizes input text while typing
- Native and easy to customize user interface
- Send button is enabled/disabled automatically
- Arbitrary message sizes
- Data detectors (recognizes phone numbers, links and dates)
- Timestamps possibilities
- Hide keyboard with swipe down
- Smooth animations
- Send/Receive sound effects

## REQUIREMENTS

- Xcode 5
- iOS 7
- ARC

## INSTALLATION

**1.,** All ParseChat files located in *Classes* directory. Vendor files located in *Vendor* directory and external Frameworks in *Framework* directory. Some resource files can be found in *Resources* directory. Simply add *Classes*, *Resources*, *Vendor* and *Framework* directories to your project.

**2.,** You need the following iOS (built in) libraries: UIKit.framework, CoreGraphics.framework, Foundation.framework, SystemConfiguration.framework, StoreKit.framework, Security.framework, QuartzCore.framework, MobileCoreServices.framework, CoreLocation.framework, CFNetwork.framework, AudioToolbox.framework, libz.dylib.

To add libraries follow these steps: Click on the Targets → Your app name → and then the 'Build Phases' tab and then expand 'Link Binary With Libraries'. Click the plus button in the bottom left of the 'Link Binary With Libraries' section and choose library items from the list.

**3.,** You also need the latest Parse.framework. (Already included, but you can download from [here](https://www.parse.com/docs/downloads)).

To add Parse.framework just unzip the downloaded file and drag the Parse.framework folder into your Xcode project under 'Frameworks'.

More info about how to [install](https://www.parse.com/apps/quickstart#parse_data/mobile/ios/native/existing) Parse SDK.

**4.,** You also need the latest FacebookSDK.framework. (Already included, but you can download from [here](https://developers.facebook.com/docs/ios)).

To add FacebookSDK.framework just drag the FacebookSDK.framework folder into your Xcode project under 'Frameworks'.

More info about how to [install](https://developers.facebook.com/docs/ios/getting-started) Facebook SDK.

**5.,** You also need several external libraries which are included. But if you need, you can download them from here:

https://github.com/AFNetworking/AFNetworking<br>
https://github.com/jessesquires/JSQMessagesViewController<br>
https://github.com/jessesquires/JSQSystemSoundPlayer<br>
https://github.com/relatedcode/ProgressHUD<br>

To use these libraries, just add AFNetworking, JSQMessagesViewController, JSQSystemSoundPlayer and ProgressHUD directories to your project.

**6.,** You need to register your app at Facebook.

https://developers.facebook.com/apps<br>

More info about how to [configure](https://developers.facebook.com/docs/ios/getting-started) Facebook.

**7.,** You need to use your own Parse account.

https://www.parse.com/#signup

**8.,** Please replace existing Parse account details in *AppDelegate.m*:

```
[Parse setApplicationId:@"ZpzAcELw53bsRGdN1ZNiDHTuPwT0QEvSQefQ8cUQ" clientKey:@"netW22vtS26ZmFaZi5rtqxYGSYdw9Xo89pdIyjkE"];
```

## CONTACT

Do you have any questions or idea? My email is: info@relatedcode.com or you can find some more info at [relatedcode.com](http://relatedcode.com)

## LICENSE

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
