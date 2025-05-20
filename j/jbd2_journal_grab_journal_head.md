# Function: <code>jbd2_journal_grab_journal_head</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_grab_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff812f3070)
Location: fs/jbd2/journal.c:2485
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_set_triggers
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
**Symbols:**

```
ffffffff812f3070-ffffffff812f30ab: jbd2_journal_grab_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_grab_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81320a40)
Location: fs/jbd2/journal.c:2502
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_set_triggers
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
**Symbols:**

```
ffffffff81320a40-ffffffff81320a7b: jbd2_journal_grab_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_grab_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813368f0)
Location: fs/jbd2/journal.c:2472
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_set_triggers
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
**Symbols:**

```
ffffffff813368f0-ffffffff8133692b: jbd2_journal_grab_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_grab_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8134b5a0)
Location: fs/jbd2/journal.c:2495
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_set_triggers
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
**Symbols:**

```
ffffffff8134b5a0-ffffffff8134b5db: jbd2_journal_grab_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_grab_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8136fbd0)
Location: fs/jbd2/journal.c:2511
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_set_triggers
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
**Symbols:**

```
ffffffff8136fbd0-ffffffff8136fc0b: jbd2_journal_grab_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_grab_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8139e0e0)
Location: fs/jbd2/journal.c:2521
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_set_triggers
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
**Symbols:**

```
ffffffff8139e0e0-ffffffff8139e11c: jbd2_journal_grab_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_grab_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813b6e50)
Location: fs/jbd2/journal.c:2521
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_set_triggers
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
**Symbols:**

```
ffffffff813b6e50-ffffffff813b6e8c: jbd2_journal_grab_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_grab_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813e1550)
Location: fs/jbd2/journal.c:2509
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_set_triggers
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
**Symbols:**

```
ffffffff813e1550-ffffffff813e158b: jbd2_journal_grab_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_grab_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813fb5a0)
Location: fs/jbd2/journal.c:2504
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_set_triggers
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
**Symbols:**

```
ffffffff813fb5a0-ffffffff813fb5db: jbd2_journal_grab_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_grab_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81448d70)
Location: fs/jbd2/journal.c:2535
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_set_triggers
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
**Symbols:**

```
ffffffff81448d70-ffffffff81448dab: jbd2_journal_grab_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_grab_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81465910)
Location: fs/jbd2/journal.c:2782
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_set_triggers
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
**Symbols:**

```
ffffffff81465910-ffffffff8146594b: jbd2_journal_grab_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_grab_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8146b0c0)
Location: fs/jbd2/journal.c:2782
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_set_triggers
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
**Symbols:**

```
ffffffff8146b0c0-ffffffff8146b0fb: jbd2_journal_grab_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_grab_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814bdfa0)
Location: fs/jbd2/journal.c:2961
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_set_triggers
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
**Symbols:**

```
ffffffff814bdfa0-ffffffff814bdfdb: jbd2_journal_grab_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_grab_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8154a000)
Location: fs/jbd2/journal.c:2964
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_set_triggers
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
**Symbols:**

```
ffffffff8154a000-ffffffff8154a072: jbd2_journal_grab_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_grab_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815e93d0)
Location: fs/jbd2/journal.c:2967
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_set_triggers
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
**Symbols:**

```
ffffffff815e93d0-ffffffff815e9442: jbd2_journal_grab_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_grab_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff816211e0)
Location: fs/jbd2/journal.c:2967
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_set_triggers
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
**Symbols:**

```
ffffffff816211e0-ffffffff81621252: jbd2_journal_grab_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_grab_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81659c50)
Location: fs/jbd2/journal.c:2954
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/transaction.c:jbd2_journal_set_triggers
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
**Symbols:**

```
ffffffff81659c50-ffffffff81659cc2: jbd2_journal_grab_journal_head (STB_GLOBAL)
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
struct journal_head *jbd2_journal_grab_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffff8000104d8cc8)
Location: fs/jbd2/journal.c:2504
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_set_triggers
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
**Symbols:**

```
ffff8000104d8cc8-ffff8000104d8d88: jbd2_journal_grab_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_grab_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c069ab98)
Location: fs/jbd2/journal.c:2504
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_set_triggers
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
**Symbols:**

```
c069ab98-c069ac90: jbd2_journal_grab_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_grab_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c000000000613c80)
Location: fs/jbd2/journal.c:2504
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_set_triggers
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
**Symbols:**

```
c000000000613c80-c000000000613d48: jbd2_journal_grab_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_grab_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffe00034e69a)
Location: fs/jbd2/journal.c:2504
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_set_triggers
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
**Symbols:**

```
ffffffe00034e69a-ffffffe00034e704: jbd2_journal_grab_journal_head (STB_GLOBAL)
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
struct journal_head *jbd2_journal_grab_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f3b80)
Location: fs/jbd2/journal.c:2504
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_set_triggers
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
**Symbols:**

```
ffffffff813f3b80-ffffffff813f3bbb: jbd2_journal_grab_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_grab_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813e4600)
Location: fs/jbd2/journal.c:2504
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_set_triggers
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
**Symbols:**

```
ffffffff813e4600-ffffffff813e463b: jbd2_journal_grab_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_grab_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f0f00)
Location: fs/jbd2/journal.c:2504
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_set_triggers
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
**Symbols:**

```
ffffffff813f0f00-ffffffff813f0f3b: jbd2_journal_grab_journal_head (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct journal_head *jbd2_journal_grab_journal_head(struct buffer_head *bh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81406a90)
Location: fs/jbd2/journal.c:2504
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:__jbd2_journal_file_buffer
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_set_triggers
  - fs/jbd2/checkpoint.c:__jbd2_journal_insert_checkpoint
```
**Symbols:**

```
ffffffff81406a90-ffffffff81406af2: jbd2_journal_grab_journal_head (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
