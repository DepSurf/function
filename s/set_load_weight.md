# Function: <code>set_load_weight</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a4b93)
Location: kernel/sched/core.c:812
Inline: True
Inline callers:
  - kernel/sched/core.c:__setscheduler_params
  - kernel/sched/core.c:sched_fork
  - kernel/sched/core.c:sched_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81fa723e)
Location: kernel/sched/core.c:730
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81fe2ed7)
Location: kernel/sched/core.c:737
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
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
In kernel/sched/core.c (ffffffff820c375a)
Location: kernel/sched/core.c:736
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void set_load_weight(struct task_struct *p, bool update_load);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b3270)
Location: kernel/sched/core.c:738
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
**Symbols:**

```
ffffffff810b3270-ffffffff810b32e0: set_load_weight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void set_load_weight(struct task_struct *p, bool update_load);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ba380)
Location: kernel/sched/core.c:716
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
**Symbols:**

```
ffffffff810ba380-ffffffff810ba3ea: set_load_weight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void set_load_weight(struct task_struct *p, bool update_load);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c3480)
Location: kernel/sched/core.c:705
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
**Symbols:**

```
ffffffff810c3480-ffffffff810c34fc: set_load_weight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void set_load_weight(struct task_struct *p, bool update_load);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c9560)
Location: kernel/sched/core.c:747
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
**Symbols:**

```
ffffffff810c9560-ffffffff810c95db: set_load_weight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void set_load_weight(struct task_struct *p, bool update_load);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d2630)
Location: kernel/sched/core.c:747
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
**Symbols:**

```
ffffffff810d2630-ffffffff810d26ab: set_load_weight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void set_load_weight(struct task_struct *p, bool update_load);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e0a23)
Location: kernel/sched/core.c:749
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff810e6c55-ffffffff810e6cbe: set_load_weight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void set_load_weight(struct task_struct *p, bool update_load);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810ddeca)
Location: kernel/sched/core.c:838
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff81bdc46b-ffffffff81bdc4d7: set_load_weight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void set_load_weight(struct task_struct *p, bool update_load);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dfdb6)
Location: kernel/sched/core.c:848
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff81bce604-ffffffff81bce670: set_load_weight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void set_load_weight(struct task_struct *p, bool update_load);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f4f4a)
Location: kernel/sched/core.c:1202
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff81ca5a1f-ffffffff81ca5ac3: set_load_weight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void set_load_weight(struct task_struct *p, bool update_load);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81111639)
Location: kernel/sched/core.c:1272
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:sched_fork
Direct callers:
  - kernel/sched/core.c:sched_init
```
**Symbols:**

```
ffffffff81e55338-ffffffff81e553e8: set_load_weight (STB_LOCAL)
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
In kernel/sched/core.c (ffffffff83ea83f3)
Location: kernel/sched/core.c:1260
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:sched_fork
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
In kernel/sched/core.c (ffffffff836cccc3)
Location: kernel/sched/core.c:1282
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:sched_fork
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
In kernel/sched/core.c (ffffffff838fe0a4)
Location: kernel/sched/core.c:1327
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:set_user_nice
  - kernel/sched/core.c:sched_fork
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffff800011444e10)
Location: kernel/sched/core.c:747
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_fork
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffff8000101335e0-ffff800010133684: set_load_weight.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (c151ef18)
Location: kernel/sched/core.c:747
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_fork
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
c0382ca0-c0382d28: set_load_weight.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (c0000000013696e4)
Location: kernel/sched/core.c:747
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_fork
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
c00000000017e8a0-c00000000017e954: set_load_weight.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sched/core.c (ffffffe000006d26)
Location: kernel/sched/core.c:747
Inline: True
Inline callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:sched_fork
Direct callers:
  - kernel/sched/core.c:__sched_setscheduler
```
**Symbols:**

```
ffffffe0000e603e-ffffffe0000e60ca: set_load_weight.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void set_load_weight(struct task_struct *p, bool update_load);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cc9b0)
Location: kernel/sched/core.c:747
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
**Symbols:**

```
ffffffff810cc9b0-ffffffff810cca2b: set_load_weight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void set_load_weight(struct task_struct *p, bool update_load);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bb1b0)
Location: kernel/sched/core.c:747
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
**Symbols:**

```
ffffffff810bb1b0-ffffffff810bb22b: set_load_weight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void set_load_weight(struct task_struct *p, bool update_load);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810cbed0)
Location: kernel/sched/core.c:747
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
**Symbols:**

```
ffffffff810cbed0-ffffffff810cbf4b: set_load_weight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void set_load_weight(struct task_struct *p, bool update_load);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d44e0)
Location: kernel/sched/core.c:747
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_init
  - kernel/sched/core.c:__sched_setscheduler
  - kernel/sched/core.c:sched_fork
```
**Symbols:**

```
ffffffff810d44e0-ffffffff810d455b: set_load_weight (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
