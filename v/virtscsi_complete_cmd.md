# Function: <code>virtscsi_complete_cmd</code>

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
<summary>In <code>6.5</code>: ✅</summary>

```c
void virtscsi_complete_cmd(struct virtio_scsi *vscsi, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/virtio_scsi.c (ffffffff81be21c0)
Location: drivers/scsi/virtio_scsi.c:109
Inline: False
Direct callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/scsi/virtio_scsi.c:virtscsi_req_done
```
**Symbols:**

```
ffffffff81be21c0-ffffffff81be23d6: virtscsi_complete_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void virtscsi_complete_cmd(struct virtio_scsi *vscsi, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/virtio_scsi.c (ffffffff81c372e0)
Location: drivers/scsi/virtio_scsi.c:115
Inline: False
Direct callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_mq_poll
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
  - drivers/scsi/virtio_scsi.c:virtscsi_req_done
```
**Symbols:**

```
ffffffff81c372e0-ffffffff81c374f6: virtscsi_complete_cmd (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void virtscsi_complete_cmd(struct virtio_scsi *vscsi, void *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/virtio_scsi.c (ffffffff81772130)
Location: drivers/scsi/virtio_scsi.c:108
Inline: False
Direct callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
```
**Symbols:**

```
ffffffff81772130-ffffffff81772382: virtscsi_complete_cmd (STB_LOCAL)
```
</details>
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
</ul>
