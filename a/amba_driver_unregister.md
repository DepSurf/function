# Function: <code>amba_driver_unregister</code>

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
void amba_driver_unregister(struct amba_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/amba/bus.c (ffff8000107b8d48)
Location: drivers/amba/bus.c:353
Inline: False
Direct callers:
  - drivers/video/fbdev/amba-clcd.c:amba_clcdfb_exit
  - drivers/tty/serial/amba-pl011.c:pl011_exit
  - drivers/mmc/host/mmci.c:mmci_driver_exit
```
**Symbols:**

```
ffff8000107b8d48-ffff8000107b8d74: amba_driver_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void amba_driver_unregister(struct amba_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/amba/bus.c (c08e51a8)
Location: drivers/amba/bus.c:353
Inline: False
Direct callers:
  - drivers/video/fbdev/amba-clcd.c:amba_clcdfb_exit
  - drivers/tty/serial/amba-pl011.c:pl011_exit
  - drivers/rtc/rtc-pl031.c:pl031_driver_exit
  - drivers/mmc/host/mmci.c:mmci_driver_exit
```
**Symbols:**

```
c08e51a8-c08e51c4: amba_driver_unregister (STB_GLOBAL)
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
