# Function: <code>output_buf_tds_dir</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff81695424)
Location: drivers/usb/host/ehci-dbg.c:603
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
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
In drivers/usb/host/ehci-hcd.c (ffffffff816c39b4)
Location: drivers/usb/host/ehci-dbg.c:603
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
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
In drivers/usb/host/ehci-hcd.c (ffffffff816d7c6a)
Location: drivers/usb/host/ehci-dbg.c:603
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
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
In drivers/usb/host/ehci-hcd.c (ffffffff8174439a)
Location: drivers/usb/host/ehci-dbg.c:593
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
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
In drivers/usb/host/ehci-hcd.c (ffffffff81785c4c)
Location: drivers/usb/host/ehci-dbg.c:593
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
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
In drivers/usb/host/ehci-hcd.c (ffffffff817af04c)
Location: drivers/usb/host/ehci-dbg.c:593
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
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
In drivers/usb/host/ehci-hcd.c (ffffffff817f2868)
Location: drivers/usb/host/ehci-dbg.c:593
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
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
In drivers/usb/host/ehci-hcd.c (ffffffff81823758)
Location: drivers/usb/host/ehci-dbg.c:593
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818eab40)
Location: drivers/usb/host/ehci-dbg.c:593
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
```
**Symbols:**

```
ffffffff818eab40-ffffffff818eac44: output_buf_tds_dir.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/usb/host/ehci-hcd.c (ffffffff818f3a30)
Location: drivers/usb/host/ehci-dbg.c:593
Inline: True
Direct callers:
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
```
**Symbols:**

```
ffffffff818f3a30-ffffffff818f3b34: output_buf_tds_dir.constprop.0 (STB_LOCAL)
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
In drivers/usb/host/ehci-hcd.c (ffffffff818d9cae)
Location: drivers/usb/host/ehci-dbg.c:593
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
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
In drivers/usb/host/ehci-hcd.c (ffffffff8197526d)
Location: drivers/usb/host/ehci-dbg.c:593
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
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
In drivers/usb/host/ehci-hcd.c (ffffffff81ad0ccb)
Location: drivers/usb/host/ehci-dbg.c:593
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
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
In drivers/usb/host/ehci-hcd.c (ffffffff81c5aa4b)
Location: drivers/usb/host/ehci-dbg.c:593
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
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
In drivers/usb/host/ehci-hcd.c (ffffffff81cc20da)
Location: drivers/usb/host/ehci-dbg.c:593
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
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
In drivers/usb/host/ehci-hcd.c (ffffffff81d76da9)
Location: drivers/usb/host/ehci-dbg.c:593
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
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
In drivers/usb/host/ehci-hcd.c (ffff800010a5d070)
Location: drivers/usb/host/ehci-dbg.c:593
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
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
In drivers/usb/host/ehci-hcd.c (c0b2f530)
Location: drivers/usb/host/ehci-dbg.c:593
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
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
In drivers/usb/host/ehci-hcd.c (c000000000b29b28)
Location: drivers/usb/host/ehci-dbg.c:593
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
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
In drivers/usb/host/ehci-hcd.c (ffffffe000672294)
Location: drivers/usb/host/ehci-dbg.c:593
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
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
In drivers/usb/host/ehci-hcd.c (ffffffff817dbb38)
Location: drivers/usb/host/ehci-dbg.c:593
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
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
In drivers/usb/host/ehci-hcd.c (ffffffff818185d8)
Location: drivers/usb/host/ehci-dbg.c:593
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
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
In drivers/usb/host/ehci-hcd.c (ffffffff818325c8)
Location: drivers/usb/host/ehci-dbg.c:593
Inline: True
Inline callers:
  - drivers/usb/host/ehci-hcd.c:fill_periodic_buffer
```
</details>
</li>
</ul>

## Differences
