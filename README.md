# TricksHints 
There are several solutions,hints and also some tricks about Android in this repository.
I hope this paper would help the programmers' community. 

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
|[Lottie-android](https://github.com/airbnb/lottie-android)| Animation  |
|[Material-Animations](https://github.com/lgvalle/Material-Animations)| Animation  |
|[android-about-page](https://github.com/medyo/android-about-page)| About page  |
|[about-page-android](https://github.com/husaynhakeem/about-page-android)| About page  |
|[MaterialAbout](https://github.com/jrvansuita/MaterialAbout)| About page  |
|[DrawableBadge](https://github.com/minibugdev/DrawableBadge)| Badges  |
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
|[CameraFragment](https://github.com/florent37/CameraFragment)| Camera  |
|[android-hidden-camera](https://github.com/kevalpatel2106/android-hidden-camera)| Camera   |
|20- [Horizontal-Calendar](https://github.com/Mulham-Raee/Horizontal-Calendar)| Calendar  |
|[Sdp](https://github.com/intuit/sdp)| Dimensions  |
|[LovelyDialog](https://github.com/yarolegovich/LovelyDialog)| Dialog  |
|[OmegaRecyclerView](https://github.com/Omega-R/OmegaRecyclerView)| Expandable  |
|[RecyclerViewHelper](https://github.com/BoBoMEe/RecyclerViewHelper)| Expandable  |
|[recyclerview-expandable](https://github.com/hendraanggrian/recyclerview-expandable)| Expandable  |
|[ExpandableSwipeRecyclerView](https://github.com/hyunstyle/ExpandableSwipeRecyclerView)| Expandable  |
|[async-expandable-list](https://github.com/Ericliu001/async-expandable-list)| Expandable  |
|[ExpandableListView](https://github.com/harishsn/ExpandableListView)| Expandable  |
|[ExpandableLayout](https://github.com/traex/ExpandableLayout)| Expandable  |
|[expandit](https://github.com/AmalH/expandit)| Expandable  |
|[NestedExpandableRecyclerView](https://github.com/thejitesh/NestedExpandableRecyclerView)| Expandable  |
|[CounterFab](https://github.com/andremion/CounterFab)| Floating Action Button  |
|[Android-Goldfinger](https://github.com/infinum/Android-Goldfinger)| Fingerprint  |
|[Logger](https://github.com/orhanobut/logger)| Logcat  |
|[Smart location](https://github.com/mrmans0n/smart-location-lib)| Location  |
|[AirLocation](https://github.com/mumayank/AirLocation)| Location  |
|[SwitchButton](https://github.com/KingJA/SwitchButton)| Material  |
|[TapTargetView](https://github.com/KeepSafe/TapTargetView)| Material  |
|[CameraView](https://github.com/natario1/CameraView)| Material  |
|40- [fit-chart](https://github.com/txusballesteros/fit-chart)| Material  |
|[welcome-coordinator](https://github.com/txusballesteros/welcome-coordinator)| Material  |
|[sliding-deck](https://github.com/txusballesteros/sliding-deck)| Material  |
|[DrawerMultiLevelListview](https://github.com/awidiyadew/DrawerMultiLevelListview)| Material  |
|[Material](https://github.com/rey5137/material)| Material  |
|[Calligraphy](https://github.com/chrisjenx/Calligraphy)| Material  |
|[Autocomplete](https://github.com/natario1/Autocomplete)| Material  |
|[GestureViews](https://github.com/alexvasilkov/GestureViews)| Material  |
|[lottiebottomnavbar](https://github.com/subsub/lottiebottomnavbar)| Material  |
|[BoomMenu](https://github.com/Nightonke/BoomMenu)| Material  |
|[MaterialStyledDialogs](https://github.com/javiersantos/MaterialStyledDialogs)| Material  |
|[AppIntro](https://github.com/AppIntro/AppIntro)| Material  |
|[Konfetti](https://github.com/DanielMartinus/Konfetti)| Material  |
|[ShineButton](https://github.com/ChadCSong/ShineButton)| Material  |
|[MyLittleCanvas](https://github.com/florent37/MyLittleCanvas)| Material  |
|[TutoShowcase](https://github.com/florent37/TutoShowcase)| Material  |
|[DiagonalLayout](https://github.com/florent37/DiagonalLayout)| Material  |
|[GlidePalette](https://github.com/florent37/GlidePalette)| Material  |
|[material-menu](https://github.com/balysv/material-menu)| Material  |
|[material-calendarview](https://github.com/prolificinteractive/material-calendarview)| Material  |
|60- [WaveSwipeRefreshLayout](https://github.com/recruit-lifestyle/WaveSwipeRefreshLayout)| Material  |
|[circular-progress-button](https://github.com/dmytrodanylyk/circular-progress-button)**  | Material  |
|[android-slidr](https://github.com/florent37/android-slidr)| Material  |
|[RippleEffect](https://github.com/traex/RippleEffect)| Material  |
|[CircleRefreshLayout](https://github.com/tuesda/CircleRefreshLayout)| Material  |
|[WaveView](https://github.com/gelitenight/WaveView)| Material  |
|[BottomBar](https://github.com/roughike/BottomBar)| Material  |
|[RecyclerRefreshLayout](https://github.com/dinuscxj/RecyclerRefreshLayout)| Material  |
|[AdaptableBottomNavigation](https://github.com/bufferapp/AdaptableBottomNavigation)| Material  |
|[BottomNavBar](https://github.com/adib2149/BottomNavBar)| Material  |
|[PowerMenu](https://github.com/skydoves/PowerMenu)| Menu  |
|[boxing](https://github.com/bilibili/boxing)| Multi media selector  |
|[Alerter](https://github.com/Tapadoo/Alerter)| Notif  |
|[duo-navigation-drawer](https://github.com/PSD-Company/duo-navigation-drawer)| Navigation drawer  |
|[Drawer-Behavior](https://github.com/shiburagi/Drawer-Behavior)| Navigation drawer  |
|[ArcNavigationView](https://github.com/rom4ek/ArcNavigationView)| Navigation drawer  |
|[NavigationTabStrip](https://github.com/Devlight/NavigationTabStrip)| Navigation Tab  |
|[Glide](https://github.com/bumptech/glide)| Photo  |
|[Rounded Imageview](https://github.com/vinc3m1/RoundedImageView)| Photo  |
|[Easy Image](https://github.com/jkwiecien/EasyImage)| Photo  |
|80- [CircleImageView](https://github.com/hdodenhof/CircleImageView)| Photo  |
|[Blurkit Android](https://github.com/CameraKit/blurkit-android)| Photo  |
|[android-crop](https://github.com/jdamcd/android-crop)| Photo  |
|[Dexter](https://github.com/Karumi/Dexter)| Permissions  |
|[NumberProgressBar](https://github.com/daimajia/NumberProgressBar)| ProgressBar  |
|[CircleProgress](https://github.com/lzyzsd/CircleProgress)| ProgressBar  |
|[CatLoadingView](https://github.com/Rogero0o/CatLoadingView)| ProgressBar  |
|[ShimmerRecyclerView](https://github.com/sharish/ShimmerRecyclerView)| Recycler View  |
|[shortbread](https://github.com/MatthiasRobbers/shortbread)| Shortcut  |
|[BubbleShowCase-Android](https://github.com/ECLaboratorio/BubbleShowCase-Android)| Show Case  |
|[MultiLamp](https://github.com/ujwalthote/MultiLamp)| Show Case  |
|[ShowCaseView](https://github.com/mreram/ShowCaseView)| Show Case  |
|[FancyShowCaseView](https://github.com/faruktoptas/FancyShowCaseView)| Show Case  |
|[sensey](https://github.com/nisrulz/sensey)| Sensor   |
|[Hawk](https://github.com/orhanobut/hawk)| Shared preference  |
|[Android-SwitchIcon](https://github.com/zagum/Android-SwitchIcon)| Switch (enable/disable)  |
|[StyleableToast](https://github.com/Muddz/StyleableToast)| Toast  |
|[Toasty](https://github.com/GrenderG/Toasty)| Toast  |
|[MyToast](https://github.com/lopspower/MyToast)| Toast  |
|100- [TextSurface](https://github.com/elevenetc/TextSurface)| TextView  |
|[Titanic](https://github.com/RomainPiel/Titanic)| TextView  |
|[fading-text-view](https://github.com/rosenpin/fading-text-view)| TextView  |
|[Justified TextView](https://github.com/ufo22940268/android-justifiedtextview)| TextView  |
|[MaterialTextField](https://github.com/florent37/MaterialTextField)| TextView  |
|[SingleDateAndTimePicker](https://github.com/florent37/SingleDateAndTimePicker)| Time  |
|[CalendarListview](https://github.com/traex/CalendarListview)| Time  |
|[FlatTimeCollection](https://github.com/anastr/FlatTimeCollection)| Time   |
|[android-times-square](https://github.com/square/android-times-square)| Time  |
|[welcome-android](https://github.com/stephentuso/welcome-android)| Welcome page |
|[android-gpuimage](https://github.com/cats-oss/android-gpuimage)| Photo |
|[ExoPlayer](https://github.com/google/ExoPlayer)| Media player |
|[flexbox-layout](https://github.com/google/flexbox-layout)| Material |
|[Matisse](https://github.com/zhihu/Matisse)| Photo |
|[android-shape-imageview](https://github.com/siyamed/android-shape-imageview)| Photo |
|[Compressor](https://github.com/zetbaitsu/Compressor)| Photo |
|[Crescento](https://github.com/developer-shivam/crescento)| Photo |
|[Android-Bootstrap](https://github.com/Bearded-Hen/Android-Bootstrap)| Material |
|[DiscreteScrollView](https://github.com/yarolegovich/DiscreteScrollView)| Photo |
|[subsampling-scale-image-view](https://github.com/davemorrissey/subsampling-scale-image-view)| Photo |
|[richeditor-android](https://github.com/wasabeef/richeditor-android)| Editor |
|[material-intro-screen](https://github.com/TangoAgency/material-intro-screen)| Intro |
|[CountdownView](https://github.com/iwgang/CountdownView)| Countdown |
|[Noty](https://github.com/emre1512/Noty)| Notif |
|[HijriDatePicker](https://github.com/alhazmy13/HijriDatePicker)| Time |
|[MediaRecorderDialog](https://github.com/alhazmy13/MediaRecorderDialog)| Dialog |
|[easy-rating-dialog](https://github.com/fernandodev/easy-rating-dialog)| Dialog |
|[PatternLockView](https://github.com/aritraroy/PatternLockView)| Pattern lock |
|[Skeleton](https://github.com/ethanhua/Skeleton)| Loading |
|[TastyToast](https://github.com/yadav-rahul/TastyToast)| Toast |
|[MaterialStepperView](https://github.com/fython/MaterialStepperView)| Material |
|[cropiwa](https://github.com/steelkiwi/cropiwa)| Photo |
|[MaterialProgressBar](https://github.com/zhanghai/MaterialProgressBar)| Loading |
|[material-intro](https://github.com/heinrichreimer/material-intro)| Intro |
|[Backboard](https://github.com/tumblr/Backboard)| Animation |
|[FrescoImageViewer](https://github.com/stfalcon-studio/FrescoImageViewer)| Photo |
|[ENViews](https://github.com/codeestX/ENViews)| Loading |
|[RotatingText](https://github.com/mdg-iitr/RotatingText)| TextView |
|[ReadMoreTextView](https://github.com/emre1512/Noty)| TextView |
|[CompactCalendarView](https://github.com/SundeepK/CompactCalendarView)| Calendar |
|[Fetch](https://github.com/tonyofrancis/Fetch)| File Downloader |
|[Zoomy](https://github.com/imablanco/Zoomy)| Photo |
|[MaterialScrollBar](https://github.com/turing-tech/MaterialScrollBar)| Material |
|[CreditCardView](https://github.com/vinaygaba/CreditCardView)| Material |
|[bubble-navigation](https://github.com/gauravk95/bubble-navigation)| Navigation drawer |
|[slideview](https://github.com/emre1512/Noty)| Material |
|[StickySwitch](https://github.com/GwonHyeok/StickySwitch)| Switch (enable/disable) |
|[material-drawer](https://github.com/heinrichreimer/material-drawer)| Navigation drawer |
|[FreeDrawView](https://github.com/RiccardoMoro/FreeDrawView)| Material |
|[UberCarAnimation](https://github.com/amanjeetsingh150/UberCarAnimation)| Animation |
|[GoogleMapsAnimations](https://github.com/aarsy/GoogleMapsAnimations)| Animation |
|[AVLoadingIndicatorView](https://github.com/81813780/AVLoadingIndicatorView)| Animation |
|[HTextView](https://github.com/hanks-zyh/HTextView)| TextView |
|[spruce-android](https://github.com/willowtreeapps/spruce-android)| Animation |
|[FragmentAnimations](https://github.com/kakajika/FragmentAnimations)| Animation |
|[Android-SpinKit](https://github.com/ybq/Android-SpinKit)| Animation |
|[TextViewExpandableAnimation](https://github.com/freecats/TextViewExpandableAnimation)| Animation |
|[LoadingView](https://github.com/ldoublem/LoadingView)| Animation |
|[JJSearchViewAnim](https://github.com/android-cjj/JJSearchViewAnim)| Animation |
|[FlipAnimation](https://github.com/4xes/FlipAnimation)| Animation |
|[LDrawer](https://github.com/keklikhasan/LDrawer)| Navigation drawer |


