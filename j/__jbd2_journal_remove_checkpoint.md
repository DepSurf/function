# Function: <code>__jbd2_journal_remove_checkpoint</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __jbd2_journal_remove_checkpoint(struct journal_head *jh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff812ecac0)
Location: fs/jbd2/checkpoint.c:551
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
```
**Symbols:**

```
ffffffff812ecac0-ffffffff812ecc25: __jbd2_journal_remove_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __jbd2_journal_remove_checkpoint(struct journal_head *jh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff8131a530)
Location: fs/jbd2/checkpoint.c:551
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
**Symbols:**

```
ffffffff8131a530-ffffffff8131a696: __jbd2_journal_remove_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __jbd2_journal_remove_checkpoint(struct journal_head *jh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff81330520)
Location: fs/jbd2/checkpoint.c:551
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
**Symbols:**

```
ffffffff81330520-ffffffff81330686: __jbd2_journal_remove_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __jbd2_journal_remove_checkpoint(struct journal_head *jh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff81345440)
Location: fs/jbd2/checkpoint.c:551
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
**Symbols:**

```
ffffffff81345440-ffffffff813455a8: __jbd2_journal_remove_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __jbd2_journal_remove_checkpoint(struct journal_head *jh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff81369af0)
Location: fs/jbd2/checkpoint.c:551
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
**Symbols:**

```
ffffffff81369af0-ffffffff81369c5a: __jbd2_journal_remove_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __jbd2_journal_remove_checkpoint(struct journal_head *jh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff81398270)
Location: fs/jbd2/checkpoint.c:548
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
**Symbols:**

```
ffffffff81398270-ffffffff813983d2: __jbd2_journal_remove_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __jbd2_journal_remove_checkpoint(struct journal_head *jh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff813b0fe0)
Location: fs/jbd2/checkpoint.c:548
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
**Symbols:**

```
ffffffff813b0fe0-ffffffff813b1142: __jbd2_journal_remove_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __jbd2_journal_remove_checkpoint(struct journal_head *jh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff813db640)
Location: fs/jbd2/checkpoint.c:560
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
**Symbols:**

```
ffffffff813db640-ffffffff813db7b7: __jbd2_journal_remove_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __jbd2_journal_remove_checkpoint(struct journal_head *jh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff813f5690)
Location: fs/jbd2/checkpoint.c:560
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
**Symbols:**

```
ffffffff813f5690-ffffffff813f5807: __jbd2_journal_remove_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __jbd2_journal_remove_checkpoint(struct journal_head *jh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff81442a30)
Location: fs/jbd2/checkpoint.c:560
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
**Symbols:**

```
ffffffff81442a30-ffffffff81442ba4: __jbd2_journal_remove_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __jbd2_journal_remove_checkpoint(struct journal_head *jh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff8145ec00)
Location: fs/jbd2/checkpoint.c:562
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
**Symbols:**

```
ffffffff8145ec00-ffffffff8145ed45: __jbd2_journal_remove_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __jbd2_journal_remove_checkpoint(struct journal_head *jh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff81464490)
Location: fs/jbd2/checkpoint.c:562
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
**Symbols:**

```
ffffffff81464490-ffffffff814645cf: __jbd2_journal_remove_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __jbd2_journal_remove_checkpoint(struct journal_head *jh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff814b9ad0)
Location: fs/jbd2/checkpoint.c:674
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
**Symbols:**

```
ffffffff814b9ad0-ffffffff814b9c3b: __jbd2_journal_remove_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __jbd2_journal_remove_checkpoint(struct journal_head *jh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff81543800)
Location: fs/jbd2/checkpoint.c:674
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
**Symbols:**

```
ffffffff81543800-ffffffff81543993: __jbd2_journal_remove_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __jbd2_journal_remove_checkpoint(struct journal_head *jh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff815e2760)
Location: fs/jbd2/checkpoint.c:674
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
**Symbols:**

```
ffffffff815e2760-ffffffff815e28f3: __jbd2_journal_remove_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __jbd2_journal_remove_checkpoint(struct journal_head *jh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff8161a0d0)
Location: fs/jbd2/checkpoint.c:558
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_journal_try_remove_checkpoint
  - fs/jbd2/checkpoint.c:journal_shrink_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
**Symbols:**

```
ffffffff8161a0d0-ffffffff8161a23c: __jbd2_journal_remove_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __jbd2_journal_remove_checkpoint(struct journal_head *jh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff81653020)
Location: fs/jbd2/checkpoint.c:554
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_journal_try_remove_checkpoint
  - fs/jbd2/checkpoint.c:journal_shrink_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
**Symbols:**

```
ffffffff81653020-ffffffff81653174: __jbd2_journal_remove_checkpoint (STB_GLOBAL)
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
int __jbd2_journal_remove_checkpoint(struct journal_head *jh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffff8000104d10e0)
Location: fs/jbd2/checkpoint.c:560
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
**Symbols:**

```
ffff8000104d10e0-ffff8000104d128c: __jbd2_journal_remove_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __jbd2_journal_remove_checkpoint(struct journal_head *jh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (c0693c50)
Location: fs/jbd2/checkpoint.c:560
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
**Symbols:**

```
c0693c50-c0693de4: __jbd2_journal_remove_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __jbd2_journal_remove_checkpoint(struct journal_head *jh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (c00000000060a410)
Location: fs/jbd2/checkpoint.c:560
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:journal_unmap_buffer
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
**Symbols:**

```
c00000000060a410-c00000000060a650: __jbd2_journal_remove_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __jbd2_journal_remove_checkpoint(struct journal_head *jh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffe000348546)
Location: fs/jbd2/checkpoint.c:560
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
**Symbols:**

```
ffffffe000348546-ffffffe0003486a6: __jbd2_journal_remove_checkpoint (STB_GLOBAL)
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
int __jbd2_journal_remove_checkpoint(struct journal_head *jh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff813edc70)
Location: fs/jbd2/checkpoint.c:560
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
**Symbols:**

```
ffffffff813edc70-ffffffff813edde7: __jbd2_journal_remove_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __jbd2_journal_remove_checkpoint(struct journal_head *jh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff813de6f0)
Location: fs/jbd2/checkpoint.c:560
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
**Symbols:**

```
ffffffff813de6f0-ffffffff813de867: __jbd2_journal_remove_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __jbd2_journal_remove_checkpoint(struct journal_head *jh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff813eaff0)
Location: fs/jbd2/checkpoint.c:560
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
**Symbols:**

```
ffffffff813eaff0-ffffffff813eb167: __jbd2_journal_remove_checkpoint (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __jbd2_journal_remove_checkpoint(struct journal_head *jh);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/checkpoint.c (ffffffff81400970)
Location: fs/jbd2/checkpoint.c:560
Inline: False
Direct callers:
  - fs/jbd2/transaction.c:jbd2_journal_invalidatepage
  - fs/jbd2/transaction.c:jbd2_journal_try_to_free_buffers
  - fs/jbd2/transaction.c:jbd2_journal_forget
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:journal_clean_one_cp_list
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
```
**Symbols:**

```
ffffffff81400970-ffffffff81400b00: __jbd2_journal_remove_checkpoint (STB_GLOBAL)
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
