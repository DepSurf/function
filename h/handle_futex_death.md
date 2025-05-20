# Function: <code>handle_futex_death</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int handle_futex_death(u32 *uaddr, struct task_struct *curr, int pi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811028f0)
Location: kernel/futex.c:2909
Inline: True
Direct callers:
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
```
**Symbols:**

```
ffffffff811028f0-ffffffff811029d7: handle_futex_death (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int handle_futex_death(u32 *uaddr, struct task_struct *curr, int pi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81109db0)
Location: kernel/futex.c:3042
Inline: True
Direct callers:
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
```
**Symbols:**

```
ffffffff81109db0-ffffffff81109e8a: handle_futex_death (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int handle_futex_death(u32 *uaddr, struct task_struct *curr, int pi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff811115a0)
Location: kernel/futex.c:3055
Inline: True
Direct callers:
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
```
**Symbols:**

```
ffffffff811115a0-ffffffff8111167a: handle_futex_death (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int handle_futex_death(u32 *uaddr, struct task_struct *curr, int pi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff81112bf0)
Location: kernel/futex.c:3230
Inline: True
Direct callers:
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
```
**Symbols:**

```
ffffffff81112bf0-ffffffff81112cd0: handle_futex_death (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int handle_futex_death(u32 *uaddr, struct task_struct *curr, int pi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8111e190)
Location: kernel/futex.c:3381
Inline: True
Direct callers:
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
```
**Symbols:**

```
ffffffff8111e190-ffffffff8111e270: handle_futex_death (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int handle_futex_death(u32 *uaddr, struct task_struct *curr, int pi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffff8112aab0)
Location: kernel/futex.c:3363
Inline: True
Direct callers:
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
  - kernel/futex_compat.c:compat_exit_robust_list
```
**Symbols:**

```
ffffffff8112aab0-ffffffff8112ab90: handle_futex_death (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/futex.c (ffffffff81137919)
Location: kernel/futex.c:3439
Inline: True
Inline callers:
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:exit_robust_list
Direct callers:
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:exit_robust_list
```
**Symbols:**

```
ffffffff81134290-ffffffff81134370: handle_futex_death.part.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/futex.c (ffffffff8114289d)
Location: kernel/futex.c:3461
Inline: True
Inline callers:
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:exit_robust_list
Direct callers:
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:exit_robust_list
```
**Symbols:**

```
ffffffff8113f1f0-ffffffff8113f30d: handle_futex_death.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/futex.c (ffffffff8114bea6)
Location: kernel/futex.c:3566
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
```
**Symbols:**

```
ffffffff8114aba0-ffffffff8114accd: handle_futex_death.part.0 (STB_LOCAL)
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
In kernel/futex.c (ffffffff8115b9da)
Location: kernel/futex.c:3479
Inline: True
Inline callers:
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:exit_robust_list
Direct callers:
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:exit_robust_list
```
**Symbols:**

```
ffffffff8115b7c0-ffffffff8115b92f: handle_futex_death.part.0 (STB_LOCAL)
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
In kernel/futex.c (ffffffff811584aa)
Location: kernel/futex.c:3403
Inline: True
Inline callers:
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:exit_robust_list
Direct callers:
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:exit_robust_list
```
**Symbols:**

```
ffffffff811581b0-ffffffff811582cb: handle_futex_death.part.0 (STB_LOCAL)
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
In kernel/futex.c (ffffffff8115972a)
Location: kernel/futex.c:3400
Inline: True
Inline callers:
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:exit_robust_list
Direct callers:
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:exit_robust_list
```
**Symbols:**

```
ffffffff81159430-ffffffff8115954b: handle_futex_death.part.0 (STB_LOCAL)
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
In kernel/futex.c (ffffffff8117e3fa)
Location: kernel/futex.c:3631
Inline: True
Inline callers:
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:exit_robust_list
Direct callers:
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:compat_exit_robust_list
  - kernel/futex.c:exit_robust_list
  - kernel/futex.c:exit_robust_list
```
**Symbols:**

```
ffffffff8117e230-ffffffff8117e34b: handle_futex_death.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int handle_futex_death(u32 *uaddr, struct task_struct *curr, bool pi, bool pending_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811b2d40)
Location: kernel/futex/core.c:637
Inline: False
Direct callers:
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
```
**Symbols:**

```
ffffffff811b2d40-ffffffff811b2e79: handle_futex_death (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int handle_futex_death(u32 *uaddr, struct task_struct *curr, bool pi, bool pending_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff811f3c20)
Location: kernel/futex/core.c:637
Inline: False
Direct callers:
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
```
**Symbols:**

```
ffffffff811f3c20-ffffffff811f3d5e: handle_futex_death (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int handle_futex_death(u32 *uaddr, struct task_struct *curr, bool pi, bool pending_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff812083b0)
Location: kernel/futex/core.c:637
Inline: False
Direct callers:
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
```
**Symbols:**

```
ffffffff812083b0-ffffffff812084ee: handle_futex_death (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int handle_futex_death(u32 *uaddr, struct task_struct *curr, bool pi, bool pending_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex/core.c (ffffffff8121f240)
Location: kernel/futex/core.c:659
Inline: False
Direct callers:
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
  - kernel/futex/core.c:futex_cleanup
```
**Symbols:**

```
ffffffff8121f240-ffffffff8121f37e: handle_futex_death (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int handle_futex_death(u32 *uaddr, struct task_struct *curr, bool pi, bool pending_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffff8000101b7fb0)
Location: kernel/futex.c:3566
Inline: False
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
```
**Symbols:**

```
ffff8000101b7fb0-ffff8000101b8200: handle_futex_death (STB_LOCAL)
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
In kernel/futex.c (c040312c)
Location: kernel/futex.c:3566
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
```
**Symbols:**

```
c0401d30-c0401ec8: handle_futex_death.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int handle_futex_death(u32 *uaddr, struct task_struct *curr, bool pi, bool pending_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (c00000000021d660)
Location: kernel/futex.c:3566
Inline: False
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
```
**Symbols:**

```
c00000000021d660-c00000000021d924: handle_futex_death (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int handle_futex_death(u32 *uaddr, struct task_struct *curr, bool pi, bool pending_op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/futex.c (ffffffe00013cd7c)
Location: kernel/futex.c:3566
Inline: False
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
```
**Symbols:**

```
ffffffe00013cd7c-ffffffe00013cea6: handle_futex_death (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/futex.c (ffffffff811444c6)
Location: kernel/futex.c:3566
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
```
**Symbols:**

```
ffffffff811431c0-ffffffff811432ed: handle_futex_death.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/futex.c (ffffffff81136cf6)
Location: kernel/futex.c:3566
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
```
**Symbols:**

```
ffffffff81136520-ffffffff8113664d: handle_futex_death.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/futex.c (ffffffff81142376)
Location: kernel/futex.c:3566
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
```
**Symbols:**

```
ffffffff81141070-ffffffff8114119d: handle_futex_death.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/futex.c (ffffffff8114e3ef)
Location: kernel/futex.c:3566
Inline: True
Inline callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
Direct callers:
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
  - kernel/futex.c:futex_cleanup
```
**Symbols:**

```
ffffffff8114e1b0-ffffffff8114e2d4: handle_futex_death.part.0 (STB_LOCAL)
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
