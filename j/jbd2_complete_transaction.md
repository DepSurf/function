# Function: <code>jbd2_complete_transaction</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int jbd2_complete_transaction(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff812f1720)
Location: fs/jbd2/journal.c:724
Inline: False
Direct callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff812f1720-ffffffff812f17ba: jbd2_complete_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int jbd2_complete_transaction(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8131ef30)
Location: fs/jbd2/journal.c:726
Inline: False
Direct callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff8131ef30-ffffffff8131efc9: jbd2_complete_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int jbd2_complete_transaction(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81334fb0)
Location: fs/jbd2/journal.c:726
Inline: False
Direct callers:
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/extents.c:ext4_fallocate
```
**Symbols:**

```
ffffffff81334fb0-ffffffff81335049: jbd2_complete_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int jbd2_complete_transaction(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81349d50)
Location: fs/jbd2/journal.c:748
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff81349d50-ffffffff81349de4: jbd2_complete_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int jbd2_complete_transaction(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8136e3a0)
Location: fs/jbd2/journal.c:764
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff8136e3a0-ffffffff8136e434: jbd2_complete_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int jbd2_complete_transaction(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8139ca20)
Location: fs/jbd2/journal.c:761
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff8139ca20-ffffffff8139caa1: jbd2_complete_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int jbd2_complete_transaction(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813b5790)
Location: fs/jbd2/journal.c:761
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff813b5790-ffffffff813b5811: jbd2_complete_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int jbd2_complete_transaction(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813dfe70)
Location: fs/jbd2/journal.c:744
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff813dfe70-ffffffff813dfefa: jbd2_complete_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int jbd2_complete_transaction(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f9ec0)
Location: fs/jbd2/journal.c:742
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff813f9ec0-ffffffff813f9f4a: jbd2_complete_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int jbd2_complete_transaction(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81447e80)
Location: fs/jbd2/journal.c:741
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff81447e80-ffffffff81447f1f: jbd2_complete_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int jbd2_complete_transaction(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81464810)
Location: fs/jbd2/journal.c:826
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff81464810-ffffffff814648af: jbd2_complete_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int jbd2_complete_transaction(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81469fa0)
Location: fs/jbd2/journal.c:826
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff81469fa0-ffffffff8146a03f: jbd2_complete_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int jbd2_complete_transaction(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff814c0320)
Location: fs/jbd2/journal.c:826
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/fast_commit.c:ext4_fc_commit
```
**Symbols:**

```
ffffffff814c0320-ffffffff814c03c2: jbd2_complete_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int jbd2_complete_transaction(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8154ab30)
Location: fs/jbd2/journal.c:828
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/jbd2/journal.c:__jbd2_fc_end_commit
```
**Symbols:**

```
ffffffff8154ab30-ffffffff8154abda: jbd2_complete_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int jbd2_complete_transaction(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815e99c0)
Location: fs/jbd2/journal.c:825
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_evict_inode
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/jbd2/journal.c:__jbd2_fc_end_commit
```
**Symbols:**

```
ffffffff815e99c0-ffffffff815e9a6a: jbd2_complete_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int jbd2_complete_transaction(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff816217c0)
Location: fs/jbd2/journal.c:824
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/jbd2/journal.c:__jbd2_fc_end_commit
```
**Symbols:**

```
ffffffff816217c0-ffffffff8162186a: jbd2_complete_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int jbd2_complete_transaction(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81659ce0)
Location: fs/jbd2/journal.c:813
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_commit
  - fs/jbd2/journal.c:__jbd2_fc_end_commit
```
**Symbols:**

```
ffffffff81659ce0-ffffffff81659d87: jbd2_complete_transaction (STB_GLOBAL)
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
int jbd2_complete_transaction(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffff8000104d6b40)
Location: fs/jbd2/journal.c:742
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffff8000104d6b40-ffff8000104d6c60: jbd2_complete_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int jbd2_complete_transaction(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c0698db4)
Location: fs/jbd2/journal.c:742
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
c0698db4-c0698eac: jbd2_complete_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int jbd2_complete_transaction(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c0000000006116a0)
Location: fs/jbd2/journal.c:742
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
c0000000006116a0-c0000000006117c4: jbd2_complete_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int jbd2_complete_transaction(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffe00034ccbe)
Location: fs/jbd2/journal.c:742
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffe00034ccbe-ffffffe00034cd5e: jbd2_complete_transaction (STB_GLOBAL)
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
int jbd2_complete_transaction(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813f24a0)
Location: fs/jbd2/journal.c:742
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff813f24a0-ffffffff813f252a: jbd2_complete_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int jbd2_complete_transaction(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813e2f20)
Location: fs/jbd2/journal.c:742
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff813e2f20-ffffffff813e2faa: jbd2_complete_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int jbd2_complete_transaction(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813ef820)
Location: fs/jbd2/journal.c:742
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff813ef820-ffffffff813ef8aa: jbd2_complete_transaction (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int jbd2_complete_transaction(journal_t *journal, tid_t tid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81405200)
Location: fs/jbd2/journal.c:742
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_fallocate
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/fsync.c:ext4_sync_file
  - fs/ext4/inode.c:ext4_write_inode
  - fs/ext4/inode.c:ext4_evict_inode
```
**Symbols:**

```
ffffffff81405200-ffffffff8140528a: jbd2_complete_transaction (STB_GLOBAL)
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
