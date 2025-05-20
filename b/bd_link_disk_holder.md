# Function: <code>bd_link_disk_holder</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bd_link_disk_holder(struct block_device *bdev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81248e40)
Location: fs/block_dev.c:945
Inline: False
Direct callers:
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81248e40-ffffffff81248ff9: bd_link_disk_holder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bd_link_disk_holder(struct block_device *bdev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81270e50)
Location: fs/block_dev.c:1023
Inline: False
Direct callers:
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81270e50-ffffffff81270fff: bd_link_disk_holder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bd_link_disk_holder(struct block_device *bdev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812847c0)
Location: fs/block_dev.c:1275
Inline: False
Direct callers:
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff812847c0-ffffffff8128496f: bd_link_disk_holder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bd_link_disk_holder(struct block_device *bdev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812925b0)
Location: fs/block_dev.c:1200
Inline: False
Direct callers:
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff812925b0-ffffffff81292730: bd_link_disk_holder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bd_link_disk_holder(struct block_device *bdev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812b53c0)
Location: fs/block_dev.c:1190
Inline: False
Direct callers:
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff812b53c0-ffffffff812b5540: bd_link_disk_holder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bd_link_disk_holder(struct block_device *bdev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812dbf60)
Location: fs/block_dev.c:1211
Inline: False
Direct callers:
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff812dbf60-ffffffff812dc0e9: bd_link_disk_holder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bd_link_disk_holder(struct block_device *bdev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff812f0d60)
Location: fs/block_dev.c:1250
Inline: False
Direct callers:
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff812f0d60-ffffffff812f0ee9: bd_link_disk_holder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int bd_link_disk_holder(struct block_device *bdev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/block_dev.c (0)
Location: fs/block_dev.c:1302
Inline: False
Direct callers:
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81314f86-ffffffff81314f9c: bd_link_disk_holder.cold (STB_LOCAL)
ffffffff81312c60-ffffffff81312dd6: bd_link_disk_holder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bd_link_disk_holder(struct block_device *bdev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81325ba0)
Location: fs/block_dev.c:1302
Inline: False
Direct callers:
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81325ba0-ffffffff81325d20: bd_link_disk_holder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bd_link_disk_holder(struct block_device *bdev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8135f4c0)
Location: fs/block_dev.c:1283
Inline: False
Direct callers:
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff8135f4c0-ffffffff8135f646: bd_link_disk_holder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bd_link_disk_holder(struct block_device *bdev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136cc20)
Location: fs/block_dev.c:1148
Inline: False
Direct callers:
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff8136cc20-ffffffff8136cd94: bd_link_disk_holder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bd_link_disk_holder(struct block_device *bdev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813734c0)
Location: fs/block_dev.c:1154
Inline: False
Direct callers:
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff813734c0-ffffffff81373634: bd_link_disk_holder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bd_link_disk_holder(struct block_device *bdev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/holder.c (ffffffff8160f9b0)
Location: block/holder.c:73
Inline: False
Direct callers:
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff8160f9b0-ffffffff8160fb31: bd_link_disk_holder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bd_link_disk_holder(struct block_device *bdev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/holder.c (ffffffff816c4300)
Location: block/holder.c:73
Inline: False
Direct callers:
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff816c4300-ffffffff816c4469: bd_link_disk_holder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bd_link_disk_holder(struct block_device *bdev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/holder.c (ffffffff81785850)
Location: block/holder.c:60
Inline: False
Direct callers:
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff81785850-ffffffff81785a91: bd_link_disk_holder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bd_link_disk_holder(struct block_device *bdev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/holder.c (ffffffff817c5cc0)
Location: block/holder.c:60
Inline: False
Direct callers:
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff817c5cc0-ffffffff817c5f04: bd_link_disk_holder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bd_link_disk_holder(struct block_device *bdev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/holder.c (ffffffff8180a9b0)
Location: block/holder.c:60
Inline: False
Direct callers:
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff8180a9b0-ffffffff8180ac23: bd_link_disk_holder (STB_GLOBAL)
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
int bd_link_disk_holder(struct block_device *bdev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103dfd28)
Location: fs/block_dev.c:1302
Inline: False
Direct callers:
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffff8000103dfd28-ffff8000103dfec8: bd_link_disk_holder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bd_link_disk_holder(struct block_device *bdev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b8768)
Location: fs/block_dev.c:1302
Inline: False
Direct callers:
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
c05b8768-c05b890c: bd_link_disk_holder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bd_link_disk_holder(struct block_device *bdev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e66c0)
Location: fs/block_dev.c:1302
Inline: False
Direct callers:
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
c0000000004e66c0-c0000000004e6924: bd_link_disk_holder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bd_link_disk_holder(struct block_device *bdev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe000296bdc)
Location: fs/block_dev.c:1302
Inline: False
Direct callers:
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffe000296bdc-ffffffe000296d12: bd_link_disk_holder (STB_GLOBAL)
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
int bd_link_disk_holder(struct block_device *bdev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131e180)
Location: fs/block_dev.c:1302
Inline: False
Direct callers:
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff8131e180-ffffffff8131e300: bd_link_disk_holder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bd_link_disk_holder(struct block_device *bdev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8130ed20)
Location: fs/block_dev.c:1302
Inline: False
Direct callers:
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff8130ed20-ffffffff8130eea0: bd_link_disk_holder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bd_link_disk_holder(struct block_device *bdev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131bc50)
Location: fs/block_dev.c:1302
Inline: False
Direct callers:
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff8131bc50-ffffffff8131bdd0: bd_link_disk_holder (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bd_link_disk_holder(struct block_device *bdev, struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132da30)
Location: fs/block_dev.c:1302
Inline: False
Direct callers:
  - drivers/md/md.c:bind_rdev_to_array
  - drivers/md/dm.c:dm_get_table_device
```
**Symbols:**

```
ffffffff8132da30-ffffffff8132dbb0: bd_link_disk_holder (STB_GLOBAL)
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
