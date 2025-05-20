# Function: <code>default_wake_function</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int default_wake_function(wait_queue_t *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810abde0)
Location: kernel/sched/core.c:3345
Inline: False
Direct callers:
  - kernel/sched/wait.c:woken_wake_function
```
**Symbols:**

```
ffffffff810abde0-ffffffff810abdf4: default_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int default_wake_function(wait_queue_t *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810aea80)
Location: kernel/sched/core.c:3593
Inline: False
Direct callers:
  - kernel/sched/wait.c:woken_wake_function
```
**Symbols:**

```
ffffffff810aea80-ffffffff810aea94: default_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int default_wake_function(wait_queue_t *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b4bc0)
Location: kernel/sched/core.c:3624
Inline: False
Direct callers:
  - kernel/sched/wait.c:woken_wake_function
  - mm/shmem.c:synchronous_wake_function
```
**Symbols:**

```
ffffffff810b4bc0-ffffffff810b4bd4: default_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int default_wake_function(wait_queue_entry_t *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b0cb0)
Location: kernel/sched/core.c:3582
Inline: False
Direct callers:
  - kernel/sched/wait.c:woken_wake_function
  - mm/shmem.c:synchronous_wake_function
```
**Symbols:**

```
ffffffff810b0cb0-ffffffff810b0cc4: default_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int default_wake_function(wait_queue_entry_t *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810b8100)
Location: kernel/sched/core.c:3626
Inline: False
Direct callers:
  - kernel/sched/wait.c:woken_wake_function
  - mm/shmem.c:synchronous_wake_function
```
**Symbols:**

```
ffffffff810b8100-ffffffff810b8114: default_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int default_wake_function(wait_queue_entry_t *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810bfc00)
Location: kernel/sched/core.c:3736
Inline: False
Direct callers:
  - kernel/sched/wait.c:woken_wake_function
  - mm/shmem.c:synchronous_wake_function
  - fs/select.c:pollwake
```
**Symbols:**

```
ffffffff810bfc00-ffffffff810bfc14: default_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int default_wake_function(wait_queue_entry_t *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c8f80)
Location: kernel/sched/core.c:3720
Inline: False
Direct callers:
  - kernel/sched/wait.c:woken_wake_function
  - mm/shmem.c:synchronous_wake_function
  - fs/select.c:pollwake
```
**Symbols:**

```
ffffffff810c8f80-ffffffff810c8f94: default_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int default_wake_function(wait_queue_entry_t *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d0b20)
Location: kernel/sched/core.c:4139
Inline: False
Direct callers:
  - kernel/sched/wait.c:woken_wake_function
  - mm/shmem.c:synchronous_wake_function
  - fs/select.c:pollwake
```
**Symbols:**

```
ffffffff810d0b20-ffffffff810d0b34: default_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int default_wake_function(wait_queue_entry_t *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810daad0)
Location: kernel/sched/core.c:4341
Inline: False
Direct callers:
  - kernel/sched/wait.c:woken_wake_function
  - mm/shmem.c:synchronous_wake_function
  - fs/select.c:pollwake
  - block/blk-iocost.c:iocg_wake_fn
```
**Symbols:**

```
ffffffff810daad0-ffffffff810daae4: default_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int default_wake_function(wait_queue_entry_t *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e3960)
Location: kernel/sched/core.c:4573
Inline: False
Direct callers:
  - kernel/sched/wait.c:woken_wake_function
  - mm/shmem.c:synchronous_wake_function
  - fs/select.c:pollwake
  - block/blk-iocost.c:iocg_wake_fn
```
**Symbols:**

```
ffffffff810e3960-ffffffff810e3989: default_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int default_wake_function(wait_queue_entry_t *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e13d0)
Location: kernel/sched/core.c:5343
Inline: False
Direct callers:
  - kernel/sched/wait.c:woken_wake_function
  - mm/shmem.c:synchronous_wake_function
  - fs/select.c:pollwake
  - block/blk-iocost.c:iocg_wake_fn
```
**Symbols:**

```
ffffffff810e13d0-ffffffff810e13f9: default_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int default_wake_function(wait_queue_entry_t *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810e31f0)
Location: kernel/sched/core.c:5545
Inline: False
Direct callers:
  - kernel/sched/wait.c:woken_wake_function
  - mm/shmem.c:synchronous_wake_function
  - fs/select.c:pollwake
  - block/blk-iocost.c:iocg_wake_fn
```
**Symbols:**

```
ffffffff810e31f0-ffffffff810e3219: default_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int default_wake_function(wait_queue_entry_t *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810f9c90)
Location: kernel/sched/core.c:6708
Inline: False
Direct callers:
  - kernel/sched/wait.c:woken_wake_function
  - mm/shmem.c:synchronous_wake_function
  - fs/select.c:pollwake
  - block/blk-iocost.c:iocg_wake_fn
```
**Symbols:**

```
ffffffff810f9c90-ffffffff810f9cb9: default_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int default_wake_function(wait_queue_entry_t *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81116220)
Location: kernel/sched/core.c:6788
Inline: False
Direct callers:
  - kernel/exit.c:child_wait_callback
  - kernel/sched/build_utility.c:woken_wake_function
  - kernel/sched/build_utility.c:var_wake_function
  - kernel/sched/build_utility.c:wake_bit_function
  - mm/shmem.c:synchronous_wake_function
  - fs/select.c:pollwake
  - fs/eventpoll.c:ep_autoremove_wake_function
  - block/blk-iocost.c:iocg_wake_fn
```
**Symbols:**

```
ffffffff81116220-ffffffff8111625d: default_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int default_wake_function(wait_queue_entry_t *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8113d6e0)
Location: kernel/sched/core.c:6929
Inline: False
Direct callers:
  - kernel/exit.c:child_wait_callback
  - kernel/sched/build_utility.c:woken_wake_function
  - kernel/sched/build_utility.c:var_wake_function
  - kernel/sched/build_utility.c:wake_bit_function
  - mm/shmem.c:synchronous_wake_function
  - fs/select.c:pollwake
  - fs/eventpoll.c:ep_autoremove_wake_function
  - block/blk-iocost.c:iocg_wake_fn
```
**Symbols:**

```
ffffffff8113d6e0-ffffffff8113d71d: default_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int default_wake_function(wait_queue_entry_t *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff81151290)
Location: kernel/sched/core.c:7030
Inline: False
Direct callers:
  - kernel/exit.c:child_wait_callback
  - kernel/sched/build_utility.c:woken_wake_function
  - kernel/sched/build_utility.c:var_wake_function
  - kernel/sched/build_utility.c:wake_bit_function
  - mm/shmem.c:synchronous_wake_function
  - fs/select.c:pollwake
  - fs/eventpoll.c:ep_autoremove_wake_function
  - block/blk-iocost.c:iocg_wake_fn
```
**Symbols:**

```
ffffffff81151290-ffffffff811512cd: default_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int default_wake_function(wait_queue_entry_t *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff8115d120)
Location: kernel/sched/core.c:7055
Inline: False
Direct callers:
  - kernel/exit.c:child_wait_callback
  - kernel/sched/build_utility.c:woken_wake_function
  - kernel/sched/build_utility.c:var_wake_function
  - kernel/sched/build_utility.c:wake_bit_function
  - mm/shmem.c:synchronous_wake_function
  - fs/select.c:pollwake
  - fs/eventpoll.c:ep_autoremove_wake_function
  - block/blk-iocost.c:iocg_wake_fn
```
**Symbols:**

```
ffffffff8115d120-ffffffff8115d15d: default_wake_function (STB_GLOBAL)
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
int default_wake_function(wait_queue_entry_t *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffff80001013a620)
Location: kernel/sched/core.c:4341
Inline: False
Direct callers:
  - kernel/sched/wait.c:woken_wake_function
  - mm/shmem.c:synchronous_wake_function
  - fs/select.c:pollwake
  - block/blk-iocost.c:iocg_wake_fn
```
**Symbols:**

```
ffff80001013a620-ffff80001013a664: default_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int default_wake_function(wait_queue_entry_t *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c038a1ac)
Location: kernel/sched/core.c:4341
Inline: False
Direct callers:
  - kernel/sched/wait.c:woken_wake_function
  - mm/shmem.c:synchronous_wake_function
  - fs/select.c:pollwake
  - block/blk-iocost.c:iocg_wake_fn
```
**Symbols:**

```
c038a1ac-c038a1cc: default_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int default_wake_function(wait_queue_entry_t *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (c000000000187f30)
Location: kernel/sched/core.c:4341
Inline: False
Direct callers:
  - kernel/sched/wait.c:woken_wake_function
  - mm/shmem.c:synchronous_wake_function
  - fs/select.c:pollwake
  - block/blk-iocost.c:iocg_wake_fn
```
**Symbols:**

```
c000000000187f30-c000000000187f48: default_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int default_wake_function(wait_queue_entry_t *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffe0000e9fd8)
Location: kernel/sched/core.c:4341
Inline: False
Direct callers:
  - kernel/sched/wait.c:woken_wake_function
  - mm/shmem.c:synchronous_wake_function
  - fs/select.c:pollwake
  - block/blk-iocost.c:iocg_wake_fn
```
**Symbols:**

```
ffffffe0000e9fd8-ffffffe0000ea012: default_wake_function (STB_GLOBAL)
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
int default_wake_function(wait_queue_entry_t *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d4f80)
Location: kernel/sched/core.c:4341
Inline: False
Direct callers:
  - kernel/sched/wait.c:woken_wake_function
  - mm/shmem.c:synchronous_wake_function
  - fs/select.c:pollwake
  - block/blk-iocost.c:iocg_wake_fn
```
**Symbols:**

```
ffffffff810d4f80-ffffffff810d4f94: default_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int default_wake_function(wait_queue_entry_t *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810c35d0)
Location: kernel/sched/core.c:4341
Inline: False
Direct callers:
  - kernel/sched/wait.c:woken_wake_function
  - mm/shmem.c:synchronous_wake_function
  - fs/select.c:pollwake
  - block/blk-iocost.c:iocg_wake_fn
```
**Symbols:**

```
ffffffff810c35d0-ffffffff810c35e4: default_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int default_wake_function(wait_queue_entry_t *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810d1dc0)
Location: kernel/sched/core.c:4341
Inline: False
Direct callers:
  - kernel/sched/wait.c:woken_wake_function
  - mm/shmem.c:synchronous_wake_function
  - fs/select.c:pollwake
  - block/blk-iocost.c:iocg_wake_fn
```
**Symbols:**

```
ffffffff810d1dc0-ffffffff810d1dd4: default_wake_function (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int default_wake_function(wait_queue_entry_t *curr, unsigned int mode, int wake_flags, void *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/core.c (ffffffff810dc7e0)
Location: kernel/sched/core.c:4341
Inline: False
Direct callers:
  - kernel/sched/wait.c:woken_wake_function
  - mm/shmem.c:synchronous_wake_function
  - fs/select.c:pollwake
  - block/blk-iocost.c:iocg_wake_fn
```
**Symbols:**

```
ffffffff810dc7e0-ffffffff810dc7f4: default_wake_function (STB_GLOBAL)
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
<b>Param type changed. </b>
<code>wait_queue_t *curr</code> ➡️ <code>wait_queue_entry_t *curr</code>
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
