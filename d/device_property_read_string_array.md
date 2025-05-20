# Function: <code>device_property_read_string_array</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int device_property_read_string_array(struct device *dev, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81551200)
Location: drivers/base/property.c:345
Inline: False
```
**Symbols:**

```
ffffffff81551200-ffffffff81551217: device_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int device_property_read_string_array(struct device *dev, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815a2fc0)
Location: drivers/base/property.c:351
Inline: False
```
**Symbols:**

```
ffffffff815a2fc0-ffffffff815a2fd7: device_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int device_property_read_string_array(struct device *dev, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815d16d0)
Location: drivers/base/property.c:351
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
```
**Symbols:**

```
ffffffff815d16d0-ffffffff815d16e7: device_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int device_property_read_string_array(struct device *dev, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e6400)
Location: drivers/base/property.c:383
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff815e6400-ffffffff815e6417: device_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int device_property_read_string_array(struct device *dev, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164d770)
Location: drivers/base/property.c:392
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff8164d770-ffffffff8164d787: device_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int device_property_read_string_array(struct device *dev, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816889d0)
Location: drivers/base/property.c:453
Inline: False
```
**Symbols:**

```
ffffffff816889d0-ffffffff816889e7: device_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int device_property_read_string_array(struct device *dev, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a86c0)
Location: drivers/base/property.c:178
Inline: False
```
**Symbols:**

```
ffffffff816a86c0-ffffffff816a86d7: device_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int device_property_read_string_array(struct device *dev, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e1ef0)
Location: drivers/base/property.c:178
Inline: False
```
**Symbols:**

```
ffffffff816e1ef0-ffffffff816e1f07: device_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int device_property_read_string_array(struct device *dev, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817060a0)
Location: drivers/base/property.c:178
Inline: False
```
**Symbols:**

```
ffffffff817060a0-ffffffff817060b7: device_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int device_property_read_string_array(struct device *dev, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c0710)
Location: drivers/base/property.c:178
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff817c0710-ffffffff817c0727: device_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int device_property_read_string_array(struct device *dev, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d55d0)
Location: drivers/base/property.c:178
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff817d55d0-ffffffff817d55e7: device_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int device_property_read_string_array(struct device *dev, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b9010)
Location: drivers/base/property.c:178
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff817b9010-ffffffff817b9027: device_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int device_property_read_string_array(struct device *dev, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81842c70)
Location: drivers/base/property.c:178
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff81842c70-ffffffff81842c87: device_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int device_property_read_string_array(struct device *dev, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81986560)
Location: drivers/base/property.c:194
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff81986560-ffffffff81986583: device_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int device_property_read_string_array(struct device *dev, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af4bd0)
Location: drivers/base/property.c:201
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff81af4bd0-ffffffff81af4bf3: device_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int device_property_read_string_array(const struct device *dev, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b42de0)
Location: drivers/base/property.c:205
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff81b42de0-ffffffff81b42e03: device_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int device_property_read_string_array(const struct device *dev, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9acb0)
Location: drivers/base/property.c:205
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/power/supply/power_supply_core.c:__power_supply_register
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff81b9acb0-ffffffff81b9acd3: device_property_read_string_array (STB_GLOBAL)
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
int device_property_read_string_array(struct device *dev, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f2e50)
Location: drivers/base/property.c:178
Inline: False
```
**Symbols:**

```
ffff8000108f2e50-ffff8000108f2ec8: device_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int device_property_read_string_array(struct device *dev, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09df9a8)
Location: drivers/base/property.c:178
Inline: False
```
**Symbols:**

```
c09df9a8-c09df9d4: device_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int device_property_read_string_array(struct device *dev, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098cad0)
Location: drivers/base/property.c:178
Inline: False
```
**Symbols:**

```
c00000000098cad0-c00000000098cb08: device_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int device_property_read_string_array(struct device *dev, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe000584810)
Location: drivers/base/property.c:178
Inline: False
```
**Symbols:**

```
ffffffe000584810-ffffffe000584860: device_property_read_string_array (STB_GLOBAL)
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
int device_property_read_string_array(struct device *dev, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cb7f0)
Location: drivers/base/property.c:178
Inline: False
```
**Symbols:**

```
ffffffff816cb7f0-ffffffff816cb807: device_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int device_property_read_string_array(struct device *dev, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a6b20)
Location: drivers/base/property.c:178
Inline: False
```
**Symbols:**

```
ffffffff816a6b20-ffffffff816a6b37: device_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int device_property_read_string_array(struct device *dev, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816f9d60)
Location: drivers/base/property.c:178
Inline: False
```
**Symbols:**

```
ffffffff816f9d60-ffffffff816f9d77: device_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int device_property_read_string_array(struct device *dev, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81714600)
Location: drivers/base/property.c:178
Inline: False
```
**Symbols:**

```
ffffffff81714600-ffffffff81714617: device_property_read_string_array (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct device *dev</code> ➡️ <code>const struct device *dev</code>
</li>
</ul>
</details>
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
