# Function: <code>set_host_byte</code>

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
In drivers/scsi/scsi_error.c (ffffffff815aa1ea)
Location: include/scsi/scsi_cmnd.h:331
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
```
```
In drivers/scsi/scsi_lib.c (ffffffff815ad0c0)
Location: include/scsi/scsi_cmnd.h:331
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_error_from_host_byte
  - drivers/scsi/scsi_lib.c:__scsi_error_from_host_byte
  - drivers/scsi/scsi_lib.c:__scsi_error_from_host_byte
  - drivers/scsi/scsi_lib.c:__scsi_error_from_host_byte
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
In drivers/scsi/scsi_error.c (ffffffff816043f2)
Location: include/scsi/scsi_cmnd.h:331
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/scsi_lib.c (ffffffff81605000)
Location: include/scsi/scsi_cmnd.h:331
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_error_from_host_byte
  - drivers/scsi/scsi_lib.c:__scsi_error_from_host_byte
  - drivers/scsi/scsi_lib.c:__scsi_error_from_host_byte
  - drivers/scsi/scsi_lib.c:__scsi_error_from_host_byte
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
In drivers/scsi/scsi_error.c (ffffffff81633ad2)
Location: include/scsi/scsi_cmnd.h:331
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/scsi_lib.c (ffffffff816346e0)
Location: include/scsi/scsi_cmnd.h:331
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_error_from_host_byte
  - drivers/scsi/scsi_lib.c:__scsi_error_from_host_byte
  - drivers/scsi/scsi_lib.c:__scsi_error_from_host_byte
  - drivers/scsi/scsi_lib.c:__scsi_error_from_host_byte
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
In drivers/scsi/scsi_error.c (ffffffff81648728)
Location: include/scsi/scsi_cmnd.h:336
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/scsi_lib.c (ffffffff8164907b)
Location: include/scsi/scsi_cmnd.h:336
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_error_from_host_byte
  - drivers/scsi/scsi_lib.c:__scsi_error_from_host_byte
  - drivers/scsi/scsi_lib.c:__scsi_error_from_host_byte
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
In drivers/scsi/scsi_error.c (ffffffff816b182e)
Location: include/scsi/scsi_cmnd.h:342
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b2181)
Location: include/scsi/scsi_cmnd.h:342
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_error_from_host_byte
  - drivers/scsi/scsi_lib.c:__scsi_error_from_host_byte
  - drivers/scsi/scsi_lib.c:__scsi_error_from_host_byte
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
In drivers/scsi/scsi_error.c (ffffffff816edb8a)
Location: include/scsi/scsi_cmnd.h:345
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/scsi_lib.c (ffffffff816f03ea)
Location: include/scsi/scsi_cmnd.h:345
Inline: True
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
In drivers/scsi/scsi_error.c (ffffffff8171173d)
Location: include/scsi/scsi_cmnd.h:342
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/scsi_lib.c (ffffffff81713b4c)
Location: include/scsi/scsi_cmnd.h:342
Inline: True
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
In drivers/scsi/scsi_error.c (ffffffff8174cbd8)
Location: include/scsi/scsi_cmnd.h:314
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/scsi_lib.c (ffffffff8174f3cc)
Location: include/scsi/scsi_cmnd.h:314
Inline: True
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
In drivers/scsi/scsi_error.c (ffffffff81770d58)
Location: include/scsi/scsi_cmnd.h:315
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/scsi_lib.c (ffffffff817735ac)
Location: include/scsi/scsi_cmnd.h:315
Inline: True
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
In drivers/scsi/scsi_error.c (ffffffff8183362e)
Location: include/scsi/scsi_cmnd.h:315
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/scsi_lib.c (ffffffff818342ac)
Location: include/scsi/scsi_cmnd.h:315
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
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
In drivers/scsi/scsi_error.c (ffffffff8184422e)
Location: include/scsi/scsi_cmnd.h:316
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/scsi_lib.c (ffffffff81844c2c)
Location: include/scsi/scsi_cmnd.h:316
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
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
In drivers/scsi/scsi_error.c (ffffffff818273cb)
Location: include/scsi/scsi_cmnd.h:323
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182a54f)
Location: include/scsi/scsi_cmnd.h:323
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
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
In drivers/scsi/hosts.c (ffffffff818adb7b)
Location: include/scsi/scsi_cmnd.h:348
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:complete_all_cmds_iter
```
```
In drivers/scsi/scsi_error.c (ffffffff818b2dc4)
Location: include/scsi/scsi_cmnd.h:348
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b4fbf)
Location: include/scsi/scsi_cmnd.h:348
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
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
In drivers/scsi/hosts.c (ffffffff819f8a55)
Location: include/scsi/scsi_cmnd.h:338
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:complete_all_cmds_iter
```
```
In drivers/scsi/scsi_error.c (ffffffff819fdfd3)
Location: include/scsi/scsi_cmnd.h:338
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/scsi_lib.c (ffffffff819fff5d)
Location: include/scsi/scsi_cmnd.h:338
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
  - drivers/scsi/scsi_lib.c:scsi_result_to_blk_status
```
```
In drivers/ata/libata-scsi.c (ffffffff81a2b479)
Location: include/scsi/scsi_cmnd.h:338
Inline: True
Inline callers:
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
In drivers/scsi/hosts.c (ffffffff81b76535)
Location: include/scsi/scsi_cmnd.h:339
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:complete_all_cmds_iter
```
```
In drivers/scsi/scsi_error.c (ffffffff81b7c43e)
Location: include/scsi/scsi_cmnd.h:339
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_timeout
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/ata/libata-scsi.c (ffffffff81bae509)
Location: include/scsi/scsi_cmnd.h:339
Inline: True
Inline callers:
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
In drivers/scsi/hosts.c (ffffffff81bca1b5)
Location: include/scsi/scsi_cmnd.h:344
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:complete_all_cmds_iter
```
```
In drivers/scsi/scsi_error.c (ffffffff81bd01b2)
Location: include/scsi/scsi_cmnd.h:344
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_timeout
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81be2225)
Location: include/scsi/scsi_cmnd.h:344
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff81c05cde)
Location: include/scsi/scsi_cmnd.h:344
Inline: True
Inline callers:
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
In drivers/scsi/hosts.c (ffffffff81c1ede5)
Location: include/scsi/scsi_cmnd.h:344
Inline: True
Inline callers:
  - drivers/scsi/hosts.c:complete_all_cmds_iter
```
```
In drivers/scsi/scsi_error.c (ffffffff81c24e12)
Location: include/scsi/scsi_cmnd.h:344
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_timeout
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81c37345)
Location: include/scsi/scsi_cmnd.h:344
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
```
```
In drivers/ata/libata-scsi.c (ffffffff81c59d0e)
Location: include/scsi/scsi_cmnd.h:344
Inline: True
Inline callers:
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
In drivers/scsi/scsi_error.c (ffff8000109741fc)
Location: include/scsi/scsi_cmnd.h:315
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/scsi_lib.c (ffff800010976a60)
Location: include/scsi/scsi_cmnd.h:315
Inline: True
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
In drivers/scsi/scsi_error.c (c0a48c78)
Location: include/scsi/scsi_cmnd.h:315
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/scsi_lib.c (c0a4b3e4)
Location: include/scsi/scsi_cmnd.h:315
Inline: True
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
In drivers/scsi/scsi_error.c (c000000000a2dfac)
Location: include/scsi/scsi_cmnd.h:315
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/scsi_lib.c (c000000000a31480)
Location: include/scsi/scsi_cmnd.h:315
Inline: True
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
In drivers/scsi/scsi_error.c (ffffffe0005dce72)
Location: include/scsi/scsi_cmnd.h:315
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005df070)
Location: include/scsi/scsi_cmnd.h:315
Inline: True
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
In drivers/scsi/scsi_error.c (ffffffff81725448)
Location: include/scsi/scsi_cmnd.h:315
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/scsi_lib.c (ffffffff81727c9c)
Location: include/scsi/scsi_cmnd.h:315
Inline: True
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
In drivers/scsi/scsi_error.c (ffffffff816fe878)
Location: include/scsi/scsi_cmnd.h:315
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/scsi_lib.c (ffffffff817010cc)
Location: include/scsi/scsi_cmnd.h:315
Inline: True
```
```
In drivers/scsi/storvsc_drv.c (ffffffff81713663)
Location: include/scsi/scsi_cmnd.h:315
Inline: True
Inline callers:
  - drivers/scsi/storvsc_drv.c:storvsc_on_channel_callback
  - drivers/scsi/storvsc_drv.c:storvsc_on_channel_callback
  - drivers/scsi/storvsc_drv.c:storvsc_on_channel_callback
  - drivers/scsi/storvsc_drv.c:storvsc_on_channel_callback
  - drivers/scsi/storvsc_drv.c:storvsc_on_channel_callback
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
In drivers/scsi/scsi_error.c (ffffffff81764218)
Location: include/scsi/scsi_cmnd.h:315
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/scsi_lib.c (ffffffff81766a6c)
Location: include/scsi/scsi_cmnd.h:315
Inline: True
```
```
In drivers/scsi/virtio_scsi.c (ffffffff81772183)
Location: include/scsi/scsi_cmnd.h:315
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
  - drivers/scsi/virtio_scsi.c:virtscsi_complete_cmd
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
In drivers/scsi/scsi_error.c (ffffffff8177f898)
Location: include/scsi/scsi_cmnd.h:315
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_decide_disposition
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_check_sense
  - drivers/scsi/scsi_error.c:scsi_times_out
  - drivers/scsi/scsi_error.c:scmd_eh_abort_handler
```
```
In drivers/scsi/scsi_lib.c (ffffffff8178217c)
Location: include/scsi/scsi_cmnd.h:315
Inline: True
```
</details>
</li>
</ul>

## Differences
