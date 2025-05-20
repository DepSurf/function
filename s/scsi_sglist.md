# Function: <code>scsi_sglist</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib_dma.c (ffffffff815b1945)
Location: include/scsi/scsi_cmnd.h:176
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff815c00d1)
Location: include/scsi/scsi_cmnd.h:176
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff815d115f)
Location: include/scsi/scsi_cmnd.h:176
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib_dma.c (ffffffff81609cd5)
Location: include/scsi/scsi_cmnd.h:176
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff8161887c)
Location: include/scsi/scsi_cmnd.h:176
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff8162b815)
Location: include/scsi/scsi_cmnd.h:176
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib_dma.c (ffffffff816395b5)
Location: include/scsi/scsi_cmnd.h:176
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/scsi/scsi_cmnd.h:176
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff816494f5)
Location: include/scsi/scsi_cmnd.h:176
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff8165c9b5)
Location: include/scsi/scsi_cmnd.h:176
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib_dma.c (ffffffff8164e07b)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff8165de29)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff816712c0)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib_dma.c (ffffffff816b736c)
Location: include/scsi/scsi_cmnd.h:187
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/scsi/scsi_cmnd.h:187
Inline: True
```
```
In drivers/scsi/sr.c (ffffffff816c7414)
Location: include/scsi/scsi_cmnd.h:187
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff816da8a0)
Location: include/scsi/scsi_cmnd.h:187
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib_dma.c (ffffffff816f3678)
Location: include/scsi/scsi_cmnd.h:190
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sd_zbc.c (ffffffff817028e1)
Location: include/scsi/scsi_cmnd.h:190
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
```
```
In drivers/scsi/sr.c (ffffffff81703b8f)
Location: include/scsi/scsi_cmnd.h:190
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff81716d70)
Location: include/scsi/scsi_cmnd.h:190
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib_dma.c (ffffffff81716062)
Location: include/scsi/scsi_cmnd.h:193
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff81726059)
Location: include/scsi/scsi_cmnd.h:193
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff817393b0)
Location: include/scsi/scsi_cmnd.h:193
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib_dma.c (ffffffff8175183f)
Location: include/scsi/scsi_cmnd.h:182
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff81761790)
Location: include/scsi/scsi_cmnd.h:182
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff817753e4)
Location: include/scsi/scsi_cmnd.h:182
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib_dma.c (ffffffff81775abf)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff81785780)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff81799354)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib_dma.c (ffffffff818389df)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff81849a30)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff8185d99c)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_format_dsm_trim_descr
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib_dma.c (ffffffff81849330)
Location: include/scsi/scsi_cmnd.h:184
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff81859f88)
Location: include/scsi/scsi_cmnd.h:184
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff8186ca16)
Location: include/scsi/scsi_cmnd.h:184
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_format_dsm_trim_descr
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib_dma.c (ffffffff8182c760)
Location: include/scsi/scsi_cmnd.h:186
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff8183cf98)
Location: include/scsi/scsi_cmnd.h:186
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff8184f60a)
Location: include/scsi/scsi_cmnd.h:186
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib_dma.c (ffffffff818b84f0)
Location: include/scsi/scsi_cmnd.h:190
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff818c9927)
Location: include/scsi/scsi_cmnd.h:190
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff818de21e)
Location: include/scsi/scsi_cmnd.h:190
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib_dma.c (ffffffff81a03be1)
Location: include/scsi/scsi_cmnd.h:180
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff81a16c94)
Location: include/scsi/scsi_cmnd.h:180
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff81a2f6f5)
Location: include/scsi/scsi_cmnd.h:180
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:__ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib_dma.c (ffffffff81b82781)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff81b97af4)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff81bb2c40)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:__ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib_dma.c (ffffffff81bd6481)
Location: include/scsi/scsi_cmnd.h:186
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff81bee073)
Location: include/scsi/scsi_cmnd.h:186
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff81c0a0ad)
Location: include/scsi/scsi_cmnd.h:186
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:__ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib_dma.c (ffffffff81c2b0d1)
Location: include/scsi/scsi_cmnd.h:186
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff81c43780)
Location: include/scsi/scsi_cmnd.h:186
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff81c5f162)
Location: include/scsi/scsi_cmnd.h:186
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:__ata_scsi_queuecmd
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_qc_new
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib_dma.c (ffff80001097a25c)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffff80001098c03c)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffff8000109a2a68)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib_dma.c (c0a4da88)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (c0a5e3b8)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (c0a73c34)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib_dma.c (c000000000a348e0)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (c000000000a4d020)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (c000000000a686a0)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib_dma.c (ffffffe0005e1388)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffe0005f069e)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffe000603144)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib_dma.c (ffffffff8172a1af)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff81739e70)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff8175e444)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib_dma.c (ffffffff817035cf)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/storvsc_drv.c (ffffffff817140c6)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/scsi/storvsc_drv.c:storvsc_queuecommand
```
```
In drivers/scsi/sr.c (ffffffff8171bb10)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff8173e2e4)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib_dma.c (ffffffff81768f7f)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff8177a600)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff8178e1d4)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib_dma.c (ffffffff817846ef)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff81794430)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff817a8024)
Location: include/scsi/scsi_cmnd.h:183
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:atapi_qc_complete
  - drivers/ata/libata-scsi.c:ata_scsi_rbuf_fill
  - drivers/ata/libata-scsi.c:ata_scsi_translate
  - drivers/ata/libata-scsi.c:ata_scsi_translate
```
</details>
</li>
</ul>

## Differences
