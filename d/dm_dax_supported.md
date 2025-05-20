# Function: <code>dm_dax_supported</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool dm_dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81877b10)
Location: drivers/md/dm.c:1108
Inline: False
```
**Symbols:**

```
ffffffff81877b10-ffffffff81877b98: dm_dax_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool dm_dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818a94d0)
Location: drivers/md/dm.c:1108
Inline: False
```
**Symbols:**

```
ffffffff818a94d0-ffffffff818a9558: dm_dax_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool dm_dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81978630)
Location: drivers/md/dm.c:1134
Inline: False
```
**Symbols:**

```
ffffffff81978630-ffffffff819786a8: dm_dax_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool dm_dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197d4c0)
Location: drivers/md/dm.c:1139
Inline: False
```
**Symbols:**

```
ffffffff8197d4c0-ffffffff8197d538: dm_dax_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool dm_dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81960ff0)
Location: drivers/md/dm.c:1143
Inline: False
```
**Symbols:**

```
ffffffff81960ff0-ffffffff81961068: dm_dax_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool dm_dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81a083e0)
Location: drivers/md/dm.c:1030
Inline: False
```
**Symbols:**

```
ffffffff81a083e0-ffffffff81a08458: dm_dax_supported (STB_LOCAL)
```
</details>
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
bool dm_dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010afd918)
Location: drivers/md/dm.c:1108
Inline: False
```
**Symbols:**

```
ffff800010afd918-ffff800010afd9bc: dm_dax_supported (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool dm_dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bee960)
Location: drivers/md/dm.c:1108
Inline: False
```
**Symbols:**

```
c000000000bee960-c000000000beea48: dm_dax_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool dm_dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006ef9f6)
Location: drivers/md/dm.c:1108
Inline: False
```
**Symbols:**

```
ffffffe0006ef9f6-ffffffe0006efa86: dm_dax_supported (STB_LOCAL)
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
bool dm_dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8184f350)
Location: drivers/md/dm.c:1108
Inline: False
```
**Symbols:**

```
ffffffff8184f350-ffffffff8184f3d8: dm_dax_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool dm_dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81816960)
Location: drivers/md/dm.c:1108
Inline: False
```
**Symbols:**

```
ffffffff81816960-ffffffff818169e8: dm_dax_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool dm_dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189e980)
Location: drivers/md/dm.c:1108
Inline: False
```
**Symbols:**

```
ffffffff8189e980-ffffffff8189ea08: dm_dax_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool dm_dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818bb280)
Location: drivers/md/dm.c:1108
Inline: False
```
**Symbols:**

```
ffffffff818bb280-ffffffff818bb308: dm_dax_supported (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
