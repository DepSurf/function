# Function: <code>nvme_get_ctrl</code>

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
In <code>6.8</code>: Absent ⚠️
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff8174719d)
Location: drivers/nvme/host/nvme.h:439
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_sysfs_delete
  - drivers/nvme/host/core.c:nvme_ioctl
```
```
In drivers/nvme/host/pci.c (ffffffff8175141b)
Location: drivers/nvme/host/nvme.h:439
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_probe
  - drivers/nvme/host/pci.c:nvme_reset_work
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
In drivers/nvme/host/core.c (ffffffff81728df5)
Location: drivers/nvme/host/nvme.h:439
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:nvme_alloc_ns
  - drivers/nvme/host/core.c:nvme_sysfs_delete
  - drivers/nvme/host/core.c:nvme_ioctl
```
```
In drivers/nvme/host/pci.c (ffffffff817312bb)
Location: drivers/nvme/host/nvme.h:439
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_probe
  - drivers/nvme/host/pci.c:nvme_reset_work
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
