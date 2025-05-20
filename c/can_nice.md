# Function: <code>can_nice</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int can_nice(const struct task_struct *p, const int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810a6690)
Location: kernel/sched/core.c:3504
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:SyS_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:SyS_nice
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810a6690-ffffffff810a66a8: can_nice.part.85 (STB_LOCAL)
ffffffff810ad790-ffffffff810ad7c3: can_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int can_nice(const struct task_struct *p, const int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810ac574)
Location: kernel/sched/core.c:3757
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:SyS_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:SyS_nice
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810aa650-ffffffff810aa668: can_nice.part.88 (STB_LOCAL)
ffffffff810b0140-ffffffff810b0173: can_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int can_nice(const struct task_struct *p, const int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810b2692)
Location: kernel/sched/core.c:3794
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:SyS_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:SyS_nice
  - kernel/sched/auto_group.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810b0740-ffffffff810b0758: can_nice.part.87 (STB_LOCAL)
ffffffff810b62d0-ffffffff810b6303: can_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int can_nice(const struct task_struct *p, const int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810ae9d7)
Location: kernel/sched/core.c:3800
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:SyS_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:SyS_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810acb90-ffffffff810acba8: can_nice.part.79 (STB_LOCAL)
ffffffff810b2550-ffffffff810b2583: can_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int can_nice(const struct task_struct *p, const int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810b5c2e)
Location: kernel/sched/core.c:3844
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:SyS_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:SyS_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810b3c30-ffffffff810b3c48: can_nice.part.78 (STB_LOCAL)
ffffffff810b9950-ffffffff810b9983: can_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int can_nice(const struct task_struct *p, const int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810bd8b6)
Location: kernel/sched/core.c:3954
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810bada0-ffffffff810badb8: can_nice.part.74 (STB_LOCAL)
ffffffff810c1410-ffffffff810c1443: can_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int can_nice(const struct task_struct *p, const int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810c6a91)
Location: kernel/sched/core.c:3938
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810c40b0-ffffffff810c40c8: can_nice.part.63 (STB_LOCAL)
ffffffff810c40d0-ffffffff810c4103: can_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int can_nice(const struct task_struct *p, const int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810cce39)
Location: kernel/sched/core.c:4357
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810c9e80-ffffffff810c9e98: can_nice.part.0 (STB_LOCAL)
ffffffff810c9ea0-ffffffff810c9ed3: can_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int can_nice(const struct task_struct *p, const int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810d683f)
Location: kernel/sched/core.c:4559
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810d3090-ffffffff810d30a8: can_nice.part.0 (STB_LOCAL)
ffffffff810d30b0-ffffffff810d30e3: can_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int can_nice(const struct task_struct *p, const int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e0c68)
Location: kernel/sched/core.c:4792
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810dd020-ffffffff810dd062: can_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int can_nice(const struct task_struct *p, const int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810de0c3)
Location: kernel/sched/core.c:5565
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810d98c0-ffffffff810d9902: can_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int can_nice(const struct task_struct *p, const int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dfc18)
Location: kernel/sched/core.c:5776
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810db2f0-ffffffff810db32b: can_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int can_nice(const struct task_struct *p, const int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f4daf)
Location: kernel/sched/core.c:6939
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810ef3c0-ffffffff810ef3fb: can_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int can_nice(const struct task_struct *p, const int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81110b53)
Location: kernel/sched/core.c:7035
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff8110a910-ffffffff8110a963: can_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int can_nice(const struct task_struct *p, const int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81137ab3)
Location: kernel/sched/core.c:7176
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff8112f630-ffffffff8112f683: can_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int can_nice(const struct task_struct *p, const int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81146c23)
Location: kernel/sched/core.c:7277
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff8113d0b0-ffffffff8113d103: can_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int can_nice(const struct task_struct *p, const int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81152373)
Location: kernel/sched/core.c:7327
Inline: True
Inline callers:
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/build_utility.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff81148220-ffffffff81148273: can_nice (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int can_nice(const struct task_struct *p, const int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffff8000101372a0)
Location: kernel/sched/core.c:4559
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__arm64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__arm64_sys_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffff800010133428-ffff80001013344c: can_nice.part.0 (STB_LOCAL)
ffff800010133450-ffff8000101334a4: can_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int can_nice(const struct task_struct *p, const int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (c0386074)
Location: kernel/sched/core.c:4559
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__se_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__se_sys_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
c03829bc-c03829dc: can_nice.part.0 (STB_LOCAL)
c03829dc-c0382a14: can_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int can_nice(const struct task_struct *p, const int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (c000000000182614)
Location: kernel/sched/core.c:4559
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__se_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__se_sys_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
c00000000017e3b0-c00000000017e3ec: can_nice.part.0 (STB_LOCAL)
c00000000017e3f0-c00000000017e424: can_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int can_nice(const struct task_struct *p, const int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e793c)
Location: kernel/sched/core.c:4559
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffe0000e5ddc-ffffffe0000e5e02: can_nice.part.0 (STB_LOCAL)
ffffffe0000e5e02-ffffffe0000e5e50: can_nice (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int can_nice(const struct task_struct *p, const int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810d0e33)
Location: kernel/sched/core.c:4559
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810cd3b0-ffffffff810cd3c8: can_nice.part.0 (STB_LOCAL)
ffffffff810cd3d0-ffffffff810cd403: can_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int can_nice(const struct task_struct *p, const int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810bf005)
Location: kernel/sched/core.c:4559
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810bbc10-ffffffff810bbc28: can_nice.part.0 (STB_LOCAL)
ffffffff810bbc30-ffffffff810bbc63: can_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int can_nice(const struct task_struct *p, const int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810cef76)
Location: kernel/sched/core.c:4559
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810cc890-ffffffff810cc8a8: can_nice.part.0 (STB_LOCAL)
ffffffff810cc8b0-ffffffff810cc8e3: can_nice (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int can_nice(const struct task_struct *p, const int nice);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffff810d7ea4)
Location: kernel/sched/core.c:4559
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
Direct callers:
  - kernel/sys.c:set_one_prio
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:__ia32_sys_nice
  - kernel/sched/core.c:__x64_sys_nice
  - kernel/sched/autogroup.c:proc_sched_autogroup_set_nice
```
**Symbols:**

```
ffffffff810d5220-ffffffff810d5238: can_nice.part.0 (STB_LOCAL)
ffffffff810d5240-ffffffff810d5273: can_nice (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
