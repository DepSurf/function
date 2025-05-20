# Function: <code>nvme_dbbuf_update_and_check_event</code>

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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvme/host/pci.c (ffffffff8174fce8)
Location: drivers/nvme/host/pci.c:307
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_dev_disable
  - drivers/nvme/host/pci.c:nvme_poll
  - drivers/nvme/host/pci.c:nvme_poll_irqdisable
  - drivers/nvme/host/pci.c:nvme_poll_irqdisable
  - drivers/nvme/host/pci.c:nvme_irq
  - drivers/nvme/host/pci.c:nvme_commit_rqs
  - drivers/nvme/host/pci.c:nvme_submit_cmd
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
In drivers/nvme/host/pci.c (ffffffff8172fb88)
Location: drivers/nvme/host/pci.c:307
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_dev_disable
  - drivers/nvme/host/pci.c:nvme_poll
  - drivers/nvme/host/pci.c:nvme_poll_irqdisable
  - drivers/nvme/host/pci.c:nvme_poll_irqdisable
  - drivers/nvme/host/pci.c:nvme_irq
  - drivers/nvme/host/pci.c:nvme_commit_rqs
  - drivers/nvme/host/pci.c:nvme_submit_cmd
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
