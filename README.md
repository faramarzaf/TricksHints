# TricksHints 
There are several solutions,hints and also some tricks about Android in this repository.
I hope this paper would help the programmers' community. 

## Public APIs
**[Start](https://github.com/public-apis/public-apis)**  

## Weather Api's   
![Weather](https://cdn3.iconfinder.com/data/icons/weather-icons-10/128/sun-128.png)  
**1- [OpenWeatherMap](https://openweathermap.org/)**  
**2- [Apixu](https://www.apixu.com/)**  
**3- [AccuWeather](https://www.accuweather.com/)**  
**4- [DarkSky](https://darksky.net/)**  
**5- [Climacell](https://www.climacell.co/weather-api/)**  

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

| Library  | Category |
| ------------- | ------------- |
|[android-about-page](https://github.com/medyo/android-about-page)| About page  |
|[about-page-android](https://github.com/husaynhakeem/about-page-android)| About page  |
|[MaterialAbout](https://github.com/jrvansuita/MaterialAbout)| About page  |
|[Lottie-android](https://github.com/airbnb/lottie-android)| Animation  |
|[Material-Animations](https://github.com/lgvalle/Material-Animations)| Animation  |
|[spruce-android](https://github.com/willowtreeapps/spruce-android)| Animation |
|[FragmentAnimations](https://github.com/kakajika/FragmentAnimations)| Animation |
|[Android-SpinKit](https://github.com/ybq/Android-SpinKit)| Animation |
|[Backboard](https://github.com/tumblr/Backboard)| Animation |
|[TextViewExpandableAnimation](https://github.com/freecats/TextViewExpandableAnimation)| Animation |
|[LoadingView](https://github.com/ldoublem/LoadingView)| Animation |
|[JJSearchViewAnim](https://github.com/android-cjj/JJSearchViewAnim)| Animation |
|[UberCarAnimation](https://github.com/amanjeetsingh150/UberCarAnimation)| Animation |
|[GoogleMapsAnimations](https://github.com/aarsy/GoogleMapsAnimations)| Animation |
|[AVLoadingIndicatorView](https://github.com/81813780/AVLoadingIndicatorView)| Animation |
|[FlipAnimation](https://github.com/4xes/FlipAnimation)| Animation |
|[DrawableBadge](https://github.com/minibugdev/DrawableBadge)| Badges  |
|[Horizontal-Calendar](https://github.com/Mulham-Raee/Horizontal-Calendar)| Calendar  |
|[CompactCalendarView](https://github.com/SundeepK/CompactCalendarView)| Calendar |
|[CameraFragment](https://github.com/florent37/CameraFragment)| Camera  |
|[android-hidden-camera](https://github.com/kevalpatel2106/android-hidden-camera)| Camera   |
|[AnyChart-Android](https://github.com/AnyChart/AnyChart-Android)| Chart  |
|[snake](https://github.com/txusballesteros/snake)| Chart  |
|[Spark](https://github.com/robinhood/spark)| Chart  |
|[hellocharts-android](https://github.com/lecho/hellocharts-android)| Chart  |
|[WilliamChart](https://github.com/diogobernardino/WilliamChart)| Chart  |
|[EtsyBlur](https://github.com/Manabu-GT/EtsyBlur)| Chart  |
|[RichPath](https://github.com/tarek360/RichPath)| Chart  |
|[GraphView](https://github.com/jjoe64/GraphView)| Chart  |
|[EazeGraph](https://github.com/blackfizz/EazeGraph)| Chart  |
|[MPAndroidChart](https://github.com/PhilJay/MPAndroidChart)| Chart  |
|[BlurDialogFragment](https://github.com/tvbarthel/BlurDialogFragment)| Chart  |
|[CountdownView](https://github.com/iwgang/CountdownView)| Countdown |
|[dialogplus](https://github.com/orhanobut/dialogplus)| Dialog |
|[Noty](https://github.com/emre1512/Noty)| Dialog |
|[calcdialoglib](https://github.com/maltaisn/calcdialoglib)| Dialog |
|[iOSDialog](https://github.com/MagicDog707/iOSDialog)| Dialog |
|[TTFancyGifDialog-Android](https://github.com/tayyabtariq50/TTFancyGifDialog-Android)| Dialog |
|[PrettyDialog](https://github.com/mjn1369/PrettyDialog)| Dialog |
|[FancyAlertDialog-Android](https://github.com/Shashank02051997/FancyAlertDialog-Android)| Dialog |
|[AnimatedLoadingIndicator](https://github.com/yash786agg/AnimatedLoadingIndicator)| Dialog |
|[DialogSheet](https://github.com/marcoscgdev/DialogSheet)| Dialog |
|[AndroidMaterialDialog](https://github.com/michael-rapp/AndroidMaterialDialog)| Dialog |
|[material-dialogs](https://github.com/afollestad/material-dialogs)| Dialog |
|[LovelyDialog](https://github.com/yarolegovich/LovelyDialog)| Dialog |
|[MaterialStyledDialogs](https://github.com/javiersantos/MaterialStyledDialogs)| Dialog  |
|[MediaRecorderDialog](https://github.com/alhazmy13/MediaRecorderDialog)| Dialog |
|[easy-rating-dialog](https://github.com/fernandodev/easy-rating-dialog)| Dialog |
|[Sdp](https://github.com/intuit/sdp)| Dimensions |
|[richeditor-android](https://github.com/wasabeef/richeditor-android)| Editor |
|[TextFieldBoxes](https://github.com/HITGIF/TextFieldBoxes)| Edit Text |
|[OmegaRecyclerView](https://github.com/Omega-R/OmegaRecyclerView)| Expandable  |
|[RecyclerViewHelper](https://github.com/BoBoMEe/RecyclerViewHelper)| Expandable  |
|[recyclerview-expandable](https://github.com/hendraanggrian/recyclerview-expandable)| Expandable |
|[ExpandableSwipeRecyclerView](https://github.com/hyunstyle/ExpandableSwipeRecyclerView)| Expandable |
|[async-expandable-list](https://github.com/Ericliu001/async-expandable-list)| Expandable  |
|[ExpandableListView](https://github.com/harishsn/ExpandableListView)| Expandable  |
|[ExpandableLayout](https://github.com/traex/ExpandableLayout)| Expandable |
|[expandit](https://github.com/AmalH/expandit)| Expandable |
|[NestedExpandableRecyclerView](https://github.com/thejitesh/NestedExpandableRecyclerView)| Expandable |
|[Fetch](https://github.com/tonyofrancis/Fetch)| File Downloader |
|[Android-Goldfinger](https://github.com/infinum/Android-Goldfinger)| Fingerprint  |
|[CounterFab](https://github.com/andremion/CounterFab)| Floating Action Button  |
|[material-intro-screen](https://github.com/TangoAgency/material-intro-screen)| Intro |
|[material-intro](https://github.com/heinrichreimer/material-intro)| Intro |
|[Smart location](https://github.com/mrmans0n/smart-location-lib)| Location  |
|[AirLocation](https://github.com/mumayank/AirLocation)| Location  |
|[MaterialProgressBar](https://github.com/zhanghai/MaterialProgressBar)| Loading |
|[Skeleton](https://github.com/ethanhua/Skeleton)| Loading |
|[ENViews](https://github.com/codeestX/ENViews)| Loading |
|[Logger](https://github.com/orhanobut/logger)| Logcat  |
|[MaterialDrawerKt](https://github.com/zsmb13/MaterialDrawerKt)| Material  |
|[Vitrin](https://github.com/bullseyedevs/Vitrin)| Material  |
|[SwitchButton](https://github.com/KingJA/SwitchButton)| Material  |
|[TapTargetView](https://github.com/KeepSafe/TapTargetView)| Material  |
|[CameraView](https://github.com/natario1/CameraView)| Material  |
|[fit-chart](https://github.com/txusballesteros/fit-chart)| Material  |
|[welcome-coordinator](https://github.com/txusballesteros/welcome-coordinator)| Material  |
|[sliding-deck](https://github.com/txusballesteros/sliding-deck)| Material  |
|[DrawerMultiLevelListview](https://github.com/awidiyadew/DrawerMultiLevelListview)| Material  |
|[Material](https://github.com/rey5137/material)| Material  |
|[Calligraphy](https://github.com/chrisjenx/Calligraphy)| Material  |
|[Autocomplete](https://github.com/natario1/Autocomplete)| Material  |
|[GestureViews](https://github.com/alexvasilkov/GestureViews)| Material  |
|[lottiebottomnavbar](https://github.com/subsub/lottiebottomnavbar)| Material  |
|[BoomMenu](https://github.com/Nightonke/BoomMenu)| Material  |
|[AppIntro](https://github.com/AppIntro/AppIntro)| Material  |
|[Konfetti](https://github.com/DanielMartinus/Konfetti)| Material  |
|[ShineButton](https://github.com/ChadCSong/ShineButton)| Material  |
|[MyLittleCanvas](https://github.com/florent37/MyLittleCanvas)| Material  |
|[TutoShowcase](https://github.com/florent37/TutoShowcase)| Material  |
|[DiagonalLayout](https://github.com/florent37/DiagonalLayout)| Material  |
|[GlidePalette](https://github.com/florent37/GlidePalette)| Material  |
|[material-menu](https://github.com/balysv/material-menu)| Material  |
|[material-calendarview](https://github.com/prolificinteractive/material-calendarview)| Material  |
|[WaveSwipeRefreshLayout](https://github.com/recruit-lifestyle/WaveSwipeRefreshLayout)| Material  |
|[circular-progress-button](https://github.com/dmytrodanylyk/circular-progress-button) | Material  |
|[android-slidr](https://github.com/florent37/android-slidr)| Material  |
|[RippleEffect](https://github.com/traex/RippleEffect)| Material  |
|[CircleRefreshLayout](https://github.com/tuesda/CircleRefreshLayout)| Material  |
|[WaveView](https://github.com/gelitenight/WaveView)| Material  |
|[MaterialScrollBar](https://github.com/turing-tech/MaterialScrollBar)| Material |
|[CreditCardView](https://github.com/vinaygaba/CreditCardView)| Material |
|[RecyclerRefreshLayout](https://github.com/dinuscxj/RecyclerRefreshLayout)| Material  |
|[MaterialStepperView](https://github.com/fython/MaterialStepperView)| Material |
|[FreeDrawView](https://github.com/RiccardoMoro/FreeDrawView)| Material |
|[MaterialScrollBar](https://github.com/turing-tech/MaterialScrollBar)| Material |
|[flexbox-layout](https://github.com/google/flexbox-layout)| Material |
|[CreditCardView](https://github.com/vinaygaba/CreditCardView)| Material |
|[Android-Bootstrap](https://github.com/Bearded-Hen/Android-Bootstrap)| Material |
|[ExoPlayer](https://github.com/google/ExoPlayer)| Media player |
|[PowerMenu](https://github.com/skydoves/PowerMenu)| Menu  |
|[boxing](https://github.com/bilibili/boxing)| Multi media selector  |
|[ahbottomnavigation](https://github.com/aurelhubert/ahbottomnavigation)| Navigation bar  |
|[NiceBottomBar](https://github.com/ibrahimsn98/NiceBottomBar)| Navigation bar  |
|[BottomBar](https://github.com/roughike/BottomBar)| Navigation bar  |
|[AdaptableBottomNavigation](https://github.com/bufferapp/AdaptableBottomNavigation)| Navigation bar  |
|[bubble-navigation](https://github.com/gauravk95/bubble-navigation)| Navigation bar  |
|[BottomNavBar](https://github.com/adib2149/BottomNavBar)| Navigation bar  |
|[lottiebottomnavbar](https://github.com/subsub/lottiebottomnavbar)| Navigation bar  |
|[NiceBottomBar](https://github.com/ibrahimsn98/NiceBottomBar)| Navigation bar  |
|[BottomNavigation](https://github.com/Ashok-Varma/BottomNavigation)| Navigation bar  |
|[Material-BottomNavigation](https://github.com/sephiroth74/Material-BottomNavigation)| Navigation bar  |
|[bubble-navigation](https://github.com/gauravk95/bubble-navigation)| Navigation bar  |
|[morph-bottom-navigation](https://github.com/tommybuonomo/morph-bottom-navigation)| Navigation bar  |
|[BottomNavigationBar](https://github.com/fishwjy/BottomNavigationBar)| Navigation bar  |
|[AwesomeNavigationDrawer](https://github.com/root-ansh/AwesomeNavigationDrawer)| Navigation drawer |
|[duo-navigation-drawer](https://github.com/PSD-Company/duo-navigation-drawer)| Navigation drawer  |
|[Drawer-Behavior](https://github.com/shiburagi/Drawer-Behavior)| Navigation drawer  |
|[material-drawer](https://github.com/heinrichreimer/material-drawer)| Navigation drawer |
|[bubble-navigation](https://github.com/gauravk95/bubble-navigation)| Navigation drawer |
|[ArcNavigationView](https://github.com/rom4ek/ArcNavigationView)| Navigation drawer  |
|[LDrawer](https://github.com/keklikhasan/LDrawer)| Navigation drawer |
|[Custom-Navigation-Drawer](https://github.com/shrikanth7698/Custom-Navigation-Drawer)| Navigation drawer  |
|[SlidingRootNav](https://github.com/yarolegovich/SlidingRootNav)| Navigation drawer  |
|[MaterialDrawerKt](https://github.com/zsmb13/MaterialDrawerKt)| Navigation drawer  |
|[AppCompat-Extension-Library](https://github.com/TR4Android/AppCompat-Extension-Library)| Navigation drawer  |
|[TabDrawer](https://github.com/ashazar/TabDrawer)| Navigation drawer  |
|[NavigationTabStrip](https://github.com/Devlight/NavigationTabStrip)| Navigation Tab  |
|[Alerter](https://github.com/Tapadoo/Alerter)| Notif  |
|[Noty](https://github.com/emre1512/Noty)| Notif |
|[PatternLockView](https://github.com/aritraroy/PatternLockView)| Pattern lock |
|[Android-Font-Awesome](https://github.com/ravi8x/Android-Font-Awesome)| Photo  |
|[Glide](https://github.com/bumptech/glide)| Photo  |
|[Rounded Imageview](https://github.com/vinc3m1/RoundedImageView)| Photo  |
|[android-gpuimage](https://github.com/cats-oss/android-gpuimage)| Photo |
|[Matisse](https://github.com/zhihu/Matisse)| Photo |
|[Android-Image-Picker-and-Cropping](https://github.com/ravi8x/Android-Image-Picker-and-Cropping)| Photo  |
|[android-shape-imageview](https://github.com/siyamed/android-shape-imageview)| Photo |
|[Compressor](https://github.com/zetbaitsu/Compressor)| Photo |
|[Crescento](https://github.com/developer-shivam/crescento)| Photo |
|[DiscreteScrollView](https://github.com/yarolegovich/DiscreteScrollView)| Photo |
|[subsampling-scale-image-view](https://github.com/davemorrissey/subsampling-scale-image-view)| Photo |
|[cropiwa](https://github.com/steelkiwi/cropiwa)| Photo |
|[Easy Image](https://github.com/jkwiecien/EasyImage)| Photo  |
|[CircleImageView](https://github.com/hdodenhof/CircleImageView)| Photo  |
|[Zoomy](https://github.com/imablanco/Zoomy)| Photo |
|[Blurkit Android](https://github.com/CameraKit/blurkit-android)| Photo  |
|[FrescoImageViewer](https://github.com/stfalcon-studio/FrescoImageViewer)| Photo |
|[android-crop](https://github.com/jdamcd/android-crop)| Photo  |
|[Dexter](https://github.com/Karumi/Dexter)| Permissions  |
|[NumberProgressBar](https://github.com/daimajia/NumberProgressBar)| ProgressBar  |
|[CircleProgress](https://github.com/lzyzsd/CircleProgress)| ProgressBar  |
|[CatLoadingView](https://github.com/Rogero0o/CatLoadingView)| ProgressBar  |
|[ShimmerRecyclerView](https://github.com/sharish/ShimmerRecyclerView)| Recycler View  |
|[sensey](https://github.com/nisrulz/sensey)| Sensor |
|[shortbread](https://github.com/MatthiasRobbers/shortbread)| Shortcut  |
|[BubbleShowCase-Android](https://github.com/ECLaboratorio/BubbleShowCase-Android)| Show Case  |
|[MultiLamp](https://github.com/ujwalthote/MultiLamp)| Show Case  |
|[ShowCaseView](https://github.com/mreram/ShowCaseView)| Show Case  |
|[FancyShowCaseView](https://github.com/faruktoptas/FancyShowCaseView)| Show Case  |
|[Hawk](https://github.com/orhanobut/hawk)| Shared preference  |
|[MaterialStepperView](https://github.com/fython/MaterialStepperView)| Stepper |
|[stepper-indicator](https://github.com/badoualy/stepper-indicator)| Stepper |
|[VerticalStepperForm](https://github.com/ernestoyaquello/VerticalStepperForm)| Stepper |
|[Android-SwitchIcon](https://github.com/zagum/Android-SwitchIcon)| Switch (enable/disable)  |
|[StickySwitch](https://github.com/GwonHyeok/StickySwitch)| Switch (enable/disable) |
|[fading-text-view](https://github.com/rosenpin/fading-text-view)| TextView  |
|[Justified TextView](https://github.com/ufo22940268/android-justifiedtextview)| TextView  |
|[RotatingText](https://github.com/mdg-iitr/RotatingText)| TextView |
|[TextSurface](https://github.com/elevenetc/TextSurface)| TextView  |
|[Titanic](https://github.com/RomainPiel/Titanic)| TextView  |
|[ReadMoreTextView](https://github.com/emre1512/Noty)| TextView |
|[MaterialTextField](https://github.com/florent37/MaterialTextField)| TextView  |
|[SingleDateAndTimePicker](https://github.com/florent37/SingleDateAndTimePicker)| Time  |
|[CalendarListview](https://github.com/traex/CalendarListview)| Time  |
|[FlatTimeCollection](https://github.com/anastr/FlatTimeCollection)| Time   |
|[android-times-square](https://github.com/square/android-times-square)| Time  |
|[HijriDatePicker](https://github.com/alhazmy13/HijriDatePicker)| Time |
|[FlipTimerView](https://github.com/anugotta/FlipTimerView)| Time |
|[StyleableToast](https://github.com/Muddz/StyleableToast)| Toast |
|[Toasty](https://github.com/GrenderG/Toasty)| Toast  |
|[MyToast](https://github.com/lopspower/MyToast)| Toast  |
|[TastyToast](https://github.com/yadav-rahul/TastyToast)| Toast |
|[AppUpdater](https://github.com/javiersantos/AppUpdater)| Updater |
|[welcome-android](https://github.com/stephentuso/welcome-android)| Welcome page |
