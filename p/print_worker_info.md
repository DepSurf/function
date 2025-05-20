# Function: <code>print_worker_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void print_worker_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109c900)
Location: kernel/workqueue.c:4137
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_show_task
  - kernel/printk/printk.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff8109c900-ffffffff8109ca74: print_worker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void print_worker_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8109faf0)
Location: kernel/workqueue.c:4235
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_show_task
  - kernel/printk/printk.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff8109faf0-ffffffff8109fc64: print_worker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void print_worker_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a49c0)
Location: kernel/workqueue.c:4265
Inline: False
Direct callers:
  - kernel/sched/core.c:sched_show_task
  - kernel/printk/printk.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff810a49c0-ffffffff810a4b34: print_worker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void print_worker_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a1b20)
Location: kernel/workqueue.c:4285
Inline: False
Direct callers:
  - kernel/printk/printk.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff810a1b20-ffffffff810a1c94: print_worker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void print_worker_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff810a83a0)
Location: kernel/workqueue.c:4312
Inline: False
Direct callers:
  - kernel/printk/printk.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff810a83a0-ffffffff810a8514: print_worker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void print_worker_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4395
Inline: False
```
**Symbols:**

```
ffffffff810b02b3-ffffffff810b02f8: print_worker_info.cold.48 (STB_LOCAL)
ffffffff810aee50-ffffffff810aef70: print_worker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void print_worker_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4418
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff810b93f3-ffffffff810b9438: print_worker_info.cold.49 (STB_LOCAL)
ffffffff810b7fc0-ffffffff810b80e0: print_worker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void print_worker_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4563
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff810bf0e6-ffffffff810bf12b: print_worker_info.cold (STB_LOCAL)
ffffffff810bdb10-ffffffff810bdc30: print_worker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void print_worker_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4596
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff810c5547-ffffffff810c558c: print_worker_info.cold (STB_LOCAL)
ffffffff810c4060-ffffffff810c4180: print_worker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void print_worker_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4619
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff810cd0f2-ffffffff810cd137: print_worker_info.cold (STB_LOCAL)
ffffffff810cbce0-ffffffff810cbe00: print_worker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void print_worker_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4632
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff81bdbf53-ffffffff81bdbf98: print_worker_info.cold (STB_LOCAL)
ffffffff810c6e10-ffffffff810c6f30: print_worker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void print_worker_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4639
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff81bce078-ffffffff81bce0bd: print_worker_info.cold (STB_LOCAL)
ffffffff810c85b0-ffffffff810c86d0: print_worker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void print_worker_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4678
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff81ca52d1-ffffffff81ca5316: print_worker_info.cold (STB_LOCAL)
ffffffff810db150-ffffffff810db270: print_worker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void print_worker_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4661
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff81e54c00-ffffffff81e54c45: print_worker_info.cold (STB_LOCAL)
ffffffff810f4960-ffffffff810f4a8e: print_worker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void print_worker_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81116d00)
Location: kernel/workqueue.c:4670
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff81116d00-ffffffff81116e6e: print_worker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void print_worker_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff81123c80)
Location: kernel/workqueue.c:5008
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff81123c80-ffffffff81123df1: print_worker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void print_worker_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffff8112e300)
Location: kernel/workqueue.c:5031
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff8112e300-ffffffff8112e471: print_worker_info (STB_GLOBAL)
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
void print_worker_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffff800010121e60)
Location: kernel/workqueue.c:4596
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffff800010121e60-ffff800010121f9c: print_worker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void print_worker_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c0375840)
Location: kernel/workqueue.c:4596
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
c0375840-c03759a8: print_worker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void print_worker_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (c00000000016b7d0)
Location: kernel/workqueue.c:4596
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
c00000000016b7d0-c00000000016b988: print_worker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void print_worker_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/workqueue.c (ffffffe0000daa44)
Location: kernel/workqueue.c:4596
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffe0000daa44-ffffffe0000dab66: print_worker_info (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void print_worker_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4596
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff810bf8b7-ffffffff810bf8fc: print_worker_info.cold (STB_LOCAL)
ffffffff810be3d0-ffffffff810be4f0: print_worker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void print_worker_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4596
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff810ae0d7-ffffffff810ae11c: print_worker_info.cold (STB_LOCAL)
ffffffff810acc00-ffffffff810acd20: print_worker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void print_worker_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4596
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff810bee17-ffffffff810bee5c: print_worker_info.cold (STB_LOCAL)
ffffffff810bd930-ffffffff810bda50: print_worker_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void print_worker_info(const char *log_lvl, struct task_struct *task);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/workqueue.c (0)
Location: kernel/workqueue.c:4596
Inline: False
Direct callers:
  - lib/dump_stack.c:dump_stack_print_info
```
**Symbols:**

```
ffffffff810c7182-ffffffff810c71c7: print_worker_info.cold (STB_LOCAL)
ffffffff810c5cb0-ffffffff810c5dd0: print_worker_info (STB_GLOBAL)
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
