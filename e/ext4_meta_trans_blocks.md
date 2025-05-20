# Function: <code>ext4_meta_trans_blocks</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_meta_trans_blocks(struct inode *inode, int lblocks, int pextents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81295f20)
Location: fs/ext4/inode.c:4938
Inline: False
Direct callers:
  - fs/ext4/inode.c:_ext4_get_block
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff81295f20-ffffffff81295fa5: ext4_meta_trans_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_meta_trans_blocks(struct inode *inode, int lblocks, int pextents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c34f0)
Location: fs/ext4/inode.c:5279
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
```
**Symbols:**

```
ffffffff812c34f0-ffffffff812c357d: ext4_meta_trans_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_meta_trans_blocks(struct inode *inode, int lblocks, int pextents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812d8b80)
Location: fs/ext4/inode.c:5423
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
```
**Symbols:**

```
ffffffff812d8b80-ffffffff812d8c0d: ext4_meta_trans_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_meta_trans_blocks(struct inode *inode, int lblocks, int pextents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812fce20)
Location: fs/ext4/inode.c:5583
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
```
**Symbols:**

```
ffffffff812fce20-ffffffff812fcead: ext4_meta_trans_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_meta_trans_blocks(struct inode *inode, int lblocks, int pextents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81321720)
Location: fs/ext4/inode.c:5636
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
```
**Symbols:**

```
ffffffff81321720-ffffffff813217ad: ext4_meta_trans_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_meta_trans_blocks(struct inode *inode, int lblocks, int pextents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8134f780)
Location: fs/ext4/inode.c:5732
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
```
**Symbols:**

```
ffffffff8134f780-ffffffff8134f80f: ext4_meta_trans_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_meta_trans_blocks(struct inode *inode, int lblocks, int pextents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81367960)
Location: fs/ext4/inode.c:5784
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
```
**Symbols:**

```
ffffffff81367960-ffffffff813679ef: ext4_meta_trans_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_meta_trans_blocks(struct inode *inode, int lblocks, int pextents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81390c60)
Location: fs/ext4/inode.c:5806
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
```
**Symbols:**

```
ffffffff81390c60-ffffffff81390cf3: ext4_meta_trans_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_meta_trans_blocks(struct inode *inode, int lblocks, int pextents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a9620)
Location: fs/ext4/inode.c:5820
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
```
**Symbols:**

```
ffffffff813a9620-ffffffff813a96b3: ext4_meta_trans_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_meta_trans_blocks(struct inode *inode, int lblocks, int pextents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f5a80)
Location: fs/ext4/inode.c:5541
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_iomap_alloc
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff813f5a80-ffffffff813f5b0c: ext4_meta_trans_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_meta_trans_blocks(struct inode *inode, int lblocks, int pextents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814084d0)
Location: fs/ext4/inode.c:5632
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_iomap_alloc
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff814084d0-ffffffff81408562: ext4_meta_trans_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_meta_trans_blocks(struct inode *inode, int lblocks, int pextents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140ec60)
Location: fs/ext4/inode.c:5629
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff8140ec60-ffffffff8140ecf2: ext4_meta_trans_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_meta_trans_blocks(struct inode *inode, int lblocks, int pextents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81461f30)
Location: fs/ext4/inode.c:5568
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff81461f30-ffffffff81461fc2: ext4_meta_trans_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_meta_trans_blocks(struct inode *inode, int lblocks, int pextents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e0680)
Location: fs/ext4/inode.c:5646
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
```
**Symbols:**

```
ffffffff814e0680-ffffffff814e071e: ext4_meta_trans_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_meta_trans_blocks(struct inode *inode, int lblocks, int pextents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81579b40)
Location: fs/ext4/inode.c:5785
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
```
**Symbols:**

```
ffffffff81579b40-ffffffff81579bde: ext4_meta_trans_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_meta_trans_blocks(struct inode *inode, int lblocks, int pextents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b10e0)
Location: fs/ext4/inode.c:5597
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
```
**Symbols:**

```
ffffffff815b10e0-ffffffff815b117e: ext4_meta_trans_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_meta_trans_blocks(struct inode *inode, int lblocks, int pextents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815e9790)
Location: fs/ext4/inode.c:5617
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_do_writepages
  - fs/ext4/inode.c:ext4_do_writepages
```
**Symbols:**

```
ffffffff815e9790-ffffffff815e982e: ext4_meta_trans_blocks (STB_LOCAL)
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
int ext4_meta_trans_blocks(struct inode *inode, int lblocks, int pextents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff80001047d4b0)
Location: fs/ext4/inode.c:5820
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
```
**Symbols:**

```
ffff80001047d4b0-ffff80001047d570: ext4_meta_trans_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_meta_trans_blocks(struct inode *inode, int lblocks, int pextents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c063edd0)
Location: fs/ext4/inode.c:5820
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
```
**Symbols:**

```
c063edd0-c063ee6c: ext4_meta_trans_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_meta_trans_blocks(struct inode *inode, int lblocks, int pextents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a1120)
Location: fs/ext4/inode.c:5820
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
```
**Symbols:**

```
c0000000005a1120-c0000000005a121c: ext4_meta_trans_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_meta_trans_blocks(struct inode *inode, int lblocks, int pextents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe000306f4c)
Location: fs/ext4/inode.c:5820
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
```
**Symbols:**

```
ffffffe000306f4c-ffffffe000307000: ext4_meta_trans_blocks (STB_LOCAL)
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
int ext4_meta_trans_blocks(struct inode *inode, int lblocks, int pextents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a1c00)
Location: fs/ext4/inode.c:5820
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
```
**Symbols:**

```
ffffffff813a1c00-ffffffff813a1c93: ext4_meta_trans_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_meta_trans_blocks(struct inode *inode, int lblocks, int pextents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81392690)
Location: fs/ext4/inode.c:5820
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
```
**Symbols:**

```
ffffffff81392690-ffffffff81392723: ext4_meta_trans_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_meta_trans_blocks(struct inode *inode, int lblocks, int pextents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8139f460)
Location: fs/ext4/inode.c:5820
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
```
**Symbols:**

```
ffffffff8139f460-ffffffff8139f4f3: ext4_meta_trans_blocks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_meta_trans_blocks(struct inode *inode, int lblocks, int pextents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b3b00)
Location: fs/ext4/inode.c:5820
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_writepage_trans_blocks
  - fs/ext4/inode.c:ext4_iomap_begin
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_writepages
  - fs/ext4/inode.c:ext4_get_block_trans
```
**Symbols:**

```
ffffffff813b3b00-ffffffff813b3b93: ext4_meta_trans_blocks (STB_LOCAL)
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
