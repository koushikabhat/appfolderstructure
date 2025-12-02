src/
  api/                     # All API calls
    axiosConfig.js
    authApi.js
    userApi.js
    productApi.js

  assets/                  # Images, fonts, Lottie files
    images/
    icons/
    fonts/
    lottie/

  components/              # Reusable UI components
    Button/
      CustomButton.js
    Input/
      TextInputField.js
    Modals/
    Cards/

  constants/
    colors.js
    fonts.js
    endpoints.js

  hooks/
    useAuth.js
    useNetwork.js

  navigation/
    RootNavigator.js       # Decides Splash → Auth or Home
    AuthStack.js
    AppTabs.js
    HomeStack.js
    OnboardingStack.js

  screens/
    Onboarding/
      IntroScreen.js
      WalkthroughScreen.js

    Splash/
      SplashScreen.js

    Auth/
      LoginScreen.js
      SignupScreen.js
      ForgotPassword.js

    Home/
      HomeScreen.js
      MovieDetails.js

    Profile/
      ProfileScreen.js
      EditProfileScreen.js

  services/
    storage/               # Secure storage
      secureStore.js
    analytics/
      firebaseAnalytics.js
    notifications/
      fcmService.js

  store/                   # Redux Toolkit global store
    auth/
      authSlice.js
      authActions.js
    user/
      userSlice.js
    store.js

  utils/
    validators.js
    helpers.js
    permissions.js
