# PackDiff
> What Did You Pack in My App? A Systematic Analysis of Commercial Android Packers

## Introduction
> PackDiff, a dynamic analysis system to inspect the fine-grained behaviors of commercial packers. By instrumenting the Android system, PackDiff records the runtime behaviors of Android apps (e.g., Linux system call invocations, Java API calls, Binder interactions, etc.), which are further processed to pinpoint the additional sensitive behaviors introduced by packers. 

## Source Code
You can find the source code of PackDiff in the other repositories of this account.

## Usage
You need to build your own kernel and Android system, and flash your device according to Google's guideline.

- [Building Android](https://source.android.com/docs/setup/build/building)
- [Building kernels](https://source.android.com/docs/setup/build/building-kernels)
- [Flashing devices](https://source.android.com/docs/setup/build/running)