# Function: <code>autoremove_wake_function</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int autoremove_wake_function(wait_queue_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c39e1)
Location: kernel/sched/wait.c:291
Inline: True
Direct callers:
  - kernel/workqueue.c:cwt_wakefn
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - net/core/datagram.c:receiver_wake_function
```
**Symbols:**

```
ffffffff810c3a10-ffffffff810c3a44: autoremove_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int autoremove_wake_function(wait_queue_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c736d)
Location: kernel/sched/wait.c:291
Inline: True
Direct callers:
  - kernel/workqueue.c:cwt_wakefn
  - mm/memcontrol.c:memcg_oom_wake_function
  - net/core/datagram.c:receiver_wake_function
```
**Symbols:**

```
ffffffff810c73a0-ffffffff810c73d4: autoremove_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int autoremove_wake_function(wait_queue_t *wait, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810cd23d)
Location: kernel/sched/wait.c:279
Inline: True
Direct callers:
  - kernel/workqueue.c:cwt_wakefn
  - mm/filemap.c:wake_page_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - net/core/datagram.c:receiver_wake_function
```
**Symbols:**

```
ffffffff810cd270-ffffffff810cd2a4: autoremove_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int autoremove_wake_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c9b20)
Location: kernel/sched/wait.c:320
Inline: True
Direct callers:
  - kernel/workqueue.c:cwt_wakefn
  - kernel/sched/wait_bit.c:wake_atomic_t_function
  - kernel/sched/wait_bit.c:wake_bit_function
  - mm/filemap.c:wake_page_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - net/core/datagram.c:receiver_wake_function
```
**Symbols:**

```
ffffffff810c9b20-ffffffff810c9b54: autoremove_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int autoremove_wake_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d1340)
Location: kernel/sched/wait.c:375
Inline: True
Direct callers:
  - kernel/workqueue.c:cwt_wakefn
  - kernel/sched/wait_bit.c:wake_atomic_t_function
  - kernel/sched/wait_bit.c:wake_bit_function
  - mm/filemap.c:wake_page_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - net/core/datagram.c:receiver_wake_function
```
**Symbols:**

```
ffffffff810d1340-ffffffff810d1374: autoremove_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int autoremove_wake_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d9890)
Location: kernel/sched/wait.c:371
Inline: True
Direct callers:
  - kernel/workqueue.c:cwt_wakefn
  - kernel/sched/wait_bit.c:var_wake_function
  - kernel/sched/wait_bit.c:wake_bit_function
  - mm/filemap.c:wake_page_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - net/core/datagram.c:receiver_wake_function
```
**Symbols:**

```
ffffffff810d9890-ffffffff810d98c4: autoremove_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int autoremove_wake_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e3390)
Location: kernel/sched/wait.c:373
Inline: True
Direct callers:
  - kernel/workqueue.c:cwt_wakefn
  - kernel/sched/wait_bit.c:var_wake_function
  - kernel/sched/wait_bit.c:wake_bit_function
  - mm/filemap.c:wake_page_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - net/core/datagram.c:receiver_wake_function
```
**Symbols:**

```
ffffffff810e3390-ffffffff810e33c4: autoremove_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int autoremove_wake_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e9fa0)
Location: kernel/sched/wait.c:370
Inline: True
Direct callers:
  - kernel/workqueue.c:cwt_wakefn
  - kernel/sched/wait_bit.c:var_wake_function
  - kernel/sched/wait_bit.c:wake_bit_function
  - mm/filemap.c:wake_page_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - net/core/datagram.c:receiver_wake_function
```
**Symbols:**

```
ffffffff810e9fa0-ffffffff810e9fd4: autoremove_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int autoremove_wake_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f5970)
Location: kernel/sched/wait.c:370
Inline: True
Direct callers:
  - kernel/workqueue.c:cwt_wakefn
  - kernel/sched/wait_bit.c:var_wake_function
  - kernel/sched/wait_bit.c:wake_bit_function
  - mm/filemap.c:wake_page_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - fs/io_uring.c:io_wake_function
  - net/core/datagram.c:receiver_wake_function
```
**Symbols:**

```
ffffffff810f5970-ffffffff810f59a4: autoremove_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int autoremove_wake_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fee60)
Location: kernel/sched/wait.c:387
Inline: True
Direct callers:
  - kernel/workqueue.c:cwt_wakefn
  - kernel/sched/wait_bit.c:var_wake_function
  - kernel/sched/wait_bit.c:wake_bit_function
  - mm/filemap.c:wake_page_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - fs/io_uring.c:io_wake_function
  - net/core/datagram.c:receiver_wake_function
```
**Symbols:**

```
ffffffff810fee60-ffffffff810fee97: autoremove_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int autoremove_wake_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fd760)
Location: kernel/sched/wait.c:402
Inline: True
Direct callers:
  - kernel/workqueue.c:cwt_wakefn
  - kernel/sched/wait_bit.c:var_wake_function
  - kernel/sched/wait_bit.c:wake_bit_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - fs/io_uring.c:io_wake_function
  - net/core/datagram.c:receiver_wake_function
```
**Symbols:**

```
ffffffff810fd760-ffffffff810fd797: autoremove_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int autoremove_wake_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ffb40)
Location: kernel/sched/wait.c:407
Inline: True
Direct callers:
  - kernel/workqueue.c:cwt_wakefn
  - kernel/sched/wait_bit.c:var_wake_function
  - kernel/sched/wait_bit.c:wake_bit_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - fs/io_uring.c:io_wake_function
  - net/core/datagram.c:receiver_wake_function
```
**Symbols:**

```
ffffffff810ffb40-ffffffff810ffb77: autoremove_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int autoremove_wake_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff8111bc40)
Location: kernel/sched/wait.c:415
Inline: True
Direct callers:
  - kernel/workqueue.c:cwt_wakefn
  - kernel/sched/wait_bit.c:var_wake_function
  - kernel/sched/wait_bit.c:wake_bit_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - fs/io_uring.c:io_wake_function
  - net/core/datagram.c:receiver_wake_function
```
**Symbols:**

```
ffffffff8111bc40-ffffffff8111bc77: autoremove_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int autoremove_wake_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81141de5)
Location: kernel/sched/wait.c:414
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:var_wake_function
  - kernel/sched/build_utility.c:var_wake_function
  - kernel/sched/build_utility.c:wake_bit_function
  - kernel/sched/build_utility.c:wake_bit_function
Direct callers:
  - kernel/workqueue.c:cwt_wakefn
  - mm/memcontrol.c:memcg_oom_wake_function
  - io_uring/io_uring.c:io_wake_function
  - net/core/datagram.c:receiver_wake_function
```
**Symbols:**

```
ffffffff8113e890-ffffffff8113e8d3: autoremove_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int autoremove_wake_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116cae5)
Location: kernel/sched/wait.c:418
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:var_wake_function
  - kernel/sched/build_utility.c:var_wake_function
  - kernel/sched/build_utility.c:wake_bit_function
  - kernel/sched/build_utility.c:wake_bit_function
Direct callers:
  - kernel/workqueue.c:cwt_wakefn
  - mm/memcontrol.c:memcg_oom_wake_function
  - io_uring/io_uring.c:io_wake_function
  - net/core/datagram.c:receiver_wake_function
```
**Symbols:**

```
ffffffff81168e40-ffffffff81168e83: autoremove_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int autoremove_wake_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117d34d)
Location: kernel/sched/wait.c:418
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:var_wake_function
  - kernel/sched/build_utility.c:var_wake_function
  - kernel/sched/build_utility.c:wake_bit_function
  - kernel/sched/build_utility.c:wake_bit_function
Direct callers:
  - kernel/workqueue.c:cwt_wakefn
  - mm/memcontrol.c:memcg_oom_wake_function
  - io_uring/io_uring.c:io_wake_function
  - net/core/datagram.c:receiver_wake_function
```
**Symbols:**

```
ffffffff811795b0-ffffffff811795f3: autoremove_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int autoremove_wake_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118b08d)
Location: kernel/sched/wait.c:383
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:var_wake_function
  - kernel/sched/build_utility.c:var_wake_function
  - kernel/sched/build_utility.c:wake_bit_function
  - kernel/sched/build_utility.c:wake_bit_function
Direct callers:
  - kernel/workqueue.c:cwt_wakefn
  - kernel/seccomp.c:recv_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - io_uring/io_uring.c:io_wake_function
  - net/core/datagram.c:receiver_wake_function
```
**Symbols:**

```
ffffffff811870f0-ffffffff81187133: autoremove_wake_function (STB_GLOBAL)
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
int autoremove_wake_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffff8000101581e8)
Location: kernel/sched/wait.c:370
Inline: True
Direct callers:
  - kernel/workqueue.c:cwt_wakefn
  - kernel/sched/wait_bit.c:var_wake_function
  - kernel/sched/wait_bit.c:wake_bit_function
  - mm/filemap.c:wake_page_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - fs/io_uring.c:io_wake_function
  - net/core/datagram.c:receiver_wake_function
```
**Symbols:**

```
ffff8000101581e8-ffff800010158250: autoremove_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int autoremove_wake_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c03a6238)
Location: kernel/sched/wait.c:370
Inline: True
Direct callers:
  - kernel/workqueue.c:cwt_wakefn
  - kernel/sched/wait_bit.c:var_wake_function
  - kernel/sched/wait_bit.c:wake_bit_function
  - mm/filemap.c:wake_page_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - fs/io_uring.c:io_wake_function
  - net/core/datagram.c:receiver_wake_function
```
**Symbols:**

```
c03a6238-c03a627c: autoremove_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int autoremove_wake_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c0000000001ad380)
Location: kernel/sched/wait.c:370
Inline: True
Direct callers:
  - kernel/workqueue.c:cwt_wakefn
  - kernel/sched/wait_bit.c:var_wake_function
  - kernel/sched/wait_bit.c:wake_bit_function
  - mm/filemap.c:wake_page_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - fs/io_uring.c:io_wake_function
  - net/core/datagram.c:receiver_wake_function
```
**Symbols:**

```
c0000000001ad380-c0000000001ad3e4: autoremove_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int autoremove_wake_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffe0000fef0c)
Location: kernel/sched/wait.c:370
Inline: True
Direct callers:
  - kernel/workqueue.c:cwt_wakefn
  - kernel/sched/wait_bit.c:var_wake_function
  - kernel/sched/wait_bit.c:wake_bit_function
  - mm/filemap.c:wake_page_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - fs/io_uring.c:io_wake_function
  - net/core/datagram.c:receiver_wake_function
```
**Symbols:**

```
ffffffe0000fef0c-ffffffe0000fef60: autoremove_wake_function (STB_GLOBAL)
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
int autoremove_wake_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810eed70)
Location: kernel/sched/wait.c:370
Inline: True
Direct callers:
  - kernel/workqueue.c:cwt_wakefn
  - kernel/sched/wait_bit.c:var_wake_function
  - kernel/sched/wait_bit.c:wake_bit_function
  - mm/filemap.c:wake_page_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - fs/io_uring.c:io_wake_function
  - net/core/datagram.c:receiver_wake_function
```
**Symbols:**

```
ffffffff810eed70-ffffffff810eeda4: autoremove_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int autoremove_wake_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810dedf0)
Location: kernel/sched/wait.c:370
Inline: True
Direct callers:
  - kernel/workqueue.c:cwt_wakefn
  - kernel/sched/wait_bit.c:var_wake_function
  - kernel/sched/wait_bit.c:wake_bit_function
  - mm/filemap.c:wake_page_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - fs/io_uring.c:io_wake_function
  - net/core/datagram.c:receiver_wake_function
```
**Symbols:**

```
ffffffff810dedf0-ffffffff810dee24: autoremove_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int autoremove_wake_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ebea0)
Location: kernel/sched/wait.c:370
Inline: True
Direct callers:
  - kernel/workqueue.c:cwt_wakefn
  - kernel/sched/wait_bit.c:var_wake_function
  - kernel/sched/wait_bit.c:wake_bit_function
  - mm/filemap.c:wake_page_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - fs/io_uring.c:io_wake_function
  - net/core/datagram.c:receiver_wake_function
```
**Symbols:**

```
ffffffff810ebea0-ffffffff810ebed4: autoremove_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int autoremove_wake_function(struct wait_queue_entry *wq_entry, unsigned int mode, int sync, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f6ef0)
Location: kernel/sched/wait.c:370
Inline: True
Direct callers:
  - kernel/workqueue.c:cwt_wakefn
  - kernel/sched/wait_bit.c:var_wake_function
  - kernel/sched/wait_bit.c:wake_bit_function
  - mm/filemap.c:wake_page_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - mm/memcontrol.c:memcg_oom_wake_function
  - fs/io_uring.c:io_wake_function
  - net/core/datagram.c:receiver_wake_function
```
**Symbols:**

```
ffffffff810f6ef0-ffffffff810f6f24: autoremove_wake_function (STB_GLOBAL)
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
<code>struct wait_queue_entry *wq_entry</code>
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
