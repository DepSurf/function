# Function: <code>acpi_set_modalias</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_set_modalias(struct acpi_device *adev, const char *default_id, char *modalias, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff814fbe00)
Location: drivers/acpi/bus.c:700
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff814fbe00-ffffffff814fbe6e: acpi_set_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_set_modalias(struct acpi_device *adev, const char *default_id, char *modalias, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8153db70)
Location: drivers/acpi/bus.c:727
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff8153db70-ffffffff8153dbde: acpi_set_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void acpi_set_modalias(struct acpi_device *adev, const char *default_id, char *modalias, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81573a60)
Location: drivers/acpi/bus.c:739
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff81573a60-ffffffff81573acc: acpi_set_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void acpi_set_modalias(struct acpi_device *adev, const char *default_id, char *modalias, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8158b680)
Location: drivers/acpi/bus.c:708
Inline: True
Direct callers:
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff8158b680-ffffffff8158b6ec: acpi_set_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void acpi_set_modalias(struct acpi_device *adev, const char *default_id, char *modalias, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815bc4c0)
Location: drivers/acpi/bus.c:695
Inline: True
Direct callers:
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff815bc4c0-ffffffff815bc530: acpi_set_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void acpi_set_modalias(struct acpi_device *adev, const char *default_id, char *modalias, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815dd780)
Location: drivers/acpi/bus.c:695
Inline: True
Direct callers:
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff815dd780-ffffffff815dd7f0: acpi_set_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_set_modalias(struct acpi_device *adev, const char *default_id, char *modalias, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81687fb0)
Location: drivers/acpi/bus.c:695
Inline: True
Direct callers:
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff81687fb0-ffffffff81688020: acpi_set_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void acpi_set_modalias(struct acpi_device *adev, const char *default_id, char *modalias, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff816a5d20)
Location: drivers/acpi/bus.c:700
Inline: True
Direct callers:
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff816a5d20-ffffffff816a5d8e: acpi_set_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_set_modalias(struct acpi_device *adev, const char *default_id, char *modalias, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff81688a20)
Location: drivers/acpi/bus.c:779
Inline: True
Direct callers:
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff81688a20-ffffffff81688a8e: acpi_set_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_set_modalias(struct acpi_device *adev, const char *default_id, char *modalias, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff816fde60)
Location: drivers/acpi/bus.c:781
Inline: True
Direct callers:
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff816fde60-ffffffff816fdece: acpi_set_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_set_modalias(struct acpi_device *adev, const char *default_id, char *modalias, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8182b7f0)
Location: drivers/acpi/bus.c:818
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff8182b7f0-ffffffff8182b877: acpi_set_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_set_modalias(struct acpi_device *adev, const char *default_id, char *modalias, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff8195e1b0)
Location: drivers/acpi/bus.c:824
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff8195e1b0-ffffffff8195e200: acpi_set_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_set_modalias(struct acpi_device *adev, const char *default_id, char *modalias, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff819a43e0)
Location: drivers/acpi/bus.c:780
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff819a43e0-ffffffff819a4430: acpi_set_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_set_modalias(struct acpi_device *adev, const char *default_id, char *modalias, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff819ecb10)
Location: drivers/acpi/bus.c:830
Inline: False
Direct callers:
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff819ecb10-ffffffff819ecb60: acpi_set_modalias (STB_GLOBAL)
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
void acpi_set_modalias(struct acpi_device *adev, const char *default_id, char *modalias, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffff800010769a58)
Location: drivers/acpi/bus.c:695
Inline: True
Direct callers:
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffff800010769a58-ffff800010769af0: acpi_set_modalias (STB_GLOBAL)
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
void acpi_set_modalias(struct acpi_device *adev, const char *default_id, char *modalias, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815cfc60)
Location: drivers/acpi/bus.c:695
Inline: True
Direct callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff815cfc60-ffffffff815cfcd0: acpi_set_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void acpi_set_modalias(struct acpi_device *adev, const char *default_id, char *modalias, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815b9820)
Location: drivers/acpi/bus.c:695
Inline: True
Direct callers:
  - drivers/spi/spi.c:acpi_register_spi_device
```
**Symbols:**

```
ffffffff815b9820-ffffffff815b9890: acpi_set_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void acpi_set_modalias(struct acpi_device *adev, const char *default_id, char *modalias, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815d1a60)
Location: drivers/acpi/bus.c:695
Inline: True
Direct callers:
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff815d1a60-ffffffff815d1ad0: acpi_set_modalias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void acpi_set_modalias(struct acpi_device *adev, const char *default_id, char *modalias, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/bus.c (ffffffff815eb920)
Location: drivers/acpi/bus.c:695
Inline: True
Direct callers:
  - drivers/spi/spi.c:acpi_register_spi_device
  - drivers/i2c/i2c-core-acpi.c:i2c_acpi_get_info
```
**Symbols:**

```
ffffffff815eb920-ffffffff815eb990: acpi_set_modalias (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
