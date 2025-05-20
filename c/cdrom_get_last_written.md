# Function: <code>cdrom_get_last_written</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cdrom_get_last_written(struct cdrom_device_info *cdi, long int *last_written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81600040)
Location: drivers/cdrom/cdrom.c:2816
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
```
**Symbols:**

```
ffffffff81600040-ffffffff8160018b: cdrom_get_last_written (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cdrom_get_last_written(struct cdrom_device_info *cdi, long int *last_written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8165fe70)
Location: drivers/cdrom/cdrom.c:2826
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
```
**Symbols:**

```
ffffffff8165fe70-ffffffff8165ffbd: cdrom_get_last_written (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cdrom_get_last_written(struct cdrom_device_info *cdi, long int *last_written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8168dc60)
Location: drivers/cdrom/cdrom.c:2826
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
```
**Symbols:**

```
ffffffff8168dc60-ffffffff8168ddad: cdrom_get_last_written (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cdrom_get_last_written(struct cdrom_device_info *cdi, long int *last_written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff816a2ee0)
Location: drivers/cdrom/cdrom.c:2832
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
```
**Symbols:**

```
ffffffff816a2ee0-ffffffff816a3027: cdrom_get_last_written (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cdrom_get_last_written(struct cdrom_device_info *cdi, long int *last_written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8170e1e0)
Location: drivers/cdrom/cdrom.c:2832
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
```
**Symbols:**

```
ffffffff8170e1e0-ffffffff8170e32d: cdrom_get_last_written (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cdrom_get_last_written(struct cdrom_device_info *cdi, long int *last_written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8174d3a0)
Location: drivers/cdrom/cdrom.c:2829
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
```
**Symbols:**

```
ffffffff8174d3a0-ffffffff8174d4f3: cdrom_get_last_written (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cdrom_get_last_written(struct cdrom_device_info *cdi, long int *last_written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817715d0)
Location: drivers/cdrom/cdrom.c:2832
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
```
**Symbols:**

```
ffffffff817715d0-ffffffff81771723: cdrom_get_last_written (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cdrom_get_last_written(struct cdrom_device_info *cdi, long int *last_written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817af9a0)
Location: drivers/cdrom/cdrom.c:2833
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
```
**Symbols:**

```
ffffffff817af9a0-ffffffff817afaec: cdrom_get_last_written (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cdrom_get_last_written(struct cdrom_device_info *cdi, long int *last_written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817dfca0)
Location: drivers/cdrom/cdrom.c:2840
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
```
**Symbols:**

```
ffffffff817dfca0-ffffffff817dfe09: cdrom_get_last_written (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cdrom_get_last_written(struct cdrom_device_info *cdi, long int *last_written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818ae740)
Location: drivers/cdrom/cdrom.c:2857
Inline: False
Direct callers:
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:cdrom_get_next_writable
```
**Symbols:**

```
ffffffff818ae740-ffffffff818ae8ab: cdrom_get_last_written (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cdrom_get_last_written(struct cdrom_device_info *cdi, long int *last_written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818bd4d0)
Location: drivers/cdrom/cdrom.c:2840
Inline: False
Direct callers:
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:cdrom_get_next_writable
```
**Symbols:**

```
ffffffff818bd4d0-ffffffff818bd63b: cdrom_get_last_written (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cdrom_get_last_written(struct cdrom_device_info *cdi, long int *last_written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818a0120)
Location: drivers/cdrom/cdrom.c:2840
Inline: False
Direct callers:
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
```
**Symbols:**

```
ffffffff818a0120-ffffffff818a0291: cdrom_get_last_written (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cdrom_get_last_written(struct cdrom_device_info *cdi, long int *last_written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81934930)
Location: drivers/cdrom/cdrom.c:2785
Inline: False
Direct callers:
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
```
**Symbols:**

```
ffffffff81934930-ffffffff81934aa1: cdrom_get_last_written (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cdrom_get_last_written(struct cdrom_device_info *cdi, long int *last_written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81a8c790)
Location: drivers/cdrom/cdrom.c:2824
Inline: False
Direct callers:
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
```
**Symbols:**

```
ffffffff81a8c790-ffffffff81a8c95a: cdrom_get_last_written (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cdrom_get_last_written(struct cdrom_device_info *cdi, long int *last_written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81c0d680)
Location: drivers/cdrom/cdrom.c:2824
Inline: False
Direct callers:
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
```
**Symbols:**

```
ffffffff81c0d680-ffffffff81c0d84a: cdrom_get_last_written (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cdrom_get_last_written(struct cdrom_device_info *cdi, long int *last_written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81c75b00)
Location: drivers/cdrom/cdrom.c:2810
Inline: False
Direct callers:
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
```
**Symbols:**

```
ffffffff81c75b00-ffffffff81c75cca: cdrom_get_last_written (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cdrom_get_last_written(struct cdrom_device_info *cdi, long int *last_written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81d2a500)
Location: drivers/cdrom/cdrom.c:2810
Inline: False
Direct callers:
  - drivers/scsi/sr.c:get_sectorsize
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
```
**Symbols:**

```
ffffffff81d2a500-ffffffff81d2a6ca: cdrom_get_last_written (STB_GLOBAL)
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
int cdrom_get_last_written(struct cdrom_device_info *cdi, long int *last_written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffff800010a0c760)
Location: drivers/cdrom/cdrom.c:2840
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
```
**Symbols:**

```
ffff800010a0c760-ffff800010a0c910: cdrom_get_last_written (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cdrom_get_last_written(struct cdrom_device_info *cdi, long int *last_written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (c0ae4504)
Location: drivers/cdrom/cdrom.c:2840
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
```
**Symbols:**

```
c0ae4504-c0ae46bc: cdrom_get_last_written (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cdrom_get_last_written(struct cdrom_device_info *cdi, long int *last_written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (c000000000ac3d00)
Location: drivers/cdrom/cdrom.c:2840
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
```
**Symbols:**

```
c000000000ac3d00-c000000000ac3f5c: cdrom_get_last_written (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cdrom_get_last_written(struct cdrom_device_info *cdi, long int *last_written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffe000633ca2)
Location: drivers/cdrom/cdrom.c:2840
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
```
**Symbols:**

```
ffffffe000633ca2-ffffffe000633ea6: cdrom_get_last_written (STB_GLOBAL)
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
int cdrom_get_last_written(struct cdrom_device_info *cdi, long int *last_written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81798080)
Location: drivers/cdrom/cdrom.c:2840
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
```
**Symbols:**

```
ffffffff81798080-ffffffff817981e9: cdrom_get_last_written (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cdrom_get_last_written(struct cdrom_device_info *cdi, long int *last_written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81789d50)
Location: drivers/cdrom/cdrom.c:2840
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
```
**Symbols:**

```
ffffffff81789d50-ffffffff81789eb9: cdrom_get_last_written (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cdrom_get_last_written(struct cdrom_device_info *cdi, long int *last_written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817d4b20)
Location: drivers/cdrom/cdrom.c:2840
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
```
**Symbols:**

```
ffffffff817d4b20-ffffffff817d4c89: cdrom_get_last_written (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cdrom_get_last_written(struct cdrom_device_info *cdi, long int *last_written);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817eedc0)
Location: drivers/cdrom/cdrom.c:2840
Inline: False
Direct callers:
  - drivers/scsi/sr.c:sr_block_revalidate_disk
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_last_written
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_next_writable
```
**Symbols:**

```
ffffffff817eedc0-ffffffff817eef29: cdrom_get_last_written (STB_GLOBAL)
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
