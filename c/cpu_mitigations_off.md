# Function: <code>cpu_mitigations_off</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff828ac2ed)
Location: include/linux/cpu.h:227
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/mm/pti.c (ffffffff828beae4)
Location: include/linux/cpu.h:227
Inline: True
Inline callers:
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool cpu_mitigations_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a1b10)
Location: kernel/cpu.c:2412
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
**Symbols:**

```
ffffffff810a1b10-ffffffff810a1b26: cpu_mitigations_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool cpu_mitigations_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a8970)
Location: kernel/cpu.c:2543
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:srbds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v1_select_mitigation
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
**Symbols:**

```
ffffffff810a8970-ffffffff810a8986: cpu_mitigations_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool cpu_mitigations_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a43c0)
Location: kernel/cpu.c:2554
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:ssb_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:srbds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v1_select_mitigation
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
**Symbols:**

```
ffffffff810a43c0-ffffffff810a43d6: cpu_mitigations_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool cpu_mitigations_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a5070)
Location: kernel/cpu.c:2674
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_select_mitigation
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
**Symbols:**

```
ffffffff810a5070-ffffffff810a5086: cpu_mitigations_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool cpu_mitigations_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b6890)
Location: kernel/cpu.c:2701
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
**Symbols:**

```
ffffffff810b6890-ffffffff810b68a6: cpu_mitigations_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool cpu_mitigations_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810cce10)
Location: kernel/cpu.c:2723
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:md_clear_update_mitigation
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:retbleed_select_mitigation
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
**Symbols:**

```
ffffffff810cce10-ffffffff810cce2a: cpu_mitigations_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool cpu_mitigations_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810eae00)
Location: kernel/cpu.c:2750
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:md_clear_update_mitigation
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:retbleed_select_mitigation
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
**Symbols:**

```
ffffffff810eae00-ffffffff810eae1a: cpu_mitigations_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool cpu_mitigations_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810f6a40)
Location: kernel/cpu.c:3147
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
  - arch/x86/kernel/cpu/bugs.c:srso_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:md_clear_update_mitigation
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:retbleed_select_mitigation
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
**Symbols:**

```
ffffffff810f6a40-ffffffff810f6a5a: cpu_mitigations_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool cpu_mitigations_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ffdf0)
Location: kernel/cpu.c:3229
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:spectre_v2_parse_cmdline
  - arch/x86/kernel/cpu/bugs.c:rfds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
  - arch/x86/kernel/cpu/bugs.c:cpu_select_mitigations
  - arch/x86/kernel/cpu/bugs.c:srso_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:md_clear_update_mitigation
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:retbleed_select_mitigation
  - arch/x86/mm/pti.c:pti_check_boottime_disable
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/verifier.c:bpf_check
  - kernel/bpf/arraymap.c:array_map_alloc
```
**Symbols:**

```
ffffffff810ffdf0-ffffffff810ffe0a: cpu_mitigations_off (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool cpu_mitigations_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f6ce8)
Location: kernel/cpu.c:2412
Inline: False
Direct callers:
  - arch/arm64/kernel/cpu_errata.c:has_ssbd_mitigation
  - arch/arm64/kernel/cpufeature.c:unmap_kernel_at_el0
  - arch/arm64/kernel/cpufeature.c:unmap_kernel_at_el0
```
**Symbols:**

```
ffff8000100f6ce8-ffff8000100f6d10: cpu_mitigations_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool cpu_mitigations_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0354ddc)
Location: kernel/cpu.c:2412
Inline: False
```
**Symbols:**

```
c0354ddc-c0354e08: cpu_mitigations_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool cpu_mitigations_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c00000000013cc10)
Location: kernel/cpu.c:2412
Inline: False
Direct callers:
  - arch/powerpc/kernel/setup_64.c:setup_rfi_flush
  - arch/powerpc/kernel/security.c:setup_count_cache_flush
  - arch/powerpc/kernel/security.c:setup_stf_barrier
  - arch/powerpc/kernel/security.c:setup_barrier_nospec
```
**Symbols:**

```
c00000000013cc10-c00000000013cc34: cpu_mitigations_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool cpu_mitigations_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffe0000c287a)
Location: kernel/cpu.c:2412
Inline: False
```
**Symbols:**

```
ffffffe0000c287a-ffffffe0000c28a0: cpu_mitigations_off (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool cpu_mitigations_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109b430)
Location: kernel/cpu.c:2412
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
**Symbols:**

```
ffffffff8109b430-ffffffff8109b446: cpu_mitigations_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool cpu_mitigations_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81089e60)
Location: kernel/cpu.c:2412
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
**Symbols:**

```
ffffffff81089e60-ffffffff81089e76: cpu_mitigations_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool cpu_mitigations_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109b3e0)
Location: kernel/cpu.c:2412
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
**Symbols:**

```
ffffffff8109b3e0-ffffffff8109b3f6: cpu_mitigations_off (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool cpu_mitigations_off();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a3050)
Location: kernel/cpu.c:2412
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:__ssb_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/mm/pti.c:pti_check_boottime_disable
```
**Symbols:**

```
ffffffff810a3050-ffffffff810a3066: cpu_mitigations_off (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
