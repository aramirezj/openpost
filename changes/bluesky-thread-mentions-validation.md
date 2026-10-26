### Fixed

- Bluesky threads no longer fail validation with "mentions is not supported" after clearing selected mentions. Authored mention metadata (including an explicit empty spans list) is owned by mention validation, not the provider settings catalog.
