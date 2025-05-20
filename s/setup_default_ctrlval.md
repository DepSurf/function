# Function: <code>setup_default_ctrlval</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void setup_default_ctrlval(struct rdt_resource *r, u32 *dc, u32 *dm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff81046dc3)
Location: arch/x86/kernel/cpu/intel_rdt.c:442
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_online_cpu
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:set_mba_sc
```
**Symbols:**

```
ffffffff81047180-ffffffff810471aa: setup_default_ctrlval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void setup_default_ctrlval(struct rdt_resource *r, u32 *dc, u32 *dm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81055ddc)
Location: arch/x86/kernel/cpu/resctrl/core.c:475
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
**Symbols:**

```
ffffffff810561a0-ffffffff810561ca: setup_default_ctrlval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void setup_default_ctrlval(struct rdt_resource *r, u32 *dc, u32 *dm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059011)
Location: arch/x86/kernel/cpu/resctrl/core.c:467
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
**Symbols:**

```
ffffffff81059370-ffffffff8105939a: setup_default_ctrlval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void setup_default_ctrlval(struct rdt_resource *r, u32 *dc, u32 *dm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810598e1)
Location: arch/x86/kernel/cpu/resctrl/core.c:467
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
**Symbols:**

```
ffffffff81059c40-ffffffff81059c6a: setup_default_ctrlval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void setup_default_ctrlval(struct rdt_resource *r, u32 *dc, u32 *dm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105ed6e)
Location: arch/x86/kernel/cpu/resctrl/core.c:467
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
**Symbols:**

```
ffffffff8105efb0-ffffffff8105efdd: setup_default_ctrlval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void setup_default_ctrlval(struct rdt_resource *r, u32 *dc, u32 *dm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105d2b4)
Location: arch/x86/kernel/cpu/resctrl/core.c:469
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
**Symbols:**

```
ffffffff8105d4f0-ffffffff8105d51d: setup_default_ctrlval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void setup_default_ctrlval(struct rdt_resource *r, u32 *dc, u32 *dm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105da99)
Location: arch/x86/kernel/cpu/resctrl/core.c:469
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
**Symbols:**

```
ffffffff8105de20-ffffffff8105de4a: setup_default_ctrlval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void setup_default_ctrlval(struct rdt_resource *r, u32 *dc, u32 *dm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8106717c)
Location: arch/x86/kernel/cpu/resctrl/core.c:404
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
**Symbols:**

```
ffffffff810675c0-ffffffff810675f0: setup_default_ctrlval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void setup_default_ctrlval(struct rdt_resource *r, u32 *dc, u32 *dm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81073d78)
Location: arch/x86/kernel/cpu/resctrl/core.c:404
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
**Symbols:**

```
ffffffff810742b0-ffffffff810742ee: setup_default_ctrlval (STB_GLOBAL)
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81084163)
Location: arch/x86/kernel/cpu/resctrl/core.c:394
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81086703)
Location: arch/x86/kernel/cpu/resctrl/core.c:419
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108d618)
Location: arch/x86/kernel/cpu/resctrl/core.c:423
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:domain_add_cpu
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
void setup_default_ctrlval(struct rdt_resource *r, u32 *dc, u32 *dm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059461)
Location: arch/x86/kernel/cpu/resctrl/core.c:467
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
**Symbols:**

```
ffffffff810597c0-ffffffff810597ea: setup_default_ctrlval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void setup_default_ctrlval(struct rdt_resource *r, u32 *dc, u32 *dm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81049681)
Location: arch/x86/kernel/cpu/resctrl/core.c:467
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
**Symbols:**

```
ffffffff810499e0-ffffffff81049a0a: setup_default_ctrlval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void setup_default_ctrlval(struct rdt_resource *r, u32 *dc, u32 *dm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81059891)
Location: arch/x86/kernel/cpu/resctrl/core.c:467
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
**Symbols:**

```
ffffffff81059bf0-ffffffff81059c1a: setup_default_ctrlval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void setup_default_ctrlval(struct rdt_resource *r, u32 *dc, u32 *dm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8105ad31)
Location: arch/x86/kernel/cpu/resctrl/core.c:467
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_online_cpu
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
```
**Symbols:**

```
ffffffff8105b090-ffffffff8105b0ba: setup_default_ctrlval (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
