# Function: <code>jbd2_log_wait_commit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int jbd2_log_wait_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff812eea70)
Location: fs/jbd2/journal.c:689
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:jbd2_journal_flush
```
**Symbols:**

```
ffffffff812eea70-ffffffff812eeb99: jbd2_log_wait_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int jbd2_log_wait_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8131cfb0)
Location: fs/jbd2/journal.c:690
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff8131cfb0-ffffffff8131d0d7: jbd2_log_wait_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int jbd2_log_wait_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81332fe0)
Location: fs/jbd2/journal.c:690
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff81332fe0-ffffffff813330f6: jbd2_log_wait_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int jbd2_log_wait_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81347d80)
Location: fs/jbd2/journal.c:699
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff81347d80-ffffffff81347e9a: jbd2_log_wait_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int jbd2_log_wait_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8136c3c0)
Location: fs/jbd2/journal.c:698
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff8136c3c0-ffffffff8136c4da: jbd2_log_wait_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int jbd2_log_wait_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8139ac10)
Location: fs/jbd2/journal.c:695
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff8139ac10-ffffffff8139ad29: jbd2_log_wait_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int jbd2_log_wait_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813b3980)
Location: fs/jbd2/journal.c:695
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff813b3980-ffffffff813b3a99: jbd2_log_wait_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int jbd2_log_wait_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813ddf90)
Location: fs/jbd2/journal.c:678
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff813ddf90-ffffffff813de0a9: jbd2_log_wait_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int jbd2_log_wait_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f7fe0)
Location: fs/jbd2/journal.c:676
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff813f7fe0-ffffffff813f80f9: jbd2_log_wait_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int jbd2_log_wait_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81446060)
Location: fs/jbd2/journal.c:675
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff81446060-ffffffff81446179: jbd2_log_wait_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int jbd2_log_wait_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81462810)
Location: fs/jbd2/journal.c:681
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff81462810-ffffffff81462929: jbd2_log_wait_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int jbd2_log_wait_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81467ec0)
Location: fs/jbd2/journal.c:681
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff81467ec0-ffffffff81467fd9: jbd2_log_wait_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int jbd2_log_wait_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814bdfe0)
Location: fs/jbd2/journal.c:681
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff814bdfe0-ffffffff814be0f9: jbd2_log_wait_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int jbd2_log_wait_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81548390)
Location: fs/jbd2/journal.c:681
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff81548390-ffffffff815484db: jbd2_log_wait_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int jbd2_log_wait_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815e7a80)
Location: fs/jbd2/journal.c:678
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff815e7a80-ffffffff815e7bcb: jbd2_log_wait_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int jbd2_log_wait_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8161f390)
Location: fs/jbd2/journal.c:677
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff8161f390-ffffffff8161f4dc: jbd2_log_wait_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int jbd2_log_wait_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff816582a0)
Location: fs/jbd2/journal.c:666
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_wait_for_tail_page_commit
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff816582a0-ffffffff816583ec: jbd2_log_wait_commit (STB_GLOBAL)
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
int jbd2_log_wait_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffff8000104d5b68)
Location: fs/jbd2/journal.c:676
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffff8000104d5b68-ffff8000104d5d34: jbd2_log_wait_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int jbd2_log_wait_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c06989b4)
Location: fs/jbd2/journal.c:676
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
c06989b4-c0698b1c: jbd2_log_wait_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int jbd2_log_wait_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c00000000060e840)
Location: fs/jbd2/journal.c:676
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
c00000000060e840-c00000000060e9dc: jbd2_log_wait_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int jbd2_log_wait_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffe00034acec)
Location: fs/jbd2/journal.c:676
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
```
**Symbols:**

```
ffffffe00034acec-ffffffe00034adfe: jbd2_log_wait_commit (STB_GLOBAL)
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
int jbd2_log_wait_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f05c0)
Location: fs/jbd2/journal.c:676
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff813f05c0-ffffffff813f06d9: jbd2_log_wait_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int jbd2_log_wait_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813e1040)
Location: fs/jbd2/journal.c:676
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff813e1040-ffffffff813e1159: jbd2_log_wait_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int jbd2_log_wait_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813ed940)
Location: fs/jbd2/journal.c:676
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff813ed940-ffffffff813eda59: jbd2_log_wait_commit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int jbd2_log_wait_commit(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81403310)
Location: fs/jbd2/journal.c:676
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
  - fs/ext4/super.c:ext4_sync_fs
  - fs/ext4/super.c:ext4_sync_fs
  - fs/jbd2/transaction.c:jbd2_journal_stop
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_complete_transaction
  - fs/jbd2/journal.c:__jbd2_journal_force_commit
```
**Symbols:**

```
ffffffff81403310-ffffffff8140341f: jbd2_log_wait_commit (STB_GLOBAL)
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
