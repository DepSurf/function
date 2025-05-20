# Function: <code>gpiod_get_from_of_node</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiod_get_from_of_node(struct device_node *node, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81506540)
Location: drivers/gpio/gpiolib.c:3906
Inline: True
Direct callers:
  - drivers/gpio/devres.c:devm_gpiod_get_from_of_node
```
**Symbols:**

```
ffffffff81506540-ffffffff8150654d: gpiod_get_from_of_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiod_get_from_of_node(struct device_node *node, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151ab40)
Location: drivers/gpio/gpiolib.c:4181
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
```
**Symbols:**

```
ffffffff8151ab40-ffffffff8151ab4d: gpiod_get_from_of_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *gpiod_get_from_of_node(struct device_node *node, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81548b30)
Location: drivers/gpio/gpiolib.c:4279
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
```
**Symbols:**

```
ffffffff81548b30-ffffffff81548b42: gpiod_get_from_of_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/gpio/consumer.h:577
Inline: True
```
```
In drivers/gpio/gpiolib-devres.c (0)
Location: include/linux/gpio/consumer.h:577
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/gpio/consumer.h:622
Inline: True
```
```
In drivers/gpio/gpiolib-devres.c (0)
Location: include/linux/gpio/consumer.h:622
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/gpio/consumer.h:622
Inline: True
```
```
In drivers/gpio/gpiolib-devres.c (0)
Location: include/linux/gpio/consumer.h:622
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/gpio/consumer.h:622
Inline: True
```
```
In drivers/gpio/gpiolib-devres.c (0)
Location: include/linux/gpio/consumer.h:622
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/gpio/consumer.h:622
Inline: True
```
```
In drivers/gpio/gpiolib-devres.c (0)
Location: include/linux/gpio/consumer.h:622
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/gpio/consumer.h:631
Inline: True
```
```
In drivers/gpio/gpiolib-devres.c (0)
Location: include/linux/gpio/consumer.h:631
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-devres.c (0)
Location: include/linux/gpio/consumer.h:597
Inline: True
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
struct gpio_desc *gpiod_get_from_of_node(struct device_node *node, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (ffff8000106c7da8)
Location: drivers/gpio/gpiolib-of.c:316
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
```
**Symbols:**

```
ffff8000106c7da8-ffff8000106c7eac: gpiod_get_from_of_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct gpio_desc *gpiod_get_from_of_node(struct device_node *node, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (c0865570)
Location: drivers/gpio/gpiolib-of.c:316
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
```
**Symbols:**

```
c0865570-c086565c: gpiod_get_from_of_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct gpio_desc *gpiod_get_from_of_node(struct device_node *node, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (c0000000008450e0)
Location: drivers/gpio/gpiolib-of.c:316
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
```
**Symbols:**

```
c0000000008450e0-c00000000084522c: gpiod_get_from_of_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct gpio_desc *gpiod_get_from_of_node(struct device_node *node, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-of.c (ffffffe0004ab688)
Location: drivers/gpio/gpiolib-of.c:316
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_gpiod_get_from_of_node
```
**Symbols:**

```
ffffffe0004ab688-ffffffe0004ab74e: gpiod_get_from_of_node (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/gpio/consumer.h:577
Inline: True
```
```
In drivers/gpio/gpiolib-devres.c (0)
Location: include/linux/gpio/consumer.h:577
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/gpio/consumer.h:577
Inline: True
```
```
In drivers/gpio/gpiolib-devres.c (0)
Location: include/linux/gpio/consumer.h:577
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/gpio/consumer.h:577
Inline: True
```
```
In drivers/gpio/gpiolib-devres.c (0)
Location: include/linux/gpio/consumer.h:577
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: include/linux/gpio/consumer.h:577
Inline: True
```
```
In drivers/gpio/gpiolib-devres.c (0)
Location: include/linux/gpio/consumer.h:577
Inline: True
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
</ul>
<b>Arch</b>
<ul>
</ul>
