# Function: <code>usb_maxpacket</code>

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
In drivers/usb/core/hub.c (ffffffff8160b5e7)
Location: include/linux/usb.h:1851
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/devio.c (ffffffff8161af9a)
Location: include/linux/usb.h:1851
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81629308)
Location: include/linux/usb.h:1851
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81634fdf)
Location: include/linux/usb.h:1851
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81641e47)
Location: include/linux/usb.h:1851
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/core/hub.c (ffffffff8166b0ff)
Location: include/linux/usb.h:1848
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/devio.c (ffffffff8167abac)
Location: include/linux/usb.h:1848
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816890ed)
Location: include/linux/usb.h:1848
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8169693b)
Location: include/linux/usb.h:1848
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_append_tds
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816a2966)
Location: include/linux/usb.h:1848
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/core/hub.c (ffffffff81698e2f)
Location: include/linux/usb.h:1848
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/devio.c (ffffffff816a886c)
Location: include/linux/usb.h:1848
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816b72e5)
Location: include/linux/usb.h:1848
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816c271f)
Location: include/linux/usb.h:1848
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816cf693)
Location: include/linux/usb.h:1848
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/core/hub.c (ffffffff816ae14c)
Location: include/linux/usb.h:1919
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/devio.c (ffffffff816bdc29)
Location: include/linux/usb.h:1919
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/dwc2/hcd.c (ffffffff816cb610)
Location: include/linux/usb.h:1919
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816d8122)
Location: include/linux/usb.h:1919
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff816e3b2f)
Location: include/linux/usb.h:1919
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/core/hub.c (ffffffff8171975e)
Location: include/linux/usb.h:1936
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/devio.c (ffffffff817295f9)
Location: include/linux/usb.h:1936
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81737b80)
Location: include/linux/usb.h:1936
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81744852)
Location: include/linux/usb.h:1936
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8175034f)
Location: include/linux/usb.h:1936
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/core/hub.c (ffffffff81758546)
Location: include/linux/usb.h:1955
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff81768289)
Location: include/linux/usb.h:1955
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/dwc2/hcd.c (ffffffff81777b50)
Location: include/linux/usb.h:1955
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817849f2)
Location: include/linux/usb.h:1955
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81790242)
Location: include/linux/usb.h:1955
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/core/hub.c (ffffffff8177cab6)
Location: include/linux/usb.h:1955
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff8178cad9)
Location: include/linux/usb.h:1955
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/dwc2/hcd.c (ffffffff8179d9a2)
Location: include/linux/usb.h:1955
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:_dwc2_hcd_urb_enqueue
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817ad052)
Location: include/linux/usb.h:1955
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817b6a10)
Location: include/linux/usb.h:1955
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/core/hub.c (ffffffff817bb531)
Location: include/linux/usb.h:1955
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff817cbff6)
Location: include/linux/usb.h:1955
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817ec1ec)
Location: include/linux/usb.h:1955
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817f9490)
Location: include/linux/usb.h:1955
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/core/hub.c (ffffffff817ebd45)
Location: include/linux/usb.h:1960
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff817fcc56)
Location: include/linux/usb.h:1960
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8181d0bc)
Location: include/linux/usb.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8182a2f0)
Location: include/linux/usb.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/core/hub.c (ffffffff818bb35e)
Location: include/linux/usb.h:1967
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/devio.c (ffffffff818cbe2c)
Location: include/linux/usb.h:1967
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818ee631)
Location: include/linux/usb.h:1967
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818f8125)
Location: include/linux/usb.h:1967
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/core/hub.c (ffffffff81c1be87)
Location: include/linux/usb.h:1982
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/devio.c (ffffffff818d70d4)
Location: include/linux/usb.h:1982
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_bulk
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f7551)
Location: include/linux/usb.h:1982
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81900c6c)
Location: include/linux/usb.h:1982
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/core/hub.c (ffffffff81c0dd61)
Location: include/linux/usb.h:1991
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/devio.c (ffffffff818ba194)
Location: include/linux/usb.h:1991
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_bulk
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818dac10)
Location: include/linux/usb.h:1991
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818e41d9)
Location: include/linux/usb.h:1991
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/core/hub.c (ffffffff81d14e21)
Location: include/linux/usb.h:1984
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81976230)
Location: include/linux/usb.h:1984
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81980479)
Location: include/linux/usb.h:1984
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/core/hub.c (ffffffff81edf99f)
Location: include/linux/usb.h:1972
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad1ef1)
Location: include/linux/usb.h:1972
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81adc2dc)
Location: include/linux/usb.h:1972
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/core/hub.c (ffffffff81c1c14f)
Location: include/linux/usb.h:2002
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81c675dd)
Location: include/linux/usb.h:2002
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/core/hub.c (ffffffff81c830af)
Location: include/linux/usb.h:2041
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81cce96d)
Location: include/linux/usb.h:2041
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/core/hub.c (ffffffff81d37a32)
Location: include/linux/usb.h:2008
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81d8386d)
Location: include/linux/usb.h:2008
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/core/hub.c (ffff800010a1afd4)
Location: include/linux/usb.h:1960
Inline: True
```
```
In drivers/usb/core/devio.c (ffff800010a2dda4)
Location: include/linux/usb.h:1960
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a54980)
Location: include/linux/usb.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffff800010a63750)
Location: include/linux/usb.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/core/hub.c (c0af2e84)
Location: include/linux/usb.h:1960
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/devio.c (c0b03c28)
Location: include/linux/usb.h:1960
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/host/ehci-hcd.c (c0b29734)
Location: include/linux/usb.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (c0b3791c)
Location: include/linux/usb.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/core/hub.c (c000000000ad445c)
Location: include/linux/usb.h:1960
Inline: True
```
```
In drivers/usb/core/devio.c (c000000000aec9c0)
Location: include/linux/usb.h:1960
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b1e324)
Location: include/linux/usb.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (c000000000b36910)
Location: include/linux/usb.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/core/hub.c (ffffffe00063f5a2)
Location: include/linux/usb.h:1960
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffe00064e68a)
Location: include/linux/usb.h:1960
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe00066f71c)
Location: include/linux/usb.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffe00067c5e0)
Location: include/linux/usb.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/core/hub.c (ffffffff817a4125)
Location: include/linux/usb.h:1960
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff817b5036)
Location: include/linux/usb.h:1960
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817d549c)
Location: include/linux/usb.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff817e26d0)
Location: include/linux/usb.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/core/hub.c (ffffffff81795c96)
Location: include/linux/usb.h:1960
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff817a6a66)
Location: include/linux/usb.h:1960
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
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
In drivers/usb/core/hub.c (ffffffff817e0bc5)
Location: include/linux/usb.h:1960
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff817f1ad6)
Location: include/linux/usb.h:1960
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81811f3c)
Location: include/linux/usb.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8181f170)
Location: include/linux/usb.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
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
In drivers/usb/core/hub.c (ffffffff817faeb5)
Location: include/linux/usb.h:1960
Inline: True
```
```
In drivers/usb/core/devio.c (ffffffff8180bd16)
Location: include/linux/usb.h:1960
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:proc_bulk
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8182ca0c)
Location: include/linux/usb.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818390e0)
Location: include/linux/usb.h:1960
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
```
</details>
</li>
</ul>

## Differences
