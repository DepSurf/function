# Function: <code>gpiod_find_and_request</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct gpio_desc *gpiod_find_and_request(struct device *consumer, struct fwnode_handle *fwnode, const char *con_id, unsigned int idx, enum gpiod_flags flags, const char *label, bool platform_lookup_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818c0890)
Location: drivers/gpio/gpiolib.c:3900
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
  - drivers/gpio/gpiolib.c:fwnode_gpiod_get_index
```
**Symbols:**

```
ffffffff818c0890-ffffffff818c0cc1: gpiod_find_and_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct gpio_desc *gpiod_find_and_request(struct device *consumer, struct fwnode_handle *fwnode, const char *con_id, unsigned int idx, enum gpiod_flags flags, const char *label, bool platform_lookup_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81903870)
Location: drivers/gpio/gpiolib.c:3941
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
  - drivers/gpio/gpiolib.c:fwnode_gpiod_get_index
```
**Symbols:**

```
ffffffff81903870-ffffffff81903c9d: gpiod_find_and_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct gpio_desc *gpiod_find_and_request(struct device *consumer, struct fwnode_handle *fwnode, const char *con_id, unsigned int idx, enum gpiod_flags flags, const char *label, bool platform_lookup_allowed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8194b460)
Location: drivers/gpio/gpiolib.c:4141
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_array
  - drivers/gpio/gpiolib.c:gpiod_get_optional
  - drivers/gpio/gpiolib.c:gpiod_get
  - drivers/gpio/gpiolib.c:fwnode_gpiod_get_index
```
**Symbols:**

```
ffffffff8194b460-ffffffff8194b6d7: gpiod_find_and_request (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
