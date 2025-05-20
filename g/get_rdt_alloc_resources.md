# Function: <code>get_rdt_alloc_resources</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff820ae80a)
Location: arch/x86/kernel/cpu/intel_rdt.c:719
Inline: True
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
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff826b5065)
Location: arch/x86/kernel/cpu/intel_rdt.c:722
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel_rdt.c (ffffffff826ded11)
Location: arch/x86/kernel/cpu/intel_rdt.c:792
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel_rdt.c:intel_rdt_late_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82897db0)
Location: arch/x86/kernel/cpu/resctrl/core.c:843
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828af98a)
Location: arch/x86/kernel/cpu/resctrl/core.c:835
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828b2cc3)
Location: arch/x86/kernel/cpu/resctrl/core.c:835
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool get_rdt_alloc_resources();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82cd7cf4)
Location: arch/x86/kernel/cpu/resctrl/core.c:837
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff82cd7cf4-ffffffff82cd7f31: get_rdt_alloc_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool get_rdt_alloc_resources();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82fc3cc7)
Location: arch/x86/kernel/cpu/resctrl/core.c:841
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff82fc3cc7-ffffffff82fc3e80: get_rdt_alloc_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool get_rdt_alloc_resources();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff831ce2ad)
Location: arch/x86/kernel/cpu/resctrl/core.c:841
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff831ce2ad-ffffffff831ce51f: get_rdt_alloc_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool get_rdt_alloc_resources();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff832b04c0)
Location: arch/x86/kernel/cpu/resctrl/core.c:784
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff832b04c0-ffffffff832b072a: get_rdt_alloc_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool get_rdt_alloc_resources();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff834615b7)
Location: arch/x86/kernel/cpu/resctrl/core.c:784
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff834615b7-ffffffff8346182f: get_rdt_alloc_resources (STB_LOCAL)
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
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff83e836a6)
Location: arch/x86/kernel/cpu/resctrl/core.c:737
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:get_rdt_resources
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool get_rdt_alloc_resources();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff836a69b0)
Location: arch/x86/kernel/cpu/resctrl/core.c:779
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff836a69b0-ffffffff836a6c31: get_rdt_alloc_resources (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool get_rdt_alloc_resources();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff838d6fa0)
Location: arch/x86/kernel/cpu/resctrl/core.c:783
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
**Symbols:**

```
ffffffff838d6fa0-ffffffff838d7318: get_rdt_alloc_resources (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828a0ce2)
Location: arch/x86/kernel/cpu/resctrl/core.c:835
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff82898e45)
Location: arch/x86/kernel/cpu/resctrl/core.c:835
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828b3ca5)
Location: arch/x86/kernel/cpu/resctrl/core.c:835
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/core.c (ffffffff828b3cd3)
Location: arch/x86/kernel/cpu/resctrl/core.c:835
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/core.c:resctrl_late_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
