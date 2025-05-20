# Function: <code>rmdir_mondata_subdir_allrdtgrp</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rmdir_mondata_subdir_allrdtgrp(struct rdt_resource *r, unsigned int dom_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81043f30)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1355
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
**Symbols:**

```
ffffffff81043f30-ffffffff81044012: rmdir_mondata_subdir_allrdtgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rmdir_mondata_subdir_allrdtgrp(struct rdt_resource *r, unsigned int dom_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81047700)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1426
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
**Symbols:**

```
ffffffff81047700-ffffffff810477e2: rmdir_mondata_subdir_allrdtgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rmdir_mondata_subdir_allrdtgrp(struct rdt_resource *r, unsigned int dom_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81049cc0)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1526
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_offline_cpu
```
**Symbols:**

```
ffffffff81049cc0-ffffffff81049da2: rmdir_mondata_subdir_allrdtgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rmdir_mondata_subdir_allrdtgrp(struct rdt_resource *r, unsigned int dom_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105a040)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2272
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
**Symbols:**

```
ffffffff8105a040-ffffffff8105a122: rmdir_mondata_subdir_allrdtgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rmdir_mondata_subdir_allrdtgrp(struct rdt_resource *r, unsigned int dom_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d300)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2314
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
**Symbols:**

```
ffffffff8105d300-ffffffff8105d3db: rmdir_mondata_subdir_allrdtgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rmdir_mondata_subdir_allrdtgrp(struct rdt_resource *r, unsigned int dom_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105dbf0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2320
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
**Symbols:**

```
ffffffff8105dbf0-ffffffff8105dccb: rmdir_mondata_subdir_allrdtgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rmdir_mondata_subdir_allrdtgrp(struct rdt_resource *r, unsigned int dom_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81063540)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2419
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
**Symbols:**

```
ffffffff81063540-ffffffff8106361b: rmdir_mondata_subdir_allrdtgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rmdir_mondata_subdir_allrdtgrp(struct rdt_resource *r, unsigned int dom_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810619d0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2455
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
**Symbols:**

```
ffffffff810619d0-ffffffff81061aab: rmdir_mondata_subdir_allrdtgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rmdir_mondata_subdir_allrdtgrp(struct rdt_resource *r, unsigned int dom_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810621a0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2451
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
**Symbols:**

```
ffffffff810621a0-ffffffff8106227b: rmdir_mondata_subdir_allrdtgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void rmdir_mondata_subdir_allrdtgrp(struct rdt_resource *r, unsigned int dom_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2502
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
**Symbols:**

```
ffffffff81c9cbd9-ffffffff81c9cbed: rmdir_mondata_subdir_allrdtgrp.cold (STB_LOCAL)
ffffffff8106bfa0-ffffffff8106c087: rmdir_mondata_subdir_allrdtgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rmdir_mondata_subdir_allrdtgrp(struct rdt_resource *r, unsigned int dom_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2502
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_remove_cpu
```
**Symbols:**

```
ffffffff81e4bf28-ffffffff81e4bf3c: rmdir_mondata_subdir_allrdtgrp.cold (STB_LOCAL)
ffffffff810792d0-ffffffff810793e5: rmdir_mondata_subdir_allrdtgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81089e7f)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2550
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108cef5)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2832
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81094285)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2960
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_offline_domain
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
void rmdir_mondata_subdir_allrdtgrp(struct rdt_resource *r, unsigned int dom_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d770)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2320
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
**Symbols:**

```
ffffffff8105d770-ffffffff8105d84b: rmdir_mondata_subdir_allrdtgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rmdir_mondata_subdir_allrdtgrp(struct rdt_resource *r, unsigned int dom_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104d940)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2320
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
**Symbols:**

```
ffffffff8104d940-ffffffff8104da1b: rmdir_mondata_subdir_allrdtgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rmdir_mondata_subdir_allrdtgrp(struct rdt_resource *r, unsigned int dom_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105dba0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2320
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
**Symbols:**

```
ffffffff8105dba0-ffffffff8105dc7b: rmdir_mondata_subdir_allrdtgrp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rmdir_mondata_subdir_allrdtgrp(struct rdt_resource *r, unsigned int dom_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105f0c0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2320
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_offline_cpu
```
**Symbols:**

```
ffffffff8105f0c0-ffffffff8105f19b: rmdir_mondata_subdir_allrdtgrp (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
