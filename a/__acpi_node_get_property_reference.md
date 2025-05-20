# Function: <code>__acpi_node_get_property_reference</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __acpi_node_get_property_reference(struct fwnode_handle *fwnode, const char *propname, size_t index, size_t num_args, struct acpi_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff814fbfb3)
Location: drivers/acpi/property.c:559
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
```
**Symbols:**

```
ffffffff814fbfb3-ffffffff814fc14c: __acpi_node_get_property_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __acpi_node_get_property_reference(struct fwnode_handle *fwnode, const char *propname, size_t index, size_t num_args, struct acpi_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8150bb30)
Location: drivers/acpi/property.c:575
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
```
**Symbols:**

```
ffffffff8150bb30-ffffffff8150bd57: __acpi_node_get_property_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __acpi_node_get_property_reference(const struct fwnode_handle *fwnode, const char *propname, size_t index, size_t num_args, struct acpi_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8154dfb0)
Location: drivers/acpi/property.c:580
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/acpi/property.c:acpi_fwnode_get_reference_args
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
```
**Symbols:**

```
ffffffff8154dfb0-ffffffff8154e1b2: __acpi_node_get_property_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __acpi_node_get_property_reference(const struct fwnode_handle *fwnode, const char *propname, size_t index, size_t num_args, struct acpi_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81584ef0)
Location: drivers/acpi/property.c:580
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/acpi/property.c:acpi_fwnode_get_reference_args
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
```
**Symbols:**

```
ffffffff81584ef0-ffffffff81585105: __acpi_node_get_property_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __acpi_node_get_property_reference(const struct fwnode_handle *fwnode, const char *propname, size_t index, size_t num_args, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8159cd40)
Location: drivers/acpi/property.c:653
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/acpi/property.c:acpi_fwnode_get_reference_args
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
```
**Symbols:**

```
ffffffff8159cd40-ffffffff8159cf84: __acpi_node_get_property_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __acpi_node_get_property_reference(const struct fwnode_handle *fwnode, const char *propname, size_t index, size_t num_args, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ce190)
Location: drivers/acpi/property.c:671
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/acpi/property.c:acpi_fwnode_get_reference_args
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
```
**Symbols:**

```
ffffffff815ce190-ffffffff815ce3aa: __acpi_node_get_property_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __acpi_node_get_property_reference(const struct fwnode_handle *fwnode, const char *propname, size_t index, size_t num_args, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815ef410)
Location: drivers/acpi/property.c:671
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/acpi/property.c:acpi_fwnode_get_reference_args
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
```
**Symbols:**

```
ffffffff815ef410-ffffffff815ef62a: __acpi_node_get_property_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __acpi_node_get_property_reference(const struct fwnode_handle *fwnode, const char *propname, size_t index, size_t num_args, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169b620)
Location: drivers/acpi/property.c:671
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/acpi/property.c:acpi_fwnode_get_reference_args
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
```
**Symbols:**

```
ffffffff8169b620-ffffffff8169b83a: __acpi_node_get_property_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __acpi_node_get_property_reference(const struct fwnode_handle *fwnode, const char *propname, size_t index, size_t num_args, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff816b8440)
Location: drivers/acpi/property.c:664
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/acpi/property.c:acpi_fwnode_get_reference_args
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
```
**Symbols:**

```
ffffffff816b8440-ffffffff816b865a: __acpi_node_get_property_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __acpi_node_get_property_reference(const struct fwnode_handle *fwnode, const char *propname, size_t index, size_t num_args, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8169a3e0)
Location: drivers/acpi/property.c:664
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/acpi/property.c:acpi_fwnode_get_reference_args
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
```
**Symbols:**

```
ffffffff8169a3e0-ffffffff8169a5fa: __acpi_node_get_property_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __acpi_node_get_property_reference(const struct fwnode_handle *fwnode, const char *propname, size_t index, size_t num_args, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81710240)
Location: drivers/acpi/property.c:664
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/acpi/property.c:acpi_fwnode_get_reference_args
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
```
**Symbols:**

```
ffffffff81710240-ffffffff8171045a: __acpi_node_get_property_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __acpi_node_get_property_reference(const struct fwnode_handle *fwnode, const char *propname, size_t index, size_t num_args, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff8183f350)
Location: drivers/acpi/property.c:671
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/acpi/property.c:acpi_fwnode_get_reference_args
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
```
**Symbols:**

```
ffffffff8183f350-ffffffff8183f5b5: __acpi_node_get_property_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __acpi_node_get_property_reference(const struct fwnode_handle *fwnode, const char *propname, size_t index, size_t num_args, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81975b90)
Location: drivers/acpi/property.c:882
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/acpi/property.c:acpi_fwnode_get_reference_args
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
```
**Symbols:**

```
ffffffff81975b90-ffffffff81975e0b: __acpi_node_get_property_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __acpi_node_get_property_reference(const struct fwnode_handle *fwnode, const char *propname, size_t index, size_t num_args, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff819bc400)
Location: drivers/acpi/property.c:882
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/acpi/property.c:acpi_fwnode_get_reference_args
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
```
**Symbols:**

```
ffffffff819bc400-ffffffff819bc6e1: __acpi_node_get_property_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __acpi_node_get_property_reference(const struct fwnode_handle *fwnode, const char *propname, size_t index, size_t num_args, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff81a06d80)
Location: drivers/acpi/property.c:913
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/acpi/property.c:acpi_fwnode_get_reference_args
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
```
**Symbols:**

```
ffffffff81a06d80-ffffffff81a06fe0: __acpi_node_get_property_reference (STB_GLOBAL)
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
int __acpi_node_get_property_reference(const struct fwnode_handle *fwnode, const char *propname, size_t index, size_t num_args, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffff80001077a0c0)
Location: drivers/acpi/property.c:671
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/acpi/property.c:acpi_fwnode_get_reference_args
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
```
**Symbols:**

```
ffff80001077a0c0-ffff80001077a30c: __acpi_node_get_property_reference (STB_GLOBAL)
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
int __acpi_node_get_property_reference(const struct fwnode_handle *fwnode, const char *propname, size_t index, size_t num_args, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815de0a0)
Location: drivers/acpi/property.c:671
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/acpi/property.c:acpi_fwnode_get_reference_args
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
```
**Symbols:**

```
ffffffff815de0a0-ffffffff815de2ba: __acpi_node_get_property_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __acpi_node_get_property_reference(const struct fwnode_handle *fwnode, const char *propname, size_t index, size_t num_args, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815c96e0)
Location: drivers/acpi/property.c:671
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/acpi/property.c:acpi_fwnode_get_reference_args
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
```
**Symbols:**

```
ffffffff815c96e0-ffffffff815c98fa: __acpi_node_get_property_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __acpi_node_get_property_reference(const struct fwnode_handle *fwnode, const char *propname, size_t index, size_t num_args, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815e36f0)
Location: drivers/acpi/property.c:671
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/acpi/property.c:acpi_fwnode_get_reference_args
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
```
**Symbols:**

```
ffffffff815e36f0-ffffffff815e390a: __acpi_node_get_property_reference (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __acpi_node_get_property_reference(const struct fwnode_handle *fwnode, const char *propname, size_t index, size_t num_args, struct fwnode_reference_args *args);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/property.c (ffffffff815fd5b0)
Location: drivers/acpi/property.c:671
Inline: False
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_property_lookup
  - drivers/pwm/core.c:acpi_pwm_get
  - drivers/acpi/property.c:acpi_fwnode_get_reference_args
  - drivers/acpi/property.c:acpi_graph_get_remote_endpoint
```
**Symbols:**

```
ffffffff815fd5b0-ffffffff815fd7ca: __acpi_node_get_property_reference (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct acpi_reference_args *args</code> ➡️ <code>struct fwnode_reference_args *args</code>
</li>
</ul>
</details>
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
