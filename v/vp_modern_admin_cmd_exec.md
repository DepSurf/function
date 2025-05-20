# Function: <code>vp_modern_admin_cmd_exec</code>

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
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int vp_modern_admin_cmd_exec(struct virtio_device *vdev, struct virtio_admin_cmd *cmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/virtio/virtio_pci_modern.c (0)
Location: drivers/virtio/virtio_pci_modern.c:77
Inline: False
Direct callers:
  - drivers/virtio/virtio_pci_modern.c:vp_set_status
  - drivers/virtio/virtio_pci_modern.c:vp_set_status
  - drivers/virtio/virtio_pci_admin_legacy_io.c:virtio_pci_admin_legacy_io_notify_info
  - drivers/virtio/virtio_pci_admin_legacy_io.c:virtio_pci_admin_legacy_io_read
  - drivers/virtio/virtio_pci_admin_legacy_io.c:virtio_pci_admin_legacy_io_write
```
**Symbols:**

```
ffffffff821f2e61-ffffffff821f2e7a: vp_modern_admin_cmd_exec.cold (STB_LOCAL)
ffffffff81aadef0-ffffffff81aae285: vp_modern_admin_cmd_exec (STB_GLOBAL)
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
<b>Regular</b>
<ul>
</ul>
