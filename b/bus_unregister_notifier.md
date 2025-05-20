# Function: <code>bus_unregister_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bus_unregister_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8154a5e0)
Location: drivers/base/bus.c:993
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
```
**Symbols:**

```
ffffffff8154a5e0-ffffffff8154a5fe: bus_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bus_unregister_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8159c210)
Location: drivers/base/bus.c:992
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
```
**Symbols:**

```
ffffffff8159c210-ffffffff8159c22e: bus_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bus_unregister_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff815ca770)
Location: drivers/base/bus.c:992
Inline: False
Direct callers:
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
```
**Symbols:**

```
ffffffff815ca770-ffffffff815ca78e: bus_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bus_unregister_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff815df440)
Location: drivers/base/bus.c:951
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
```
**Symbols:**

```
ffffffff815df440-ffffffff815df45e: bus_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bus_unregister_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81646470)
Location: drivers/base/bus.c:951
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
```
**Symbols:**

```
ffffffff81646470-ffffffff8164648e: bus_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bus_unregister_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81681950)
Location: drivers/base/bus.c:949
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/dmar.c:dmar_free_unused_resources
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
```
**Symbols:**

```
ffffffff81681950-ffffffff8168196e: bus_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bus_unregister_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816a13f0)
Location: drivers/base/bus.c:956
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/dmar.c:dmar_free_unused_resources
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
```
**Symbols:**

```
ffffffff816a13f0-ffffffff816a140e: bus_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bus_unregister_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816da1c0)
Location: drivers/base/bus.c:930
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/dmar.c:dmar_free_unused_resources
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
```
**Symbols:**

```
ffffffff816da1c0-ffffffff816da1de: bus_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bus_unregister_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816fe170)
Location: drivers/base/bus.c:906
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/dmar.c:dmar_free_unused_resources
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
```
**Symbols:**

```
ffffffff816fe170-ffffffff816fe18e: bus_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bus_unregister_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817b74c0)
Location: drivers/base/bus.c:907
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/intel/dmar.c:dmar_free_unused_resources
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_remove
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
```
**Symbols:**

```
ffffffff817b74c0-ffffffff817b74de: bus_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bus_unregister_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817cc1e0)
Location: drivers/base/bus.c:907
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_free_unused_resources
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_remove
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
```
**Symbols:**

```
ffffffff817cc1e0-ffffffff817cc1fe: bus_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bus_unregister_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff817afb50)
Location: drivers/base/bus.c:890
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_free_unused_resources
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_remove
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_probe
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
```
**Symbols:**

```
ffffffff817afb50-ffffffff817afb6e: bus_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bus_unregister_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81838cd0)
Location: drivers/base/bus.c:886
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_free_unused_resources
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_unregister_device
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_register_device
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
```
**Symbols:**

```
ffffffff81838cd0-ffffffff81838cee: bus_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bus_unregister_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8197b200)
Location: drivers/base/bus.c:888
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_free_unused_resources
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_unregister_device
  - drivers/vfio/pci/vfio_pci_core.c:vfio_pci_core_register_device
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
```
**Symbols:**

```
ffffffff8197b200-ffffffff8197b226: bus_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bus_unregister_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81ae8240)
Location: drivers/base/bus.c:888
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_free_unused_resources
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
```
**Symbols:**

```
ffffffff81ae8240-ffffffff81ae8266: bus_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bus_unregister_notifier(const struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81b36a60)
Location: drivers/base/bus.c:967
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_free_unused_resources
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
```
**Symbols:**

```
ffffffff81b36a60-ffffffff81b36aaf: bus_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bus_unregister_notifier(const struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff81b8e480)
Location: drivers/base/bus.c:967
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_free_unused_resources
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
```
**Symbols:**

```
ffffffff81b8e480-ffffffff81b8e4cf: bus_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int bus_unregister_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffff8000108e9118)
Location: drivers/base/bus.c:906
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
```
**Symbols:**

```
ffff8000108e9118-ffff8000108e9150: bus_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bus_unregister_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (c09d742c)
Location: drivers/base/bus.c:906
Inline: False
Direct callers:
  - drivers/bus/ti-sysc.c:sysc_exit
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
```
**Symbols:**

```
c09d742c-c09d7450: bus_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bus_unregister_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (c00000000097f950)
Location: drivers/base/bus.c:906
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
```
**Symbols:**

```
c00000000097f950-c00000000097f98c: bus_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bus_unregister_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffe00057d0a8)
Location: drivers/base/bus.c:906
Inline: False
Direct callers:
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
```
**Symbols:**

```
ffffffe00057d0a8-ffffffe00057d0e0: bus_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int bus_unregister_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816c3960)
Location: drivers/base/bus.c:906
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/dmar.c:dmar_free_unused_resources
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_exit
```
**Symbols:**

```
ffffffff816c3960-ffffffff816c397e: bus_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bus_unregister_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8169ec10)
Location: drivers/base/bus.c:906
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/dmar.c:dmar_free_unused_resources
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_exit
```
**Symbols:**

```
ffffffff8169ec10-ffffffff8169ec2e: bus_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bus_unregister_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff816f1e30)
Location: drivers/base/bus.c:906
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/dmar.c:dmar_free_unused_resources
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
```
**Symbols:**

```
ffffffff816f1e30-ffffffff816f1e4e: bus_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bus_unregister_notifier(struct bus_type *bus, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/bus.c (ffffffff8170c670)
Location: drivers/base/bus.c:906
Inline: False
Direct callers:
  - drivers/iommu/iommu.c:bus_set_iommu
  - drivers/iommu/dmar.c:dmar_free_unused_resources
  - drivers/usb/core/usb.c:usb_exit
  - drivers/usb/core/usb.c:usb_init
  - drivers/input/serio/i8042.c:i8042_exit
  - drivers/i2c/i2c-dev.c:i2c_dev_exit
```
**Symbols:**

```
ffffffff8170c670-ffffffff8170c68e: bus_unregister_notifier (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct bus_type *bus</code> ➡️ <code>const struct bus_type *bus</code>
</li>
</ul>
</details>
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
