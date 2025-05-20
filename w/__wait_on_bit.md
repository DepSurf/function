# Function: <code>__wait_on_bit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __wait_on_bit(wait_queue_head_t *wq, struct wait_bit_queue *q, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff81820740)
Location: kernel/sched/wait.c:387
Inline: False
Direct callers:
  - kernel/sched/wait.c:out_of_line_wait_on_bit
  - kernel/sched/wait.c:out_of_line_wait_on_bit_timeout
  - mm/filemap.c:wait_on_page_bit
  - mm/filemap.c:wait_on_page_bit_killable_timeout
  - mm/filemap.c:wait_on_page_bit_killable
  - fs/fs-writeback.c:__inode_wait_for_writeback
```
**Symbols:**

```
ffffffff81820740-ffffffff818207c6: __wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __wait_on_bit(wait_queue_head_t *wq, struct wait_bit_queue *q, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff8189aba0)
Location: kernel/sched/wait.c:387
Inline: False
Direct callers:
  - kernel/sched/wait.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait.c:out_of_line_wait_on_bit
  - mm/filemap.c:wait_on_page_bit_killable_timeout
  - mm/filemap.c:wait_on_page_bit_killable
  - mm/filemap.c:wait_on_page_bit
  - fs/fs-writeback.c:__inode_wait_for_writeback
```
**Symbols:**

```
ffffffff8189aba0-ffffffff8189ac21: __wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __wait_on_bit(wait_queue_head_t *wq, struct wait_bit_queue *q, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff818cf1b0)
Location: kernel/sched/wait.c:375
Inline: False
Direct callers:
  - kernel/sched/wait.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait.c:out_of_line_wait_on_bit
  - fs/fs-writeback.c:__inode_wait_for_writeback
```
**Symbols:**

```
ffffffff818cf1b0-ffffffff818cf231: __wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __wait_on_bit(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff819067a0)
Location: kernel/sched/wait_bit.c:43
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
  - fs/fs-writeback.c:__inode_wait_for_writeback
```
**Symbols:**

```
ffffffff819067a0-ffffffff81906821: __wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __wait_on_bit(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81990810)
Location: kernel/sched/wait_bit.c:43
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
  - fs/fs-writeback.c:__inode_wait_for_writeback
```
**Symbols:**

```
ffffffff81990810-ffffffff81990897: __wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __wait_on_bit(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff819ecfd0)
Location: kernel/sched/wait_bit.c:40
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
  - fs/fs-writeback.c:__inode_wait_for_writeback
```
**Symbols:**

```
ffffffff819ecfd0-ffffffff819ed057: __wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __wait_on_bit(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81a28200)
Location: kernel/sched/wait_bit.c:40
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
  - fs/fs-writeback.c:__inode_wait_for_writeback
```
**Symbols:**

```
ffffffff81a28200-ffffffff81a28287: __wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __wait_on_bit(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81a989e0)
Location: kernel/sched/wait_bit.c:41
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
  - fs/fs-writeback.c:__inode_wait_for_writeback
```
**Symbols:**

```
ffffffff81a989e0-ffffffff81a98a72: __wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __wait_on_bit(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81ad0330)
Location: kernel/sched/wait_bit.c:41
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
  - fs/fs-writeback.c:__inode_wait_for_writeback
```
**Symbols:**

```
ffffffff81ad0330-ffffffff81ad03c2: __wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __wait_on_bit(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81bc8cb0)
Location: kernel/sched/wait_bit.c:41
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
  - fs/fs-writeback.c:__inode_wait_for_writeback
```
**Symbols:**

```
ffffffff81bc8cb0-ffffffff81bc8d42: __wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __wait_on_bit(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81c41aa0)
Location: kernel/sched/wait_bit.c:41
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
  - fs/fs-writeback.c:__inode_wait_for_writeback
```
**Symbols:**

```
ffffffff81c41aa0-ffffffff81c41b32: __wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __wait_on_bit(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81c33a10)
Location: kernel/sched/wait_bit.c:41
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
  - fs/fs-writeback.c:__inode_wait_for_writeback
```
**Symbols:**

```
ffffffff81c33a10-ffffffff81c33aa2: __wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __wait_on_bit(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81d523d0)
Location: kernel/sched/wait_bit.c:41
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
  - fs/fs-writeback.c:__inode_wait_for_writeback
```
**Symbols:**

```
ffffffff81d523d0-ffffffff81d52462: __wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __wait_on_bit(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81f22bf0)
Location: kernel/sched/wait_bit.c:41
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit
  - fs/fs-writeback.c:__inode_wait_for_writeback
```
**Symbols:**

```
ffffffff81f22bf0-ffffffff81f22d07: __wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __wait_on_bit(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff820cd560)
Location: kernel/sched/wait_bit.c:41
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit
  - fs/fs-writeback.c:__inode_wait_for_writeback
```
**Symbols:**

```
ffffffff820cd560-ffffffff820cd672: __wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __wait_on_bit(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff821519e0)
Location: kernel/sched/wait_bit.c:41
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit
  - fs/fs-writeback.c:__inode_wait_for_writeback
```
**Symbols:**

```
ffffffff821519e0-ffffffff82151aef: __wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __wait_on_bit(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff82234820)
Location: kernel/sched/wait_bit.c:41
Inline: False
Direct callers:
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/build_utility.c:out_of_line_wait_on_bit
  - fs/fs-writeback.c:__inode_wait_for_writeback
```
**Symbols:**

```
ffffffff82234820-ffffffff8223492f: __wait_on_bit (STB_GLOBAL)
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
int __wait_on_bit(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffff800010da2110)
Location: kernel/sched/wait_bit.c:41
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
  - fs/fs-writeback.c:__inode_wait_for_writeback
```
**Symbols:**

```
ffff800010da2110-ffff800010da21f8: __wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __wait_on_bit(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (c0e9a234)
Location: kernel/sched/wait_bit.c:41
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
  - fs/fs-writeback.c:__inode_wait_for_writeback
```
**Symbols:**

```
c0e9a234-c0e9a300: __wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __wait_on_bit(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (c000000000ee3550)
Location: kernel/sched/wait_bit.c:41
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
  - fs/fs-writeback.c:__inode_wait_for_writeback
```
**Symbols:**

```
c000000000ee3550-c000000000ee36bc: __wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __wait_on_bit(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffe0008c57cc)
Location: kernel/sched/wait_bit.c:41
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
  - fs/fs-writeback.c:__inode_wait_for_writeback
```
**Symbols:**

```
ffffffe0008c57cc-ffffffe0008c5890: __wait_on_bit (STB_GLOBAL)
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
int __wait_on_bit(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81a6f1a0)
Location: kernel/sched/wait_bit.c:41
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
  - fs/fs-writeback.c:__inode_wait_for_writeback
```
**Symbols:**

```
ffffffff81a6f1a0-ffffffff81a6f232: __wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __wait_on_bit(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81a2b5d0)
Location: kernel/sched/wait_bit.c:41
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
  - fs/fs-writeback.c:__inode_wait_for_writeback
```
**Symbols:**

```
ffffffff81a2b5d0-ffffffff81a2b662: __wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __wait_on_bit(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81adb5b0)
Location: kernel/sched/wait_bit.c:41
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
  - fs/fs-writeback.c:__inode_wait_for_writeback
```
**Symbols:**

```
ffffffff81adb5b0-ffffffff81adb642: __wait_on_bit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __wait_on_bit(struct wait_queue_head *wq_head, struct wait_bit_queue_entry *wbq_entry, wait_bit_action_f *action, unsigned int mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait_bit.c (ffffffff81ae7b50)
Location: kernel/sched/wait_bit.c:41
Inline: False
Direct callers:
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit_timeout
  - kernel/sched/wait_bit.c:out_of_line_wait_on_bit
  - fs/fs-writeback.c:__inode_wait_for_writeback
```
**Symbols:**

```
ffffffff81ae7b50-ffffffff81ae7be2: __wait_on_bit (STB_GLOBAL)
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
