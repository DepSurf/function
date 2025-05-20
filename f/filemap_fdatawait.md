# Function: <code>filemap_fdatawait</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawait(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8118cb90)
Location: mm/filemap.c:433
Inline: True
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff8118cb90-ffffffff8118cbb5: filemap_fdatawait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawait(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8119fb80)
Location: mm/filemap.c:512
Inline: True
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff8119fb80-ffffffff8119fba5: filemap_fdatawait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int filemap_fdatawait(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811afde0)
Location: mm/filemap.c:477
Inline: True
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
**Symbols:**

```
ffffffff811afde0-ffffffff811afe05: filemap_fdatawait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int filemap_fdatawait(struct address_space *mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811b6e40)
Location: mm/filemap.c:505
Inline: False
Direct callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
**Symbols:**

```
ffffffff811b6e40-ffffffff811b6e72: filemap_fdatawait (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811cd909)
Location: include/linux/fs.h:2610
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812a6531)
Location: include/linux/fs.h:2610
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff811ef439)
Location: include/linux/fs.h:2633
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812cd0f0)
Location: include/linux/fs.h:2633
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff81200c39)
Location: include/linux/fs.h:2719
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812e2410)
Location: include/linux/fs.h:2719
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121885a)
Location: include/linux/fs.h:2722
Inline: True
```
```
In fs/fs-writeback.c (ffffffff81300e24)
Location: include/linux/fs.h:2722
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812260ec)
Location: include/linux/fs.h:2757
Inline: True
```
```
In fs/fs-writeback.c (ffffffff813134f4)
Location: include/linux/fs.h:2757
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8134ce45)
Location: include/linux/fs.h:2776
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81359d59)
Location: include/linux/fs.h:2638
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8136095f)
Location: include/linux/fs.h:2872
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff813aefd9)
Location: include/linux/fs.h:2853
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff81433804)
Location: include/linux/pagemap.h:41
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814c1a64)
Location: include/linux/pagemap.h:41
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff814f6df4)
Location: include/linux/pagemap.h:44
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fs-writeback.c (ffffffff8152b534)
Location: include/linux/pagemap.h:44
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffff8000102b3340)
Location: include/linux/fs.h:2757
Inline: True
```
```
In fs/fs-writeback.c (ffff8000103c8e28)
Location: include/linux/fs.h:2757
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c04e0554)
Location: include/linux/fs.h:2757
Inline: True
```
```
In fs/fs-writeback.c (c05a5604)
Location: include/linux/fs.h:2757
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (c000000000369eb8)
Location: include/linux/fs.h:2757
Inline: True
```
```
In fs/fs-writeback.c (c0000000004ca424)
Location: include/linux/fs.h:2757
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffe0001d8ab6)
Location: include/linux/fs.h:2757
Inline: True
```
```
In fs/fs-writeback.c (ffffffe00028747c)
Location: include/linux/fs.h:2757
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121e73c)
Location: include/linux/fs.h:2757
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8130bad4)
Location: include/linux/fs.h:2757
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff812118fc)
Location: include/linux/fs.h:2757
Inline: True
```
```
In fs/fs-writeback.c (ffffffff812fc6f4)
Location: include/linux/fs.h:2757
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8121c4dc)
Location: include/linux/fs.h:2757
Inline: True
```
```
In fs/fs-writeback.c (ffffffff813098c4)
Location: include/linux/fs.h:2757
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/filemap.c (ffffffff8122b56c)
Location: include/linux/fs.h:2757
Inline: True
```
```
In fs/fs-writeback.c (ffffffff8131a2a9)
Location: include/linux/fs.h:2757
Inline: True
Inline callers:
  - fs/fs-writeback.c:__writeback_single_inode
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
</ul>
