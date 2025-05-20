# Function: <code>blk_mq_unique_tag_to_hwq</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/virtio_scsi.c (ffffffff81be270e)
Location: include/linux/blk-mq.h:776
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/virtio_scsi.c (ffffffff81c378ee)
Location: include/linux/blk-mq.h:767
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff81745967)
Location: include/linux/blk-mq.h:294
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:perf_trace_nvme_sq
  - drivers/nvme/host/core.c:perf_trace_nvme_complete_rq
  - drivers/nvme/host/core.c:perf_trace_nvme_setup_cmd
  - drivers/nvme/host/core.c:trace_event_raw_event_nvme_sq
  - drivers/nvme/host/core.c:trace_event_raw_event_nvme_complete_rq
  - drivers/nvme/host/core.c:trace_event_raw_event_nvme_setup_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff817275f7)
Location: include/linux/blk-mq.h:294
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:perf_trace_nvme_sq
  - drivers/nvme/host/core.c:perf_trace_nvme_complete_rq
  - drivers/nvme/host/core.c:perf_trace_nvme_setup_cmd
  - drivers/nvme/host/core.c:trace_event_raw_event_nvme_sq
  - drivers/nvme/host/core.c:trace_event_raw_event_nvme_complete_rq
  - drivers/nvme/host/core.c:trace_event_raw_event_nvme_setup_cmd
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/scsi/virtio_scsi.c (ffffffff817727e7)
Location: include/linux/blk-mq.h:294
Inline: True
Inline callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
```
</details>
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
