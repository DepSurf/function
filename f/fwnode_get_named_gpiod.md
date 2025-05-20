# Function: <code>fwnode_get_named_gpiod</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct gpio_desc *fwnode_get_named_gpiod(struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81426cf0)
Location: drivers/gpio/gpiolib.c:2195
Inline: False
Direct callers:
  - drivers/gpio/devres.c:devm_get_gpiod_from_child
```
**Symbols:**

```
ffffffff81426cf0-ffffffff81426d7e: fwnode_get_named_gpiod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct gpio_desc *fwnode_get_named_gpiod(struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814710b0)
Location: drivers/gpio/gpiolib.c:3201
Inline: False
Direct callers:
  - drivers/gpio/devres.c:devm_get_gpiod_from_child
```
**Symbols:**

```
ffffffff814710b0-ffffffff8147114f: fwnode_get_named_gpiod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct gpio_desc *fwnode_get_named_gpiod(struct fwnode_handle *fwnode, const char *propname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81493220)
Location: drivers/gpio/gpiolib.c:3322
Inline: False
Direct callers:
  - drivers/gpio/devres.c:devm_get_gpiod_from_child
```
**Symbols:**

```
ffffffff81493220-ffffffff814932bf: fwnode_get_named_gpiod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct gpio_desc *fwnode_get_named_gpiod(struct fwnode_handle *fwnode, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149e0d0)
Location: drivers/gpio/gpiolib.c:3338
Inline: False
Direct callers:
  - drivers/gpio/devres.c:devm_fwnode_get_index_gpiod_from_child
```
**Symbols:**

```
ffffffff8149e0d0-ffffffff8149e1db: fwnode_get_named_gpiod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct gpio_desc *fwnode_get_named_gpiod(struct fwnode_handle *fwnode, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814dcc20)
Location: drivers/gpio/gpiolib.c:3687
Inline: False
Direct callers:
  - drivers/gpio/devres.c:devm_fwnode_get_index_gpiod_from_child
```
**Symbols:**

```
ffffffff814dcc20-ffffffff814dcd34: fwnode_get_named_gpiod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct gpio_desc *fwnode_get_named_gpiod(struct fwnode_handle *fwnode, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8150b020)
Location: drivers/gpio/gpiolib.c:3983
Inline: False
Direct callers:
  - drivers/gpio/devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffff8150b020-ffffffff8150b127: fwnode_get_named_gpiod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct gpio_desc *fwnode_get_named_gpiod(struct fwnode_handle *fwnode, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151fe70)
Location: drivers/gpio/gpiolib.c:4260
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffff8151fe70-ffffffff8151ff77: fwnode_get_named_gpiod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct gpio_desc *fwnode_get_named_gpiod(struct fwnode_handle *fwnode, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154dfd0)
Location: drivers/gpio/gpiolib.c:4355
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
  - drivers/net/phy/mdio_bus.c:mdiobus_register_device
```
**Symbols:**

```
ffffffff8154dfd0-ffffffff8154e0d5: fwnode_get_named_gpiod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct gpio_desc *fwnode_get_named_gpiod(struct fwnode_handle *fwnode, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156f1d0)
Location: drivers/gpio/gpiolib.c:4620
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
```
**Symbols:**

```
ffffffff8156f1d0-ffffffff8156f2d5: fwnode_get_named_gpiod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct gpio_desc *fwnode_get_named_gpiod(struct fwnode_handle *fwnode, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff816136d0)
Location: drivers/gpio/gpiolib.c:5096
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_gpiod_get_index
```
**Symbols:**

```
ffffffff816136d0-ffffffff81613834: fwnode_get_named_gpiod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct gpio_desc *fwnode_get_named_gpiod(struct fwnode_handle *fwnode, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff816385b0)
Location: drivers/gpio/gpiolib.c:3920
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_gpiod_get_index
```
**Symbols:**

```
ffffffff816385b0-ffffffff81638714: fwnode_get_named_gpiod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct gpio_desc *fwnode_get_named_gpiod(struct fwnode_handle *fwnode, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8161c0f0)
Location: drivers/gpio/gpiolib.c:3901
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_gpiod_get_index
```
**Symbols:**

```
ffffffff8161c0f0-ffffffff8161c246: fwnode_get_named_gpiod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct gpio_desc *fwnode_get_named_gpiod(struct fwnode_handle *fwnode, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8168b610)
Location: drivers/gpio/gpiolib.c:3960
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_gpiod_get_index
```
**Symbols:**

```
ffffffff8168b610-ffffffff8168b766: fwnode_get_named_gpiod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct gpio_desc *fwnode_get_named_gpiod(struct fwnode_handle *fwnode, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a8980)
Location: drivers/gpio/gpiolib.c:4086
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_gpiod_get_index
```
**Symbols:**

```
ffffffff817a8980-ffffffff817a8b07: fwnode_get_named_gpiod (STB_GLOBAL)
```
</details>
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
struct gpio_desc *fwnode_get_named_gpiod(struct fwnode_handle *fwnode, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c5248)
Location: drivers/gpio/gpiolib.c:4620
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
```
**Symbols:**

```
ffff8000106c5248-ffff8000106c53a8: fwnode_get_named_gpiod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *fwnode_get_named_gpiod(struct fwnode_handle *fwnode, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c0863428)
Location: drivers/gpio/gpiolib.c:4620
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
```
**Symbols:**

```
c0863428-c08634d0: fwnode_get_named_gpiod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *fwnode_get_named_gpiod(struct fwnode_handle *fwnode, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c000000000841e10)
Location: drivers/gpio/gpiolib.c:4620
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
```
**Symbols:**

```
c000000000841e10-c000000000841f08: fwnode_get_named_gpiod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct gpio_desc *fwnode_get_named_gpiod(struct fwnode_handle *fwnode, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a97c4)
Location: drivers/gpio/gpiolib.c:4620
Inline: True
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
```
**Symbols:**

```
ffffffe0004a97c4-ffffffe0004a985e: fwnode_get_named_gpiod (STB_GLOBAL)
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
struct gpio_desc *fwnode_get_named_gpiod(struct fwnode_handle *fwnode, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81564990)
Location: drivers/gpio/gpiolib.c:4620
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
```
**Symbols:**

```
ffffffff81564990-ffffffff81564a95: fwnode_get_named_gpiod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct gpio_desc *fwnode_get_named_gpiod(struct fwnode_handle *fwnode, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815557e0)
Location: drivers/gpio/gpiolib.c:4620
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
```
**Symbols:**

```
ffffffff815557e0-ffffffff815558e5: fwnode_get_named_gpiod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct gpio_desc *fwnode_get_named_gpiod(struct fwnode_handle *fwnode, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81563500)
Location: drivers/gpio/gpiolib.c:4620
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
```
**Symbols:**

```
ffffffff81563500-ffffffff81563605: fwnode_get_named_gpiod (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct gpio_desc *fwnode_get_named_gpiod(struct fwnode_handle *fwnode, const char *propname, int index, enum gpiod_flags dflags, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157d420)
Location: drivers/gpio/gpiolib.c:4620
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-devres.c:devm_fwnode_get_index_gpiod_from_child
```
**Symbols:**

```
ffffffff8157d420-ffffffff8157d525: fwnode_get_named_gpiod (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int index</code>
</li>
<li>
<b>Param added. </b>
<code>enum gpiod_flags dflags</code>
</li>
<li>
<b>Param added. </b>
<code>const char *label</code>
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
