# Function: <code>acpi_get_gpiod_by_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct gpio_desc *acpi_get_gpiod_by_index(struct acpi_device *adev, const char *propname, int index, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81429270)
Location: drivers/gpio/gpiolib-acpi.c:510
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
```
**Symbols:**

```
ffffffff81429270-ffffffff814293e4: acpi_get_gpiod_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct gpio_desc *acpi_get_gpiod_by_index(struct acpi_device *adev, const char *propname, int index, struct acpi_gpio_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81474620)
Location: drivers/gpio/gpiolib-acpi.c:516
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
```
**Symbols:**

```
ffffffff81474620-ffffffff81474770: acpi_get_gpiod_by_index (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct gpio_desc *acpi_get_gpiod_by_index(struct acpi_device *adev, const char *propname, int index, struct acpi_gpio_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81496150)
Location: drivers/gpio/gpiolib-acpi.c:519
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff81496150-ffffffff814962a0: acpi_get_gpiod_by_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8149fe59)
Location: drivers/gpio/gpiolib-acpi.c:624
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff8149fcd0-ffffffff8149fe23: acpi_get_gpiod_by_index.part.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff814de8f9)
Location: drivers/gpio/gpiolib-acpi.c:563
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff814de770-ffffffff814de8c3: acpi_get_gpiod_by_index.part.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8150dbdc)
Location: drivers/gpio/gpiolib-acpi.c:622
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff8150da70-ffffffff8150dba4: acpi_get_gpiod_by_index.part.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff815238dc)
Location: drivers/gpio/gpiolib-acpi.c:652
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff81523770-ffffffff815238a4: acpi_get_gpiod_by_index.part.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81551d9c)
Location: drivers/gpio/gpiolib-acpi.c:699
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff81551c30-ffffffff81551d67: acpi_get_gpiod_by_index.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8157341c)
Location: drivers/gpio/gpiolib-acpi.c:769
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff815732b0-ffffffff815733e7: acpi_get_gpiod_by_index.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff816172bc)
Location: drivers/gpio/gpiolib-acpi.c:776
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff81617150-ffffffff81617287: acpi_get_gpiod_by_index.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8163e727)
Location: drivers/gpio/gpiolib-acpi.c:810
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff8163da80-ffffffff8163dbb8: acpi_get_gpiod_by_index.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81622137)
Location: drivers/gpio/gpiolib-acpi.c:810
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff81621630-ffffffff81621768: acpi_get_gpiod_by_index.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8169185b)
Location: drivers/gpio/gpiolib-acpi.c:864
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff81690c80-ffffffff81690dbf: acpi_get_gpiod_by_index.part.0 (STB_LOCAL)
ffffffff81ce26a4-ffffffff81ce26b9: acpi_get_gpiod_by_index.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *acpi_get_gpiod_by_index(struct acpi_device *adev, const char *propname, int index, struct acpi_gpio_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:849
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff817afec0-ffffffff817b0033: acpi_get_gpiod_by_index (STB_LOCAL)
ffffffff81ea9039-ffffffff81ea904e: acpi_get_gpiod_by_index.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *acpi_get_gpiod_by_index(struct acpi_device *adev, const char *propname, int index, struct acpi_gpio_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:890
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff818c97d0-ffffffff818c9947: acpi_get_gpiod_by_index (STB_LOCAL)
ffffffff8208e887-ffffffff8208e89c: acpi_get_gpiod_by_index.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8190d927)
Location: drivers/gpio/gpiolib-acpi.c:892
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff8190c890-ffffffff8190c9ec: acpi_get_gpiod_by_index.part.0 (STB_LOCAL)
ffffffff8210eb85-ffffffff8210eb9a: acpi_get_gpiod_by_index.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81955687)
Location: drivers/gpio/gpiolib-acpi.c:868
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_wake_get_by
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff81954490-ffffffff819545ec: acpi_get_gpiod_by_index.part.0 (STB_LOCAL)
ffffffff821ec7c7-ffffffff821ec7dc: acpi_get_gpiod_by_index.part.0.cold (STB_LOCAL)
```
</details>
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
In drivers/gpio/gpiolib-acpi.c (ffff8000106cb318)
Location: drivers/gpio/gpiolib-acpi.c:769
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffff8000106cb168-ffff8000106cb2dc: acpi_get_gpiod_by_index.part.0 (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81568bdc)
Location: drivers/gpio/gpiolib-acpi.c:769
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff81568a70-ffffffff81568ba7: acpi_get_gpiod_by_index.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81559a2c)
Location: drivers/gpio/gpiolib-acpi.c:769
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff815598c0-ffffffff815599f7: acpi_get_gpiod_by_index.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8156774c)
Location: drivers/gpio/gpiolib-acpi.c:769
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff815675e0-ffffffff81567717: acpi_get_gpiod_by_index.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8158166c)
Location: drivers/gpio/gpiolib-acpi.c:769
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_dev_gpio_irq_get
  - drivers/gpio/gpiolib-acpi.c:acpi_node_get_gpiod
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff81581500-ffffffff81581637: acpi_get_gpiod_by_index.part.0 (STB_LOCAL)
```
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
