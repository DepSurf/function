# Function: <code>cdrom_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cdrom_open(struct cdrom_device_info *cdi, struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81600700)
Location: drivers/cdrom/cdrom.c:1150
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff81600700-ffffffff81601145: cdrom_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cdrom_open(struct cdrom_device_info *cdi, struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81660540)
Location: drivers/cdrom/cdrom.c:1150
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff81660540-ffffffff81660ed8: cdrom_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cdrom_open(struct cdrom_device_info *cdi, struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8168e330)
Location: drivers/cdrom/cdrom.c:1150
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff8168e330-ffffffff8168ecc8: cdrom_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cdrom_open(struct cdrom_device_info *cdi, struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff816a35c0)
Location: drivers/cdrom/cdrom.c:1148
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff816a35c0-ffffffff816a3f67: cdrom_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cdrom_open(struct cdrom_device_info *cdi, struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8170e8d0)
Location: drivers/cdrom/cdrom.c:1148
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff8170e8d0-ffffffff8170f2b3: cdrom_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int cdrom_open(struct cdrom_device_info *cdi, struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1148
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff8174fd46-ffffffff8174fdcf: cdrom_open.cold.30 (STB_LOCAL)
ffffffff8174da30-ffffffff8174de0c: cdrom_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int cdrom_open(struct cdrom_device_info *cdi, struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1148
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff8177416a-ffffffff817741f3: cdrom_open.cold.29 (STB_LOCAL)
ffffffff81771c60-ffffffff8177203c: cdrom_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cdrom_open(struct cdrom_device_info *cdi, struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1149
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff817b2097-ffffffff817b2120: cdrom_open.cold (STB_LOCAL)
ffffffff817b0020-ffffffff817b0400: cdrom_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int cdrom_open(struct cdrom_device_info *cdi, struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1155
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff817e23d4-ffffffff817e245d: cdrom_open.cold (STB_LOCAL)
ffffffff817e0340-ffffffff817e072f: cdrom_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cdrom_open(struct cdrom_device_info *cdi, struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818b0ad0)
Location: drivers/cdrom/cdrom.c:1158
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff818b0ad0-ffffffff818b0ccb: cdrom_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cdrom_open(struct cdrom_device_info *cdi, struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818bf7a0)
Location: drivers/cdrom/cdrom.c:1158
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff818bf7a0-ffffffff818bf99b: cdrom_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cdrom_open(struct cdrom_device_info *cdi, struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818a2860)
Location: drivers/cdrom/cdrom.c:1158
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff818a2860-ffffffff818a2a5b: cdrom_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cdrom_open(struct cdrom_device_info *cdi, struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1158
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff81d13560-ffffffff81d1359f: cdrom_open.cold (STB_LOCAL)
ffffffff81937300-ffffffff8193752d: cdrom_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cdrom_open(struct cdrom_device_info *cdi, struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1158
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff81ede2b7-ffffffff81ede2f6: cdrom_open.cold (STB_LOCAL)
ffffffff81a8e840-ffffffff81a8ea84: cdrom_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int cdrom_open(struct cdrom_device_info *cdi, struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1158
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff8209e5aa-ffffffff8209e5e9: cdrom_open.cold (STB_LOCAL)
ffffffff81c0fd20-ffffffff81c0ff5c: cdrom_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int cdrom_open(struct cdrom_device_info *cdi, blk_mode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1150
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff8211f98f-ffffffff8211f9ce: cdrom_open.cold (STB_LOCAL)
ffffffff81c75600-ffffffff81c75844: cdrom_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int cdrom_open(struct cdrom_device_info *cdi, blk_mode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1150
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff82201165-ffffffff822011a4: cdrom_open.cold (STB_LOCAL)
ffffffff81d2a000-ffffffff81d2a244: cdrom_open (STB_GLOBAL)
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
int cdrom_open(struct cdrom_device_info *cdi, struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffff800010a0cc58)
Location: drivers/cdrom/cdrom.c:1155
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffff800010a0cc58-ffff800010a0d09c: cdrom_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cdrom_open(struct cdrom_device_info *cdi, struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (c0ae49d4)
Location: drivers/cdrom/cdrom.c:1155
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
c0ae49d4-c0ae4dd4: cdrom_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cdrom_open(struct cdrom_device_info *cdi, struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (c000000000ac4740)
Location: drivers/cdrom/cdrom.c:1155
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
c000000000ac4740-c000000000ac4cd4: cdrom_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cdrom_open(struct cdrom_device_info *cdi, struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffe000634420)
Location: drivers/cdrom/cdrom.c:1155
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffe000634420-ffffffe000634806: cdrom_open (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int cdrom_open(struct cdrom_device_info *cdi, struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1155
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff8179a7b4-ffffffff8179a83d: cdrom_open.cold (STB_LOCAL)
ffffffff81798720-ffffffff81798b0f: cdrom_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int cdrom_open(struct cdrom_device_info *cdi, struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1155
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff8178c484-ffffffff8178c50d: cdrom_open.cold (STB_LOCAL)
ffffffff8178a3f0-ffffffff8178a7df: cdrom_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int cdrom_open(struct cdrom_device_info *cdi, struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1155
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff817d7254-ffffffff817d72dd: cdrom_open.cold (STB_LOCAL)
ffffffff817d51c0-ffffffff817d55af: cdrom_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int cdrom_open(struct cdrom_device_info *cdi, struct block_device *bdev, fmode_t mode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/cdrom/cdrom.c (0)
Location: drivers/cdrom/cdrom.c:1155
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_open
```
**Symbols:**

```
ffffffff817f14f4-ffffffff817f157d: cdrom_open.cold (STB_LOCAL)
ffffffff817ef460-ffffffff817ef84f: cdrom_open (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct block_device *bdev</code>
</li>
<li>
<b>Param reordered. </b>
<code>cdi, bdev, mode</code> ➡️ <code>cdi, mode</code>
</li>
<li>
<b>Param type changed. </b>
<code>fmode_t mode</code> ➡️ <code>blk_mode_t mode</code>
</li>
</ul>
</details>
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
