# Function: <code>dwc2_change_bus_speed</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816c7e44)
Location: drivers/usb/dwc2/hcd.c:4894
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817342f4)
Location: drivers/usb/dwc2/hcd.c:4909
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81773844)
Location: drivers/usb/dwc2/hcd.c:4974
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81799394)
Location: drivers/usb/dwc2/hcd.c:4993
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817de848)
Location: drivers/usb/dwc2/hcd.c:4848
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8180f798)
Location: drivers/usb/dwc2/hcd.c:4848
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dwc2_change_bus_speed(struct usb_hcd *hcd, int speed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818e04b7)
Location: drivers/usb/dwc2/hcd.c:4848
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
**Symbols:**

```
ffffffff818e04b7-ffffffff818e04ee: dwc2_change_bus_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dwc2_change_bus_speed(struct usb_hcd *hcd, int speed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81c1f52e)
Location: drivers/usb/dwc2/hcd.c:4850
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
**Symbols:**

```
ffffffff81c1f52e-ffffffff81c1f565: dwc2_change_bus_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dwc2_change_bus_speed(struct usb_hcd *hcd, int speed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81c113b8)
Location: drivers/usb/dwc2/hcd.c:4967
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
**Symbols:**

```
ffffffff81c113b8-ffffffff81c113ef: dwc2_change_bus_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dwc2_change_bus_speed(struct usb_hcd *hcd, int speed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81d1a6d6)
Location: drivers/usb/dwc2/hcd.c:4968
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
**Symbols:**

```
ffffffff81d1a6d6-ffffffff81d1a70d: dwc2_change_bus_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dwc2_change_bus_speed(struct usb_hcd *hcd, int speed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81ee57fb)
Location: drivers/usb/dwc2/hcd.c:4964
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
**Symbols:**

```
ffffffff81ee57fb-ffffffff81ee584a: dwc2_change_bus_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81c426bb)
Location: drivers/usb/dwc2/hcd.c:4935
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81ca9c8b)
Location: drivers/usb/dwc2/hcd.c:4935
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81d5e93b)
Location: drivers/usb/dwc2/hcd.c:4935
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffff800010a3ffa8)
Location: drivers/usb/dwc2/hcd.c:4848
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c0b12b88)
Location: drivers/usb/dwc2/hcd.c:4848
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (c000000000b00974)
Location: drivers/usb/dwc2/hcd.c:4848
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffe00065bdcc)
Location: drivers/usb/dwc2/hcd.c:4848
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff817c7b78)
Location: drivers/usb/dwc2/hcd.c:4848
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81804618)
Location: drivers/usb/dwc2/hcd.c:4848
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8181e728)
Location: drivers/usb/dwc2/hcd.c:4848
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_reset_device
  - drivers/usb/dwc2/hcd.c:dwc2_free_dev
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
