# Function: <code>bd_acquire</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bd_acquire(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812482f0)
Location: fs/block_dev.c:692
Inline: True
Direct callers:
  - fs/block_dev.c:blkdev_open
```
**Symbols:**

```
ffffffff812482f0-ffffffff812483cf: bd_acquire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bd_acquire(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81270a70)
Location: fs/block_dev.c:770
Inline: True
Direct callers:
  - fs/block_dev.c:blkdev_open
```
**Symbols:**

```
ffffffff81270a70-ffffffff81270b25: bd_acquire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bd_acquire(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812843e0)
Location: fs/block_dev.c:1022
Inline: True
Direct callers:
  - fs/block_dev.c:blkdev_open
```
**Symbols:**

```
ffffffff812843e0-ffffffff81284495: bd_acquire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct block_device *bd_acquire(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81292f30)
Location: fs/block_dev.c:938
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_open
```
**Symbols:**

```
ffffffff81292f30-ffffffff81292ff7: bd_acquire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct block_device *bd_acquire(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b5d20)
Location: fs/block_dev.c:928
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_open
```
**Symbols:**

```
ffffffff812b5d20-ffffffff812b5de7: bd_acquire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bd_acquire(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812dd980)
Location: fs/block_dev.c:929
Inline: True
Direct callers:
  - fs/block_dev.c:blkdev_open
```
**Symbols:**

```
ffffffff812dd980-ffffffff812dda47: bd_acquire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bd_acquire(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f2f60)
Location: fs/block_dev.c:968
Inline: True
Direct callers:
  - fs/block_dev.c:blkdev_open
```
**Symbols:**

```
ffffffff812f2f60-ffffffff812f3027: bd_acquire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bd_acquire(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813149d0)
Location: fs/block_dev.c:965
Inline: True
Direct callers:
  - fs/block_dev.c:blkdev_open
```
**Symbols:**

```
ffffffff813149d0-ffffffff81314a99: bd_acquire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bd_acquire(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813271b0)
Location: fs/block_dev.c:965
Inline: True
Direct callers:
  - fs/block_dev.c:blkdev_open
```
**Symbols:**

```
ffffffff813271b0-ffffffff81327279: bd_acquire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct block_device *bd_acquire(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813610f0)
Location: fs/block_dev.c:946
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_open
```
**Symbols:**

```
ffffffff813610f0-ffffffff81361205: bd_acquire (STB_LOCAL)
```
</details>
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
struct block_device *bd_acquire(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e1ff8)
Location: fs/block_dev.c:965
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_open
```
**Symbols:**

```
ffff8000103e1ff8-ffff8000103e2150: bd_acquire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct block_device *bd_acquire(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05ba240)
Location: fs/block_dev.c:965
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_open
```
**Symbols:**

```
c05ba240-c05ba318: bd_acquire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct block_device *bd_acquire(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e7b50)
Location: fs/block_dev.c:965
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_open
```
**Symbols:**

```
c0000000004e7b50-c0000000004e7cc0: bd_acquire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bd_acquire(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe00029865c)
Location: fs/block_dev.c:965
Inline: True
Direct callers:
  - fs/block_dev.c:blkdev_open
```
**Symbols:**

```
ffffffe00029865c-ffffffe0002987b6: bd_acquire (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bd_acquire(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131f790)
Location: fs/block_dev.c:965
Inline: True
Direct callers:
  - fs/block_dev.c:blkdev_open
```
**Symbols:**

```
ffffffff8131f790-ffffffff8131f859: bd_acquire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bd_acquire(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81310330)
Location: fs/block_dev.c:965
Inline: True
Direct callers:
  - fs/block_dev.c:blkdev_open
```
**Symbols:**

```
ffffffff81310330-ffffffff813103f9: bd_acquire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bd_acquire(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131d260)
Location: fs/block_dev.c:965
Inline: True
Direct callers:
  - fs/block_dev.c:blkdev_open
```
**Symbols:**

```
ffffffff8131d260-ffffffff8131d329: bd_acquire (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct block_device *bd_acquire(struct inode *inode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132ef60)
Location: fs/block_dev.c:965
Inline: True
Direct callers:
  - fs/block_dev.c:blkdev_open
```
**Symbols:**

```
ffffffff8132ef60-ffffffff8132f02b: bd_acquire (STB_LOCAL)
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
