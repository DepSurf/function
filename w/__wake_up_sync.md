# Function: <code>__wake_up_sync</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __wake_up_sync(wait_queue_head_t *q, unsigned int mode, int nr_exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c3800)
Location: kernel/sched/wait.c:153
Inline: False
Direct callers:
  - fs/splice.c:splice_to_pipe
  - fs/coredump.c:do_coredump
  - fs/fuse/file.c:fuse_notify_poll_wakeup
```
**Symbols:**

```
ffffffff810c3800-ffffffff810c3812: __wake_up_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __wake_up_sync(wait_queue_head_t *q, unsigned int mode, int nr_exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c7190)
Location: kernel/sched/wait.c:153
Inline: False
Direct callers:
  - fs/splice.c:splice_to_pipe
  - fs/coredump.c:do_coredump
  - fs/fuse/file.c:fuse_notify_poll_wakeup
```
**Symbols:**

```
ffffffff810c7190-ffffffff810c71a2: __wake_up_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __wake_up_sync(wait_queue_head_t *q, unsigned int mode, int nr_exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ccff0)
Location: kernel/sched/wait.c:153
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fuse/file.c:fuse_notify_poll_wakeup
```
**Symbols:**

```
ffffffff810ccff0-ffffffff810cd002: __wake_up_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c9850)
Location: kernel/sched/wait.c:155
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fuse/file.c:fuse_notify_poll_wakeup
```
**Symbols:**

```
ffffffff810c9850-ffffffff810c9862: __wake_up_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d1060)
Location: kernel/sched/wait.c:210
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fuse/file.c:fuse_notify_poll_wakeup
```
**Symbols:**

```
ffffffff810d1060-ffffffff810d1082: __wake_up_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d9410)
Location: kernel/sched/wait.c:204
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fuse/file.c:fuse_notify_poll_wakeup
```
**Symbols:**

```
ffffffff810d9410-ffffffff810d9431: __wake_up_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e2f10)
Location: kernel/sched/wait.c:206
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fuse/file.c:fuse_notify_poll_wakeup
```
**Symbols:**

```
ffffffff810e2f10-ffffffff810e2f31: __wake_up_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e9cb0)
Location: kernel/sched/wait.c:203
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fuse/file.c:fuse_notify_poll_wakeup
```
**Symbols:**

```
ffffffff810e9cb0-ffffffff810e9cd1: __wake_up_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f5680)
Location: kernel/sched/wait.c:203
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fuse/file.c:fuse_notify_poll_wakeup
```
**Symbols:**

```
ffffffff810f5680-ffffffff810f56a1: __wake_up_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head *wq_head, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ff030)
Location: kernel/sched/wait.c:220
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_notify_poll_wakeup
```
**Symbols:**

```
ffffffff810ff030-ffffffff810ff053: __wake_up_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head *wq_head, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fd8d0)
Location: kernel/sched/wait.c:235
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_notify_poll_wakeup
```
**Symbols:**

```
ffffffff810fd8d0-ffffffff810fd8f3: __wake_up_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head *wq_head, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ffcb0)
Location: kernel/sched/wait.c:235
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fuse/file.c:fuse_notify_poll_wakeup
```
**Symbols:**

```
ffffffff810ffcb0-ffffffff810ffcd3: __wake_up_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head *wq_head, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff8111bda0)
Location: kernel/sched/wait.c:235
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fuse/file.c:fuse_notify_poll_wakeup
```
**Symbols:**

```
ffffffff8111bda0-ffffffff8111bdc3: __wake_up_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head *wq_head, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113fcd0)
Location: kernel/sched/wait.c:234
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fuse/file.c:fuse_notify_poll_wakeup
```
**Symbols:**

```
ffffffff8113fcd0-ffffffff8113fd11: __wake_up_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head *wq_head, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116a8c0)
Location: kernel/sched/wait.c:238
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fuse/file.c:fuse_notify_poll_wakeup
```
**Symbols:**

```
ffffffff8116a8c0-ffffffff8116a905: __wake_up_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head *wq_head, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117afd0)
Location: kernel/sched/wait.c:238
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fuse/file.c:fuse_notify_poll_wakeup
```
**Symbols:**

```
ffffffff8117afd0-ffffffff8117b015: __wake_up_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head *wq_head, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118c220)
Location: kernel/sched/wait.c:203
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fuse/file.c:fuse_notify_poll_wakeup
```
**Symbols:**

```
ffffffff8118c220-ffffffff8118c28e: __wake_up_sync (STB_GLOBAL)
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
void __wake_up_sync(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffff800010158788)
Location: kernel/sched/wait.c:203
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fuse/file.c:fuse_notify_poll_wakeup
```
**Symbols:**

```
ffff800010158788-ffff8000101587dc: __wake_up_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c03a5ddc)
Location: kernel/sched/wait.c:203
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fuse/file.c:fuse_notify_poll_wakeup
```
**Symbols:**

```
c03a5ddc-c03a5e1c: __wake_up_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c0000000001ace80)
Location: kernel/sched/wait.c:203
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fuse/file.c:fuse_notify_poll_wakeup
```
**Symbols:**

```
c0000000001ace80-c0000000001aceac: __wake_up_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffe0000fec86)
Location: kernel/sched/wait.c:203
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fuse/file.c:fuse_notify_poll_wakeup
```
**Symbols:**

```
ffffffe0000fec86-ffffffe0000feccc: __wake_up_sync (STB_GLOBAL)
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
void __wake_up_sync(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810eea80)
Location: kernel/sched/wait.c:203
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fuse/file.c:fuse_notify_poll_wakeup
```
**Symbols:**

```
ffffffff810eea80-ffffffff810eeaa1: __wake_up_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810deb10)
Location: kernel/sched/wait.c:203
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fuse/file.c:fuse_notify_poll_wakeup
```
**Symbols:**

```
ffffffff810deb10-ffffffff810deb31: __wake_up_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ebbb0)
Location: kernel/sched/wait.c:203
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fuse/file.c:fuse_notify_poll_wakeup
```
**Symbols:**

```
ffffffff810ebbb0-ffffffff810ebbd1: __wake_up_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __wake_up_sync(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f6c10)
Location: kernel/sched/wait.c:203
Inline: False
Direct callers:
  - fs/coredump.c:do_coredump
  - fs/fuse/file.c:fuse_notify_poll_wakeup
```
**Symbols:**

```
ffffffff810f6c10-ffffffff810f6c31: __wake_up_sync (STB_GLOBAL)
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
<b>Param removed. </b>
<code>wait_queue_head_t *q</code>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int nr_exclusive</code>
</li>
</ul>
</details>
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
