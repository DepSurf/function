# Function: <code>sd_zbc_do_report_zones</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sd_zbc_do_report_zones(struct scsi_disk *sdkp, unsigned char *buf, unsigned int buflen, sector_t lba, bool partial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81725290)
Location: drivers/scsi/sd_zbc.c:78
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffffffff81725290-ffffffff81725425: sd_zbc_do_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sd_zbc_do_report_zones(struct scsi_disk *sdkp, unsigned char *buf, unsigned int buflen, sector_t lba, bool partial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81760900)
Location: drivers/scsi/sd_zbc.c:66
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffffffff81760900-ffffffff81760a70: sd_zbc_do_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sd_zbc_do_report_zones(struct scsi_disk *sdkp, unsigned char *buf, unsigned int buflen, sector_t lba, bool partial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff817848a0)
Location: drivers/scsi/sd_zbc.c:66
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffffffff817848a0-ffffffff81784a10: sd_zbc_do_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sd_zbc_do_report_zones(struct scsi_disk *sdkp, unsigned char *buf, unsigned int buflen, sector_t lba, bool partial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81848580)
Location: drivers/scsi/sd_zbc.c:92
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_capacity
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffffffff81848580-ffffffff8184873c: sd_zbc_do_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sd_zbc_do_report_zones(struct scsi_disk *sdkp, unsigned char *buf, unsigned int buflen, sector_t lba, bool partial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81858a70)
Location: drivers/scsi/sd_zbc.c:93
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_capacity
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffffffff81858a70-ffffffff81858c2c: sd_zbc_do_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sd_zbc_do_report_zones(struct scsi_disk *sdkp, unsigned char *buf, unsigned int buflen, sector_t lba, bool partial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff8183b9f0)
Location: drivers/scsi/sd_zbc.c:93
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffffffff8183b9f0-ffffffff8183bbae: sd_zbc_do_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sd_zbc_do_report_zones(struct scsi_disk *sdkp, unsigned char *buf, unsigned int buflen, sector_t lba, bool partial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff818c80c0)
Location: drivers/scsi/sd_zbc.c:93
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffffffff818c80c0-ffffffff818c8282: sd_zbc_do_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sd_zbc_do_report_zones(struct scsi_disk *sdkp, unsigned char *buf, unsigned int buflen, sector_t lba, bool partial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81a14f20)
Location: drivers/scsi/sd_zbc.c:141
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffffffff81a14f20-ffffffff81a150cc: sd_zbc_do_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sd_zbc_do_report_zones(struct scsi_disk *sdkp, unsigned char *buf, unsigned int buflen, sector_t lba, bool partial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81b95b70)
Location: drivers/scsi/sd_zbc.c:144
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffffffff81b95b70-ffffffff81b95d1c: sd_zbc_do_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sd_zbc_do_report_zones(struct scsi_disk *sdkp, unsigned char *buf, unsigned int buflen, sector_t lba, bool partial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81bec110)
Location: drivers/scsi/sd_zbc.c:144
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffffffff81bec110-ffffffff81bec2da: sd_zbc_do_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sd_zbc_do_report_zones(struct scsi_disk *sdkp, unsigned char *buf, unsigned int buflen, sector_t lba, bool partial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81c417d0)
Location: drivers/scsi/sd_zbc.c:144
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_update_wp_offset_workfn
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffffffff81c417d0-ffffffff81c41997: sd_zbc_do_report_zones (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffff80001098b080)
Location: drivers/scsi/sd_zbc.c:66
Inline: True
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffff80001098b080-ffff80001098b21c: sd_zbc_do_report_zones.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sd_zbc_do_report_zones(struct scsi_disk *sdkp, unsigned char *buf, unsigned int buflen, sector_t lba, bool partial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (c0a5d320)
Location: drivers/scsi/sd_zbc.c:66
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
c0a5d320-c0a5d4d8: sd_zbc_do_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sd_zbc_do_report_zones(struct scsi_disk *sdkp, unsigned char *buf, unsigned int buflen, sector_t lba, bool partial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (c000000000a4bbc0)
Location: drivers/scsi/sd_zbc.c:66
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
c000000000a4bbc0-c000000000a4bdb4: sd_zbc_do_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sd_zbc_do_report_zones(struct scsi_disk *sdkp, unsigned char *buf, unsigned int buflen, sector_t lba, bool partial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffe0005ef45c)
Location: drivers/scsi/sd_zbc.c:66
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffffffe0005ef45c-ffffffe0005ef5fe: sd_zbc_do_report_zones (STB_LOCAL)
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
int sd_zbc_do_report_zones(struct scsi_disk *sdkp, unsigned char *buf, unsigned int buflen, sector_t lba, bool partial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81738f90)
Location: drivers/scsi/sd_zbc.c:66
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffffffff81738f90-ffffffff81739100: sd_zbc_do_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sd_zbc_do_report_zones(struct scsi_disk *sdkp, unsigned char *buf, unsigned int buflen, sector_t lba, bool partial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff8171ac30)
Location: drivers/scsi/sd_zbc.c:66
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffffffff8171ac30-ffffffff8171ada0: sd_zbc_do_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sd_zbc_do_report_zones(struct scsi_disk *sdkp, unsigned char *buf, unsigned int buflen, sector_t lba, bool partial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81779720)
Location: drivers/scsi/sd_zbc.c:66
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffffffff81779720-ffffffff81779890: sd_zbc_do_report_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sd_zbc_do_report_zones(struct scsi_disk *sdkp, unsigned char *buf, unsigned int buflen, sector_t lba, bool partial);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/sd_zbc.c (ffffffff81793550)
Location: drivers/scsi/sd_zbc.c:66
Inline: False
Direct callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones
```
**Symbols:**

```
ffffffff81793550-ffffffff817936c0: sd_zbc_do_report_zones (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
