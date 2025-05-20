# Function: <code>sg_miter_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff813fa1d0)
Location: lib/scatterlist.c:609
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_miter_skip
  - lib/scatterlist.c:sg_copy_buffer
```
**Symbols:**

```
ffffffff813fa1d0-ffffffff813fa26c: sg_miter_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81441220)
Location: lib/scatterlist.c:609
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_miter_skip
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff81441220-ffffffff814412ce: sg_miter_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8145e3c0)
Location: lib/scatterlist.c:609
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_miter_skip
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff8145e3c0-ffffffff8145e46e: sg_miter_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81463400)
Location: lib/scatterlist.c:609
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_miter_skip
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff81463400-ffffffff81463470: sg_miter_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8148f310)
Location: lib/scatterlist.c:650
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_miter_skip
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff8148f310-ffffffff8148f380: sg_miter_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814c3f20)
Location: lib/scatterlist.c:765
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_miter_skip
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff814c3f20-ffffffff814c3f90: sg_miter_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814d8610)
Location: lib/scatterlist.c:765
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_miter_skip
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff814d8610-ffffffff814d8686: sg_miter_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void sg_miter_stop(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/scatterlist.c (0)
Location: lib/scatterlist.c:800
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_miter_skip
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff8150519b-ffffffff815051ae: sg_miter_stop.cold (STB_LOCAL)
ffffffff81504630-ffffffff815046ab: sg_miter_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81522b70)
Location: lib/scatterlist.c:800
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_miter_skip
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff81522b70-ffffffff81522be1: sg_miter_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81585bb0)
Location: lib/scatterlist.c:800
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_miter_skip
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff81585bb0-ffffffff81585c21: sg_miter_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a2c90)
Location: lib/scatterlist.c:881
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_miter_skip
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff815a2c90-ffffffff815a2d01: sg_miter_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a9bc0)
Location: lib/scatterlist.c:881
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_miter_skip
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff815a9bc0-ffffffff815a9c31: sg_miter_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81612900)
Location: lib/scatterlist.c:912
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_miter_skip
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff81612900-ffffffff81612951: sg_miter_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff816df480)
Location: lib/scatterlist.c:909
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_miter_skip
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff816df480-ffffffff816df50e: sg_miter_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff817cf6c0)
Location: lib/scatterlist.c:919
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_miter_skip
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff817cf6c0-ffffffff817cf74e: sg_miter_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8180db70)
Location: lib/scatterlist.c:921
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_miter_skip
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff8180db70-ffffffff8180dbfe: sg_miter_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81853820)
Location: lib/scatterlist.c:923
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_miter_skip
  - lib/crypto/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/crypto/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/crypto/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/crypto/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff81853820-ffffffff818538ae: sg_miter_stop (STB_GLOBAL)
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
void sg_miter_stop(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffff80001062c018)
Location: lib/scatterlist.c:800
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_miter_skip
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/mmc/host/mmci.c:mmci_pio_irq
  - drivers/mmc/host/mmci.c:mmci_pio_irq
```
**Symbols:**

```
ffff80001062c018-ffff80001062c090: sg_miter_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c07d2d50)
Location: lib/scatterlist.c:800
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_miter_skip
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/usb/musb/musb_host.c:musb_host_rx
  - drivers/usb/musb/musb_host.c:musb_host_rx
  - drivers/usb/musb/musb_host.c:musb_host_tx
  - drivers/usb/musb/musb_host.c:musb_host_tx
  - drivers/mmc/host/mmci.c:mmci_pio_irq
  - drivers/mmc/host/sdhci.c:sdhci_irq
  - drivers/mmc/host/sdhci.c:sdhci_irq
```
**Symbols:**

```
c07d2d50-c07d2e28: sg_miter_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c0000000007ce840)
Location: lib/scatterlist.c:800
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_miter_skip
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
c0000000007ce840-c0000000007ce8dc: sg_miter_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffe00045c212)
Location: lib/scatterlist.c:800
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_miter_skip
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffe00045c212-ffffffe00045c282: sg_miter_stop (STB_GLOBAL)
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
void sg_miter_stop(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8151b150)
Location: lib/scatterlist.c:800
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_miter_skip
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff8151b150-ffffffff8151b1c1: sg_miter_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8150b440)
Location: lib/scatterlist.c:800
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_miter_skip
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff8150b440-ffffffff8150b4b1: sg_miter_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815171e0)
Location: lib/scatterlist.c:800
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_miter_skip
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff815171e0-ffffffff81517251: sg_miter_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sg_miter_stop(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81530970)
Location: lib/scatterlist.c:800
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/scatterlist.c:sg_miter_skip
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff81530970-ffffffff81530a18: sg_miter_stop (STB_GLOBAL)
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
