# Function: <code>mon_event_read</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void mon_event_read(struct rmid_read *rr, struct rdt_domain *d, struct rdtgroup *rdtgrp, int evtid, int first);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff81045044)
Location: arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:289
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_mondata_show
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir
```
**Symbols:**

```
ffffffff81044f90-ffffffff81044fcf: mon_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void mon_event_read(struct rmid_read *rr, struct rdt_domain *d, struct rdtgroup *rdtgrp, int evtid, int first);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff81048974)
Location: arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:319
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_mondata_show
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir
```
**Symbols:**

```
ffffffff810488c0-ffffffff810488ff: mon_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void mon_event_read(struct rmid_read *rr, struct rdt_domain *d, struct rdtgroup *rdtgrp, int evtid, int first);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c (ffffffff8104b2b5)
Location: arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:333
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_ctrlmondata.c:rdtgroup_mondata_show
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:mkdir_mondata_subdir
```
**Symbols:**

```
ffffffff8104b200-ffffffff8104b23f: mon_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void mon_event_read(struct rmid_read *rr, struct rdt_domain *d, struct rdtgroup *rdtgrp, int evtid, int first);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105bac7)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:506
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
```
**Symbols:**

```
ffffffff8105ba00-ffffffff8105ba3f: mon_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void mon_event_read(struct rmid_read *rr, struct rdt_domain *d, struct rdtgroup *rdtgrp, int evtid, int first);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105ee38)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:498
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
```
**Symbols:**

```
ffffffff8105ed70-ffffffff8105edaf: mon_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void mon_event_read(struct rmid_read *rr, struct rdt_domain *d, struct rdtgroup *rdtgrp, int evtid, int first);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105f6c1)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:498
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
```
**Symbols:**

```
ffffffff8105f5f0-ffffffff8105f62f: mon_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void mon_event_read(struct rmid_read *rr, struct rdt_resource *r, struct rdt_domain *d, struct rdtgroup *rdtgrp, int evtid, int first);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81065172)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:498
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
```
**Symbols:**

```
ffffffff81065090-ffffffff810650d4: mon_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void mon_event_read(struct rmid_read *rr, struct rdt_resource *r, struct rdt_domain *d, struct rdtgroup *rdtgrp, int evtid, int first);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81063365)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:432
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
```
**Symbols:**

```
ffffffff81063280-ffffffff810632c4: mon_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mon_event_read(struct rmid_read *rr, struct rdt_resource *r, struct rdt_domain *d, struct rdtgroup *rdtgrp, int evtid, int first);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81063ae5)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:432
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
```
**Symbols:**

```
ffffffff81063a00-ffffffff81063a44: mon_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mon_event_read(struct rmid_read *rr, struct rdt_resource *r, struct rdt_domain *d, struct rdtgroup *rdtgrp, int evtid, int first);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8106dad5)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:501
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
```
**Symbols:**

```
ffffffff8106d9f0-ffffffff8106da34: mon_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mon_event_read(struct rmid_read *rr, struct rdt_resource *r, struct rdt_domain *d, struct rdtgroup *rdtgrp, int evtid, int first);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8107b0bf)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:501
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
```
**Symbols:**

```
ffffffff8107afa0-ffffffff8107aff8: mon_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mon_event_read(struct rmid_read *rr, struct rdt_resource *r, struct rdt_domain *d, struct rdtgroup *rdtgrp, int evtid, int first);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108c3e1)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:531
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
```
**Symbols:**

```
ffffffff8108c2d0-ffffffff8108c328: mon_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mon_event_read(struct rmid_read *rr, struct rdt_resource *r, struct rdt_domain *d, struct rdtgroup *rdtgrp, int evtid, int first);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8108f230)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:523
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
```
**Symbols:**

```
ffffffff8108f120-ffffffff8108f178: mon_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mon_event_read(struct rmid_read *rr, struct rdt_resource *r, struct rdt_domain *d, struct rdtgroup *rdtgrp, int evtid, int first);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff810965c0)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:525
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
```
**Symbols:**

```
ffffffff810964b0-ffffffff81096508: mon_event_read (STB_GLOBAL)
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
void mon_event_read(struct rmid_read *rr, struct rdt_domain *d, struct rdtgroup *rdtgrp, int evtid, int first);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105f241)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:498
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
```
**Symbols:**

```
ffffffff8105f170-ffffffff8105f1af: mon_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void mon_event_read(struct rmid_read *rr, struct rdt_domain *d, struct rdtgroup *rdtgrp, int evtid, int first);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8104f571)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:498
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
```
**Symbols:**

```
ffffffff8104f4a0-ffffffff8104f4df: mon_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void mon_event_read(struct rmid_read *rr, struct rdt_domain *d, struct rdtgroup *rdtgrp, int evtid, int first);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff8105f671)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:498
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
```
**Symbols:**

```
ffffffff8105f5a0-ffffffff8105f5df: mon_event_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void mon_event_read(struct rmid_read *rr, struct rdt_domain *d, struct rdtgroup *rdtgrp, int evtid, int first);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/ctrlmondata.c (ffffffff81060bd1)
Location: arch/x86/kernel/cpu/resctrl/ctrlmondata.c:498
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/ctrlmondata.c:rdtgroup_mondata_show
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mkdir_mondata_subdir
```
**Symbols:**

```
ffffffff81060b00-ffffffff81060b3f: mon_event_read (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rdt_resource *r</code>
</li>
<li>
<b>Param reordered. </b>
<code>rr, d, rdtgrp, evtid, first</code> ➡️ <code>rr, r, d, rdtgrp, evtid, first</code>
</li>
</ul>
</details>
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
