# Function: <code>__wake_up_sync_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __wake_up_sync_key(wait_queue_head_t *q, unsigned int mode, int nr_exclusive, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c37a0)
Location: kernel/sched/wait.c:132
Inline: False
Direct callers:
  - kernel/exit.c:__wake_up_parent
  - kernel/sched/wait.c:__wake_up_sync
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_release
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff810c37a0-ffffffff810c37fc: __wake_up_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __wake_up_sync_key(wait_queue_head_t *q, unsigned int mode, int nr_exclusive, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c7130)
Location: kernel/sched/wait.c:132
Inline: False
Direct callers:
  - kernel/exit.c:__wake_up_parent
  - kernel/sched/wait.c:__wake_up_sync
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff810c7130-ffffffff810c718c: __wake_up_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __wake_up_sync_key(wait_queue_head_t *q, unsigned int mode, int nr_exclusive, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ccf90)
Location: kernel/sched/wait.c:132
Inline: False
Direct callers:
  - kernel/exit.c:__wake_up_parent
  - kernel/sched/wait.c:__wake_up_sync
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff810ccf90-ffffffff810ccfec: __wake_up_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __wake_up_sync_key(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c97f0)
Location: kernel/sched/wait.c:134
Inline: False
Direct callers:
  - kernel/exit.c:__wake_up_parent
  - kernel/sched/wait.c:__wake_up_sync
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff810c97f0-ffffffff810c984d: __wake_up_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_sync_key(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d1065)
Location: kernel/sched/wait.c:192
Inline: True
Inline callers:
  - kernel/sched/wait.c:__wake_up_sync
Direct callers:
  - kernel/exit.c:__wake_up_parent
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff810d1030-ffffffff810d1052: __wake_up_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_sync_key(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d9415)
Location: kernel/sched/wait.c:186
Inline: True
Inline callers:
  - kernel/sched/wait.c:__wake_up_sync
Direct callers:
  - kernel/exit.c:__wake_up_parent
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff810d93e0-ffffffff810d9401: __wake_up_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_sync_key(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e2f15)
Location: kernel/sched/wait.c:188
Inline: True
Inline callers:
  - kernel/sched/wait.c:__wake_up_sync
Direct callers:
  - kernel/exit.c:__wake_up_parent
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - net/unix/af_unix.c:unix_dgram_recvmsg
```
**Symbols:**

```
ffffffff810e2ee0-ffffffff810e2f01: __wake_up_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_sync_key(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e9cb5)
Location: kernel/sched/wait.c:185
Inline: True
Inline callers:
  - kernel/sched/wait.c:__wake_up_sync
Direct callers:
  - kernel/exit.c:__wake_up_parent
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff810e9c80-ffffffff810e9ca1: __wake_up_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_sync_key(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f5685)
Location: kernel/sched/wait.c:185
Inline: True
Inline callers:
  - kernel/sched/wait.c:__wake_up_sync
Direct callers:
  - kernel/exit.c:__wake_up_parent
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff810f5650-ffffffff810f5671: __wake_up_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_sync_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ff035)
Location: kernel/sched/wait.c:184
Inline: True
Inline callers:
  - kernel/sched/wait.c:__wake_up_sync
Direct callers:
  - kernel/exit.c:__wake_up_parent
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff810fed90-ffffffff810fedb3: __wake_up_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_sync_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fd8d5)
Location: kernel/sched/wait.c:199
Inline: True
Inline callers:
  - kernel/sched/wait.c:__wake_up_sync
Direct callers:
  - kernel/exit.c:__wake_up_parent
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff810fd690-ffffffff810fd6b3: __wake_up_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_sync_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ffcb5)
Location: kernel/sched/wait.c:199
Inline: True
Inline callers:
  - kernel/sched/wait.c:__wake_up_sync
Direct callers:
  - kernel/exit.c:__wake_up_parent
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff810ffa70-ffffffff810ffa93: __wake_up_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_sync_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff8111bda5)
Location: kernel/sched/wait.c:199
Inline: True
Inline callers:
  - kernel/sched/wait.c:__wake_up_sync
Direct callers:
  - kernel/exit.c:__wake_up_parent
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff8111bb40-ffffffff8111bb63: __wake_up_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_sync_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113fcd5)
Location: kernel/sched/wait.c:198
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__wake_up_sync
Direct callers:
  - kernel/exit.c:__wake_up_parent
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_wfree
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff8113c300-ffffffff8113c341: __wake_up_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_sync_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8116a8c5)
Location: kernel/sched/wait.c:202
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__wake_up_sync
Direct callers:
  - kernel/exit.c:__wake_up_parent
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_wfree
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff81166f60-ffffffff81166fa5: __wake_up_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_sync_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117afd5)
Location: kernel/sched/wait.c:202
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__wake_up_sync
Direct callers:
  - kernel/exit.c:__wake_up_parent
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_wfree
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff81177330-ffffffff81177375: __wake_up_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_sync_key(struct wait_queue_head *wq_head, unsigned int mode, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8118c225)
Location: kernel/sched/wait.c:167
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__wake_up_sync
Direct callers:
  - kernel/exit.c:__wake_up_parent
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/core/sock.c:sock_wfree
  - net/unix/af_unix.c:__unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff8118c2a0-ffffffff8118c315: __wake_up_sync_key (STB_GLOBAL)
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
void __wake_up_sync_key(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffff8000101587ac)
Location: kernel/sched/wait.c:185
Inline: True
Inline callers:
  - kernel/sched/wait.c:__wake_up_sync
Direct callers:
  - kernel/exit.c:__wake_up_parent
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffff800010158730-ffff800010158788: __wake_up_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_sync_key(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c03a5df4)
Location: kernel/sched/wait.c:185
Inline: True
Inline callers:
  - kernel/sched/wait.c:__wake_up_sync
Direct callers:
  - kernel/exit.c:__wake_up_parent
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
c03a5d9c-c03a5ddc: __wake_up_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_sync_key(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c0000000001ace90)
Location: kernel/sched/wait.c:185
Inline: True
Inline callers:
  - kernel/sched/wait.c:__wake_up_sync
Direct callers:
  - kernel/exit.c:__wake_up_parent
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
c0000000001ace50-c0000000001ace7c: __wake_up_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_sync_key(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffe0000feca4)
Location: kernel/sched/wait.c:185
Inline: True
Inline callers:
  - kernel/sched/wait.c:__wake_up_sync
Direct callers:
  - kernel/exit.c:__wake_up_parent
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffe0000fec3a-ffffffe0000fec86: __wake_up_sync_key (STB_GLOBAL)
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
void __wake_up_sync_key(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810eea85)
Location: kernel/sched/wait.c:185
Inline: True
Inline callers:
  - kernel/sched/wait.c:__wake_up_sync
Direct callers:
  - kernel/exit.c:__wake_up_parent
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff810eea50-ffffffff810eea71: __wake_up_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_sync_key(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810deb15)
Location: kernel/sched/wait.c:185
Inline: True
Inline callers:
  - kernel/sched/wait.c:__wake_up_sync
Direct callers:
  - kernel/exit.c:__wake_up_parent
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff810deae0-ffffffff810deb01: __wake_up_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_sync_key(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ebbb5)
Location: kernel/sched/wait.c:185
Inline: True
Inline callers:
  - kernel/sched/wait.c:__wake_up_sync
Direct callers:
  - kernel/exit.c:__wake_up_parent
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff810ebb80-ffffffff810ebba1: __wake_up_sync_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __wake_up_sync_key(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, void *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f6c15)
Location: kernel/sched/wait.c:185
Inline: True
Inline callers:
  - kernel/sched/wait.c:__wake_up_sync
Direct callers:
  - kernel/exit.c:__wake_up_parent
  - fs/pipe.c:pipe_release
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_write
  - fs/pipe.c:pipe_read
  - fs/pipe.c:pipe_read
  - net/core/sock.c:sock_def_write_space
  - net/core/sock.c:sock_def_readable
  - net/unix/af_unix.c:unix_dgram_recvmsg
  - net/unix/af_unix.c:unix_write_space
```
**Symbols:**

```
ffffffff810f6be0-ffffffff810f6c01: __wake_up_sync_key (STB_GLOBAL)
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
<li>
<b>Param reordered. </b>
<code>wq_head, mode, nr_exclusive, key</code> ➡️ <code>wq_head, mode, key</code>
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
