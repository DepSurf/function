# Function: <code>rdtgroup_mode_by_closid</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
enum rdtgrp_mode rdtgroup_mode_by_closid(int closid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105795f)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:161
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
```
**Symbols:**

```
ffffffff81057fe0-ffffffff81058027: rdtgroup_mode_by_closid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
enum rdtgrp_mode rdtgroup_mode_by_closid(int closid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105abc7)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
```
**Symbols:**

```
ffffffff8105b560-ffffffff8105b5a4: rdtgroup_mode_by_closid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
enum rdtgrp_mode rdtgroup_mode_by_closid(int closid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b4b7)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
```
**Symbols:**

```
ffffffff8105be70-ffffffff8105beb4: rdtgroup_mode_by_closid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
enum rdtgrp_mode rdtgroup_mode_by_closid(int closid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810618a2)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
```
**Symbols:**

```
ffffffff81061d00-ffffffff81061d44: rdtgroup_mode_by_closid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
enum rdtgrp_mode rdtgroup_mode_by_closid(int closid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105fcb2)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
```
**Symbols:**

```
ffffffff81060220-ffffffff81060264: rdtgroup_mode_by_closid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
enum rdtgrp_mode rdtgroup_mode_by_closid(int closid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060242)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
```
**Symbols:**

```
ffffffff81060410-ffffffff81060454: rdtgroup_mode_by_closid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
enum rdtgrp_mode rdtgroup_mode_by_closid(int closid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81069376)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:158
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
```
**Symbols:**

```
ffffffff810695c0-ffffffff81069604: rdtgroup_mode_by_closid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
enum rdtgrp_mode rdtgroup_mode_by_closid(int closid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810765d7)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:158
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
```
**Symbols:**

```
ffffffff81076840-ffffffff81076894: rdtgroup_mode_by_closid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
enum rdtgrp_mode rdtgroup_mode_by_closid(int closid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108709f)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:158
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
```
**Symbols:**

```
ffffffff81087310-ffffffff81087364: rdtgroup_mode_by_closid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
enum rdtgrp_mode rdtgroup_mode_by_closid(int closid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81089f4f)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:171
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
```
**Symbols:**

```
ffffffff8108a270-ffffffff8108a2c4: rdtgroup_mode_by_closid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
enum rdtgrp_mode rdtgroup_mode_by_closid(int closid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8109106f)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:176
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__init_one_rdt_domain
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
```
**Symbols:**

```
ffffffff81091390-ffffffff810913e4: rdtgroup_mode_by_closid (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
enum rdtgrp_mode rdtgroup_mode_by_closid(int closid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b037)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
```
**Symbols:**

```
ffffffff8105b9f0-ffffffff8105ba34: rdtgroup_mode_by_closid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
enum rdtgrp_mode rdtgroup_mode_by_closid(int closid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104b1c7)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
```
**Symbols:**

```
ffffffff8104bbc0-ffffffff8104bc04: rdtgroup_mode_by_closid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
enum rdtgrp_mode rdtgroup_mode_by_closid(int closid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b467)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
```
**Symbols:**

```
ffffffff8105be20-ffffffff8105be64: rdtgroup_mode_by_closid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
enum rdtgrp_mode rdtgroup_mode_by_closid(int closid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c927)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:155
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:__rdtgroup_cbm_overlaps
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_bit_usage_show
```
**Symbols:**

```
ffffffff8105d310-ffffffff8105d354: rdtgroup_mode_by_closid (STB_GLOBAL)
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
