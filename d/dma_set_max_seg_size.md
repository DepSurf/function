# Function: <code>dma_set_max_seg_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814337c5)
Location: include/linux/dma-mapping.h:154
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_set_dma_max_seg_size
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8147cd23)
Location: include/linux/dma-mapping.h:575
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff8149e283)
Location: include/linux/dma-mapping.h:627
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814a8172)
Location: include/linux/dma-mapping.h:658
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff814e71b2)
Location: include/linux/dma-mapping.h:666
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/probe.c (ffffffff815167c9)
Location: include/linux/dma-mapping.h:670
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
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
In drivers/pci/probe.c (ffffffff8152c1d9)
Location: include/linux/dma-mapping.h:696
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81712b6d)
Location: include/linux/dma-mapping.h:696
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
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
In drivers/pci/probe.c (ffffffff8155abb9)
Location: include/linux/dma-mapping.h:721
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff8174e6a2)
Location: include/linux/dma-mapping.h:721
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
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
In drivers/pci/probe.c (ffffffff8157bc49)
Location: include/linux/dma-mapping.h:726
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81772852)
Location: include/linux/dma-mapping.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
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
In drivers/pci/probe.c (ffffffff81621456)
Location: include/linux/dma-mapping.h:812
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81834ba2)
Location: include/linux/dma-mapping.h:812
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
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
In drivers/pci/probe.c (ffffffff81647fdc)
Location: include/linux/dma-mapping.h:459
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff818455e2)
Location: include/linux/dma-mapping.h:459
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
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
In drivers/pci/probe.c (ffffffff8162ab6c)
Location: include/linux/dma-mapping.h:501
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81828752)
Location: include/linux/dma-mapping.h:501
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
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
In drivers/pci/probe.c (ffffffff8169a04c)
Location: include/linux/dma-mapping.h:481
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff818b4052)
Location: include/linux/dma-mapping.h:481
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
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
In drivers/pci/probe.c (ffffffff817bb68c)
Location: include/linux/dma-mapping.h:481
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff819ff092)
Location: include/linux/dma-mapping.h:481
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
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
In drivers/pci/probe.c (ffffffff818d718c)
Location: include/linux/dma-mapping.h:486
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a07bfc)
Location: include/linux/dma-mapping.h:486
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
```
```
In drivers/scsi/scsi_lib.c (ffffffff81b7d664)
Location: include/linux/dma-mapping.h:486
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
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
In drivers/pci/probe.c (ffffffff8191a40c)
Location: include/linux/dma-mapping.h:487
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a50a7a)
Location: include/linux/dma-mapping.h:487
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
```
```
In drivers/scsi/scsi_lib.c (ffffffff81bd13f4)
Location: include/linux/dma-mapping.h:487
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
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
In drivers/pci/probe.c (ffffffff8196280c)
Location: include/linux/dma-mapping.h:480
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/dma/hsu/hsu.c (ffffffff81a9c74a)
Location: include/linux/dma-mapping.h:480
Inline: True
Inline callers:
  - drivers/dma/hsu/hsu.c:hsu_dma_probe
```
```
In drivers/scsi/scsi_lib.c (ffffffff81c26064)
Location: include/linux/dma-mapping.h:480
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
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
In drivers/pci/probe.c (ffff8000106df210)
Location: include/linux/dma-mapping.h:726
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/dma/bcm2835-dma.c (ffff8000108046c8)
Location: include/linux/dma-mapping.h:726
Inline: True
Inline callers:
  - drivers/dma/bcm2835-dma.c:bcm2835_dma_probe
```
```
In drivers/dma/mxs-dma.c (ffff80001148f0a0)
Location: include/linux/dma-mapping.h:726
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_probe
```
```
In drivers/scsi/scsi_lib.c (ffff800010975d74)
Location: include/linux/dma-mapping.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
```
In drivers/mmc/core/queue.c (ffff800010b44480)
Location: include/linux/dma-mapping.h:726
Inline: True
Inline callers:
  - drivers/mmc/core/queue.c:mmc_init_queue
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
In drivers/pci/probe.c (c087aeb0)
Location: include/linux/dma-mapping.h:726
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/dma/mxs-dma.c (c158eae8)
Location: include/linux/dma-mapping.h:726
Inline: True
Inline callers:
  - drivers/dma/mxs-dma.c:mxs_dma_probe
```
```
In drivers/scsi/scsi_lib.c (c0a4a660)
Location: include/linux/dma-mapping.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
```
In drivers/mmc/core/queue.c (c0c1e004)
Location: include/linux/dma-mapping.h:726
Inline: True
Inline callers:
  - drivers/mmc/core/queue.c:mmc_init_queue
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
In drivers/pci/probe.c (c00000000085789c)
Location: include/linux/dma-mapping.h:726
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/scsi/scsi_lib.c (c000000000a30110)
Location: include/linux/dma-mapping.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
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
In drivers/pci/probe.c (ffffffe0004b7286)
Location: include/linux/dma-mapping.h:726
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/scsi/scsi_lib.c (ffffffe0005de456)
Location: include/linux/dma-mapping.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
```
In drivers/mmc/core/queue.c (ffffffe000719d6e)
Location: include/linux/dma-mapping.h:726
Inline: True
Inline callers:
  - drivers/mmc/core/queue.c:mmc_init_queue
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
In drivers/pci/probe.c (ffffffff81570169)
Location: include/linux/dma-mapping.h:726
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81726f42)
Location: include/linux/dma-mapping.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
```
In drivers/nvme/host/pci.c (ffffffff81750cc2)
Location: include/linux/dma-mapping.h:726
Inline: True
Inline callers:
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
In drivers/pci/probe.c (ffffffff8155e8c9)
Location: include/linux/dma-mapping.h:726
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81700372)
Location: include/linux/dma-mapping.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
```
In drivers/nvme/host/pci.c (ffffffff81730b62)
Location: include/linux/dma-mapping.h:726
Inline: True
Inline callers:
  - drivers/nvme/host/pci.c:nvme_reset_work
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
In drivers/pci/probe.c (ffffffff8156f999)
Location: include/linux/dma-mapping.h:726
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff81765d12)
Location: include/linux/dma-mapping.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
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
In drivers/pci/probe.c (ffffffff81589e79)
Location: include/linux/dma-mapping.h:726
Inline: True
Inline callers:
  - drivers/pci/probe.c:pci_device_add
```
```
In drivers/scsi/scsi_lib.c (ffffffff817813a2)
Location: include/linux/dma-mapping.h:726
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:__scsi_init_queue
```
</details>
</li>
</ul>

## Differences
