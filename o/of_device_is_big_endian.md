# Function: <code>of_device_is_big_endian</code>

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
bool of_device_is_big_endian(const struct device_node *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffff800010b69030)
Location: drivers/of/base.c:668
Inline: False
Direct callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/tty/serial/8250/8250_dw.c:dw8250_probe
```
**Symbols:**

```
ffff800010b69030-ffff800010b69070: of_device_is_big_endian (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool of_device_is_big_endian(const struct device_node *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c0c4c7f4)
Location: drivers/of/base.c:668
Inline: False
Direct callers:
  - drivers/bus/brcmstb_gisb.c:brcmstb_gisb_arb_probe
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_setup
```
**Symbols:**

```
c0c4c7f4-c0c4c824: of_device_is_big_endian (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool of_device_is_big_endian(const struct device_node *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (c000000000c41450)
Location: drivers/of/base.c:668
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
**Symbols:**

```
c000000000c41450-c000000000c41494: of_device_is_big_endian (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool of_device_is_big_endian(const struct device_node *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/of/base.c (ffffffe00071eb50)
Location: drivers/of/base.c:668
Inline: False
Direct callers:
  - drivers/gpio/gpio-mmio.c:bgpio_pdev_probe
```
**Symbols:**

```
ffffffe00071eb50-ffffffe00071eb88: of_device_is_big_endian (STB_GLOBAL)
```
</details>
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
