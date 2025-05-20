# Function: <code>nvme_stop_queues</code>

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
<summary>In <code>aws</code>: ✅</summary>

```c
void nvme_stop_queues(struct nvme_ctrl *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff817426c0)
Location: drivers/nvme/host/core.c:4165
Inline: False
Direct callers:
  - drivers/nvme/host/core.c:nvme_fw_act_work
  - drivers/nvme/host/pci.c:nvme_dev_disable
  - drivers/nvme/host/pci.c:nvme_dev_disable
  - drivers/nvme/host/pci.c:nvme_dev_disable
  - drivers/nvme/host/pci.c:nvme_dev_disable
```
**Symbols:**

```
ffffffff817426c0-ffffffff8174270d: nvme_stop_queues (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void nvme_stop_queues(struct nvme_ctrl *ctrl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/core.c (ffffffff81724350)
Location: drivers/nvme/host/core.c:4165
Inline: False
Direct callers:
  - drivers/nvme/host/core.c:nvme_fw_act_work
  - drivers/nvme/host/pci.c:nvme_dev_disable
  - drivers/nvme/host/pci.c:nvme_dev_disable
  - drivers/nvme/host/pci.c:nvme_dev_disable
  - drivers/nvme/host/pci.c:nvme_dev_disable
```
**Symbols:**

```
ffffffff81724350-ffffffff8172439d: nvme_stop_queues (STB_GLOBAL)
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
