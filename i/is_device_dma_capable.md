# Function: <code>is_device_dma_capable</code>

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
In arch/x86/kernel/pci-dma.c (ffffffff81034cf7)
Location: include/linux/dma-mapping.h:81
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:arch_dma_alloc_attrs
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
In arch/x86/kernel/pci-dma.c (ffffffff81033ed7)
Location: include/linux/dma-mapping.h:132
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:arch_dma_alloc_attrs
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
In arch/x86/kernel/pci-dma.c (ffffffff81033b07)
Location: include/linux/dma-mapping.h:143
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:arch_dma_alloc_attrs
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
In arch/x86/kernel/pci-dma.c (ffffffff81031c76)
Location: include/linux/dma-mapping.h:150
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:arch_dma_alloc_attrs
```
```
In drivers/usb/core/buffer.c (ffffffff816bab73)
Location: include/linux/dma-mapping.h:150
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/core/buffer.c:hcd_buffer_create
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
In arch/x86/kernel/pci-dma.c (ffffffff81033f96)
Location: include/linux/dma-mapping.h:153
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:arch_dma_alloc_attrs
```
```
In drivers/usb/core/buffer.c (ffffffff81726533)
Location: include/linux/dma-mapping.h:153
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/core/buffer.c:hcd_buffer_create
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
In arch/x86/kernel/pci-dma.c (ffffffff810352a8)
Location: include/linux/dma-mapping.h:153
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:arch_dma_alloc_attrs
```
```
In drivers/usb/core/buffer.c (ffffffff81765330)
Location: include/linux/dma-mapping.h:153
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/core/buffer.c:hcd_buffer_create
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
In arch/x86/kernel/pci-dma.c (ffffffff81036488)
Location: include/linux/dma-mapping.h:152
Inline: True
Inline callers:
  - arch/x86/kernel/pci-dma.c:arch_dma_alloc_attrs
```
```
In drivers/usb/core/buffer.c (ffffffff817898ec)
Location: include/linux/dma-mapping.h:152
Inline: True
Inline callers:
  - drivers/usb/core/buffer.c:hcd_buffer_free
  - drivers/usb/core/buffer.c:hcd_buffer_alloc
  - drivers/usb/core/buffer.c:hcd_buffer_create
```
</details>
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
