# Function: <code>filemap_fdatawait_keep_errors</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void filemap_fdatawait_keep_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118f5a0)
Location: mm/filemap.c:411
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/sync.c:fdatawait_one_bdev
```
**Symbols:**

```
ffffffff8118f5a0-ffffffff8118f5c3: filemap_fdatawait_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void filemap_fdatawait_keep_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811a2b70)
Location: mm/filemap.c:490
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/sync.c:fdatawait_one_bdev
```
**Symbols:**

```
ffffffff811a2b70-ffffffff811a2b93: filemap_fdatawait_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void filemap_fdatawait_keep_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b32a0)
Location: mm/filemap.c:455
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/sync.c:fdatawait_one_bdev
```
**Symbols:**

```
ffffffff811b32a0-ffffffff811b32c3: filemap_fdatawait_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b6e80)
Location: mm/filemap.c:481
Inline: True
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/sync.c:fdatawait_one_bdev
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff811b6e80-ffffffff811b6eca: filemap_fdatawait_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811caff0)
Location: mm/filemap.c:599
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/sync.c:fdatawait_one_bdev
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff811caff0-ffffffff811cb02f: filemap_fdatawait_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ec250)
Location: mm/filemap.c:599
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/sync.c:fdatawait_one_bdev
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff811ec250-ffffffff811ec28f: filemap_fdatawait_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811fe5b0)
Location: mm/filemap.c:576
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/sync.c:fdatawait_one_bdev
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff811fe5b0-ffffffff811fe5ef: filemap_fdatawait_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81213680)
Location: mm/filemap.c:613
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/sync.c:fdatawait_one_bdev
```
**Symbols:**

```
ffffffff81213680-ffffffff812136c0: filemap_fdatawait_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81220e50)
Location: mm/filemap.c:619
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/sync.c:fdatawait_one_bdev
```
**Symbols:**

```
ffffffff81220e50-ffffffff81220e90: filemap_fdatawait_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8124e890)
Location: mm/filemap.c:619
Inline: False
Direct callers:
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/sync.c:fdatawait_one_bdev
```
**Symbols:**

```
ffffffff8124e890-ffffffff8124e8d3: filemap_fdatawait_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81258d50)
Location: mm/filemap.c:620
Inline: False
Direct callers:
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/sync.c:fdatawait_one_bdev
```
**Symbols:**

```
ffffffff81258d50-ffffffff81258d93: filemap_fdatawait_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8125d200)
Location: mm/filemap.c:611
Inline: False
Direct callers:
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/sync.c:fdatawait_one_bdev
```
**Symbols:**

```
ffffffff8125d200-ffffffff8125d243: filemap_fdatawait_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81299150)
Location: mm/filemap.c:629
Inline: False
Direct callers:
  - fs/fs-writeback.c:wait_sb_inodes
  - fs/sync.c:fdatawait_one_bdev
```
**Symbols:**

```
ffffffff81299150-ffffffff81299199: filemap_fdatawait_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812efdf0)
Location: mm/filemap.c:617
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - block/bdev.c:sync_bdevs
```
**Symbols:**

```
ffffffff812efdf0-ffffffff812efe43: filemap_fdatawait_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8135aff0)
Location: mm/filemap.c:614
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - block/bdev.c:sync_bdevs
```
**Symbols:**

```
ffffffff8135aff0-ffffffff8135b043: filemap_fdatawait_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8138dd40)
Location: mm/filemap.c:621
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - block/bdev.c:sync_bdevs
```
**Symbols:**

```
ffffffff8138dd40-ffffffff8138dd8d: filemap_fdatawait_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff813b7480)
Location: mm/filemap.c:616
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - block/bdev.c:sync_bdevs
```
**Symbols:**

```
ffffffff813b7480-ffffffff813b74cd: filemap_fdatawait_keep_errors (STB_GLOBAL)
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
int filemap_fdatawait_keep_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102ae8a0)
Location: mm/filemap.c:619
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/sync.c:fdatawait_one_bdev
```
**Symbols:**

```
ffff8000102ae8a0-ffff8000102ae8f8: filemap_fdatawait_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04dae2c)
Location: mm/filemap.c:619
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/sync.c:fdatawait_one_bdev
```
**Symbols:**

```
c04dae2c-c04dae8c: filemap_fdatawait_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c0000000003627c0)
Location: mm/filemap.c:619
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/sync.c:fdatawait_one_bdev
```
**Symbols:**

```
c0000000003627c0-c000000000362838: filemap_fdatawait_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d4658)
Location: mm/filemap.c:619
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/sync.c:fdatawait_one_bdev
```
**Symbols:**

```
ffffffe0001d4658-ffffffe0001d469e: filemap_fdatawait_keep_errors (STB_GLOBAL)
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
int filemap_fdatawait_keep_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812194a0)
Location: mm/filemap.c:619
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/sync.c:fdatawait_one_bdev
```
**Symbols:**

```
ffffffff812194a0-ffffffff812194e0: filemap_fdatawait_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8120c6b0)
Location: mm/filemap.c:619
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/sync.c:fdatawait_one_bdev
```
**Symbols:**

```
ffffffff8120c6b0-ffffffff8120c6f0: filemap_fdatawait_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81217240)
Location: mm/filemap.c:619
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/sync.c:fdatawait_one_bdev
```
**Symbols:**

```
ffffffff81217240-ffffffff81217280: filemap_fdatawait_keep_errors (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int filemap_fdatawait_keep_errors(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812262d0)
Location: mm/filemap.c:619
Inline: False
Direct callers:
  - fs/fs-writeback.c:sync_inodes_sb
  - fs/sync.c:fdatawait_one_bdev
```
**Symbols:**

```
ffffffff812262d0-ffffffff81226310: filemap_fdatawait_keep_errors (STB_GLOBAL)
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
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
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
