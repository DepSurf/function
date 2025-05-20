# Function: <code>device_trylock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81435a01)
Location: include/linux/device.h:960
Inline: True
```
```
In drivers/usb/core/usb.c (ffffffff816033e8)
Location: include/linux/device.h:960
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814814e1)
Location: include/linux/device.h:976
Inline: True
```
```
In drivers/usb/core/usb.c (ffffffff816630a8)
Location: include/linux/device.h:976
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a2a11)
Location: include/linux/device.h:1085
Inline: True
```
```
In drivers/usb/core/usb.c (ffffffff81690e98)
Location: include/linux/device.h:1085
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ac841)
Location: include/linux/device.h:1089
Inline: True
```
```
In drivers/usb/core/usb.c (ffffffff816a642c)
Location: include/linux/device.h:1089
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814eb931)
Location: include/linux/device.h:1097
Inline: True
```
```
In drivers/usb/core/usb.c (ffffffff817117fc)
Location: include/linux/device.h:1097
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151b371)
Location: include/linux/device.h:1142
Inline: True
```
```
In drivers/usb/core/usb.c (ffffffff8175052c)
Location: include/linux/device.h:1142
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
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
In drivers/pci/pci.c (ffffffff81531221)
Location: include/linux/device.h:1195
Inline: True
```
```
In drivers/usb/core/usb.c (ffffffff8177496c)
Location: include/linux/device.h:1195
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
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
In drivers/pci/pci.c (ffffffff81560a69)
Location: include/linux/device.h:1228
Inline: True
```
```
In drivers/usb/core/usb.c (ffffffff817b2a7d)
Location: include/linux/device.h:1228
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
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
In drivers/pci/pci.c (ffffffff81581b89)
Location: include/linux/device.h:1470
Inline: True
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817d7c5b)
Location: include/linux/device.h:1470
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
```
In drivers/usb/core/usb.c (ffffffff817e31ad)
Location: include/linux/device.h:1470
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
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
In drivers/pci/pci.c (ffffffff81628b27)
Location: include/linux/device.h:777
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818a55e9)
Location: include/linux/device.h:777
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
```
In drivers/usb/core/usb.c (ffffffff818b1cfd)
Location: include/linux/device.h:777
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
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
In drivers/pci/pci.c (ffffffff8164ed47)
Location: include/linux/device.h:745
Inline: True
Inline callers:
  - drivers/pci/pci.c:pci_slot_trylock
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff818b4729)
Location: include/linux/device.h:745
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
```
In drivers/usb/core/usb.c (ffffffff818c06ed)
Location: include/linux/device.h:745
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
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
In drivers/pci/pci.c (ffffffff816323da)
Location: include/linux/device.h:751
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81897a8a)
Location: include/linux/device.h:751
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
```
In drivers/usb/core/usb.c (ffffffff818a396d)
Location: include/linux/device.h:751
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
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
In drivers/pci/pci.c (ffffffff816a26aa)
Location: include/linux/device.h:768
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
```
In drivers/usb/core/usb.c (ffffffff8193852d)
Location: include/linux/device.h:768
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
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
In drivers/pci/pci.c (ffffffff817c4722)
Location: include/linux/device.h:843
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
```
In drivers/usb/core/usb.c (ffffffff81a8fe15)
Location: include/linux/device.h:843
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
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
In drivers/pci/pci.c (ffffffff818e1682)
Location: include/linux/device.h:840
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
```
In drivers/usb/core/usb.c (ffffffff81c11c95)
Location: include/linux/device.h:840
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
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
In drivers/pci/pci.c (ffffffff81924ac2)
Location: include/linux/device.h:966
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
```
In drivers/usb/core/usb.c (ffffffff81c78a55)
Location: include/linux/device.h:966
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
```
```
In drivers/platform/x86/intel/pmc/mtl.c (ffffffff81ddd0cb)
Location: include/linux/device.h:966
Inline: True
Inline callers:
  - drivers/platform/x86/intel/pmc/mtl.c:mtl_set_device_d3
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
In drivers/pci/pci.c (ffffffff8196d192)
Location: include/linux/device.h:998
Inline: True
Inline callers:
  - drivers/pci/pci.c:__pci_reset_slot
  - drivers/pci/pci.c:pci_bus_trylock
  - drivers/pci/pci.c:pci_try_reset_function
```
```
In drivers/usb/core/usb.c (ffffffff81d2d455)
Location: include/linux/device.h:998
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
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
In drivers/pci/pci.c (ffff8000106e4d8c)
Location: include/linux/device.h:1470
Inline: True
```
```
In drivers/usb/core/usb.c (ffff800010a116d0)
Location: include/linux/device.h:1470
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
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
In drivers/pci/pci.c (c0880a74)
Location: include/linux/device.h:1470
Inline: True
```
```
In drivers/usb/core/usb.c (c0ae9f88)
Location: include/linux/device.h:1470
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
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
In drivers/pci/pci.c (c00000000085f490)
Location: include/linux/device.h:1470
Inline: True
```
```
In drivers/vfio/pci/vfio_pci.c (c000000000ab73d4)
Location: include/linux/device.h:1470
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
```
In drivers/usb/core/usb.c (c000000000ac87e0)
Location: include/linux/device.h:1470
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
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
In drivers/pci/pci.c (ffffffe0004bc0ec)
Location: include/linux/device.h:1470
Inline: True
```
```
In drivers/usb/core/usb.c (ffffffe0006371ee)
Location: include/linux/device.h:1470
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
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
In drivers/pci/pci.c (ffffffff815760a9)
Location: include/linux/device.h:1470
Inline: True
```
```
In drivers/usb/core/usb.c (ffffffff8179b58d)
Location: include/linux/device.h:1470
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
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
In drivers/pci/pci.c (ffffffff81564809)
Location: include/linux/device.h:1470
Inline: True
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff81781d0b)
Location: include/linux/device.h:1470
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
```
In drivers/usb/core/usb.c (ffffffff8178d21d)
Location: include/linux/device.h:1470
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
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
In drivers/pci/pci.c (ffffffff815758d9)
Location: include/linux/device.h:1470
Inline: True
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817ccadb)
Location: include/linux/device.h:1470
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
```
In drivers/usb/core/usb.c (ffffffff817d802d)
Location: include/linux/device.h:1470
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
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
In drivers/pci/pci.c (ffffffff8158fea9)
Location: include/linux/device.h:1470
Inline: True
```
```
In drivers/vfio/pci/vfio_pci.c (ffffffff817e6d7b)
Location: include/linux/device.h:1470
Inline: True
Inline callers:
  - drivers/vfio/pci/vfio_pci.c:vfio_pci_disable
```
```
In drivers/usb/core/usb.c (ffffffff817f22cd)
Location: include/linux/device.h:1470
Inline: True
Inline callers:
  - drivers/usb/core/usb.c:usb_lock_device_for_reset
```
</details>
</li>
</ul>

## Differences
