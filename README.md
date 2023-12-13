Template app on RN 0.73.0 with lottie-react-native added.
iOS build fails when new architecture is enabled.

# Setup

```bash
yarn install
yarn pod-fabric     # or yarn pod-legacy
yarn ios
```

iOS build will fail if `RCT_NEW_ARCH_ENABLED=1` (i.e., you use `yarn pod-fabric`)

