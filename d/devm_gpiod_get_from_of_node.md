# Function: <code>devm_gpiod_get_from_of_node</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_from_of_node(struct device *dev, struct device_node *node, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/devres.c (ffffffff81505e40)
Location: drivers/gpio/devres.c:142
Inline: False
```
**Symbols:**

```
ffffffff81505e40-ffffffff81505ef9: devm_gpiod_get_from_of_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_from_of_node(struct device *dev, struct device_node *node, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81521170)
Location: drivers/gpio/gpiolib-devres.c:147
Inline: False
```
**Symbols:**

```
ffffffff81521170-ffffffff8152123e: devm_gpiod_get_from_of_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_from_of_node(struct device *dev, struct device_node *node, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8154f670)
Location: drivers/gpio/gpiolib-devres.c:147
Inline: False
```
**Symbols:**

```
ffffffff8154f670-ffffffff8154f73e: devm_gpiod_get_from_of_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_from_of_node(struct device *dev, struct device_node *node, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81570a90)
Location: drivers/gpio/gpiolib-devres.c:147
Inline: False
```
**Symbols:**

```
ffffffff81570a90-ffffffff81570aa2: devm_gpiod_get_from_of_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_from_of_node(struct device *dev, struct device_node *node, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81614f70)
Location: drivers/gpio/gpiolib-devres.c:147
Inline: False
```
**Symbols:**

```
ffffffff81614f70-ffffffff81614f82: devm_gpiod_get_from_of_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_from_of_node(struct device *dev, struct device_node *node, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81639260)
Location: drivers/gpio/gpiolib-devres.c:147
Inline: False
```
**Symbols:**

```
ffffffff81639260-ffffffff81639272: devm_gpiod_get_from_of_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_from_of_node(struct device *dev, struct device_node *node, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8161cec0)
Location: drivers/gpio/gpiolib-devres.c:147
Inline: False
```
**Symbols:**

```
ffffffff8161cec0-ffffffff8161ced2: devm_gpiod_get_from_of_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_from_of_node(struct device *dev, const struct device_node *node, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8168c340)
Location: drivers/gpio/gpiolib-devres.c:147
Inline: False
```
**Symbols:**

```
ffffffff8168c340-ffffffff8168c352: devm_gpiod_get_from_of_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_from_of_node(struct device *dev, const struct device_node *node, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff817a9890)
Location: drivers/gpio/gpiolib-devres.c:147
Inline: False
```
**Symbols:**

```
ffffffff817a9890-ffffffff817a98a6: devm_gpiod_get_from_of_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_from_of_node(struct device *dev, const struct device_node *node, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff818c2340)
Location: drivers/gpio/gpiolib-devres.c:147
Inline: False
```
**Symbols:**

```
ffffffff818c2340-ffffffff818c2356: devm_gpiod_get_from_of_node (STB_GLOBAL)
```
</details>
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
struct gpio_desc *devm_gpiod_get_from_of_node(struct device *dev, struct device_node *node, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffff8000106c6c18)
Location: drivers/gpio/gpiolib-devres.c:147
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
**Symbols:**

```
ffff8000106c6c18-ffff8000106c6d2c: devm_gpiod_get_from_of_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_from_of_node(struct device *dev, struct device_node *node, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (c0864634)
Location: drivers/gpio/gpiolib-devres.c:147
Inline: False
Direct callers:
  - drivers/pci/controller/pci-tegra.c:tegra_pcie_parse_dt
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
**Symbols:**

```
c0864634-c086472c: devm_gpiod_get_from_of_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_from_of_node(struct device *dev, struct device_node *node, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (c000000000843540)
Location: drivers/gpio/gpiolib-devres.c:147
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
**Symbols:**

```
c000000000843540-c000000000843664: devm_gpiod_get_from_of_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_from_of_node(struct device *dev, struct device_node *node, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffe0004aa7a0)
Location: drivers/gpio/gpiolib-devres.c:147
Inline: False
Direct callers:
  - drivers/mfd/arizona-core.c:arizona_dev_init
```
**Symbols:**

```
ffffffe0004aa7a0-ffffffe0004aa862: devm_gpiod_get_from_of_node (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_from_of_node(struct device *dev, struct device_node *node, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81566250)
Location: drivers/gpio/gpiolib-devres.c:147
Inline: False
```
**Symbols:**

```
ffffffff81566250-ffffffff81566262: devm_gpiod_get_from_of_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_from_of_node(struct device *dev, struct device_node *node, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff815570a0)
Location: drivers/gpio/gpiolib-devres.c:147
Inline: False
```
**Symbols:**

```
ffffffff815570a0-ffffffff815570b2: devm_gpiod_get_from_of_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_from_of_node(struct device *dev, struct device_node *node, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff81564dc0)
Location: drivers/gpio/gpiolib-devres.c:147
Inline: False
```
**Symbols:**

```
ffffffff81564dc0-ffffffff81564dd2: devm_gpiod_get_from_of_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct gpio_desc *devm_gpiod_get_from_of_node(struct device *dev, struct device_node *node, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (ffffffff8157ece0)
Location: drivers/gpio/gpiolib-devres.c:147
Inline: False
```
**Symbols:**

```
ffffffff8157ece0-ffffffff8157ecf2: devm_gpiod_get_from_of_node (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct device_node *node</code> ➡️ <code>const struct device_node *node</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
