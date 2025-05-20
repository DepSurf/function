# Function: <code>generic_fsdax_supported</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81879b65)
Location: include/linux/dax.h:124
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_supports_dax
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818ab955)
Location: include/linux/dax.h:124
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_supports_dax
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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool generic_fsdax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t sectors);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/dax/super.c (0)
Location: drivers/dax/super.c:123
Inline: False
```
**Symbols:**

```
ffffffff81d0b8af-ffffffff81d0b910: generic_fsdax_supported.cold (STB_LOCAL)
ffffffff8189f910-ffffffff8189fd90: generic_fsdax_supported (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffff800010b02258)
Location: include/linux/dax.h:124
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_supports_dax
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (0)
Location: include/linux/dax.h:156
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (c000000000bf110c)
Location: include/linux/dax.h:124
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_supports_dax
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffe0006f1b70)
Location: include/linux/dax.h:124
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_supports_dax
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818517d5)
Location: include/linux/dax.h:124
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_supports_dax
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
bool generic_fsdax_supported(struct dax_device *dax_dev, struct block_device *bdev, int blocksize, sector_t start, sector_t sectors);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/pmem.c (ffffffff816ead60)
Location: include/linux/dax.h:124
Inline: False
```
```
In drivers/md/dm-table.c (ffffffff81818de5)
Location: include/linux/dax.h:124
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_supports_dax
```
**Symbols:**

```
ffffffff816ead60-ffffffff816ead6b: generic_fsdax_supported (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818a0e05)
Location: include/linux/dax.h:124
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_supports_dax
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/md/dm-table.c (ffffffff818bd045)
Location: include/linux/dax.h:124
Inline: True
Inline callers:
  - drivers/md/dm-table.c:device_supports_dax
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
</ul>
