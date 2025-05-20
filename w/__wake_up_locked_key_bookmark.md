# Function: <code>__wake_up_locked_key_bookmark</code>

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
void __wake_up_locked_key_bookmark(struct wait_queue_head *wq_head, unsigned int mode, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d0e70)
Location: kernel/sched/wait.c:168
Inline: False
Direct callers:
  - mm/filemap.c:wake_up_page_bit
```
**Symbols:**

```
ffffffff810d0e70-ffffffff810d0e8d: __wake_up_locked_key_bookmark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __wake_up_locked_key_bookmark(struct wait_queue_head *wq_head, unsigned int mode, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810d93c0)
Location: kernel/sched/wait.c:162
Inline: False
Direct callers:
  - mm/filemap.c:wake_up_page_bit
```
**Symbols:**

```
ffffffff810d93c0-ffffffff810d93dd: __wake_up_locked_key_bookmark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __wake_up_locked_key_bookmark(struct wait_queue_head *wq_head, unsigned int mode, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e2ec0)
Location: kernel/sched/wait.c:164
Inline: False
Direct callers:
  - mm/filemap.c:wake_up_page_bit
```
**Symbols:**

```
ffffffff810e2ec0-ffffffff810e2edd: __wake_up_locked_key_bookmark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __wake_up_locked_key_bookmark(struct wait_queue_head *wq_head, unsigned int mode, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810e9ac0)
Location: kernel/sched/wait.c:161
Inline: False
Direct callers:
  - mm/filemap.c:wake_up_page_bit
```
**Symbols:**

```
ffffffff810e9ac0-ffffffff810e9add: __wake_up_locked_key_bookmark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __wake_up_locked_key_bookmark(struct wait_queue_head *wq_head, unsigned int mode, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f5490)
Location: kernel/sched/wait.c:161
Inline: False
Direct callers:
  - mm/filemap.c:wake_up_page_bit
```
**Symbols:**

```
ffffffff810f5490-ffffffff810f54ad: __wake_up_locked_key_bookmark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __wake_up_locked_key_bookmark(struct wait_queue_head *wq_head, unsigned int mode, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810febb0)
Location: kernel/sched/wait.c:161
Inline: False
Direct callers:
  - mm/filemap.c:wake_up_page_bit
```
**Symbols:**

```
ffffffff810febb0-ffffffff810febcd: __wake_up_locked_key_bookmark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __wake_up_locked_key_bookmark(struct wait_queue_head *wq_head, unsigned int mode, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810fd530)
Location: kernel/sched/wait.c:176
Inline: False
Direct callers:
  - mm/filemap.c:wake_up_page_bit
```
**Symbols:**

```
ffffffff810fd530-ffffffff810fd54d: __wake_up_locked_key_bookmark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __wake_up_locked_key_bookmark(struct wait_queue_head *wq_head, unsigned int mode, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ff8f0)
Location: kernel/sched/wait.c:176
Inline: False
Direct callers:
  - mm/filemap.c:wake_up_page_bit
```
**Symbols:**

```
ffffffff810ff8f0-ffffffff810ff90d: __wake_up_locked_key_bookmark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __wake_up_locked_key_bookmark(struct wait_queue_head *wq_head, unsigned int mode, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff8111b9e0)
Location: kernel/sched/wait.c:176
Inline: False
Direct callers:
  - mm/filemap.c:wake_up_page_bit
```
**Symbols:**

```
ffffffff8111b9e0-ffffffff8111b9fd: __wake_up_locked_key_bookmark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __wake_up_locked_key_bookmark(struct wait_queue_head *wq_head, unsigned int mode, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8113bd40)
Location: kernel/sched/wait.c:175
Inline: False
Direct callers:
  - mm/filemap.c:folio_wake_bit
```
**Symbols:**

```
ffffffff8113bd40-ffffffff8113bd71: __wake_up_locked_key_bookmark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __wake_up_locked_key_bookmark(struct wait_queue_head *wq_head, unsigned int mode, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81166820)
Location: kernel/sched/wait.c:179
Inline: False
Direct callers:
  - mm/filemap.c:folio_wake_bit
```
**Symbols:**

```
ffffffff81166820-ffffffff81166851: __wake_up_locked_key_bookmark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __wake_up_locked_key_bookmark(struct wait_queue_head *wq_head, unsigned int mode, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81176c90)
Location: kernel/sched/wait.c:179
Inline: False
Direct callers:
  - mm/filemap.c:folio_wake_bit
```
**Symbols:**

```
ffffffff81176c90-ffffffff81176cc1: __wake_up_locked_key_bookmark (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __wake_up_locked_key_bookmark(struct wait_queue_head *wq_head, unsigned int mode, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffff800010158040)
Location: kernel/sched/wait.c:161
Inline: False
Direct callers:
  - mm/filemap.c:wake_up_page_bit
  - mm/filemap.c:wake_up_page_bit
```
**Symbols:**

```
ffff800010158040-ffff800010158094: __wake_up_locked_key_bookmark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __wake_up_locked_key_bookmark(struct wait_queue_head *wq_head, unsigned int mode, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c03a5b30)
Location: kernel/sched/wait.c:161
Inline: False
Direct callers:
  - mm/filemap.c:wake_up_page_bit
```
**Symbols:**

```
c03a5b30-c03a5b68: __wake_up_locked_key_bookmark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __wake_up_locked_key_bookmark(struct wait_queue_head *wq_head, unsigned int mode, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (c0000000001acb70)
Location: kernel/sched/wait.c:161
Inline: False
Direct callers:
  - mm/filemap.c:wake_up_page_bit
```
**Symbols:**

```
c0000000001acb70-c0000000001acb94: __wake_up_locked_key_bookmark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __wake_up_locked_key_bookmark(struct wait_queue_head *wq_head, unsigned int mode, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffe0000fea70)
Location: kernel/sched/wait.c:161
Inline: False
Direct callers:
  - mm/filemap.c:wake_up_page_bit
```
**Symbols:**

```
ffffffe0000fea70-ffffffe0000feab6: __wake_up_locked_key_bookmark (STB_GLOBAL)
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
void __wake_up_locked_key_bookmark(struct wait_queue_head *wq_head, unsigned int mode, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810ee890)
Location: kernel/sched/wait.c:161
Inline: False
Direct callers:
  - mm/filemap.c:wake_up_page_bit
```
**Symbols:**

```
ffffffff810ee890-ffffffff810ee8ad: __wake_up_locked_key_bookmark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __wake_up_locked_key_bookmark(struct wait_queue_head *wq_head, unsigned int mode, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810de920)
Location: kernel/sched/wait.c:161
Inline: False
Direct callers:
  - mm/filemap.c:wake_up_page_bit
```
**Symbols:**

```
ffffffff810de920-ffffffff810de93d: __wake_up_locked_key_bookmark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __wake_up_locked_key_bookmark(struct wait_queue_head *wq_head, unsigned int mode, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810eb9c0)
Location: kernel/sched/wait.c:161
Inline: False
Direct callers:
  - mm/filemap.c:wake_up_page_bit
```
**Symbols:**

```
ffffffff810eb9c0-ffffffff810eb9dd: __wake_up_locked_key_bookmark (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __wake_up_locked_key_bookmark(struct wait_queue_head *wq_head, unsigned int mode, void *key, wait_queue_entry_t *bookmark);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/wait.c (ffffffff810f6a20)
Location: kernel/sched/wait.c:161
Inline: False
Direct callers:
  - mm/filemap.c:wake_up_page_bit
```
**Symbols:**

```
ffffffff810f6a20-ffffffff810f6a3d: __wake_up_locked_key_bookmark (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
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
