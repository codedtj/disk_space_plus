# Temporary fork (codedtj)

Forked from harrowmykel/disk_space_plus master (pub.dev 0.2.6).
Only change: `android/build.gradle` no longer applies `kotlin-android` on AGP 9+ (built-in Kotlin);
`kotlinOptions` replaced by the `kotlin {}` block.
Upstream: issue #17, rewrite PR #19. Delete this fork once a published disk_space_plus release supports AGP 9 built-in Kotlin.
