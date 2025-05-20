# Function: <code>irq_set_affinity_and_hint</code>

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
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff818c42ad)
Location: include/linux/interrupt.h:340
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff81a1499d)
Location: include/linux/interrupt.h:340
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_pci_common.c (ffffffff81a5da0d)
Location: include/linux/interrupt.h:340
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
  - drivers/virtio/virtio_pci_common.c:vp_del_vqs
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
In drivers/virtio/virtio_pci_common.c (ffffffff81aaf9bd)
Location: include/linux/interrupt.h:340
Inline: True
Inline callers:
  - drivers/virtio/virtio_pci_common.c:vp_set_vq_affinity
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
