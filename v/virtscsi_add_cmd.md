# Function: <code>virtscsi_add_cmd</code>

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
int virtscsi_add_cmd(struct virtio_scsi_vq *vq, struct virtio_scsi_cmd *cmd, size_t req_size, size_t resp_size, bool kick);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/virtio_scsi.c (ffffffff81be2000)
Location: drivers/scsi/virtio_scsi.c:491
Inline: False
Direct callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
```
**Symbols:**

```
ffffffff81be2000-ffffffff81be20a0: virtscsi_add_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int virtscsi_add_cmd(struct virtio_scsi_vq *vq, struct virtio_scsi_cmd *cmd, size_t req_size, size_t resp_size, bool kick);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/virtio_scsi.c (ffffffff81c37120)
Location: drivers/scsi/virtio_scsi.c:495
Inline: False
Direct callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
```
**Symbols:**

```
ffffffff81c37120-ffffffff81c371c0: virtscsi_add_cmd (STB_LOCAL)
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
int virtscsi_add_cmd(struct virtio_scsi_vq *vq, struct virtio_scsi_cmd *cmd, size_t req_size, size_t resp_size, bool kick);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/virtio_scsi.c (ffffffff81771e60)
Location: drivers/scsi/virtio_scsi.c:471
Inline: False
Direct callers:
  - drivers/scsi/virtio_scsi.c:virtscsi_queuecommand
```
**Symbols:**

```
ffffffff81771e60-ffffffff81771ef1: virtscsi_add_cmd (STB_LOCAL)
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
