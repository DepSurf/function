# Function: <code>acpi_can_fallback_to_crs</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool acpi_can_fallback_to_crs(struct acpi_device *adev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81474e10)
Location: drivers/gpio/gpiolib-acpi.c:960
Inline: False
Direct callers:
  - drivers/gpio/gpiolib.c:gpiod_get_index
```
**Symbols:**

```
ffffffff81474e10-ffffffff81474f0c: acpi_can_fallback_to_crs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool acpi_can_fallback_to_crs(struct acpi_device *adev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81496c89)
Location: drivers/gpio/gpiolib-acpi.c:1099
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
Direct callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff81496490-ffffffff81496581: acpi_can_fallback_to_crs.part.8 (STB_LOCAL)
ffffffff814974b0-ffffffff814974d8: acpi_can_fallback_to_crs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool acpi_can_fallback_to_crs(struct acpi_device *adev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff814a10ae)
Location: drivers/gpio/gpiolib-acpi.c:1205
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff814a1170-ffffffff814a1199: acpi_can_fallback_to_crs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool acpi_can_fallback_to_crs(struct acpi_device *adev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff814dfa73)
Location: drivers/gpio/gpiolib-acpi.c:1134
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff814dfb30-ffffffff814dfb59: acpi_can_fallback_to_crs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool acpi_can_fallback_to_crs(struct acpi_device *adev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8150ee42)
Location: drivers/gpio/gpiolib-acpi.c:1189
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff8150eef0-ffffffff8150ef19: acpi_can_fallback_to_crs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool acpi_can_fallback_to_crs(struct acpi_device *adev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff815244a8)
Location: drivers/gpio/gpiolib-acpi.c:1212
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff81524550-ffffffff81524582: acpi_can_fallback_to_crs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool acpi_can_fallback_to_crs(struct acpi_device *adev, const char *con_id);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff815529f8)
Location: drivers/gpio/gpiolib-acpi.c:1268
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
**Symbols:**

```
ffffffff81552aa0-ffffffff81552ad2: acpi_can_fallback_to_crs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81574038)
Location: drivers/gpio/gpiolib-acpi.c:802
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81618528)
Location: drivers/gpio/gpiolib-acpi.c:809
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8163ef28)
Location: drivers/gpio/gpiolib-acpi.c:843
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81622a88)
Location: drivers/gpio/gpiolib-acpi.c:843
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81692204)
Location: drivers/gpio/gpiolib-acpi.c:897
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff817b180b)
Location: drivers/gpio/gpiolib-acpi.c:882
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff818cb27b)
Location: drivers/gpio/gpiolib-acpi.c:962
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8190e2ee)
Location: drivers/gpio/gpiolib-acpi.c:964
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8195607e)
Location: drivers/gpio/gpiolib-acpi.c:941
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffff8000106cc0e8)
Location: drivers/gpio/gpiolib-acpi.c:802
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff815697f8)
Location: drivers/gpio/gpiolib-acpi.c:802
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8155a648)
Location: drivers/gpio/gpiolib-acpi.c:802
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81568368)
Location: drivers/gpio/gpiolib-acpi.c:802
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81582288)
Location: drivers/gpio/gpiolib-acpi.c:802
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:acpi_gpio_count
  - drivers/gpio/gpiolib-acpi.c:acpi_find_gpio
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
