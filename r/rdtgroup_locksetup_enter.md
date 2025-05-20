# Function: <code>rdtgroup_locksetup_enter</code>

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
int rdtgroup_locksetup_enter(struct rdtgroup *rdtgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105cfd0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:659
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
```
**Symbols:**

```
ffffffff8105cfd0-ffffffff8105d262: rdtgroup_locksetup_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int rdtgroup_locksetup_enter(struct rdtgroup *rdtgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060350)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:648
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
```
**Symbols:**

```
ffffffff81060350-ffffffff810605e7: rdtgroup_locksetup_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rdtgroup_locksetup_enter(struct rdtgroup *rdtgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060c00)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:648
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
```
**Symbols:**

```
ffffffff81060c00-ffffffff81060e97: rdtgroup_locksetup_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rdtgroup_locksetup_enter(struct rdtgroup *rdtgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff810668a0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:648
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
```
**Symbols:**

```
ffffffff810668a0-ffffffff81066ac1: rdtgroup_locksetup_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rdtgroup_locksetup_enter(struct rdtgroup *rdtgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81064af0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:648
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
```
**Symbols:**

```
ffffffff81064af0-ffffffff81064d11: rdtgroup_locksetup_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rdtgroup_locksetup_enter(struct rdtgroup *rdtgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81065090)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:648
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
```
**Symbols:**

```
ffffffff81065090-ffffffff8106533e: rdtgroup_locksetup_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rdtgroup_locksetup_enter(struct rdtgroup *rdtgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:652
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
```
**Symbols:**

```
ffffffff81c9cd78-ffffffff81c9cdb4: rdtgroup_locksetup_enter.cold (STB_LOCAL)
ffffffff8106f130-ffffffff8106f402: rdtgroup_locksetup_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rdtgroup_locksetup_enter(struct rdtgroup *rdtgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:652
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
```
**Symbols:**

```
ffffffff81e4c0d5-ffffffff81e4c114: rdtgroup_locksetup_enter.cold (STB_LOCAL)
ffffffff8107c980-ffffffff8107cc55: rdtgroup_locksetup_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int rdtgroup_locksetup_enter(struct rdtgroup *rdtgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:654
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
```
**Symbols:**

```
ffffffff8205370b-ffffffff8205374a: rdtgroup_locksetup_enter.cold (STB_LOCAL)
ffffffff8108dcd0-ffffffff8108dfa5: rdtgroup_locksetup_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int rdtgroup_locksetup_enter(struct rdtgroup *rdtgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:654
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
```
**Symbols:**

```
ffffffff820d1cfe-ffffffff820d1d3d: rdtgroup_locksetup_enter.cold (STB_LOCAL)
ffffffff81090b80-ffffffff81090e5a: rdtgroup_locksetup_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int rdtgroup_locksetup_enter(struct rdtgroup *rdtgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:668
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
```
**Symbols:**

```
ffffffff821ac962-ffffffff821ac9a1: rdtgroup_locksetup_enter.cold (STB_LOCAL)
ffffffff81097f10-ffffffff81098219: rdtgroup_locksetup_enter (STB_GLOBAL)
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
int rdtgroup_locksetup_enter(struct rdtgroup *rdtgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060780)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:648
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
```
**Symbols:**

```
ffffffff81060780-ffffffff81060a17: rdtgroup_locksetup_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rdtgroup_locksetup_enter(struct rdtgroup *rdtgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81050be0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:648
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
```
**Symbols:**

```
ffffffff81050be0-ffffffff81050e77: rdtgroup_locksetup_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rdtgroup_locksetup_enter(struct rdtgroup *rdtgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81060bb0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:648
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
```
**Symbols:**

```
ffffffff81060bb0-ffffffff81060e47: rdtgroup_locksetup_enter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rdtgroup_locksetup_enter(struct rdtgroup *rdtgrp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81062170)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:648
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/resctrl/rdtgroup.c:rdtgroup_mode_write
```
**Symbols:**

```
ffffffff81062170-ffffffff81062407: rdtgroup_locksetup_enter (STB_GLOBAL)
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
