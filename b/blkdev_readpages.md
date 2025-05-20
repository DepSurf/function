# Function: <code>blkdev_readpages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blkdev_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81247c50)
Location: fs/block_dev.c:307
Inline: False
```
**Symbols:**

```
ffffffff81247c50-ffffffff81247c6f: blkdev_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blkdev_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81270460)
Location: fs/block_dev.c:326
Inline: False
```
**Symbols:**

```
ffffffff81270460-ffffffff8127047f: blkdev_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blkdev_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81283c30)
Location: fs/block_dev.c:578
Inline: False
```
**Symbols:**

```
ffffffff81283c30-ffffffff81283c4f: blkdev_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blkdev_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81291330)
Location: fs/block_dev.c:586
Inline: False
```
**Symbols:**

```
ffffffff81291330-ffffffff8129134f: blkdev_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blkdev_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b4080)
Location: fs/block_dev.c:574
Inline: False
```
**Symbols:**

```
ffffffff812b4080-ffffffff812b409f: blkdev_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blkdev_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812db6d0)
Location: fs/block_dev.c:575
Inline: False
```
**Symbols:**

```
ffffffff812db6d0-ffffffff812db6ef: blkdev_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blkdev_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f0cd0)
Location: fs/block_dev.c:612
Inline: False
```
**Symbols:**

```
ffffffff812f0cd0-ffffffff812f0cef: blkdev_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blkdev_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81312bd0)
Location: fs/block_dev.c:617
Inline: False
```
**Symbols:**

```
ffffffff81312bd0-ffffffff81312bef: blkdev_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blkdev_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81325b10)
Location: fs/block_dev.c:617
Inline: False
```
**Symbols:**

```
ffffffff81325b10-ffffffff81325b2f: blkdev_readpages (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int blkdev_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103dfbf8)
Location: fs/block_dev.c:617
Inline: False
```
**Symbols:**

```
ffff8000103dfbf8-ffff8000103dfc44: blkdev_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blkdev_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b86a4)
Location: fs/block_dev.c:617
Inline: False
```
**Symbols:**

```
c05b86a4-c05b86d4: blkdev_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blkdev_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e50f0)
Location: fs/block_dev.c:617
Inline: False
```
**Symbols:**

```
c0000000004e50f0-c0000000004e513c: blkdev_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blkdev_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe000296ad0)
Location: fs/block_dev.c:617
Inline: False
```
**Symbols:**

```
ffffffe000296ad0-ffffffe000296b12: blkdev_readpages (STB_LOCAL)
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
int blkdev_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131e0f0)
Location: fs/block_dev.c:617
Inline: False
```
**Symbols:**

```
ffffffff8131e0f0-ffffffff8131e10f: blkdev_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blkdev_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8130ec90)
Location: fs/block_dev.c:617
Inline: False
```
**Symbols:**

```
ffffffff8130ec90-ffffffff8130ecaf: blkdev_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blkdev_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131bbc0)
Location: fs/block_dev.c:617
Inline: False
```
**Symbols:**

```
ffffffff8131bbc0-ffffffff8131bbdf: blkdev_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blkdev_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132d9a0)
Location: fs/block_dev.c:617
Inline: False
```
**Symbols:**

```
ffffffff8132d9a0-ffffffff8132d9bf: blkdev_readpages (STB_LOCAL)
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
