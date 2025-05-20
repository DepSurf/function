# Function: <code>dwc2_hcd_cleanup_channels</code>

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
In drivers/usb/dwc2/hcd.c (ffffffff81629d4e)
Location: drivers/usb/dwc2/hcd.c:218
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
In drivers/usb/dwc2/hcd.c (ffffffff81689bdb)
Location: drivers/usb/dwc2/hcd.c:1800
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
In drivers/usb/dwc2/hcd.c (ffffffff816b7d4e)
Location: drivers/usb/dwc2/hcd.c:1830
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff816cc038)
Location: drivers/usb/dwc2/hcd.c:1847
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
In drivers/usb/dwc2/hcd.c (ffffffff817385a8)
Location: drivers/usb/dwc2/hcd.c:1853
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
In drivers/usb/dwc2/hcd.c (ffffffff8177859f)
Location: drivers/usb/dwc2/hcd.c:1898
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
In drivers/usb/dwc2/hcd.c (ffffffff8179e4b6)
Location: drivers/usb/dwc2/hcd.c:1888
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
In drivers/usb/dwc2/hcd.c (ffffffff817dd0cb)
Location: drivers/usb/dwc2/hcd.c:1698
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
In drivers/usb/dwc2/hcd.c (ffffffff8180dffb)
Location: drivers/usb/dwc2/hcd.c:1698
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dwc2_hcd_cleanup_channels(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818dc7b0)
Location: drivers/usb/dwc2/hcd.c:1698
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
**Symbols:**

```
ffffffff818dc7b0-ffffffff818dc985: dwc2_hcd_cleanup_channels (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dwc2_hcd_cleanup_channels(struct dwc2_hsotg *hsotg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818e6640)
Location: drivers/usb/dwc2/hcd.c:1699
Inline: False
Direct callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
**Symbols:**

```
ffffffff818e6640-ffffffff818e6815: dwc2_hcd_cleanup_channels (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff818ca5ba)
Location: drivers/usb/dwc2/hcd.c:1697
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff8196367b)
Location: drivers/usb/dwc2/hcd.c:1697
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/dwc2/hcd.c (ffffffff81abdbab)
Location: drivers/usb/dwc2/hcd.c:1693
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
In drivers/usb/dwc2/hcd.c (ffffffff81c472eb)
Location: drivers/usb/dwc2/hcd.c:1664
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
In drivers/usb/dwc2/hcd.c (ffffffff81cae8cb)
Location: drivers/usb/dwc2/hcd.c:1664
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
In drivers/usb/dwc2/hcd.c (ffffffff81d6357b)
Location: drivers/usb/dwc2/hcd.c:1664
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
In drivers/usb/dwc2/hcd.c (ffff800010a46aa0)
Location: drivers/usb/dwc2/hcd.c:1698
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
In drivers/usb/dwc2/hcd.c (c0b191d0)
Location: drivers/usb/dwc2/hcd.c:1698
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
In drivers/usb/dwc2/hcd.c (c000000000b0af9c)
Location: drivers/usb/dwc2/hcd.c:1698
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
In drivers/usb/dwc2/hcd.c (ffffffe0006634bc)
Location: drivers/usb/dwc2/hcd.c:1698
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
In drivers/usb/dwc2/hcd.c (ffffffff817c63db)
Location: drivers/usb/dwc2/hcd.c:1698
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
In drivers/usb/dwc2/hcd.c (ffffffff81802e7b)
Location: drivers/usb/dwc2/hcd.c:1698
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
In drivers/usb/dwc2/hcd.c (ffffffff8181cf8b)
Location: drivers/usb/dwc2/hcd.c:1698
Inline: True
Inline callers:
  - drivers/usb/dwc2/hcd.c:dwc2_hcd_disconnect
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
</ul>
