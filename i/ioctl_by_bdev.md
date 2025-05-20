# Function: <code>ioctl_by_bdev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ioctl_by_bdev(struct block_device *bdev, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81247fa0)
Location: fs/block_dev.c:1749
Inline: False
```
**Symbols:**

```
ffffffff81247fa0-ffffffff81247fdf: ioctl_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ioctl_by_bdev(struct block_device *bdev, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81270790)
Location: fs/block_dev.c:1828
Inline: False
```
**Symbols:**

```
ffffffff81270790-ffffffff812707cf: ioctl_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ioctl_by_bdev(struct block_device *bdev, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81284110)
Location: fs/block_dev.c:2150
Inline: False
```
**Symbols:**

```
ffffffff81284110-ffffffff8128414f: ioctl_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ioctl_by_bdev(struct block_device *bdev, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812917c0)
Location: fs/block_dev.c:2066
Inline: False
```
**Symbols:**

```
ffffffff812917c0-ffffffff812917ff: ioctl_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ioctl_by_bdev(struct block_device *bdev, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b4510)
Location: fs/block_dev.c:2062
Inline: False
```
**Symbols:**

```
ffffffff812b4510-ffffffff812b4559: ioctl_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ioctl_by_bdev(struct block_device *bdev, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812dbb30)
Location: fs/block_dev.c:2078
Inline: False
```
**Symbols:**

```
ffffffff812dbb30-ffffffff812dbb79: ioctl_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ioctl_by_bdev(struct block_device *bdev, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f1220)
Location: fs/block_dev.c:2112
Inline: False
```
**Symbols:**

```
ffffffff812f1220-ffffffff812f1269: ioctl_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ioctl_by_bdev(struct block_device *bdev, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81313880)
Location: fs/block_dev.c:2153
Inline: False
```
**Symbols:**

```
ffffffff81313880-ffffffff813138c9: ioctl_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ioctl_by_bdev(struct block_device *bdev, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81326790)
Location: fs/block_dev.c:2137
Inline: False
```
**Symbols:**

```
ffffffff81326790-ffffffff813267d9: ioctl_by_bdev (STB_GLOBAL)
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
int ioctl_by_bdev(struct block_device *bdev, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103e0b38)
Location: fs/block_dev.c:2137
Inline: False
```
**Symbols:**

```
ffff8000103e0b38-ffff8000103e0c00: ioctl_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ioctl_by_bdev(struct block_device *bdev, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b9130)
Location: fs/block_dev.c:2137
Inline: False
```
**Symbols:**

```
c05b9130-c05b9190: ioctl_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ioctl_by_bdev(struct block_device *bdev, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e5e90)
Location: fs/block_dev.c:2137
Inline: False
```
**Symbols:**

```
c0000000004e5e90-c0000000004e5f30: ioctl_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ioctl_by_bdev(struct block_device *bdev, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe000296fda)
Location: fs/block_dev.c:2137
Inline: False
```
**Symbols:**

```
ffffffe000296fda-ffffffe000297028: ioctl_by_bdev (STB_GLOBAL)
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
int ioctl_by_bdev(struct block_device *bdev, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131ed70)
Location: fs/block_dev.c:2137
Inline: False
```
**Symbols:**

```
ffffffff8131ed70-ffffffff8131edb9: ioctl_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ioctl_by_bdev(struct block_device *bdev, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8130f910)
Location: fs/block_dev.c:2137
Inline: False
```
**Symbols:**

```
ffffffff8130f910-ffffffff8130f959: ioctl_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ioctl_by_bdev(struct block_device *bdev, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131c840)
Location: fs/block_dev.c:2137
Inline: False
```
**Symbols:**

```
ffffffff8131c840-ffffffff8131c889: ioctl_by_bdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ioctl_by_bdev(struct block_device *bdev, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132eb40)
Location: fs/block_dev.c:2137
Inline: False
```
**Symbols:**

```
ffffffff8132eb40-ffffffff8132eb89: ioctl_by_bdev (STB_GLOBAL)
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
