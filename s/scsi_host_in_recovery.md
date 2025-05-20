# Function: <code>scsi_host_in_recovery</code>

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
In drivers/scsi/scsi_ioctl.c (ffffffff815a8af8)
Location: include/scsi/scsi_host.h:769
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff815aba38)
Location: include/scsi/scsi_host.h:769
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff815aed51)
Location: include/scsi/scsi_host.h:769
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:scsi_request_fn
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff815b4a98)
Location: include/scsi/scsi_host.h:769
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/ata/libata-eh.c (ffffffff815d4df9)
Location: include/scsi/scsi_host.h:769
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
In drivers/scsi/scsi_ioctl.c (ffffffff816009a4)
Location: include/scsi/scsi_host.h:766
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff816039ef)
Location: include/scsi/scsi_host.h:766
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff81607c0d)
Location: include/scsi/scsi_host.h:766
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8160c728)
Location: include/scsi/scsi_host.h:766
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/ata/libata-eh.c (ffffffff8162e879)
Location: include/scsi/scsi_host.h:766
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
In drivers/scsi/scsi_ioctl.c (ffffffff81630084)
Location: include/scsi/scsi_host.h:774
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff816330d6)
Location: include/scsi/scsi_host.h:774
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_times_out
```
```
In drivers/scsi/scsi_lib.c (ffffffff81637517)
Location: include/scsi/scsi_host.h:774
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8163bfc8)
Location: include/scsi/scsi_host.h:774
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/ata/libata-eh.c (ffffffff8165f9c9)
Location: include/scsi/scsi_host.h:774
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
In drivers/scsi/scsi_ioctl.c (ffffffff81644e24)
Location: include/scsi/scsi_host.h:766
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff81647e66)
Location: include/scsi/scsi_host.h:766
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff8164d04c)
Location: include/scsi/scsi_host.h:766
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81650a38)
Location: include/scsi/scsi_host.h:766
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/ata/libata-eh.c (ffffffff81674419)
Location: include/scsi/scsi_host.h:766
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
In drivers/scsi/scsi_ioctl.c (ffffffff816addb4)
Location: include/scsi/scsi_host.h:761
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff816b0ee6)
Location: include/scsi/scsi_host.h:761
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff816b6361)
Location: include/scsi/scsi_host.h:761
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_lld_busy
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff816b9d48)
Location: include/scsi/scsi_host.h:761
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/ata/libata-eh.c (ffffffff816dda79)
Location: include/scsi/scsi_host.h:761
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
In drivers/scsi/scsi_ioctl.c (ffffffff816ea1b4)
Location: include/scsi/scsi_host.h:737
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff816ed1d5)
Location: include/scsi/scsi_host.h:737
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff816f255f)
Location: include/scsi/scsi_host.h:737
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_request_fn
  - drivers/scsi/scsi_lib.c:scsi_lld_busy
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff816f612b)
Location: include/scsi/scsi_host.h:737
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/ata/libata-eh.c (ffffffff8171a289)
Location: include/scsi/scsi_host.h:737
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
In drivers/scsi/scsi_ioctl.c (ffffffff8170dc64)
Location: include/scsi/scsi_host.h:720
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff81710d35)
Location: include/scsi/scsi_host.h:720
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff8171509e)
Location: include/scsi/scsi_host.h:720
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81718a3b)
Location: include/scsi/scsi_host.h:720
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/ata/libata-eh.c (ffffffff8173cb89)
Location: include/scsi/scsi_host.h:720
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
In drivers/scsi/scsi_ioctl.c (ffffffff81749414)
Location: include/scsi/scsi_host.h:714
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff8174c165)
Location: include/scsi/scsi_host.h:714
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff8175087f)
Location: include/scsi/scsi_host.h:714
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff817541bd)
Location: include/scsi/scsi_host.h:714
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/ata/libata-eh.c (ffffffff817786c5)
Location: include/scsi/scsi_host.h:714
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
In drivers/scsi/scsi_ioctl.c (ffffffff8176d544)
Location: include/scsi/scsi_host.h:726
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff817702e5)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff81774aa2)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8177843d)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/ata/libata-eh.c (ffffffff8179c535)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
In drivers/scsi/scsi_ioctl.c (ffffffff8182fbc4)
Location: include/scsi/scsi_host.h:720
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff818314cc)
Location: include/scsi/scsi_host.h:720
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff81837eae)
Location: include/scsi/scsi_host.h:720
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
  - drivers/scsi/scsi_lib.c:scsi_device_unbusy
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8183b3cb)
Location: include/scsi/scsi_host.h:720
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/ata/libata-eh.c (ffffffff81860315)
Location: include/scsi/scsi_host.h:720
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
In drivers/scsi/scsi_ioctl.c (ffffffff81840884)
Location: include/scsi/scsi_host.h:727
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff818420dc)
Location: include/scsi/scsi_host.h:727
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff818487f8)
Location: include/scsi/scsi_host.h:727
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8184c2eb)
Location: include/scsi/scsi_host.h:727
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/ata/libata-eh.c (ffffffff8186f135)
Location: include/scsi/scsi_host.h:727
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
In drivers/scsi/scsi_ioctl.c (ffffffff81823ac4)
Location: include/scsi/scsi_host.h:743
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff818252e0)
Location: include/scsi/scsi_host.h:743
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff8182bb86)
Location: include/scsi/scsi_host.h:743
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8182f70b)
Location: include/scsi/scsi_host.h:743
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/ata/libata-eh.c (ffffffff81851945)
Location: include/scsi/scsi_host.h:743
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
In drivers/scsi/scsi_ioctl.c (ffffffff818ae3f4)
Location: include/scsi/scsi_host.h:744
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff818b0b60)
Location: include/scsi/scsi_host.h:744
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b7739)
Location: include/scsi/scsi_host.h:744
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff818bb55b)
Location: include/scsi/scsi_host.h:744
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/ata/libata-eh.c (ffffffff818df665)
Location: include/scsi/scsi_host.h:744
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
In drivers/scsi/scsi_ioctl.c (ffffffff819f9514)
Location: include/scsi/scsi_host.h:736
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl_block_when_processing_errors
```
```
In drivers/scsi/scsi_error.c (ffffffff819faddd)
Location: include/scsi/scsi_host.h:736
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff81a02e34)
Location: include/scsi/scsi_host.h:736
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81a071f9)
Location: include/scsi/scsi_host.h:736
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/ata/libata-eh.c (ffffffff81a30b2b)
Location: include/scsi/scsi_host.h:736
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
In drivers/scsi/scsi_ioctl.c (ffffffff81b773e4)
Location: include/scsi/scsi_host.h:739
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl_block_when_processing_errors
```
```
In drivers/scsi/scsi_error.c (ffffffff81b78e4d)
Location: include/scsi/scsi_host.h:739
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b8173a)
Location: include/scsi/scsi_host.h:739
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81b86139)
Location: include/scsi/scsi_host.h:739
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/ata/libata-eh.c (ffffffff81bb41bb)
Location: include/scsi/scsi_host.h:739
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
In drivers/scsi/scsi_ioctl.c (ffffffff81bcb044)
Location: include/scsi/scsi_host.h:745
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl_block_when_processing_errors
```
```
In drivers/scsi/scsi_error.c (ffffffff81bccadd)
Location: include/scsi/scsi_host.h:745
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd543d)
Location: include/scsi/scsi_host.h:745
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81bd9f09)
Location: include/scsi/scsi_host.h:745
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/ata/libata-eh.c (ffffffff81c0b6ab)
Location: include/scsi/scsi_host.h:745
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
In drivers/scsi/scsi_ioctl.c (ffffffff81c1fc74)
Location: include/scsi/scsi_host.h:748
Inline: True
Inline callers:
  - drivers/scsi/scsi_ioctl.c:scsi_ioctl_block_when_processing_errors
```
```
In drivers/scsi/scsi_error.c (ffffffff81c2170d)
Location: include/scsi/scsi_host.h:748
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c2a099)
Location: include/scsi/scsi_host.h:748
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
  - drivers/scsi/scsi_lib.c:__scsi_queue_insert
  - drivers/scsi/scsi_lib.c:scsi_mq_requeue_cmd
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81c2ec39)
Location: include/scsi/scsi_host.h:748
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/ata/libata-eh.c (ffffffff81c6072b)
Location: include/scsi/scsi_host.h:748
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
In drivers/scsi/scsi_ioctl.c (ffff80001096fd00)
Location: include/scsi/scsi_host.h:726
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffff800010971c90)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffff800010978afc)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/scsi/scsi_sysfs.c (ffff80001097f2ec)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/ata/libata-eh.c (ffff8000109a7fbc)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
In drivers/scsi/scsi_ioctl.c (c0a44eac)
Location: include/scsi/scsi_host.h:726
Inline: True
```
```
In drivers/scsi/scsi_error.c (c0a480d4)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (c0a4ca24)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/scsi/scsi_sysfs.c (c0a50730)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/ata/libata-eh.c (c0a77328)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
In drivers/scsi/scsi_ioctl.c (c000000000a29404)
Location: include/scsi/scsi_host.h:726
Inline: True
```
```
In drivers/scsi/scsi_error.c (c000000000a2d05c)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (c000000000a33284)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/scsi/scsi_sysfs.c (c000000000a382ec)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/ata/libata-eh.c (c000000000a6d7dc)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
In drivers/scsi/scsi_ioctl.c (ffffffe0005d9c20)
Location: include/scsi/scsi_host.h:726
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffe0005dc4d8)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005e046a)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/scsi/scsi_sysfs.c (ffffffe0005e3aea)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/ata/libata-eh.c (ffffffe000605a3c)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
In drivers/scsi/scsi_ioctl.c (ffffffff81721c34)
Location: include/scsi/scsi_host.h:726
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff817249d5)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff81729192)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8172cb2d)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/ata/libata-eh.c (ffffffff81761625)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
In drivers/scsi/scsi_ioctl.c (ffffffff816fb064)
Location: include/scsi/scsi_host.h:726
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff816fde05)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff817025c2)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff81705f4d)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/ata/libata-eh.c (ffffffff81741485)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
In drivers/scsi/scsi_ioctl.c (ffffffff81760a04)
Location: include/scsi/scsi_host.h:726
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff817637a5)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff81767f62)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8176b8fd)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/ata/libata-eh.c (ffffffff817913b5)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_wait_eh
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
In drivers/scsi/scsi_ioctl.c (ffffffff8177c064)
Location: include/scsi/scsi_host.h:726
Inline: True
```
```
In drivers/scsi/scsi_error.c (ffffffff8177ee00)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
  - drivers/scsi/scsi_error.c:scsi_block_when_processing_errors
```
```
In drivers/scsi/scsi_lib.c (ffffffff8178369f)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_queue_rq
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_mq_lld_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
  - drivers/scsi/scsi_lib.c:scsi_dec_host_busy
```
```
In drivers/scsi/scsi_sysfs.c (ffffffff8178703d)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_sysfs.c:store_shost_eh_deadline
```
```
In drivers/ata/libata-eh.c (ffffffff817ab1f5)
Location: include/scsi/scsi_host.h:726
Inline: True
Inline callers:
  - drivers/ata/libata-eh.c:ata_port_wait_eh
```
</details>
</li>
</ul>

## Differences
