# Function: <code>serdev_acpi_get_uart_resource</code>

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
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool serdev_acpi_get_uart_resource(struct acpi_resource *ares, struct acpi_resource_uart_serialbus **uart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff817f17d5)
Location: drivers/tty/serdev/core.c:575
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_parse_resource
```
**Symbols:**

```
ffffffff817f12e0-ffffffff817f1306: serdev_acpi_get_uart_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool serdev_acpi_get_uart_resource(struct acpi_resource *ares, struct acpi_resource_uart_serialbus **uart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81931e95)
Location: drivers/tty/serdev/core.c:575
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_parse_resource
```
**Symbols:**

```
ffffffff819318d0-ffffffff81931906: serdev_acpi_get_uart_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool serdev_acpi_get_uart_resource(struct acpi_resource *ares, struct acpi_resource_uart_serialbus **uart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81a908d5)
Location: drivers/tty/serdev/core.c:575
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_parse_resource
```
**Symbols:**

```
ffffffff81a901c0-ffffffff81a901f6: serdev_acpi_get_uart_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool serdev_acpi_get_uart_resource(struct acpi_resource *ares, struct acpi_resource_uart_serialbus **uart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81adc0e5)
Location: drivers/tty/serdev/core.c:586
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_parse_resource
```
**Symbols:**

```
ffffffff81adb9d0-ffffffff81adba06: serdev_acpi_get_uart_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool serdev_acpi_get_uart_resource(struct acpi_resource *ares, struct acpi_resource_uart_serialbus **uart);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/serdev/core.c (ffffffff81b2f3c5)
Location: drivers/tty/serdev/core.c:579
Inline: True
Inline callers:
  - drivers/tty/serdev/core.c:acpi_serdev_parse_resource
```
**Symbols:**

```
ffffffff81b2ed30-ffffffff81b2ed66: serdev_acpi_get_uart_resource (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
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
<b>Regular</b>
<ul>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
