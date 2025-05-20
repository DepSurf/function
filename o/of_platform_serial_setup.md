# Function: <code>of_platform_serial_setup</code>

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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_of.c (ffff800010892f30)
Location: drivers/tty/serial/8250/8250_of.c:54
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
```
**Symbols:**

```
ffff800010892f30-ffff8000108933bc: of_platform_serial_setup.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int of_platform_serial_setup(struct platform_device *ofdev, int type, struct uart_port *port, struct of_serial_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/serial/8250/8250_of.c (c098e29c)
Location: drivers/tty/serial/8250/8250_of.c:54
Inline: False
Direct callers:
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
```
**Symbols:**

```
c098e29c-c098e704: of_platform_serial_setup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_of.c (c00000000093ae50)
Location: drivers/tty/serial/8250/8250_of.c:54
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
```
**Symbols:**

```
c00000000093ae50-c00000000093b364: of_platform_serial_setup.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/serial/8250/8250_of.c (ffffffe000559a5e)
Location: drivers/tty/serial/8250/8250_of.c:54
Inline: True
Direct callers:
  - drivers/tty/serial/8250/8250_of.c:of_platform_serial_probe
```
**Symbols:**

```
ffffffe000559a5e-ffffffe000559e00: of_platform_serial_setup.isra.0 (STB_LOCAL)
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
