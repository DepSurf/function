# Function: <code>ext4_write_merkle_tree_block</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_write_merkle_tree_block(struct inode *inode, const void *buf, u64 index, int log_blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff813eee90)
Location: fs/ext4/verity.c:353
Inline: False
```
**Symbols:**

```
ffffffff813eee90-ffffffff813eeede: ext4_write_merkle_tree_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_write_merkle_tree_block(struct inode *inode, const void *buf, u64 index, int log_blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff8143c060)
Location: fs/ext4/verity.c:368
Inline: False
```
**Symbols:**

```
ffffffff8143c060-ffffffff8143c0a7: ext4_write_merkle_tree_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_write_merkle_tree_block(struct inode *inode, const void *buf, u64 index, int log_blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff814583c0)
Location: fs/ext4/verity.c:389
Inline: False
```
**Symbols:**

```
ffffffff814583c0-ffffffff81458407: ext4_write_merkle_tree_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_write_merkle_tree_block(struct inode *inode, const void *buf, u64 index, int log_blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff8145dd60)
Location: fs/ext4/verity.c:383
Inline: False
```
**Symbols:**

```
ffffffff8145dd60-ffffffff8145dda7: ext4_write_merkle_tree_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_write_merkle_tree_block(struct inode *inode, const void *buf, u64 index, int log_blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/verity.c (0)
Location: fs/ext4/verity.c:383
Inline: False
```
**Symbols:**

```
ffffffff814b3220-ffffffff814b32a2: ext4_write_merkle_tree_block (STB_LOCAL)
ffffffff81cce332-ffffffff81cce385: ext4_write_merkle_tree_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_write_merkle_tree_block(struct inode *inode, const void *buf, u64 index, int log_blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/verity.c (0)
Location: fs/ext4/verity.c:384
Inline: False
```
**Symbols:**

```
ffffffff8153be10-ffffffff8153be8b: ext4_write_merkle_tree_block (STB_LOCAL)
ffffffff81e8138f-ffffffff81e813e9: ext4_write_merkle_tree_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_write_merkle_tree_block(struct inode *inode, const void *buf, u64 index, int log_blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/verity.c (0)
Location: fs/ext4/verity.c:383
Inline: False
```
**Symbols:**

```
ffffffff815da4b0-ffffffff815da52b: ext4_write_merkle_tree_block (STB_LOCAL)
ffffffff82071233-ffffffff8207128d: ext4_write_merkle_tree_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_write_merkle_tree_block(struct inode *inode, const void *buf, u64 pos, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff816121e0)
Location: fs/ext4/verity.c:383
Inline: False
```
**Symbols:**

```
ffffffff816121e0-ffffffff81612225: ext4_write_merkle_tree_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_write_merkle_tree_block(struct inode *inode, const void *buf, u64 pos, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff8164af80)
Location: fs/ext4/verity.c:383
Inline: False
```
**Symbols:**

```
ffffffff8164af80-ffffffff8164afc5: ext4_write_merkle_tree_block (STB_LOCAL)
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
int ext4_write_merkle_tree_block(struct inode *inode, const void *buf, u64 index, int log_blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffff8000104c81f0)
Location: fs/ext4/verity.c:353
Inline: False
```
**Symbols:**

```
ffff8000104c81f0-ffff8000104c8274: ext4_write_merkle_tree_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_write_merkle_tree_block(struct inode *inode, const void *buf, u64 index, int log_blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (c068c020)
Location: fs/ext4/verity.c:353
Inline: False
```
**Symbols:**

```
c068c020-c068c0b8: ext4_write_merkle_tree_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_write_merkle_tree_block(struct inode *inode, const void *buf, u64 index, int log_blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (c000000000600dd0)
Location: fs/ext4/verity.c:353
Inline: False
```
**Symbols:**

```
c000000000600dd0-c000000000600e28: ext4_write_merkle_tree_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_write_merkle_tree_block(struct inode *inode, const void *buf, u64 index, int log_blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffe000342084)
Location: fs/ext4/verity.c:353
Inline: False
```
**Symbols:**

```
ffffffe000342084-ffffffe0003420f0: ext4_write_merkle_tree_block (STB_LOCAL)
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
int ext4_write_merkle_tree_block(struct inode *inode, const void *buf, u64 index, int log_blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff813e7470)
Location: fs/ext4/verity.c:353
Inline: False
```
**Symbols:**

```
ffffffff813e7470-ffffffff813e74be: ext4_write_merkle_tree_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_write_merkle_tree_block(struct inode *inode, const void *buf, u64 index, int log_blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff813d7ef0)
Location: fs/ext4/verity.c:353
Inline: False
```
**Symbols:**

```
ffffffff813d7ef0-ffffffff813d7f3e: ext4_write_merkle_tree_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_write_merkle_tree_block(struct inode *inode, const void *buf, u64 index, int log_blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff813e47f0)
Location: fs/ext4/verity.c:353
Inline: False
```
**Symbols:**

```
ffffffff813e47f0-ffffffff813e483e: ext4_write_merkle_tree_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_write_merkle_tree_block(struct inode *inode, const void *buf, u64 index, int log_blocksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff813f9c20)
Location: fs/ext4/verity.c:353
Inline: False
```
**Symbols:**

```
ffffffff813f9c20-ffffffff813f9c6e: ext4_write_merkle_tree_block (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 pos</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int size</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 index</code>
</li>
<li>
<b>Param removed. </b>
<code>int log_blocksize</code>
</li>
</ul>
</details>
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
