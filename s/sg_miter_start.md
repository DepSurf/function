# Function: <code>sg_miter_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter *miter, struct scatterlist *sgl, unsigned int nents, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff813fa150)
Location: lib/scatterlist.c:484
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_copy_buffer
```
**Symbols:**

```
ffffffff813fa150-ffffffff813fa1c3: sg_miter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter *miter, struct scatterlist *sgl, unsigned int nents, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814411a0)
Location: lib/scatterlist.c:484
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff814411a0-ffffffff81441213: sg_miter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter *miter, struct scatterlist *sgl, unsigned int nents, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8145e340)
Location: lib/scatterlist.c:484
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff8145e340-ffffffff8145e3b3: sg_miter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter *miter, struct scatterlist *sgl, unsigned int nents, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814634b0)
Location: lib/scatterlist.c:484
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff814634b0-ffffffff8146350e: sg_miter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter *miter, struct scatterlist *sgl, unsigned int nents, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8148f3c0)
Location: lib/scatterlist.c:525
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff8148f3c0-ffffffff8148f41d: sg_miter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter *miter, struct scatterlist *sgl, unsigned int nents, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814c3fd0)
Location: lib/scatterlist.c:640
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff814c3fd0-ffffffff814c402d: sg_miter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter *miter, struct scatterlist *sgl, unsigned int nents, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814d86d0)
Location: lib/scatterlist.c:640
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff814d86d0-ffffffff814d872d: sg_miter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void sg_miter_start(struct sg_mapping_iter *miter, struct scatterlist *sgl, unsigned int nents, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/scatterlist.c (0)
Location: lib/scatterlist.c:674
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff81505188-ffffffff8150519b: sg_miter_start.cold (STB_LOCAL)
ffffffff815045d0-ffffffff8150462e: sg_miter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter *miter, struct scatterlist *sgl, unsigned int nents, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815225c0)
Location: lib/scatterlist.c:674
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff815225c0-ffffffff81522619: sg_miter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void sg_miter_start(struct sg_mapping_iter *miter, struct scatterlist *sgl, unsigned int nents, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81585e9b)
Location: lib/scatterlist.c:674
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
Direct callers:
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff81585920-ffffffff81585969: sg_miter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void sg_miter_start(struct sg_mapping_iter *miter, struct scatterlist *sgl, unsigned int nents, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a2f7b)
Location: lib/scatterlist.c:755
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
Direct callers:
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff815a2a00-ffffffff815a2a49: sg_miter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void sg_miter_start(struct sg_mapping_iter *miter, struct scatterlist *sgl, unsigned int nents, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a9eab)
Location: lib/scatterlist.c:755
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
Direct callers:
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff815a9930-ffffffff815a9979: sg_miter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void sg_miter_start(struct sg_mapping_iter *miter, struct scatterlist *sgl, unsigned int nents, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81612f6b)
Location: lib/scatterlist.c:786
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
Direct callers:
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff81612b70-ffffffff81612bb9: sg_miter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void sg_miter_start(struct sg_mapping_iter *miter, struct scatterlist *sgl, unsigned int nents, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff816dfbdb)
Location: lib/scatterlist.c:786
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
Direct callers:
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff816df280-ffffffff816df2f1: sg_miter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void sg_miter_start(struct sg_mapping_iter *miter, struct scatterlist *sgl, unsigned int nents, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff817cf9ab)
Location: lib/scatterlist.c:796
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
Direct callers:
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff817cf4a0-ffffffff817cf4fa: sg_miter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter *miter, struct scatterlist *sgl, unsigned int nents, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8180d950)
Location: lib/scatterlist.c:798
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff8180d950-ffffffff8180d9aa: sg_miter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter *miter, struct scatterlist *sgl, unsigned int nents, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81853600)
Location: lib/scatterlist.c:800
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/crypto/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/crypto/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff81853600-ffffffff8185365a: sg_miter_start (STB_GLOBAL)
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
void sg_miter_start(struct sg_mapping_iter *miter, struct scatterlist *sgl, unsigned int nents, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffff80001062c240)
Location: lib/scatterlist.c:674
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/mmc/host/mmci.c:mmci_start_data
```
**Symbols:**

```
ffff80001062c240-ffff80001062c274: sg_miter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter *miter, struct scatterlist *sgl, unsigned int nents, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c07d2c34)
Location: lib/scatterlist.c:674
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/usb/musb/musb_host.c:musb_host_rx
  - drivers/mmc/host/mmci.c:mmci_start_data
  - drivers/mmc/host/sdhci.c:sdhci_prepare_data
```
**Symbols:**

```
c07d2c34-c07d2c90: sg_miter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter *miter, struct scatterlist *sgl, unsigned int nents, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c0000000007cebc0)
Location: lib/scatterlist.c:674
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
c0000000007cebc0-c0000000007cec40: sg_miter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter *miter, struct scatterlist *sgl, unsigned int nents, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffe00045c43c)
Location: lib/scatterlist.c:674
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffe00045c43c-ffffffe00045c488: sg_miter_start (STB_GLOBAL)
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
void sg_miter_start(struct sg_mapping_iter *miter, struct scatterlist *sgl, unsigned int nents, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8151aba0)
Location: lib/scatterlist.c:674
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff8151aba0-ffffffff8151abf9: sg_miter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter *miter, struct scatterlist *sgl, unsigned int nents, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8150ae90)
Location: lib/scatterlist.c:674
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff8150ae90-ffffffff8150aee9: sg_miter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter *miter, struct scatterlist *sgl, unsigned int nents, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81516c30)
Location: lib/scatterlist.c:674
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff81516c30-ffffffff81516c89: sg_miter_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sg_miter_start(struct sg_mapping_iter *miter, struct scatterlist *sgl, unsigned int nents, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815303c0)
Location: lib/scatterlist.c:674
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff815303c0-ffffffff81530419: sg_miter_start (STB_GLOBAL)
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
