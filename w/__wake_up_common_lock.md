# Function: <code>__wake_up_common_lock</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __wake_up_common_lock(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d0d50)
Location: kernel/sched/wait.c:113
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_sync
  - kernel/sched/wait.c:__wake_up
```
**Symbols:**

```
ffffffff810d0d50-ffffffff810d0e07: __wake_up_common_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __wake_up_common_lock(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d92a0)
Location: kernel/sched/wait.c:107
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_sync
  - kernel/sched/wait.c:__wake_up
```
**Symbols:**

```
ffffffff810d92a0-ffffffff810d9357: __wake_up_common_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __wake_up_common_lock(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e2da0)
Location: kernel/sched/wait.c:109
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_sync
  - kernel/sched/wait.c:__wake_up
```
**Symbols:**

```
ffffffff810e2da0-ffffffff810e2e57: __wake_up_common_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __wake_up_common_lock(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e99a0)
Location: kernel/sched/wait.c:110
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_sync
  - kernel/sched/wait.c:__wake_up
```
**Symbols:**

```
ffffffff810e99a0-ffffffff810e9a53: __wake_up_common_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __wake_up_common_lock(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f5370)
Location: kernel/sched/wait.c:110
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_sync
  - kernel/sched/wait.c:__wake_up
```
**Symbols:**

```
ffffffff810f5370-ffffffff810f5423: __wake_up_common_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __wake_up_common_lock(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fea90)
Location: kernel/sched/wait.c:110
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_sync
  - kernel/sched/wait.c:__wake_up
```
**Symbols:**

```
ffffffff810fea90-ffffffff810feb43: __wake_up_common_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __wake_up_common_lock(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fd410)
Location: kernel/sched/wait.c:125
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_sync
  - kernel/sched/wait.c:__wake_up
```
**Symbols:**

```
ffffffff810fd410-ffffffff810fd4c3: __wake_up_common_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __wake_up_common_lock(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ff7d0)
Location: kernel/sched/wait.c:125
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_sync
  - kernel/sched/wait.c:__wake_up
```
**Symbols:**

```
ffffffff810ff7d0-ffffffff810ff883: __wake_up_common_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __wake_up_common_lock(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff8111b8c0)
Location: kernel/sched/wait.c:125
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_pollfree
  - kernel/sched/wait.c:__wake_up_sync
```
**Symbols:**

```
ffffffff8111b8c0-ffffffff8111b973: __wake_up_common_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __wake_up_common_lock(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113bb50)
Location: kernel/sched/wait.c:124
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:poll_timer_fn
  - kernel/sched/build_utility.c:update_triggers
  - kernel/sched/build_utility.c:__wake_up_pollfree
  - kernel/sched/build_utility.c:__wake_up_sync
  - kernel/sched/build_utility.c:wake_up_var
  - kernel/sched/build_utility.c:wake_up_bit
```
**Symbols:**

```
ffffffff8113bb50-ffffffff8113bc15: __wake_up_common_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __wake_up_common_lock(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811665e0)
Location: kernel/sched/wait.c:124
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:poll_timer_fn
  - kernel/sched/build_utility.c:update_triggers
  - kernel/sched/build_utility.c:__wake_up_sync
  - kernel/sched/build_utility.c:wake_up_var
  - kernel/sched/build_utility.c:wake_up_bit
```
**Symbols:**

```
ffffffff811665e0-ffffffff811666ab: __wake_up_common_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __wake_up_common_lock(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81176a50)
Location: kernel/sched/wait.c:124
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:poll_timer_fn
  - kernel/sched/build_utility.c:update_triggers
  - kernel/sched/build_utility.c:__wake_up_pollfree
  - kernel/sched/build_utility.c:__wake_up_sync
  - kernel/sched/build_utility.c:wake_up_var
  - kernel/sched/build_utility.c:wake_up_bit
```
**Symbols:**

```
ffffffff81176a50-ffffffff81176b1b: __wake_up_common_lock (STB_LOCAL)
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
In kernel/sched/build_utility.c (ffffffff8119b13b)
Location: kernel/sched/wait.c:99
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:poll_timer_fn
  - kernel/sched/build_utility.c:update_triggers
  - kernel/sched/build_utility.c:__wake_up_pollfree
  - kernel/sched/build_utility.c:__wake_up_sync
  - kernel/sched/build_utility.c:__wake_up_on_current_cpu
  - kernel/sched/build_utility.c:wake_up_var
  - kernel/sched/build_utility.c:wake_up_bit
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
void __wake_up_common_lock(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffff8000101585b0)
Location: kernel/sched/wait.c:110
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_sync
  - kernel/sched/wait.c:__wake_up
```
**Symbols:**

```
ffff8000101585b0-ffff8000101586dc: __wake_up_common_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __wake_up_common_lock(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c03a59d8)
Location: kernel/sched/wait.c:110
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_sync
  - kernel/sched/wait.c:__wake_up
```
**Symbols:**

```
c03a59d8-c03a5aa0: __wake_up_common_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __wake_up_common_lock(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c0000000001ac9f0)
Location: kernel/sched/wait.c:110
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_sync
  - kernel/sched/wait.c:__wake_up
```
**Symbols:**

```
c0000000001ac9f0-c0000000001acb00: __wake_up_common_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __wake_up_common_lock(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffe0000fe920)
Location: kernel/sched/wait.c:110
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_sync
  - kernel/sched/wait.c:__wake_up
```
**Symbols:**

```
ffffffe0000fe920-ffffffe0000fe9ac: __wake_up_common_lock (STB_LOCAL)
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
void __wake_up_common_lock(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ee770)
Location: kernel/sched/wait.c:110
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_sync
  - kernel/sched/wait.c:__wake_up
```
**Symbols:**

```
ffffffff810ee770-ffffffff810ee823: __wake_up_common_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __wake_up_common_lock(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810de800)
Location: kernel/sched/wait.c:110
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_sync
  - kernel/sched/wait.c:__wake_up
```
**Symbols:**

```
ffffffff810de800-ffffffff810de8b3: __wake_up_common_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __wake_up_common_lock(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810eb8a0)
Location: kernel/sched/wait.c:110
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_sync
  - kernel/sched/wait.c:__wake_up
```
**Symbols:**

```
ffffffff810eb8a0-ffffffff810eb953: __wake_up_common_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __wake_up_common_lock(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f6900)
Location: kernel/sched/wait.c:110
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_sync
  - kernel/sched/wait.c:__wake_up
```
**Symbols:**

```
ffffffff810f6900-ffffffff810f69b3: __wake_up_common_lock (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
