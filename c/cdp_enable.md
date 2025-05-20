# Function: <code>cdp_enable</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810438e6)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:625
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff810427fa)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:958
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81045c5f)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1026
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cdp_enable(int level, int data_type, int code_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt_rdtgroup.c (ffffffff81048420)
Location: arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:1072
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/intel_rdt_rdtgroup.c:rdt_mount
```
**Symbols:**

```
ffffffff81048420-ffffffff810484a2: cdp_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cdp_enable(int level, int data_type, int code_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81056660)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1798
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_mount
```
**Symbols:**

```
ffffffff81056660-ffffffff810566eb: cdp_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cdp_enable(int level, int data_type, int code_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81059730)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1796
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff81059730-ffffffff810597cc: cdp_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cdp_enable(int level, int data_type, int code_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105a000)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1794
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff8105a000-ffffffff8105a09c: cdp_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff810611c4)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1898
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105f5bb)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1949
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105fbff)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1949
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81069cb1)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1917
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81076fdd)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1917
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81087b2d)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1957
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8108aa8b)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2234
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled
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
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81091bfb)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:2325
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:resctrl_arch_set_cdp_enabled
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
int cdp_enable(int level, int data_type, int code_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81059b80)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1794
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff81059b80-ffffffff81059c1c: cdp_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cdp_enable(int level, int data_type, int code_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81049cf0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1794
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff81049cf0-ffffffff81049d8c: cdp_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cdp_enable(int level, int data_type, int code_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff81059fb0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1794
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff81059fb0-ffffffff8105a04c: cdp_enable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cdp_enable(int level, int data_type, int code_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/rdtgroup.c (ffffffff8105b4e0)
Location: arch/x86/kernel/cpu/resctrl/rdtgroup.c:1794
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdt_get_tree
```
**Symbols:**

```
ffffffff8105b4e0-ffffffff8105b57c: cdp_enable (STB_LOCAL)
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
