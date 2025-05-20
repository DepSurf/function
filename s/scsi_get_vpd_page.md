# Function: <code>scsi_get_vpd_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int scsi_get_vpd_page(struct scsi_device *sdev, u8 page, unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815a64f0)
Location: drivers/scsi/scsi.c:731
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff815a64f0-ffffffff815a65a7: scsi_get_vpd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int scsi_get_vpd_page(struct scsi_device *sdev, u8 page, unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff815fe780)
Location: drivers/scsi/scsi.c:731
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
```
**Symbols:**

```
ffffffff815fe780-ffffffff815fe83e: scsi_get_vpd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int scsi_get_vpd_page(struct scsi_device *sdev, u8 page, unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8162ddc0)
Location: drivers/scsi/scsi.c:734
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff8162ddc0-ffffffff8162de7e: scsi_get_vpd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int scsi_get_vpd_page(struct scsi_device *sdev, u8 page, unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816431e0)
Location: drivers/scsi/scsi.c:375
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff816431e0-ffffffff81643295: scsi_get_vpd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int scsi_get_vpd_page(struct scsi_device *sdev, u8 page, unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816ac1f0)
Location: drivers/scsi/scsi.c:375
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff816ac1f0-ffffffff816ac2a5: scsi_get_vpd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int scsi_get_vpd_page(struct scsi_device *sdev, u8 page, unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816e8720)
Location: drivers/scsi/scsi.c:375
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff816e8720-ffffffff816e87dc: scsi_get_vpd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int scsi_get_vpd_page(struct scsi_device *sdev, u8 page, unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8170c220)
Location: drivers/scsi/scsi.c:375
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff8170c220-ffffffff8170c2dc: scsi_get_vpd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int scsi_get_vpd_page(struct scsi_device *sdev, u8 page, unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81747950)
Location: drivers/scsi/scsi.c:355
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff81747950-ffffffff81747a04: scsi_get_vpd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int scsi_get_vpd_page(struct scsi_device *sdev, u8 page, unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8176baa0)
Location: drivers/scsi/scsi.c:355
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff8176baa0-ffffffff8176bb54: scsi_get_vpd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int scsi_get_vpd_page(struct scsi_device *sdev, u8 page, unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8182dd70)
Location: drivers/scsi/scsi.c:341
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_write_same
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
```
**Symbols:**

```
ffffffff8182dd70-ffffffff8182de21: scsi_get_vpd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int scsi_get_vpd_page(struct scsi_device *sdev, u8 page, unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8183edb0)
Location: drivers/scsi/scsi.c:341
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_read_write_same
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
```
**Symbols:**

```
ffffffff8183edb0-ffffffff8183ee61: scsi_get_vpd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int scsi_get_vpd_page(struct scsi_device *sdev, u8 page, unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81821fc0)
Location: drivers/scsi/scsi.c:354
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff81821fc0-ffffffff81822071: scsi_get_vpd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int scsi_get_vpd_page(struct scsi_device *sdev, u8 page, unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff818ac900)
Location: drivers/scsi/scsi.c:347
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_read_block_characteristics
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff818ac900-ffffffff818ac9b1: scsi_get_vpd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int scsi_get_vpd_page(struct scsi_device *sdev, u8 page, unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi.c (0)
Location: drivers/scsi/scsi.c:362
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
```
**Symbols:**

```
ffffffff81ed4cca-ffffffff81ed4d14: scsi_get_vpd_page.cold (STB_LOCAL)
ffffffff819f7f10-ffffffff819f7fd4: scsi_get_vpd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int scsi_get_vpd_page(struct scsi_device *sdev, u8 page, unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi.c (0)
Location: drivers/scsi/scsi.c:362
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
```
**Symbols:**

```
ffffffff8209b9d8-ffffffff8209b9f3: scsi_get_vpd_page.cold (STB_LOCAL)
ffffffff81b75830-ffffffff81b7593a: scsi_get_vpd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int scsi_get_vpd_page(struct scsi_device *sdev, u8 page, unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi.c (0)
Location: drivers/scsi/scsi.c:372
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
```
**Symbols:**

```
ffffffff8211c86f-ffffffff8211c88a: scsi_get_vpd_page.cold (STB_LOCAL)
ffffffff81bc9160-ffffffff81bc926a: scsi_get_vpd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int scsi_get_vpd_page(struct scsi_device *sdev, u8 page, unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/scsi/scsi.c (0)
Location: drivers/scsi/scsi.c:390
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_read_cpr
  - drivers/scsi/sd_zbc.c:sd_zbc_check_zoned_characteristics
```
**Symbols:**

```
ffffffff821fa6fe-ffffffff821fa719: scsi_get_vpd_page.cold (STB_LOCAL)
ffffffff81c1d590-ffffffff81c1d69a: scsi_get_vpd_page (STB_GLOBAL)
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
int scsi_get_vpd_page(struct scsi_device *sdev, u8 page, unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffff80001096da18)
Location: drivers/scsi/scsi.c:355
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_read_block_limits
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffff80001096da18-ffff80001096dae4: scsi_get_vpd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int scsi_get_vpd_page(struct scsi_device *sdev, u8 page, unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c0a434ac)
Location: drivers/scsi/scsi.c:355
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
c0a434ac-c0a43584: scsi_get_vpd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int scsi_get_vpd_page(struct scsi_device *sdev, u8 page, unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (c000000000a26d40)
Location: drivers/scsi/scsi.c:355
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
c000000000a26d40-c000000000a26e80: scsi_get_vpd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int scsi_get_vpd_page(struct scsi_device *sdev, u8 page, unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffe0005d8310)
Location: drivers/scsi/scsi.c:355
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffe0005d8310-ffffffe0005d83d2: scsi_get_vpd_page (STB_GLOBAL)
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
int scsi_get_vpd_page(struct scsi_device *sdev, u8 page, unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff81720190)
Location: drivers/scsi/scsi.c:355
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff81720190-ffffffff81720244: scsi_get_vpd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int scsi_get_vpd_page(struct scsi_device *sdev, u8 page, unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff816f95c0)
Location: drivers/scsi/scsi.c:355
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff816f95c0-ffffffff816f9674: scsi_get_vpd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int scsi_get_vpd_page(struct scsi_device *sdev, u8 page, unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8175ef60)
Location: drivers/scsi/scsi.c:355
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff8175ef60-ffffffff8175f014: scsi_get_vpd_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int scsi_get_vpd_page(struct scsi_device *sdev, u8 page, unsigned char *buf, int buf_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi.c (ffffffff8177a5c0)
Location: drivers/scsi/scsi.c:355
Inline: False
Direct callers:
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd.c:sd_revalidate_disk
  - drivers/scsi/sd_zbc.c:sd_zbc_read_zones
```
**Symbols:**

```
ffffffff8177a5c0-ffffffff8177a674: scsi_get_vpd_page (STB_GLOBAL)
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
