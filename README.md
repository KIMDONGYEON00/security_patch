# Security Patch Contributions

This repository documents my open-source security patch contributions and vulnerability reports. Most CVE IDs in the table refer to **previously disclosed vulnerabilities** that I worked on fixing in downstream projects; they are **not CVEs assigned to my discoveries**.

## CVE Associated with My Research

- [CVE-2025-26269](https://nvd.nist.gov/vuln/detail/CVE-2025-26269) — `dragonflydb/dragonfly`

*This section is separate from the existing CVEs referenced below for downstream patch contributions.*

## Patch and Report Contributions

**How to read this table:** Rows with a CVE ID document my patches for **already published vulnerabilities** in affected open-source projects. The CVE IDs identify the underlying issues, not CVEs awarded to me. Rows with `—` document **new issues I reported or submitted fixes for** that have not been assigned CVE IDs. One PR can address multiple CVEs, so it may appear on multiple rows.

**Status:** ✅ **Patched** — accepted or merged upstream. ⏳ **Pending** — submitted and awaiting upstream review or merge.

| No. | Repository | Vulnerability | CVE | Patch Link | Status |
|---:|---|---|---|---|:---:|
| 1 | `wireshark/wireshark` | Lua bit library stack buffer overflow | CVE-2024-31449 | [MR #19487](https://gitlab.com/wireshark/wireshark/-/merge_requests/19487) | ✅ |
| 2 | `dragonflydb/dragonfly` | Lua bit library stack buffer overflow | CVE-2024-31449 | [PR #4854](https://github.com/dragonflydb/dragonfly/pull/4854) | ✅ |
| 3 | `dragonflydb/dragonfly` | Lua struct integer overflow / stack overflow | CVE-2020-14147 | [PR #5421](https://github.com/dragonflydb/dragonfly/pull/5421) | ✅ |
| 4 | `Snapchat/KeyDB` | Lua bit library stack buffer overflow | CVE-2024-31449 | [PR #906](https://github.com/Snapchat/KeyDB/pull/906) | ⏳ |
| 5 | `Snapchat/KeyDB` | Lua garbage collector use-after-free | CVE-2025-49844 | [PR #918](https://github.com/Snapchat/KeyDB/pull/918) | ✅ |
| 6 | `Snapchat/KeyDB` | Lua out-of-bounds read / denial of service | CVE-2025-46819 | [PR #918](https://github.com/Snapchat/KeyDB/pull/918) | ✅ |
| 7 | `Snapchat/KeyDB` | Lua integer overflow | CVE-2025-46817 | [PR #918](https://github.com/Snapchat/KeyDB/pull/918) | ✅ |
| 8 | `rspamd/rspamd` | Lua bit library stack buffer overflow | CVE-2024-31449 | [PR #5422](https://github.com/rspamd/rspamd/pull/5422) | ✅ |
| 9 | `seemoo-lab/nexmon` | Lua bit library stack buffer overflow | CVE-2024-31449 | [PR #667](https://github.com/seemoo-lab/nexmon/pull/667) | ⏳ |
| 10 | `lishen2/isotp-c` | CAN ISO-TP buffer overflow | CVE-2023-3725 | [PR #36](https://github.com/lishen2/isotp-c/pull/36) | ✅ |
| 11 | `SoftFever/OrcaSlicer` | Expat XML parser integer overflow | CVE-2024-45492 | [PR #10141](https://github.com/SoftFever/OrcaSlicer/pull/10141) | ✅ |
| 12 | `slic3r/Slic3r` | Expat XML parser integer overflow | CVE-2024-45492 | [PR #5196](https://github.com/slic3r/Slic3r/pull/5196) | ⏳ |
| 13 | `viabtc/viabtc_exchange_server` | Hiredis RESP multi-bulk integer overflow | CVE-2021-32765 | [PR #309](https://github.com/viabtc/viabtc_exchange_server/pull/309) | ⏳ |
| 14 | `swoole/swoole-src` | Hiredis RESP multi-bulk integer overflow | CVE-2021-32765 | [PR #5822](https://github.com/swoole/swoole-src/pull/5822) | ✅ |
| 15 | `kbengine/kbengine` | Hiredis RESP multi-bulk integer overflow | CVE-2021-32765 | [PR #1610](https://github.com/kbengine/kbengine/pull/1610) | ⏳ |
| 16 | `F-Stack/f-stack` | Lua bit library stack buffer overflow | CVE-2024-31449 | [PR #1022](https://github.com/F-Stack/f-stack/pull/1022) | ✅ |
| 17 | `F-Stack/f-stack` | Lua garbage collector use-after-free | CVE-2025-49844 | [PR #1022](https://github.com/F-Stack/f-stack/pull/1022) | ✅ |
| 18 | `F-Stack/f-stack` | Lua out-of-bounds read / denial of service | CVE-2025-46819 | [PR #1022](https://github.com/F-Stack/f-stack/pull/1022) | ✅ |
| 19 | `F-Stack/f-stack` | Lua integer overflow | CVE-2025-46817 | [PR #1022](https://github.com/F-Stack/f-stack/pull/1022) | ✅ |
| 20 | `Tencent/Tendis` | Lua struct integer overflow / stack overflow | CVE-2020-14147 | [PR #412](https://github.com/Tencent/Tendis/pull/412) | ✅ |
| 21 | `Tencent/Tendis` | Lua bit library stack buffer overflow | CVE-2024-31449 | [PR #412](https://github.com/Tencent/Tendis/pull/412) | ✅ |
| 22 | `Tencent/Tendis` | Lua garbage collector use-after-free | CVE-2025-49844 | [PR #412](https://github.com/Tencent/Tendis/pull/412) | ✅ |
| 23 | `CodisLabs/codis` | Lua bit library stack buffer overflow | CVE-2024-31449 | [PR #1763](https://github.com/CodisLabs/codis/pull/1763) | ⏳ |
| 24 | `CodisLabs/codis` | Lua garbage collector use-after-free | CVE-2025-49844 | [PR #1763](https://github.com/CodisLabs/codis/pull/1763) | ⏳ |
| 25 | `kbengine/kbengine` | Expat XML parser integer overflow | CVE-2022-22822 | [PR #1612](https://github.com/kbengine/kbengine/pull/1612) | ⏳ |
| 26 | `kbengine/kbengine` | Expat XML parser integer overflow | CVE-2022-22823 | [PR #1612](https://github.com/kbengine/kbengine/pull/1612) | ⏳ |
| 27 | `kbengine/kbengine` | Expat XML parser integer overflow | CVE-2022-22824 | [PR #1612](https://github.com/kbengine/kbengine/pull/1612) | ⏳ |
| 28 | `kbengine/kbengine` | Expat XML parser integer overflow | CVE-2022-22825 | [PR #1612](https://github.com/kbengine/kbengine/pull/1612) | ⏳ |
| 29 | `kbengine/kbengine` | Expat XML parser integer overflow | CVE-2022-22826 | [PR #1612](https://github.com/kbengine/kbengine/pull/1612) | ⏳ |
| 30 | `kbengine/kbengine` | Expat XML parser integer overflow | CVE-2022-22827 | [PR #1612](https://github.com/kbengine/kbengine/pull/1612) | ⏳ |
| 31 | `kbengine/kbengine` | Expat XML namespace separator validation | CVE-2022-25236 | [PR #1612](https://github.com/kbengine/kbengine/pull/1612) | ⏳ |
| 32 | `eduard-permyakov/permafrost-engine` | Expat XML parser integer overflow | CVE-2022-22822 | [PR #33](https://github.com/eduard-permyakov/permafrost-engine/pull/33) | ⏳ |
| 33 | `eduard-permyakov/permafrost-engine` | Expat XML parser integer overflow | CVE-2022-22823 | [PR #33](https://github.com/eduard-permyakov/permafrost-engine/pull/33) | ⏳ |
| 34 | `eduard-permyakov/permafrost-engine` | Expat XML parser integer overflow | CVE-2022-22824 | [PR #33](https://github.com/eduard-permyakov/permafrost-engine/pull/33) | ⏳ |
| 35 | `eduard-permyakov/permafrost-engine` | Expat XML parser integer overflow | CVE-2022-22825 | [PR #33](https://github.com/eduard-permyakov/permafrost-engine/pull/33) | ⏳ |
| 36 | `eduard-permyakov/permafrost-engine` | Expat XML parser integer overflow | CVE-2022-22826 | [PR #33](https://github.com/eduard-permyakov/permafrost-engine/pull/33) | ⏳ |
| 37 | `eduard-permyakov/permafrost-engine` | Expat XML parser integer overflow | CVE-2022-22827 | [PR #33](https://github.com/eduard-permyakov/permafrost-engine/pull/33) | ⏳ |
| 38 | `eduard-permyakov/permafrost-engine` | Expat XML namespace separator validation | CVE-2022-25236 | [PR #33](https://github.com/eduard-permyakov/permafrost-engine/pull/33) | ⏳ |
| 39 | `Tencent/Tendis` | Out-of-bounds read in `easyCopy` | — | [PR #492](https://github.com/Tencent/Tendis/pull/492) | ⏳ |
| 40 | `Tencent/Tendis` | Malformed Quicklist `RESTORE` crash | — | [PR #493](https://github.com/Tencent/Tendis/pull/493) | ⏳ |
| 41 | `Snapchat/KeyDB` | Cluster Bus message-length integer overflow | — | [PR #987](https://github.com/Snapchat/KeyDB/pull/987) | ⏳ |
| 42 | `Snapchat/KeyDB` | TLS pending-list use-after-free | — | [PR #988](https://github.com/Snapchat/KeyDB/pull/988) | ⏳ |
| 43 | `wireshark/wireshark` | Procmon PML memory amplification | — | [MR !28321](https://gitlab.com/wireshark/wireshark/-/merge_requests/28321) | ✅ |

---

*Only publicly disclosed fixes or public pull/merge requests are listed. Findings under coordinated disclosure are not included until publication or maintainer approval.*

*Statuses reflect the last recorded upstream state and may change. The CVE column identifies the underlying vulnerability addressed by each patch; it does not indicate CVE discoverer credit or a separate CVE assignment to each downstream project.*
