# Function: <code>rdtgroup_cbm_to_size</code>

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
unsigned int rdtgroup_cbm_to_size(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81058170)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1262
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff81058170-ffffffff81058218: rdtgroup_cbm_to_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int rdtgroup_cbm_to_size(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b710)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1260
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff8105b710-ffffffff8105b7ac: rdtgroup_cbm_to_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int rdtgroup_cbm_to_size(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105c020)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1258
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff8105c020-ffffffff8105c0bc: rdtgroup_cbm_to_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int rdtgroup_cbm_to_size(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810620b0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1349
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_init
```
**Symbols:**

```
ffffffff810620b0-ffffffff8106214c: rdtgroup_cbm_to_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int rdtgroup_cbm_to_size(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060600)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1371
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_init
```
**Symbols:**

```
ffffffff81060600-ffffffff8106069c: rdtgroup_cbm_to_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int rdtgroup_cbm_to_size(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81060710)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1371
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
```
**Symbols:**

```
ffffffff81060710-ffffffff810607ab: rdtgroup_cbm_to_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int rdtgroup_cbm_to_size(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81069920)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1329
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
```
**Symbols:**

```
ffffffff81069920-ffffffff810699bb: rdtgroup_cbm_to_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int rdtgroup_cbm_to_size(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81076bf0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1329
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:pseudo_lock_region_alloc
```
**Symbols:**

```
ffffffff81076bf0-ffffffff81076ca9: rdtgroup_cbm_to_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int rdtgroup_cbm_to_size(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81087700)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1326
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff81087700-ffffffff810877b9: rdtgroup_cbm_to_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int rdtgroup_cbm_to_size(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108a660)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1341
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff8108a660-ffffffff8108a719: rdtgroup_cbm_to_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int rdtgroup_cbm_to_size(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81091780)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1409
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff81091780-ffffffff81091839: rdtgroup_cbm_to_size (STB_GLOBAL)
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
unsigned int rdtgroup_cbm_to_size(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105bba0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1258
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff8105bba0-ffffffff8105bc3c: rdtgroup_cbm_to_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int rdtgroup_cbm_to_size(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8104bd70)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1258
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff8104bd70-ffffffff8104be0c: rdtgroup_cbm_to_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int rdtgroup_cbm_to_size(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105bfd0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1258
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff8105bfd0-ffffffff8105c06c: rdtgroup_cbm_to_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int rdtgroup_cbm_to_size(struct rdt_resource *r, struct rdt_domain *d, long unsigned int cbm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105d4e0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1258
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_size_show
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_pseudo_lock_create
```
**Symbols:**

```
ffffffff8105d4e0-ffffffff8105d57c: rdtgroup_cbm_to_size (STB_GLOBAL)
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
