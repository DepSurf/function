# Function: <code>__dl_clear_params</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __dl_clear_params(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810a59b5)
Location: kernel/sched/core.c:2079
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_fork
Direct callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810ac7f0-ffffffff810ac84f: __dl_clear_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __dl_clear_params(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aa092)
Location: kernel/sched/core.c:2168
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_fork
Direct callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810af110-ffffffff810af165: __dl_clear_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __dl_clear_params(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810affe2)
Location: kernel/sched/core.c:2178
Inline: True
Inline callers:
  - kernel/sched/core.c:__sched_fork
Direct callers:
  - kernel/sched/deadline.c:dl_task_timer
```
**Symbols:**

```
ffffffff810b5250-ffffffff810b52a5: __dl_clear_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __dl_clear_params(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810c68e9)
Location: kernel/sched/deadline.c:2568
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
Direct callers:
  - kernel/sched/core.c:__sched_fork
```
**Symbols:**

```
ffffffff810c90a0-ffffffff810c90f8: __dl_clear_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __dl_clear_params(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810ce148)
Location: kernel/sched/deadline.c:2555
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
Direct callers:
  - kernel/sched/core.c:__sched_fork
```
**Symbols:**

```
ffffffff810d0790-ffffffff810d07e3: __dl_clear_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __dl_clear_params(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810d7fbe)
Location: kernel/sched/deadline.c:2644
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
Direct callers:
  - kernel/sched/core.c:__sched_fork
```
**Symbols:**

```
ffffffff810d8cc0-ffffffff810d8d13: __dl_clear_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __dl_clear_params(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810df75e)
Location: kernel/sched/deadline.c:2647
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
Direct callers:
  - kernel/sched/core.c:__sched_fork
```
**Symbols:**

```
ffffffff810e27c0-ffffffff810e2813: __dl_clear_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __dl_clear_params(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e633f)
Location: kernel/sched/deadline.c:2638
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
Direct callers:
  - kernel/sched/core.c:__sched_fork
```
**Symbols:**

```
ffffffff810e92d0-ffffffff810e9323: __dl_clear_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __dl_clear_params(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f19bf)
Location: kernel/sched/deadline.c:2685
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
Direct callers:
  - kernel/sched/core.c:__sched_fork
```
**Symbols:**

```
ffffffff810f4db0-ffffffff810f4e03: __dl_clear_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __dl_clear_params(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fafcf)
Location: kernel/sched/deadline.c:2684
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
Direct callers:
  - kernel/sched/core.c:__sched_fork
```
**Symbols:**

```
ffffffff810fe4c0-ffffffff810fe513: __dl_clear_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __dl_clear_params(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f970f)
Location: kernel/sched/deadline.c:2830
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
Direct callers:
  - kernel/sched/core.c:__sched_fork
```
**Symbols:**

```
ffffffff810fccf0-ffffffff810fcd51: __dl_clear_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __dl_clear_params(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810fb862)
Location: kernel/sched/deadline.c:2814
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
Direct callers:
  - kernel/sched/core.c:__sched_fork
```
**Symbols:**

```
ffffffff810ff070-ffffffff810ff0d1: __dl_clear_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __dl_clear_params(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff811186cd)
Location: kernel/sched/deadline.c:2828
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
Direct callers:
  - kernel/sched/core.c:__sched_fork
```
**Symbols:**

```
ffffffff8111af40-ffffffff8111afa1: __dl_clear_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __dl_clear_params(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff81132f2c)
Location: kernel/sched/deadline.c:2970
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:task_non_contending
Direct callers:
  - kernel/sched/core.c:__sched_fork
```
**Symbols:**

```
ffffffff8113aef0-ffffffff8113af59: __dl_clear_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __dl_clear_params(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8115d252)
Location: kernel/sched/deadline.c:2970
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:task_non_contending
Direct callers:
  - kernel/sched/core.c:__sched_fork
```
**Symbols:**

```
ffffffff81165800-ffffffff81165869: __dl_clear_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __dl_clear_params(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_policy.c (ffffffff8116cb62)
Location: kernel/sched/deadline.c:2996
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:task_non_contending
Direct callers:
  - kernel/sched/core.c:__sched_fork
```
**Symbols:**

```
ffffffff81175fc0-ffffffff81176029: __dl_clear_params (STB_GLOBAL)
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
In kernel/sched/build_policy.c (ffffffff81184273)
Location: kernel/sched/deadline.c:3093
Inline: True
Inline callers:
  - kernel/sched/build_policy.c:init_dl_entity
  - kernel/sched/build_policy.c:inactive_task_timer
  - kernel/sched/build_policy.c:task_non_contending
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void __dl_clear_params(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffff8000101536ec)
Location: kernel/sched/deadline.c:2685
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
Direct callers:
  - kernel/sched/core.c:__sched_fork
```
**Symbols:**

```
ffff800010157508-ffff800010157550: __dl_clear_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __dl_clear_params(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c03a181c)
Location: kernel/sched/deadline.c:2685
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
```
**Symbols:**

```
c03a52d4-c03a5320: __dl_clear_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __dl_clear_params(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (c0000000001a7a4c)
Location: kernel/sched/deadline.c:2685
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
Direct callers:
  - kernel/sched/core.c:__sched_fork
```
**Symbols:**

```
c0000000001ac0b0-c0000000001ac0e8: __dl_clear_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __dl_clear_params(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffe0000fb442)
Location: kernel/sched/deadline.c:2685
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
```
**Symbols:**

```
ffffffe0000fe334-ffffffe0000fe376: __dl_clear_params (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __dl_clear_params(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810eadbf)
Location: kernel/sched/deadline.c:2685
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
Direct callers:
  - kernel/sched/core.c:__sched_fork
```
**Symbols:**

```
ffffffff810ee1b0-ffffffff810ee203: __dl_clear_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __dl_clear_params(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810daddf)
Location: kernel/sched/deadline.c:2685
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
Direct callers:
  - kernel/sched/core.c:__sched_fork
```
**Symbols:**

```
ffffffff810de240-ffffffff810de293: __dl_clear_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __dl_clear_params(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810e7eef)
Location: kernel/sched/deadline.c:2685
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
Direct callers:
  - kernel/sched/core.c:__sched_fork
```
**Symbols:**

```
ffffffff810eb2e0-ffffffff810eb333: __dl_clear_params (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __dl_clear_params(struct task_struct *p);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/deadline.c (ffffffff810f315d)
Location: kernel/sched/deadline.c:2685
Inline: True
Inline callers:
  - kernel/sched/deadline.c:inactive_task_timer
  - kernel/sched/deadline.c:task_non_contending
Direct callers:
  - kernel/sched/core.c:__sched_fork
```
**Symbols:**

```
ffffffff810f62e0-ffffffff810f6333: __dl_clear_params (STB_GLOBAL)
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
