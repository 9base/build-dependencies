> [!NOTE]
> **9base status: Preserved** · **Lifecycle: archived reference copy.**
>
> This is a historical fork of [open-license-manager/build-dependencies](https://github.com/open-license-manager/build-dependencies).
> 9base retains it for provenance and reference and does not actively maintain it.
> Upstream source and inherited authorship remain attributed to their original contributors.

# build-dependencies — 9base preservation notes

## Role and provenance

Despite the generic repository name, this is an Open License Manager
**licensecc** dependency archive. The upstream README explicitly identifies
copied precompiled artifacts used to compile/test licensecc; the root contains
`boost` and `openssl` directories. It is not evidence of general-purpose
9base build infrastructure. An absent GitHub language result does not mean
this artifact repository is empty.

The retained `main` branch was identical to upstream in the 8 October 2026
audit, with 0 ahead / 0 behind. No fork-only or account-linked Zaryob-authored
commits were exposed. The account filter cannot exhaustively identify every
unlinked historical author. Original artifact attribution and the upstream
README, including its recorded OpenSSL download source, are retained below.

## Open License Manager / licensecc family

| Component | Preserved 9base repository |
| --- | --- |
| C++ licensing runtime library | [licensecc](https://github.com/9base/licensecc) |
| Project-key and license generator | [lcc-license-generator](https://github.com/9base/lcc-license-generator) |
| Precompiled build/test dependencies | [build-dependencies](https://github.com/9base/build-dependencies) |
| C++ integration examples | [examples](https://github.com/9base/examples) |

These are preserved upstream components. Their relationship is recorded by upstream
documentation; this curation does not assert a 9base licensing product or modify
submodule URLs. The existing upstream license and attribution remain unchanged.

## Historical note

These preservation notes were reconstructed on **8 October 2026** from the
repository tree, exposed branches, commit history and upstream comparisons.
They are new archival documentation, not evidence that this explanation existed
at the historical fork date. The original reason for retention or any deployment
is not established by the inspected record. No contemporary build, support or
upstream synchronization commitment is implied.

---

## Original upstream README (preserved)

# Precompiled version of libraries

Tired of getting the tests failing because some needed library was moved elsewhere, i'm copying here some pre-compiled artifact we need to compile/test `licensecc`

## openssl

 * openssl-dev-1.0.2s-x86_64-win-mingw-w64.zip: pre-compiled version of openssl for mingw. Downloaded from [TeskaLabs](https://teskalabs.blob.core.windows.net/openssl/openssl-dev-1.0.2s-x86_64-win-mingw-w64.zip)

