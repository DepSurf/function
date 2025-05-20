# Function: <code>rdtgroup_locksetup_user_restore</code>

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
int rdtgroup_locksetup_user_restore(struct rdtgroup *rdtgrp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105c3a0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:606
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8105c3a0-ffffffff8105c462: rdtgroup_locksetup_user_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int rdtgroup_locksetup_user_restore(struct rdtgroup *rdtgrp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105f730)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:595
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8105f730-ffffffff8105f7f6: rdtgroup_locksetup_user_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int rdtgroup_locksetup_user_restore(struct rdtgroup *rdtgrp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105fff0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:595
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8105fff0-ffffffff810600b6: rdtgroup_locksetup_user_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81066b00)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:595
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff81065ac0-ffffffff81065b63: rdtgroup_locksetup_user_restore.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81064d50)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:595
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff81063d70-ffffffff81063e13: rdtgroup_locksetup_user_restore.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81065370)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:595
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff81064410-ffffffff810644b3: rdtgroup_locksetup_user_restore.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8106f44f)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8106e400-ffffffff8106e4b2: rdtgroup_locksetup_user_restore.part.0 (STB_LOCAL)
ffffffff81c9cd64-ffffffff81c9cd78: rdtgroup_locksetup_user_restore.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8107cc9d)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:599
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8107bc50-ffffffff8107bd0d: rdtgroup_locksetup_user_restore.part.0 (STB_LOCAL)
ffffffff81e4c0c0-ffffffff81e4c0d5: rdtgroup_locksetup_user_restore.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8108dffd)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:601
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8108d070-ffffffff8108d12d: rdtgroup_locksetup_user_restore.part.0 (STB_LOCAL)
ffffffff820536f6-ffffffff8205370b: rdtgroup_locksetup_user_restore.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81090ead)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:601
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8108ff00-ffffffff8108ffbd: rdtgroup_locksetup_user_restore.part.0 (STB_LOCAL)
ffffffff820d1ce9-ffffffff820d1cfe: rdtgroup_locksetup_user_restore.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8109826d)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:615
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff81097290-ffffffff8109734d: rdtgroup_locksetup_user_restore.part.0 (STB_LOCAL)
ffffffff821ac94d-ffffffff821ac962: rdtgroup_locksetup_user_restore.part.0.cold (STB_LOCAL)
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
int rdtgroup_locksetup_user_restore(struct rdtgroup *rdtgrp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105fb70)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:595
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8105fb70-ffffffff8105fc36: rdtgroup_locksetup_user_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int rdtgroup_locksetup_user_restore(struct rdtgroup *rdtgrp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8104fea0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:595
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8104fea0-ffffffff8104ff66: rdtgroup_locksetup_user_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int rdtgroup_locksetup_user_restore(struct rdtgroup *rdtgrp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff8105ffa0)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:595
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff8105ffa0-ffffffff81060066: rdtgroup_locksetup_user_restore (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int rdtgroup_locksetup_user_restore(struct rdtgroup *rdtgrp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/resctrl/pseudo_lock.c (ffffffff81061500)
Location: arch/x86/kernel/cpu/resctrl/pseudo_lock.c:595
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_exit
  - arch/x86/kernel/cpu/resctrl/pseudo_lock.c:rdtgroup_locksetup_enter
```
**Symbols:**

```
ffffffff81061500-ffffffff810615c6: rdtgroup_locksetup_user_restore (STB_LOCAL)
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
