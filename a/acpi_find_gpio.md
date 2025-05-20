# Function: <code>acpi_find_gpio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
struct gpio_desc *acpi_find_gpio(struct device *dev, const char *con_id, unsigned int idx, enum gpio_lookup_flags *flags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81426ed5)
Location: drivers/gpio/gpiolib.c:1850
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81428bc0)
Location: drivers/gpio/gpiolib-acpi.c:397
Inline: True
```
**Symbols:**

```
ffffffff81428bc0-ffffffff81428cbe: acpi_find_gpio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
struct gpio_desc *acpi_find_gpio(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags, enum gpio_lookup_flags *lookupflags);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81471b45)
Location: drivers/gpio/gpiolib.c:2855
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
```
In drivers/gpio/gpiolib-acpi.c (ffffffff81473f40)
Location: drivers/gpio/gpiolib-acpi.c:398
Inline: True
```
**Symbols:**

```
ffffffff81473f40-ffffffff81474047: acpi_find_gpio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct gpio_desc *acpi_find_gpio(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags flags, enum gpio_lookup_flags *lookupflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81496b60)
Location: drivers/gpio/gpiolib-acpi.c:552
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff81496b60-ffffffff81496d19: acpi_find_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct gpio_desc *acpi_find_gpio(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags *dflags, enum gpio_lookup_flags *lookupflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff814a0780)
Location: drivers/gpio/gpiolib-acpi.c:657
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff814a0780-ffffffff814a09a2: acpi_find_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct gpio_desc *acpi_find_gpio(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags *dflags, enum gpio_lookup_flags *lookupflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff814df190)
Location: drivers/gpio/gpiolib-acpi.c:596
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff814df190-ffffffff814df3ac: acpi_find_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct gpio_desc *acpi_find_gpio(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags *dflags, enum gpio_lookup_flags *lookupflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8150e580)
Location: drivers/gpio/gpiolib-acpi.c:655
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff8150e580-ffffffff8150e754: acpi_find_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct gpio_desc *acpi_find_gpio(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags *dflags, enum gpio_lookup_flags *lookupflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81523bd0)
Location: drivers/gpio/gpiolib-acpi.c:685
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff81523bd0-ffffffff81523dad: acpi_find_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct gpio_desc *acpi_find_gpio(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags *dflags, long unsigned int *lookupflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81552140)
Location: drivers/gpio/gpiolib-acpi.c:732
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff81552140-ffffffff81552357: acpi_find_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct gpio_desc *acpi_find_gpio(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags *dflags, long unsigned int *lookupflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81573780)
Location: drivers/gpio/gpiolib-acpi.c:812
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff81573780-ffffffff81573997: acpi_find_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct gpio_desc *acpi_find_gpio(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags *dflags, long unsigned int *lookupflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81617ea0)
Location: drivers/gpio/gpiolib-acpi.c:819
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff81617ea0-ffffffff816180b7: acpi_find_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct gpio_desc *acpi_find_gpio(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags *dflags, long unsigned int *lookupflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8163e8c0)
Location: drivers/gpio/gpiolib-acpi.c:853
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff8163e8c0-ffffffff8163eae0: acpi_find_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct gpio_desc *acpi_find_gpio(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags *dflags, long unsigned int *lookupflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff816222d0)
Location: drivers/gpio/gpiolib-acpi.c:853
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff816222d0-ffffffff816224ef: acpi_find_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *acpi_find_gpio(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags *dflags, long unsigned int *lookupflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:907
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff81ce27dd-ffffffff81ce27fa: acpi_find_gpio.cold (STB_LOCAL)
ffffffff81691a50-ffffffff81691c7e: acpi_find_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *acpi_find_gpio(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags *dflags, long unsigned int *lookupflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:892
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff81ea91bc-ffffffff81ea91d9: acpi_find_gpio.cold (STB_LOCAL)
ffffffff817b0f70-ffffffff817b11ec: acpi_find_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *acpi_find_gpio(struct fwnode_handle *fwnode, const char *con_id, unsigned int idx, enum gpiod_flags *dflags, long unsigned int *lookupflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:972
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
```
**Symbols:**

```
ffffffff8208e95a-ffffffff8208e976: acpi_find_gpio.cold (STB_LOCAL)
ffffffff818caaa0-ffffffff818cacd6: acpi_find_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *acpi_find_gpio(struct fwnode_handle *fwnode, const char *con_id, unsigned int idx, enum gpiod_flags *dflags, long unsigned int *lookupflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:974
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
```
**Symbols:**

```
ffffffff8210ec4c-ffffffff8210ec68: acpi_find_gpio.cold (STB_LOCAL)
ffffffff8190dbb0-ffffffff8190ddec: acpi_find_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct gpio_desc *acpi_find_gpio(struct fwnode_handle *fwnode, const char *con_id, unsigned int idx, enum gpiod_flags *dflags, long unsigned int *lookupflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (0)
Location: drivers/gpio/gpiolib-acpi.c:951
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
```
**Symbols:**

```
ffffffff821ec888-ffffffff821ec8a4: acpi_find_gpio.cold (STB_LOCAL)
ffffffff81955910-ffffffff81955b4c: acpi_find_gpio (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct gpio_desc *acpi_find_gpio(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags *dflags, long unsigned int *lookupflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffff8000106cb730)
Location: drivers/gpio/gpiolib-acpi.c:812
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffff8000106cb730-ffff8000106cb960: acpi_find_gpio (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
struct gpio_desc *acpi_find_gpio(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags *dflags, long unsigned int *lookupflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81568f40)
Location: drivers/gpio/gpiolib-acpi.c:812
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff81568f40-ffffffff81569157: acpi_find_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct gpio_desc *acpi_find_gpio(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags *dflags, long unsigned int *lookupflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81559d90)
Location: drivers/gpio/gpiolib-acpi.c:812
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff81559d90-ffffffff81559fa7: acpi_find_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct gpio_desc *acpi_find_gpio(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags *dflags, long unsigned int *lookupflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81567ab0)
Location: drivers/gpio/gpiolib-acpi.c:812
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff81567ab0-ffffffff81567cc7: acpi_find_gpio (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct gpio_desc *acpi_find_gpio(struct device *dev, const char *con_id, unsigned int idx, enum gpiod_flags *dflags, long unsigned int *lookupflags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff815819d0)
Location: drivers/gpio/gpiolib-acpi.c:812
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff815819d0-ffffffff81581be7: acpi_find_gpio (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum gpio_lookup_flags *lookupflags</code>
</li>
<li>
<b>Param type changed. </b>
<code>enum gpio_lookup_flags *flags</code> ➡️ <code>enum gpiod_flags flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum gpiod_flags *dflags</code>
</li>
<li>
<b>Param removed. </b>
<code>enum gpiod_flags flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>enum gpio_lookup_flags *lookupflags</code> ➡️ <code>long unsigned int *lookupflags</code>
</li>
</ul>
</details>
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct fwnode_handle *fwnode</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device *dev</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
