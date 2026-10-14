# react-native-reanimated evidence

Before/after captures for pull requests to software-mansion/react-native-reanimated.

Each pair is one scene, one device and one run, differing only in the code under test: `before` is `main` at the pull request's base commit, `after` is the pull request's branch. Web pairs are captured in headless Chromium at a 420 px viewport from `apps/web-example`, exported once per variant after building the package. Android pairs are captured on a stock Android emulator at 1140×2400 and 480 dpi from release builds of `apps/fabric-example`, one per variant.
