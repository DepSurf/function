# Function: <code>fwnode_property_read_string_array</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fwnode_property_read_string_array(struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815511b0)
Location: drivers/base/property.c:589
Inline: False
Direct callers:
  - drivers/base/property.c:device_property_read_string_array
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:fwnode_property_match_string
```
**Symbols:**

```
ffffffff815511b0-ffffffff815511ff: fwnode_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fwnode_property_read_string_array(struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815a2f50)
Location: drivers/base/property.c:596
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:device_property_read_string_array
```
**Symbols:**

```
ffffffff815a2f50-ffffffff815a2fb6: fwnode_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fwnode_property_read_string_array(struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815d1660)
Location: drivers/base/property.c:596
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:device_property_read_string_array
```
**Symbols:**

```
ffffffff815d1660-ffffffff815d16c6: fwnode_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fwnode_property_read_string_array(struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e6340)
Location: drivers/base/property.c:574
Inline: False
Direct callers:
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:device_property_read_string_array
```
**Symbols:**

```
ffffffff815e6340-ffffffff815e63f1: fwnode_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fwnode_property_read_string_array(const struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164d6b0)
Location: drivers/base/property.c:583
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:device_get_phy_mode
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:device_property_read_string_array
```
**Symbols:**

```
ffffffff8164d6b0-ffffffff8164d766: fwnode_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fwnode_property_read_string_array(const struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81688910)
Location: drivers/base/property.c:644
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
```
**Symbols:**

```
ffffffff81688910-ffffffff816889c6: fwnode_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fwnode_property_read_string_array(const struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a8600)
Location: drivers/base/property.c:369
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
```
**Symbols:**

```
ffffffff816a8600-ffffffff816a86b6: fwnode_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fwnode_property_read_string_array(const struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e1e40)
Location: drivers/base/property.c:369
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
```
**Symbols:**

```
ffffffff816e1e40-ffffffff816e1ee8: fwnode_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fwnode_property_read_string_array(const struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81705ff0)
Location: drivers/base/property.c:369
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
```
**Symbols:**

```
ffffffff81705ff0-ffffffff81706098: fwnode_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fwnode_property_read_string_array(const struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c0660)
Location: drivers/base/property.c:369
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
```
**Symbols:**

```
ffffffff817c0660-ffffffff817c0708: fwnode_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fwnode_property_read_string_array(const struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d5520)
Location: drivers/base/property.c:369
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
```
**Symbols:**

```
ffffffff817d5520-ffffffff817d55c8: fwnode_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fwnode_property_read_string_array(const struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b8f60)
Location: drivers/base/property.c:369
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
```
**Symbols:**

```
ffffffff817b8f60-ffffffff817b9008: fwnode_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fwnode_property_read_string_array(const struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81842bc0)
Location: drivers/base/property.c:369
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:devprop_gpiochip_set_names
  - drivers/gpio/gpiolib.c:devprop_gpiochip_set_names
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
```
**Symbols:**

```
ffffffff81842bc0-ffffffff81842c68: fwnode_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fwnode_property_read_string_array(const struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81986480)
Location: drivers/base/property.c:401
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/gpio/gpiolib.c:gpiochip_add_data_with_key
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
```
**Symbols:**

```
ffffffff81986480-ffffffff8198655a: fwnode_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fwnode_property_read_string_array(const struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af4ae0)
Location: drivers/base/property.c:408
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
```
**Symbols:**

```
ffffffff81af4ae0-ffffffff81af4bba: fwnode_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fwnode_property_read_string_array(const struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b42cf0)
Location: drivers/base/property.c:412
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
```
**Symbols:**

```
ffffffff81b42cf0-ffffffff81b42dca: fwnode_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fwnode_property_read_string_array(const struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9abc0)
Location: drivers/base/property.c:412
Inline: False
Direct callers:
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_property_match_property_string
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
```
**Symbols:**

```
ffffffff81b9abc0-ffffffff81b9ac9a: fwnode_property_read_string_array (STB_GLOBAL)
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
int fwnode_property_read_string_array(const struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f2d80)
Location: drivers/base/property.c:369
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
  - drivers/base/property.c:device_property_read_string_array
```
**Symbols:**

```
ffff8000108f2d80-ffff8000108f2e4c: fwnode_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fwnode_property_read_string_array(const struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09df904)
Location: drivers/base/property.c:369
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
```
**Symbols:**

```
c09df904-c09df9a8: fwnode_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fwnode_property_read_string_array(const struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098c990)
Location: drivers/base/property.c:369
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
  - drivers/base/property.c:device_property_read_string_array
```
**Symbols:**

```
c00000000098c990-c00000000098cac8: fwnode_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fwnode_property_read_string_array(const struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe000584780)
Location: drivers/base/property.c:369
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
```
**Symbols:**

```
ffffffe000584780-ffffffe000584810: fwnode_property_read_string_array (STB_GLOBAL)
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
int fwnode_property_read_string_array(const struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cb740)
Location: drivers/base/property.c:369
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
```
**Symbols:**

```
ffffffff816cb740-ffffffff816cb7e8: fwnode_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fwnode_property_read_string_array(const struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a6a70)
Location: drivers/base/property.c:369
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
```
**Symbols:**

```
ffffffff816a6a70-ffffffff816a6b18: fwnode_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fwnode_property_read_string_array(const struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816f9cb0)
Location: drivers/base/property.c:369
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
```
**Symbols:**

```
ffffffff816f9cb0-ffffffff816f9d58: fwnode_property_read_string_array (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fwnode_property_read_string_array(const struct fwnode_handle *fwnode, const char *propname, const char **val, size_t nval);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81714550)
Location: drivers/base/property.c:369
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/gpio/gpiolib-devprop.c:devprop_gpiochip_set_names
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_get_phy_mode
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:fwnode_property_match_string
  - drivers/base/property.c:device_property_read_string
  - drivers/base/property.c:device_property_read_string_array
```
**Symbols:**

```
ffffffff81714550-ffffffff817145f8: fwnode_property_read_string_array (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fwnode_handle *fwnode</code> ➡️ <code>const struct fwnode_handle *fwnode</code>
</li>
</ul>
</details>
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
