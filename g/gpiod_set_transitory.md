# Function: <code>gpiod_set_transitory</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int gpiod_set_transitory(struct gpio_desc *desc, bool transitory);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81507190)
Location: drivers/gpio/gpiolib.c:2667
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81507190-ffffffff8150723d: gpiod_set_transitory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int gpiod_set_transitory(struct gpio_desc *desc, bool transitory);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8151b710)
Location: drivers/gpio/gpiolib.c:2747
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff8151b710-ffffffff8151b7bd: gpiod_set_transitory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int gpiod_set_transitory(struct gpio_desc *desc, bool transitory);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff815498d0)
Location: drivers/gpio/gpiolib.c:2835
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff815498d0-ffffffff8154997d: gpiod_set_transitory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int gpiod_set_transitory(struct gpio_desc *desc, bool transitory);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8156aa70)
Location: drivers/gpio/gpiolib.c:3182
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff8156aa70-ffffffff8156ab1d: gpiod_set_transitory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gpiod_set_transitory(struct gpio_desc *desc, bool transitory);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8160faf0)
Location: drivers/gpio/gpiolib.c:3593
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff8160faf0-ffffffff8160fb9d: gpiod_set_transitory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int gpiod_set_transitory(struct gpio_desc *desc, bool transitory);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2436
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81bf646f-ffffffff81bf64d4: gpiod_set_transitory.cold (STB_LOCAL)
ffffffff81636fd0-ffffffff81637040: gpiod_set_transitory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int gpiod_set_transitory(struct gpio_desc *desc, bool transitory);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2413
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81be8315-ffffffff81be837a: gpiod_set_transitory.cold (STB_LOCAL)
ffffffff8161a8f0-ffffffff8161a960: gpiod_set_transitory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gpiod_set_transitory(struct gpio_desc *desc, bool transitory);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib.c (0)
Location: drivers/gpio/gpiolib.c:2442
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81ce1f0c-ffffffff81ce1f71: gpiod_set_transitory.cold (STB_LOCAL)
ffffffff81689d30-ffffffff81689da0: gpiod_set_transitory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int gpiod_set_transitory(struct gpio_desc *desc, bool transitory);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff817a53f0)
Location: drivers/gpio/gpiolib.c:2560
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff817a53f0-ffffffff817a54a4: gpiod_set_transitory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gpiod_set_transitory(struct gpio_desc *desc, bool transitory);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff818bd660)
Location: drivers/gpio/gpiolib.c:2630
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff818bd660-ffffffff818bd713: gpiod_set_transitory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gpiod_set_transitory(struct gpio_desc *desc, bool transitory);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81900790)
Location: drivers/gpio/gpiolib.c:2671
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81900790-ffffffff81900843: gpiod_set_transitory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gpiod_set_transitory(struct gpio_desc *desc, bool transitory);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8194a000)
Location: drivers/gpio/gpiolib.c:2865
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib-cdev.c:linereq_create
  - drivers/gpio/gpiolib-cdev.c:linehandle_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff8194a000-ffffffff8194a0a2: gpiod_set_transitory (STB_GLOBAL)
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
int gpiod_set_transitory(struct gpio_desc *desc, bool transitory);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffff8000106c0f70)
Location: drivers/gpio/gpiolib.c:3182
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffff8000106c0f70-ffff8000106c1080: gpiod_set_transitory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int gpiod_set_transitory(struct gpio_desc *desc, bool transitory);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c085e138)
Location: drivers/gpio/gpiolib.c:3182
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
c085e138-c085e1fc: gpiod_set_transitory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int gpiod_set_transitory(struct gpio_desc *desc, bool transitory);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (c00000000083b070)
Location: drivers/gpio/gpiolib.c:3182
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
c00000000083b070-c00000000083b1ac: gpiod_set_transitory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int gpiod_set_transitory(struct gpio_desc *desc, bool transitory);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffe0004a5276)
Location: drivers/gpio/gpiolib.c:3182
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffe0004a5276-ffffffe0004a5346: gpiod_set_transitory (STB_GLOBAL)
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
int gpiod_set_transitory(struct gpio_desc *desc, bool transitory);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81560230)
Location: drivers/gpio/gpiolib.c:3182
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81560230-ffffffff815602dd: gpiod_set_transitory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int gpiod_set_transitory(struct gpio_desc *desc, bool transitory);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81551080)
Location: drivers/gpio/gpiolib.c:3182
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81551080-ffffffff8155112d: gpiod_set_transitory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int gpiod_set_transitory(struct gpio_desc *desc, bool transitory);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff8155eda0)
Location: drivers/gpio/gpiolib.c:3182
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff8155eda0-ffffffff8155ee4d: gpiod_set_transitory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int gpiod_set_transitory(struct gpio_desc *desc, bool transitory);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib.c (ffffffff81578c30)
Location: drivers/gpio/gpiolib.c:3182
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_configure_flags
  - drivers/gpio/gpiolib.c:linehandle_create
  - drivers/gpio/gpiolib-sysfs.c:export_store
```
**Symbols:**

```
ffffffff81578c30-ffffffff81578cdd: gpiod_set_transitory (STB_GLOBAL)
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
