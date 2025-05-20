# Function: <code>scsicam_bios_param</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsicam_bios_param(struct block_device *bdev, sector_t capacity, int *ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff815a93a0)
Location: drivers/scsi/scsicam.c:67
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_getgeo
```
**Symbols:**

```
ffffffff815a93a0-ffffffff815a9509: scsicam_bios_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsicam_bios_param(struct block_device *bdev, sector_t capacity, int *ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff816012d0)
Location: drivers/scsi/scsicam.c:67
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_getgeo
```
**Symbols:**

```
ffffffff816012d0-ffffffff81601451: scsicam_bios_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsicam_bios_param(struct block_device *bdev, sector_t capacity, int *ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff816309c0)
Location: drivers/scsi/scsicam.c:67
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_getgeo
```
**Symbols:**

```
ffffffff816309c0-ffffffff81630b41: scsicam_bios_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int scsicam_bios_param(struct block_device *bdev, sector_t capacity, int *ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff81645720)
Location: drivers/scsi/scsicam.c:67
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_getgeo
```
**Symbols:**

```
ffffffff81645720-ffffffff816458db: scsicam_bios_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scsicam_bios_param(struct block_device *bdev, sector_t capacity, int *ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff816ae6f0)
Location: drivers/scsi/scsicam.c:68
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_getgeo
```
**Symbols:**

```
ffffffff816ae6f0-ffffffff816ae8ab: scsicam_bios_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int scsicam_bios_param(struct block_device *bdev, sector_t capacity, int *ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff816eaad0)
Location: drivers/scsi/scsicam.c:68
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_getgeo
```
**Symbols:**

```
ffffffff816eaad0-ffffffff816eac5a: scsicam_bios_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int scsicam_bios_param(struct block_device *bdev, sector_t capacity, int *ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff8170e580)
Location: drivers/scsi/scsicam.c:68
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_getgeo
```
**Symbols:**

```
ffffffff8170e580-ffffffff8170e70a: scsicam_bios_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int scsicam_bios_param(struct block_device *bdev, sector_t capacity, int *ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff81749d40)
Location: drivers/scsi/scsicam.c:68
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_getgeo
```
**Symbols:**

```
ffffffff81749d40-ffffffff81749eca: scsicam_bios_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int scsicam_bios_param(struct block_device *bdev, sector_t capacity, int *ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff8176de90)
Location: drivers/scsi/scsicam.c:68
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_getgeo
```
**Symbols:**

```
ffffffff8176de90-ffffffff8176e01a: scsicam_bios_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int scsicam_bios_param(struct block_device *bdev, sector_t capacity, int *ip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff81830490)
Location: drivers/scsi/scsicam.c:219
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_getgeo
```
**Symbols:**

```
ffffffff81830490-ffffffff818305da: scsicam_bios_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int scsicam_bios_param(struct block_device *bdev, sector_t capacity, int *ip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff81841100)
Location: drivers/scsi/scsicam.c:219
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_getgeo
```
**Symbols:**

```
ffffffff81841100-ffffffff81841249: scsicam_bios_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int scsicam_bios_param(struct block_device *bdev, sector_t capacity, int *ip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff818242f0)
Location: drivers/scsi/scsicam.c:220
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_getgeo
```
**Symbols:**

```
ffffffff818242f0-ffffffff81824438: scsicam_bios_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int scsicam_bios_param(struct block_device *bdev, sector_t capacity, int *ip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff818afb30)
Location: drivers/scsi/scsicam.c:220
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_getgeo
```
**Symbols:**

```
ffffffff818afb30-ffffffff818afc78: scsicam_bios_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int scsicam_bios_param(struct block_device *bdev, sector_t capacity, int *ip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff819faab0)
Location: drivers/scsi/scsicam.c:218
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_getgeo
```
**Symbols:**

```
ffffffff819faab0-ffffffff819fac4a: scsicam_bios_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int scsicam_bios_param(struct block_device *bdev, sector_t capacity, int *ip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff81b78ad0)
Location: drivers/scsi/scsicam.c:218
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_getgeo
```
**Symbols:**

```
ffffffff81b78ad0-ffffffff81b78c6a: scsicam_bios_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int scsicam_bios_param(struct block_device *bdev, sector_t capacity, int *ip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff81bcc760)
Location: drivers/scsi/scsicam.c:218
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_getgeo
```
**Symbols:**

```
ffffffff81bcc760-ffffffff81bcc8fa: scsicam_bios_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int scsicam_bios_param(struct block_device *bdev, sector_t capacity, int *ip);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff81c21390)
Location: drivers/scsi/scsicam.c:218
Inline: True
Direct callers:
  - drivers/scsi/sd.c:sd_getgeo
```
**Symbols:**

```
ffffffff81c21390-ffffffff81c2152a: scsicam_bios_param (STB_GLOBAL)
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
int scsicam_bios_param(struct block_device *bdev, sector_t capacity, int *ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffff800010970d88)
Location: drivers/scsi/scsicam.c:68
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_getgeo
```
**Symbols:**

```
ffff800010970d88-ffff800010970f34: scsicam_bios_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsicam_bios_param(struct block_device *bdev, sector_t capacity, int *ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (c0a459b0)
Location: drivers/scsi/scsicam.c:68
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_getgeo
```
**Symbols:**

```
c0a459b0-c0a45bb0: scsicam_bios_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsicam_bios_param(struct block_device *bdev, sector_t capacity, int *ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (c000000000a2a170)
Location: drivers/scsi/scsicam.c:68
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_getgeo
```
**Symbols:**

```
c000000000a2a170-c000000000a2a3bc: scsicam_bios_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsicam_bios_param(struct block_device *bdev, sector_t capacity, int *ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffe0005da420)
Location: drivers/scsi/scsicam.c:68
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_getgeo
```
**Symbols:**

```
ffffffe0005da420-ffffffe0005da578: scsicam_bios_param (STB_GLOBAL)
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
int scsicam_bios_param(struct block_device *bdev, sector_t capacity, int *ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff81722580)
Location: drivers/scsi/scsicam.c:68
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_getgeo
```
**Symbols:**

```
ffffffff81722580-ffffffff8172270a: scsicam_bios_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int scsicam_bios_param(struct block_device *bdev, sector_t capacity, int *ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff816fb9b0)
Location: drivers/scsi/scsicam.c:68
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_getgeo
```
**Symbols:**

```
ffffffff816fb9b0-ffffffff816fbb3a: scsicam_bios_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int scsicam_bios_param(struct block_device *bdev, sector_t capacity, int *ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff81761350)
Location: drivers/scsi/scsicam.c:68
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_getgeo
```
**Symbols:**

```
ffffffff81761350-ffffffff817614da: scsicam_bios_param (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int scsicam_bios_param(struct block_device *bdev, sector_t capacity, int *ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsicam.c (ffffffff8177c9b0)
Location: drivers/scsi/scsicam.c:68
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_getgeo
```
**Symbols:**

```
ffffffff8177c9b0-ffffffff8177cb3a: scsicam_bios_param (STB_GLOBAL)
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
