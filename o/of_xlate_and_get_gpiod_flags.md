# Function: <code>of_xlate_and_get_gpiod_flags</code>

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
In drivers/gpio/gpiolib-of.c (ffff8000106c7fc0)
Location: drivers/gpio/gpiolib-of.c:95
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-of.c:of_parse_own_gpio
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_parse_own_gpio
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
```
**Symbols:**

```
ffff8000106c78d8-ffff8000106c7944: of_xlate_and_get_gpiod_flags.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-of.c (c0866048)
Location: drivers/gpio/gpiolib-of.c:95
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_gpiochip_add
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
```
**Symbols:**

```
c08650ec-c0865124: of_xlate_and_get_gpiod_flags.part.0 (STB_LOCAL)
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
In drivers/gpio/gpiolib-of.c (c0000000008453a4)
Location: drivers/gpio/gpiolib-of.c:95
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-of.c:of_parse_own_gpio
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_parse_own_gpio
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
```
**Symbols:**

```
c000000000844510-c000000000844574: of_xlate_and_get_gpiod_flags.part.0 (STB_LOCAL)
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
In drivers/gpio/gpiolib-of.c (ffffffe0004ab81a)
Location: drivers/gpio/gpiolib-of.c:95
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-of.c:of_parse_own_gpio
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
Direct callers:
  - drivers/gpio/gpiolib-of.c:of_parse_own_gpio
  - drivers/gpio/gpiolib-of.c:of_get_named_gpiod_flags
```
**Symbols:**

```
ffffffe0004ab22a-ffffffe0004ab276: of_xlate_and_get_gpiod_flags.part.0 (STB_LOCAL)
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
