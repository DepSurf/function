# Function: <code>__rounddown_pow_of_two</code>

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
In mm/page_alloc.c (ffffffff81191c7c)
Location: include/linux/log2.h:70
Inline: True
```
```
In mm/percpu.c (ffffffff81208d65)
Location: include/linux/log2.h:70
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/memory.c (ffffffff811bbc80)
Location: include/linux/log2.h:70
Inline: True
```
```
In lib/rhashtable.c (ffffffff81400362)
Location: include/linux/log2.h:70
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8150ba5c)
Location: include/linux/log2.h:70
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:byt_set_termios
```
```
In drivers/iommu/intel-svm.c (ffffffff8153b65a)
Location: include/linux/log2.h:70
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81635d81)
Location: include/linux/log2.h:70
Inline: True
```
```
In drivers/clk/clk-divider.c (ffffffff816e9444)
Location: include/linux/log2.h:70
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
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
In mm/page_alloc.c (ffffffff811a684d)
Location: include/linux/log2.h:70
Inline: True
```
```
In mm/percpu.c (ffffffff8122ea8c)
Location: include/linux/log2.h:70
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/memory.c (ffffffff811d642b)
Location: include/linux/log2.h:70
Inline: True
```
```
In lib/rhashtable.c (ffffffff81447c22)
Location: include/linux/log2.h:70
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
```
```
In drivers/tty/serial/8250/8250_pci.c (ffffffff8155cfcb)
Location: include/linux/log2.h:70
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_pci.c:byt_set_termios
```
```
In drivers/iommu/intel-svm.c (ffffffff8159016b)
Location: include/linux/log2.h:70
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81696dc5)
Location: include/linux/log2.h:70
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
```
```
In drivers/clk/clk-divider.c (ffffffff8174d8fd)
Location: include/linux/log2.h:70
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
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
In mm/page_alloc.c (ffffffff811b6b86)
Location: include/linux/log2.h:64
Inline: True
```
```
In mm/percpu.c (ffffffff8124101c)
Location: include/linux/log2.h:64
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/memory.c (ffffffff811e638b)
Location: include/linux/log2.h:64
Inline: True
```
```
In lib/rhashtable.c (ffffffff81466572)
Location: include/linux/log2.h:64
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
  - lib/rhashtable.c:rhashtable_init
```
```
In drivers/clk/clk-divider.c (ffffffff8153616d)
Location: include/linux/log2.h:64
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/iommu/intel-svm.c (ffffffff815bd9fc)
Location: include/linux/log2.h:64
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816c4c7c)
Location: include/linux/log2.h:64
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
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
In mm/page_alloc.c (ffffffff811beac6)
Location: include/linux/log2.h:64
Inline: True
```
```
In mm/percpu.c (ffffffff811e4c90)
Location: include/linux/log2.h:64
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/memory.c (ffffffff811f140b)
Location: include/linux/log2.h:64
Inline: True
```
```
In lib/rhashtable.c (ffffffff8146be28)
Location: include/linux/log2.h:64
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In drivers/clk/clk-divider.c (ffffffff81549551)
Location: include/linux/log2.h:64
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/iommu/intel-svm.c (ffffffff815d3b0b)
Location: include/linux/log2.h:64
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816d926e)
Location: include/linux/log2.h:64
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
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
In kernel/memremap.c (ffffffff811c8cd1)
Location: include/linux/log2.h:69
Inline: True
Inline callers:
  - kernel/memremap.c:order_at
```
```
In mm/page_alloc.c (ffffffff811d3842)
Location: include/linux/log2.h:69
Inline: True
```
```
In mm/percpu.c (ffffffff811faef2)
Location: include/linux/log2.h:69
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/memory.c (ffffffff812080d8)
Location: include/linux/log2.h:69
Inline: True
```
```
In lib/rhashtable.c (ffffffff81498128)
Location: include/linux/log2.h:69
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In drivers/clk/clk-divider.c (ffffffff815acad1)
Location: include/linux/log2.h:69
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/iommu/intel-svm.c (ffffffff8163a83b)
Location: include/linux/log2.h:69
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8174599e)
Location: include/linux/log2.h:69
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
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
In kernel/memremap.c (ffffffff811e924e)
Location: include/linux/log2.h:69
Inline: True
Inline callers:
  - kernel/memremap.c:order_at
```
```
In mm/page_alloc.c (ffffffff811f4b01)
Location: include/linux/log2.h:69
Inline: True
```
```
In mm/percpu.c (ffffffff8121c182)
Location: include/linux/log2.h:69
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/memory.c (ffffffff81228f77)
Location: include/linux/log2.h:69
Inline: True
```
```
In lib/rhashtable.c (ffffffff814ccc99)
Location: include/linux/log2.h:69
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In drivers/clk/clk-divider.c (ffffffff815e4b51)
Location: include/linux/log2.h:69
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/iommu/intel-svm.c (ffffffff81675e33)
Location: include/linux/log2.h:69
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817864be)
Location: include/linux/log2.h:69
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
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
In mm/page_alloc.c (ffffffff81206755)
Location: include/linux/log2.h:69
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_batchsize
```
```
In mm/percpu.c (ffffffff8122f17f)
Location: include/linux/log2.h:69
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/memory.c (ffffffff8123c787)
Location: include/linux/log2.h:69
Inline: True
```
```
In lib/rhashtable.c (ffffffff814e122c)
Location: include/linux/log2.h:69
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In drivers/clk/clk-divider.c (ffffffff815ff171)
Location: include/linux/log2.h:69
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/iommu/intel-svm.c (ffffffff81695633)
Location: include/linux/log2.h:69
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817acede)
Location: include/linux/log2.h:69
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
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
In mm/percpu.c (ffffffff8123f179)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/memory.c (ffffffff8124dfdb)
Location: include/linux/log2.h:65
Inline: True
```
```
In mm/page_alloc.c (ffffffff8126c70f)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_batchsize
```
```
In lib/kfifo.c (ffffffff8150b3ec)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/rhashtable.c (ffffffff8150d01f)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In drivers/clk/clk-divider.c (ffffffff8163185c)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/iommu/intel-svm.c (ffffffff816cd9d1)
Location: include/linux/log2.h:65
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817ebe8a)
Location: include/linux/log2.h:65
Inline: True
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
In mm/percpu.c (ffffffff8124d5d9)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/memory.c (ffffffff8125c50b)
Location: include/linux/log2.h:65
Inline: True
```
```
In mm/page_alloc.c (ffffffff8127b51f)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_batchsize
```
```
In lib/kfifo.c (ffffffff8152920c)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/rhashtable.c (ffffffff8152ae6f)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In drivers/clk/clk-divider.c (ffffffff8165358c)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/iommu/intel-svm.c (ffffffff816f183f)
Location: include/linux/log2.h:65
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8181cd5a)
Location: include/linux/log2.h:65
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8183bd22)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In mm/percpu.c (ffffffff8127b965)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/memory.c (ffffffff8128ba8b)
Location: include/linux/log2.h:65
Inline: True
```
```
In mm/page_alloc.c (ffffffff812ad680)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_batchsize
```
```
In lib/kfifo.c (ffffffff8158c9b5)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/rhashtable.c (ffffffff8158e533)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In drivers/clk/clk-divider.c (ffffffff81703407)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/iommu/intel/svm.c (ffffffff817a9577)
Location: include/linux/log2.h:65
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818ec781)
Location: include/linux/log2.h:65
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8190eb0b)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In mm/percpu.c (ffffffff81be70e4)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/memory.c (ffffffff81296a3b)
Location: include/linux/log2.h:65
Inline: True
```
```
In mm/page_alloc.c (ffffffff812b9060)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_batchsize
```
```
In lib/kfifo.c (ffffffff815a9405)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/rhashtable.c (ffffffff815ab0a3)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In drivers/clk/clk-divider.c (ffffffff81720667)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/iommu/intel/svm.c (ffffffff817b5570)
Location: include/linux/log2.h:65
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f57aa)
Location: include/linux/log2.h:65
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8191663f)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In mm/percpu.c (ffffffff81bd8e8b)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/memory.c (ffffffff8129c5db)
Location: include/linux/log2.h:65
Inline: True
```
```
In mm/page_alloc.c (ffffffff812be530)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_batchsize
```
```
In lib/kfifo.c (ffffffff815b4005)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/rhashtable.c (ffffffff815b5bb1)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In drivers/clk/clk-divider.c (ffffffff817018ac)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818d8df7)
Location: include/linux/log2.h:65
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff818f9ac4)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In mm/percpu.c (ffffffff81cbadff)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/memory.c (ffffffff812dd247)
Location: include/linux/log2.h:65
Inline: True
```
```
In mm/page_alloc.c (ffffffff813016bf)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
```
In lib/kfifo.c (ffffffff8161a1f5)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/rhashtable.c (ffffffff8161c040)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In drivers/clk/clk-divider.c (ffffffff8177c2a8)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8197409a)
Location: include/linux/log2.h:65
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81998392)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In mm/percpu.c (ffffffff81e6c98e)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/memory.c (ffffffff8133ce3c)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/memory.c:fault_around_bytes_set
```
```
In mm/page_alloc.c (ffffffff81368fcf)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
```
In lib/kfifo.c (ffffffff816e77e5)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/rhashtable.c (ffffffff816e9940)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In drivers/clk/clk-divider.c (ffffffff818b2bf4)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad051b)
Location: include/linux/log2.h:65
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81af55d7)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In mm/percpu.c (ffffffff8139b130)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/memory.c (ffffffff813b4a3c)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/memory.c:fault_around_bytes_set
```
```
In mm/page_alloc.c (ffffffff820c7cc9)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_pcp_init
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
```
In lib/kfifo.c (ffffffff817d7625)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/rhashtable.c (ffffffff817d9ae0)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In drivers/clk/clk-divider.c (ffffffff819ff354)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/tty/serial/8250/8250_mid.c (ffffffff81a87ea5)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mid.c:mid8250_set_termios
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c5b66b)
Location: include/linux/log2.h:65
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81c82e47)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In mm/percpu.c (ffffffff813ce1f0)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/memory.c (ffffffff813e967e)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/memory.c:fault_around_bytes_set
```
```
In mm/page_alloc.c (ffffffff8214c730)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_pcp_init
  - mm/page_alloc.c:zone_set_pageset_high_and_batch
```
```
In lib/kfifo.c (ffffffff81816835)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/rhashtable.c (ffffffff81818e60)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In drivers/clk/clk-divider.c (ffffffff81a48012)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/tty/serial/8250/8250_mid.c (ffffffff81ad3595)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mid.c:mid8250_set_termios
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc2cd0)
Location: include/linux/log2.h:65
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81ce9b35)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In mm/percpu.c (ffffffff813f8b60)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/memory.c (ffffffff814145ae)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/memory.c:fault_around_bytes_set
```
```
In mm/page_alloc.c (ffffffff81445af9)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_batchsize
```
```
In security/selinux/ss/avtab.c (ffffffff816f9f56)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - security/selinux/ss/avtab.c:avtab_alloc
```
```
In lib/kfifo.c (ffffffff8185bb15)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/rhashtable.c (ffffffff8185e1b0)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In drivers/clk/clk-divider.c (ffffffff81a93ab8)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/tty/serial/8250/8250_mid.c (ffffffff81b22c74)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/tty/serial/8250/8250_mid.c:mid8250_set_termios
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d779d0)
Location: include/linux/log2.h:65
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81d9f35d)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In mm/percpu.c (ffff8000102e413c)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/memory.c (ffff8000102f3f2c)
Location: include/linux/log2.h:65
Inline: True
```
```
In mm/page_alloc.c (ffff800010312ac0)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_batchsize
```
```
In lib/kfifo.c (ffff800010633b94)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/rhashtable.c (ffff800010635f50)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In drivers/video/fbdev/amba-clcd.c (ffff80001075bd68)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_init_display
```
```
In drivers/clk/clk-divider.c (ffff8000107c425c)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a54680)
Location: include/linux/log2.h:65
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffff800010a79a74)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In mm/percpu.c (c050828c)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/memory.c (c05166e8)
Location: include/linux/log2.h:65
Inline: True
```
```
In mm/page_alloc.c (c052d7c0)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_batchsize
```
```
In fs/pstore/ram.c (c06d6b70)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - fs/pstore/ram.c:ramoops_probe
  - fs/pstore/ram.c:ramoops_probe
  - fs/pstore/ram.c:ramoops_probe
  - fs/pstore/ram.c:ramoops_probe
```
```
In lib/kfifo.c (c07d9f00)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/rhashtable.c (c07dbec0)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In drivers/pci/controller/pci-mvebu.c (c08a969c)
Location: include/linux/log2.h:65
Inline: True
```
```
In drivers/video/fbdev/amba-clcd.c (c08de86c)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/video/fbdev/amba-clcd.c:clcdfb_of_init_display
```
```
In drivers/clk/clk-divider.c (c08efc3c)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:_div_round_closest
```
```
In drivers/usb/host/ehci-hcd.c (c0b29430)
Location: include/linux/log2.h:65
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (c0b4d4b4)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In arch/powerpc/platforms/powernv/pci-ioda.c (c0000000000d5c48)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - arch/powerpc/platforms/powernv/pci-ioda.c:pnv_pci_ioda2_setup_default_config
```
```
In mm/percpu.c (c0000000003a4708)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/memory.c (c0000000003bab60)
Location: include/linux/log2.h:65
Inline: True
```
```
In mm/page_alloc.c (c0000000003e3b28)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_batchsize
```
```
In lib/kfifo.c (c0000000007d902c)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/rhashtable.c (c0000000007dc59c)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b20408)
Location: include/linux/log2.h:65
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (c000000000b51150)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In mm/percpu.c (ffffffe0001fa826)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/memory.c (ffffffe000205d3a)
Location: include/linux/log2.h:65
Inline: True
```
```
In mm/page_alloc.c (ffffffe00021a974)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_batchsize
```
```
In lib/kfifo.c (ffffffe000461bde)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/rhashtable.c (ffffffe000463e5a)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In drivers/clk/clk-divider.c (ffffffe000511cdc)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe000670194)
Location: include/linux/log2.h:65
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffe000691232)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In mm/percpu.c (ffffffff81245c29)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/memory.c (ffffffff81254b5b)
Location: include/linux/log2.h:65
Inline: True
```
```
In mm/page_alloc.c (ffffffff81273b6f)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_batchsize
```
```
In lib/kfifo.c (ffffffff815217ec)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/rhashtable.c (ffffffff8152344f)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In drivers/clk/clk-divider.c (ffffffff816195ec)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/iommu/intel-svm.c (ffffffff816b702f)
Location: include/linux/log2.h:65
Inline: True
```
```
In drivers/nvme/host/core.c (ffffffff81743644)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:__nvme_revalidate_disk
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817d513a)
Location: include/linux/log2.h:65
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817f40d2)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In mm/percpu.c (ffffffff81238bd9)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/memory.c (ffffffff8124799b)
Location: include/linux/log2.h:65
Inline: True
```
```
In mm/page_alloc.c (ffffffff81265adf)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_batchsize
```
```
In lib/kfifo.c (ffffffff81511adc)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/rhashtable.c (ffffffff8151372f)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In drivers/clk/clk-divider.c (ffffffff8160db1c)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/iommu/intel-svm.c (ffffffff81694c6f)
Location: include/linux/log2.h:65
Inline: True
```
```
In drivers/nvme/host/core.c (ffffffff817252d4)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/nvme/host/core.c:__nvme_revalidate_disk
```
```
In drivers/usb/host/xhci-mem.c (ffffffff817b9272)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In mm/percpu.c (ffffffff812439c9)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/memory.c (ffffffff812528fb)
Location: include/linux/log2.h:65
Inline: True
```
```
In mm/page_alloc.c (ffffffff8127190f)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_batchsize
```
```
In lib/kfifo.c (ffffffff8151d87c)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/rhashtable.c (ffffffff8151f4df)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In drivers/clk/clk-divider.c (ffffffff816473cc)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/iommu/intel-svm.c (ffffffff816e54ff)
Location: include/linux/log2.h:65
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81811bda)
Location: include/linux/log2.h:65
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff81830ba2)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
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
In mm/percpu.c (ffffffff81253189)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_dump_alloc_info
```
```
In mm/memory.c (ffffffff812622cb)
Location: include/linux/log2.h:65
Inline: True
```
```
In mm/page_alloc.c (ffffffff8128136f)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - mm/page_alloc.c:zone_batchsize
```
```
In lib/kfifo.c (ffffffff815370ec)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/kfifo.c:__kfifo_init
```
```
In lib/rhashtable.c (ffffffff81538eff)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - lib/rhashtable.c:rhashtable_init
```
```
In drivers/clk/clk-divider.c (ffffffff8166195c)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/clk/clk-divider.c:clk_divider_bestdiv
```
```
In drivers/iommu/intel-svm.c (ffffffff817001af)
Location: include/linux/log2.h:65
Inline: True
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8182c6aa)
Location: include/linux/log2.h:65
Inline: True
```
```
In drivers/usb/host/xhci-mem.c (ffffffff8184ad72)
Location: include/linux/log2.h:65
Inline: True
Inline callers:
  - drivers/usb/host/xhci-mem.c:xhci_endpoint_init
```
</details>
</li>
</ul>

## Differences
