# Function: <code>acpi_dev_remove_driver_gpios</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8149f834)
Location: include/linux/acpi.h:961
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff814de1dd)
Location: include/linux/acpi.h:987
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8150d3fd)
Location: include/linux/acpi.h:1020
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81522a2d)
Location: include/linux/acpi.h:1025
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81550f4d)
Location: include/linux/acpi.h:1025
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_remove_driver_gpios(struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8157240d)
Location: drivers/gpio/gpiolib-acpi.c:457
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
```
**Symbols:**

```
ffffffff815723b0-ffffffff815723cb: acpi_dev_remove_driver_gpios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_remove_driver_gpios(struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8161696d)
Location: drivers/gpio/gpiolib-acpi.c:464
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
```
**Symbols:**

```
ffffffff81616910-ffffffff8161692b: acpi_dev_remove_driver_gpios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_remove_driver_gpios(struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8163d29d)
Location: drivers/gpio/gpiolib-acpi.c:525
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
```
**Symbols:**

```
ffffffff8163d240-ffffffff8163d25b: acpi_dev_remove_driver_gpios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_remove_driver_gpios(struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81620dfd)
Location: drivers/gpio/gpiolib-acpi.c:525
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
```
**Symbols:**

```
ffffffff81620da0-ffffffff81620dbb: acpi_dev_remove_driver_gpios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_remove_driver_gpios(struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8169043d)
Location: drivers/gpio/gpiolib-acpi.c:579
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
```
**Symbols:**

```
ffffffff81690390-ffffffff816903ab: acpi_dev_remove_driver_gpios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_remove_driver_gpios(struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff817b05f7)
Location: drivers/gpio/gpiolib-acpi.c:576
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
```
**Symbols:**

```
ffffffff817af770-ffffffff817af791: acpi_dev_remove_driver_gpios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_remove_driver_gpios(struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff818ca117)
Location: drivers/gpio/gpiolib-acpi.c:613
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
```
**Symbols:**

```
ffffffff818c8e60-ffffffff818c8e81: acpi_dev_remove_driver_gpios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_remove_driver_gpios(struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8190d1ae)
Location: drivers/gpio/gpiolib-acpi.c:618
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
```
**Symbols:**

```
ffffffff8190bf10-ffffffff8190bf31: acpi_dev_remove_driver_gpios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_remove_driver_gpios(struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81954eae)
Location: drivers/gpio/gpiolib-acpi.c:594
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_add_driver_gpios
```
**Symbols:**

```
ffffffff81953c30-ffffffff81953c51: acpi_dev_remove_driver_gpios (STB_GLOBAL)
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
void acpi_dev_remove_driver_gpios(struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffff8000106ca0cc)
Location: drivers/gpio/gpiolib-acpi.c:457
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
```
**Symbols:**

```
ffff8000106ca028-ffff8000106ca054: acpi_dev_remove_driver_gpios (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_remove_driver_gpios(struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81567bcd)
Location: drivers/gpio/gpiolib-acpi.c:457
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
```
**Symbols:**

```
ffffffff81567b70-ffffffff81567b8b: acpi_dev_remove_driver_gpios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_remove_driver_gpios(struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff81558a1d)
Location: drivers/gpio/gpiolib-acpi.c:457
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
```
**Symbols:**

```
ffffffff815589c0-ffffffff815589db: acpi_dev_remove_driver_gpios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_remove_driver_gpios(struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8156673d)
Location: drivers/gpio/gpiolib-acpi.c:457
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
```
**Symbols:**

```
ffffffff815666e0-ffffffff815666fb: acpi_dev_remove_driver_gpios (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void acpi_dev_remove_driver_gpios(struct acpi_device *adev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/gpio/gpiolib-acpi.c (ffffffff8158065d)
Location: drivers/gpio/gpiolib-acpi.c:457
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-acpi.c:devm_acpi_dev_release_driver_gpios
```
**Symbols:**

```
ffffffff81580600-ffffffff8158061b: acpi_dev_remove_driver_gpios (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
