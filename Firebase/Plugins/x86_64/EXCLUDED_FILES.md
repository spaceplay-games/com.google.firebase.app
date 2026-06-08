# Excluded Large Files

The following files exceed GitHub's 100MB file size limit and are excluded from this repository:

- `FirebaseCppApp-13_12_0.bundle` (105MB)

## Impact

**Mobile development (iOS/Android)**: Not affected. All mobile plugins are included.

**Desktop development (Windows)**: Not affected if the Windows DLL is under 100MB.

## Workaround

Download the files manually from Google's registry:

```
https://dl.google.com/games/registry/unity/com.google.firebase.app/com.google.firebase.app-13.12.0.tgz
```

Extract and copy the missing files to the appropriate directory.
