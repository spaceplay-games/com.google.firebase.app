# Excluded Large Files

The following files exceed GitHub's 100MB file size limit and are excluded from this repository:

- `FirebaseCppApp-13_9_0.bundle` (189MB)
- `FirebaseCppApp-13_9_0.so` (122MB)

## Impact

**Mobile development (iOS/Android)**: Not affected. All mobile plugins are included.

**Desktop development (Windows)**: Not affected if the Windows DLL is under 100MB.

## Workaround

Download the files manually from Google's registry:

```
https://dl.google.com/games/registry/unity/com.google.firebase.app/com.google.firebase.app-13.9.0.tgz
```

Extract and copy the missing files to the appropriate directory.
