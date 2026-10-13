# Butter Edit RAW profiles

버터 편집(Butter Edit)이 설정 → **RAW 프로필**에서 받는 카메라 프로필 묶음입니다.
카메라마다 Lightroom(Camera Raw, Adobe Standard)과 같은 색 · 밝기가 나오도록 맞춘 값이 들어 있습니다.

Camera profiles that Butter Edit downloads from Settings → **RAW Profiles**. Each profile is tuned so the
camera's RAW files match Lightroom (Camera Raw, Adobe Standard) in color and brightness.

- `raw-profiles.json` — 프로필 묶음 / the profile set
- `raw-profiles.json.sig` — Ed25519 서명 / signature. 앱은 서명이 맞는 묶음만 씁니다 — 손으로 고치면 거부됩니다.
  The app only accepts a set whose signature verifies; hand edits are rejected.

만드는 법은 앱 저장소의 `Tools/raw_profiles/README.md`에 있습니다.
