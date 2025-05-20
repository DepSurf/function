# Function: <code>hc32_to_cpup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci.h:844
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci.h:641
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci.h:855
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci.h:641
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci.h:863
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci.h:641
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci.h:863
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci.h:642
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci.h:850
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci.h:643
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci.h:850
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci.h:640
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci.h:850
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci.h:640
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci.h:850
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci.h:642
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci.h:850
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci.h:642
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f1e86)
Location: drivers/usb/host/ehci.h:850
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818fa762)
Location: drivers/usb/host/ohci.h:642
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818fada6)
Location: drivers/usb/host/ehci.h:850
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff8190329a)
Location: drivers/usb/host/ohci.h:642
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818ddb66)
Location: drivers/usb/host/ehci.h:851
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff818e686a)
Location: drivers/usb/host/ohci.h:642
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81979686)
Location: drivers/usb/host/ehci.h:852
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81982c2a)
Location: drivers/usb/host/ohci.h:642
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81ad6d76)
Location: drivers/usb/host/ehci.h:853
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81adaf40)
Location: drivers/usb/host/ohci.h:642
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81c61af6)
Location: drivers/usb/host/ehci.h:853
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81c66180)
Location: drivers/usb/host/ohci.h:642
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81cc8e94)
Location: drivers/usb/host/ehci.h:853
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81ccd3ff)
Location: drivers/usb/host/ohci.h:642
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81d7dd74)
Location: drivers/usb/host/ehci.h:863
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:sitd_complete
  - drivers/usb/host/ehci-hcd.c:itd_complete
  - drivers/usb/host/ehci-hcd.c:qh_unlink_periodic
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
```
```
In drivers/usb/host/ohci-hcd.c (ffffffff81d822ff)
Location: drivers/usb/host/ohci.h:642
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:finish_unlinks
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci.h:850
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci.h:642
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (c0b2a558)
Location: drivers/usb/host/ehci.h:850
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:scan_isoc
  - drivers/usb/host/ehci-hcd.c:qh_link_periodic
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
  - drivers/usb/host/ehci-hcd.c:qh_lines
```
```
In drivers/usb/host/ohci-hcd.c (c0b32c3c)
Location: drivers/usb/host/ohci.h:642
Inline: True
Inline callers:
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:update_done_list
  - drivers/usb/host/ohci-hcd.c:td_done
  - drivers/usb/host/ohci-hcd.c:td_done
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci.h:850
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci.h:642
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci.h:850
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci.h:642
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci.h:850
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci.h:642
Inline: True
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci.h:850
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci.h:642
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (0)
Location: drivers/usb/host/ehci.h:850
Inline: True
```
```
In drivers/usb/host/ohci-hcd.c (0)
Location: drivers/usb/host/ohci.h:642
Inline: True
```
</details>
</li>
</ul>

## Differences
