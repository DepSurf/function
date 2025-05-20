# Function: <code>jbd2_journal_restart</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t *handle, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff812e7760)
Location: fs/jbd2/transaction.c:683
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/resize.c:update_backups
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
```
**Symbols:**

```
ffffffff812e7760-ffffffff812e7775: jbd2_journal_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t *handle, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813153d0)
Location: fs/jbd2/transaction.c:680
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/resize.c:update_backups
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff813153d0-ffffffff813153e5: jbd2_journal_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t *handle, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8132b3d0)
Location: fs/jbd2/transaction.c:682
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/resize.c:update_backups
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
```
**Symbols:**

```
ffffffff8132b3d0-ffffffff8132b3e5: jbd2_journal_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t *handle, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81340610)
Location: fs/jbd2/transaction.c:695
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/resize.c:update_backups
```
**Symbols:**

```
ffffffff81340610-ffffffff81340625: jbd2_journal_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t *handle, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81364c20)
Location: fs/jbd2/transaction.c:698
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/resize.c:update_backups
```
**Symbols:**

```
ffffffff81364c20-ffffffff81364c35: jbd2_journal_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t *handle, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81393390)
Location: fs/jbd2/transaction.c:694
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/resize.c:update_backups
```
**Symbols:**

```
ffffffff81393390-ffffffff813933a5: jbd2_journal_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t *handle, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813ac0b0)
Location: fs/jbd2/transaction.c:727
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/resize.c:update_backups
```
**Symbols:**

```
ffffffff813ac0b0-ffffffff813ac0c5: jbd2_journal_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t *handle, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813d6330)
Location: fs/jbd2/transaction.c:727
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/resize.c:update_backups
```
**Symbols:**

```
ffffffff813d6330-ffffffff813d6345: jbd2_journal_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t *handle, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813f0360)
Location: fs/jbd2/transaction.c:730
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/resize.c:update_backups
```
**Symbols:**

```
ffffffff813f0360-ffffffff813f0375: jbd2_journal_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t *handle, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8143d770)
Location: fs/jbd2/transaction.c:809
Inline: False
```
**Symbols:**

```
ffffffff8143d770-ffffffff8143d787: jbd2_journal_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t *handle, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff81459ac0)
Location: fs/jbd2/transaction.c:811
Inline: False
```
**Symbols:**

```
ffffffff81459ac0-ffffffff81459ad7: jbd2_journal_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t *handle, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8145f380)
Location: fs/jbd2/transaction.c:816
Inline: False
```
**Symbols:**

```
ffffffff8145f380-ffffffff8145f397: jbd2_journal_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t *handle, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff814b4830)
Location: fs/jbd2/transaction.c:833
Inline: False
```
**Symbols:**

```
ffffffff814b4830-ffffffff814b4847: jbd2_journal_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t *handle, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8153e140)
Location: fs/jbd2/transaction.c:825
Inline: False
```
**Symbols:**

```
ffffffff8153e140-ffffffff8153e163: jbd2_journal_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t *handle, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff815dca20)
Location: fs/jbd2/transaction.c:825
Inline: False
```
**Symbols:**

```
ffffffff815dca20-ffffffff815dca43: jbd2_journal_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t *handle, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff816144c0)
Location: fs/jbd2/transaction.c:825
Inline: False
```
**Symbols:**

```
ffffffff816144c0-ffffffff816144e3: jbd2_journal_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t *handle, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff8164d2b0)
Location: fs/jbd2/transaction.c:825
Inline: False
```
**Symbols:**

```
ffffffff8164d2b0-ffffffff8164d2d3: jbd2_journal_restart (STB_GLOBAL)
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
int jbd2_journal_restart(handle_t *handle, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffff8000104c9c88)
Location: fs/jbd2/transaction.c:730
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_swap_inode_data
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/resize.c:update_backups
```
**Symbols:**

```
ffff8000104c9c88-ffff8000104c9cc0: jbd2_journal_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t *handle, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c068d798)
Location: fs/jbd2/transaction.c:730
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/resize.c:update_backups
```
**Symbols:**

```
c068d798-c068d7b8: jbd2_journal_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t *handle, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (c000000000602450)
Location: fs/jbd2/transaction.c:730
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/resize.c:update_backups
```
**Symbols:**

```
c000000000602450-c000000000602468: jbd2_journal_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t *handle, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffe000343144)
Location: fs/jbd2/transaction.c:730
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/resize.c:update_backups
```
**Symbols:**

```
ffffffe000343144-ffffffe00034317c: jbd2_journal_restart (STB_GLOBAL)
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
int jbd2_journal_restart(handle_t *handle, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813e8940)
Location: fs/jbd2/transaction.c:730
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/resize.c:update_backups
```
**Symbols:**

```
ffffffff813e8940-ffffffff813e8955: jbd2_journal_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t *handle, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813d93c0)
Location: fs/jbd2/transaction.c:730
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/resize.c:update_backups
```
**Symbols:**

```
ffffffff813d93c0-ffffffff813d93d5: jbd2_journal_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t *handle, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813e5cc0)
Location: fs/jbd2/transaction.c:730
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/resize.c:update_backups
```
**Symbols:**

```
ffffffff813e5cc0-ffffffff813e5cd5: jbd2_journal_restart (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int jbd2_journal_restart(handle_t *handle, int nblocks);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/transaction.c (ffffffff813fadb0)
Location: fs/jbd2/transaction.c:730
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_truncate_restart_trans
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:ext4_ext_migrate
  - fs/ext4/migrate.c:finish_range
  - fs/ext4/resize.c:update_backups
```
**Symbols:**

```
ffffffff813fadb0-ffffffff813fadc5: jbd2_journal_restart (STB_GLOBAL)
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
