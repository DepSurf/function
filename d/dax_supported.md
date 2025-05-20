# Function: <code>dax_supported</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8173f481)
Location: drivers/dax/super.c:318
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__bdev_dax_supported
```
**Symbols:**

```
ffffffff8173fa90-ffffffff8173fab8: dax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81763661)
Location: drivers/dax/super.c:318
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__bdev_dax_supported
```
**Symbols:**

```
ffffffff81763c70-ffffffff81763c98: dax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81823501)
Location: drivers/dax/super.c:318
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - drivers/md/dm-table.c:device_supports_dax
```
**Symbols:**

```
ffffffff81822d80-ffffffff81822db0: dax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8183222e)
Location: drivers/dax/super.c:326
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - drivers/md/dm-table.c:device_not_dax_capable
```
**Symbols:**

```
ffffffff81831a90-ffffffff81831ac0: dax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8181580e)
Location: drivers/dax/super.c:326
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__bdev_dax_supported
Direct callers:
  - drivers/md/dm-table.c:device_not_dax_capable
```
**Symbols:**

```
ffffffff81814cc0-ffffffff81814cf0: dax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff8189f860)
Location: drivers/dax/super.c:205
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - drivers/md/dm-table.c:device_not_dax_capable
```
**Symbols:**

```
ffffffff8189f860-ffffffff8189f905: dax_supported (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffff800010963330)
Location: drivers/dax/super.c:318
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__bdev_dax_supported
```
**Symbols:**

```
ffff800010963b28-ffff800010963b9c: dax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c0a3a760)
Location: drivers/dax/super.c:318
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__bdev_dax_supported
```
**Symbols:**

```
c0a3a8a8-c0a3a8f8: dax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c000000000a19b68)
Location: drivers/dax/super.c:318
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__bdev_dax_supported
```
**Symbols:**

```
c000000000a1a3a0-c000000000a1a3f8: dax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffe0005d0a4e)
Location: drivers/dax/super.c:318
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__bdev_dax_supported
```
**Symbols:**

```
ffffffe0005d0d9a-ffffffe0005d0dee: dax_supported (STB_GLOBAL)
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
bool dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81717d51)
Location: drivers/dax/super.c:318
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__bdev_dax_supported
```
**Symbols:**

```
ffffffff81718360-ffffffff81718388: dax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff816f0281)
Location: drivers/dax/super.c:318
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__bdev_dax_supported
```
**Symbols:**

```
ffffffff816f0890-ffffffff816f08b8: dax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81756b21)
Location: drivers/dax/super.c:318
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__bdev_dax_supported
```
**Symbols:**

```
ffffffff81757130-ffffffff81757158: dax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool dax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81771f81)
Location: drivers/dax/super.c:318
Inline: True
Inline callers:
  - drivers/dax/super.c:__bdev_dax_supported
  - drivers/dax/super.c:__bdev_dax_supported
```
**Symbols:**

```
ffffffff817725d0-ffffffff817725f8: dax_supported (STB_GLOBAL)
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
