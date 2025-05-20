# Function: <code>gpiod_set_config</code>

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
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int gpiod_set_config(struct gpio_desc *desc, long unsigned int config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:3556
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
```
**Symbols:**

```
ffffffff81614acd-ffffffff81614b3d: gpiod_set_config.cold (STB_LOCAL)
ffffffff81610a60-ffffffff81610acd: gpiod_set_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int gpiod_set_config(struct gpio_desc *desc, long unsigned int config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2399
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
```
**Symbols:**

```
ffffffff81bf6336-ffffffff81bf63a6: gpiod_set_config.cold (STB_LOCAL)
ffffffff81636e50-ffffffff81636ec9: gpiod_set_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int gpiod_set_config(struct gpio_desc *desc, long unsigned int config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2376
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
```
**Symbols:**

```
ffffffff81be81dc-ffffffff81be824c: gpiod_set_config.cold (STB_LOCAL)
ffffffff8161a770-ffffffff8161a7e1: gpiod_set_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gpiod_set_config(struct gpio_desc *desc, long unsigned int config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2405
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
```
**Symbols:**

```
ffffffff81ce1da9-ffffffff81ce1e19: gpiod_set_config.cold (STB_LOCAL)
ffffffff81689b90-ffffffff81689c01: gpiod_set_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gpiod_set_config(struct gpio_desc *desc, long unsigned int config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2523
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
```
**Symbols:**

```
ffffffff81ea8687-ffffffff81ea86f7: gpiod_set_config.cold (STB_LOCAL)
ffffffff817a6bd0-ffffffff817a6c4c: gpiod_set_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gpiod_set_config(struct gpio_desc *desc, long unsigned int config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818beeb0)
Location: drivers/gpio/gpiolib.c:2593
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
```
**Symbols:**

```
ffffffff818beeb0-ffffffff818bef99: gpiod_set_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gpiod_set_config(struct gpio_desc *desc, long unsigned int config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81901f30)
Location: drivers/gpio/gpiolib.c:2634
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
```
**Symbols:**

```
ffffffff81901f30-ffffffff81901ffc: gpiod_set_config (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gpiod_set_config(struct gpio_desc *desc, long unsigned int config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81949b50)
Location: drivers/gpio/gpiolib.c:2828
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_set_debounce
```
**Symbols:**

```
ffffffff81949b50-ffffffff81949c18: gpiod_set_config (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
