# Function: <code>mutex_lock_io</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mutex_lock_io(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff819080b0)
Location: kernel/locking/mutex.c:1118
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_update_log_tail
```
**Symbols:**

```
ffffffff819080b0-ffffffff819080da: mutex_lock_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mutex_lock_io(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81992190)
Location: kernel/locking/mutex.c:1118
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_update_log_tail
```
**Symbols:**

```
ffffffff81992190-ffffffff819921ba: mutex_lock_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mutex_lock_io(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff819eef40)
Location: kernel/locking/mutex.c:1142
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_update_log_tail
```
**Symbols:**

```
ffffffff819eef40-ffffffff819eef6a: mutex_lock_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mutex_lock_io(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a2a280)
Location: kernel/locking/mutex.c:1320
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_update_log_tail
```
**Symbols:**

```
ffffffff81a2a280-ffffffff81a2a2aa: mutex_lock_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mutex_lock_io(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a9aa10)
Location: kernel/locking/mutex.c:1325
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_update_log_tail
```
**Symbols:**

```
ffffffff81a9aa10-ffffffff81a9aa3e: mutex_lock_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mutex_lock_io(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81ad2360)
Location: kernel/locking/mutex.c:1351
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_update_log_tail
```
**Symbols:**

```
ffffffff81ad2360-ffffffff81ad238e: mutex_lock_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mutex_lock_io(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81bca540)
Location: kernel/locking/mutex.c:1351
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_update_log_tail
```
**Symbols:**

```
ffffffff81bca540-ffffffff81bca594: mutex_lock_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mutex_lock_io(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81c433a0)
Location: kernel/locking/mutex.c:1354
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_update_log_tail
```
**Symbols:**

```
ffffffff81c433a0-ffffffff81c433f4: mutex_lock_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mutex_lock_io(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81c34a60)
Location: kernel/locking/mutex.c:1352
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_update_log_tail
```
**Symbols:**

```
ffffffff81c34a60-ffffffff81c34ab4: mutex_lock_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mutex_lock_io(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81d532f0)
Location: kernel/locking/mutex.c:966
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_update_log_tail
```
**Symbols:**

```
ffffffff81d532f0-ffffffff81d53344: mutex_lock_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mutex_lock_io(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81f24bf0)
Location: kernel/locking/mutex.c:1022
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_update_log_tail
```
**Symbols:**

```
ffffffff81f24bf0-ffffffff81f24c54: mutex_lock_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mutex_lock_io(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff820d0190)
Location: kernel/locking/mutex.c:1022
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_update_log_tail
```
**Symbols:**

```
ffffffff820d0190-ffffffff820d01f4: mutex_lock_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mutex_lock_io(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff82153950)
Location: kernel/locking/mutex.c:1022
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_update_log_tail
```
**Symbols:**

```
ffffffff82153950-ffffffff821539b4: mutex_lock_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mutex_lock_io(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff82236790)
Location: kernel/locking/mutex.c:1027
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:journal_reset
  - fs/jbd2/journal.c:jbd2_update_log_tail
```
**Symbols:**

```
ffffffff82236790-ffffffff822367f4: mutex_lock_io (STB_GLOBAL)
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
void mutex_lock_io(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffff800010da3680)
Location: kernel/locking/mutex.c:1351
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_update_log_tail
```
**Symbols:**

```
ffff800010da3680-ffff800010da36bc: mutex_lock_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mutex_lock_io(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c0e9c8dc)
Location: kernel/locking/mutex.c:1351
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_update_log_tail
```
**Symbols:**

```
c0e9c8dc-c0e9c910: mutex_lock_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mutex_lock_io(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c000000000ee5c90)
Location: kernel/locking/mutex.c:1351
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_update_log_tail
```
**Symbols:**

```
c000000000ee5c90-c000000000ee5cf0: mutex_lock_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mutex_lock_io(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffe0008c74b2)
Location: kernel/locking/mutex.c:1351
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_update_log_tail
```
**Symbols:**

```
ffffffe0008c74b2-ffffffe0008c74f4: mutex_lock_io (STB_GLOBAL)
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
void mutex_lock_io(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a711d0)
Location: kernel/locking/mutex.c:1351
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_update_log_tail
```
**Symbols:**

```
ffffffff81a711d0-ffffffff81a711fe: mutex_lock_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mutex_lock_io(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a2d5c0)
Location: kernel/locking/mutex.c:1351
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_update_log_tail
```
**Symbols:**

```
ffffffff81a2d5c0-ffffffff81a2d5ee: mutex_lock_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mutex_lock_io(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81add5e0)
Location: kernel/locking/mutex.c:1351
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_update_log_tail
```
**Symbols:**

```
ffffffff81add5e0-ffffffff81add60e: mutex_lock_io (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mutex_lock_io(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81ae9190)
Location: kernel/locking/mutex.c:1351
Inline: False
Direct callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/checkpoint.c:jbd2_log_do_checkpoint
  - fs/jbd2/checkpoint.c:__jbd2_log_wait_for_space
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_flush
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_journal_destroy
  - fs/jbd2/journal.c:jbd2_update_log_tail
```
**Symbols:**

```
ffffffff81ae9190-ffffffff81ae91be: mutex_lock_io (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
