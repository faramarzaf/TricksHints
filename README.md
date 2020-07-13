# TricksHints 
There are several solutions,hints and also some tricks about Android in this repository.
I hope this paper would help the programmer's community. 


## Command cheat sheet
**[Open link](https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf)** 

## Public APIs
**[Start](https://github.com/public-apis/public-apis)**  

## Weather Api's   
![Weather](https://cdn3.iconfinder.com/data/icons/weather-icons-10/128/sun-128.png)  
**1- [OpenWeatherMap](https://openweathermap.org/)**  
**2- [Apixu](https://www.apixu.com/)**  
**3- [AccuWeather](https://www.accuweather.com/)**  
**4- [DarkSky](https://darksky.net/)**  
**5- [Climacell](https://www.climacell.co/weather-api/)**  


## Proguard
![Android proguard snippets ](https://github.com/krschultz/android-proguard-snippets)


## How publish our Android library?
:point_right: [Look at this](https://medium.com/@sgkantamani/how-to-create-and-publish-an-android-library-f37bf715932)

<a href="url"><img src="https://httpwg.org/asset/http.svg" height="86" width="106" ></a>  
**1- [AndroidAsync](https://github.com/koush/AndroidAsync)**  
**2- [Fetch](https://github.com/tonyofrancis/Fetch)**  
<a href="url"><img src="https://www.cab.de/media/images/_produktuebersicht/produkt2031.png" height="86" width="106" ></a>  
**1- [ObjectBox](https://docs.objectbox.io/getting-started)**  

## Useful plugins  
![Android](https://cdn0.iconfinder.com/data/icons/communication-icons-rounded/110/Android-128.png)  
**1- [Android Material Design Icon Generator](https://github.com/konifar/android-material-design-icon-generator-plugin)**  
**2- [MVVM Generator](https://plugins.jetbrains.com/plugin/9325-mvvm-generator)**  
**3- [Parcelable Class Generator](https://github.com/mcharmas/android-parcelable-intellij-plugin)**   
**4- [GSON formatter](https://github.com/zzz40500/GsonFormat)**  
**5- [Android Studio Prettify](https://github.com/Haehnchen/idea-android-studio-plugin)**  
**6- [Generate MVP code](https://plugins.jetbrains.com/plugin/9784-generate-m-v-p-code)**  
**7- [Awesome POJO Generator](https://github.com/jineshfrancs/AwesomePojoGenerator)**  

## Some solutions
- Locale  
For people who are still looking for `Locale`solutions in higher APIs, since`configuration.locale()`was deprecated from API 24, We use below code instead.    
```java
  Locale locale1 = new Locale("en");
                                Locale.setDefault(locale1);
                                Configuration config1 = getBaseContext().getResources().getConfiguration();
                                config1.locale = locale1;
                              getBaseContext().getResources().updateConfiguration(config1,getBaseContext().getResources().getDisplayMetrics());
```

## Android useful libraries  
![libraries](https://cdn0.iconfinder.com/data/icons/cosmo-culture/40/books_1-128.png)   



|Library| Category | Library |Category|
| ------------- | ------------- | ------------- | ------------- |
|[android-about-page](https://github.com/medyo/android-about-page)| About page |[about-page-android](https://github.com/husaynhakeem/about-page-android)| About page |
|[MaterialAbout](https://github.com/jrvansuita/MaterialAbout)| About page |[TransformationLayout](https://github.com/skydoves/TransformationLayout)| Animation |
|[Lottie-android](https://github.com/airbnb/lottie-android)| Animation  |[Animatoo](https://github.com/AtifSayings/Animatoo)| Animation  |
|[Material-Animations](https://github.com/lgvalle/Material-Animations)| Animation  |[spruce-android](https://github.com/willowtreeapps/spruce-android)| Animation |
|[FragmentAnimations](https://github.com/kakajika/FragmentAnimations)| Animation |[Android-SpinKit](https://github.com/ybq/Android-SpinKit)| Animation |
|[Backboard](https://github.com/tumblr/Backboard)| Animation |[TextViewExpandableAnimation](https://github.com/freecats/TextViewExpandableAnimation)| Animation |
|[LoadingView](https://github.com/ldoublem/LoadingView)| Animation |[JJSearchViewAnim](https://github.com/android-cjj/JJSearchViewAnim)| Animation |
|[UberCarAnimation](https://github.com/amanjeetsingh150/UberCarAnimation)| Animation |[GoogleMapsAnimations](https://github.com/aarsy/GoogleMapsAnimations)| Animation |
|[AVLoadingIndicatorView](https://github.com/81813780/AVLoadingIndicatorView)| Animation |[FlipAnimation](https://github.com/4xes/FlipAnimation)| Animation |
|[RichPath](https://github.com/tarek360/RichPath)| Animation  |[AndroidViewAnimations](https://github.com/daimajia/AndroidViewAnimations)| Animation  |
|[material-cab](https://github.com/afollestad/material-cab)| Action Bar |[DrawableBadge](https://github.com/minibugdev/DrawableBadge)| Badges  |
|[ModalBottomSheetDialogFragment](https://github.com/Commit451/ModalBottomSheetDialogFragment)| BottomSheet |[bottomsheet-imagepicker](https://github.com/kroegerama/bottomsheet-imagepicker)| BottomSheet |
|[AlertView](https://github.com/Hamadakram/AlertView)| BottomSheet |[sheetmenu](https://github.com/whalemare/sheetmenu)| BottomSheet |
|[BottomSheet](https://github.com/michaelbel/bottomsheet)| BottomSheet |[BottomSheetLayout](https://github.com/qhutch/BottomSheetLayout)| BottomSheet |
|[BottomDrawer](https://github.com/HeyAlex/BottomDrawer)| BottomSheet |[HijriCalendar-master](https://github.com/sahaab/HijriCalendar-master)| Calendar |
|[material-calendarview](https://github.com/prolificinteractive/material-calendarview)| Calendar |[PersianRangeDatePicker](https://github.com/ali-sardari/PersianRangeDatePicker)| Calendar |
|[android-calendar](https://github.com/ShirlyK/android-calendar)| Calendar |[Horizontal-Calendar](https://github.com/Mulham-Raee/Horizontal-Calendar)| Calendar  |
|[CompactCalendarView](https://github.com/SundeepK/CompactCalendarView)| Calendar |[Material-Calendar-View](https://github.com/Applandeo/Material-Calendar-View)| Calendar |
|[material-calendarview](https://github.com/prolificinteractive/material-calendarview)| Calendar  |[datetimepicker](https://github.com/flavienlaurent/datetimepicker)| Calendar |
|[persian-calendar-view](https://github.com/Roojin/persian-calendar-view)| Calendar |[android-betterpickers](https://github.com/code-troopers/android-betterpickers)| Calendar |
|[CrunchyCalendar](https://github.com/CleverPumpkin/CrunchyCalendar)| Calendar |[CameraFragment](https://github.com/florent37/CameraFragment)| Camera  |
|[android-hidden-camera](https://github.com/kevalpatel2106/android-hidden-camera)| Camera  |[QuickShot](https://github.com/Muddz/QuickShot)| Camera|
|[CameraView](https://github.com/natario1/CameraView)| Camera  |[HzGrapher](https://github.com/handstudio/HzGrapher)| Chart  |
|[CurveGraphView](https://github.com/swapnil1104/CurveGraphView)| Chart  |[AnyChart-Android](https://github.com/AnyChart/AnyChart-Android)| Chart  |
|[snake](https://github.com/txusballesteros/snake)| Chart  |[Spark](https://github.com/robinhood/spark)| Chart  |
|[hellocharts-android](https://github.com/lecho/hellocharts-android)| Chart  |[WilliamChart](https://github.com/diogobernardino/WilliamChart)| Chart  |
|[GraphView](https://github.com/jjoe64/GraphView)| Chart  |[EazeGraph](https://github.com/blackfizz/EazeGraph)| Chart  |
|[MPAndroidChart](https://github.com/PhilJay/MPAndroidChart)| Chart  |[android-material-chips](https://github.com/DoodleScheduling/android-material-chips)| Chip  |
|[MaterialChipsInput](https://github.com/pchmn/MaterialChipsInput)| Chip  |[materialChipView](https://github.com/robertlevonyan/materialChipView)| Chip  |
|[MaterialChipsInput](https://github.com/pchmn/MaterialChipsInput)| Chip  |[materialChipView](https://github.com/robertlevonyan/materialChipView)| Chip  |
|[chips-input-layout](https://github.com/tylersuehr7/chips-input-layout)| Chip  |[checkable-chip-view](https://github.com/okdroid/checkable-chip-view)| Chip  |
|[ColorPicker](https://github.com/duanhong169/ColorPicker)| Color Picker |[android-color-wheel](https://github.com/AntonPopoff/android-color-wheel)| Color Picker |
|[CountdownView](https://github.com/iwgang/CountdownView)| Countdown |[PersianMaterialDateTimePicker](https://github.com/mohamad-amin/PersianMaterialDateTimePicker)| Date picker |
|[SunDatePicker](https://github.com/alirezaafkar/SunDatePicker)| Date picker |[date-picker](https://github.com/afollestad/date-picker)| Date picker |
|[SublimePicker](https://github.com/vikramkakkar/SublimePicker)| Date picker |[Persian-Date-Picker-Dialog](https://github.com/aliab/Persian-Date-Picker-Dialog)| Date picker |
|[dialogplus](https://github.com/orhanobut/dialogplus)| Dialog |[Two-Step-Picker-Dialog](https://github.com/aliab/Two-Step-Picker-Dialog)| Dialog |
|[Noty](https://github.com/emre1512/Noty)| Dialog |[BlurDialogFragment](https://github.com/tvbarthel/BlurDialogFragment)| Dialog  |
|[calcdialoglib](https://github.com/maltaisn/calcdialoglib)| Dialog |[iOSDialog](https://github.com/MagicDog707/iOSDialog)| Dialog |
|[TTFancyGifDialog-Android](https://github.com/tayyabtariq50/TTFancyGifDialog-Android)| Dialog |[PrettyDialog](https://github.com/mjn1369/PrettyDialog)| Dialog |
|[FancyAlertDialog-Android](https://github.com/Shashank02051997/FancyAlertDialog-Android)| Dialog |[AnimatedLoadingIndicator](https://github.com/yash786agg/AnimatedLoadingIndicator)| Dialog |
|[DialogSheet](https://github.com/marcoscgdev/DialogSheet)| Dialog |[AndroidMaterialDialog](https://github.com/michael-rapp/AndroidMaterialDialog)| Dialog |
|[material-dialogs](https://github.com/afollestad/material-dialogs)| Dialog |[LovelyDialog](https://github.com/yarolegovich/LovelyDialog)| Dialog |
|[MaterialStyledDialogs](https://github.com/javiersantos/MaterialStyledDialogs)| Dialog |[MediaRecorderDialog](https://github.com/alhazmy13/MediaRecorderDialog)| Dialog |
|[easy-rating-dialog](https://github.com/fernandodev/easy-rating-dialog)| Dialog |[dialogPlus](https://github.com/ma7madfawzy/dialogPlus)| Dialog |
|[Sdp](https://github.com/intuit/sdp)| Dimensions |[richeditor-android](https://github.com/wasabeef/richeditor-android)| Editor |
|[TextFieldBoxes](https://github.com/HITGIF/TextFieldBoxes)| Edit Text |[PasswordEditText](https://github.com/txusballesteros/PasswordEditText)| Edit Text |
|[AutosizeEditText](https://github.com/txusballesteros/AutosizeEditText)| Edit Text |[AutoLinkTextViewV2](https://github.com/armcha/AutoLinkTextViewV2)| Edit Text |
|[OmegaRecyclerView](https://github.com/Omega-R/OmegaRecyclerView)| Expandable  |[RecyclerViewHelper](https://github.com/BoBoMEe/RecyclerViewHelper)| Expandable  |
|[recyclerview-expandable](https://github.com/hendraanggrian/recyclerview-expandable)| Expandable |[ExpandableSwipeRecyclerView](https://github.com/hyunstyle/ExpandableSwipeRecyclerView)| Expandable |
|[async-expandable-list](https://github.com/Ericliu001/async-expandable-list)| Expandable  |[ExpandableListView](https://github.com/harishsn/ExpandableListView)| Expandable  |
|[ExpandableLayout](https://github.com/traex/ExpandableLayout)| Expandable |[expandit](https://github.com/AmalH/expandit)| Expandable |
|[NLeveLExpandableListView](https://github.com/sadra/NLeveLExpandableListView)| Expandable |[DoubleLift](https://github.com/skydoves/DoubleLift)| Expandable |
|[NestedExpandableRecyclerView](https://github.com/thejitesh/NestedExpandableRecyclerView)| Expandable |[ExpandableLayout](https://github.com/skydoves/ExpandableLayout)| Expandable |
|[Fetch](https://github.com/tonyofrancis/Fetch)| File Downloader |[FileDownloader](https://github.com/lingochamp/FileDownloader)| File Downloader |
|[Android-Goldfinger](https://github.com/infinum/Android-Goldfinger)| Fingerprint  |[CounterFab](https://github.com/andremion/CounterFab)| Floating Action Button  |
|[FloatingActionButton](https://github.com/Clans/FloatingActionButton)| Floating Action Button |[FloatingActionButtonSpeedDial](https://github.com/leinardi/FloatingActionButtonSpeedDial)| Floating Action Button  |
|[fab-submenu](https://github.com/ptyagicodecamp/fab-submenu)| Floating Action Button  |[fab](https://github.com/Scalified/fab)| Floating Action Button  |
|[MaterialFavoriteButton](https://github.com/IvBaranov/MaterialFavoriteButton)| Floating Action Button|[RapidFloatingActionButton](https://github.com/wangjiegulu/RapidFloatingActionButton)| Floating Action Button  |
|[BoomMenu](https://github.com/Nightonke/BoomMenu)| Floating Action Button |[EasyFonts](https://github.com/vsvankhede/EasyFonts)| Font |
|[Calligraphy](https://github.com/chrisjenx/Calligraphy)| Font |[AppIntroAnimation](https://github.com/TakeoffAndroid/AppIntroAnimation)| Intro |
|[material-intro-screen](https://github.com/TangoAgency/material-intro-screen)| Intro |[material-intro](https://github.com/heinrichreimer/material-intro)| Intro |
|[AppIntro](https://github.com/AppIntro/AppIntro)| Intro |[welcome-coordinator](https://github.com/txusballesteros/welcome-coordinator)| Intro  |
|[welcome-android](https://github.com/stephentuso/welcome-android)| Intro |[MaterialProgressBar](https://github.com/zhanghai/MaterialProgressBar)| Loading |  
|[Skeleton](https://github.com/ethanhua/Skeleton)| Loading |[ENViews](https://github.com/codeestX/ENViews)| Loading |
|[WaveView](https://github.com/gelitenight/WaveView)| Loading  |[DialerLoading](https://github.com/SaeedMasoumi/DialerLoading)| Loading |
|[locale-helper-android](https://github.com/zeugma-solutions/locale-helper-android)| Locale |[EasyWayLocation](https://github.com/prabhat1707/EasyWayLocation)| Location  |
|[TinyTravelTracker](https://github.com/redfish64/TinyTravelTracker)| Location  |[Smart location](https://github.com/mrmans0n/smart-location-lib)| Location  |
|[AirLocation](https://github.com/mumayank/AirLocation)| Location  |[Track-My-Location](https://github.com/abdularis/Track-My-Location)| Location  |
|[Logger](https://github.com/orhanobut/logger)| Logcat  |[android-material-play-pause-view](https://github.com/OHoussein/android-material-play-pause-view)| Material  |
|[Vitrin](https://github.com/bullseyedevs/Vitrin)| Material  |[sliding-deck](https://github.com/txusballesteros/sliding-deck)| Material  |
|[Material](https://github.com/rey5137/material)| Material  |[Autocomplete](https://github.com/natario1/Autocomplete)| Material  |
|[GestureViews](https://github.com/alexvasilkov/GestureViews)| Material  |[Konfetti](https://github.com/DanielMartinus/Konfetti)| Material  |
|[ShineButton](https://github.com/ChadCSong/ShineButton)| Material  |[MyLittleCanvas](https://github.com/florent37/MyLittleCanvas)| Material  |
|[DiagonalLayout](https://github.com/florent37/DiagonalLayout)| Material  |[GlidePalette](https://github.com/florent37/GlidePalette)| Material  |
|[material-menu](https://github.com/balysv/material-menu)| Material  |[RippleEffect](https://github.com/traex/RippleEffect)| Material  |
|[MaterialScrollBar](https://github.com/turing-tech/MaterialScrollBar)| Material |[CreditCardView](https://github.com/vinaygaba/CreditCardView)| Material |
|[RecyclerRefreshLayout](https://github.com/dinuscxj/RecyclerRefreshLayout)| Material  |[FreeDrawView](https://github.com/RiccardoMoro/FreeDrawView)| Material |
|[MaterialScrollBar](https://github.com/turing-tech/MaterialScrollBar)| Material |[flexbox-layout](https://github.com/google/flexbox-layout)| Material |
|[CreditCardView](https://github.com/vinaygaba/CreditCardView)| Material |[Android-Bootstrap](https://github.com/Bearded-Hen/Android-Bootstrap)| Material |
|[ExoPlayer](https://github.com/google/ExoPlayer)| Media player |[PowerMenu](https://github.com/skydoves/PowerMenu)| Menu  |
|[CircleMenu](https://github.com/ImangazalievM/CircleMenu)| Menu  |[CycleMenu](https://github.com/Cleveroad/CycleMenu)| Menu  |
|[boxing](https://github.com/bilibili/boxing)| Multi media selector  |[AnimatedBottomBar](https://github.com/Droppers/AnimatedBottomBar)| Navigation bar  |
|[SmoothBottomBar](https://github.com/ibrahimsn98/SmoothBottomBar)| Navigation bar  |[ahbottomnavigation](https://github.com/aurelhubert/ahbottomnavigation)| Navigation bar  |
|[NiceBottomBar](https://github.com/ibrahimsn98/NiceBottomBar)| Navigation bar  |[BottomBar](https://github.com/roughike/BottomBar)| Navigation bar  |
|[ReadableBottomBar](https://github.com/iammert/ReadableBottomBar)| Navigation bar  |[AdaptableBottomNavigation](https://github.com/bufferapp/AdaptableBottomNavigation)| Navigation bar  |
|[PagerBottomTabStrip](https://github.com/tyzlmjj/PagerBottomTabStrip)| Navigation bar  |[bubble-navigation](https://github.com/gauravk95/bubble-navigation)| Navigation bar  |
|[BottomNavBar](https://github.com/adib2149/BottomNavBar)| Navigation bar  |[lottiebottomnavbar](https://github.com/subsub/lottiebottomnavbar)| Navigation bar  |
|[NiceBottomBar](https://github.com/ibrahimsn98/NiceBottomBar)| Navigation bar  |[BottomNavigation](https://github.com/Ashok-Varma/BottomNavigation)| Navigation bar  |
|[Material-BottomNavigation](https://github.com/sephiroth74/Material-BottomNavigation)| Navigation bar  |[bubble-navigation](https://github.com/gauravk95/bubble-navigation)| Navigation bar  |
|[morph-bottom-navigation](https://github.com/tommybuonomo/morph-bottom-navigation)| Navigation bar  |[BottomNavigationBar](https://github.com/fishwjy/BottomNavigationBar)| Navigation bar  |
|[MeowBottomNavigation](https://github.com/shetmobile/MeowBottomNavigation)| Navigation bar  |[AdvancedMaterialDrawer](https://github.com/madcyph3r/AdvancedMaterialDrawer)| Navigation drawer |
|[AwesomeNavigationDrawer](https://github.com/root-ansh/AwesomeNavigationDrawer)| Navigation drawer |[duo-navigation-drawer](https://github.com/PSD-Company/duo-navigation-drawer)| Navigation drawer  |
|[Drawer-Behavior](https://github.com/shiburagi/Drawer-Behavior)| Navigation drawer  |[material-drawer](https://github.com/heinrichreimer/material-drawer)| Navigation drawer |
|[bubble-navigation](https://github.com/gauravk95/bubble-navigation)| Navigation drawer |[ArcNavigationView](https://github.com/rom4ek/ArcNavigationView)| Navigation drawer  |
|[LDrawer](https://github.com/keklikhasan/LDrawer)| Navigation drawer |[Custom-Navigation-Drawer](https://github.com/shrikanth7698/Custom-Navigation-Drawer)| Navigation drawer  |
|[SlidingRootNav](https://github.com/yarolegovich/SlidingRootNav)| Navigation drawer  |[MaterialDrawerKt](https://github.com/zsmb13/MaterialDrawerKt)| Navigation drawer  |
|[AppCompat-Extension-Library](https://github.com/TR4Android/AppCompat-Extension-Library)| Navigation drawer  |[TabDrawer](https://github.com/ashazar/TabDrawer)| Navigation drawer  |
|[FlowingDrawer](https://github.com/mxn21/FlowingDrawer)| Navigation drawer  |[DrawerMultiLevelListview](https://github.com/awidiyadew/DrawerMultiLevelListview)| Navigation drawer   |
|[NavigationTabStrip](https://github.com/Devlight/NavigationTabStrip)| Navigation Tab  |[Alerter](https://github.com/Tapadoo/Alerter)| Notif  |
|[Noty](https://github.com/emre1512/Noty)| Notif |[VNTNumberPickerPreference](https://github.com/vanniktech/VNTNumberPickerPreference)| NumberPicker |
|[NumberPicker](https://github.com/ShawnLin013/NumberPicker)| NumberPicker |[NumberSlidingPicker](https://github.com/sephiroth74/NumberSlidingPicker)| NumberPicker |
|[meter-number-picker](https://github.com/alexzaitsev/meter-number-picker)| NumberPicker |[MaterialNumberPicker](https://github.com/StephenVinouze/MaterialNumberPicker)| NumberPicker |
|[ScrollableNumberPicker](https://github.com/michaelmuenzer/ScrollableNumberPicker)| NumberPicker |[actual-number-picker](https://github.com/milosmns/actual-number-picker)| NumberPicker |
|[SwipePicker](https://github.com/m4xp1/SwipePicker)| NumberPicker |[PinView-Android](https://github.com/darshan-miskin/PinView-Android)| OTP View|
|[PinEntryEditText](https://github.com/alphamu/PinEntryEditText)| OTP View|[Pinview](https://github.com/GoodieBag/Pinview)| OTP View|
|[AndroidOtpCustomViewmaster](https://github.com/Temidtech/AndroidOtpCustomViewmaster)| OTP View|[OtpView](https://github.com/aabhasr1/OtpView)| OTP View|
|[PinView](https://github.com/ChaosLeung/PinView)| OTP View|[android-otpview-pinview](https://github.com/mukeshsolanki/android-otpview-pinview)| OTP View|
|[PatternLockView](https://github.com/aritraroy/PatternLockView)| Pattern lock |[persian-calendar-view](https://github.com/Roojin/persian-calendar-view)| Persian date |
|[DroidPersianCalendar](https://github.com/persian-calendar/DroidPersianCalendar)| Persian date |[Persian-Date-Picker-Dialog](https://github.com/aliab/Persian-Date-Picker-Dialog)| Persian date |
|[PersianMaterialDateTimePicker](https://github.com/mohamad-amin/PersianMaterialDateTimePicker)| Persian date |[PersianRangeDatePicker](https://github.com/ali-sardari/PersianRangeDatePicker)| Persian date |
|[PersianCaldroid](https://github.com/dariushm2/PersianCaldroid)| Persian date |[PersianLinearDatePicker](https://github.com/SirLordPouya/PersianLinearDatePicker)| Persian date |
|[QuickShot](https://github.com/Muddz/QuickShot)| Photo  |[RxLowpoly](https://github.com/abhriyaroy/RxLowpoly)| Photo  |
|[ion](https://github.com/koush/ion)| Photo  |[Android-Universal-Image-Loader](https://github.com/nostra13/Android-Universal-Image-Loader)| Photo  |
|[Android-Font-Awesome](https://github.com/ravi8x/Android-Font-Awesome)| Photo  |[Glide](https://github.com/bumptech/glide)| Photo  |
|[EtsyBlur](https://github.com/Manabu-GT/EtsyBlur)| Photo  |[Rounded Imageview](https://github.com/vinc3m1/RoundedImageView)| Photo  |
|[android-gpuimage](https://github.com/cats-oss/android-gpuimage)| Photo |[Matisse](https://github.com/zhihu/Matisse)| Photo |
|[Android-Image-Picker-and-Cropping](https://github.com/ravi8x/Android-Image-Picker-and-Cropping)| Photo  |[android-shape-imageview](https://github.com/siyamed/android-shape-imageview)| Photo |
|[Compressor](https://github.com/zetbaitsu/Compressor)| Photo |[Crescento](https://github.com/developer-shivam/crescento)| Photo |
|[subsampling-scale-image-view](https://github.com/davemorrissey/subsampling-scale-image-view)| Photo |[cropiwa](https://github.com/steelkiwi/cropiwa)| Photo |
|[Easy Image](https://github.com/jkwiecien/EasyImage)| Photo  |[CircleImageView](https://github.com/hdodenhof/CircleImageView)| Photo  |
|[Zoomy](https://github.com/imablanco/Zoomy)| Photo |[Blurkit Android](https://github.com/CameraKit/blurkit-android)| Photo  |
|[FrescoImageViewer](https://github.com/stfalcon-studio/FrescoImageViewer)| Photo |[android-crop](https://github.com/jdamcd/android-crop)| Photo  |
|[Blurry](https://github.com/wasabeef/Blurry)| Photo |[uCrop](https://github.com/Yalantis/uCrop)| Photo |
|[Android-Image-Cropper](https://github.com/ArthurHub/Android-Image-Cropper)| Photo |[Dexter](https://github.com/Karumi/Dexter)| Permissions  |
|[ProtractorView](https://github.com/GoodieBag/ProtractorView)| ProgressBar  |[circular-music-progressbar](https://github.com/aliab/circular-music-progressbar)| ProgressBar  |
|[NumberProgressBar](https://github.com/daimajia/NumberProgressBar)| ProgressBar  |[CircleProgress](https://github.com/lzyzsd/CircleProgress)| ProgressBar  |
|[CatLoadingView](https://github.com/Rogero0o/CatLoadingView)| ProgressBar  |[Circle-Progress-View](https://github.com/jakob-grabner/Circle-Progress-View)| ProgressBar  |
|[fit-chart](https://github.com/txusballesteros/fit-chart)| ProgressBar  |[circular-progress-button](https://github.com/dmytrodanylyk/circular-progress-button) | ProgressBar  |
|[android-morphing-button](https://github.com/dmytrodanylyk/android-morphing-button)| ProgressBar  |[zxing-android-embedded](https://github.com/journeyapps/zxing-android-embedded)| QR code |
|[MaterialRangeBar](https://github.com/oli107/material-range-bar)| Range Bar  |[android-slidr](https://github.com/florent37/android-slidr)| Range Bar  |
|[simple-range-view](https://github.com/bendikv/simple-range-view)| Range Bar  |[SmileyRating](https://github.com/sujithkanna/SmileyRating)| Rating Bar |
|[TextDrawable](https://github.com/amulyakhare/TextDrawable)| Recycler View Helper |[RecyclerViewItemAnimators](https://github.com/gabrielemariotti/RecyclerViewItemAnimators)| Recycler View  |
|[ShimmerRecyclerView](https://github.com/sharish/ShimmerRecyclerView)| Recycler View  |[drag-select-recyclerview](https://github.com/afollestad/drag-select-recyclerview)| Recycler View  |
|[recyclical](https://github.com/afollestad/recyclical)| Recycler View  |[RecyclerBanner](https://github.com/ren93/RecyclerBanner)| Recycler View  |
|[AutoPlayVideoRecyclerView](https://github.com/mobileappsvn/AutoPlayVideoRecyclerView)| Recycler View  |[RendererRecyclerViewAdapter](https://github.com/vivchar/RendererRecyclerViewAdapter)| Recycler View  |
|[MultiSnapRecyclerView](https://github.com/TakuSemba/MultiSnapRecyclerView)| Recycler View  |[dynamic-recyclerview](https://github.com/masudias/dynamic-recyclerview)| Recycler View  |
|[MultiViewAdapter](https://github.com/DevAhamed/MultiViewAdapter)| Recycler View  |[android-advancedrecyclerview](https://github.com/h6ah4i/android-advancedrecyclerview)| Recycler View  |
|[recycler-view-margin-decoration](https://github.com/TheKhaeng/recycler-view-margin-decoration)| Recycler View  |[IndicatorScrollView](https://github.com/skydoves/IndicatorScrollView)| Scroll View |
|[MaterialScrollBar](https://github.com/turing-tech/MaterialScrollBar)| Scroll View |[DiscreteScrollView](https://github.com/yarolegovich/DiscreteScrollView)| Scroll View |
|[MaterialSearchView](https://github.com/MiguelCatalan/MaterialSearchView)| Search View |[MaterialSearchBar](https://github.com/mancj/MaterialSearchBar)| Search View |
|[Croller](https://github.com/harjot-oberai/Croller)| Seekbar |[ProtractorView](https://github.com/GoodieBag/ProtractorView)| Seekbar |
|[fluid-slider-android](https://github.com/Ramotion/fluid-slider-android)| Seekbar |[ToggleButtonLayout](https://github.com/savvyapps/ToggleButtonLayout)| Segmented |
|[android-segmented-control](https://github.com/Kaopiz/android-segmented-control)| Segmented |[SegmentedControl](https://github.com/RobertApikyan/SegmentedControl)| Segmented |
|[RadioRealButton](https://github.com/ceryle/RadioRealButton)| Segmented |[SegmentedButton](https://github.com/ceryle/SegmentedButton)| Segmented |
|[android-segmentedtab](https://github.com/pucamafra/android-segmentedtab)| Segmented |[sensey](https://github.com/nisrulz/sensey)| Sensor |
|[shortbread](https://github.com/MatthiasRobbers/shortbread)| Shortcut  |[BubbleShowCase-Android](https://github.com/ECLaboratorio/BubbleShowCase-Android)| Show Case  |
|[MultiLamp](https://github.com/ujwalthote/MultiLamp)| Show Case  |[ShowCaseView](https://github.com/mreram/ShowCaseView)| Show Case  |
|[FancyShowCaseView](https://github.com/faruktoptas/FancyShowCaseView)| Show Case  |[VSpot](https://github.com/TutorialsAndroid/VSpot)| Show Case  |
|[TapTargetView](https://github.com/KeepSafe/TapTargetView)| Show Case |[TutoShowcase](https://github.com/florent37/TutoShowcase)| Show Case  |
|[Hawk](https://github.com/orhanobut/hawk)| Shared preference  |[Light](https://github.com/TonnyL/Light)| Snackbar |
|[ChocoBar](https://github.com/Pradyuman7/ChocoBar)| Snackbar |[MaterialSpinner](https://github.com/jaredrummler/MaterialSpinner)| Spinner |
|[AwesomeSpinner](https://github.com/sadra/AwesomeSpinner)| Spinner |[nice-spinner](https://github.com/arcadefire/nice-spinner)| Spinner |
|[MaterialSpinner](https://github.com/tiper/MaterialSpinner)| Spinner |[RTLMaterialSpinner](https://github.com/aliab/RTLMaterialSpinner)| Spinner |
|[SmartMaterialSpinner](https://github.com/Chivorns/SmartMaterialSpinner)| Spinner |[MaterialStepperView](https://github.com/fython/MaterialStepperView)| Stepper |
|[stepper-indicator](https://github.com/badoualy/stepper-indicator)| Stepper |[VerticalStepperForm](https://github.com/ernestoyaquello/VerticalStepperForm)| Stepper |
|[MaterialStepper](https://github.com/PedroCarrillo/MaterialStepper)| Stepper |[Image-Steps](https://github.com/denisviana/Image-Steps)| Stepper |
|[Timeline-View](https://github.com/vipulasri/Timeline-View)| Stepper |[Android-Timeline-View](https://github.com/akshaykale/Android-Timeline-View)| Stepper |
|[jerryOkaforTimeLineView](https://github.com/jerryOkafor/TimeLineView)| Stepper |[StickyTimeLine](https://github.com/sangcomz/StickyTimeLine)| Stepper |
|[TimeLine](https://github.com/vivian8725118/TimeLine)| Stepper |[TimelineView](https://github.com/qapqap/TimelineView)| Stepper |
|[MaterialTimelineView](https://github.com/hypeapps/MaterialTimelineView?source=post_page-----9fb77a590316----------------------)| Stepper |[WaveSwipeRefreshLayout](https://github.com/recruit-lifestyle/WaveSwipeRefreshLayout)| SwipeRefreshLayout |
|[CircleRefreshLayout](https://github.com/tuesda/CircleRefreshLayout)| SwipeRefreshLayout |[Android-SwitchIcon](https://github.com/zagum/Android-SwitchIcon)| Switch (enable/disable)  |
|[StickySwitch](https://github.com/GwonHyeok/StickySwitch)| Switch (enable/disable) |[SwitchButton](https://github.com/zcweng/SwitchButton)| Switch |
|[SwitchButton2](https://github.com/kyleduo/SwitchButton)| Switch |[SmartTabLayout](https://github.com/ogaclejapan/SmartTabLayout)| Tab Bar |
|[fading-text-view](https://github.com/rosenpin/fading-text-view)| TextView  |[Justified TextView](https://github.com/ufo22940268/android-justifiedtextview)| TextView  |
|[RotatingText](https://github.com/mdg-iitr/RotatingText)| TextView |[TextSurface](https://github.com/elevenetc/TextSurface)| TextView  |
|[Titanic](https://github.com/RomainPiel/Titanic)| TextView  |[ReadMoreTextView](https://github.com/bravoborja/ReadMoreTextView)| TextView |
|[MaterialTextField](https://github.com/florent37/MaterialTextField)| TextView  |[Android-ExpandableTextView](https://github.com/Blogcat/Android-ExpandableTextView)| TextView  |
|[Android-ExpandableTextView](https://github.com/Blogcat/Android-ExpandableTextView)| TextView  |[SingleDateAndTimePicker](https://github.com/florent37/SingleDateAndTimePicker)| Time  |
|[CalendarListview](https://github.com/traex/CalendarListview)| Time  |[FlatTimeCollection](https://github.com/anastr/FlatTimeCollection)| Time   |
|[android-times-square](https://github.com/square/android-times-square)| Time  |[HijriDatePicker](https://github.com/alhazmy13/HijriDatePicker)| Time |
|[FlipTimerView](https://github.com/anugotta/FlipTimerView)| Time |[Range-Time-Picker-Dialog](https://github.com/PuffoCyano/Range-Time-Picker-Dialog)| Time |
|[StyleableToast](https://github.com/Muddz/StyleableToast)| Toast |[Toasty](https://github.com/GrenderG/Toasty)| Toast  |
|[MyToast](https://github.com/lopspower/MyToast)| Toast  |[TastyToast](https://github.com/yadav-rahul/TastyToast)| Toast |
|[MotionToast](https://github.com/Spikeysanju/MotionToast)| Toast |[AppUpdater](https://github.com/javiersantos/AppUpdater)| Updater |
|[MaterialViewPager](https://github.com/florent37/MaterialViewPager)| ViewPager |[WoWoViewPager](https://github.com/Nightonke/WoWoViewPager)| ViewPager |

| Library  | Category |
| ------------- | ------------- |
|[CircleIndicator](https://github.com/ongakuer/CircleIndicator)| ViewPager |
|[MovingImageView](https://github.com/AlbertGrobas/MovingImageView)| Animation |
|[RingProgressBar](https://github.com/HotBitmapGG/RingProgressBar)| ProgressBar |
|[AndroidAppUpdater](https://github.com/SirLordPouya/AndroidAppUpdater)| Updater |
|[EasyTransition](https://github.com/huzenan/EasyTransition)| Animation |
|[Space-Navigation-View ](https://github.com/armcha/Space-Navigation-View)| Navigation bar |
|[Colorful](https://github.com/garretyoder/Colorful)| Theme |
|[StickySwitch](https://github.com/GwonHyeok/StickySwitch)| Switch |
|[RoundCornerProgressBar](https://github.com/GwonHyeok/StickySwitch)| ProgressBar |
|[SearchableSpinner](https://github.com/MdFarhanRaja/SearchableSpinner)| ProgressBar |
|[MultiProgressBar](https://github.com/knight-rider1609/MultiProgressBar)| ProgressBar |
|[ProgressView](https://github.com/skydoves/ProgressView)| ProgressBar |
|[CirclesLoadingView](https://github.com/ibrahimsn98/CirclesLoadingView)| Loading |
|[DroidPersianCalendar](https://github.com/persian-calendar/DroidPersianCalendar)| Calendar |
|[easypermissions-android](https://github.com/mukeshsolanki/easypermissions-android)| Permission |
|[SmileyRating](https://github.com/sujithkanna/SmileyRating)| Rating |
|[ChatMessagesAdapter-android](https://github.com/QuickBlox/ChatMessagesAdapter-android)| Chat |
|[stream-chat-android](https://github.com/GetStream/stream-chat-android)| Chat |
|[ChatView](https://github.com/shrikanth7698/ChatView)| Chat |
|[ChatMessageView](https://github.com/bassaer/ChatMessageView)| Chat |
[WindView](https://github.com/AhmadNemati/WindView)| Animation |
[StepView](https://github.com/shuhart/StepView)| Stepper |
[ColorPickerView](https://github.com/skydoves/ColorPickerView)| ColorPicker |
|[LandscapeVideoCamera](https://github.com/JeroenMols/LandscapeVideoCamera)| Camera |
|[CardStackView](https://github.com/loopeer/CardStackView)| Material |
|[JellyToggleButton](https://github.com/Nightonke/JellyToggleButton)| ToogleButton |
|[animate](https://github.com/hitherejoe/animate)| Animation |
|[AnimationEasingFunctions](https://github.com/daimajia/AnimationEasingFunctions)| Animation |
|[LiquidButton](https://github.com/yoruriko/LiquidButton)| Animation |
|[Particle](https://github.com/JeasonWong/Particle)| Animation |
|[dotsindicator](https://github.com/tommybuonomo/dotsindicator)| Intro |
