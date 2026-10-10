---
title: Open Source Licenses
locale: en
---

<!-- markdownlint-disable MD034 -->

<!-- markdownlint-disable-next-line MD025 -->
# Open Source Licenses

Shuffleep uses the open source software and fonts listed below. We thank each copyright holder.

This page covers the **105 software packages bundled into the app's JavaScript code**, the bundled fonts, and the **native libraries and Java / Kotlin libraries bundled into the Android app**. Development tools used only at build time are not listed, because they are not part of the distribution.

The list is checked against the Android release build (the JavaScript source map, the native libraries in the APK, and the Gradle dependencies). It will be updated to reflect the iOS build once that version ships.

Last updated: 2026-10-01

## Bundled fonts

### Manrope

- License: OFL-1.1
- Copyright 2019 The Manrope Project Authors (https://github.com/sharanda/manrope)
- SIL OFL 1.1 confirmed in the ttf name table (nameID 13 / 14). Bundled unmodified.

### Inter

- License: OFL-1.1
- Copyright 2020 The Inter Project Authors (https://github.com/rsms/inter)
- SIL OFL 1.1 confirmed in the ttf name table (nameID 13 / 14). Bundled unmodified.

### Roboto (roboto_medium_numbers)

- License: Apache-2.0
- Copyright 2011 Google Inc. All Rights Reserved.
- Bundled as an Android native resource by AndroidX Media3 UI (via `expo-audio`); it does not appear in the JS bundle.

## Software packages

### MIT (99)

- `@babel/runtime` — Copyright (c) 2014-present Sebastian McKenzie and other contributors
- `@expo-google-fonts/inter` — Copyright Expo Team <team@expo.io>
- `@expo-google-fonts/manrope` — Copyright Expo Team <team@expo.io>
- `@expo/cli` — Copyright Expo
- `@expo/metro-runtime` — Copyright 650 Industries, Inc.
- `@formatjs/bigdecimal` — Copyright (c) 2026 FormatJS
- `@formatjs/fast-memoize` — Copyright (c) 2023 FormatJS
- `@formatjs/intl-localematcher` — Copyright (c) 2023 FormatJS
- `@formatjs/intl-pluralrules` — Copyright (c) 2023 FormatJS
- `@radix-ui/react-compose-refs` — Copyright (c) 2022 WorkOS
- `@radix-ui/react-slot` — Copyright (c) 2022 WorkOS
- `@react-native-async-storage/async-storage` — Copyright (c) 2015-present, Facebook, Inc.
- `@react-native/assets-registry` — Copyright (c) Meta Platforms, Inc. and affiliates.
- `@react-native/js-polyfills` — Copyright (c) Meta Platforms, Inc. and affiliates.
- `@react-native/normalize-colors` — Copyright (c) Meta Platforms, Inc. and affiliates.
- `@react-native/virtualized-lists` — Copyright (c) Meta Platforms, Inc. and affiliates.
- `@react-navigation/bottom-tabs` — Copyright (c) 2017 React Navigation Contributors
- `@react-navigation/core` — Copyright (c) 2017 React Navigation Contributors
- `@react-navigation/elements` — Copyright (c) 2017 React Navigation Contributors
- `@react-navigation/native` — Copyright (c) 2017 React Navigation Contributors
- `@react-navigation/native-stack` — Copyright (c) 2017 React Navigation Contributors
- `@react-navigation/routers` — Copyright (c) 2017 React Navigation Contributors
- `@revenuecat/purchases-js-hybrid-mappings` — Copyright RevenueCat, Inc.
- `@revenuecat/purchases-typescript-internal` — Copyright RevenueCat, Inc.
- `@shopify/react-native-skia` — Copyright 2021-present, Shopify Inc.
- `abort-controller` — Copyright (c) 2017 Toru Nagashima
- `base64-js` — Copyright (c) 2014 Jameson Little
- `color` — Copyright (c) 2012 Heather Arthur
- `color-convert` — Copyright (c) 2011-2016 Heather Arthur <fayearthur@gmail.com>
- `color-name` — Copyright (c) 2015 Dmitry Ivanov
- `color-string` — Copyright (c) 2011 Heather Arthur <fayearthur@gmail.com>
- `decode-uri-component` — Copyright (c) 2017, Sam Verschueren <sam.verschueren@gmail.com> (github.com/SamVerschueren)
- `dequal` — Copyright (c) Luke Edwards <luke.edwards05@gmail.com> (lukeed.com)
- `escape-string-regexp` — Copyright (c) Sindre Sorhus <sindresorhus@gmail.com> (https://sindresorhus.com)
- `event-target-shim` — Copyright (c) 2015 Toru Nagashima
- `expo` — Copyright Expo
- `expo-application` — Copyright 650 Industries, Inc.
- `expo-asset` — Copyright 650 Industries, Inc.
- `expo-audio` — Copyright 650 Industries, Inc.
- `expo-constants` — Copyright 650 Industries, Inc.
- `expo-device` — Copyright 650 Industries, Inc.
- `expo-file-system` — Copyright 650 Industries, Inc.
- `expo-font` — Copyright 650 Industries, Inc.
- `expo-glass-effect` — Copyright 650 Industries, Inc.
- `expo-intent-launcher` — Copyright 650 Industries, Inc.
- `expo-linear-gradient` — Copyright 650 Industries, Inc.
- `expo-linking` — Copyright 650 Industries, Inc.
- `expo-localization` — Copyright 650 Industries, Inc.
- `expo-modules-core` — Copyright 650 Industries, Inc.
- `expo-network` — Copyright 650 Industries, Inc.
- `expo-notifications` — Copyright 650 Industries, Inc.
- `expo-router` — Copyright 650 Industries, Inc.
- `expo-splash-screen` — Copyright 650 Industries, Inc.
- `expo-status-bar` — Copyright 650 Industries, Inc.
- `expo-symbols` — Copyright 650 Industries, Inc.
- `expo-updates` — Copyright 650 Industries, Inc.
- `expo-web-browser` — Copyright 650 Industries, Inc.
- `fast-deep-equal` — Copyright (c) 2017 Evgeny Poberezkin
- `fflate` — Copyright (c) 2026 Arjun Barrett
- `filter-obj` — Copyright (c) Sindre Sorhus <sindresorhus@gmail.com> (sindresorhus.com)
- `flow-enums-runtime` — Copyright (c) Facebook, Inc. and its affiliates.
- `html-parse-stringify` — Copyright Henrik Joreteg <henrik@joreteg.com>
- `i18next` — Copyright (c) 2024 i18next
- `invariant` — Copyright (c) 2013-present, Facebook, Inc.
- `is-arrayish` — Copyright (c) 2015 JD Ballard
- `memoize-one` — Copyright (c) 2019 Alexander Reardon
- `nanoid` — Copyright 2017 Andrey Sitnik <andrey@sitnik.ru>
- `nullthrows` — Copyright (c) 2016 Andres Suarez
- `promise` — Copyright (c) 2014 Forbes Lindesay
- `query-string` — Copyright (c) Sindre Sorhus <sindresorhus@gmail.com> (http://sindresorhus.com)
- `react` — Copyright (c) Meta Platforms, Inc. and affiliates.
- `react-freeze` — Copyright (c) 2021 Software Mansion
- `react-i18next` — Copyright (c) 2025 i18next
- `react-is` — Copyright (c) Facebook, Inc. and its affiliates.
- `react-native` — Copyright (c) Meta Platforms, Inc. and affiliates.
- `react-native-audio-api` — Copyright Software Mansion (https://github.com/software-mansion)
- `react-native-gesture-handler` — Copyright (c) 2016 Software Mansion <swmansion.com>
- `react-native-is-edge-to-edge` — Copyright (c) 2024 Mathieu Acthernoene
- `react-native-purchases` — Copyright (c) 2023 RevenueCat
- `react-native-reanimated` — Copyright (c) 2016 Software Mansion <swmansion.com>
- `react-native-safe-area-context` — Copyright (c) 2019 Th3rd Wave
- `react-native-screens` — Copyright (c) 2018 Software Mansion <swmansion.com>
- `react-native-svg` — Copyright (c) [2015-2016] [Horcrux]
- `react-native-worklets` — Copyright (c) 2024 nobody
- `react-reconciler` — Copyright (c) Meta Platforms, Inc. and affiliates.
- `regenerator-runtime` — Copyright (c) 2014-present, Facebook, Inc.
- `scheduler` — Copyright (c) Meta Platforms, Inc. and affiliates.
- `simple-swizzle` — Copyright (c) 2015 Josh Junon
- `split-on-first` — Copyright (c) Sindre Sorhus <sindresorhus@gmail.com> (sindresorhus.com)
- `stacktrace-parser` — Copyright (c) 2014-2019 Georg Tavonius
- `strict-uri-encode` — Copyright (c) Kevin Martensson <kevinmartensson@gmail.com> (github.com/kevva)
- `use-deep-compare-effect` — Copyright (c) 2020 Kent C. Dodds
- `use-latest-callback` — Copyright (c) 2023 Satyajit Sahoo
- `use-sync-external-store` — Copyright (c) Meta Platforms, Inc. and affiliates.
- `void-elements` — Copyright (c) 2014 hemanth
- `warn-once` — Copyright (c) 2022 Satyajit Sahoo
- `whatwg-fetch` — Copyright (c) 2014-2023 GitHub, Inc.
- `whatwg-url-minimum` — Copyright (c) Phil Pluckthun, / Copyright (c) 650 Industries, Inc. (aka Expo), / Copyright (c) Sebastian Mayr
- `zustand` — Copyright (c) 2019 Paul Henschel

### Apache-2.0 (2)

- `@iabtcf/core` — Copyright 2019 IAB Technology Laboratory, Inc
- `react-native-google-mobile-ads` — Copyright (c) 2021-present Invertase Limited <oss@invertase.io> / Copyright (c) 2016-present Invertase Limited <oss@invertase.io>

### ISC (2)

- `@ungap/structured-clone` — Copyright (c) 2021, Andrea Giammarchi, @WebReflection
- `semver` — Copyright (c) Isaac Z. Schlueter and Contributors

### MIT AND Apache-2.0 (1)

- `@expo-google-fonts/material-symbols` — Copyright (c) 2020 Expo
  - Only the code portion (MIT) is bundled; the Apache-2.0 Material Symbols fonts are not included.

### BSD-3-Clause (1)

- `hoist-non-react-statics` — Copyright (c) 2015, Yahoo! Inc. All rights reserved.

## Android native libraries and Java / Kotlin libraries

### {fmt}

- License: MIT
- Copyright (c) 2012 - present, Victor Zverovich and {fmt} contributors
- String formatting inside React Native.

### Adobe DNG SDK

- License: LicenseRef-Adobe-DNG-SDK
- This product includes DNG technology under license by Adobe Systems Incorporated.
- RAW image (DNG) processing inside Skia.

### Android NDK cpufeatures

- License: BSD-2-Clause
- Copyright (C) 2010 The Android Open Source Project
- All rights reserved.
- CPU feature detection inside Skia.

### AndroidX (Android Jetpack)

- License: Apache-2.0
- Copyright (C) The Android Open Source Project
- Android support libraries for UI, lifecycle, storage, and more (including `libdatastore_shared_counter` from DataStore).

### AndroidX Media3

- License: Apache-2.0
- Copyright (C) 2016 The Android Open Source Project
- Audio playback and media sessions.

### Apache Commons Codec

- License: Apache-2.0
- Apache Commons Codec
- Copyright 2002-2014 The Apache Software Foundation
- This product includes software developed at
- The Apache Software Foundation (http://www.apache.org/).
- Copyright (C) 2002 Kevin Atkinson (kevina@gnu.org)
- Copyright (c) 2008 Alexander Beider & Stephen P. Morse.
- Hashing and hex conversion (expo-file-system).

### Apache Commons IO

- License: Apache-2.0
- Apache Commons IO
- Copyright 2001-2008 The Apache Software Foundation
- This product includes software developed by
- The Apache Software Foundation (http://www.apache.org/).
- File utilities (expo-file-system).

### audio-stretch

- License: BSD-3-Clause
- Copyright (c) David Bryant
- All rights reserved.
- Time stretching inside React Native Audio API.

### base64 (René Nyffenegger)

- License: Zlib
- Copyright (C) 2004-2017, 2020-2022 René Nyffenegger
- Copyright (C) 2023 Kevin Heifner
- Base64 conversion inside React Native Audio API.

### Bolts (bolts-tasks)

- License: BSD-3-Clause
- Copyright (c) 2013-present, Facebook, Inc. All rights reserved.
- Task handling used by Fresco (with Facebook's additional patent grant, PATENTS).

### Bouncy Castle

- License: MIT
- Copyright (c) 2000-2023 The Legion of the Bouncy Castle Inc. (https://www.bouncycastle.org)
- Cryptography library used to verify OTA update signatures (expo-updates).

### Brotli (Java decoder)

- License: MIT
- Copyright (c) 2009, 2010, 2013-2016 by the Brotli Authors.
- Brotli decompression for OTA updates (expo-updates).

### bsdiff / bspatch

- License: BSD-2-Clause
- Copyright 2003-2005 Colin Percival
- All rights reserved
- Applies OTA update patches (expo-updates).

### bzip2 / libbzip2

- License: bzip2-1.0.6
- This program, "bzip2", the associated library "libbzip2", and all
- documentation, are copyright (C) 1996-2019 Julian R Seward.  All
- rights reserved.
- Decompresses OTA update patches (expo-updates).

### Chromium WebView support library boundary interfaces (in AndroidX WebKit)

- License: BSD-3-Clause
- Copyright 2018 The Chromium Authors
- Boundary interfaces bundled inside AndroidX WebKit.

### CSS Color Parser

- License: MIT
- (c) Dean McNamee <dean@gmail.com>, 2012.
- C++ port by Mapbox, Konstantin Käfer <mail@kkaefer.com>, 2014-2017.
- Color parsing inside React Native Skia.

### Device Year Class

- License: BSD-3-Clause
- Copyright (c) 2015, Facebook, Inc. All rights reserved.
- Estimates the device performance class (expo-device; with Facebook's additional patent grant, PATENTS).

### double-conversion

- License: BSD-3-Clause
- Copyright 2006-2011, the V8 project authors. All rights reserved.
- Number conversion inside React Native.

### dtoa (David M. Gay)

- License: dtoa
- The author of this software is David M. Gay.
- Copyright (c) 1991, 2000, 2001 by Lucent Technologies.
- Number-to-string conversion inside Hermes.

### Expat

- License: MIT
- Copyright (c) 1998-2000 Thai Open Source Software Center Ltd and Clark Cooper
- Copyright (c) 2001-2025 Expat maintainers
- XML parsing inside Skia.

### Expo (native modules)

- License: MIT
- Copyright (c) 2015-present 650 Industries, Inc. (aka Expo)
- The Expo native foundation and the Android parts of each module (bundled with the npm expo-* packages).

### fast_float

- License: MIT
- Copyright (c) 2021 The fast_float authors
- Number parsing inside React Native (licensed under Apache-2.0, MIT, or BSL-1.0; MIT is chosen).

### fbjni

- License: Apache-2.0
- Copyright (c) Facebook, Inc. and its affiliates.
- JNI helpers between C++ and Java.

### Firebase Android SDK

- License: Apache-2.0
- Copyright 2020 Google LLC
- Firebase common and data transport components used by expo-notifications.

### Folly

- License: Apache-2.0
- Copyright (c) Meta Platforms, Inc. and affiliates.
- C++ utilities used by React Native.

### FreeType

- License: FTL
- Portions of this software are copyright © 2024 The FreeType Project (https://freetype.org).  All rights reserved.
- Copyright 1996-2002, 2006 by David Turner, Robert Wilhelm, and Werner Lemberg
- Font rendering inside Skia.

### Fresco

- License: MIT
- Copyright (c) Meta Platforms, Inc. and affiliates.
- The React Native image pipeline.

### glog

- License: BSD-3-Clause
- Copyright (c) 2008, Google Inc.
- Logging inside React Native.

### Gson

- License: Apache-2.0
- Copyright 2008 Google Inc.
- JSON library.

### Guava

- License: Apache-2.0
- Copyright (C) 2011 The Guava Authors
- Google core libraries.

### HarfBuzz

- License: MIT-Modern-Variant
- Copyright © 2010-2022  Google, Inc.
- Copyright © 2015-2020  Ebrahim Byagowi
- Copyright © 2019,2020  Facebook, Inc.
- Copyright © 2012,2015  Mozilla Foundation
- Copyright © 2011  Codethink Limited
- Copyright © 2008,2010  Nokia Corporation and/or its subsidiary(-ies)
- Copyright © 2009  Keith Stribley
- Copyright © 2011  Martin Hosken and SIL International
- Copyright © 2007  Chris Wilson
- Copyright © 2005,2006,2020,2021,2022,2023  Behdad Esfahbod
- Copyright © 2004,2007,2008,2009,2010,2013,2021,2022,2023  Red Hat, Inc.
- Copyright © 1998-2005  David Turner and Werner Lemberg
- Copyright © 2016  Igalia S.L.
- Copyright © 2022  Matthias Clasen
- Copyright © 2018,2021  Khaled Hosny
- Copyright © 2018,2019,2020  Adobe, Inc
- Copyright © 2013-2015  Alexei Podtelezhnikov
- Text shaping inside Skia.

### Hermes

- License: MIT
- Copyright (c) Meta Platforms, Inc. and affiliates.
- JavaScript engine.

### JSR-330 (javax.inject)

- License: Apache-2.0
- Copyright (C) 2009 The JSR-330 Expert Group
- Dependency injection annotations.

### Kotlin

- License: Apache-2.0
- Kotlin Compiler
- Copyright 2010-2024 JetBrains s.r.o and respective authors and developers
- Kotlin runtime libraries.

### kotlinx.coroutines

- License: Apache-2.0
- kotlinx.coroutines library.
- Copyright 2016-2025 JetBrains s.r.o and contributors
- Kotlin coroutines.

### kotlinx.serialization

- License: Apache-2.0
- kotlinx.serialization library.
- Copyright 2017-2019 JetBrains s.r.o and respective authors and developers
- Kotlin serialization.

### libjpeg-turbo

- License: IJG AND BSD-3-Clause AND Zlib
- This software is based in part on the work of the Independent JPEG Group.
- Copyright (C)2009-2024 D. R. Commander.  All Rights Reserved.
- Copyright (C)2015 Viktor Szathmáry.  All Rights Reserved.
- This software is copyright (C) 1991-2020, Thomas G. Lane, Guido Vollbeding.
- JPEG processing inside Skia and Fresco.

### libpng

- License: libpng-2.0
- Copyright (c) 1995-2025 The PNG Reference Library Authors.
- Copyright (c) 2018-2025 Cosmin Truta.
- Copyright (c) 2000-2002, 2004, 2006-2018 Glenn Randers-Pehrson.
- Copyright (c) 1996-1997 Andreas Dilger.
- Copyright (c) 1995-1996 Guy Eric Schalnat, Group 42, Inc.
- PNG processing inside Skia.

### libwebp

- License: BSD-3-Clause
- Copyright (c) 2010, Google Inc. All rights reserved.
- WebP processing inside Skia (with Google's additional patent grant, PATENTS).

### LLVM (libc++ / libc++abi / libunwind, llvh in Hermes)

- License: Apache-2.0 WITH LLVM-exception
- Copyright (c) 2003-2019 University of Illinois at Urbana-Champaign.
- Copyright (c) 2009-2019 by the contributors listed in CREDITS.TXT
- The C++ standard library (the Android NDK `libc++_shared` and the copies linked statically into other libraries) and the LLVM-derived code inside Hermes.

### Material Components for Android

- License: Apache-2.0
- Copyright (C) 2017 The Android Open Source Project
- Material Design UI components.

### miniaudio

- License: MIT-0
- Copyright 2023 David Reid
- Audio decoding inside React Native Audio API (licensed under the Unlicense or MIT-0; MIT-0 is chosen).

### Oboe

- License: Apache-2.0
- Copyright (C) 2016 The Android Open Source Project
- Low-latency audio output.

### OkHttp

- License: Apache-2.0
- Copyright 2019 Square, Inc.
- HTTP client.

### Okio

- License: Apache-2.0
- Copyright 2013 Square, Inc.
- I/O library for OkHttp.

### Ooura FFT

- License: LicenseRef-Ooura
- Copyright(C) 1996-2001 Takuya OOURA
- FFT inside r8brain.

### Opus / Opusfile / Ogg / Vorbis (Xiph.Org)

- License: BSD-3-Clause
- Copyright 2001-2023 Xiph.Org, Skype Limited, Octasic,
- Jean-Marc Valin, Timothy B. Terriberry,
- CSIRO, Gregory Maxwell, Mark Borgerding,
- Erik de Castro Lopo, Mozilla, Amazon
- Copyright (c) 1994-2013 Xiph.Org Foundation and contributors
- Copyright (c) 2002, Xiph.org Foundation
- Copyright (c) 2002-2020 Xiph.org Foundation
- Ogg Opus / Ogg Vorbis decoding inside React Native Audio API.

### PFFFT

- License: LicenseRef-FFTPACK
- Copyright (c) 2013  Julien Pommier ( pommier@modartt.com )
- Copyright (c) 2004 the University Corporation for Atmospheric Research ("UCAR"). All rights reserved.
- Copyright (c) 2020  Hayati Ayguen ( h_ayguen@web.de )
- Copyright (c) 2020  Dario Mambro ( dario.mambro@gmail.com )
- FFT inside React Native Audio API.

### piex

- License: Apache-2.0
- Copyright 2015 Google Inc.
- RAW image preview extraction inside Skia.

### Protocol Buffers (in AndroidX DataStore)

- License: BSD-3-Clause
- Copyright 2008 Google Inc.  All rights reserved.
- Serialization repackaged inside AndroidX DataStore.

### Protocol Buffers for Java (in kotlin-reflect)

- License: BSD-3-Clause
- Copyright 2008, Google Inc.
- All rights reserved.
- Serialization bundled inside kotlin-reflect.

### Public Suffix List (in OkHttp)

- License: MPL-2.0
- Note that publicsuffixes.gz is compiled from The Public Suffix List:
- https://publicsuffix.org/list/public_suffix_list.dat
- It is subject to the terms of the Mozilla Public License, v. 2.0:
- https://mozilla.org/MPL/2.0/
- Domain data bundled with OkHttp (`publicsuffixes.gz`).

### r8brain-free-src

- License: MIT
- r8brain-free-src Copyright (c) 2013-2025 Aleksey Vaneev
- Resampler inside React Native Audio API.

### React Native (Android)

- License: MIT
- Copyright (c) Meta Platforms, Inc. and affiliates.
- The React Native runtime (including Yoga and JSI). `libappmodules` holds the app template and the generated code of each library; their notices are in the Software packages section above.

### React Native Audio API

- License: MIT
- Copyright (c) 2024 Software Mansion
- Native parts of the audio playback engine.

### React Native Reanimated / React Native Gesture Handler

- License: MIT
- Copyright (c) 2016 Software Mansion <swmansion.com>
- Native parts of animations and gestures.

### React Native Screens

- License: MIT
- Copyright (c) 2018 Software Mansion <swmansion.com>
- Native parts of screen navigation.

### React Native Skia

- License: MIT
- Copyright 2021-present, Shopify Inc.
- Wrapper for 2D graphics.

### React Native Worklets

- License: MIT
- Copyright (c) 2024 nobody
- Native parts for running JavaScript on other threads.

### react-native-safe-area-context

- License: MIT
- Copyright (c) 2019 Th3rd Wave
- Generated code for safe areas.

### react-native-svg

- License: MIT
- Copyright (c) [2015-2016] [Horcrux]
- Generated code for SVG rendering.

### RevenueCat Purchases

- License: MIT
- Copyright (c) 2018 RevenueCat, Inc.
- Copyright (c) 2019 RevenueCat, Inc.
- In-app purchases.

### ShortcutBadger

- License: Apache-2.0
- Copyright 2014 Leo Lin
- App icon badges (expo-notifications).

### Signalsmith Stretch

- License: MIT
- Copyright (c) 2022 Geraint Luff / Signalsmith Audio Ltd.
- Time stretching inside React Native Audio API.

### Skia

- License: BSD-3-Clause
- Copyright (c) 2011 Google Inc. All rights reserved.
- 2D graphics library.

### SoLoader

- License: Apache-2.0
- Copyright (c) Meta Platforms, Inc. and affiliates.
- Native library loader.

### ThreadSafeQueue (Juan Palacios)

- License: BSD-2-Clause
- Copyright (c) 2013 Juan Palacios juan.palacios.puyana@gmail.com
- Queue implementation inside Worklets.

### Tink

- License: Apache-2.0
- Copyright 2017 Google Inc.
- Cryptography library (RevenueCat).

### WebKit / Chromium Web Audio

- License: BSD-3-Clause AND BSD-2-Clause
- Copyright (C) 2010 Google Inc. All rights reserved.
- Copyright (C) 2012 Google Inc. All rights reserved.
- Copyright 2016 The Chromium Authors. All rights reserved.
- Copyright (C) 2020 Apple Inc. All rights reserved.
- Copyright (C) 2010, Google Inc. All rights reserved.
- Copyright (C) 2020, Apple Inc. All rights reserved.
- Filters and waveform generation inside React Native Audio API.

### Wuffs

- License: Apache-2.0
- Copyright 2017 The Wuffs Authors.
- GIF decoding inside Skia.

### zlib (Chromium)

- License: Zlib AND BSD-3-Clause
- Copyright (C) 1995-2022 Jean-loup Gailly and Mark Adler
- Copyright 2017 The Chromium Authors
- Compression inside Skia (with Chromium optimizations).

The following SDKs are also bundled. They are not open source and are provided under the terms of their providers (Google and Amazon): Google Mobile Ads SDK, Google User Messaging Platform, Google Play services, Firebase (firebase-iid-interop, firebase-measurement-connector), Google Play Billing Library, Play Install Referrer Library, Play Age Signals API / Play Core / HSDP, Amazon Appstore SDK. The notices for the open source software included in the Google SDKs are on [a separate page](/shuffleep/licenses-google-sdk.html).

## License texts

### Apache-2.0

```text
                                 Apache License
                           Version 2.0, January 2004
                        http://www.apache.org/licenses/

   TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

   1. Definitions.

      "License" shall mean the terms and conditions for use, reproduction,
      and distribution as defined by Sections 1 through 9 of this document.

      "Licensor" shall mean the copyright owner or entity authorized by
      the copyright owner that is granting the License.

      "Legal Entity" shall mean the union of the acting entity and all
      other entities that control, are controlled by, or are under common
      control with that entity. For the purposes of this definition,
      "control" means (i) the power, direct or indirect, to cause the
      direction or management of such entity, whether by contract or
      otherwise, or (ii) ownership of fifty percent (50%) or more of the
      outstanding shares, or (iii) beneficial ownership of such entity.

      "You" (or "Your") shall mean an individual or Legal Entity
      exercising permissions granted by this License.

      "Source" form shall mean the preferred form for making modifications,
      including but not limited to software source code, documentation
      source, and configuration files.

      "Object" form shall mean any form resulting from mechanical
      transformation or translation of a Source form, including but
      not limited to compiled object code, generated documentation,
      and conversions to other media types.

      "Work" shall mean the work of authorship, whether in Source or
      Object form, made available under the License, as indicated by a
      copyright notice that is included in or attached to the work
      (an example is provided in the Appendix below).

      "Derivative Works" shall mean any work, whether in Source or Object
      form, that is based on (or derived from) the Work and for which the
      editorial revisions, annotations, elaborations, or other modifications
      represent, as a whole, an original work of authorship. For the purposes
      of this License, Derivative Works shall not include works that remain
      separable from, or merely link (or bind by name) to the interfaces of,
      the Work and Derivative Works thereof.

      "Contribution" shall mean any work of authorship, including
      the original version of the Work and any modifications or additions
      to that Work or Derivative Works thereof, that is intentionally
      submitted to Licensor for inclusion in the Work by the copyright owner
      or by an individual or Legal Entity authorized to submit on behalf of
      the copyright owner. For the purposes of this definition, "submitted"
      means any form of electronic, verbal, or written communication sent
      to the Licensor or its representatives, including but not limited to
      communication on electronic mailing lists, source code control systems,
      and issue tracking systems that are managed by, or on behalf of, the
      Licensor for the purpose of discussing and improving the Work, but
      excluding communication that is conspicuously marked or otherwise
      designated in writing by the copyright owner as "Not a Contribution."

      "Contributor" shall mean Licensor and any individual or Legal Entity
      on behalf of whom a Contribution has been received by Licensor and
      subsequently incorporated within the Work.

   2. Grant of Copyright License. Subject to the terms and conditions of
      this License, each Contributor hereby grants to You a perpetual,
      worldwide, non-exclusive, no-charge, royalty-free, irrevocable
      copyright license to reproduce, prepare Derivative Works of,
      publicly display, publicly perform, sublicense, and distribute the
      Work and such Derivative Works in Source or Object form.

   3. Grant of Patent License. Subject to the terms and conditions of
      this License, each Contributor hereby grants to You a perpetual,
      worldwide, non-exclusive, no-charge, royalty-free, irrevocable
      (except as stated in this section) patent license to make, have made,
      use, offer to sell, sell, import, and otherwise transfer the Work,
      where such license applies only to those patent claims licensable
      by such Contributor that are necessarily infringed by their
      Contribution(s) alone or by combination of their Contribution(s)
      with the Work to which such Contribution(s) was submitted. If You
      institute patent litigation against any entity (including a
      cross-claim or counterclaim in a lawsuit) alleging that the Work
      or a Contribution incorporated within the Work constitutes direct
      or contributory patent infringement, then any patent licenses
      granted to You under this License for that Work shall terminate
      as of the date such litigation is filed.

   4. Redistribution. You may reproduce and distribute copies of the
      Work or Derivative Works thereof in any medium, with or without
      modifications, and in Source or Object form, provided that You
      meet the following conditions:

      (a) You must give any other recipients of the Work or
          Derivative Works a copy of this License; and

      (b) You must cause any modified files to carry prominent notices
          stating that You changed the files; and

      (c) You must retain, in the Source form of any Derivative Works
          that You distribute, all copyright, patent, trademark, and
          attribution notices from the Source form of the Work,
          excluding those notices that do not pertain to any part of
          the Derivative Works; and

      (d) If the Work includes a "NOTICE" text file as part of its
          distribution, then any Derivative Works that You distribute must
          include a readable copy of the attribution notices contained
          within such NOTICE file, excluding those notices that do not
          pertain to any part of the Derivative Works, in at least one
          of the following places: within a NOTICE text file distributed
          as part of the Derivative Works; within the Source form or
          documentation, if provided along with the Derivative Works; or,
          within a display generated by the Derivative Works, if and
          wherever such third-party notices normally appear. The contents
          of the NOTICE file are for informational purposes only and
          do not modify the License. You may add Your own attribution
          notices within Derivative Works that You distribute, alongside
          or as an addendum to the NOTICE text from the Work, provided
          that such additional attribution notices cannot be construed
          as modifying the License.

      You may add Your own copyright statement to Your modifications and
      may provide additional or different license terms and conditions
      for use, reproduction, or distribution of Your modifications, or
      for any such Derivative Works as a whole, provided Your use,
      reproduction, and distribution of the Work otherwise complies with
      the conditions stated in this License.

   5. Submission of Contributions. Unless You explicitly state otherwise,
      any Contribution intentionally submitted for inclusion in the Work
      by You to the Licensor shall be under the terms and conditions of
      this License, without any additional terms or conditions.
      Notwithstanding the above, nothing herein shall supersede or modify
      the terms of any separate license agreement you may have executed
      with Licensor regarding such Contributions.

   6. Trademarks. This License does not grant permission to use the trade
      names, trademarks, service marks, or product names of the Licensor,
      except as required for reasonable and customary use in describing the
      origin of the Work and reproducing the content of the NOTICE file.

   7. Disclaimer of Warranty. Unless required by applicable law or
      agreed to in writing, Licensor provides the Work (and each
      Contributor provides its Contributions) on an "AS IS" BASIS,
      WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or
      implied, including, without limitation, any warranties or conditions
      of TITLE, NON-INFRINGEMENT, MERCHANTABILITY, or FITNESS FOR A
      PARTICULAR PURPOSE. You are solely responsible for determining the
      appropriateness of using or redistributing the Work and assume any
      risks associated with Your exercise of permissions under this License.

   8. Limitation of Liability. In no event and under no legal theory,
      whether in tort (including negligence), contract, or otherwise,
      unless required by applicable law (such as deliberate and grossly
      negligent acts) or agreed to in writing, shall any Contributor be
      liable to You for damages, including any direct, indirect, special,
      incidental, or consequential damages of any character arising as a
      result of this License or out of the use or inability to use the
      Work (including but not limited to damages for loss of goodwill,
      work stoppage, computer failure or malfunction, or any and all
      other commercial damages or losses), even if such Contributor
      has been advised of the possibility of such damages.

   9. Accepting Warranty or Additional Liability. While redistributing
      the Work or Derivative Works thereof, You may choose to offer,
      and charge a fee for, acceptance of support, warranty, indemnity,
      or other liability obligations and/or rights consistent with this
      License. However, in accepting such obligations, You may act only
      on Your own behalf and on Your sole responsibility, not on behalf
      of any other Contributor, and only if You agree to indemnify,
      defend, and hold each Contributor harmless for any liability
      incurred by, or claims asserted against, such Contributor by reason
      of your accepting any such warranty or additional liability.

   END OF TERMS AND CONDITIONS

   APPENDIX: How to apply the Apache License to your work.

      To apply the Apache License to your work, attach the following
      boilerplate notice, with the fields enclosed by brackets "{}"
      replaced with your own identifying information. (Don't include
      the brackets!)  The text should be enclosed in the appropriate
      comment syntax for the file format. We also recommend that a
      file or class name and description of purpose be included on the
      same "printed page" as the copyright notice for easier
      identification within third-party archives.

   Copyright {yyyy} {name of copyright owner}

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```

### BSD-2-Clause

```text
Copyright (c) <year> <owner>

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```

### BSD-3-Clause

```text
Software License Agreement (BSD License)
========================================

Copyright (c) <year> <copyright holders>
----------------------------------------------------

Redistribution and use of this software in source and binary forms, with or
without modification, are permitted provided that the following conditions are
met:

  * Redistributions of source code must retain the above copyright notice, this
    list of conditions and the following disclaimer.
  * Redistributions in binary form must reproduce the above copyright notice,
    this list of conditions and the following disclaimer in the documentation
    and/or other materials provided with the distribution.
  * Neither the name of Yahoo! Inc. nor the names of YUI's contributors may be
    used to endorse or promote products derived from this software without
    specific prior written permission of Yahoo! Inc.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR
ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON
ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```

### FTL

```text
The FreeType Project LICENSE

2006-Jan-27

Copyright 1996-2002, 2006 by David Turner, Robert Wilhelm, and Werner Lemberg

Introduction

The FreeType Project is distributed in several archive packages; some of them may contain, in addition to the FreeType font engine, various tools and contributions which rely on, or relate to, the FreeType Project.

This license applies to all files found in such packages, and which do not fall under their own explicit license. The license affects thus the FreeType font engine, the test programs, documentation and makefiles, at the very least.

This license was inspired by the BSD, Artistic, and IJG (Independent JPEG Group) licenses, which all encourage inclusion and use of free software in commercial and freeware products alike. As a consequence, its main points are that:

     o We don't promise that this software works. However, we will be interested in any kind of bug reports. (`as is' distribution)

     o You can use this software for whatever you want, in parts or full form, without having to pay us. (`royalty-free' usage)

     o You may not pretend that you wrote this software. If you use it, or only parts of it, in a program, you must acknowledge somewhere in your documentation that you have used the FreeType code. (`credits')

We specifically permit and encourage the inclusion of this software, with or without modifications, in commercial products. We disclaim all warranties covering The FreeType Project and assume no liability related to The FreeType Project.

Finally, many people asked us for a preferred form for a credit/disclaimer to use in compliance with this license. We thus encourage you to use the following text:

     """ Portions of this software are copyright © <year> The FreeType Project (www.freetype.org). All rights reserved. """

Please replace <year> with the value from the FreeType version you actually use.

Legal Terms

0. Definitions

Throughout this license, the terms `package', `FreeType Project', and `FreeType archive' refer to the set of files originally distributed by the authors (David Turner, Robert Wilhelm, and Werner Lemberg) as the `FreeType Project', be they named as alpha, beta or final release.

`You' refers to the licensee, or person using the project, where `using' is a generic term including compiling the project's source code as well as linking it to form a `program' or `executable'. This program is referred to as `a program using the FreeType engine'.

This license applies to all files distributed in the original FreeType Project, including all source code, binaries and documentation, unless otherwise stated in the file in its original, unmodified form as distributed in the original archive. If you are unsure whether or not a particular file is covered by this license, you must contact us to verify this.

The FreeType Project is copyright (C) 1996-2000 by David Turner, Robert Wilhelm, and Werner Lemberg. All rights reserved except as specified below.

1. No Warranty

THE FREETYPE PROJECT IS PROVIDED `AS IS' WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING, BUT NOT LIMITED TO, WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE. IN NO EVENT WILL ANY OF THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY DAMAGES CAUSED BY THE USE OR THE INABILITY TO USE, OF THE FREETYPE PROJECT.

2. Redistribution

This license grants a worldwide, royalty-free, perpetual and irrevocable right and license to use, execute, perform, compile, display, copy, create derivative works of, distribute and sublicense the FreeType Project (in both source and object code forms) and derivative works thereof for any purpose; and to authorize others to exercise some or all of the rights granted herein, subject to the following conditions:

     o Redistribution of source code must retain this license file (`FTL.TXT') unaltered; any additions, deletions or changes to the original files must be clearly indicated in accompanying documentation. The copyright notices of the unaltered, original files must be preserved in all copies of source files.

     o Redistribution in binary form must provide a disclaimer that states that the software is based in part of the work of the FreeType Team, in the distribution documentation. We also encourage you to put an URL to the FreeType web page in your documentation, though this isn't mandatory.

These conditions apply to any software derived from or based on the FreeType Project, not just the unmodified files. If you use our work, you must acknowledge us. However, no fee need be paid to us.

3. Advertising

Neither the FreeType authors and contributors nor you shall use the name of the other for commercial, advertising, or promotional purposes without specific prior written permission.

We suggest, but do not require, that you use one or more of the following phrases to refer to this software in your documentation or advertising materials: `FreeType Project', `FreeType Engine', `FreeType library', or `FreeType Distribution'.

As you have not signed this license, you are not required to accept it. However, as the FreeType Project is copyrighted material, only this license, or another one contracted with the authors, grants you the right to use, distribute, and modify it. Therefore, by using, distributing, or modifying the FreeType Project, you indicate that you understand and accept all the terms of this license.

4. Contacts

There are two mailing lists related to FreeType:

     o freetype@nongnu.org

     Discusses general use and applications of FreeType, as well as future and wanted additions to the library and distribution. If you are looking for support, start in this list if you haven't found anything to help you in the documentation.

     o freetype-devel@nongnu.org

     Discusses bugs, as well as engine internals, design issues, specific licenses, porting, etc.

Our home page can be found at

 http://www.freetype.org

--- end of FTL.TXT ---
```

### IJG

```text
Independent JPEG Group License

LEGAL ISSUES

In plain English:

1. We don't promise that this software works. (But if you find any bugs, please let us know!)
2. You can use this software for whatever you want. You don't have to pay us.
3. You may not pretend that you wrote this software. If you use it in a program, you must acknowledge somewhere in your documentation that you've used the IJG code.

In legalese:

The authors make NO WARRANTY or representation, either express or implied, with respect to this software, its quality, accuracy, merchantability, or fitness for a particular purpose. This software is provided "AS IS", and you, its user, assume the entire risk as to its quality and accuracy.

This software is copyright (C) 1991-1998, Thomas G. Lane. All Rights Reserved except as specified below.

Permission is hereby granted to use, copy, modify, and distribute this software (or portions thereof) for any purpose, without fee, subject to these conditions:

     (1) If any part of the source code for this software is distributed, then this README file must be included, with this copyright and no-warranty notice unaltered; and any additions, deletions, or changes to the original files must be clearly indicated in accompanying documentation.
     (2) If only executable code is distributed, then the accompanying documentation must state that "this software is based in part on the work of the Independent JPEG Group".
     (3) Permission for use of this software is granted only if the user accepts full responsibility for any undesirable consequences; the authors accept NO LIABILITY for damages of any kind.

These conditions apply to any software derived from or based on the IJG code, not just to the unmodified library. If you use our work, you ought to acknowledge us.

Permission is NOT granted for the use of any IJG author's name or company name in advertising or publicity relating to this software or products derived from it. This software may be referred to only as "the Independent JPEG Group's software".

We specifically permit and encourage the use of this software as the basis of commercial products, provided that all warranty or liability claims are assumed by the product vendor.

ansi2knr.c is included in this distribution by permission of L. Peter Deutsch, sole proprietor of its copyright holder, Aladdin Enterprises of Menlo Park, CA. ansi2knr.c is NOT covered by the above copyright and conditions, but instead by the usual distribution terms of the Free Software Foundation; principally, that you must include source code if you redistribute it. (See the file ansi2knr.c for full details.) However, since ansi2knr.c is not needed as part of any program generated from the IJG code, this does not limit you more than the foregoing paragraphs do.

The Unix configuration script "configure" was produced with GNU Autoconf. It is copyright by the Free Software Foundation but is freely distributable. The same holds for its supporting scripts (config.guess, config.sub, ltconfig, ltmain.sh). Another support script, install-sh, is copyright by M.I.T. but is also freely distributable.

It appears that the arithmetic coding option of the JPEG spec is covered by patents owned by IBM, AT&T, and Mitsubishi. Hence arithmetic coding cannot legally be used without obtaining one or more licenses. For this reason, support for arithmetic coding has been removed from the free JPEG software. (Since arithmetic coding provides only a marginal gain over the unpatented Huffman mode, it is unlikely that very many implementations will support it.) So far as we are aware, there are no patent restrictions on the remaining code.

The IJG distribution formerly included code to read and write GIF files. To avoid entanglement with the Unisys LZW patent, GIF reading support has been removed altogether, and the GIF writer has been simplified to produce "uncompressed GIFs". This technique does not use the LZW algorithm; the resulting GIF files are larger than usual, but are readable by all standard GIF decoders.

We are required to state that
     "The Graphics Interchange Format(c) is the Copyright property of CompuServe Incorporated. GIF(sm) is a Service Mark property of CompuServe Incorporated."
```

### ISC

```text
The ISC License

Copyright (c) <year> <copyright holders>

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF OR
IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.
```

### LLVM-exception

```text
---- LLVM Exceptions to the Apache 2.0 License ----

   As an exception, if, as a result of your compiling your source code, portions
   of this Software are embedded into an Object form of such source code, you
   may redistribute such embedded portions in such Object form without complying
   with the conditions of Sections 4(a), 4(b) and 4(d) of the License.

   In addition, if you combine or link compiled forms of this Software with
   software that is licensed under the GPLv2 ("Combined Software") and if a
   court of competent jurisdiction determines that the patent provision (Section
   3), the indemnity provision (Section 9) or other Section of the License
   conflicts with the conditions of the GPLv2, you may retroactively and
   prospectively choose to deem waived or otherwise exclude such Section(s) of
   the License, but only in their entirety and only with respect to the Combined
   Software.
```

### LicenseRef-Adobe-DNG-SDK

```text
This product includes DNG technology under license by Adobe Systems
Incorporated.

DNG SDK License Agreement
NOTICE TO USER:
Adobe Systems Incorporated provides the Software and Documentation for use under
the terms of this Agreement. Any download, installation, use, reproduction,
modification or distribution of the Software or Documentation, or any
derivatives or portions thereof, constitutes your acceptance of this Agreement.

As used in this Agreement, "Adobe" means Adobe Systems Incorporated. "Software"
means the software code, in any format, including sample code and source code,
accompanying this Agreement. "Documentation" means the documents, specifications
and all other items accompanying this Agreement other than the Software.

1. LICENSE GRANT
Software License.  Subject to the restrictions below and other terms of this
Agreement, Adobe hereby grants you a non-exclusive, worldwide, royalty free
license to use, reproduce, prepare derivative works from, publicly display,
publicly perform, distribute and sublicense the Software for any purpose.

Document License.  Subject to the terms of this Agreement, Adobe hereby grants
you a non-exclusive, worldwide, royalty free license to make a limited number of
copies of the Documentation for your development purposes and to publicly
display, publicly perform and distribute such copies.  You may not modify the
Documentation.

2. RESTRICTIONS AND OWNERSHIP
You will not remove any copyright or other notice included in the Software or
Documentation and you will include such notices in any copies of the Software
that you distribute in human-readable format.

You will not copy, use, display, modify or distribute the Software or
Documentation in any manner not permitted by this Agreement. No title to the
intellectual property in the Software or Documentation is transferred to you
under the terms of this Agreement. You do not acquire any rights to the Software
or the Documentation except as expressly set forth in this Agreement. All rights
not granted are reserved by Adobe.

3. DISCLAIMER OF WARRANTY
ADOBE PROVIDES THE SOFTWARE AND DOCUMENTATION ONLY ON AN "AS IS" BASIS WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING
WITHOUT LIMITATION ANY WARRANTIES OR CONDITIONS OF TITLE, NON-INFRINGEMENT,
MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE. ADOBE MAKES NO WARRANTY
THAT THE SOFTWARE OR DOCUMENTATION WILL BE ERROR-FREE. To the extent
permissible, any warranties that are not and cannot be excluded by the foregoing
are limited to ninety (90) days.

4. LIMITATION OF LIABILITY
ADOBE AND ITS SUPPLIERS SHALL NOT BE LIABLE FOR LOSS OR DAMAGE ARISING OUT OF
THIS AGREEMENT OR FROM THE USE OF THE SOFTWARE OR DOCUMENTATION. IN NO EVENT
WILL ADOBE BE LIABLE TO YOU OR ANY THIRD PARTY FOR ANY DIRECT, INDIRECT,
CONSEQUENTIAL, INCIDENTAL, OR SPECIAL DAMAGES INCLUDING LOST PROFITS, LOST
SAVINGS, COSTS, FEES, OR EXPENSES OF ANY KIND ARISING OUT OF ANY PROVISION OF
THIS AGREEMENT OR THE USE OR THE INABILITY TO USE THE SOFTWARE OR DOCUMENTATION,
HOWEVER CAUSED AND UNDER ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT
LIABILITY OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE), EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGES. ADOBE'S AGGREGATE LIABILITY AND THAT OF ITS
SUPPLIERS UNDER OR IN CONNECTION WITH THIS AGREEMENT SHALL BE LIMITED TO THE
AMOUNT PAID BY YOU FOR THE SOFTWARE AND DOCUMENTATION.

5. INDEMNIFICATION
If you choose to distribute the Software in a commercial product, you do so with
the understanding that you agree to defend, indemnify and hold harmless Adobe
against any losses, damages and costs arising from the claims, lawsuits or other
legal actions arising out of such distribution.

6. TRADEMARK USAGE
Adobe and the DNG logo are the trademarks or registered trademarks of Adobe
Systems Incorporated in the United States and other countries. Such trademarks
may not be used to endorse or promote any product unless expressly permitted
under separate agreement with Adobe. For information on how to license the DNG
logo please go to www.adobe.com.

7. TERM
Your rights under this Agreement shall terminate if you fail to comply with any
of the material terms or conditions of this Agreement. If all your rights under
this Agreement terminate, you will immediately cease use and distribution of the
Software and Documentation.

8. GOVERNING LAW AND JURISDICTION. This Agreement is governed by the statutes
and laws of the State of California, without regard to the conflicts of law
principles thereof. The federal and state courts located in Santa Clara County,
California, USA, will have non-exclusive jurisdiction over any dispute arising
out of this Agreement.

9. GENERAL
This Agreement supersedes any prior agreement, oral or written, between Adobe
and you with respect to the licensing to you of the Software and Documentation.
No variation of the terms of this Agreement will be enforceable against Adobe
unless Adobe gives its express consent in writing signed by an authorized
signatory of Adobe. If any part of this Agreement is found void and
unenforceable, it will not affect the validity of the balance of the Agreement,
which shall remain valid and enforceable according to its terms.
```

### LicenseRef-FFTPACK

```text
FFTPACK license:

http://www.cisl.ucar.edu/css/software/fftpack5/ftpk.html

Copyright (c) 2004 the University Corporation for Atmospheric
Research ("UCAR"). All rights reserved. Developed by NCAR's
Computational and Information Systems Laboratory, UCAR,
www.cisl.ucar.edu.

Redistribution and use of the Software in source and binary forms,
with or without modification, is permitted provided that the
following conditions are met:

- Neither the names of NCAR's Computational and Information Systems
Laboratory, the University Corporation for Atmospheric Research,
nor the names of its sponsors or contributors may be used to
endorse or promote products derived from this Software without
specific prior written permission.

- Redistributions of source code must retain the above copyright
notices, this list of conditions, and the disclaimer below.

- Redistributions in binary form must reproduce the above copyright
notice, this list of conditions, and the disclaimer below in the
documentation and/or other materials provided with the
distribution.

THIS SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING, BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE CONTRIBUTORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, INDIRECT, INCIDENTAL, SPECIAL,
EXEMPLARY, OR CONSEQUENTIAL DAMAGES OR OTHER LIABILITY, WHETHER IN AN
ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS WITH THE
SOFTWARE.
```

### LicenseRef-Ooura

```text
Copyright Takuya OOURA, 1996-2001

You may use, copy, modify and distribute this code for any purpose
(include commercial use) and without fee. Please refer to this
package when you modify this code.
```

### MIT

```text
MIT License

Copyright (c) <year> <copyright holders>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### MIT-0

```text
MIT No Attribution

Copyright <YEAR> <COPYRIGHT HOLDER>

Permission is hereby granted, free of charge, to any person obtaining a copy of this
software and associated documentation files (the "Software"), to deal in the Software
without restriction, including without limitation the rights to use, copy, modify,
merge, publish, distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED,
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A
PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

### MIT-Modern-Variant

```text
Permission is hereby granted, without written agreement and without
license or royalty fees, to use, copy, modify, and distribute this
software and its documentation for any purpose, provided that the
above copyright notice and the following two paragraphs appear in
all copies of this software.

IN NO EVENT SHALL THE COPYRIGHT HOLDER BE LIABLE TO ANY PARTY FOR
DIRECT, INDIRECT, SPECIAL, INCIDENTAL, OR CONSEQUENTIAL DAMAGES
ARISING OUT OF THE USE OF THIS SOFTWARE AND ITS DOCUMENTATION, EVEN
IF THE COPYRIGHT HOLDER HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH
DAMAGE.

THE COPYRIGHT HOLDER SPECIFICALLY DISCLAIMS ANY WARRANTIES, INCLUDING,
BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND
FITNESS FOR A PARTICULAR PURPOSE.  THE SOFTWARE PROVIDED HEREUNDER IS
ON AN "AS IS" BASIS, AND THE COPYRIGHT HOLDER HAS NO OBLIGATION TO
PROVIDE MAINTENANCE, SUPPORT, UPDATES, ENHANCEMENTS, OR MODIFICATIONS.
```

### MPL-2.0

```text
Mozilla Public License Version 2.0
==================================

1. Definitions
--------------

1.1. "Contributor"
    means each individual or legal entity that creates, contributes to
    the creation of, or owns Covered Software.

1.2. "Contributor Version"
    means the combination of the Contributions of others (if any) used
    by a Contributor and that particular Contributor's Contribution.

1.3. "Contribution"
    means Covered Software of a particular Contributor.

1.4. "Covered Software"
    means Source Code Form to which the initial Contributor has attached
    the notice in Exhibit A, the Executable Form of such Source Code
    Form, and Modifications of such Source Code Form, in each case
    including portions thereof.

1.5. "Incompatible With Secondary Licenses"
    means

    (a) that the initial Contributor has attached the notice described
        in Exhibit B to the Covered Software; or

    (b) that the Covered Software was made available under the terms of
        version 1.1 or earlier of the License, but not also under the
        terms of a Secondary License.

1.6. "Executable Form"
    means any form of the work other than Source Code Form.

1.7. "Larger Work"
    means a work that combines Covered Software with other material, in
    a separate file or files, that is not Covered Software.

1.8. "License"
    means this document.

1.9. "Licensable"
    means having the right to grant, to the maximum extent possible,
    whether at the time of the initial grant or subsequently, any and
    all of the rights conveyed by this License.

1.10. "Modifications"
    means any of the following:

    (a) any file in Source Code Form that results from an addition to,
        deletion from, or modification of the contents of Covered
        Software; or

    (b) any new file in Source Code Form that contains any Covered
        Software.

1.11. "Patent Claims" of a Contributor
    means any patent claim(s), including without limitation, method,
    process, and apparatus claims, in any patent Licensable by such
    Contributor that would be infringed, but for the grant of the
    License, by the making, using, selling, offering for sale, having
    made, import, or transfer of either its Contributions or its
    Contributor Version.

1.12. "Secondary License"
    means either the GNU General Public License, Version 2.0, the GNU
    Lesser General Public License, Version 2.1, the GNU Affero General
    Public License, Version 3.0, or any later versions of those
    licenses.

1.13. "Source Code Form"
    means the form of the work preferred for making modifications.

1.14. "You" (or "Your")
    means an individual or a legal entity exercising rights under this
    License. For legal entities, "You" includes any entity that
    controls, is controlled by, or is under common control with You. For
    purposes of this definition, "control" means (a) the power, direct
    or indirect, to cause the direction or management of such entity,
    whether by contract or otherwise, or (b) ownership of more than
    fifty percent (50%) of the outstanding shares or beneficial
    ownership of such entity.

2. License Grants and Conditions
--------------------------------

2.1. Grants

Each Contributor hereby grants You a world-wide, royalty-free,
non-exclusive license:

(a) under intellectual property rights (other than patent or trademark)
    Licensable by such Contributor to use, reproduce, make available,
    modify, display, perform, distribute, and otherwise exploit its
    Contributions, either on an unmodified basis, with Modifications, or
    as part of a Larger Work; and

(b) under Patent Claims of such Contributor to make, use, sell, offer
    for sale, have made, import, and otherwise transfer either its
    Contributions or its Contributor Version.

2.2. Effective Date

The licenses granted in Section 2.1 with respect to any Contribution
become effective for each Contribution on the date the Contributor first
distributes such Contribution.

2.3. Limitations on Grant Scope

The licenses granted in this Section 2 are the only rights granted under
this License. No additional rights or licenses will be implied from the
distribution or licensing of Covered Software under this License.
Notwithstanding Section 2.1(b) above, no patent license is granted by a
Contributor:

(a) for any code that a Contributor has removed from Covered Software;
    or

(b) for infringements caused by: (i) Your and any other third party's
    modifications of Covered Software, or (ii) the combination of its
    Contributions with other software (except as part of its Contributor
    Version); or

(c) under Patent Claims infringed by Covered Software in the absence of
    its Contributions.

This License does not grant any rights in the trademarks, service marks,
or logos of any Contributor (except as may be necessary to comply with
the notice requirements in Section 3.4).

2.4. Subsequent Licenses

No Contributor makes additional grants as a result of Your choice to
distribute the Covered Software under a subsequent version of this
License (see Section 10.2) or under the terms of a Secondary License (if
permitted under the terms of Section 3.3).

2.5. Representation

Each Contributor represents that the Contributor believes its
Contributions are its original creation(s) or it has sufficient rights
to grant the rights to its Contributions conveyed by this License.

2.6. Fair Use

This License is not intended to limit any rights You have under
applicable copyright doctrines of fair use, fair dealing, or other
equivalents.

2.7. Conditions

Sections 3.1, 3.2, 3.3, and 3.4 are conditions of the licenses granted
in Section 2.1.

3. Responsibilities
-------------------

3.1. Distribution of Source Form

All distribution of Covered Software in Source Code Form, including any
Modifications that You create or to which You contribute, must be under
the terms of this License. You must inform recipients that the Source
Code Form of the Covered Software is governed by the terms of this
License, and how they can obtain a copy of this License. You may not
attempt to alter or restrict the recipients' rights in the Source Code
Form.

3.2. Distribution of Executable Form

If You distribute Covered Software in Executable Form then:

(a) such Covered Software must also be made available in Source Code
    Form, as described in Section 3.1, and You must inform recipients of
    the Executable Form how they can obtain a copy of such Source Code
    Form by reasonable means in a timely manner, at a charge no more
    than the cost of distribution to the recipient; and

(b) You may distribute such Executable Form under the terms of this
    License, or sublicense it under different terms, provided that the
    license for the Executable Form does not attempt to limit or alter
    the recipients' rights in the Source Code Form under this License.

3.3. Distribution of a Larger Work

You may create and distribute a Larger Work under terms of Your choice,
provided that You also comply with the requirements of this License for
the Covered Software. If the Larger Work is a combination of Covered
Software with a work governed by one or more Secondary Licenses, and the
Covered Software is not Incompatible With Secondary Licenses, this
License permits You to additionally distribute such Covered Software
under the terms of such Secondary License(s), so that the recipient of
the Larger Work may, at their option, further distribute the Covered
Software under the terms of either this License or such Secondary
License(s).

3.4. Notices

You may not remove or alter the substance of any license notices
(including copyright notices, patent notices, disclaimers of warranty,
or limitations of liability) contained within the Source Code Form of
the Covered Software, except that You may alter any license notices to
the extent required to remedy known factual inaccuracies.

3.5. Application of Additional Terms

You may choose to offer, and to charge a fee for, warranty, support,
indemnity or liability obligations to one or more recipients of Covered
Software. However, You may do so only on Your own behalf, and not on
behalf of any Contributor. You must make it absolutely clear that any
such warranty, support, indemnity, or liability obligation is offered by
You alone, and You hereby agree to indemnify every Contributor for any
liability incurred by such Contributor as a result of warranty, support,
indemnity or liability terms You offer. You may include additional
disclaimers of warranty and limitations of liability specific to any
jurisdiction.

4. Inability to Comply Due to Statute or Regulation
---------------------------------------------------

If it is impossible for You to comply with any of the terms of this
License with respect to some or all of the Covered Software due to
statute, judicial order, or regulation then You must: (a) comply with
the terms of this License to the maximum extent possible; and (b)
describe the limitations and the code they affect. Such description must
be placed in a text file included with all distributions of the Covered
Software under this License. Except to the extent prohibited by statute
or regulation, such description must be sufficiently detailed for a
recipient of ordinary skill to be able to understand it.

5. Termination
--------------

5.1. The rights granted under this License will terminate automatically
if You fail to comply with any of its terms. However, if You become
compliant, then the rights granted under this License from a particular
Contributor are reinstated (a) provisionally, unless and until such
Contributor explicitly and finally terminates Your grants, and (b) on an
ongoing basis, if such Contributor fails to notify You of the
non-compliance by some reasonable means prior to 60 days after You have
come back into compliance. Moreover, Your grants from a particular
Contributor are reinstated on an ongoing basis if such Contributor
notifies You of the non-compliance by some reasonable means, this is the
first time You have received notice of non-compliance with this License
from such Contributor, and You become compliant prior to 30 days after
Your receipt of the notice.

5.2. If You initiate litigation against any entity by asserting a patent
infringement claim (excluding declaratory judgment actions,
counter-claims, and cross-claims) alleging that a Contributor Version
directly or indirectly infringes any patent, then the rights granted to
You by any and all Contributors for the Covered Software under Section
2.1 of this License shall terminate.

5.3. In the event of termination under Sections 5.1 or 5.2 above, all
end user license agreements (excluding distributors and resellers) which
have been validly granted by You or Your distributors under this License
prior to termination shall survive termination.

************************************************************************
*                                                                      *
*  6. Disclaimer of Warranty                                           *
*  -------------------------                                           *
*                                                                      *
*  Covered Software is provided under this License on an "as is"       *
*  basis, without warranty of any kind, either expressed, implied, or  *
*  statutory, including, without limitation, warranties that the       *
*  Covered Software is free of defects, merchantable, fit for a        *
*  particular purpose or non-infringing. The entire risk as to the     *
*  quality and performance of the Covered Software is with You.        *
*  Should any Covered Software prove defective in any respect, You     *
*  (not any Contributor) assume the cost of any necessary servicing,   *
*  repair, or correction. This disclaimer of warranty constitutes an   *
*  essential part of this License. No use of any Covered Software is   *
*  authorized under this License except under this disclaimer.         *
*                                                                      *
************************************************************************

************************************************************************
*                                                                      *
*  7. Limitation of Liability                                          *
*  --------------------------                                          *
*                                                                      *
*  Under no circumstances and under no legal theory, whether tort      *
*  (including negligence), contract, or otherwise, shall any           *
*  Contributor, or anyone who distributes Covered Software as          *
*  permitted above, be liable to You for any direct, indirect,         *
*  special, incidental, or consequential damages of any character      *
*  including, without limitation, damages for lost profits, loss of    *
*  goodwill, work stoppage, computer failure or malfunction, or any    *
*  and all other commercial damages or losses, even if such party      *
*  shall have been informed of the possibility of such damages. This   *
*  limitation of liability shall not apply to liability for death or   *
*  personal injury resulting from such party's negligence to the       *
*  extent applicable law prohibits such limitation. Some               *
*  jurisdictions do not allow the exclusion or limitation of           *
*  incidental or consequential damages, so this exclusion and          *
*  limitation may not apply to You.                                    *
*                                                                      *
************************************************************************

8. Litigation
-------------

Any litigation relating to this License may be brought only in the
courts of a jurisdiction where the defendant maintains its principal
place of business and such litigation shall be governed by laws of that
jurisdiction, without reference to its conflict-of-law provisions.
Nothing in this Section shall prevent a party's ability to bring
cross-claims or counter-claims.

9. Miscellaneous
----------------

This License represents the complete agreement concerning the subject
matter hereof. If any provision of this License is held to be
unenforceable, such provision shall be reformed only to the extent
necessary to make it enforceable. Any law or regulation which provides
that the language of a contract shall be construed against the drafter
shall not be used to construe this License against a Contributor.

10. Versions of the License
---------------------------

10.1. New Versions

Mozilla Foundation is the license steward. Except as provided in Section
10.3, no one other than the license steward has the right to modify or
publish new versions of this License. Each version will be given a
distinguishing version number.

10.2. Effect of New Versions

You may distribute the Covered Software under the terms of the version
of the License under which You originally received the Covered Software,
or under the terms of any subsequent version published by the license
steward.

10.3. Modified Versions

If you create software not governed by this License, and you want to
create a new license for such software, you may create and use a
modified version of this License if you rename the license and remove
any references to the name of the license steward (except to note that
such modified license differs from this License).

10.4. Distributing Source Code Form that is Incompatible With Secondary
Licenses

If You choose to distribute Source Code Form that is Incompatible With
Secondary Licenses under the terms of this version of the License, the
notice described in Exhibit B of this License must be attached.

Exhibit A - Source Code Form License Notice
-------------------------------------------

  This Source Code Form is subject to the terms of the Mozilla Public
  License, v. 2.0. If a copy of the MPL was not distributed with this
  file, You can obtain one at https://mozilla.org/MPL/2.0/.

If it is not possible or desirable to put the notice in a particular
file, then You may include the notice in a location (such as a LICENSE
file in a relevant directory) where a recipient would be likely to look
for such a notice.

You may add additional accurate notices of copyright ownership.

Exhibit B - "Incompatible With Secondary Licenses" Notice
---------------------------------------------------------

  This Source Code Form is "Incompatible With Secondary Licenses", as
  defined by the Mozilla Public License, v. 2.0.
```

### OFL-1.1

```text
SIL OPEN FONT LICENSE Version 1.1 - 26 February 2007
-----------------------------------------------------------

PREAMBLE
The goals of the Open Font License (OFL) are to stimulate worldwide
development of collaborative font projects, to support the font creation
efforts of academic and linguistic communities, and to provide a free and
open framework in which fonts may be shared and improved in partnership
with others.

The OFL allows the licensed fonts to be used, studied, modified and
redistributed freely as long as they are not sold by themselves. The
fonts, including any derivative works, can be bundled, embedded,
redistributed and/or sold with any software provided that any reserved
names are not used by derivative works. The fonts and derivatives,
however, cannot be released under any other type of license. The
requirement for fonts to remain under this license does not apply
to any document created using the fonts or their derivatives.

DEFINITIONS
"Font Software" refers to the set of files released by the Copyright
Holder(s) under this license and clearly marked as such. This may
include source files, build scripts and documentation.

"Reserved Font Name" refers to any names specified as such after the
copyright statement(s).

"Original Version" refers to the collection of Font Software components as
distributed by the Copyright Holder(s).

"Modified Version" refers to any derivative made by adding to, deleting,
or substituting -- in part or in whole -- any of the components of the
Original Version, by changing formats or by porting the Font Software to a
new environment.

"Author" refers to any designer, engineer, programmer, technical
writer or other person who contributed to the Font Software.

PERMISSION & CONDITIONS
Permission is hereby granted, free of charge, to any person obtaining
a copy of the Font Software, to use, study, copy, merge, embed, modify,
redistribute, and sell modified and unmodified copies of the Font
Software, subject to the following conditions:

1) Neither the Font Software nor any of its individual components,
in Original or Modified Versions, may be sold by itself.

2) Original or Modified Versions of the Font Software may be bundled,
redistributed and/or sold with any software, provided that each copy
contains the above copyright notice and this license. These can be
included either as stand-alone text files, human-readable headers or
in the appropriate machine-readable metadata fields within text or
binary files as long as those fields can be easily viewed by the user.

3) No Modified Version of the Font Software may use the Reserved Font
Name(s) unless explicit written permission is granted by the corresponding
Copyright Holder. This restriction only applies to the primary font name as
presented to the users.

4) The name(s) of the Copyright Holder(s) or the Author(s) of the Font
Software shall not be used to promote, endorse or advertise any
Modified Version, except to acknowledge the contribution(s) of the
Copyright Holder(s) and the Author(s) or with their explicit written
permission.

5) The Font Software, modified or unmodified, in part or in whole,
must be distributed entirely under this license, and must not be
distributed under any other license. The requirement for fonts to
remain under this license does not apply to any document created
using the Font Software.

TERMINATION
This license becomes null and void if any of the above conditions are
not met.

DISCLAIMER
THE FONT SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO ANY WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT
OF COPYRIGHT, PATENT, TRADEMARK, OR OTHER RIGHT. IN NO EVENT SHALL THE
COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
INCLUDING ANY GENERAL, SPECIAL, INDIRECT, INCIDENTAL, OR CONSEQUENTIAL
DAMAGES, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF THE USE OR INABILITY TO USE THE FONT SOFTWARE OR FROM
OTHER DEALINGS IN THE FONT SOFTWARE.
```

### Zlib

```text
zlib License

This software is provided 'as-is', without any express or implied warranty.  In no event will the authors be held liable for any damages arising from the use of this software.

Permission is granted to anyone to use this software for any purpose, including commercial applications, and to alter it and redistribute it freely, subject to the following restrictions:

     1. The origin of this software must not be misrepresented; you must not claim that you wrote the original software. If you use this software in a product, an acknowledgment in the product documentation would be appreciated but is not required.

     2. Altered source versions must be plainly marked as such, and must not be misrepresented as being the original software.

     3. This notice may not be removed or altered from any source distribution.
```

### bzip2-1.0.6

```text
This program, "bzip2", the associated library "libbzip2", and all documentation, are copyright (C) 1996-2010 Julian R Seward. All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

     1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

     2. The origin of this software must not be misrepresented; you must not claim that you wrote the original software. If you use this software in a product, an acknowledgment in the product documentation would be appreciated but is not required.

     3. Altered source versions must be plainly marked as such, and must not be misrepresented as being the original software.

     4. The name of the author may not be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE AUTHOR ``AS IS'' AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

Julian Seward, jseward@bzip.org bzip2/libbzip2 version 1.0.6 of 6 September 2010
```

### dtoa

```text
The author of this software is David M. Gay.

Copyright (c) 1991, 2000, 2001 by Lucent Technologies.

Permission to use, copy, modify, and distribute this software for any
purpose without fee is hereby granted, provided that this entire notice
is included in all copies of any software which is or includes a copy
or modification of this software and in all copies of the supporting
documentation for such software.

THIS SOFTWARE IS BEING PROVIDED "AS IS", WITHOUT ANY EXPRESS OR IMPLIED
WARRANTY.  IN PARTICULAR, NEITHER THE AUTHOR NOR LUCENT MAKES ANY
REPRESENTATION OR WARRANTY OF ANY KIND CONCERNING THE MERCHANTABILITY
OF THIS SOFTWARE OR ITS FITNESS FOR ANY PARTICULAR PURPOSE.
```

### libpng-2.0

```text
PNG Reference Library License version 2
---------------------------------------

 * Copyright (c) 1995-2018 The PNG Reference Library Authors.
 * Copyright (c) 2018 Cosmin Truta.
 * Copyright (c) 2000-2002, 2004, 2006-2018 Glenn Randers-Pehrson.
 * Copyright (c) 1996-1997 Andreas Dilger.
 * Copyright (c) 1995-1996 Guy Eric Schalnat, Group 42, Inc.

The software is supplied "as is", without warranty of any kind,
express or implied, including, without limitation, the warranties
of merchantability, fitness for a particular purpose, title, and
non-infringement.  In no event shall the Copyright owners, or
anyone distributing the software, be liable for any damages or
other liability, whether in contract, tort or otherwise, arising
from, out of, or in connection with the software, or the use or
other dealings in the software, even if advised of the possibility
of such damage.

Permission is hereby granted to use, copy, modify, and distribute
this software, or portions hereof, for any purpose, without fee,
subject to the following restrictions:

 1. The origin of this software must not be misrepresented; you
    must not claim that you wrote the original software.  If you
    use this software in a product, an acknowledgment in the product
    documentation would be appreciated, but is not required.

 2. Altered source versions must be plainly marked as such, and must
    not be misrepresented as being the original software.

 3. This Copyright notice may not be removed or altered from any
    source or altered source distribution.
```

---

[Back to the Shuffleep page](/shuffleep/)
