# Function: <code>cdrom_read_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8160120c)
Location: drivers/cdrom/cdrom.c:2082
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81660f9c)
Location: drivers/cdrom/cdrom.c:2092
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8168ed8c)
Location: drivers/cdrom/cdrom.c:2092
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cdrom_read_block(struct cdrom_device_info *cdi, struct packet_command *cgc, int lba, int nblocks, int format, int blksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff816a1270)
Location: drivers/cdrom/cdrom.c:2090
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
```
**Symbols:**

```
ffffffff816a1270-ffffffff816a12fc: cdrom_read_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cdrom_read_block(struct cdrom_device_info *cdi, struct packet_command *cgc, int lba, int nblocks, int format, int blksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8170c4b0)
Location: drivers/cdrom/cdrom.c:2090
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
```
**Symbols:**

```
ffffffff8170c4b0-ffffffff8170c54b: cdrom_read_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cdrom_read_block(struct cdrom_device_info *cdi, struct packet_command *cgc, int lba, int nblocks, int format, int blksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8174b830)
Location: drivers/cdrom/cdrom.c:2087
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
```
**Symbols:**

```
ffffffff8174b830-ffffffff8174b8a6: cdrom_read_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cdrom_read_block(struct cdrom_device_info *cdi, struct packet_command *cgc, int lba, int nblocks, int format, int blksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8176fa50)
Location: drivers/cdrom/cdrom.c:2087
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
```
**Symbols:**

```
ffffffff8176fa50-ffffffff8176fac6: cdrom_read_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cdrom_read_block(struct cdrom_device_info *cdi, struct packet_command *cgc, int lba, int nblocks, int format, int blksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817ad8e0)
Location: drivers/cdrom/cdrom.c:2088
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
```
**Symbols:**

```
ffffffff817ad8e0-ffffffff817ad971: cdrom_read_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cdrom_read_block(struct cdrom_device_info *cdi, struct packet_command *cgc, int lba, int nblocks, int format, int blksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817ddbc0)
Location: drivers/cdrom/cdrom.c:2095
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
```
**Symbols:**

```
ffffffff817ddbc0-ffffffff817ddc51: cdrom_read_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cdrom_read_block(struct cdrom_device_info *cdi, struct packet_command *cgc, int lba, int nblocks, int format, int blksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818ac7c0)
Location: drivers/cdrom/cdrom.c:2098
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
```
**Symbols:**

```
ffffffff818ac7c0-ffffffff818ac839: cdrom_read_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cdrom_read_block(struct cdrom_device_info *cdi, struct packet_command *cgc, int lba, int nblocks, int format, int blksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff818bb400)
Location: drivers/cdrom/cdrom.c:2081
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
```
**Symbols:**

```
ffffffff818bb400-ffffffff818bb479: cdrom_read_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cdrom_read_block(struct cdrom_device_info *cdi, struct packet_command *cgc, int lba, int nblocks, int format, int blksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8189e480)
Location: drivers/cdrom/cdrom.c:2081
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
```
**Symbols:**

```
ffffffff8189e480-ffffffff8189e4fc: cdrom_read_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cdrom_read_block(struct cdrom_device_info *cdi, struct packet_command *cgc, int lba, int nblocks, int format, int blksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81931770)
Location: drivers/cdrom/cdrom.c:2081
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
```
**Symbols:**

```
ffffffff81931770-ffffffff819317ec: cdrom_read_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int cdrom_read_block(struct cdrom_device_info *cdi, struct packet_command *cgc, int lba, int nblocks, int format, int blksize);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81a8c324)
Location: drivers/cdrom/cdrom.c:2085
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
```
**Symbols:**

```
ffffffff81a888d0-ffffffff81a88960: cdrom_read_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int cdrom_read_block(struct cdrom_device_info *cdi, struct packet_command *cgc, int lba, int nblocks, int format, int blksize);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81c0d2c2)
Location: drivers/cdrom/cdrom.c:2085
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
```
**Symbols:**

```
ffffffff81c09700-ffffffff81c09790: cdrom_read_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cdrom_read_block(struct cdrom_device_info *cdi, struct packet_command *cgc, int lba, int nblocks, int format, int blksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81c70630)
Location: drivers/cdrom/cdrom.c:2068
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
```
**Symbols:**

```
ffffffff81c70630-ffffffff81c706c0: cdrom_read_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cdrom_read_block(struct cdrom_device_info *cdi, struct packet_command *cgc, int lba, int nblocks, int format, int blksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81d24ee0)
Location: drivers/cdrom/cdrom.c:2068
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
```
**Symbols:**

```
ffffffff81d24ee0-ffffffff81d24f70: cdrom_read_block (STB_LOCAL)
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
int cdrom_read_block(struct cdrom_device_info *cdi, struct packet_command *cgc, int lba, int nblocks, int format, int blksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffff800010a0b1e0)
Location: drivers/cdrom/cdrom.c:2095
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
```
**Symbols:**

```
ffff800010a0b1e0-ffff800010a0b29c: cdrom_read_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cdrom_read_block(struct cdrom_device_info *cdi, struct packet_command *cgc, int lba, int nblocks, int format, int blksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (c0ae2dfc)
Location: drivers/cdrom/cdrom.c:2095
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
```
**Symbols:**

```
c0ae2dfc-c0ae2ea4: cdrom_read_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cdrom_read_block(struct cdrom_device_info *cdi, struct packet_command *cgc, int lba, int nblocks, int format, int blksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (c000000000ac0f10)
Location: drivers/cdrom/cdrom.c:2095
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
```
**Symbols:**

```
c000000000ac0f10-c000000000ac105c: cdrom_read_block (STB_LOCAL)
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
In drivers/cdrom/cdrom.c (ffffffe0006348c4)
Location: drivers/cdrom/cdrom.c:2095
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
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
int cdrom_read_block(struct cdrom_device_info *cdi, struct packet_command *cgc, int lba, int nblocks, int format, int blksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81795fa0)
Location: drivers/cdrom/cdrom.c:2095
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
```
**Symbols:**

```
ffffffff81795fa0-ffffffff81796031: cdrom_read_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cdrom_read_block(struct cdrom_device_info *cdi, struct packet_command *cgc, int lba, int nblocks, int format, int blksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81787c70)
Location: drivers/cdrom/cdrom.c:2095
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
```
**Symbols:**

```
ffffffff81787c70-ffffffff81787d01: cdrom_read_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cdrom_read_block(struct cdrom_device_info *cdi, struct packet_command *cgc, int lba, int nblocks, int format, int blksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817d2a40)
Location: drivers/cdrom/cdrom.c:2095
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
```
**Symbols:**

```
ffffffff817d2a40-ffffffff817d2ad1: cdrom_read_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cdrom_read_block(struct cdrom_device_info *cdi, struct packet_command *cgc, int lba, int nblocks, int format, int blksize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817ecce0)
Location: drivers/cdrom/cdrom.c:2095
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:mmc_ioctl_cdrom_read_data
  - drivers/cdrom/cdrom.c:cdrom_read_cdda_old
```
**Symbols:**

```
ffffffff817ecce0-ffffffff817ecd71: cdrom_read_block (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
