# Function: <code>add_wait_queue_exclusive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void add_wait_queue_exclusive(wait_queue_head_t *q, wait_queue_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c3250)
Location: kernel/sched/wait.c:34
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_start
```
**Symbols:**

```
ffffffff810c3250-ffffffff810c3298: add_wait_queue_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void add_wait_queue_exclusive(wait_queue_head_t *q, wait_queue_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c6be0)
Location: kernel/sched/wait.c:34
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_start
  - fs/eventpoll.c:ep_ptable_queue_proc
```
**Symbols:**

```
ffffffff810c6be0-ffffffff810c6c28: add_wait_queue_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void add_wait_queue_exclusive(wait_queue_head_t *q, wait_queue_t *wait);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ccbc0)
Location: kernel/sched/wait.c:34
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
**Symbols:**

```
ffffffff810ccbc0-ffffffff810ccc08: add_wait_queue_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c9480)
Location: kernel/sched/wait.c:35
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
**Symbols:**

```
ffffffff810c9480-ffffffff810c94c8: add_wait_queue_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d0b70)
Location: kernel/sched/wait.c:35
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
**Symbols:**

```
ffffffff810d0b70-ffffffff810d0bb8: add_wait_queue_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d90b0)
Location: kernel/sched/wait.c:28
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
**Symbols:**

```
ffffffff810d90b0-ffffffff810d90f8: add_wait_queue_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e2bb0)
Location: kernel/sched/wait.c:28
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
**Symbols:**

```
ffffffff810e2bb0-ffffffff810e2bf8: add_wait_queue_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e97c0)
Location: kernel/sched/wait.c:29
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
**Symbols:**

```
ffffffff810e97c0-ffffffff810e9808: add_wait_queue_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f5190)
Location: kernel/sched/wait.c:29
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
**Symbols:**

```
ffffffff810f5190-ffffffff810f51d8: add_wait_queue_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fe8b0)
Location: kernel/sched/wait.c:29
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
**Symbols:**

```
ffffffff810fe8b0-ffffffff810fe8f8: add_wait_queue_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fd230)
Location: kernel/sched/wait.c:29
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/io_uring.c:__io_queue_proc
```
**Symbols:**

```
ffffffff810fd230-ffffffff810fd278: add_wait_queue_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ff5f0)
Location: kernel/sched/wait.c:29
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/io_uring.c:__io_queue_proc
```
**Symbols:**

```
ffffffff810ff5f0-ffffffff810ff638: add_wait_queue_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff8111b6e0)
Location: kernel/sched/wait.c:29
Inline: False
Direct callers:
  - kernel/audit.c:audit_receive
  - fs/eventpoll.c:ep_ptable_queue_proc
  - fs/io_uring.c:__io_queue_proc
```
**Symbols:**

```
ffffffff8111b6e0-ffffffff8111b728: add_wait_queue_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113b940)
Location: kernel/sched/wait.c:28
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_receive
  - fs/eventpoll.c:ep_ptable_queue_proc
  - io_uring/io_uring.c:__io_queue_proc
```
**Symbols:**

```
ffffffff8113b940-ffffffff8113b996: add_wait_queue_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811663a0)
Location: kernel/sched/wait.c:28
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_receive
  - fs/eventpoll.c:ep_ptable_queue_proc
  - io_uring/poll.c:__io_queue_proc
```
**Symbols:**

```
ffffffff811663a0-ffffffff811663f6: add_wait_queue_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81176810)
Location: kernel/sched/wait.c:28
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_receive
  - fs/eventpoll.c:ep_ptable_queue_proc
  - io_uring/poll.c:__io_queue_proc
```
**Symbols:**

```
ffffffff81176810-ffffffff81176866: add_wait_queue_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81184a90)
Location: kernel/sched/wait.c:28
Inline: False
Direct callers:
  - kernel/audit.c:audit_log_start
  - kernel/audit.c:audit_receive
  - fs/eventpoll.c:ep_ptable_queue_proc
  - io_uring/poll.c:__io_queue_proc
```
**Symbols:**

```
ffffffff81184a90-ffffffff81184ae6: add_wait_queue_exclusive (STB_GLOBAL)
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
void add_wait_queue_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffff8000101588a0)
Location: kernel/sched/wait.c:29
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
**Symbols:**

```
ffff8000101588a0-ffff800010158960: add_wait_queue_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c03a57c4)
Location: kernel/sched/wait.c:29
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
**Symbols:**

```
c03a57c4-c03a5818: add_wait_queue_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c0000000001ac690)
Location: kernel/sched/wait.c:29
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
**Symbols:**

```
c0000000001ac690-c0000000001ac714: add_wait_queue_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffe0000fe768)
Location: kernel/sched/wait.c:29
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
**Symbols:**

```
ffffffe0000fe768-ffffffe0000fe7c6: add_wait_queue_exclusive (STB_GLOBAL)
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
void add_wait_queue_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ee590)
Location: kernel/sched/wait.c:29
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
**Symbols:**

```
ffffffff810ee590-ffffffff810ee5d8: add_wait_queue_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810de620)
Location: kernel/sched/wait.c:29
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
**Symbols:**

```
ffffffff810de620-ffffffff810de668: add_wait_queue_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810eb6c0)
Location: kernel/sched/wait.c:29
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
**Symbols:**

```
ffffffff810eb6c0-ffffffff810eb708: add_wait_queue_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void add_wait_queue_exclusive(struct wait_queue_head *wq_head, struct wait_queue_entry *wq_entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f6720)
Location: kernel/sched/wait.c:29
Inline: False
Direct callers:
  - fs/eventpoll.c:ep_ptable_queue_proc
```
**Symbols:**

```
ffffffff810f6720-ffffffff810f6768: add_wait_queue_exclusive (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct wait_queue_head *wq_head</code>
</li>
<li>
<b>Param added. </b>
<code>struct wait_queue_entry *wq_entry</code>
</li>
<li>
<b>Param removed. </b>
<code>wait_queue_head_t *q</code>
</li>
<li>
<b>Param removed. </b>
<code>wait_queue_t *wait</code>
</li>
</ul>
</details>
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
