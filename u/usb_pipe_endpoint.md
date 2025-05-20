# Function: <code>usb_pipe_endpoint</code>

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
In drivers/usb/core/urb.c (ffffffff81610171)
Location: include/linux/usb.h:1841
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff81611286)
Location: include/linux/usb.h:1841
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
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
In drivers/usb/core/urb.c (ffffffff8166fd41)
Location: include/linux/usb.h:1838
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff81670e86)
Location: include/linux/usb.h:1838
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
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
In drivers/usb/core/urb.c (ffffffff8169da11)
Location: include/linux/usb.h:1838
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff8169eb36)
Location: include/linux/usb.h:1838
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816c481b)
Location: include/linux/usb.h:1838
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
In drivers/usb/core/urb.c (ffffffff816b2e5b)
Location: include/linux/usb.h:1909
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff816b3d36)
Location: include/linux/usb.h:1909
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff816d8e1b)
Location: include/linux/usb.h:1909
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
In drivers/usb/core/urb.c (ffffffff8171e0bd)
Location: include/linux/usb.h:1926
Inline: True
```
```
In drivers/usb/core/message.c (ffffffff8171f566)
Location: include/linux/usb.h:1926
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8174554b)
Location: include/linux/usb.h:1926
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
In drivers/usb/core/urb.c (ffffffff8175d019)
Location: include/linux/usb.h:1945
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff8175e315)
Location: include/linux/usb.h:1945
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8178607a)
Location: include/linux/usb.h:1945
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
In drivers/usb/core/urb.c (ffffffff81781649)
Location: include/linux/usb.h:1945
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff817828e5)
Location: include/linux/usb.h:1945
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817aca9a)
Location: include/linux/usb.h:1945
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
In drivers/usb/core/urb.c (ffffffff817bfb69)
Location: include/linux/usb.h:1945
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff817c0d85)
Location: include/linux/usb.h:1945
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817ebab6)
Location: include/linux/usb.h:1945
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
In drivers/usb/core/urb.c (ffffffff817f04e9)
Location: include/linux/usb.h:1950
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff817f1705)
Location: include/linux/usb.h:1950
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8181c986)
Location: include/linux/usb.h:1950
Inline: True
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
In drivers/usb/core/urb.c (ffffffff818bfa4a)
Location: include/linux/usb.h:1957
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_urb_ep_type_check
```
```
In drivers/usb/core/message.c (ffffffff818c1045)
Location: include/linux/usb.h:1957
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818ec506)
Location: include/linux/usb.h:1957
Inline: True
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
In drivers/usb/core/urb.c (ffffffff818cc60a)
Location: include/linux/usb.h:1972
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_urb_ep_type_check
```
```
In drivers/usb/core/message.c (ffffffff818cd145)
Location: include/linux/usb.h:1972
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818f53d6)
Location: include/linux/usb.h:1972
Inline: True
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
In drivers/usb/core/urb.c (ffffffff818afc2a)
Location: include/linux/usb.h:1981
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_urb_ep_type_check
```
```
In drivers/usb/core/message.c (ffffffff818b0765)
Location: include/linux/usb.h:1981
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff818d8a2a)
Location: include/linux/usb.h:1981
Inline: True
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
In drivers/usb/core/urb.c (ffffffff81944d79)
Location: include/linux/usb.h:1974
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_urb_ep_type_check
```
```
In drivers/usb/core/message.c (ffffffff819459c5)
Location: include/linux/usb.h:1974
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/core/devio.c (ffffffff8194ffbb)
Location: include/linux/usb.h:1974
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_bulk
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81973ca1)
Location: include/linux/usb.h:1974
Inline: True
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
Location: include/linux/usb.h:1965
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/urb.c (ffffffff81a9d3da)
Location: include/linux/usb.h:1965
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_urb_ep_type_check
```
```
In drivers/usb/core/message.c (ffffffff81a9e0ff)
Location: include/linux/usb.h:1965
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/core/devio.c (ffffffff81aab577)
Location: include/linux/usb.h:1965
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_bulk
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad1ef1)
Location: include/linux/usb.h:1965
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:qh_urb_transaction
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81adc2dc)
Location: include/linux/usb.h:1965
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
Location: include/linux/usb.h:1995
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/urb.c (ffffffff81c224aa)
Location: include/linux/usb.h:1995
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_urb_ep_type_check
```
```
In drivers/usb/core/message.c (ffffffff81c2320f)
Location: include/linux/usb.h:1995
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/core/devio.c (ffffffff81c32a57)
Location: include/linux/usb.h:1995
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_bulk
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81c5b284)
Location: include/linux/usb.h:1995
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81c675dd)
Location: include/linux/usb.h:1995
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
Location: include/linux/usb.h:2034
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/urb.c (ffffffff81c89419)
Location: include/linux/usb.h:2034
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_urb_ep_type_check
```
```
In drivers/usb/core/message.c (ffffffff81c8a18f)
Location: include/linux/usb.h:2034
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/core/devio.c (ffffffff81c99d22)
Location: include/linux/usb.h:2034
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_bulk
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc2904)
Location: include/linux/usb.h:2034
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81cce96d)
Location: include/linux/usb.h:2034
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
Location: include/linux/usb.h:2001
Inline: True
Inline callers:
  - drivers/usb/core/hub.c:hub_configure
```
```
In drivers/usb/core/urb.c (ffffffff81d3de6a)
Location: include/linux/usb.h:2001
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_urb_ep_type_check
```
```
In drivers/usb/core/message.c (ffffffff81d3ebaf)
Location: include/linux/usb.h:2001
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/core/devio.c (ffffffff81d4e8f2)
Location: include/linux/usb.h:2001
Inline: True
Inline callers:
  - drivers/usb/core/devio.c:do_proc_bulk
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81d77604)
Location: include/linux/usb.h:2001
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81d8386d)
Location: include/linux/usb.h:2001
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
In drivers/usb/core/urb.c (ffff800010a200b4)
Location: include/linux/usb.h:1950
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffff800010a21c10)
Location: include/linux/usb.h:1950
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/host/ehci-hcd.c (ffff800010a54304)
Location: include/linux/usb.h:1950
Inline: True
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
In drivers/usb/core/urb.c (c0af72a0)
Location: include/linux/usb.h:1950
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (c0af858c)
Location: include/linux/usb.h:1950
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/host/ehci-hcd.c (c0b290e4)
Location: include/linux/usb.h:1950
Inline: True
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
In drivers/usb/core/urb.c (c000000000ada368)
Location: include/linux/usb.h:1950
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (c000000000adbf50)
Location: include/linux/usb.h:1950
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/host/ehci-hcd.c (c000000000b1ff8c)
Location: include/linux/usb.h:1950
Inline: True
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
In drivers/usb/core/urb.c (ffffffe00064342e)
Location: include/linux/usb.h:1950
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffe000644696)
Location: include/linux/usb.h:1950
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/host/ehci-hcd.c (ffffffe00066fe8a)
Location: include/linux/usb.h:1950
Inline: True
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
In drivers/usb/core/urb.c (ffffffff817a88c9)
Location: include/linux/usb.h:1950
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff817a9ae5)
Location: include/linux/usb.h:1950
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff817d4d66)
Location: include/linux/usb.h:1950
Inline: True
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
In drivers/usb/core/urb.c (ffffffff8179a2d9)
Location: include/linux/usb.h:1950
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff8179b4e5)
Location: include/linux/usb.h:1950
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
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
In drivers/usb/core/urb.c (ffffffff817e5369)
Location: include/linux/usb.h:1950
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff817e6585)
Location: include/linux/usb.h:1950
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff81811806)
Location: include/linux/usb.h:1950
Inline: True
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
In drivers/usb/core/urb.c (ffffffff817ff5c9)
Location: include/linux/usb.h:1950
Inline: True
Inline callers:
  - drivers/usb/core/urb.c:usb_submit_urb
  - drivers/usb/core/urb.c:usb_submit_urb
```
```
In drivers/usb/core/message.c (ffffffff818007e5)
Location: include/linux/usb.h:1950
Inline: True
Inline callers:
  - drivers/usb/core/message.c:usb_bulk_msg
```
```
In drivers/usb/host/ehci-hcd.c (ffffffff8182c2d6)
Location: include/linux/usb.h:1950
Inline: True
```
</details>
</li>
</ul>

## Differences
