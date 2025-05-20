# Function: <code>rcu_dynticks_curr_cpu_in_eqs</code>

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
bool rcu_dynticks_curr_cpu_in_eqs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f5e12)
Location: kernel/rcu/tree.c:361
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_nmi_exit
  - kernel/rcu/tree.c:rcu_nmi_enter
```
**Symbols:**

```
ffffffff810f5bf0-ffffffff810f5c15: rcu_dynticks_curr_cpu_in_eqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool rcu_dynticks_curr_cpu_in_eqs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810ffcb2)
Location: kernel/rcu/tree.c:358
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_nmi_exit
  - kernel/rcu/tree.c:rcu_nmi_enter
```
**Symbols:**

```
ffffffff810ff9f0-ffffffff810ffa15: rcu_dynticks_curr_cpu_in_eqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool rcu_dynticks_curr_cpu_in_eqs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81107f85)
Location: kernel/rcu/tree.c:345
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_nmi_exit
```
**Symbols:**

```
ffffffff81107d00-ffffffff81107d25: rcu_dynticks_curr_cpu_in_eqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool rcu_dynticks_curr_cpu_in_eqs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811134c8)
Location: kernel/rcu/tree.c:301
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_irq_exit
```
**Symbols:**

```
ffffffff81113220-ffffffff81113248: rcu_dynticks_curr_cpu_in_eqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool rcu_dynticks_curr_cpu_in_eqs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111d108)
Location: kernel/rcu/tree.c:296
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
Direct callers:
  - kernel/rcu/tree.c:rcu_nmi_enter
```
**Symbols:**

```
ffffffff8111cd90-ffffffff8111cdb8: rcu_dynticks_curr_cpu_in_eqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool rcu_dynticks_curr_cpu_in_eqs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811282cc)
Location: kernel/rcu/tree.c:297
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
Direct callers:
  - kernel/rcu/tree.c:rcu_nmi_enter
```
**Symbols:**

```
ffffffff81129270-ffffffff81129298: rcu_dynticks_curr_cpu_in_eqs (STB_GLOBAL)
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
In kernel/rcu/tree.c (ffffffff81136ba0)
Location: kernel/rcu/tree.c:312
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__rcu_is_watching
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_nmi_exit
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
In kernel/rcu/tree.c (ffffffff81132200)
Location: kernel/rcu/tree.c:317
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_nmi_exit
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
In kernel/rcu/tree.c (ffffffff811329e8)
Location: kernel/rcu/tree.c:323
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_nmi_exit
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
In kernel/rcu/tree.c (ffffffff81154c1c)
Location: kernel/rcu/tree.c:328
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_nmi_exit
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
In kernel/rcu/tree.c (ffffffff8117df63)
Location: kernel/rcu/tree.c:339
Inline: True
Inline callers:
  - kernel/rcu/tree.c:call_rcu
  - kernel/rcu/tree.c:call_rcu
  - kernel/rcu/tree.c:rcu_nmi_enter
  - kernel/rcu/tree.c:rcu_nmi_exit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810e9f15)
Location: include/linux/context_tracking.h:119
Inline: True
Inline callers:
  - kernel/panic.c:__warn_printk
```
```
In kernel/rcu/tree.c (ffffffff811afa17)
Location: include/linux/context_tracking.h:119
Inline: True
```
```
In kernel/context_tracking.c (ffffffff820c01f6)
Location: include/linux/context_tracking.h:119
Inline: True
Inline callers:
  - kernel/context_tracking.c:ct_nmi_enter
  - kernel/context_tracking.c:ct_nmi_exit
```
```
In lib/bug.c (ffffffff8201ebae)
Location: include/linux/context_tracking.h:119
Inline: True
Inline callers:
  - lib/bug.c:report_bug
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810f5b15)
Location: include/linux/context_tracking.h:120
Inline: True
Inline callers:
  - kernel/panic.c:__warn_printk
```
```
In kernel/rcu/tree.c (ffffffff811c1a87)
Location: include/linux/context_tracking.h:120
Inline: True
```
```
In kernel/context_tracking.c (ffffffff82142076)
Location: include/linux/context_tracking.h:120
Inline: True
Inline callers:
  - kernel/context_tracking.c:ct_nmi_enter
  - kernel/context_tracking.c:ct_nmi_exit
```
```
In lib/bug.c (ffffffff8209ebbe)
Location: include/linux/context_tracking.h:120
Inline: True
Inline callers:
  - lib/bug.c:report_bug
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/panic.c (ffffffff810feec5)
Location: include/linux/context_tracking.h:120
Inline: True
Inline callers:
  - kernel/panic.c:__warn_printk
```
```
In kernel/rcu/tree.c (ffffffff811e0a7d)
Location: include/linux/context_tracking.h:120
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu_common
  - kernel/rcu/tree.c:__call_rcu_common
```
```
In kernel/context_tracking.c (ffffffff82224717)
Location: include/linux/context_tracking.h:120
Inline: True
Inline callers:
  - kernel/context_tracking.c:ct_nmi_enter
  - kernel/context_tracking.c:ct_nmi_exit
```
```
In lib/bug.c (ffffffff82176bbe)
Location: include/linux/context_tracking.h:120
Inline: True
Inline callers:
  - lib/bug.c:report_bug
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
bool rcu_dynticks_curr_cpu_in_eqs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001018f08c)
Location: kernel/rcu/tree.c:297
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_irq_exit
Direct callers:
  - kernel/rcu/tree.c:rcu_nmi_enter
```
**Symbols:**

```
ffff800010190800-ffff800010190834: rcu_dynticks_curr_cpu_in_eqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool rcu_dynticks_curr_cpu_in_eqs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03dc4c0)
Location: kernel/rcu/tree.c:297
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_irq_exit
Direct callers:
  - kernel/rcu/tree.c:rcu_nmi_enter
```
**Symbols:**

```
c03de364-c03de398: rcu_dynticks_curr_cpu_in_eqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool rcu_dynticks_curr_cpu_in_eqs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001e99c0)
Location: kernel/rcu/tree.c:297
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
Direct callers:
  - kernel/rcu/tree.c:rcu_nmi_enter
```
**Symbols:**

```
c0000000001ebb20-c0000000001ebb50: rcu_dynticks_curr_cpu_in_eqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool rcu_dynticks_curr_cpu_in_eqs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe0001232a0)
Location: kernel/rcu/tree.c:297
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_irq_exit
```
**Symbols:**

```
ffffffe000123e36-ffffffe000123e7e: rcu_dynticks_curr_cpu_in_eqs (STB_GLOBAL)
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
bool rcu_dynticks_curr_cpu_in_eqs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811208ac)
Location: kernel/rcu/tree.c:297
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
Direct callers:
  - kernel/rcu/tree.c:rcu_nmi_enter
```
**Symbols:**

```
ffffffff81121850-ffffffff81121878: rcu_dynticks_curr_cpu_in_eqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool rcu_dynticks_curr_cpu_in_eqs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81113d47)
Location: kernel/rcu/tree.c:297
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
Direct callers:
  - kernel/rcu/tree.c:rcu_nmi_enter
```
**Symbols:**

```
ffffffff81113f30-ffffffff81113f58: rcu_dynticks_curr_cpu_in_eqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool rcu_dynticks_curr_cpu_in_eqs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111e79c)
Location: kernel/rcu/tree.c:297
Inline: True
Inline callers:
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
Direct callers:
  - kernel/rcu/tree.c:rcu_nmi_enter
```
**Symbols:**

```
ffffffff8111f740-ffffffff8111f768: rcu_dynticks_curr_cpu_in_eqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool rcu_dynticks_curr_cpu_in_eqs();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112a82f)
Location: kernel/rcu/tree.c:297
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:rcu_exp_handler
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:__call_rcu
  - kernel/rcu/tree.c:rcu_irq_enter
  - kernel/rcu/tree.c:rcu_irq_exit
  - kernel/rcu/tree.c:rcu_nmi_exit
Direct callers:
  - kernel/rcu/tree.c:rcu_nmi_enter
```
**Symbols:**

```
ffffffff8112b890-ffffffff8112b8b8: rcu_dynticks_curr_cpu_in_eqs (STB_GLOBAL)
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
