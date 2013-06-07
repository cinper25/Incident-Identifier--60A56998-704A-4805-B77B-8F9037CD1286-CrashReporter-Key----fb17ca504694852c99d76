Incident-Identifier--60A56998-704A-4805-B77B-8F9037CD1286-CrashReporter-Key----fb17ca504694852c99d76
====================================================================================================
Incident Identifier: 60A56998-704A-4805-B77B-8F9037CD1286
CrashReporter Key:   fb17ca504694852c99d76185bde1e32944cf9797
Hardware Model:      iPad2,4
Process:         iArchive-Lite [408]
Path:            /var/mobile/Applications/D74D6EC5-785D-4DCF-959D-ECB54A9E9C9C/iArchive-Lite.app/iArchive-Lite
Identifier:      iArchive-Lite
Version:         ??? (???)
Code Type:       ARM (Native)
Parent Process:  launchd [1]

Date/Time:       2013-06-06 23:45:36.592 -0500
OS Version:      iOS 6.1.3 (10B329)
Report Version:  104

Exception Type:  00000020
Exception Codes: 0x000000008badf00d
Highlighted Thread:  0

Application Specific Information:
iArchive-Lite[408] has active assertions beyond permitted time: 
{(
    <BKProcessAssertion: 0x1dd52880> identifier: UIKitBackgroundCompletionTask process: iArchive-Lite[408] permittedBackgroundDuration: 600.000000 reason: finishTask owner pid:408 preventSuspend  preventIdleSleep 
)}

Elapsed total CPU time (seconds): 235.590 (user 235.590, system 0.000), 20% CPU 
Elapsed application CPU time (seconds): 1.345, 0% CPU

Thread 0 name:  Dispatch queue: com.apple.main-thread
Thread 0:
0   libsystem_kernel.dylib        	0x39d59eb4 0x39d59000 + 3764
1   libsystem_kernel.dylib        	0x39d5a048 0x39d59000 + 4168
2   CoreFoundation                	0x319dd040 0x31946000 + 618560
3   CoreFoundation                	0x319dbd5a 0x31946000 + 613722
4   CoreFoundation                	0x3194eeb8 0x31946000 + 36536
5   CoreFoundation                	0x3194ed44 0x31946000 + 36164
6   GraphicsServices              	0x355052e6 0x35500000 + 21222
7   UIKit                         	0x338642fc 0x3380d000 + 357116
8   iArchive-Lite                 	0x0002af42 0x25000 + 24386
9   iArchive-Lite                 	0x00027754 0x25000 + 10068

Thread 1 name:  Dispatch queue: com.apple.libdispatch-manager
Thread 1:
0   libsystem_kernel.dylib        	0x39d5a648 0x39d59000 + 5704
1   libdispatch.dylib             	0x39c8a974 0x39c82000 + 35188
2   libdispatch.dylib             	0x39c8a654 0x39c82000 + 34388

Thread 2 name:  WebThread
Thread 2:
0   libsystem_kernel.dylib        	0x39d59eb4 0x39d59000 + 3764
1   libsystem_kernel.dylib        	0x39d5a048 0x39d59000 + 4168
2   CoreFoundation                	0x319dd040 0x31946000 + 618560
3   CoreFoundation                	0x319dbd9e 0x31946000 + 613790
4   CoreFoundation                	0x3194eeb8 0x31946000 + 36536
5   CoreFoundation                	0x3194ed44 0x31946000 + 36164
6   WebCore                       	0x3791f500 0x37915000 + 42240
7   libsystem_c.dylib             	0x39cc330e 0x39cb2000 + 70414
8   libsystem_c.dylib             	0x39cc31d4 0x39cb2000 + 70100

Thread 3 name:  com.apple.coremedia.player.async
Thread 3:
0   libsystem_kernel.dylib        	0x39d6a08c 0x39d59000 + 69772
1   libsystem_c.dylib             	0x39cbbd2a 0x39cb2000 + 40234
2   libsystem_c.dylib             	0x39cc5f14 0x39cb2000 + 81684
3   CoreMedia                     	0x31f348ac 0x31f31000 + 14508
4   MediaToolbox                  	0x32a26e56 0x32a23000 + 15958
5   CoreMedia                     	0x31f52890 0x31f31000 + 137360
6   libsystem_c.dylib             	0x39cc330e 0x39cb2000 + 70414
7   libsystem_c.dylib             	0x39cc31d4 0x39cb2000 + 70100

Thread 4 name:  com.apple.NSURLConnectionLoader
Thread 4:
0   libsystem_kernel.dylib        	0x39d59eb4 0x39d59000 + 3764
1   libsystem_kernel.dylib        	0x39d5a048 0x39d59000 + 4168
2   CoreFoundation                	0x319dd040 0x31946000 + 618560
3   CoreFoundation                	0x319dbd9e 0x31946000 + 613790
4   CoreFoundation                	0x3194eeb8 0x31946000 + 36536
5   CoreFoundation                	0x3194ed44 0x31946000 + 36164
6   Foundation                    	0x3229b3d0 0x3226e000 + 185296
7   Foundation                    	0x3231ee80 0x3226e000 + 724608
8   libsystem_c.dylib             	0x39cc330e 0x39cb2000 + 70414
9   libsystem_c.dylib             	0x39cc31d4 0x39cb2000 + 70100

Thread 5 name:  JavaScriptCore::BlockFree
Thread 5:
0   libsystem_kernel.dylib        	0x39d6a08c 0x39d59000 + 69772
1   libsystem_c.dylib             	0x39cbbd2a 0x39cb2000 + 40234
2   libsystem_c.dylib             	0x39cbbaa0 0x39cb2000 + 39584
3   JavaScriptCore                	0x358fbc70 0x358a0000 + 375920
4   JavaScriptCore                	0x35a0d552 0x358a0000 + 1496402
5   JavaScriptCore                	0x35a1ffa8 0x358a0000 + 1572776
6   libsystem_c.dylib             	0x39cc330e 0x39cb2000 + 70414
7   libsystem_c.dylib             	0x39cc31d4 0x39cb2000 + 70100

Thread 6 name:  JavaScriptCore::Marking
Thread 6:
0   libsystem_kernel.dylib        	0x39d6a08c 0x39d59000 + 69772
1   libsystem_c.dylib             	0x39cbbd2a 0x39cb2000 + 40234
2   libsystem_c.dylib             	0x39cc5f14 0x39cb2000 + 81684
3   JavaScriptCore                	0x359a0f3c 0x358a0000 + 1052476
4   JavaScriptCore                	0x359a0e7c 0x358a0000 + 1052284
5   JavaScriptCore                	0x35a1ffa8 0x358a0000 + 1572776
6   libsystem_c.dylib             	0x39cc330e 0x39cb2000 + 70414
7   libsystem_c.dylib             	0x39cc31d4 0x39cb2000 + 70100

Thread 7 name:  WebCore: CFNetwork Loader
Thread 7:
0   libsystem_kernel.dylib        	0x39d59eb4 0x39d59000 + 3764
1   libsystem_kernel.dylib        	0x39d5a048 0x39d59000 + 4168
2   CoreFoundation                	0x319dd040 0x31946000 + 618560
3   CoreFoundation                	0x319dbd9e 0x31946000 + 613790
4   CoreFoundation                	0x3194eeb8 0x31946000 + 36536
5   CoreFoundation                	0x3194ed44 0x31946000 + 36164
6   WebCore                       	0x379b9d02 0x37915000 + 675074
7   JavaScriptCore                	0x35a1ffa8 0x358a0000 + 1572776
8   libsystem_c.dylib             	0x39cc330e 0x39cb2000 + 70414
9   libsystem_c.dylib             	0x39cc31d4 0x39cb2000 + 70100

Thread 8:
0   libsystem_kernel.dylib        	0x39d6ad98 0x39d59000 + 73112
1   libsystem_c.dylib             	0x39cb8cf6 0x39cb2000 + 27894
2   libsystem_c.dylib             	0x39cb8a12 0x39cb2000 + 27154
3   libsystem_c.dylib             	0x39cb88a0 0x39cb2000 + 26784

Thread 9:
0   libsystem_kernel.dylib        	0x39d6ad98 0x39d59000 + 73112
1   libsystem_c.dylib             	0x39cb8cf6 0x39cb2000 + 27894
2   libsystem_c.dylib             	0x39cb8a12 0x39cb2000 + 27154
3   libsystem_c.dylib             	0x39cb88a0 0x39cb2000 + 26784

Unknown thread crashed with unknown flavor: 5, state_count: 1

Binary Images:
   0x25000 -   0x4e6fff +iArchive-Lite armv7  <a8534427ee96309eaf4a1a78bd234d76> /var/mobile/Applications/D74D6EC5-785D-4DCF-959D-ECB54A9E9C9C/iArchive-Lite.app/iArchive-Lite
0x2fee3000 - 0x2ff03fff  dyld armv7  <280610df5ed43ec7aa00629a27009302> /usr/lib/dyld
0x3093c000 - 0x30a0dfff  RawCamera armv7  <8752cce31e8e3ceab5d88c84e3481db2> /System/Library/CoreServices/RawCamera.bundle/RawCamera
0x30a16000 - 0x30b1ffff  IMGSGX543GLDriver armv7  <a31ea5c288c6353f9d6c75cf37c10fae> /System/Library/Extensions/IMGSGX543GLDriver.bundle/IMGSGX543GLDriver
0x30b29000 - 0x30c0ffff  AVFoundation armv7  <320761e836883aeabf3cb5c53edb636d> /System/Library/Frameworks/AVFoundation.framework/AVFoundation
0x30c10000 - 0x30c10fff  Accelerate armv7  <b68ff92e404931f3bcb6361720f77724> /System/Library/Frameworks/Accelerate.framework/Accelerate
0x30c11000 - 0x30d4ffff  vImage armv7  <30522b92940d3dd184c8e46780594048> /System/Library/Frameworks/Accelerate.framework/Frameworks/vImage.framework/vImage
0x30d50000 - 0x30e33fff  libBLAS.dylib armv7  <d8edada1cea133458ca779e34a3a7f88> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libBLAS.dylib
0x30e34000 - 0x310e9fff  libLAPACK.dylib armv7  <9e08aead79d13043bab622402a270fba> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libLAPACK.dylib
0x310ea000 - 0x31143fff  libvDSP.dylib armv7  <09e2a5e3e9203950890ba57592523132> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libvDSP.dylib
0x31144000 - 0x31155fff  libvMisc.dylib armv7  <7b7d4ccc9f2b364cb0da4251e745545d> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libvMisc.dylib
0x31156000 - 0x31156fff  vecLib armv7  <a7751c047dcc35ba8885212e1938b93f> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/vecLib
0x31157000 - 0x31168fff  Accounts armv7  <ea2de358b6cc3baab27d6ab809c31e39> /System/Library/Frameworks/Accounts.framework/Accounts
0x3116a000 - 0x311cefff  AddressBook armv7  <8cfae84dc66d3c1f9d17335c53c3d7b7> /System/Library/Frameworks/AddressBook.framework/AddressBook
0x311cf000 - 0x31289fff  AddressBookUI armv7  <0017d0a0c2593522acaaa0eee41775e4> /System/Library/Frameworks/AddressBookUI.framework/AddressBookUI
0x3128a000 - 0x31298fff  AssetsLibrary armv7  <9a3a4a47a77833eb82a28757a3488660> /System/Library/Frameworks/AssetsLibrary.framework/AssetsLibrary
0x313d4000 - 0x3165cfff  AudioToolbox armv7  <394ee11cf826367db9ff4968dbc71d6d> /System/Library/Frameworks/AudioToolbox.framework/AudioToolbox
0x3165d000 - 0x31722fff  CFNetwork armv7  <4771a5e4f9b83bceb252f0f3d166aaca> /System/Library/Frameworks/CFNetwork.framework/CFNetwork
0x31723000 - 0x31779fff  CoreAudio armv7  <5d534dbf76ff30f4a628f25f56c5f26a> /System/Library/Frameworks/CoreAudio.framework/CoreAudio
0x3178d000 - 0x31945fff  CoreData armv7  <3930f672c76535a2abb768ee59958fa7> /System/Library/Frameworks/CoreData.framework/CoreData
0x31946000 - 0x31a78fff  CoreFoundation armv7  <fcb8d4e838543bcb9a52c9f232b8b4eb> /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
0x31a79000 - 0x31bb1fff  CoreGraphics armv7  <81e213f810a034d4ba411f9b505da2a6> /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics
0x31bb3000 - 0x31beefff  libCGFreetype.A.dylib armv7  <a5d20b80ab1532d8831027a66d2d9eb5> /System/Library/Frameworks/CoreGraphics.framework/Resources/libCGFreetype.A.dylib
0x31dd2000 - 0x31dedfff  libRIP.A.dylib armv7  <ec1487f9bdb93597a3f8d434406ad9bf> /System/Library/Frameworks/CoreGraphics.framework/Resources/libRIP.A.dylib
0x31dee000 - 0x31ea3fff  CoreImage armv7  <6ae4ae2461313e3f84c6a8102d5b1b0e> /System/Library/Frameworks/CoreImage.framework/CoreImage
0x31ea4000 - 0x31efcfff  CoreLocation armv7  <4edb4b0f05e13af8b84699fe3ea4c538> /System/Library/Frameworks/CoreLocation.framework/CoreLocation
0x31f31000 - 0x31f96fff  CoreMedia armv7  <8592bdc268b83b8886acfc1fdab649ed> /System/Library/Frameworks/CoreMedia.framework/CoreMedia
0x31f97000 - 0x3201ffff  CoreMotion armv7  <4512d901170d32e7842e7fc1c519386b> /System/Library/Frameworks/CoreMotion.framework/CoreMotion
0x32020000 - 0x32076fff  CoreTelephony armv7  <bea09dbe25363c3b8e8016b5b5148055> /System/Library/Frameworks/CoreTelephony.framework/CoreTelephony
0x32077000 - 0x320d9fff  CoreText armv7  <e135debbc8f937299f4986fc3e9459e3> /System/Library/Frameworks/CoreText.framework/CoreText
0x320da000 - 0x320e9fff  CoreVideo armv7  <00f18bb26e663da9ae251a6ec36a19ec> /System/Library/Frameworks/CoreVideo.framework/CoreVideo
0x320ea000 - 0x3219efff  EventKit armv7  <99a7a1603323319f9e24f97e9f89bfd3> /System/Library/Frameworks/EventKit.framework/EventKit
0x3226e000 - 0x32431fff  Foundation armv7  <0179934581d13346aa7583165108b95c> /System/Library/Frameworks/Foundation.framework/Foundation
0x325ec000 - 0x32635fff  IOKit armv7  <a98ba9fefc7333e4a5a9169198848c62> /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit
0x32636000 - 0x3280efff  ImageIO armv7  <b5ce84bb074d3de4b07b55da9fd8bfd1> /System/Library/Frameworks/ImageIO.framework/ImageIO
0x32888000 - 0x32a22fff  MediaPlayer armv7  <ce97a30e514d3a17ae93ba4a9d1d69d2> /System/Library/Frameworks/MediaPlayer.framework/MediaPlayer
0x32a23000 - 0x32c9dfff  MediaToolbox armv7  <ed439fc5c9a03f8b9fae43af33de8a57> /System/Library/Frameworks/MediaToolbox.framework/MediaToolbox
0x32c9e000 - 0x32d24fff  MessageUI armv7  <8dbc0a8e6a253c8c8d6301064f23dfea> /System/Library/Frameworks/MessageUI.framework/MessageUI
0x32d25000 - 0x32d7efff  MobileCoreServices armv7  <77da8a9e7f813f5baf37eaa4a87fae84> /System/Library/Frameworks/MobileCoreServices.framework/MobileCoreServices
0x32dab000 - 0x32e6cfff  GLEngine armv7  <b3fd8a93778b317fab8630340a2d741b> /System/Library/Frameworks/OpenGLES.framework/GLEngine.bundle/GLEngine
0x32e6d000 - 0x32e74fff  OpenGLES armv7  <f2ede6b206f336de82cc38619692e762> /System/Library/Frameworks/OpenGLES.framework/OpenGLES
0x32e76000 - 0x32e76fff  libCVMSPluginSupport.dylib armv7  <2506af1c983f3f09ac69aca44f67e863> /System/Library/Frameworks/OpenGLES.framework/libCVMSPluginSupport.dylib
0x32e77000 - 0x32e79fff  libCoreFSCache.dylib armv7  <761c0f0e263c3d39adbb5bf789cedde1> /System/Library/Frameworks/OpenGLES.framework/libCoreFSCache.dylib
0x32e7a000 - 0x32e7cfff  libCoreVMClient.dylib armv7  <af6ff28dce6031baaa850ccc79e5699b> /System/Library/Frameworks/OpenGLES.framework/libCoreVMClient.dylib
0x32e7d000 - 0x32e81fff  libGFXShared.dylib armv7  <a6ac1673a088379aa512ba5cac301f5b> /System/Library/Frameworks/OpenGLES.framework/libGFXShared.dylib
0x32e82000 - 0x32ebffff  libGLImage.dylib armv7  <b8b8f3a1bfd0345e86aa0c2952534949> /System/Library/Frameworks/OpenGLES.framework/libGLImage.dylib
0x32ec0000 - 0x32fe5fff  libGLProgrammability.dylib armv7  <0b3cb1b9a5003c4a975ec268cabca3fc> /System/Library/Frameworks/OpenGLES.framework/libGLProgrammability.dylib
0x335ba000 - 0x336cffff  QuartzCore armv7  <c086b6e6cd9d341399bcc3675c82f1fe> /System/Library/Frameworks/QuartzCore.framework/QuartzCore
0x336d0000 - 0x3371dfff  QuickLook armv7  <954e3a8bdaf337b085b30fd514ea5f3a> /System/Library/Frameworks/QuickLook.framework/QuickLook
0x3371e000 - 0x3374cfff  Security armv7  <fbc24f15bd9e37539cdd6e3576bde938> /System/Library/Frameworks/Security.framework/Security
0x337bb000 - 0x337cafff  StoreKit armv7  <e63a14831d2d315ba5cf654102d67f8c> /System/Library/Frameworks/StoreKit.framework/StoreKit
0x337cb000 - 0x3380afff  SystemConfiguration armv7  <410d69b356e533d6a1d538cf33059634> /System/Library/Frameworks/SystemConfiguration.framework/SystemConfiguration
0x3380d000 - 0x33d61fff  UIKit armv7  <ad8b3ad23f413187a178179db39cfa6b> /System/Library/Frameworks/UIKit.framework/UIKit
0x33d62000 - 0x33da0fff  VideoToolbox armv7  <d2e8067306d9346ab4a448f10f336894> /System/Library/Frameworks/VideoToolbox.framework/VideoToolbox
0x33da1000 - 0x33db7fff  iAd armv7  <e64ed3a1472d368e878a38e46803c73e> /System/Library/Frameworks/iAd.framework/iAd
0x33fd0000 - 0x33fd5fff  AITTarget armv7  <a06d2cb1f2c434fb8fcb57871a3075d2> /System/Library/PrivateFrameworks/AITTarget.framework/AITTarget
0x34029000 - 0x34035fff  AccountSettings armv7  <8db45acc4d3d3017af10fa5ee82c2306> /System/Library/PrivateFrameworks/AccountSettings.framework/AccountSettings
0x3407c000 - 0x3407ffff  ActorKit armv7  <5dfc59258ea63006be9c542e5fafbc45> /System/Library/PrivateFrameworks/ActorKit.framework/ActorKit
0x34081000 - 0x34084fff  AggregateDictionary armv7  <c2a6c1ff89a9318d8b74fc5dfc8847b8> /System/Library/PrivateFrameworks/AggregateDictionary.framework/AggregateDictionary
0x3416d000 - 0x34180fff  AirTraffic armv7  <752b64045f4d3ea88a946b53b731ce1a> /System/Library/PrivateFrameworks/AirTraffic.framework/AirTraffic
0x344b0000 - 0x344ebfff  AppSupport armv7  <921794b7d82a3558a0eb860979be199c> /System/Library/PrivateFrameworks/AppSupport.framework/AppSupport
0x344ec000 - 0x34510fff  AppleAccount armv7  <c54536fbc0f235f693060be33d4d4749> /System/Library/PrivateFrameworks/AppleAccount.framework/AppleAccount
0x3451d000 - 0x3452afff  ApplePushService armv7  <8bad4a9300db3d4d8555535f25c32da4> /System/Library/PrivateFrameworks/ApplePushService.framework/ApplePushService
0x3455e000 - 0x34567fff  AssetsLibraryServices armv7  <de7ca29cd47433cd8eca9c04102f5508> /System/Library/PrivateFrameworks/AssetsLibraryServices.framework/AssetsLibraryServices
0x34582000 - 0x34599fff  BackBoardServices armv7  <772912697ec23e5199a452e97f075dd9> /System/Library/PrivateFrameworks/BackBoardServices.framework/BackBoardServices
0x345a3000 - 0x345c7fff  Bom armv7  <b5315d733e123a0781683efdc734064b> /System/Library/PrivateFrameworks/Bom.framework/Bom
0x345da000 - 0x34609fff  BulletinBoard armv7  <9f46015c5d263064901f7725f4bb93e0> /System/Library/PrivateFrameworks/BulletinBoard.framework/BulletinBoard
0x34647000 - 0x3464efff  CaptiveNetwork armv7  <a4f4b86cc84839f78ff746f013bcee6f> /System/Library/PrivateFrameworks/CaptiveNetwork.framework/CaptiveNetwork
0x3464f000 - 0x34719fff  Celestial armv7  <a688df527b65382da586ebc87f28c061> /System/Library/PrivateFrameworks/Celestial.framework/Celestial
0x34726000 - 0x3472afff  CertUI armv7  <ce979f715cdb3cb5a0f7935f14cc0b35> /System/Library/PrivateFrameworks/CertUI.framework/CertUI
0x347d0000 - 0x347e9fff  ChunkingLibrary armv7  <ec2f76b3ac723a39bbf3f122d7fe73cf> /System/Library/PrivateFrameworks/ChunkingLibrary.framework/ChunkingLibrary
0x347fd000 - 0x34802fff  CommonUtilities armv7  <f8fea9ee6ca236b0a7fa6c00eb8a0d24> /System/Library/PrivateFrameworks/CommonUtilities.framework/CommonUtilities
0x34887000 - 0x348b7fff  ContentIndex armv7  <00ed488e47ee34ca9f01f2cc911f453c> /System/Library/PrivateFrameworks/ContentIndex.framework/ContentIndex
0x34933000 - 0x34a1bfff  CoreMediaStream armv7  <828bf27fe7a3337cbff7dd8837508819> /System/Library/PrivateFrameworks/CoreMediaStream.framework/CoreMediaStream
0x34aaa000 - 0x34ac7fff  CoreServicesInternal armv7  <09bda41ea1d935148d18c07a7102ede5> /System/Library/PrivateFrameworks/CoreServicesInternal.framework/CoreServicesInternal
0x34ac8000 - 0x34ac9fff  CoreSurface armv7  <6065f7e040e93d6ea2837e929592cc30> /System/Library/PrivateFrameworks/CoreSurface.framework/CoreSurface
0x34b31000 - 0x34b35fff  CoreTime armv7  <5f0b123555f03d8aa76cc54314907942> /System/Library/PrivateFrameworks/CoreTime.framework/CoreTime
0x34b36000 - 0x34b3bfff  CrashReporterSupport armv7  <03ee46e3ca3f3920a7174e62096723fb> /System/Library/PrivateFrameworks/CrashReporterSupport.framework/CrashReporterSupport
0x34b3c000 - 0x34b78fff  DataAccess armv7  <d7185042adf63908ae87fe4a5c3f8a6c> /System/Library/PrivateFrameworks/DataAccess.framework/DataAccess
0x34d0d000 - 0x34d1ffff  DataAccessExpress armv7  <b9423867a9ef303b87d2e1eac1712957> /System/Library/PrivateFrameworks/DataAccessExpress.framework/DataAccessExpress
0x34d33000 - 0x34d48fff  DataDetectorsCore armv7  <58352df07a0139de878e5e275e27ab52> /System/Library/PrivateFrameworks/DataDetectorsCore.framework/DataDetectorsCore
0x34d4a000 - 0x34d5dfff  DataDetectorsUI armv7  <331c11e50793340f9ce758435c9420ac> /System/Library/PrivateFrameworks/DataDetectorsUI.framework/DataDetectorsUI
0x34d5e000 - 0x34d5ffff  DataMigration armv7  <5903e08348b83f119022cbbf83ad100a> /System/Library/PrivateFrameworks/DataMigration.framework/DataMigration
0x34d62000 - 0x34d7bfff  DictionaryServices armv7  <84669055e3e63d6ab56b8fe7b0476aaa> /System/Library/PrivateFrameworks/DictionaryServices.framework/DictionaryServices
0x34d83000 - 0x34d9bfff  EAP8021X armv7  <6d5ab53850e23fe389e64e2705bd7810> /System/Library/PrivateFrameworks/EAP8021X.framework/EAP8021X
0x34dab000 - 0x34daffff  FTClientServices armv7  <6354e5b30919340db3b976312b284fce> /System/Library/PrivateFrameworks/FTClientServices.framework/FTClientServices
0x34db0000 - 0x34dedfff  FTServices armv7  <89c066d12a6031038a9b8c61221abc0a> /System/Library/PrivateFrameworks/FTServices.framework/FTServices
0x34dee000 - 0x35201fff  FaceCoreLight armv7  <43de0b31da3b39e4acf85ec2c8d5c65c> /System/Library/PrivateFrameworks/FaceCoreLight.framework/FaceCoreLight
0x3524e000 - 0x35253fff  libGPUSupportMercury.dylib armv7  <4366fa0d1a0938a794bd8346e286d6f8> /System/Library/PrivateFrameworks/GPUSupport.framework/libGPUSupportMercury.dylib
0x353f9000 - 0x35405fff  GenerationalStorage armv7  <d77ad2367fff37d485480aa39df7d325> /System/Library/PrivateFrameworks/GenerationalStorage.framework/GenerationalStorage
0x35406000 - 0x354fffff  GeoServices armv7  <edbf37a31a6a31f49e392ed8ece200c7> /System/Library/PrivateFrameworks/GeoServices.framework/GeoServices
0x35500000 - 0x3550bfff  GraphicsServices armv7  <d4b7fd6509753bff9525fef374ddc359> /System/Library/PrivateFrameworks/GraphicsServices.framework/GraphicsServices
0x3557a000 - 0x355f5fff  HomeSharing armv7  <280b77b71df23f1cb5c9a2b76fc53212> /System/Library/PrivateFrameworks/HomeSharing.framework/HomeSharing
0x355f6000 - 0x35600fff  IAP armv7  <a9554a91bbb9308f96fcd9fddf596275> /System/Library/PrivateFrameworks/IAP.framework/IAP
0x356b8000 - 0x35730fff  IMCore armv7  <d5f1d98ec53d3acbb51b116e93923d9c> /System/Library/PrivateFrameworks/IMCore.framework/IMCore
0x357f7000 - 0x35843fff  IMFoundation armv7  <797535fc363c3f818bcd1424251393bf> /System/Library/PrivateFrameworks/IMFoundation.framework/IMFoundation
0x3584a000 - 0x3584bfff  IOAccelerator armv7  <9655464326203d258d3d0fc7e94651e2> /System/Library/PrivateFrameworks/IOAccelerator.framework/IOAccelerator
0x3584c000 - 0x35851fff  IOMobileFramebuffer armv7  <f38c374982a931d5a47458dd3c34ac59> /System/Library/PrivateFrameworks/IOMobileFramebuffer.framework/IOMobileFramebuffer
0x35852000 - 0x35856fff  IOSurface armv7  <a55bf03c35de3fd9b56dce82083c3d10> /System/Library/PrivateFrameworks/IOSurface.framework/IOSurface
0x358a0000 - 0x35a46fff  JavaScriptCore armv7  <a5780997f4b738659172f40877c9a7d9> /System/Library/PrivateFrameworks/JavaScriptCore.framework/JavaScriptCore
0x35a6c000 - 0x35a76fff  Librarian armv7  <2f90575c8cf839da9db74d2eb3a1ccc1> /System/Library/PrivateFrameworks/Librarian.framework/Librarian
0x35a77000 - 0x35aadfff  MIME armv7  <57a1db0d5d3237708f54b3bd83553bae> /System/Library/PrivateFrameworks/MIME.framework/MIME
0x35aae000 - 0x35ae4fff  MMCS armv7  <7f329f193ef138c2b372e8b16e855bce> /System/Library/PrivateFrameworks/MMCS.framework/MMCS
0x35aec000 - 0x35af6fff  MailServices armv7  <a688a9972cb43169a19d2f2f57121a1e> /System/Library/PrivateFrameworks/MailServices.framework/MailServices
0x35b12000 - 0x35b6afff  ManagedConfiguration armv7  <44bbb2ba85c8320bb9e73c654b90f8c0> /System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration
0x35b6b000 - 0x35b70fff  Marco armv7  <da45fc9b228b3d1fad95e03071441585> /System/Library/PrivateFrameworks/Marco.framework/Marco
0x35b81000 - 0x35bf7fff  MediaControlSender armv7  <9fb205b64b5333a495ac61c149e0304b> /System/Library/PrivateFrameworks/MediaControlSender.framework/MediaControlSender
0x35bf8000 - 0x35c01fff  MediaRemote armv7  <73da55e989e73cb9ad6e9fdd4604ecc3> /System/Library/PrivateFrameworks/MediaRemote.framework/MediaRemote
0x35c02000 - 0x35c16fff  MediaStream armv7  <86443ae270083a829e1797d24cd0d17c> /System/Library/PrivateFrameworks/MediaStream.framework/MediaStream
0x35c74000 - 0x35d2dfff  Message armv7  <f6684c79e78f371fa81c6ec7336a0701> /System/Library/PrivateFrameworks/Message.framework/Message
0x35d36000 - 0x35d38fff  MessageSupport armv7  <81eb34b663513745b0ed65e244c7ab0f> /System/Library/PrivateFrameworks/MessageSupport.framework/MessageSupport
0x35d41000 - 0x35d6efff  MobileAsset armv7  <3a9e6258ae1230f5b12f1638b09cb974> /System/Library/PrivateFrameworks/MobileAsset.framework/MobileAsset
0x35d9b000 - 0x35daafff  MobileDeviceLink armv7  <817380030c613284a12074d960087522> /System/Library/PrivateFrameworks/MobileDeviceLink.framework/MobileDeviceLink
0x35db3000 - 0x35db6fff  MobileInstallation armv7  <c63e4b1ae40635cd9c6a7de851c80d10> /System/Library/PrivateFrameworks/MobileInstallation.framework/MobileInstallation
0x35db7000 - 0x35dbdfff  MobileKeyBag armv7  <35882c57076334aeb0641969a9b69ff3> /System/Library/PrivateFrameworks/MobileKeyBag.framework/MobileKeyBag
0x35df6000 - 0x35e19fff  MobileSync armv7  <1edd78024ae13e9997972ee905bc944e> /System/Library/PrivateFrameworks/MobileSync.framework/MobileSync
0x35e1a000 - 0x35e1dfff  MobileSystemServices armv7  <10b4eee2739c353183ac2cfe4e39a443> /System/Library/PrivateFrameworks/MobileSystemServices.framework/MobileSystemServices
0x35e35000 - 0x35e3efff  MobileWiFi armv7  <bb4efbe3c7273c0fb534f12789756089> /System/Library/PrivateFrameworks/MobileWiFi.framework/MobileWiFi
0x35e58000 - 0x35f9cfff  MusicLibrary armv7  <3870f4cb0c8b36778ad1a3f7556547f7> /System/Library/PrivateFrameworks/MusicLibrary.framework/MusicLibrary
0x35fb4000 - 0x35fcdfff  Notes armv7  <3d4a8d4b012a3743b0ffc8dc33fb79e9> /System/Library/PrivateFrameworks/Notes.framework/Notes
0x35fce000 - 0x35fd0fff  OAuth armv7  <575df12a2f2436af92e31494c3b74465> /System/Library/PrivateFrameworks/OAuth.framework/OAuth
0x3670a000 - 0x3672ffff  OpenCL armv7  <9baf655cae4e3f9f99a5c6a99207099d> /System/Library/PrivateFrameworks/OpenCL.framework/OpenCL
0x36a90000 - 0x36aadfff  PersistentConnection armv7  <c773b3dc885832f8a916de67f24f9f92> /System/Library/PrivateFrameworks/PersistentConnection.framework/PersistentConnection
0x36c1f000 - 0x36d06fff  PhotoLibraryServices armv7  <7759e7908e87323f87719265209ebc41> /System/Library/PrivateFrameworks/PhotoLibraryServices.framework/PhotoLibraryServices
0x36d43000 - 0x36d6bfff  PrintKit armv7  <3f0b9c58a458358eb506858e8ff9e1fe> /System/Library/PrivateFrameworks/PrintKit.framework/PrintKit
0x36d6c000 - 0x36de0fff  ProofReader armv7  <9cb25467554637bcb268ba30527d3c0f> /System/Library/PrivateFrameworks/ProofReader.framework/ProofReader
0x36de1000 - 0x36de9fff  ProtocolBuffer armv7  <d1f2888d5e5a39cca6a6179a35c86770> /System/Library/PrivateFrameworks/ProtocolBuffer.framework/ProtocolBuffer
0x36f25000 - 0x36f36fff  SpringBoardServices armv7  <0e48e91ad40f34aab3323c7c4157ce52> /System/Library/PrivateFrameworks/SpringBoardServices.framework/SpringBoardServices
0x36f37000 - 0x36f4bfff  SpringBoardUI armv7  <6efc1c71f1fc3c07ae44d9cf45a6614e> /System/Library/PrivateFrameworks/SpringBoardUI.framework/SpringBoardUI
0x36f77000 - 0x37052fff  StoreServices armv7  <6d45f42eff2736d18cdd81af0473dd5a> /System/Library/PrivateFrameworks/StoreServices.framework/StoreServices
0x370a0000 - 0x370a2fff  TCC armv7  <d5bef30a5bda315194173b862975f9fb> /System/Library/PrivateFrameworks/TCC.framework/TCC
0x370a3000 - 0x370c0fff  TelephonyUI armv7  <f4944c45b790382ea44b08f088b27d6f> /System/Library/PrivateFrameworks/TelephonyUI.framework/TelephonyUI
0x370c1000 - 0x370cefff  TelephonyUtilities armv7  <803d7a92439238ee942086999c481eb6> /System/Library/PrivateFrameworks/TelephonyUtilities.framework/TelephonyUtilities
0x370cf000 - 0x374f3fff  TextInput armv7  <d54d5ca42b503f26ab45e5efd4b87135> /System/Library/PrivateFrameworks/TextInput.framework/TextInput
0x374f4000 - 0x37522fff  ToneLibrary armv7  <99c310617b7d3fe4bdabf13892fc6f0c> /System/Library/PrivateFrameworks/ToneLibrary.framework/ToneLibrary
0x37551000 - 0x375f1fff  UIFoundation armv7  <9a464526e26634bc834537e5ac3abf1f> /System/Library/PrivateFrameworks/UIFoundation.framework/UIFoundation
0x375f2000 - 0x3760afff  Ubiquity armv7  <d72afdd00be23174984d033f197059f7> /System/Library/PrivateFrameworks/Ubiquity.framework/Ubiquity
0x378f5000 - 0x37914fff  WebBookmarks armv7  <77b65bc9c87b367ebea9a5b7984b13a5> /System/Library/PrivateFrameworks/WebBookmarks.framework/WebBookmarks
0x37915000 - 0x38244fff  WebCore armv7  <06c849df1ad435aeb8b6130d85cee5df> /System/Library/PrivateFrameworks/WebCore.framework/WebCore
0x38245000 - 0x38322fff  WebKit armv7  <e0768dbdbdf13c769af7959497e24024> /System/Library/PrivateFrameworks/WebKit.framework/WebKit
0x383c6000 - 0x383ccfff  XPCKit armv7  <cf94468d5a44389e8fdfd2b0802c4378> /System/Library/PrivateFrameworks/XPCKit.framework/XPCKit
0x383cd000 - 0x383d4fff  XPCObjects armv7  <723fe314ab95381cbfa69a0000005692> /System/Library/PrivateFrameworks/XPCObjects.framework/XPCObjects
0x38527000 - 0x38562fff  iCalendar armv7  <1c4486846efd3c9480174d9e7df8cec6> /System/Library/PrivateFrameworks/iCalendar.framework/iCalendar
0x38845000 - 0x3887dfff  iTunesStore armv7  <e88e4626134b32f8bac8e3f79afddf24> /System/Library/PrivateFrameworks/iTunesStore.framework/iTunesStore
0x390e5000 - 0x390ebfff  libAccessibility.dylib armv7  <f40705b5e9c43ce3b1f185fe690b9ac8> /usr/lib/libAccessibility.dylib
0x390ec000 - 0x39102fff  libCRFSuite.dylib armv7  <5a8a3d18a1ff3c97bd773705fef2d81c> /usr/lib/libCRFSuite.dylib
0x39118000 - 0x39119fff  libMobileCheckpoint.dylib armv7  <1e9d719e2f4e3b41970b635e47ee8058> /usr/lib/libMobileCheckpoint.dylib
0x3911a000 - 0x39126fff  libMobileGestalt.dylib armv7  <d0dce72a604b37309b8714fb35d74468> /usr/lib/libMobileGestalt.dylib
0x39138000 - 0x39138fff  libSystem.B.dylib armv7  <7aeeab280f7e361e9986d962d0fa5281> /usr/lib/libSystem.B.dylib
0x39256000 - 0x39262fff  libbsm.0.dylib armv7  <3870b1c8b1783b788bd51da1a04eae6e> /usr/lib/libbsm.0.dylib
0x39263000 - 0x3926cfff  libbz2.1.0.dylib armv7  <b04d27fa0f2d31d8bd0745f8aa0d7f67> /usr/lib/libbz2.1.0.dylib
0x3926d000 - 0x392b7fff  libc++.1.dylib armv7  <ceb9fb64fb203d3a94063a9db6590ca4> /usr/lib/libc++.1.dylib
0x392b8000 - 0x392cbfff  libc++abi.dylib armv7  <4b8520bc534231ae97ce146e076bc7bf> /usr/lib/libc++abi.dylib
0x392f7000 - 0x392f7fff  libgcc_s.1.dylib armv7  <e7e2e533904235d7869baf2ef943407e> /usr/lib/libgcc_s.1.dylib
0x392fc000 - 0x393e9fff  libiconv.2.dylib armv7  <ac23bb84e91e35418c9a2fb4792658b2> /usr/lib/libiconv.2.dylib
0x393ea000 - 0x39533fff  libicucore.A.dylib armv7  <da9d04cc6f6d3825aa52636342ef1e04> /usr/lib/libicucore.A.dylib
0x3953b000 - 0x3953bfff  liblangid.dylib armv7  <a10d8f96815d35e0a1d2c7b998a941f3> /usr/lib/liblangid.dylib
0x3953e000 - 0x39545fff  liblockdown.dylib armv7  <224c65d491603e21a78a00af9e10f012> /usr/lib/liblockdown.dylib
0x39682000 - 0x39825fff  libmecabra.dylib armv7  <0747e596e9983bd6a76cf8349da325e4> /usr/lib/libmecabra.dylib
0x39826000 - 0x3983bfff  libmis.dylib armv7  <7502589f14733beb963c542fa40438c8> /usr/lib/libmis.dylib
0x39864000 - 0x39962fff  libobjc.A.dylib armv7  <79e5d714945834e4b2587abfc6c7269c> /usr/lib/libobjc.A.dylib
0x39a26000 - 0x39a3bfff  libresolv.9.dylib armv7  <3ee61a04a99b322e97e179bc03c46cf1> /usr/lib/libresolv.9.dylib
0x39a60000 - 0x39ae5fff  libsqlite3.dylib armv7  <cbefd01867b93d2a869a534825a1414c> /usr/lib/libsqlite3.dylib
0x39ae6000 - 0x39b31fff  libstdc++.6.dylib armv7  <e3154b06ac5d360c948111abfb2bc339> /usr/lib/libstdc++.6.dylib
0x39b32000 - 0x39b58fff  libtidy.A.dylib armv7  <c43990ee3a5e389aacf288c3615a50dc> /usr/lib/libtidy.A.dylib
0x39b5c000 - 0x39c09fff  libxml2.2.dylib armv7  <28dcf6ee713b387ebb763d11d4b3cd37> /usr/lib/libxml2.2.dylib
0x39c0a000 - 0x39c2afff  libxslt.1.dylib armv7  <d327d9e0f43333568abda8d83558c8a9> /usr/lib/libxslt.1.dylib
0x39c2b000 - 0x39c37fff  libz.1.dylib armv7  <3ea49513bc023326be68e35324c11d0e> /usr/lib/libz.1.dylib
0x39c38000 - 0x39c3bfff  libcache.dylib armv7  <91862e82d5063531b4fb4da9a19e5365> /usr/lib/system/libcache.dylib
0x39c3c000 - 0x39c42fff  libcommonCrypto.dylib armv7  <d9e66574881739e8b25c3ae087a9f409> /usr/lib/system/libcommonCrypto.dylib
0x39c43000 - 0x39c45fff  libcompiler_rt.dylib armv7  <6ac449c92d743640a23d9d1ebe0b48a9> /usr/lib/system/libcompiler_rt.dylib
0x39c46000 - 0x39c4bfff  libcopyfile.dylib armv7  <87bcae8743ab35c8a070ac95b7d57acb> /usr/lib/system/libcopyfile.dylib
0x39c4c000 - 0x39c81fff  libcorecrypto.dylib armv7  <04b464137fc2304b84eeed1a5418f4a8> /usr/lib/system/libcorecrypto.dylib
0x39c82000 - 0x39c9ffff  libdispatch.dylib armv7  <9323bb560d4e3a3fb41efdc78bd0cf94> /usr/lib/system/libdispatch.dylib
0x39ca0000 - 0x39ca1fff  libdnsinfo.dylib armv7  <c25502085c833181b2a12cf525cffde6> /usr/lib/system/libdnsinfo.dylib
0x39ca2000 - 0x39ca3fff  libdyld.dylib armv7  <f0b2fad1b720361297e22866c5c0fb64> /usr/lib/system/libdyld.dylib
0x39ca4000 - 0x39ca4fff  libkeymgr.dylib armv7  <e19c865e73e2352bbc8022033e953f22> /usr/lib/system/libkeymgr.dylib
0x39ca5000 - 0x39caafff  liblaunch.dylib armv7  <c8bedc36bc3d3b55b91b12ebb1240968> /usr/lib/system/liblaunch.dylib
0x39cab000 - 0x39caefff  libmacho.dylib armv7  <965ab939e24935e7a3a65981574a7745> /usr/lib/system/libmacho.dylib
0x39caf000 - 0x39cb0fff  libremovefile.dylib armv7  <295706037a5238b4aa145df7b9354a0e> /usr/lib/system/libremovefile.dylib
0x39cb1000 - 0x39cb1fff  libsystem_blocks.dylib armv7  <50a01a02f573317fbd21e1070b0afc7d> /usr/lib/system/libsystem_blocks.dylib
0x39cb2000 - 0x39d38fff  libsystem_c.dylib armv7  <cacc68d271e53338b7780c26f651b767> /usr/lib/system/libsystem_c.dylib
0x39d39000 - 0x39d3ffff  libsystem_dnssd.dylib armv7  <6c5ac17133a1366aaeea5dc38dceaf1f> /usr/lib/system/libsystem_dnssd.dylib
0x39d40000 - 0x39d58fff  libsystem_info.dylib armv7  <5a4a4c9da868317db7f17cb616eb32d1> /usr/lib/system/libsystem_info.dylib
0x39d59000 - 0x39d6ffff  libsystem_kernel.dylib armv7  <7d409890411a396a9c812f488f8ea99a> /usr/lib/system/libsystem_kernel.dylib
0x39d70000 - 0x39d8cfff  libsystem_m.dylib armv7  <036ea0321da038e8b69a0c4413da00fe> /usr/lib/system/libsystem_m.dylib
0x39d8d000 - 0x39d9bfff  libsystem_network.dylib armv7  <afc167a2e9be3dd6851da8deaf42bafd> /usr/lib/system/libsystem_network.dylib
0x39d9c000 - 0x39da3fff  libsystem_notify.dylib armv7  <c1d71aa978383c51a9ba2b32782d6cc6> /usr/lib/system/libsystem_notify.dylib
0x39da4000 - 0x39da5fff  libsystem_sandbox.dylib armv7  <45bb99d46408351a9c61b5326032adea> /usr/lib/system/libsystem_sandbox.dylib
0x39da6000 - 0x39da6fff  libunwind.dylib armv7  <df8f1d90cbb837cc92d5901fab94e6ca> /usr/lib/system/libunwind.dylib
0x39da7000 - 0x39dbcfff  libxpc.dylib armv7  <7f983066ea4c3c119f3e2344a04fef6e> /usr/lib/system/libxpc.dylib
