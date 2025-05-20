# Function: <code>__wake_up_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __wake_up_common(wait_queue_head_t *q, unsigned int mode, int nr_exclusive, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c3300)
Location: kernel/sched/wait.c:65
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up
  - kernel/sched/wait.c:__wake_up_locked
  - kernel/sched/wait.c:abort_exclusive_wait
  - kernel/sched/wait.c:__wake_up_sync_key
```
**Symbols:**

```
ffffffff810c3300-ffffffff810c3384: __wake_up_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __wake_up_common(wait_queue_head_t *q, unsigned int mode, int nr_exclusive, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c6c90)
Location: kernel/sched/wait.c:65
Inline: False
Direct callers:
  - kernel/sched/wait.c:abort_exclusive_wait
  - kernel/sched/wait.c:__wake_up_sync_key
  - kernel/sched/wait.c:__wake_up_locked
  - kernel/sched/wait.c:__wake_up
```
**Symbols:**

```
ffffffff810c6c90-ffffffff810c6d0f: __wake_up_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __wake_up_common(wait_queue_head_t *q, unsigned int mode, int nr_exclusive, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ccc70)
Location: kernel/sched/wait.c:65
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_sync_key
  - kernel/sched/wait.c:__wake_up_locked_key
  - kernel/sched/wait.c:__wake_up_locked
  - kernel/sched/wait.c:__wake_up
```
**Symbols:**

```
ffffffff810ccc70-ffffffff810cccef: __wake_up_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __wake_up_common(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810c9530)
Location: kernel/sched/wait.c:66
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_sync_key
  - kernel/sched/wait.c:__wake_up_locked_key
  - kernel/sched/wait.c:__wake_up_locked
  - kernel/sched/wait.c:__wake_up
```
**Symbols:**

```
ffffffff810c9530-ffffffff810c95b5: __wake_up_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __wake_up_common(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d0c20)
Location: kernel/sched/wait.c:72
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_locked_key_bookmark
  - kernel/sched/wait.c:__wake_up_locked_key
  - kernel/sched/wait.c:__wake_up_locked
  - kernel/sched/wait.c:__wake_up_common_lock
```
**Symbols:**

```
ffffffff810d0c20-ffffffff810d0d41: __wake_up_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __wake_up_common(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d9160)
Location: kernel/sched/wait.c:65
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_locked_key_bookmark
  - kernel/sched/wait.c:__wake_up_locked_key
  - kernel/sched/wait.c:__wake_up_locked
  - kernel/sched/wait.c:__wake_up_common_lock
```
**Symbols:**

```
ffffffff810d9160-ffffffff810d9296: __wake_up_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __wake_up_common(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e2c60)
Location: kernel/sched/wait.c:65
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_locked_key_bookmark
  - kernel/sched/wait.c:__wake_up_locked_key
  - kernel/sched/wait.c:__wake_up_locked
  - kernel/sched/wait.c:__wake_up_common_lock
```
**Symbols:**

```
ffffffff810e2c60-ffffffff810e2d96: __wake_up_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __wake_up_common(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e9860)
Location: kernel/sched/wait.c:66
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_locked_key_bookmark
  - kernel/sched/wait.c:__wake_up_locked_key
  - kernel/sched/wait.c:__wake_up_locked
  - kernel/sched/wait.c:__wake_up_common_lock
```
**Symbols:**

```
ffffffff810e9860-ffffffff810e9997: __wake_up_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __wake_up_common(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f5230)
Location: kernel/sched/wait.c:66
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_locked_key_bookmark
  - kernel/sched/wait.c:__wake_up_locked_key
  - kernel/sched/wait.c:__wake_up_locked
  - kernel/sched/wait.c:__wake_up_common_lock
```
**Symbols:**

```
ffffffff810f5230-ffffffff810f5367: __wake_up_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __wake_up_common(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fe950)
Location: kernel/sched/wait.c:66
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_locked_sync_key
  - kernel/sched/wait.c:__wake_up_locked_key_bookmark
  - kernel/sched/wait.c:__wake_up_locked_key
  - kernel/sched/wait.c:__wake_up_locked
  - kernel/sched/wait.c:__wake_up_common_lock
```
**Symbols:**

```
ffffffff810fe950-ffffffff810fea87: __wake_up_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __wake_up_common(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fd2d0)
Location: kernel/sched/wait.c:81
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_locked_sync_key
  - kernel/sched/wait.c:__wake_up_locked_key_bookmark
  - kernel/sched/wait.c:__wake_up_locked_key
  - kernel/sched/wait.c:__wake_up_locked
  - kernel/sched/wait.c:__wake_up_common_lock
```
**Symbols:**

```
ffffffff810fd2d0-ffffffff810fd407: __wake_up_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __wake_up_common(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ff690)
Location: kernel/sched/wait.c:81
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_locked_sync_key
  - kernel/sched/wait.c:__wake_up_locked_key_bookmark
  - kernel/sched/wait.c:__wake_up_locked_key
  - kernel/sched/wait.c:__wake_up_locked
  - kernel/sched/wait.c:__wake_up_common_lock
```
**Symbols:**

```
ffffffff810ff690-ffffffff810ff7c6: __wake_up_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __wake_up_common(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff8111b780)
Location: kernel/sched/wait.c:81
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_locked_sync_key
  - kernel/sched/wait.c:__wake_up_locked_key_bookmark
  - kernel/sched/wait.c:__wake_up_locked_key
  - kernel/sched/wait.c:__wake_up_locked
  - kernel/sched/wait.c:__wake_up_common_lock
```
**Symbols:**

```
ffffffff8111b780-ffffffff8111b8b6: __wake_up_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __wake_up_common(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113ba00)
Location: kernel/sched/wait.c:80
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:__wake_up_locked_sync_key
  - kernel/sched/build_utility.c:__wake_up_locked_key_bookmark
  - kernel/sched/build_utility.c:__wake_up_locked_key
  - kernel/sched/build_utility.c:__wake_up_locked
  - kernel/sched/build_utility.c:__wake_up_common_lock
```
**Symbols:**

```
ffffffff8113ba00-ffffffff8113bb42: __wake_up_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __wake_up_common(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81166480)
Location: kernel/sched/wait.c:80
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:__wake_up_locked_sync_key
  - kernel/sched/build_utility.c:__wake_up_locked_key_bookmark
  - kernel/sched/build_utility.c:__wake_up_locked_key
  - kernel/sched/build_utility.c:__wake_up_locked
  - kernel/sched/build_utility.c:__wake_up_common_lock
```
**Symbols:**

```
ffffffff81166480-ffffffff811665c2: __wake_up_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __wake_up_common(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811768f0)
Location: kernel/sched/wait.c:80
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:__wake_up_locked_sync_key
  - kernel/sched/build_utility.c:__wake_up_locked_key_bookmark
  - kernel/sched/build_utility.c:__wake_up_locked_key
  - kernel/sched/build_utility.c:__wake_up_locked
  - kernel/sched/build_utility.c:__wake_up_common_lock
```
**Symbols:**

```
ffffffff811768f0-ffffffff81176a32: __wake_up_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __wake_up_common(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81184b70)
Location: kernel/sched/wait.c:73
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:psi_trigger_destroy
  - kernel/sched/build_utility.c:poll_timer_fn
  - kernel/sched/build_utility.c:update_triggers
  - kernel/sched/build_utility.c:__wake_up_pollfree
  - kernel/sched/build_utility.c:__wake_up_sync
  - kernel/sched/build_utility.c:__wake_up_locked_sync_key
  - kernel/sched/build_utility.c:__wake_up_locked_key
  - kernel/sched/build_utility.c:__wake_up_locked
  - kernel/sched/build_utility.c:__wake_up_on_current_cpu
  - kernel/sched/build_utility.c:wake_up_var
  - kernel/sched/build_utility.c:wake_up_bit
```
**Symbols:**

```
ffffffff81184b70-ffffffff81184c12: __wake_up_common (STB_LOCAL)
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
int __wake_up_common(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffff800010157e50)
Location: kernel/sched/wait.c:66
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_locked_key_bookmark
  - kernel/sched/wait.c:__wake_up_locked_key
  - kernel/sched/wait.c:__wake_up_locked
  - kernel/sched/wait.c:__wake_up_common_lock
```
**Symbols:**

```
ffff800010157e50-ffff800010157fa0: __wake_up_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __wake_up_common(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c03a5868)
Location: kernel/sched/wait.c:66
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_locked_key_bookmark
  - kernel/sched/wait.c:__wake_up_locked_key
  - kernel/sched/wait.c:__wake_up_locked
  - kernel/sched/wait.c:__wake_up_common_lock
```
**Symbols:**

```
c03a5868-c03a59d8: __wake_up_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __wake_up_common(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c0000000001ac7c0)
Location: kernel/sched/wait.c:66
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_locked_key_bookmark
  - kernel/sched/wait.c:__wake_up_locked_key
  - kernel/sched/wait.c:__wake_up_locked
  - kernel/sched/wait.c:__wake_up_common_lock
```
**Symbols:**

```
c0000000001ac7c0-c0000000001ac9f0: __wake_up_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __wake_up_common(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffe0000fe816)
Location: kernel/sched/wait.c:66
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_locked_key_bookmark
  - kernel/sched/wait.c:__wake_up_locked_key
  - kernel/sched/wait.c:__wake_up_locked
  - kernel/sched/wait.c:__wake_up_common_lock
```
**Symbols:**

```
ffffffe0000fe816-ffffffe0000fe920: __wake_up_common (STB_LOCAL)
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
int __wake_up_common(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ee630)
Location: kernel/sched/wait.c:66
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_locked_key_bookmark
  - kernel/sched/wait.c:__wake_up_locked_key
  - kernel/sched/wait.c:__wake_up_locked
  - kernel/sched/wait.c:__wake_up_common_lock
```
**Symbols:**

```
ffffffff810ee630-ffffffff810ee767: __wake_up_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __wake_up_common(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810de6c0)
Location: kernel/sched/wait.c:66
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_locked_key_bookmark
  - kernel/sched/wait.c:__wake_up_locked_key
  - kernel/sched/wait.c:__wake_up_locked
  - kernel/sched/wait.c:__wake_up_common_lock
```
**Symbols:**

```
ffffffff810de6c0-ffffffff810de7f7: __wake_up_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __wake_up_common(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810eb760)
Location: kernel/sched/wait.c:66
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_locked_key_bookmark
  - kernel/sched/wait.c:__wake_up_locked_key
  - kernel/sched/wait.c:__wake_up_locked
  - kernel/sched/wait.c:__wake_up_common_lock
```
**Symbols:**

```
ffffffff810eb760-ffffffff810eb897: __wake_up_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __wake_up_common(struct wait_queue_head *wq_head, unsigned int mode, int nr_exclusive, int wake_flags, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f67c0)
Location: kernel/sched/wait.c:66
Inline: False
Direct callers:
  - kernel/sched/wait.c:__wake_up_locked_key_bookmark
  - kernel/sched/wait.c:__wake_up_locked_key
  - kernel/sched/wait.c:__wake_up_locked
  - kernel/sched/wait.c:__wake_up_common_lock
```
**Symbols:**

```
ffffffff810f67c0-ffffffff810f68f7: __wake_up_common (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>wait_queue_entry_t *bookmark</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>wait_queue_entry_t *bookmark</code>
</li>
</ul>
</details>
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
