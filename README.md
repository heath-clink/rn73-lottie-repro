Template app on RN 0.73.1 with lottie-react-native added.

# Setup

```bash
yarn install
yarn pod-fabric

#### Or one of these:
#  yarn pod-legacy          # new architecture not enabled
#  yarn pod-fabric-static   # USE_FRAMEWORKS=static
#  yarn pod-fabric-dynamic  # USE_FRAMEWORKS=dynamic

yarn ios
```

Now incorporates the change from https://github.com/lottie-react-native/lottie-react-native/pull/1139

The app contains a LottieView to test functionality.

Note that when `yarn pod-fabric-dynamic` is used, a LottieView displays as if it is a legacy
component (pink box with "Unimplemented component").
