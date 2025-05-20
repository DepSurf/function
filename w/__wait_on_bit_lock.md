# Function: <code>__wait_on_bit_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __wait_on_bit_lock(wait_queue_head_t *wq, struct wait_bit_queue *q, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff81820940)
Location: kernel/sched/wait.c:425
Inline: False
Direct callers:
  - kernel/sched/wait.c:out_of_line_wait_on_bit_lock
  - mm/filemap.c:__lock_page
  - mm/filemap.c:__lock_page_killable
```
**Symbols:**

```
ffffffff81820940-ffffffff818209e2: __wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __wait_on_bit_lock(wait_queue_head_t *wq, struct wait_bit_queue *q, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff8189ada0)
Location: kernel/sched/wait.c:425
Inline: False
Direct callers:
  - kernel/sched/wait.c:out_of_line_wait_on_bit_lock
  - mm/filemap.c:__lock_page_killable
  - mm/filemap.c:__lock_page
```
**Symbols:**

```
ffffffff8189ada0-ffffffff8189ae3e: __wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __wait_on_bit_lock(wait_queue_head_t *wq, struct wait_bit_queue *q, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff818cf240)
Location: kernel/sched/wait.c:413
Inline: False
Direct callers:
  - kernel/sched/wait.c:out_of_line_wait_on_bit_lock
```
**Symbols:**

```
ffffffff818cf240-ffffffff818cf2f5: __wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __wait_on_bit_lock(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff819069a0)
Location: kernel/sched/wait_bit.c:81
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
```
**Symbols:**

```
ffffffff819069a0-ffffffff81906a52: __wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __wait_on_bit_lock(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81990a10)
Location: kernel/sched/wait_bit.c:81
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
```
**Symbols:**

```
ffffffff81990a10-ffffffff81990ac4: __wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __wait_on_bit_lock(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff819ed1d0)
Location: kernel/sched/wait_bit.c:81
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
```
**Symbols:**

```
ffffffff819ed1d0-ffffffff819ed285: __wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __wait_on_bit_lock(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81a28400)
Location: kernel/sched/wait_bit.c:81
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
```
**Symbols:**

```
ffffffff81a28400-ffffffff81a284b5: __wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __wait_on_bit_lock(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81a98bf0)
Location: kernel/sched/wait_bit.c:82
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
```
**Symbols:**

```
ffffffff81a98bf0-ffffffff81a98ca1: __wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __wait_on_bit_lock(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81ad0540)
Location: kernel/sched/wait_bit.c:82
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
```
**Symbols:**

```
ffffffff81ad0540-ffffffff81ad05f1: __wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __wait_on_bit_lock(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81bc8ec0)
Location: kernel/sched/wait_bit.c:82
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
```
**Symbols:**

```
ffffffff81bc8ec0-ffffffff81bc8f71: __wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __wait_on_bit_lock(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81c41cb0)
Location: kernel/sched/wait_bit.c:82
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
```
**Symbols:**

```
ffffffff81c41cb0-ffffffff81c41d61: __wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __wait_on_bit_lock(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81c33c20)
Location: kernel/sched/wait_bit.c:82
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
```
**Symbols:**

```
ffffffff81c33c20-ffffffff81c33cd1: __wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __wait_on_bit_lock(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81d525e0)
Location: kernel/sched/wait_bit.c:82
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
```
**Symbols:**

```
ffffffff81d525e0-ffffffff81d52691: __wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __wait_on_bit_lock(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81f22a40)
Location: kernel/sched/wait_bit.c:82
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit_lock
```
**Symbols:**

```
ffffffff81f22a40-ffffffff81f22b3c: __wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __wait_on_bit_lock(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff820cd390)
Location: kernel/sched/wait_bit.c:82
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit_lock
```
**Symbols:**

```
ffffffff820cd390-ffffffff820cd48c: __wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __wait_on_bit_lock(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff82151810)
Location: kernel/sched/wait_bit.c:82
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit_lock
```
**Symbols:**

```
ffffffff82151810-ffffffff8215190c: __wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __wait_on_bit_lock(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff82234650)
Location: kernel/sched/wait_bit.c:82
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit_lock
```
**Symbols:**

```
ffffffff82234650-ffffffff8223474c: __wait_on_bit_lock (STB_GLOBAL)
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
int __wait_on_bit_lock(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffff800010da23a8)
Location: kernel/sched/wait_bit.c:82
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
```
**Symbols:**

```
ffff800010da23a8-ffff800010da24ec: __wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __wait_on_bit_lock(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (c0e9a48c)
Location: kernel/sched/wait_bit.c:82
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
```
**Symbols:**

```
c0e9a48c-c0e9a580: __wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __wait_on_bit_lock(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (c000000000ee3880)
Location: kernel/sched/wait_bit.c:82
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
```
**Symbols:**

```
c000000000ee3880-c000000000ee3a2c: __wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __wait_on_bit_lock(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffe0008c59d2)
Location: kernel/sched/wait_bit.c:82
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
```
**Symbols:**

```
ffffffe0008c59d2-ffffffe0008c5aac: __wait_on_bit_lock (STB_GLOBAL)
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
int __wait_on_bit_lock(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81a6f3b0)
Location: kernel/sched/wait_bit.c:82
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
```
**Symbols:**

```
ffffffff81a6f3b0-ffffffff81a6f461: __wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __wait_on_bit_lock(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81a2b7e0)
Location: kernel/sched/wait_bit.c:82
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
```
**Symbols:**

```
ffffffff81a2b7e0-ffffffff81a2b891: __wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __wait_on_bit_lock(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81adb7c0)
Location: kernel/sched/wait_bit.c:82
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
```
**Symbols:**

```
ffffffff81adb7c0-ffffffff81adb871: __wait_on_bit_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __wait_on_bit_lock(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81ae7d60)
Location: kernel/sched/wait_bit.c:82
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_lock
```
**Symbols:**

```
ffffffff81ae7d60-ffffffff81ae7e11: __wait_on_bit_lock (STB_GLOBAL)
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
<code>struct wait_bit_queue_entry *wbq_entry</code>
</li>
<li>
<b>Param removed. </b>
<code>wait_queue_head_t *wq</code>
</li>
<li>
<b>Param removed. </b>
<code>struct wait_bit_queue *q</code>
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
