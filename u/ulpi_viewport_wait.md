# Function: <code>ulpi_viewport_wait</code>

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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ulpi_viewport_wait(void *view, u32 mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/usb/phy/phy-ulpi-viewport.c (ffff800010a39fc8)
Location: drivers/usb/phy/phy-ulpi-viewport.c:21
Inline: False
Direct callers:
  - drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_write
  - drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_write
  - drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_read
  - drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_read
```
**Symbols:**

```
ffff800010a39fc8-ffff800010a3a044: ulpi_viewport_wait (STB_LOCAL)
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
In drivers/usb/phy/phy-ulpi-viewport.c (0)
Location: drivers/usb/phy/phy-ulpi-viewport.c:21
Inline: True
Inline callers:
  - drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_write
  - drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_write
  - drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_read
  - drivers/usb/phy/phy-ulpi-viewport.c:ulpi_viewport_read
```
</details>
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
<b>Arch</b>
<ul>
</ul>
