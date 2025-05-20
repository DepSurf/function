# Function: <code>xhci_get_usb3_hcd</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/xhci.c (ffffffff81eeb934)
Location: drivers/usb/host/xhci.h:1969
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81af4d27)
Location: drivers/usb/host/xhci.h:1969
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81aff895)
Location: drivers/usb/host/xhci.h:1969
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
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
In drivers/usb/host/xhci.c (ffffffff81c797d3)
Location: drivers/usb/host/xhci.h:1971
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81c82558)
Location: drivers/usb/host/xhci.h:1971
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
```
```
In drivers/usb/host/xhci-hub.c (ffffffff81c8e5f5)
Location: drivers/usb/host/xhci.h:1971
Inline: True
Inline callers:
  - drivers/usb/host/xhci-hub.c:xhci_enter_test_mode
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
In drivers/usb/host/xhci.c (ffffffff81ce0a91)
Location: drivers/usb/host/xhci.h:1980
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81ce9271)
Location: drivers/usb/host/xhci.h:1980
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
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
In drivers/usb/host/xhci.c (ffffffff81d95be1)
Location: drivers/usb/host/xhci.h:1956
Inline: True
Inline callers:
  - drivers/usb/host/xhci.c:xhci_gen_setup
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81d9ea8a)
Location: drivers/usb/host/xhci.h:1956
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_setup_addressable_virt_dev
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
