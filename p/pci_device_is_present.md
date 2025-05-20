# Function: <code>pci_device_is_present</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool pci_device_is_present(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81434e50)
Location: drivers/pci/pci.c:4571
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff81434e50-ffffffff81434e94: pci_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool pci_device_is_present(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814807c0)
Location: drivers/pci/pci.c:4923
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff814807c0-ffffffff81480804: pci_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool pci_device_is_present(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a1e10)
Location: drivers/pci/pci.c:4931
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff814a1e10-ffffffff814a1e54: pci_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool pci_device_is_present(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ad080)
Location: drivers/pci/pci.c:5089
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff814ad080-ffffffff814ad0d0: pci_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool pci_device_is_present(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ec450)
Location: drivers/pci/pci.c:5113
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff814ec450-ffffffff814ec4a0: pci_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool pci_device_is_present(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151b980)
Location: drivers/pci/pci.c:5493
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff8151b980-ffffffff8151b9d0: pci_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool pci_device_is_present(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815317d0)
Location: drivers/pci/pci.c:5804
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff815317d0-ffffffff8153181d: pci_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool pci_device_is_present(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81560f20)
Location: drivers/pci/pci.c:5900
Inline: True
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff81560f20-ffffffff81560f6d: pci_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_device_is_present(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81584c0d)
Location: drivers/pci/pci.c:6060
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff81581cb0-ffffffff81581cf4: pci_device_is_present.part.0 (STB_LOCAL)
ffffffff81581d00-ffffffff81581d1c: pci_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool pci_device_is_present(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162b848)
Location: drivers/pci/pci.c:6083
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_update_current_state
  - drivers/pci/pci.c:pci_update_current_state
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff816266a0-ffffffff816266ed: pci_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool pci_device_is_present(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81651543)
Location: drivers/pci/pci.c:6157
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_update_current_state
  - drivers/pci/pci.c:pci_update_current_state
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff8164c660-ffffffff8164c6ad: pci_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool pci_device_is_present(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81633fbc)
Location: drivers/pci/pci.c:6206
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_update_current_state
  - drivers/pci/pci.c:pci_update_current_state
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
```
**Symbols:**

```
ffffffff8162f1e0-ffffffff8162f22d: pci_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool pci_device_is_present(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff816a419c)
Location: drivers/pci/pci.c:6396
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/pci.c:pci_update_current_state
  - drivers/pci/pci.c:pci_update_current_state
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
```
**Symbols:**

```
ffffffff8169eb10-ffffffff8169eb5d: pci_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool pci_device_is_present(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817c658c)
Location: drivers/pci/pci.c:6493
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
```
**Symbols:**

```
ffffffff817bfde0-ffffffff817bfe40: pci_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool pci_device_is_present(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818dc3c0)
Location: drivers/pci/pci.c:6440
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
```
**Symbols:**

```
ffffffff818dc3c0-ffffffff818dc432: pci_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool pci_device_is_present(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8191f6f0)
Location: drivers/pci/pci.c:6562
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
```
**Symbols:**

```
ffffffff8191f6f0-ffffffff8191f762: pci_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool pci_device_is_present(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81967860)
Location: drivers/pci/pci.c:6706
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/virtio/virtio_pci_common.c:virtio_pci_remove
```
**Symbols:**

```
ffffffff81967860-ffffffff819678d2: pci_device_is_present (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_device_is_present(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e926c)
Location: drivers/pci/pci.c:6060
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffff8000106e4ee8-ffff8000106e4f44: pci_device_is_present.part.0 (STB_LOCAL)
ffff8000106e4f48-ffff8000106e4f94: pci_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_device_is_present(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (c0884228)
Location: drivers/pci/pci.c:6060
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
**Symbols:**

```
c0880b3c-c0880ba0: pci_device_is_present.part.0 (STB_LOCAL)
c0880ba0-c0880bd0: pci_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_device_is_present(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (c000000000864120)
Location: drivers/pci/pci.c:6060
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
**Symbols:**

```
c00000000085f5f0-c00000000085f65c: pci_device_is_present.part.0 (STB_LOCAL)
c00000000085f660-c00000000085f688: pci_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_device_is_present(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bf664)
Location: drivers/pci/pci.c:6060
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
```
**Symbols:**

```
ffffffe0004bc1b4-ffffffe0004bc1e6: pci_device_is_present.part.0 (STB_LOCAL)
ffffffe0004bc1e6-ffffffe0004bc21c: pci_device_is_present (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_device_is_present(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8157912d)
Location: drivers/pci/pci.c:6060
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/nvme/host/pci.c:nvme_remove
```
**Symbols:**

```
ffffffff815761d0-ffffffff81576214: pci_device_is_present.part.0 (STB_LOCAL)
ffffffff81576220-ffffffff8157623c: pci_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_device_is_present(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8156786d)
Location: drivers/pci/pci.c:6060
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
  - drivers/nvme/host/pci.c:nvme_remove
```
**Symbols:**

```
ffffffff81564930-ffffffff81564974: pci_device_is_present.part.0 (STB_LOCAL)
ffffffff81564980-ffffffff8156499c: pci_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_device_is_present(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff8157895d)
Location: drivers/pci/pci.c:6060
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff81575a00-ffffffff81575a44: pci_device_is_present.part.0 (STB_LOCAL)
ffffffff81575a50-ffffffff81575a6c: pci_device_is_present (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool pci_device_is_present(struct pci_dev *pdev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pci/pci.c (ffffffff81592e1d)
Location: drivers/pci/pci.c:6060
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
Direct callers:
  - drivers/pci/pci.c:pci_bridge_wait_for_secondary_bus
  - drivers/pci/hotplug/acpiphp_glue.c:trim_stale_devices
```
**Symbols:**

```
ffffffff8158ffd0-ffffffff81590014: pci_device_is_present.part.0 (STB_LOCAL)
ffffffff81590020-ffffffff8159003c: pci_device_is_present (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
