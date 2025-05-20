# Function: <code>scsi_partsize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_partsize(unsigned char *buf, long unsigned int capacity, unsigned int *cyls, unsigned int *hds, unsigned int *secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff815a91c0)
Location: drivers/scsi/scsicam.c:125
Inline: False
Direct callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
```
**Symbols:**

```
ffffffff815a91c0-ffffffff815a92b4: scsi_partsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_partsize(unsigned char *buf, long unsigned int capacity, unsigned int *cyls, unsigned int *hds, unsigned int *secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff816010a0)
Location: drivers/scsi/scsicam.c:125
Inline: False
Direct callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
```
**Symbols:**

```
ffffffff816010a0-ffffffff8160119d: scsi_partsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_partsize(unsigned char *buf, long unsigned int capacity, unsigned int *cyls, unsigned int *hds, unsigned int *secs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff81630790)
Location: drivers/scsi/scsicam.c:125
Inline: False
Direct callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
```
**Symbols:**

```
ffffffff81630790-ffffffff8163088d: scsi_partsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int scsi_partsize(unsigned char *buf, long unsigned int capacity, unsigned int *cyls, unsigned int *hds, unsigned int *secs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff81645744)
Location: drivers/scsi/scsicam.c:125
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
Direct callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
```
**Symbols:**

```
ffffffff81645600-ffffffff816456f2: scsi_partsize.part.0 (STB_LOCAL)
ffffffff81645700-ffffffff8164571e: scsi_partsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int scsi_partsize(unsigned char *buf, long unsigned int capacity, unsigned int *cyls, unsigned int *hds, unsigned int *secs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff816ae714)
Location: drivers/scsi/scsicam.c:126
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
Direct callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
```
**Symbols:**

```
ffffffff816ae5d0-ffffffff816ae6c2: scsi_partsize.part.1 (STB_LOCAL)
ffffffff816ae6d0-ffffffff816ae6ee: scsi_partsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int scsi_partsize(unsigned char *buf, long unsigned int capacity, unsigned int *cyls, unsigned int *hds, unsigned int *secs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff816eab05)
Location: drivers/scsi/scsicam.c:126
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
Direct callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
```
**Symbols:**

```
ffffffff816ea9c0-ffffffff816eaaa6: scsi_partsize.part.2 (STB_LOCAL)
ffffffff816eaab0-ffffffff816eaace: scsi_partsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int scsi_partsize(unsigned char *buf, long unsigned int capacity, unsigned int *cyls, unsigned int *hds, unsigned int *secs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff8170e5b5)
Location: drivers/scsi/scsicam.c:126
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
Direct callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
```
**Symbols:**

```
ffffffff8170e470-ffffffff8170e556: scsi_partsize.part.2 (STB_LOCAL)
ffffffff8170e560-ffffffff8170e57e: scsi_partsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int scsi_partsize(unsigned char *buf, long unsigned int capacity, unsigned int *cyls, unsigned int *hds, unsigned int *secs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff81749d75)
Location: drivers/scsi/scsicam.c:126
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
Direct callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
```
**Symbols:**

```
ffffffff81749c30-ffffffff81749d17: scsi_partsize.part.0 (STB_LOCAL)
ffffffff81749d20-ffffffff81749d3e: scsi_partsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int scsi_partsize(unsigned char *buf, long unsigned int capacity, unsigned int *cyls, unsigned int *hds, unsigned int *secs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff8176dec5)
Location: drivers/scsi/scsicam.c:126
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
Direct callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
```
**Symbols:**

```
ffffffff8176dd80-ffffffff8176de67: scsi_partsize.part.0 (STB_LOCAL)
ffffffff8176de70-ffffffff8176de8e: scsi_partsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool scsi_partsize(struct block_device *bdev, sector_t capacity, int *geom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff81830360)
Location: drivers/scsi/scsicam.c:61
Inline: False
```
**Symbols:**

```
ffffffff81830360-ffffffff8183048c: scsi_partsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool scsi_partsize(struct block_device *bdev, sector_t capacity, int *geom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff81840fd0)
Location: drivers/scsi/scsicam.c:61
Inline: False
```
**Symbols:**

```
ffffffff81840fd0-ffffffff818410fc: scsi_partsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool scsi_partsize(struct block_device *bdev, sector_t capacity, int *geom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff818241c0)
Location: drivers/scsi/scsicam.c:62
Inline: False
```
**Symbols:**

```
ffffffff818241c0-ffffffff818242ec: scsi_partsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool scsi_partsize(struct block_device *bdev, sector_t capacity, int *geom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff818afa00)
Location: drivers/scsi/scsicam.c:62
Inline: False
```
**Symbols:**

```
ffffffff818afa00-ffffffff818afb23: scsi_partsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool scsi_partsize(struct block_device *bdev, sector_t capacity, int *geom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff819fa960)
Location: drivers/scsi/scsicam.c:60
Inline: False
```
**Symbols:**

```
ffffffff819fa960-ffffffff819faaa7: scsi_partsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool scsi_partsize(struct block_device *bdev, sector_t capacity, int *geom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff81b78970)
Location: drivers/scsi/scsicam.c:60
Inline: False
```
**Symbols:**

```
ffffffff81b78970-ffffffff81b78ab7: scsi_partsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool scsi_partsize(struct block_device *bdev, sector_t capacity, int *geom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff81bcc600)
Location: drivers/scsi/scsicam.c:60
Inline: False
```
**Symbols:**

```
ffffffff81bcc600-ffffffff81bcc747: scsi_partsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool scsi_partsize(struct block_device *bdev, sector_t capacity, int *geom);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff81c21230)
Location: drivers/scsi/scsicam.c:60
Inline: False
```
**Symbols:**

```
ffffffff81c21230-ffffffff81c21377: scsi_partsize (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int scsi_partsize(unsigned char *buf, long unsigned int capacity, unsigned int *cyls, unsigned int *hds, unsigned int *secs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsicam.c (ffff800010970dcc)
Location: drivers/scsi/scsicam.c:126
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
Direct callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
```
**Symbols:**

```
ffff800010970af8-ffff800010970c04: scsi_partsize.part.0 (STB_LOCAL)
ffff800010970c08-ffff800010970c7c: scsi_partsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int scsi_partsize(unsigned char *buf, long unsigned int capacity, unsigned int *cyls, unsigned int *hds, unsigned int *secs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsicam.c (c0a459f4)
Location: drivers/scsi/scsicam.c:126
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
Direct callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
```
**Symbols:**

```
c0a45850-c0a4596c: scsi_partsize.part.0 (STB_LOCAL)
c0a4596c-c0a459b0: scsi_partsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int scsi_partsize(unsigned char *buf, long unsigned int capacity, unsigned int *cyls, unsigned int *hds, unsigned int *secs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsicam.c (c000000000a2a1bc)
Location: drivers/scsi/scsicam.c:126
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
Direct callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
```
**Symbols:**

```
c000000000a2a010-c000000000a2a12c: scsi_partsize.part.0 (STB_LOCAL)
c000000000a2a130-c000000000a2a168: scsi_partsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int scsi_partsize(unsigned char *buf, long unsigned int capacity, unsigned int *cyls, unsigned int *hds, unsigned int *secs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffe0005da44e)
Location: drivers/scsi/scsicam.c:126
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
Direct callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
```
**Symbols:**

```
ffffffe0005da2a4-ffffffe0005da3c4: scsi_partsize.part.0 (STB_LOCAL)
ffffffe0005da3c4-ffffffe0005da420: scsi_partsize (STB_GLOBAL)
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
int scsi_partsize(unsigned char *buf, long unsigned int capacity, unsigned int *cyls, unsigned int *hds, unsigned int *secs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff817225b5)
Location: drivers/scsi/scsicam.c:126
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
Direct callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
```
**Symbols:**

```
ffffffff81722470-ffffffff81722557: scsi_partsize.part.0 (STB_LOCAL)
ffffffff81722560-ffffffff8172257e: scsi_partsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int scsi_partsize(unsigned char *buf, long unsigned int capacity, unsigned int *cyls, unsigned int *hds, unsigned int *secs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff816fb9e5)
Location: drivers/scsi/scsicam.c:126
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
Direct callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
```
**Symbols:**

```
ffffffff816fb8a0-ffffffff816fb987: scsi_partsize.part.0 (STB_LOCAL)
ffffffff816fb990-ffffffff816fb9ae: scsi_partsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int scsi_partsize(unsigned char *buf, long unsigned int capacity, unsigned int *cyls, unsigned int *hds, unsigned int *secs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff81761385)
Location: drivers/scsi/scsicam.c:126
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
Direct callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
```
**Symbols:**

```
ffffffff81761240-ffffffff81761327: scsi_partsize.part.0 (STB_LOCAL)
ffffffff81761330-ffffffff8176134e: scsi_partsize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int scsi_partsize(unsigned char *buf, long unsigned int capacity, unsigned int *cyls, unsigned int *hds, unsigned int *secs);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff8177c9e5)
Location: drivers/scsi/scsicam.c:126
Inline: True
Inline callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
Direct callers:
  - drivers/scsi/scsicam.c:scsicam_bios_param
```
**Symbols:**

```
ffffffff8177c8a0-ffffffff8177c987: scsi_partsize.part.0 (STB_LOCAL)
ffffffff8177c990-ffffffff8177c9ae: scsi_partsize (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct block_device *bdev</code>
</li>
<li>
<b>Param added. </b>
<code>int *geom</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned char *buf</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int *cyls</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int *hds</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int *secs</code>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int capacity</code> ➡️ <code>sector_t capacity</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
