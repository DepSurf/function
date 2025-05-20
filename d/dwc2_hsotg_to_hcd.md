# Function: <code>dwc2_hsotg_to_hcd</code>

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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.h:360
Inline: True
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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.h:436
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd.h:436
Inline: True
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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.h:436
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd.h:436
Inline: True
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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.h:436
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd.h:436
Inline: True
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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.h:437
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd.h:437
Inline: True
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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.h:458
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd.h:458
Inline: True
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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.h:458
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd.h:458
Inline: True
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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.h:461
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd.h:461
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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.h:461
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd.h:461
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
In drivers/usb/dwc2/hcd.c (ffffffff818e0405)
Location: drivers/usb/dwc2/hcd.h:461
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start_func
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd.h:461
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
In drivers/usb/dwc2/hcd.c (ffffffff818ea265)
Location: drivers/usb/dwc2/hcd.h:461
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start_func
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd.h:461
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
In drivers/usb/dwc2/hcd.c (ffffffff818cbd75)
Location: drivers/usb/dwc2/hcd.h:461
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start_func
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd.h:461
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
In drivers/usb/dwc2/hcd.c (ffffffff81965555)
Location: drivers/usb/dwc2/hcd.h:461
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start_func
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd.h:461
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
In drivers/usb/dwc2/hcd.c (ffffffff81abf925)
Location: drivers/usb/dwc2/hcd.h:461
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start_func
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd.h:461
Inline: True
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
In drivers/usb/dwc2/hcd.c (ffffffff81c492a5)
Location: drivers/usb/dwc2/hcd.h:432
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start_func
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd.h:432
Inline: True
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
In drivers/usb/dwc2/hcd.c (ffffffff81cb0885)
Location: drivers/usb/dwc2/hcd.h:432
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start_func
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd.h:432
Inline: True
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
In drivers/usb/dwc2/hcd.c (ffffffff81d65595)
Location: drivers/usb/dwc2/hcd.h:432
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start_func
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_port_suspend
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd.h:432
Inline: True
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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.h:461
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd.h:461
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
In drivers/usb/dwc2/hcd.c (c0b1acdc)
Location: drivers/usb/dwc2/hcd.h:461
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start_func
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
```
In drivers/usb/dwc2/hcd_intr.c (c0b1ad2c)
Location: drivers/usb/dwc2/hcd.h:461
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd_intr.c:dwc2_hc_handle_tt_clear
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
In drivers/usb/dwc2/hcd.c (c000000000b0db20)
Location: drivers/usb/dwc2/hcd.h:461
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start_func
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
```
In drivers/usb/dwc2/hcd_intr.c (c000000000b0dc84)
Location: drivers/usb/dwc2/hcd.h:461
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
In drivers/usb/dwc2/hcd.c (ffffffe0006655e8)
Location: drivers/usb/dwc2/hcd.h:461
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_host_can_poweroff_phy
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_remove
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_start_func
  - drivers/usb/dwc2/hcd.c:dwc2_host_complete
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
```
In drivers/usb/dwc2/hcd_intr.c (ffffffe000665702)
Location: drivers/usb/dwc2/hcd.h:461
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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.h:461
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd.h:461
Inline: True
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.h:461
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd.h:461
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
In drivers/usb/dwc2/hcd.c (0)
Location: drivers/usb/dwc2/hcd.h:461
Inline: True
```
```
In drivers/usb/dwc2/hcd_intr.c (0)
Location: drivers/usb/dwc2/hcd.h:461
Inline: True
```
</details>
</li>
</ul>

## Differences
