# Function: <code>amba_driver_register</code>

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
int amba_driver_register(struct amba_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/amba/bus.c (ffff8000107b8cd0)
Location: drivers/amba/bus.c:333
Inline: False
Direct callers:
  - drivers/gpio/gpio-pl061.c:pl061_gpio_init
  - drivers/video/fbdev/amba-clcd.c:amba_clcdfb_init
  - drivers/dma/amba-pl08x.c:pl08x_init
  - drivers/tty/serial/amba-pl011.c:pl011_init
  - drivers/mmc/host/mmci.c:mmci_driver_init
  - drivers/mailbox/pl320-ipc.c:ipc_init
```
**Symbols:**

```
ffff8000107b8cd0-ffff8000107b8d44: amba_driver_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int amba_driver_register(struct amba_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/amba/bus.c (c08e510c)
Location: drivers/amba/bus.c:333
Inline: False
Direct callers:
  - drivers/gpio/gpio-pl061.c:pl061_gpio_init
  - drivers/video/fbdev/amba-clcd.c:amba_clcdfb_init
  - drivers/dma/amba-pl08x.c:pl08x_init
  - drivers/tty/serial/amba-pl011.c:pl011_init
  - drivers/rtc/rtc-pl031.c:pl031_driver_init
  - drivers/mmc/host/mmci.c:mmci_driver_init
  - drivers/mailbox/pl320-ipc.c:ipc_init
```
**Symbols:**

```
c08e510c-c08e5170: amba_driver_register (STB_GLOBAL)
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
