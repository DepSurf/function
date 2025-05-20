# Function: <code>perf_pin_task_context</code>

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
In kernel/events/core.c (ffffffff81184dc3)
Location: kernel/events/core.c:1107
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_task
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct perf_event_context *perf_pin_task_context(struct task_struct *task, int ctxn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8118cb40)
Location: kernel/events/core.c:1356
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_exit_task
```
**Symbols:**

```
ffffffff8118cb40-ffffffff8118cb9b: perf_pin_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct perf_event_context *perf_pin_task_context(struct task_struct *task, int ctxn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8119bca0)
Location: kernel/events/core.c:1364
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_exit_task
```
**Symbols:**

```
ffffffff8119bca0-ffffffff8119bcfb: perf_pin_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct perf_event_context *perf_pin_task_context(struct task_struct *task, int ctxn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a3a90)
Location: kernel/events/core.c:1356
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_exit_task
```
**Symbols:**

```
ffffffff811a3a90-ffffffff811a3ae7: perf_pin_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct perf_event_context *perf_pin_task_context(struct task_struct *task, int ctxn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b7c60)
Location: kernel/events/core.c:1404
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_exit_task
```
**Symbols:**

```
ffffffff811b7c60-ffffffff811b7cb7: perf_pin_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct perf_event_context *perf_pin_task_context(struct task_struct *task, int ctxn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811daee0)
Location: kernel/events/core.c:1427
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_exit_task
```
**Symbols:**

```
ffffffff811daee0-ffffffff811daf3b: perf_pin_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct perf_event_context *perf_pin_task_context(struct task_struct *task, int ctxn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811eae70)
Location: kernel/events/core.c:1427
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_exit_task
```
**Symbols:**

```
ffffffff811eae70-ffffffff811eaecb: perf_pin_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct perf_event_context *perf_pin_task_context(struct task_struct *task, int ctxn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81201cd0)
Location: kernel/events/core.c:1429
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_exit_task
```
**Symbols:**

```
ffffffff81201cd0-ffffffff81201d2d: perf_pin_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct perf_event_context *perf_pin_task_context(struct task_struct *task, int ctxn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120eb80)
Location: kernel/events/core.c:1429
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_exit_task
```
**Symbols:**

```
ffffffff8120eb80-ffffffff8120ebdd: perf_pin_task_context (STB_LOCAL)
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
In kernel/events/core.c (ffffffff8123e004)
Location: kernel/events/core.c:1491
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_exit_task_context
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
In kernel/events/core.c (ffffffff812483c4)
Location: kernel/events/core.c:1509
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_exit_task_context
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
In kernel/events/core.c (ffffffff8124c2b7)
Location: kernel/events/core.c:1507
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
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
In kernel/events/core.c (ffffffff81287bb6)
Location: kernel/events/core.c:1538
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
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
In kernel/events/core.c (ffffffff812dc3be)
Location: kernel/events/core.c:1447
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
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
In kernel/events/core.c (ffffffff813446c7)
Location: kernel/events/core.c:1420
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
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
In kernel/events/core.c (ffffffff81375767)
Location: kernel/events/core.c:1420
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
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
In kernel/events/core.c (ffffffff8139ea97)
Location: kernel/events/core.c:1431
Inline: True
Inline callers:
  - kernel/events/core.c:perf_event_init_context
  - kernel/events/core.c:perf_event_exit_task
  - kernel/events/core.c:perf_event_exec
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
struct perf_event_context *perf_pin_task_context(struct task_struct *task, int ctxn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff8000102955c8)
Location: kernel/events/core.c:1429
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_exit_task_context
```
**Symbols:**

```
ffff8000102955c8-ffff80001029563c: perf_pin_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct perf_event_context *perf_pin_task_context(struct task_struct *task, int ctxn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c0ae8)
Location: kernel/events/core.c:1429
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_exit_task_context
```
**Symbols:**

```
c04c0ae8-c04c0b5c: perf_pin_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct perf_event_context *perf_pin_task_context(struct task_struct *task, int ctxn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000033e940)
Location: kernel/events/core.c:1429
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_exit_task
```
**Symbols:**

```
c00000000033e940-c00000000033e9c4: perf_pin_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct perf_event_context *perf_pin_task_context(struct task_struct *task, int ctxn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c8a82)
Location: kernel/events/core.c:1429
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_exit_task
```
**Symbols:**

```
ffffffe0001c8a82-ffffffe0001c8ac0: perf_pin_task_context (STB_LOCAL)
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
struct perf_event_context *perf_pin_task_context(struct task_struct *task, int ctxn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812071a0)
Location: kernel/events/core.c:1429
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_exit_task
```
**Symbols:**

```
ffffffff812071a0-ffffffff812071fd: perf_pin_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct perf_event_context *perf_pin_task_context(struct task_struct *task, int ctxn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fa140)
Location: kernel/events/core.c:1429
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_exit_task
```
**Symbols:**

```
ffffffff811fa140-ffffffff811fa19d: perf_pin_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct perf_event_context *perf_pin_task_context(struct task_struct *task, int ctxn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81204f70)
Location: kernel/events/core.c:1429
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_exit_task
```
**Symbols:**

```
ffffffff81204f70-ffffffff81204fcd: perf_pin_task_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct perf_event_context *perf_pin_task_context(struct task_struct *task, int ctxn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812115c0)
Location: kernel/events/core.c:1429
Inline: False
Direct callers:
  - kernel/events/core.c:perf_event_init_task
  - kernel/events/core.c:perf_event_exit_task
```
**Symbols:**

```
ffffffff812115c0-ffffffff8121161d: perf_pin_task_context (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
