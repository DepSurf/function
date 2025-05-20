# Function: <code>gpiod_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81426c00)
Location: drivers/gpio/gpiolib.c:942
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81426c00-ffffffff81426cef: gpiod_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81470f50)
Location: drivers/gpio/gpiolib.c:1899
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81470f50-ffffffff814710ac: gpiod_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814930c0)
Location: drivers/gpio/gpiolib.c:2086
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff814930c0-ffffffff8149321c: gpiod_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8149ca70)
Location: drivers/gpio/gpiolib.c:2087
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff8149ca70-ffffffff8149cbc8: gpiod_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff814db070)
Location: drivers/gpio/gpiolib.c:2224
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff814db070-ffffffff814db1c8: gpiod_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81509340)
Location: drivers/gpio/gpiolib.c:2338
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81509340-ffffffff8150941a: gpiod_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151dcd0)
Location: drivers/gpio/gpiolib.c:2366
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff8151dcd0-ffffffff8151ddaa: gpiod_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8154be00)
Location: drivers/gpio/gpiolib.c:2430
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff8154be00-ffffffff8154beda: gpiod_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156cf70)
Location: drivers/gpio/gpiolib.c:2762
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff8156cf70-ffffffff8156d04a: gpiod_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8161375a)
Location: drivers/gpio/gpiolib.c:3129
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:lineevent_create
  - drivers/gpio/gpiolib.c:linehandle_create
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:lineevent_create
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81610580-ffffffff81610653: gpiod_request.part.0 (STB_LOCAL)
ffffffff81614c4e-ffffffff81614cad: gpiod_request.cold (STB_LOCAL)
ffffffff81612010-ffffffff81612063: gpiod_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8163863a)
Location: drivers/gpio/gpiolib.c:1933
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81636800-ffffffff816368d0: gpiod_request.part.0 (STB_LOCAL)
ffffffff81bf64d4-ffffffff81bf6533: gpiod_request.cold (STB_LOCAL)
ffffffff81637040-ffffffff81637093: gpiod_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8161c16f)
Location: drivers/gpio/gpiolib.c:1910
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81619e50-ffffffff81619f20: gpiod_request.part.0 (STB_LOCAL)
ffffffff81be837a-ffffffff81be83d9: gpiod_request.cold (STB_LOCAL)
ffffffff8161a960-ffffffff8161a9b3: gpiod_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8168b68f)
Location: drivers/gpio/gpiolib.c:1932
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-acpi.c:acpi_get_and_request_gpiod
```
**Symbols:**

```
ffffffff81689130-ffffffff816891fd: gpiod_request.part.0 (STB_LOCAL)
ffffffff81ce1f71-ffffffff81ce1fd0: gpiod_request.cold (STB_LOCAL)
ffffffff81689da0-ffffffff81689df3: gpiod_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a8a26)
Location: drivers/gpio/gpiolib.c:1993
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-acpi.c:acpi_get_and_request_gpiod
```
**Symbols:**

```
ffffffff817a6550-ffffffff817a6657: gpiod_request.part.0 (STB_LOCAL)
ffffffff81ea896c-ffffffff81ea89c9: gpiod_request.cold (STB_LOCAL)
ffffffff817a6e20-ffffffff817a6e7c: gpiod_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818bf1b0)
Location: drivers/gpio/gpiolib.c:2063
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-acpi.c:acpi_get_and_request_gpiod
```
**Symbols:**

```
ffffffff818bf1b0-ffffffff818bf342: gpiod_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff819022d0)
Location: drivers/gpio/gpiolib.c:2102
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
  - drivers/gpio/gpiolib-acpi.c:acpi_get_and_request_gpiod
```
**Symbols:**

```
ffffffff819022d0-ffffffff819023cd: gpiod_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81949e10)
Location: drivers/gpio/gpiolib.c:2285
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_find_and_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-cdev.c:lineevent_create
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81949e10-ffffffff81949f07: gpiod_request (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c2678)
Location: drivers/gpio/gpiolib.c:2762
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffff8000106c2678-ffff8000106c2788: gpiod_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c0860cb8)
Location: drivers/gpio/gpiolib.c:2762
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
c0860cb8-c0860da0: gpiod_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083ebc0)
Location: drivers/gpio/gpiolib.c:2762
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
c00000000083ebc0-c00000000083ed10: gpiod_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a77d8)
Location: drivers/gpio/gpiolib.c:2762
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-of.c:gpiod_get_from_of_node
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffe0004a77d8-ffffffe0004a78c0: gpiod_request (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81562730)
Location: drivers/gpio/gpiolib.c:2762
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81562730-ffffffff8156280a: gpiod_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81553580)
Location: drivers/gpio/gpiolib.c:2762
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81553580-ffffffff8155365a: gpiod_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815612a0)
Location: drivers/gpio/gpiolib.c:2762
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff815612a0-ffffffff8156137a: gpiod_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int gpiod_request(struct gpio_desc *desc, const char *label);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8157b190)
Location: drivers/gpio/gpiolib.c:2762
Inline: True
Direct callers:
  - drivers/gpio/gpiolib.c:fwnode_get_named_gpiod
  - drivers/gpio/gpiolib.c:gpiod_get_index
  - drivers/gpio/gpiolib.c:gpio_ioctl
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-legacy.c:gpio_request
  - drivers/gpio/gpiolib-legacy.c:gpio_request_one
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff8157b190-ffffffff8157b26a: gpiod_request (STB_GLOBAL)
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
