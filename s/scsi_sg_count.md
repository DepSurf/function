# Function: <code>scsi_sg_count</code>

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
In drivers/scsi/scsi.c (ffffffff815a5d1b)
Location: include/scsi/scsi_cmnd.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff815b1895)
Location: include/scsi/scsi_cmnd.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (0)
Location: include/scsi/scsi_cmnd.h:171
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff815d116e)
Location: include/scsi/scsi_cmnd.h:171
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_translate
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
In drivers/scsi/scsi.c (ffffffff815fde97)
Location: include/scsi/scsi_cmnd.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81609c25)
Location: include/scsi/scsi_cmnd.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (0)
Location: include/scsi/scsi_cmnd.h:171
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff8162a56e)
Location: include/scsi/scsi_cmnd.h:171
Inline: True
Inline callers:
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
In drivers/scsi/scsi.c (ffffffff8162d495)
Location: include/scsi/scsi_cmnd.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81639505)
Location: include/scsi/scsi_cmnd.h:171
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/scsi/scsi_cmnd.h:171
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: include/scsi/scsi_cmnd.h:171
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff8165b7ee)
Location: include/scsi/scsi_cmnd.h:171
Inline: True
Inline callers:
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
In drivers/scsi/scsi.c (ffffffff81642b5a)
Location: include/scsi/scsi_cmnd.h:176
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff8164e065)
Location: include/scsi/scsi_cmnd.h:176
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/scsi/scsi_cmnd.h:176
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: include/scsi/scsi_cmnd.h:176
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff816702ef)
Location: include/scsi/scsi_cmnd.h:176
Inline: True
Inline callers:
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
In drivers/scsi/scsi.c (ffffffff816abb8f)
Location: include/scsi/scsi_cmnd.h:182
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff816b7355)
Location: include/scsi/scsi_cmnd.h:182
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sd_zbc.c (0)
Location: include/scsi/scsi_cmnd.h:182
Inline: True
```
```
In drivers/scsi/sr.c (0)
Location: include/scsi/scsi_cmnd.h:182
Inline: True
```
```
In drivers/ata/libata-scsi.c (ffffffff816d98f5)
Location: include/scsi/scsi_cmnd.h:182
Inline: True
Inline callers:
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
In drivers/scsi/scsi.c (ffffffff816e8085)
Location: include/scsi/scsi_cmnd.h:185
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff816f3655)
Location: include/scsi/scsi_cmnd.h:185
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sd_zbc.c (ffffffff817028e1)
Location: include/scsi/scsi_cmnd.h:185
Inline: True
Inline callers:
  - drivers/scsi/sd_zbc.c:sd_zbc_report_zones_complete
```
```
In drivers/scsi/sr.c (ffffffff81703b80)
Location: include/scsi/scsi_cmnd.h:185
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff81716d62)
Location: include/scsi/scsi_cmnd.h:185
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
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
In drivers/scsi/scsi.c (ffffffff8170bb85)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81716035)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff8172604d)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff817393a2)
Location: include/scsi/scsi_cmnd.h:188
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
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
In drivers/scsi/scsi.c (ffffffff8174728d)
Location: include/scsi/scsi_cmnd.h:177
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81751815)
Location: include/scsi/scsi_cmnd.h:177
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff8176177f)
Location: include/scsi/scsi_cmnd.h:177
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff817753d4)
Location: include/scsi/scsi_cmnd.h:177
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
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
In drivers/scsi/scsi.c (ffffffff8176b3dd)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81775a95)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff8178576f)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff81799344)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
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
In drivers/scsi/scsi.c (ffffffff8182d6cf)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff818389b5)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff81849a1f)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff8185d98e)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
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
In drivers/scsi/scsi.c (ffffffff8183e70f)
Location: include/scsi/scsi_cmnd.h:179
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81849325)
Location: include/scsi/scsi_cmnd.h:179
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff81859f77)
Location: include/scsi/scsi_cmnd.h:179
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff8186ca08)
Location: include/scsi/scsi_cmnd.h:179
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
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
In drivers/scsi/scsi.c (ffffffff818218c8)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff8182c755)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff8183cf87)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff8184f5fa)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
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
In drivers/scsi/scsi.c (ffffffff818ac218)
Location: include/scsi/scsi_cmnd.h:185
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff818b84e5)
Location: include/scsi/scsi_cmnd.h:185
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff818c9914)
Location: include/scsi/scsi_cmnd.h:185
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff818de21e)
Location: include/scsi/scsi_cmnd.h:185
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_simulate
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
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
In drivers/scsi/scsi.c (ffffffff819f6be8)
Location: include/scsi/scsi_cmnd.h:175
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81a03bc5)
Location: include/scsi/scsi_cmnd.h:175
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff81a16c84)
Location: include/scsi/scsi_cmnd.h:175
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff81a2f6f5)
Location: include/scsi/scsi_cmnd.h:175
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
In drivers/scsi/scsi.c (ffffffff81b74afb)
Location: include/scsi/scsi_cmnd.h:176
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81b82765)
Location: include/scsi/scsi_cmnd.h:176
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff81b97ae4)
Location: include/scsi/scsi_cmnd.h:176
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff81bb2c40)
Location: include/scsi/scsi_cmnd.h:176
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
In drivers/scsi/scsi.c (ffffffff81bc85ce)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81bd6465)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81be270e)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
```
```
In drivers/scsi/sr.c (ffffffff81bee063)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff81c0a0ad)
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
In drivers/scsi/scsi.c (ffffffff81c1d13e)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81c2b0b5)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81c378ee)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
```
```
In drivers/scsi/sr.c (ffffffff81c43770)
Location: include/scsi/scsi_cmnd.h:181
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff81c5f162)
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
In drivers/scsi/scsi.c (ffff80001096d28c)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib_dma.c (ffff80001097a230)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffff80001098c038)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffff8000109a2a5c)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
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
In drivers/scsi/scsi.c (c0a42c40)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib_dma.c (c0a4da64)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (c0a5e3b4)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (c0a73c28)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
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
In drivers/scsi/scsi.c (c000000000a26264)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib_dma.c (c000000000a348b0)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (c000000000a4d01c)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (c000000000a68694)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
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
In drivers/scsi/scsi.c (ffffffe0005d7c16)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffe0005e1376)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffe0005f069a)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffe00060313c)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
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
In drivers/scsi/scsi.c (ffffffff8171facd)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff8172a185)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff81739e5f)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff8175e434)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
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
In drivers/scsi/scsi.c (ffffffff816f8efd)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff817035a5)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/storvsc_drv.c (ffffffff817140c6)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/storvsc_drv.c:storvsc_queuecommand
```
```
In drivers/scsi/sr.c (ffffffff8171baff)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff8173e2d4)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
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
In drivers/scsi/scsi.c (ffffffff8175e89d)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff81768f55)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/virtio_scsi.c (ffffffff817727e7)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
```
```
In drivers/scsi/sr.c (ffffffff8177a5ef)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff8178e1c4)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
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
In drivers/scsi/scsi.c (ffffffff81779efd)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/scsi.c:perf_trace_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:perf_trace_scsi_dispatch_cmd_start
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_cmd_done_timeout_template
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_error
  - drivers/scsi/scsi.c:trace_event_raw_event_scsi_dispatch_cmd_start
```
```
In drivers/scsi/scsi_lib_dma.c (ffffffff817846c5)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_unmap
  - drivers/scsi/scsi_lib_dma.c:scsi_dma_map
```
```
In drivers/scsi/sr.c (ffffffff8179441f)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/scsi/sr.c:sr_init_command
```
```
In drivers/ata/libata-scsi.c (ffffffff817a8014)
Location: include/scsi/scsi_cmnd.h:178
Inline: True
Inline callers:
  - drivers/ata/libata-scsi.c:ata_scsi_mode_select_xlat
  - drivers/ata/libata-scsi.c:ata_scsi_report_zones_complete
  - drivers/ata/libata-scsi.c:ata_scsi_write_same_xlat
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
