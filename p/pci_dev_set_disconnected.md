# Function: <code>pci_dev_set_disconnected</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pci_dev_set_disconnected(struct pci_dev *dev, void *unused);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pcie-dpc.c (ffffffff814c4603)
Location: drivers/pci/pci.h:278
Inline: True
Inline callers:
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff814c8ba6)
Location: drivers/pci/pci.h:278
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
```
**Symbols:**

```
ffffffff814c4230-ffffffff814c4240: pci_dev_set_disconnected (STB_LOCAL)
ffffffff814c89c0-ffffffff814c89d0: pci_dev_set_disconnected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pci_dev_set_disconnected(struct pci_dev *dev, void *unused);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/pcie-dpc.c (ffffffff81504b1e)
Location: drivers/pci/pci.h:281
Inline: True
Inline callers:
  - drivers/pci/pcie/pcie-dpc.c:interrupt_event_handler
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81509166)
Location: drivers/pci/pci.h:281
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
```
**Symbols:**

```
ffffffff81504480-ffffffff81504490: pci_dev_set_disconnected (STB_LOCAL)
ffffffff81508f70-ffffffff81508f80: pci_dev_set_disconnected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pci_dev_set_disconnected(struct pci_dev *dev, void *unused);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pcie/err.c (ffffffff81530f98)
Location: drivers/pci/pci.h:293
Inline: True
Inline callers:
  - drivers/pci/pcie/err.c:pcie_do_fatal_recovery
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8153a0a2)
Location: drivers/pci/pci.h:293
Inline: True
Inline callers:
  - drivers/pci/hotplug/pciehp_pci.c:pciehp_unconfigure_device
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8153ffb5)
Location: drivers/pci/pci.h:293
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff81530ba0-ffffffff81530bb0: pci_dev_set_disconnected (STB_LOCAL)
ffffffff81539ed0-ffffffff81539ee0: pci_dev_set_disconnected (STB_LOCAL)
ffffffff8153fc60-ffffffff8153fc70: pci_dev_set_disconnected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pci_dev_set_disconnected(struct pci_dev *dev, void *unused);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815511e0)
Location: drivers/pci/pci.h:352
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815578bb)
Location: drivers/pci/pci.h:352
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff815511e0-ffffffff81551220: pci_dev_set_disconnected (STB_LOCAL)
ffffffff81557120-ffffffff81557160: pci_dev_set_disconnected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pci_dev_set_disconnected(struct pci_dev *dev, void *unused);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81581160)
Location: drivers/pci/pci.h:357
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815878ea)
Location: drivers/pci/pci.h:357
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff81581160-ffffffff815811a0: pci_dev_set_disconnected (STB_LOCAL)
ffffffff81587160-ffffffff815871a0: pci_dev_set_disconnected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pci_dev_set_disconnected(struct pci_dev *dev, void *unused);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815a2c60)
Location: drivers/pci/pci.h:391
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815a92aa)
Location: drivers/pci/pci.h:391
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff815a2c60-ffffffff815a2ca0: pci_dev_set_disconnected (STB_LOCAL)
ffffffff815a8b30-ffffffff815a8b70: pci_dev_set_disconnected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pci_dev_set_disconnected(struct pci_dev *dev, void *unused);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8164b7e0)
Location: drivers/pci/pci.h:396
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81651f35)
Location: drivers/pci/pci.h:396
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff8164b7e0-ffffffff8164b820: pci_dev_set_disconnected (STB_LOCAL)
ffffffff816517e0-ffffffff81651820: pci_dev_set_disconnected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pci_dev_set_disconnected(struct pci_dev *dev, void *unused);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8166fb60)
Location: drivers/pci/pci.h:379
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff816748f5)
Location: drivers/pci/pci.h:379
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff8166fb60-ffffffff8166fba0: pci_dev_set_disconnected (STB_LOCAL)
ffffffff816741a0-ffffffff816741e0: pci_dev_set_disconnected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pci_dev_set_disconnected(struct pci_dev *dev, void *unused);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81652060)
Location: drivers/pci/pci.h:372
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81656e25)
Location: drivers/pci/pci.h:372
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff81652060-ffffffff816520a0: pci_dev_set_disconnected (STB_LOCAL)
ffffffff816566d0-ffffffff81656710: pci_dev_set_disconnected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pci_dev_set_disconnected(struct pci_dev *dev, void *unused);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff816c3db0)
Location: drivers/pci/pci.h:393
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff816c8da5)
Location: drivers/pci/pci.h:393
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff816c3db0-ffffffff816c3df0: pci_dev_set_disconnected (STB_LOCAL)
ffffffff816c86a0-ffffffff816c86e0: pci_dev_set_disconnected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pci_dev_set_disconnected(struct pci_dev *dev, void *unused);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff817e98e0)
Location: drivers/pci/pci.h:354
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff817eeffc)
Location: drivers/pci/pci.h:354
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff817e98e0-ffffffff817e9926: pci_dev_set_disconnected (STB_LOCAL)
ffffffff817ee850-ffffffff817ee896: pci_dev_set_disconnected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pci_dev_set_disconnected(struct pci_dev *dev, void *unused);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8190f8e0)
Location: drivers/pci/pci.h:354
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff81916afc)
Location: drivers/pci/pci.h:354
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff8190f8e0-ffffffff8190f8f4: pci_dev_set_disconnected (STB_LOCAL)
ffffffff81916750-ffffffff81916764: pci_dev_set_disconnected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pci_dev_set_disconnected(struct pci_dev *dev, void *unused);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81952fd0)
Location: drivers/pci/pci.h:352
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8195a0ec)
Location: drivers/pci/pci.h:352
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff81952fd0-ffffffff81952fee: pci_dev_set_disconnected (STB_LOCAL)
ffffffff81959f10-ffffffff81959f2e: pci_dev_set_disconnected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pci_dev_set_disconnected(struct pci_dev *dev, void *unused);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci-driver.c (ffffffff81970f30)
Location: drivers/pci/pci.h:363
Inline: False
```
```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff8199c460)
Location: drivers/pci/pci.h:363
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff819a368c)
Location: drivers/pci/pci.h:363
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff81970f30-ffffffff81970f4e: pci_dev_set_disconnected (STB_LOCAL)
ffffffff8199c460-ffffffff8199c47e: pci_dev_set_disconnected (STB_LOCAL)
ffffffff819a34b0-ffffffff819a34ce: pci_dev_set_disconnected (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pci_dev_set_disconnected(struct pci_dev *dev, void *unused);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffff80001070b500)
Location: drivers/pci/pci.h:391
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffff80001071257c)
Location: drivers/pci/pci.h:391
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffff80001070b500-ffff80001070b54c: pci_dev_set_disconnected (STB_LOCAL)
ffff800010711cf8-ffff800010711d44: pci_dev_set_disconnected (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_dev_set_disconnected(struct pci_dev *dev, void *unused);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffffffe0004d813a)
Location: drivers/pci/pci.h:391
Inline: False
```
**Symbols:**

```
ffffffe0004d813a-ffffffe0004d8180: pci_dev_set_disconnected (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pci_dev_set_disconnected(struct pci_dev *dev, void *unused);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81596470)
Location: drivers/pci/pci.h:391
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159ca7a)
Location: drivers/pci/pci.h:391
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff81596470-ffffffff815964b0: pci_dev_set_disconnected (STB_LOCAL)
ffffffff8159c340-ffffffff8159c380: pci_dev_set_disconnected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pci_dev_set_disconnected(struct pci_dev *dev, void *unused);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff81585600)
Location: drivers/pci/pci.h:391
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8158bc0a)
Location: drivers/pci/pci.h:391
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff81585600-ffffffff81585640: pci_dev_set_disconnected (STB_LOCAL)
ffffffff8158b4d0-ffffffff8158b510: pci_dev_set_disconnected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pci_dev_set_disconnected(struct pci_dev *dev, void *unused);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815969b0)
Location: drivers/pci/pci.h:391
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff8159cffa)
Location: drivers/pci/pci.h:391
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff815969b0-ffffffff815969f0: pci_dev_set_disconnected (STB_LOCAL)
ffffffff8159c880-ffffffff8159c8c0: pci_dev_set_disconnected (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int pci_dev_set_disconnected(struct pci_dev *dev, void *unused);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/pciehp_pci.c (ffffffff815b0e30)
Location: drivers/pci/pci.h:391
Inline: False
```
```
In drivers/pci/hotplug/acpiphp_glue.c (ffffffff815b742a)
Location: drivers/pci/pci.h:391
Inline: True
Inline callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff815b0e30-ffffffff815b0e70: pci_dev_set_disconnected (STB_LOCAL)
ffffffff815b6cb0-ffffffff815b6cf0: pci_dev_set_disconnected (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
