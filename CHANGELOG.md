# Changelog

<!-- next-header -->

## git

- Also allow `simd128` on WASM.

## 0.1.0
- initial release
- `compile_error` check for NEON or AVX2.
- `ensure_simd::ensure_simd()` to run-time check for AVX2 when AVX2 was enabled
  at compile-time.
