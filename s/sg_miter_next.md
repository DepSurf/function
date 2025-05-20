# Function: <code>sg_miter_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
bool sg_miter_next(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff813fa440)
Location: lib/scatterlist.c:572
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_copy_buffer
```
**Symbols:**

```
ffffffff813fa440-ffffffff813fa4dc: sg_miter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool sg_miter_next(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814414b0)
Location: lib/scatterlist.c:572
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff814414b0-ffffffff81441552: sg_miter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool sg_miter_next(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8145e6d0)
Location: lib/scatterlist.c:572
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff8145e6d0-ffffffff8145e77a: sg_miter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool sg_miter_next(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814638e0)
Location: lib/scatterlist.c:572
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff814638e0-ffffffff81463987: sg_miter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool sg_miter_next(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8148f880)
Location: lib/scatterlist.c:613
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff8148f880-ffffffff8148f927: sg_miter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool sg_miter_next(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814c4560)
Location: lib/scatterlist.c:728
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff814c4560-ffffffff814c4607: sg_miter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool sg_miter_next(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814d8c50)
Location: lib/scatterlist.c:728
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff814d8c50-ffffffff814d8cf8: sg_miter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool sg_miter_next(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81504b00)
Location: lib/scatterlist.c:763
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff81504b00-ffffffff81504bab: sg_miter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool sg_miter_next(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81522c40)
Location: lib/scatterlist.c:763
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff81522c40-ffffffff81522ceb: sg_miter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool sg_miter_next(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81585c30)
Location: lib/scatterlist.c:763
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff81585c30-ffffffff81585d36: sg_miter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool sg_miter_next(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a2d10)
Location: lib/scatterlist.c:844
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff815a2d10-ffffffff815a2e16: sg_miter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool sg_miter_next(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a9c40)
Location: lib/scatterlist.c:844
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff815a9c40-ffffffff815a9d45: sg_miter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool sg_miter_next(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81612da0)
Location: lib/scatterlist.c:875
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff81612da0-ffffffff81612e7f: sg_miter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool sg_miter_next(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/scatterlist.c (ffffffff816dfc3a)
Location: lib/scatterlist.c:873
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff816df3f0-ffffffff816df479: sg_miter_next.part.0 (STB_LOCAL)
ffffffff816dfc90-ffffffff816dfd19: sg_miter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool sg_miter_next(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/scatterlist.c (ffffffff817cfa0a)
Location: lib/scatterlist.c:883
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff817cf620-ffffffff817cf6a9: sg_miter_next.part.0 (STB_LOCAL)
ffffffff817cfa70-ffffffff817cfaf6: sg_miter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool sg_miter_next(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/scatterlist.c (ffffffff8180e50d)
Location: lib/scatterlist.c:885
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff8180dad0-ffffffff8180db59: sg_miter_next.part.0 (STB_LOCAL)
ffffffff8180e8f0-ffffffff8180e976: sg_miter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool sg_miter_next(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/scatterlist.c (ffffffff8185418d)
Location: lib/scatterlist.c:887
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/crypto/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/crypto/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/crypto/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/crypto/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/crypto/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/crypto/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff81853780-ffffffff81853809: sg_miter_next.part.0 (STB_LOCAL)
ffffffff81854570-ffffffff818545f6: sg_miter_next (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool sg_miter_next(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffff80001062c7d0)
Location: lib/scatterlist.c:763
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/mmc/host/mmci.c:mmci_pio_irq
```
**Symbols:**

```
ffff80001062c7d0-ffff80001062c898: sg_miter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool sg_miter_next(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c07d3250)
Location: lib/scatterlist.c:763
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/usb/musb/musb_host.c:musb_host_rx
  - drivers/usb/musb/musb_host.c:musb_host_tx
  - drivers/mmc/host/mmci.c:mmci_pio_irq
  - drivers/mmc/host/sdhci.c:sdhci_irq
  - drivers/mmc/host/sdhci.c:sdhci_irq
```
**Symbols:**

```
c07d3250-c07d32f8: sg_miter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool sg_miter_next(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c0000000007cf370)
Location: lib/scatterlist.c:763
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
c0000000007cf370-c0000000007cf45c: sg_miter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool sg_miter_next(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffe00045c8fc)
Location: lib/scatterlist.c:763
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffe00045c8fc-ffffffe00045c99a: sg_miter_next (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool sg_miter_next(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8151b220)
Location: lib/scatterlist.c:763
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff8151b220-ffffffff8151b2cb: sg_miter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool sg_miter_next(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8150b510)
Location: lib/scatterlist.c:763
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff8150b510-ffffffff8150b5bb: sg_miter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool sg_miter_next(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815172b0)
Location: lib/scatterlist.c:763
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff815172b0-ffffffff8151735b: sg_miter_next (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool sg_miter_next(struct sg_mapping_iter *miter);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81530a70)
Location: lib/scatterlist.c:763
Inline: True
Direct callers:
  - lib/scatterlist.c:sg_zero_buffer
  - lib/scatterlist.c:sg_copy_buffer
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_read_raw_from_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - lib/mpi/mpicoder.c:mpi_write_to_sgl
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
```
**Symbols:**

```
ffffffff81530a70-ffffffff81530aff: sg_miter_next (STB_GLOBAL)
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
