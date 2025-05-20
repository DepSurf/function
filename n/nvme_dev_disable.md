# Function: <code>nvme_dev_disable</code>

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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void nvme_dev_disable(struct nvme_dev *dev, bool shutdown);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvme/host/pci.c (0)
Location: drivers/nvme/host/pci.c:2415
Inline: False
Direct callers:
  - drivers/nvme/host/pci.c:nvme_error_detected
  - drivers/nvme/host/pci.c:nvme_simple_suspend
  - drivers/nvme/host/pci.c:nvme_suspend
  - drivers/nvme/host/pci.c:nvme_suspend
  - drivers/nvme/host/pci.c:nvme_remove
  - drivers/nvme/host/pci.c:nvme_remove
  - drivers/nvme/host/pci.c:nvme_shutdown
  - drivers/nvme/host/pci.c:nvme_reset_prepare
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_timeout
  - drivers/nvme/host/pci.c:nvme_timeout
  - drivers/nvme/host/pci.c:nvme_timeout
```
**Symbols:**

```
ffffffff8174faa0-ffffffff8174ff8b: nvme_dev_disable (STB_LOCAL)
ffffffff817514e8-ffffffff8175150c: nvme_dev_disable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void nvme_dev_disable(struct nvme_dev *dev, bool shutdown);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvme/host/pci.c (0)
Location: drivers/nvme/host/pci.c:2415
Inline: False
Direct callers:
  - drivers/nvme/host/pci.c:nvme_error_detected
  - drivers/nvme/host/pci.c:nvme_simple_suspend
  - drivers/nvme/host/pci.c:nvme_suspend
  - drivers/nvme/host/pci.c:nvme_suspend
  - drivers/nvme/host/pci.c:nvme_remove
  - drivers/nvme/host/pci.c:nvme_remove
  - drivers/nvme/host/pci.c:nvme_shutdown
  - drivers/nvme/host/pci.c:nvme_reset_prepare
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_reset_work
  - drivers/nvme/host/pci.c:nvme_timeout
  - drivers/nvme/host/pci.c:nvme_timeout
  - drivers/nvme/host/pci.c:nvme_timeout
```
**Symbols:**

```
ffffffff8172f940-ffffffff8172fe2b: nvme_dev_disable (STB_LOCAL)
ffffffff81731388-ffffffff817313ac: nvme_dev_disable.cold (STB_LOCAL)
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
<b>Flavor</b>
<ul>
</ul>
