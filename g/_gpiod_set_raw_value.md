# Function: <code>_gpiod_set_raw_value</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void _gpiod_set_raw_value(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81426370)
Location: drivers/gpio/gpiolib.c:1396
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_value_cansleep
  - drivers/gpio/gpiolib.c:gpiod_set_raw_value
  - drivers/gpio/gpiolib.c:gpiod_set_value
```
**Symbols:**

```
ffffffff81426370-ffffffff81426467: _gpiod_set_raw_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void _gpiod_set_raw_value(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8146fae0)
Location: drivers/gpio/gpiolib.c:2354
Inline: False
```
**Symbols:**

```
ffffffff8146fae0-ffffffff8146fbd6: _gpiod_set_raw_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void _gpiod_set_raw_value(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81491e50)
Location: drivers/gpio/gpiolib.c:2544
Inline: False
```
**Symbols:**

```
ffffffff81491e50-ffffffff81491f46: _gpiod_set_raw_value (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void _gpiod_set_raw_value(struct gpio_desc *desc, bool value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149b950)
Location: drivers/gpio/gpiolib.c:2548
Inline: False
```
**Symbols:**

```
ffffffff8149b950-ffffffff8149ba42: _gpiod_set_raw_value (STB_LOCAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
