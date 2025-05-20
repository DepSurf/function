# Function: <code>rdtgroup_cbm_overlaps</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool rdtgroup_cbm_overlaps(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm, int closid, bool exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810580c0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1120
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff810580c0-ffffffff81058162: rdtgroup_cbm_overlaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool rdtgroup_cbm_overlaps(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm, int closid, bool exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b660)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1118
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff8105b660-ffffffff8105b701: rdtgroup_cbm_overlaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool rdtgroup_cbm_overlaps(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm, int closid, bool exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105bf70)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1116
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff8105bf70-ffffffff8105c011: rdtgroup_cbm_overlaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool rdtgroup_cbm_overlaps(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm, int closid, bool exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81061f30)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1207
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_test_exclusive
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff81061f30-ffffffff81061fcd: rdtgroup_cbm_overlaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool rdtgroup_cbm_overlaps(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm, int closid, bool exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060480)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1229
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_test_exclusive
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff81060480-ffffffff8106051d: rdtgroup_cbm_overlaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool rdtgroup_cbm_overlaps(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm, int closid, bool exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060670)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1229
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff81060670-ffffffff8106070d: rdtgroup_cbm_overlaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool rdtgroup_cbm_overlaps(struct resctrl_schema *s, struct rdt_domain *d, long unsigned int cbm, int closid, bool exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1183
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff81c9c92b-ffffffff81c9c94c: rdtgroup_cbm_overlaps.cold (STB_LOCAL)
ffffffff81069860-ffffffff81069914: rdtgroup_cbm_overlaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool rdtgroup_cbm_overlaps(struct resctrl_schema *s, struct rdt_domain *d, long unsigned int cbm, int closid, bool exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1183
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff81e4bc62-ffffffff81e4bc7d: rdtgroup_cbm_overlaps.cold (STB_LOCAL)
ffffffff81076b10-ffffffff81076bee: rdtgroup_cbm_overlaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool rdtgroup_cbm_overlaps(struct resctrl_schema *s, struct rdt_domain *d, long unsigned int cbm, int closid, bool exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1180
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff820532da-ffffffff820532f5: rdtgroup_cbm_overlaps.cold (STB_LOCAL)
ffffffff81087610-ffffffff810876ee: rdtgroup_cbm_overlaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool rdtgroup_cbm_overlaps(struct resctrl_schema *s, struct rdt_domain *d, long unsigned int cbm, int closid, bool exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1195
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff820d18fc-ffffffff820d1917: rdtgroup_cbm_overlaps.cold (STB_LOCAL)
ffffffff8108a570-ffffffff8108a64e: rdtgroup_cbm_overlaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool rdtgroup_cbm_overlaps(struct resctrl_schema *s, struct rdt_domain *d, long unsigned int cbm, int closid, bool exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1263
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff821ac536-ffffffff821ac551: rdtgroup_cbm_overlaps.cold (STB_LOCAL)
ffffffff81091690-ffffffff8109176e: rdtgroup_cbm_overlaps (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
bool rdtgroup_cbm_overlaps(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm, int closid, bool exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105baf0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1116
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff8105baf0-ffffffff8105bb91: rdtgroup_cbm_overlaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool rdtgroup_cbm_overlaps(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm, int closid, bool exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104bcc0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1116
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff8104bcc0-ffffffff8104bd61: rdtgroup_cbm_overlaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool rdtgroup_cbm_overlaps(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm, int closid, bool exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105bf20)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1116
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff8105bf20-ffffffff8105bfc1: rdtgroup_cbm_overlaps (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool rdtgroup_cbm_overlaps(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm, int closid, bool exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d430)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1116
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:parse_cbm
```
**Symbols:**

```
ffffffff8105d430-ffffffff8105d4d1: rdtgroup_cbm_overlaps (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct resctrl_schema *s</code>
</li>
<li>
<b>Param removed. </b>
<code>struct rdt_resource *r</code>
</li>
</ul>
</details>
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
