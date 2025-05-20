# Function: <code>resctrl_arch_get_num_closid</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 resctrl_arch_get_num_closid(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810674d0)
Location: arch/x86/kernel/cpu/resctrl/core.c:349
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:schemata_list_add
```
**Symbols:**

```
ffffffff810674d0-ffffffff810674e1: resctrl_arch_get_num_closid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 resctrl_arch_get_num_closid(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81074190)
Location: arch/x86/kernel/cpu/resctrl/core.c:349
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:schemata_list_add
```
**Symbols:**

```
ffffffff81074190-ffffffff810741a7: resctrl_arch_get_num_closid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 resctrl_arch_get_num_closid(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff810843d0)
Location: arch/x86/kernel/cpu/resctrl/core.c:339
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:schemata_list_add
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mba_sc_domain_allocate
```
**Symbols:**

```
ffffffff810843d0-ffffffff810843e7: resctrl_arch_get_num_closid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 resctrl_arch_get_num_closid(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff81086980)
Location: arch/x86/kernel/cpu/resctrl/core.c:364
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:schemata_list_add
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mba_sc_domain_allocate
```
**Symbols:**

```
ffffffff81086980-ffffffff81086997: resctrl_arch_get_num_closid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 resctrl_arch_get_num_closid(struct rdt_resource *r);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff8108d8a0)
Location: arch/x86/kernel/cpu/resctrl/core.c:368
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:schemata_list_add
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:set_mba_sc
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:mba_sc_domain_allocate
```
**Symbols:**

```
ffffffff8108d8a0-ffffffff8108d8b7: resctrl_arch_get_num_closid (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
