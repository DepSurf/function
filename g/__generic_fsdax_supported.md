# Function: <code>__generic_fsdax_supported</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __generic_fsdax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dax/super.c (ffffffff8173f550)
Location: drivers/dax/super.c:69
Inline: True
Direct callers:
  - drivers/md/dm-table.c:device_supports_dax
```
**Symbols:**

```
ffffffff8173f550-ffffffff8173fa0e: __generic_fsdax_supported.part.0 (STB_LOCAL)
ffffffff8173fa10-ffffffff8173fa87: __generic_fsdax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __generic_fsdax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dax/super.c (ffffffff81763730)
Location: drivers/dax/super.c:69
Inline: True
Direct callers:
  - drivers/md/dm-table.c:device_supports_dax
```
**Symbols:**

```
ffffffff81763730-ffffffff81763bee: __generic_fsdax_supported.part.0 (STB_LOCAL)
ffffffff81763bf0-ffffffff81763c67: __generic_fsdax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __generic_fsdax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff818235d0)
Location: drivers/dax/super.c:69
Inline: False
```
**Symbols:**

```
ffffffff818235d0-ffffffff81823ae2: __generic_fsdax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __generic_fsdax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff81832300)
Location: drivers/dax/super.c:70
Inline: False
```
**Symbols:**

```
ffffffff81832300-ffffffff818327fd: __generic_fsdax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __generic_fsdax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffff818150f0)
Location: drivers/dax/super.c:70
Inline: False
```
**Symbols:**

```
ffffffff818150f0-ffffffff818155ed: __generic_fsdax_supported (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool __generic_fsdax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffff800010963410)
Location: drivers/dax/super.c:69
Inline: True
Direct callers:
  - drivers/md/dm-table.c:device_supports_dax
```
**Symbols:**

```
ffff800010963410-ffff8000109636ac: __generic_fsdax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool __generic_fsdax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (c0a3a004)
Location: drivers/dax/super.c:69
Inline: True
```
**Symbols:**

```
c0a3a004-c0a3a35c: __generic_fsdax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __generic_fsdax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dax/super.c (c000000000a19ce0)
Location: drivers/dax/super.c:69
Inline: True
Direct callers:
  - drivers/md/dm-table.c:device_supports_dax
```
**Symbols:**

```
c000000000a19ce0-c000000000a1a2b8: __generic_fsdax_supported.part.0 (STB_LOCAL)
c000000000a1a2c0-c000000000a1a394: __generic_fsdax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool __generic_fsdax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/super.c (ffffffe0005d0b0c)
Location: drivers/dax/super.c:69
Inline: True
Direct callers:
  - drivers/md/dm-table.c:device_supports_dax
```
**Symbols:**

```
ffffffe0005d0b0c-ffffffe0005d0d9a: __generic_fsdax_supported (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __generic_fsdax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dax/super.c (ffffffff81717e20)
Location: drivers/dax/super.c:69
Inline: True
Direct callers:
  - drivers/md/dm-table.c:device_supports_dax
```
**Symbols:**

```
ffffffff81717e20-ffffffff817182de: __generic_fsdax_supported.part.0 (STB_LOCAL)
ffffffff817182e0-ffffffff81718357: __generic_fsdax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __generic_fsdax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dax/super.c (ffffffff816f0350)
Location: drivers/dax/super.c:69
Inline: True
Direct callers:
  - drivers/nvdimm/pmem.c:generic_fsdax_supported
  - drivers/md/dm-table.c:device_supports_dax
```
**Symbols:**

```
ffffffff816f0350-ffffffff816f080e: __generic_fsdax_supported.part.0 (STB_LOCAL)
ffffffff816f0810-ffffffff816f0887: __generic_fsdax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __generic_fsdax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dax/super.c (ffffffff81756bf0)
Location: drivers/dax/super.c:69
Inline: True
Direct callers:
  - drivers/md/dm-table.c:device_supports_dax
```
**Symbols:**

```
ffffffff81756bf0-ffffffff817570ae: __generic_fsdax_supported.part.0 (STB_LOCAL)
ffffffff817570b0-ffffffff81757127: __generic_fsdax_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __generic_fsdax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t sectors);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/dax/super.c (ffffffff81772050)
Location: drivers/dax/super.c:69
Inline: True
Direct callers:
  - drivers/md/dm-table.c:device_supports_dax
```
**Symbols:**

```
ffffffff81772050-ffffffff81772542: __generic_fsdax_supported.part.0 (STB_LOCAL)
ffffffff81772550-ffffffff817725c7: __generic_fsdax_supported (STB_GLOBAL)
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
