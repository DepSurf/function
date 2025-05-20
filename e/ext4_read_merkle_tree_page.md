# Function: <code>ext4_read_merkle_tree_page</code>

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
struct page *ext4_read_merkle_tree_page(struct inode *inode, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff813eeb90)
Location: fs/ext4/verity.c:345
Inline: False
```
**Symbols:**

```
ffffffff813eeb90-ffffffff813eebc5: ext4_read_merkle_tree_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *ext4_read_merkle_tree_page(struct inode *inode, long unsigned int index, long unsigned int num_ra_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff8143bc50)
Location: fs/ext4/verity.c:348
Inline: False
```
**Symbols:**

```
ffffffff8143bc50-ffffffff8143bd4a: ext4_read_merkle_tree_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *ext4_read_merkle_tree_page(struct inode *inode, long unsigned int index, long unsigned int num_ra_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff81457f80)
Location: fs/ext4/verity.c:369
Inline: False
```
**Symbols:**

```
ffffffff81457f80-ffffffff814580ad: ext4_read_merkle_tree_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *ext4_read_merkle_tree_page(struct inode *inode, long unsigned int index, long unsigned int num_ra_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff8145d930)
Location: fs/ext4/verity.c:363
Inline: False
```
**Symbols:**

```
ffffffff8145d930-ffffffff8145da65: ext4_read_merkle_tree_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *ext4_read_merkle_tree_page(struct inode *inode, long unsigned int index, long unsigned int num_ra_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff814b2df0)
Location: fs/ext4/verity.c:363
Inline: False
```
**Symbols:**

```
ffffffff814b2df0-ffffffff814b2f22: ext4_read_merkle_tree_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *ext4_read_merkle_tree_page(struct inode *inode, long unsigned int index, long unsigned int num_ra_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff8153c550)
Location: fs/ext4/verity.c:364
Inline: False
```
**Symbols:**

```
ffffffff8153c550-ffffffff8153c6f0: ext4_read_merkle_tree_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *ext4_read_merkle_tree_page(struct inode *inode, long unsigned int index, long unsigned int num_ra_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff815dac30)
Location: fs/ext4/verity.c:362
Inline: False
```
**Symbols:**

```
ffffffff815dac30-ffffffff815dae06: ext4_read_merkle_tree_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *ext4_read_merkle_tree_page(struct inode *inode, long unsigned int index, long unsigned int num_ra_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff81611d20)
Location: fs/ext4/verity.c:360
Inline: False
```
**Symbols:**

```
ffffffff81611d20-ffffffff81611e6d: ext4_read_merkle_tree_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *ext4_read_merkle_tree_page(struct inode *inode, long unsigned int index, long unsigned int num_ra_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff8164aad0)
Location: fs/ext4/verity.c:360
Inline: False
```
**Symbols:**

```
ffffffff8164aad0-ffffffff8164ac0a: ext4_read_merkle_tree_page (STB_LOCAL)
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
struct page *ext4_read_merkle_tree_page(struct inode *inode, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffff8000104c8048)
Location: fs/ext4/verity.c:345
Inline: False
```
**Symbols:**

```
ffff8000104c8048-ffff8000104c8094: ext4_read_merkle_tree_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *ext4_read_merkle_tree_page(struct inode *inode, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (c068bc90)
Location: fs/ext4/verity.c:345
Inline: False
```
**Symbols:**

```
c068bc90-c068bce4: ext4_read_merkle_tree_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct page *ext4_read_merkle_tree_page(struct inode *inode, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (c0000000006007c0)
Location: fs/ext4/verity.c:345
Inline: False
```
**Symbols:**

```
c0000000006007c0-c000000000600818: ext4_read_merkle_tree_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct page *ext4_read_merkle_tree_page(struct inode *inode, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffe000341d20)
Location: fs/ext4/verity.c:345
Inline: False
```
**Symbols:**

```
ffffffe000341d20-ffffffe000341d66: ext4_read_merkle_tree_page (STB_LOCAL)
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
struct page *ext4_read_merkle_tree_page(struct inode *inode, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff813e7170)
Location: fs/ext4/verity.c:345
Inline: False
```
**Symbols:**

```
ffffffff813e7170-ffffffff813e71a5: ext4_read_merkle_tree_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *ext4_read_merkle_tree_page(struct inode *inode, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff813d7bf0)
Location: fs/ext4/verity.c:345
Inline: False
```
**Symbols:**

```
ffffffff813d7bf0-ffffffff813d7c25: ext4_read_merkle_tree_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *ext4_read_merkle_tree_page(struct inode *inode, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff813e44f0)
Location: fs/ext4/verity.c:345
Inline: False
```
**Symbols:**

```
ffffffff813e44f0-ffffffff813e4525: ext4_read_merkle_tree_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *ext4_read_merkle_tree_page(struct inode *inode, long unsigned int index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/verity.c (ffffffff813f9900)
Location: fs/ext4/verity.c:345
Inline: False
```
**Symbols:**

```
ffffffff813f9900-ffffffff813f9935: ext4_read_merkle_tree_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int num_ra_pages</code>
</li>
</ul>
</details>
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
