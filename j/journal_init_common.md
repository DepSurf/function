# Function: <code>journal_init_common</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
journal_t *journal_init_common();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff812ef4d0)
Location: fs/jbd2/journal.c:1069
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_init_dev
  - fs/jbd2/journal.c:jbd2_journal_init_inode
```
**Symbols:**

```
ffffffff812ef4d0-ffffffff812ef62f: journal_init_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
journal_t *journal_init_common();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8131da40)
Location: fs/jbd2/journal.c:1093
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
```
**Symbols:**

```
ffffffff8131da40-ffffffff8131db9f: journal_init_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
journal_t *journal_init_common(struct block_device *bdev, struct block_device *fs_dev, long long unsigned int start, int len, int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813339c0)
Location: fs/jbd2/journal.c:1093
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
```
**Symbols:**

```
ffffffff813339c0-ffffffff81333c48: journal_init_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
journal_t *journal_init_common(struct block_device *bdev, struct block_device *fs_dev, long long unsigned int start, int len, int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff813487b0)
Location: fs/jbd2/journal.c:1116
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
```
**Symbols:**

```
ffffffff813487b0-ffffffff81348a10: journal_init_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
journal_t *journal_init_common(struct block_device *bdev, struct block_device *fs_dev, long long unsigned int start, int len, int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8136ce00)
Location: fs/jbd2/journal.c:1132
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
```
**Symbols:**

```
ffffffff8136ce00-ffffffff8136d060: journal_init_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
journal_t *journal_init_common(struct block_device *bdev, struct block_device *fs_dev, long long unsigned int start, int len, int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1129
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
```
**Symbols:**

```
ffffffff8139b3c0-ffffffff8139b601: journal_init_common (STB_LOCAL)
ffffffff8139e291-ffffffff8139e2b0: journal_init_common.cold.46 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
journal_t *journal_init_common(struct block_device *bdev, struct block_device *fs_dev, long long unsigned int start, int len, int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1129
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
```
**Symbols:**

```
ffffffff813b4180-ffffffff813b43c1: journal_init_common (STB_LOCAL)
ffffffff813b7001-ffffffff813b7020: journal_init_common.cold.47 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
journal_t *journal_init_common(struct block_device *bdev, struct block_device *fs_dev, long long unsigned int start, int len, int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1112
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
```
**Symbols:**

```
ffffffff813de790-ffffffff813de9d1: journal_init_common (STB_LOCAL)
ffffffff813e171d-ffffffff813e173c: journal_init_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
journal_t *journal_init_common(struct block_device *bdev, struct block_device *fs_dev, long long unsigned int start, int len, int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1111
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
```
**Symbols:**

```
ffffffff813f8850-ffffffff813f8a91: journal_init_common (STB_LOCAL)
ffffffff813fb783-ffffffff813fb7a2: journal_init_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
journal_t *journal_init_common(struct block_device *bdev, struct block_device *fs_dev, long long unsigned int start, int len, int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1124
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
```
**Symbols:**

```
ffffffff814458a0-ffffffff81445af1: journal_init_common (STB_LOCAL)
ffffffff81448ee6-ffffffff81448f05: journal_init_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
journal_t *journal_init_common(struct block_device *bdev, struct block_device *fs_dev, long long unsigned int start, int len, int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1303
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
```
**Symbols:**

```
ffffffff814639e0-ffffffff81463c56: journal_init_common (STB_LOCAL)
ffffffff81bed149-ffffffff81bed168: journal_init_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
journal_t *journal_init_common(struct block_device *bdev, struct block_device *fs_dev, long long unsigned int start, int len, int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1303
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
```
**Symbols:**

```
ffffffff81467fe0-ffffffff81468253: journal_init_common (STB_LOCAL)
ffffffff81bdf138-ffffffff81bdf157: journal_init_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
journal_t *journal_init_common(struct block_device *bdev, struct block_device *fs_dev, long long unsigned int start, int len, int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1337
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
```
**Symbols:**

```
ffffffff814be5e0-ffffffff814be8d5: journal_init_common (STB_LOCAL)
ffffffff81cceb23-ffffffff81cceb3b: journal_init_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
journal_t *journal_init_common(struct block_device *bdev, struct block_device *fs_dev, long long unsigned int start, int len, int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1343
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
```
**Symbols:**

```
ffffffff815493f0-ffffffff815496f2: journal_init_common (STB_LOCAL)
ffffffff81e81abe-ffffffff81e81ad6: journal_init_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
journal_t *journal_init_common(struct block_device *bdev, struct block_device *fs_dev, long long unsigned int start, int len, int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff815e9460)
Location: fs/jbd2/journal.c:1346
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
```
**Symbols:**

```
ffffffff815e9460-ffffffff815e978c: journal_init_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
journal_t *journal_init_common(struct block_device *bdev, struct block_device *fs_dev, long long unsigned int start, int len, int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff81621270)
Location: fs/jbd2/journal.c:1348
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
```
**Symbols:**

```
ffffffff81621270-ffffffff8162159c: journal_init_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
journal_t *journal_init_common(struct block_device *bdev, struct block_device *fs_dev, long long unsigned int start, int len, int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffff8165ad70)
Location: fs/jbd2/journal.c:1519
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
```
**Symbols:**

```
ffffffff8165ad70-ffffffff8165b11f: journal_init_common (STB_LOCAL)
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
journal_t *journal_init_common(struct block_device *bdev, struct block_device *fs_dev, long long unsigned int start, int len, int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffff8000104d3d70)
Location: fs/jbd2/journal.c:1111
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
```
**Symbols:**

```
ffff8000104d3d70-ffff8000104d3f84: journal_init_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
journal_t *journal_init_common(struct block_device *bdev, struct block_device *fs_dev, long long unsigned int start, int len, int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c0697278)
Location: fs/jbd2/journal.c:1111
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
```
**Symbols:**

```
c0697278-c0697464: journal_init_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
journal_t *journal_init_common(struct block_device *bdev, struct block_device *fs_dev, long long unsigned int start, int len, int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (c00000000060f7b0)
Location: fs/jbd2/journal.c:1111
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
```
**Symbols:**

```
c00000000060f7b0-c00000000060fa64: journal_init_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
journal_t *journal_init_common(struct block_device *bdev, struct block_device *fs_dev, long long unsigned int start, int len, int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/jbd2/journal.c (ffffffe00034b528)
Location: fs/jbd2/journal.c:1111
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
```
**Symbols:**

```
ffffffe00034b528-ffffffe00034b72a: journal_init_common (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
journal_t *journal_init_common(struct block_device *bdev, struct block_device *fs_dev, long long unsigned int start, int len, int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1111
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
```
**Symbols:**

```
ffffffff813f0e30-ffffffff813f1071: journal_init_common (STB_LOCAL)
ffffffff813f3d63-ffffffff813f3d82: journal_init_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
journal_t *journal_init_common(struct block_device *bdev, struct block_device *fs_dev, long long unsigned int start, int len, int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1111
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
```
**Symbols:**

```
ffffffff813e18b0-ffffffff813e1af1: journal_init_common (STB_LOCAL)
ffffffff813e47e3-ffffffff813e4802: journal_init_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
journal_t *journal_init_common(struct block_device *bdev, struct block_device *fs_dev, long long unsigned int start, int len, int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1111
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
```
**Symbols:**

```
ffffffff813ee1b0-ffffffff813ee3f1: journal_init_common (STB_LOCAL)
ffffffff813f10e3-ffffffff813f1102: journal_init_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
journal_t *journal_init_common(struct block_device *bdev, struct block_device *fs_dev, long long unsigned int start, int len, int blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/jbd2/journal.c (0)
Location: fs/jbd2/journal.c:1111
Inline: False
Direct callers:
  - fs/jbd2/journal.c:jbd2_journal_init_inode
  - fs/jbd2/journal.c:jbd2_journal_init_dev
```
**Symbols:**

```
ffffffff81403e00-ffffffff81404041: journal_init_common (STB_LOCAL)
ffffffff81406cde-ffffffff81406cfd: journal_init_common.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct block_device *bdev</code>
</li>
<li>
<b>Param added. </b>
<code>struct block_device *fs_dev</code>
</li>
<li>
<b>Param added. </b>
<code>long long unsigned int start</code>
</li>
<li>
<b>Param added. </b>
<code>int len</code>
</li>
<li>
<b>Param added. </b>
<code>int blocksize</code>
</li>
</ul>
</details>
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
