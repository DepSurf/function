# Function: <code>optimize_nops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81035fbf)
Location: arch/x86/kernel/alternative.c:339
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:apply_alternatives
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff810351af)
Location: arch/x86/kernel/alternative.c:340
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:apply_alternatives
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void optimize_nops(struct alt_instr *a, u8 *instr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81034cd0)
Location: arch/x86/kernel/alternative.c:344
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff81034cd0-ffffffff81034d93: optimize_nops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void optimize_nops(struct alt_instr *a, u8 *instr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81032d00)
Location: arch/x86/kernel/alternative.c:344
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff81032d00-ffffffff81032dbc: optimize_nops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void optimize_nops(struct alt_instr *a, u8 *instr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81035050)
Location: arch/x86/kernel/alternative.c:333
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff81035050-ffffffff8103512f: optimize_nops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:333
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff810361d0-ffffffff81036263: optimize_nops.isra.5 (STB_LOCAL)
ffffffff81036e12-ffffffff81036e64: optimize_nops.isra.5.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:337
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff810373c0-ffffffff81037453: optimize_nops.isra.5 (STB_LOCAL)
ffffffff81038022-ffffffff81038074: optimize_nops.isra.5.cold.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:341
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff81039670-ffffffff81039700: optimize_nops.isra.0 (STB_LOCAL)
ffffffff8103a538-ffffffff8103a588: optimize_nops.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:341
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff81039e40-ffffffff81039ed0: optimize_nops.isra.0 (STB_LOCAL)
ffffffff8103ad18-ffffffff8103ad68: optimize_nops.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void optimize_nops(struct alt_instr *a, u8 *instr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:341
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff8103cab0-ffffffff8103cb3c: optimize_nops (STB_LOCAL)
ffffffff8103d99c-ffffffff8103d9ee: optimize_nops.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void optimize_nops(struct alt_instr *a, u8 *instr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:344
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff8103cf70-ffffffff8103cffc: optimize_nops (STB_LOCAL)
ffffffff81bd3ec2-ffffffff81bd3f14: optimize_nops.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void optimize_nops(struct alt_instr *a, u8 *instr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff8103eef0-ffffffff8103f05f: optimize_nops (STB_LOCAL)
ffffffff81bc6396-ffffffff81bc63f5: optimize_nops.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void optimize_nops(struct alt_instr *a, u8 *instr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff81044c90-ffffffff81044dff: optimize_nops (STB_LOCAL)
ffffffff81c993c6-ffffffff81c99425: optimize_nops.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void optimize_nops(u8 *instr, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:228
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_retpolines
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff8104c940-ffffffff8104cbb8: optimize_nops (STB_LOCAL)
ffffffff81e489b6-ffffffff81e48a32: optimize_nops.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void optimize_nops(u8 *instr, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81058cb0)
Location: arch/x86/kernel/alternative.c:229
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_retpolines
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff81058cb0-ffffffff81058fbe: optimize_nops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void optimize_nops(u8 *instr, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81059fb0)
Location: arch/x86/kernel/alternative.c:242
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_retpolines
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff81059fb0-ffffffff8105a0a8: optimize_nops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void optimize_nops(u8 *instr, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81061120)
Location: arch/x86/kernel/alternative.c:242
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_retpolines
  - arch/x86/kernel/alternative.c:optimize_nops_inplace
```
**Symbols:**

```
ffffffff81061120-ffffffff81061218: optimize_nops (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:341
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff81039fa0-ffffffff8103a030: optimize_nops.isra.0 (STB_LOCAL)
ffffffff8103ae78-ffffffff8103aec8: optimize_nops.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:341
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff81029890-ffffffff8102990c: optimize_nops.isra.0 (STB_LOCAL)
ffffffff8102a688-ffffffff8102a6d8: optimize_nops.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:341
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff81039e00-ffffffff81039e90: optimize_nops.isra.0 (STB_LOCAL)
ffffffff8103acd8-ffffffff8103ad28: optimize_nops.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:341
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:apply_alternatives
```
**Symbols:**

```
ffffffff8103ae00-ffffffff8103ae90: optimize_nops.isra.0 (STB_LOCAL)
ffffffff8103bcd8-ffffffff8103bd28: optimize_nops.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>size_t len</code>
</li>
<li>
<b>Param removed. </b>
<code>struct alt_instr *a</code>
</li>
<li>
<b>Param reordered. </b>
<code>a, instr</code> ➡️ <code>instr, len</code>
</li>
</ul>
</details>
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
