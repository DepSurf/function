# Function: <code>cpu_mitigations_auto_nosmt</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff828acb09)
Location: include/linux/cpu.h:233
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool cpu_mitigations_auto_nosmt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a1b30)
Location: kernel/cpu.c:2419
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
```
**Symbols:**

```
ffffffff810a1b30-ffffffff810a1b45: cpu_mitigations_auto_nosmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool cpu_mitigations_auto_nosmt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a8990)
Location: kernel/cpu.c:2550
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
```
**Symbols:**

```
ffffffff810a8990-ffffffff810a89a5: cpu_mitigations_auto_nosmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool cpu_mitigations_auto_nosmt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a43e0)
Location: kernel/cpu.c:2561
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
```
**Symbols:**

```
ffffffff810a43e0-ffffffff810a43f5: cpu_mitigations_auto_nosmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool cpu_mitigations_auto_nosmt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a5090)
Location: kernel/cpu.c:2681
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
```
**Symbols:**

```
ffffffff810a5090-ffffffff810a50a5: cpu_mitigations_auto_nosmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool cpu_mitigations_auto_nosmt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b68b0)
Location: kernel/cpu.c:2708
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
```
**Symbols:**

```
ffffffff810b68b0-ffffffff810b68c5: cpu_mitigations_auto_nosmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool cpu_mitigations_auto_nosmt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810cce30)
Location: kernel/cpu.c:2730
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:retbleed_select_mitigation
```
**Symbols:**

```
ffffffff810cce30-ffffffff810cce49: cpu_mitigations_auto_nosmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool cpu_mitigations_auto_nosmt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810eae30)
Location: kernel/cpu.c:2757
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:retbleed_select_mitigation
```
**Symbols:**

```
ffffffff810eae30-ffffffff810eae49: cpu_mitigations_auto_nosmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool cpu_mitigations_auto_nosmt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810f6a70)
Location: kernel/cpu.c:3154
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:retbleed_select_mitigation
```
**Symbols:**

```
ffffffff810f6a70-ffffffff810f6a89: cpu_mitigations_auto_nosmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool cpu_mitigations_auto_nosmt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ffe20)
Location: kernel/cpu.c:3236
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:mmio_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:taa_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
  - arch/x86/kernel/cpu/bugs.c:retbleed_select_mitigation
```
**Symbols:**

```
ffffffff810ffe20-ffffffff810ffe39: cpu_mitigations_auto_nosmt (STB_GLOBAL)
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
bool cpu_mitigations_auto_nosmt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f6d10)
Location: kernel/cpu.c:2419
Inline: False
```
**Symbols:**

```
ffff8000100f6d10-ffff8000100f6d38: cpu_mitigations_auto_nosmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool cpu_mitigations_auto_nosmt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0354e08)
Location: kernel/cpu.c:2419
Inline: False
```
**Symbols:**

```
c0354e08-c0354e38: cpu_mitigations_auto_nosmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool cpu_mitigations_auto_nosmt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c00000000013cc40)
Location: kernel/cpu.c:2419
Inline: False
```
**Symbols:**

```
c00000000013cc40-c00000000013cc68: cpu_mitigations_auto_nosmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool cpu_mitigations_auto_nosmt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffe0000c28a0)
Location: kernel/cpu.c:2419
Inline: False
```
**Symbols:**

```
ffffffe0000c28a0-ffffffe0000c28c8: cpu_mitigations_auto_nosmt (STB_GLOBAL)
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
bool cpu_mitigations_auto_nosmt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109b450)
Location: kernel/cpu.c:2419
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
```
**Symbols:**

```
ffffffff8109b450-ffffffff8109b465: cpu_mitigations_auto_nosmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool cpu_mitigations_auto_nosmt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81089e80)
Location: kernel/cpu.c:2419
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
```
**Symbols:**

```
ffffffff81089e80-ffffffff81089e95: cpu_mitigations_auto_nosmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool cpu_mitigations_auto_nosmt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109b400)
Location: kernel/cpu.c:2419
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
```
**Symbols:**

```
ffffffff8109b400-ffffffff8109b415: cpu_mitigations_auto_nosmt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool cpu_mitigations_auto_nosmt();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a3070)
Location: kernel/cpu.c:2419
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:check_bugs
  - arch/x86/kernel/cpu/bugs.c:mds_select_mitigation
```
**Symbols:**

```
ffffffff810a3070-ffffffff810a3085: cpu_mitigations_auto_nosmt (STB_GLOBAL)
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
