# Function: <code>jbd2_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void jbd2_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff812f2ad0)
Location: fs/jbd2/journal.c:2322
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
```
**Symbols:**

```
ffffffff812f2ad0-ffffffff812f2b30: jbd2_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void jbd2_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813204b0)
Location: fs/jbd2/journal.c:2349
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff813204b0-ffffffff813204f8: jbd2_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void jbd2_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81336360)
Location: fs/jbd2/journal.c:2319
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff81336360-ffffffff813363a8: jbd2_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void jbd2_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8134b090)
Location: fs/jbd2/journal.c:2342
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff8134b090-ffffffff8134b0d8: jbd2_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void jbd2_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8136f6e0)
Location: fs/jbd2/journal.c:2358
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff8136f6e0-ffffffff8136f728: jbd2_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void jbd2_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8139dc00)
Location: fs/jbd2/journal.c:2370
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff8139dc00-ffffffff8139dc48: jbd2_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void jbd2_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813b6970)
Location: fs/jbd2/journal.c:2370
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff813b6970-ffffffff813b69b8: jbd2_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void jbd2_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813e1040)
Location: fs/jbd2/journal.c:2361
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff813e1040-ffffffff813e108b: jbd2_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void jbd2_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813fb090)
Location: fs/jbd2/journal.c:2356
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff813fb090-ffffffff813fb0db: jbd2_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void jbd2_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814489ae)
Location: fs/jbd2/journal.c:2385
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
```
**Symbols:**

```
ffffffff81448c00-ffffffff81448c44: jbd2_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void jbd2_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81465400)
Location: fs/jbd2/journal.c:2632
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff81465400-ffffffff81465452: jbd2_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void jbd2_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8146ab90)
Location: fs/jbd2/journal.c:2632
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff8146ab90-ffffffff8146abe2: jbd2_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void jbd2_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814c13a0)
Location: fs/jbd2/journal.c:2811
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff814c13a0-ffffffff814c13f2: jbd2_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void jbd2_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8154bcd0)
Location: fs/jbd2/journal.c:2814
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff8154bcd0-ffffffff8154bd35: jbd2_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void jbd2_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815eba90)
Location: fs/jbd2/journal.c:2817
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff815eba90-ffffffff815ebaf5: jbd2_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void jbd2_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81623570)
Location: fs/jbd2/journal.c:2817
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff81623570-ffffffff816235d5: jbd2_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void jbd2_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8165c5d0)
Location: fs/jbd2/journal.c:2804
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff8165c5d0-ffffffff8165c635: jbd2_free (STB_GLOBAL)
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
void jbd2_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffff8000104d8618)
Location: fs/jbd2/journal.c:2356
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffff8000104d8618-ffff8000104d8688: jbd2_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void jbd2_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c069a524)
Location: fs/jbd2/journal.c:2356
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
c069a524-c069a570: jbd2_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void jbd2_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c000000000613400)
Location: fs/jbd2/journal.c:2356
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
c000000000613400-c00000000061348c: jbd2_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void jbd2_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffe00034e0fa)
Location: fs/jbd2/journal.c:2356
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffe00034e0fa-ffffffe00034e1b0: jbd2_free (STB_GLOBAL)
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
void jbd2_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f3670)
Location: fs/jbd2/journal.c:2356
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff813f3670-ffffffff813f36bb: jbd2_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void jbd2_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813e40f0)
Location: fs/jbd2/journal.c:2356
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff813e40f0-ffffffff813e413b: jbd2_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void jbd2_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f09f0)
Location: fs/jbd2/journal.c:2356
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff813f09f0-ffffffff813f0a3b: jbd2_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void jbd2_free(void *ptr, size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81406460)
Location: fs/jbd2/journal.c:2356
Inline: True
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_get_undo_access
  - fs/jbd2/transaction.c:do_get_write_access
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_put_journal_head
  - fs/jbd2/journal.c:jbd2_journal_write_metadata_buffer
```
**Symbols:**

```
ffffffff81406460-ffffffff814064ab: jbd2_free (STB_GLOBAL)
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
