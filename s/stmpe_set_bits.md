# Function: <code>stmpe_set_bits</code>

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
int stmpe_set_bits(struct stmpe *stmpe, u8 reg, u8 mask, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (ffff80001092ec80)
Location: drivers/mfd/stmpe.c:203
Inline: False
Direct callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_direction_input
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_direction_output
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_set
  - drivers/mfd/stmpe.c:stmpe811_adc_common_init
  - drivers/mfd/stmpe.c:stmpe811_adc_common_init
```
**Symbols:**

```
ffff80001092ec80-ffff80001092ecf0: stmpe_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int stmpe_set_bits(struct stmpe *stmpe, u8 reg, u8 mask, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (c0a10438)
Location: drivers/mfd/stmpe.c:203
Inline: False
Direct callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_direction_input
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_direction_output
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_set
  - drivers/mfd/stmpe.c:stmpe811_adc_common_init
  - drivers/mfd/stmpe.c:stmpe811_adc_common_init
```
**Symbols:**

```
c0a10438-c0a10490: stmpe_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int stmpe_set_bits(struct stmpe *stmpe, u8 reg, u8 mask, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (c0000000009ce6d0)
Location: drivers/mfd/stmpe.c:203
Inline: False
Direct callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_direction_input
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_direction_output
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_set
  - drivers/mfd/stmpe.c:stmpe811_adc_common_init
  - drivers/mfd/stmpe.c:stmpe811_adc_common_init
```
**Symbols:**

```
c0000000009ce6d0-c0000000009ce754: stmpe_set_bits (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int stmpe_set_bits(struct stmpe *stmpe, u8 reg, u8 mask, u8 val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mfd/stmpe.c (ffffffe0005a576a)
Location: drivers/mfd/stmpe.c:203
Inline: False
Direct callers:
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_direction_input
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_direction_output
  - drivers/gpio/gpio-stmpe.c:stmpe_gpio_set
  - drivers/mfd/stmpe.c:stmpe811_adc_common_init
  - drivers/mfd/stmpe.c:stmpe811_adc_common_init
```
**Symbols:**

```
ffffffe0005a576a-ffffffe0005a57cc: stmpe_set_bits (STB_GLOBAL)
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
