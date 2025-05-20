# Function: <code>flush_signals</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void flush_signals(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108dbd0)
Location: kernel/signal.c:419
Inline: False
Direct callers:
  - kernel/signal.c:ignore_signals
  - drivers/md/md.c:md_thread
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
```
**Symbols:**

```
ffffffff8108dbd0-ffffffff8108dc35: flush_signals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void flush_signals(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81090c50)
Location: kernel/signal.c:419
Inline: False
Direct callers:
  - kernel/signal.c:ignore_signals
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff81090c50-ffffffff81090cb5: flush_signals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void flush_signals(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81095be0)
Location: kernel/signal.c:419
Inline: False
Direct callers:
  - kernel/signal.c:ignore_signals
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff81095be0-ffffffff81095c40: flush_signals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void flush_signals(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092b90)
Location: kernel/signal.c:425
Inline: False
Direct callers:
  - kernel/signal.c:ignore_signals
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff81092b90-ffffffff81092bf0: flush_signals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void flush_signals(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099a70)
Location: kernel/signal.c:427
Inline: False
Direct callers:
  - kernel/signal.c:ignore_signals
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff81099a70-ffffffff81099ad0: flush_signals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void flush_signals(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109da40)
Location: kernel/signal.c:429
Inline: False
Direct callers:
  - kernel/signal.c:ignore_signals
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff8109da40-ffffffff8109daa0: flush_signals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void flush_signals(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a5d50)
Location: kernel/signal.c:460
Inline: False
Direct callers:
  - kernel/signal.c:ignore_signals
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810a5d50-ffffffff810a5db0: flush_signals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void flush_signals(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aaa20)
Location: kernel/signal.c:470
Inline: False
Direct callers:
  - kernel/signal.c:ignore_signals
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810aaa20-ffffffff810aaa72: flush_signals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void flush_signals(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b1020)
Location: kernel/signal.c:475
Inline: False
Direct callers:
  - kernel/signal.c:ignore_signals
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810b1020-ffffffff810b1072: flush_signals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void flush_signals(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b81f0)
Location: kernel/signal.c:475
Inline: False
Direct callers:
  - kernel/signal.c:ignore_signals
  - fs/io_uring.c:io_sq_thread
  - fs/io-wq.c:io_wqe_worker
  - fs/io-wq.c:io_assign_current_work
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810b81f0-ffffffff810b82c8: flush_signals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void flush_signals(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b34a0)
Location: kernel/signal.c:476
Inline: False
Direct callers:
  - kernel/signal.c:ignore_signals
  - fs/io-wq.c:io_wqe_worker
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810b34a0-ffffffff810b3578: flush_signals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void flush_signals(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b4ad0)
Location: kernel/signal.c:475
Inline: False
Direct callers:
  - kernel/signal.c:ignore_signals
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810b4ad0-ffffffff810b4ba8: flush_signals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void flush_signals(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810c99d0)
Location: kernel/signal.c:476
Inline: False
Direct callers:
  - kernel/signal.c:ignore_signals
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810c99d0-ffffffff810c9a22: flush_signals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void flush_signals(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e1420)
Location: kernel/signal.c:476
Inline: False
Direct callers:
  - kernel/signal.c:ignore_signals
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810e1420-ffffffff810e147c: flush_signals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void flush_signals(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811016a0)
Location: kernel/signal.c:476
Inline: False
Direct callers:
  - kernel/signal.c:ignore_signals
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff811016a0-ffffffff811016fc: flush_signals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void flush_signals(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110d800)
Location: kernel/signal.c:477
Inline: False
Direct callers:
  - kernel/signal.c:ignore_signals
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff8110d800-ffffffff8110d85c: flush_signals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void flush_signals(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81117140)
Location: kernel/signal.c:468
Inline: False
Direct callers:
  - kernel/signal.c:ignore_signals
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff81117140-ffffffff8111719c: flush_signals (STB_GLOBAL)
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
void flush_signals(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff80001010cb18)
Location: kernel/signal.c:475
Inline: False
Direct callers:
  - kernel/signal.c:ignore_signals
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffff80001010cb18-ffff80001010cbe4: flush_signals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void flush_signals(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0364e78)
Location: kernel/signal.c:475
Inline: False
Direct callers:
  - arch/arm/common/bL_switcher.c:bL_switcher_thread
  - kernel/signal.c:ignore_signals
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
c0364e78-c0364ed0: flush_signals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void flush_signals(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000153b00)
Location: kernel/signal.c:475
Inline: False
Direct callers:
  - kernel/signal.c:ignore_signals
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
c000000000153b00-c000000000153b84: flush_signals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void flush_signals(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000ce1b0)
Location: kernel/signal.c:475
Inline: False
Direct callers:
  - kernel/signal.c:ignore_signals
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffe0000ce1b0-ffffffe0000ce212: flush_signals (STB_GLOBAL)
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
void flush_signals(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ab390)
Location: kernel/signal.c:475
Inline: False
Direct callers:
  - kernel/signal.c:ignore_signals
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810ab390-ffffffff810ab3e2: flush_signals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void flush_signals(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81099d30)
Location: kernel/signal.c:475
Inline: False
Direct callers:
  - kernel/signal.c:ignore_signals
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff81099d30-ffffffff81099d82: flush_signals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void flush_signals(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810aa8f0)
Location: kernel/signal.c:475
Inline: False
Direct callers:
  - kernel/signal.c:ignore_signals
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810aa8f0-ffffffff810aa942: flush_signals (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void flush_signals(struct task_struct *t);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b29d0)
Location: kernel/signal.c:475
Inline: False
Direct callers:
  - kernel/signal.c:ignore_signals
  - fs/io_uring.c:io_sq_thread
  - drivers/md/md.c:md_check_recovery
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_do_sync
  - drivers/md/md.c:md_thread
```
**Symbols:**

```
ffffffff810b29d0-ffffffff810b2a22: flush_signals (STB_GLOBAL)
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
