# Function: <code>device_get_next_child_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *device_get_next_child_node(struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81551420)
Location: drivers/base/property.c:855
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
```
**Symbols:**

```
ffffffff81551420-ffffffff81551430: device_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *device_get_next_child_node(struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815a3276)
Location: drivers/base/property.c:874
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:device_get_named_child_node
```
**Symbols:**

```
ffffffff815a3260-ffffffff815a3270: device_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *device_get_next_child_node(struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815d1986)
Location: drivers/base/property.c:874
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_named_child_node
  - drivers/base/property.c:device_get_named_child_node
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
```
**Symbols:**

```
ffffffff815d1970-ffffffff815d1980: device_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct fwnode_handle *device_get_next_child_node(struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff815e6470)
Location: drivers/base/property.c:961
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
```
**Symbols:**

```
ffffffff815e6470-ffffffff815e64cb: device_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fwnode_handle *device_get_next_child_node(struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff8164dc30)
Location: drivers/base/property.c:1004
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
```
**Symbols:**

```
ffffffff8164dc30-ffffffff8164dca2: device_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fwnode_handle *device_get_next_child_node(struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81688f00)
Location: drivers/base/property.c:1090
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
```
**Symbols:**

```
ffffffff81688f00-ffffffff81688f72: device_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fwnode_handle *device_get_next_child_node(struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a8bd0)
Location: drivers/base/property.c:613
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
```
**Symbols:**

```
ffffffff816a8bd0-ffffffff816a8c45: device_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fwnode_handle *device_get_next_child_node(struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e1ff0)
Location: drivers/base/property.c:637
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
```
**Symbols:**

```
ffffffff816e1ff0-ffffffff816e206c: device_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct fwnode_handle *device_get_next_child_node(struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817061a0)
Location: drivers/base/property.c:637
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
```
**Symbols:**

```
ffffffff817061a0-ffffffff8170621c: device_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct fwnode_handle *device_get_next_child_node(struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c0f20)
Location: drivers/base/property.c:707
Inline: False
Direct callers:
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
```
**Symbols:**

```
ffffffff817c0f20-ffffffff817c0fd0: device_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct fwnode_handle *device_get_next_child_node(struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d5c90)
Location: drivers/base/property.c:759
Inline: False
Direct callers:
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
```
**Symbols:**

```
ffffffff817d5c90-ffffffff817d5d40: device_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct fwnode_handle *device_get_next_child_node(struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b96b0)
Location: drivers/base/property.c:759
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
```
**Symbols:**

```
ffffffff817b96b0-ffffffff817b9760: device_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *device_get_next_child_node(struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff818433c1)
Location: drivers/base/property.c:759
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_child_node_count
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/base/property.c:device_get_child_node_count
```
**Symbols:**

```
ffffffff81843310-ffffffff81843386: device_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *device_get_next_child_node(struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81987145)
Location: drivers/base/property.c:759
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
```
**Symbols:**

```
ffffffff819870a0-ffffffff81987137: device_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *device_get_next_child_node(const struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81af59a5)
Location: drivers/base/property.c:767
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
```
**Symbols:**

```
ffffffff81af58f0-ffffffff81af5987: device_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *device_get_next_child_node(const struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b43c05)
Location: drivers/base/property.c:794
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
```
**Symbols:**

```
ffffffff81b43b50-ffffffff81b43be7: device_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *device_get_next_child_node(const struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81b9bc55)
Location: drivers/base/property.c:858
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_scan_gpios
```
**Symbols:**

```
ffffffff81b9bba0-ffffffff81b9bc37: device_get_next_child_node (STB_GLOBAL)
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
struct fwnode_handle *device_get_next_child_node(struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f3058)
Location: drivers/base/property.c:637
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
```
**Symbols:**

```
ffff8000108f3058-ffff8000108f30ec: device_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *device_get_next_child_node(struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09df2f8)
Location: drivers/base/property.c:637
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
```
**Symbols:**

```
c09df170-c09df1cc: device_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *device_get_next_child_node(struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098c198)
Location: drivers/base/property.c:637
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
```
**Symbols:**

```
c00000000098bf20-c00000000098bf98: device_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct fwnode_handle *device_get_next_child_node(struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe000584240)
Location: drivers/base/property.c:637
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
```
**Symbols:**

```
ffffffe0005840d0-ffffffe00058411e: device_get_next_child_node (STB_GLOBAL)
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
struct fwnode_handle *device_get_next_child_node(struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cb8f0)
Location: drivers/base/property.c:637
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
```
**Symbols:**

```
ffffffff816cb8f0-ffffffff816cb96c: device_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct fwnode_handle *device_get_next_child_node(struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a6c20)
Location: drivers/base/property.c:637
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
```
**Symbols:**

```
ffffffff816a6c20-ffffffff816a6c9c: device_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct fwnode_handle *device_get_next_child_node(struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816f9e60)
Location: drivers/base/property.c:637
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
```
**Symbols:**

```
ffffffff816f9e60-ffffffff816f9edc: device_get_next_child_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct fwnode_handle *device_get_next_child_node(struct device *dev, struct fwnode_handle *child);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81714700)
Location: drivers/base/property.c:637
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/gpio/gpiolib-acpi.c:acpi_gpiochip_add
  - drivers/base/property.c:device_get_child_node_count
  - drivers/base/property.c:device_get_child_node_count
```
**Symbols:**

```
ffffffff81714700-ffffffff8171477c: device_get_next_child_node (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct device *dev</code> ➡️ <code>const struct device *dev</code>
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
