# Function: <code>perf_lock_task_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct perf_event_context *perf_lock_task_context(struct task_struct *task, int ctxn, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8117b6c0)
Location: kernel/events/core.c:1054
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
```
**Symbols:**

```
ffffffff8117b6c0-ffffffff8117b780: perf_lock_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct perf_event_context *perf_lock_task_context(struct task_struct *task, int ctxn, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118ca30)
Location: kernel/events/core.c:1300
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pin_task_context
```
**Symbols:**

```
ffffffff8118ca30-ffffffff8118cb33: perf_lock_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct perf_event_context *perf_lock_task_context(struct task_struct *task, int ctxn, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119bb90)
Location: kernel/events/core.c:1308
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pin_task_context
```
**Symbols:**

```
ffffffff8119bb90-ffffffff8119bc93: perf_lock_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct perf_event_context *perf_lock_task_context(struct task_struct *task, int ctxn, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a39b0)
Location: kernel/events/core.c:1300
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pin_task_context
```
**Symbols:**

```
ffffffff811a39b0-ffffffff811a3a87: perf_lock_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct perf_event_context *perf_lock_task_context(struct task_struct *task, int ctxn, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b7b80)
Location: kernel/events/core.c:1348
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pin_task_context
```
**Symbols:**

```
ffffffff811b7b80-ffffffff811b7c57: perf_lock_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct perf_event_context *perf_lock_task_context(struct task_struct *task, int ctxn, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811dae10)
Location: kernel/events/core.c:1371
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pin_task_context
```
**Symbols:**

```
ffffffff811dae10-ffffffff811daee0: perf_lock_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct perf_event_context *perf_lock_task_context(struct task_struct *task, int ctxn, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811eada0)
Location: kernel/events/core.c:1371
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pin_task_context
```
**Symbols:**

```
ffffffff811eada0-ffffffff811eae70: perf_lock_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct perf_event_context *perf_lock_task_context(struct task_struct *task, int ctxn, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81201be0)
Location: kernel/events/core.c:1373
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pin_task_context
```
**Symbols:**

```
ffffffff81201be0-ffffffff81201cc2: perf_lock_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct perf_event_context *perf_lock_task_context(struct task_struct *task, int ctxn, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120ea90)
Location: kernel/events/core.c:1373
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pin_task_context
```
**Symbols:**

```
ffffffff8120ea90-ffffffff8120eb72: perf_lock_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct perf_event_context *perf_lock_task_context(struct task_struct *task, int ctxn, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812384a0)
Location: kernel/events/core.c:1435
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:find_get_context
```
**Symbols:**

```
ffffffff812384a0-ffffffff8123858b: perf_lock_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct perf_event_context *perf_lock_task_context(struct task_struct *task, int ctxn, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81243260)
Location: kernel/events/core.c:1453
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_exit_task_context
  - kernel/events/core.c:find_get_context
```
**Symbols:**

```
ffffffff81243260-ffffffff8124335c: perf_lock_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct perf_event_context *perf_lock_task_context(struct task_struct *task, int ctxn, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81249ee0)
Location: kernel/events/core.c:1451
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:find_get_context
```
**Symbols:**

```
ffffffff81249ee0-ffffffff81249fd7: perf_lock_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct perf_event_context *perf_lock_task_context(struct task_struct *task, int ctxn, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81282dd0)
Location: kernel/events/core.c:1482
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:find_get_context
```
**Symbols:**

```
ffffffff81282dd0-ffffffff81282f1b: perf_lock_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct perf_event_context *perf_lock_task_context(struct task_struct *task, int ctxn, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812cdd50)
Location: kernel/events/core.c:1391
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:find_get_context
```
**Symbols:**

```
ffffffff812cdd50-ffffffff812cdea5: perf_lock_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct perf_event_context *perf_lock_task_context(struct task_struct *task, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81335840)
Location: kernel/events/core.c:1364
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:find_get_context
```
**Symbols:**

```
ffffffff81335840-ffffffff81335959: perf_lock_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct perf_event_context *perf_lock_task_context(struct task_struct *task, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81366590)
Location: kernel/events/core.c:1364
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:find_get_context
```
**Symbols:**

```
ffffffff81366590-ffffffff813666a5: perf_lock_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct perf_event_context *perf_lock_task_context(struct task_struct *task, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8138f720)
Location: kernel/events/core.c:1375
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
  - kernel/events/core.c:find_get_context
```
**Symbols:**

```
ffffffff8138f720-ffffffff8138f835: perf_lock_task_context (STB_LOCAL)
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
struct perf_event_context *perf_lock_task_context(struct task_struct *task, int ctxn, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff800010295460)
Location: kernel/events/core.c:1373
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pin_task_context
```
**Symbols:**

```
ffff800010295460-ffff8000102955c8: perf_lock_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct perf_event_context *perf_lock_task_context(struct task_struct *task, int ctxn, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c09c0)
Location: kernel/events/core.c:1373
Inline: False
Direct callers:
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:perf_pin_task_context
```
**Symbols:**

```
c04c09c0-c04c0ae8: perf_lock_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct perf_event_context *perf_lock_task_context(struct task_struct *task, int ctxn, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000033e6f0)
Location: kernel/events/core.c:1373
Inline: False
Direct callers:
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:perf_pin_task_context
```
**Symbols:**

```
c00000000033e6f0-c00000000033e938: perf_lock_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct perf_event_context *perf_lock_task_context(struct task_struct *task, int ctxn, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c893e)
Location: kernel/events/core.c:1373
Inline: False
Direct callers:
  - kernel/events/core.c:find_get_context
  - kernel/events/core.c:perf_pin_task_context
```
**Symbols:**

```
ffffffe0001c893e-ffffffe0001c8a82: perf_lock_task_context (STB_LOCAL)
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
struct perf_event_context *perf_lock_task_context(struct task_struct *task, int ctxn, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812070b0)
Location: kernel/events/core.c:1373
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pin_task_context
```
**Symbols:**

```
ffffffff812070b0-ffffffff81207192: perf_lock_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct perf_event_context *perf_lock_task_context(struct task_struct *task, int ctxn, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fa060)
Location: kernel/events/core.c:1373
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pin_task_context
```
**Symbols:**

```
ffffffff811fa060-ffffffff811fa140: perf_lock_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct perf_event_context *perf_lock_task_context(struct task_struct *task, int ctxn, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81204e80)
Location: kernel/events/core.c:1373
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pin_task_context
```
**Symbols:**

```
ffffffff81204e80-ffffffff81204f62: perf_lock_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct perf_event_context *perf_lock_task_context(struct task_struct *task, int ctxn, long unsigned int *flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812114c0)
Location: kernel/events/core.c:1373
Inline: False
Direct callers:
  - kernel/events/core.c:perf_pin_task_context
```
**Symbols:**

```
ffffffff812114c0-ffffffff812115bb: perf_lock_task_context (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int ctxn</code>
</li>
<li>
<b>Param reordered. </b>
<code>task, ctxn, flags</code> ➡️ <code>task, flags</code>
</li>
</ul>
</details>
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
