# Function: <code>acpi_device_add_finalize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_device_add_finalize(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814809a3)
Location: drivers/acpi/scan.c:1407
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff814809a3-ffffffff814809c3: acpi_device_add_finalize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_device_add_finalize(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814cf346)
Location: drivers/acpi/scan.c:1427
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff814cf346-ffffffff814cf366: acpi_device_add_finalize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_device_add_finalize(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814f12b0)
Location: drivers/acpi/scan.c:1457
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff814f12b0-ffffffff814f12d0: acpi_device_add_finalize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_device_add_finalize(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814fef0c)
Location: drivers/acpi/scan.c:1486
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
Direct callers:
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff814ffab0-ffffffff814ffad0: acpi_device_add_finalize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_device_add_finalize(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81540f0b)
Location: drivers/acpi/scan.c:1585
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
Direct callers:
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff81541c60-ffffffff81541c80: acpi_device_add_finalize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void acpi_device_add_finalize(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81576dd4)
Location: drivers/acpi/scan.c:1588
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
Direct callers:
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff81577b30-ffffffff81577b50: acpi_device_add_finalize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void acpi_device_add_finalize(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8158e9c7)
Location: drivers/acpi/scan.c:1601
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
Direct callers:
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff8158f770-ffffffff8158f790: acpi_device_add_finalize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void acpi_device_add_finalize(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815bf731)
Location: drivers/acpi/scan.c:1600
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
Direct callers:
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff815c03e0-ffffffff815c0400: acpi_device_add_finalize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void acpi_device_add_finalize(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815e09f1)
Location: drivers/acpi/scan.c:1600
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
Direct callers:
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff815e16a0-ffffffff815e16c0: acpi_device_add_finalize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_device_add_finalize(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8168bccb)
Location: drivers/acpi/scan.c:1609
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
Direct callers:
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff8168c390-ffffffff8168c3b0: acpi_device_add_finalize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void acpi_device_add_finalize(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816a9b4e)
Location: drivers/acpi/scan.c:1676
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
Direct callers:
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff816aa410-ffffffff816aa430: acpi_device_add_finalize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_device_add_finalize(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8168c374)
Location: drivers/acpi/scan.c:1690
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
Direct callers:
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff8168cc90-ffffffff8168ccb0: acpi_device_add_finalize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_device_add_finalize(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81701be8)
Location: drivers/acpi/scan.c:1772
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
Direct callers:
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff817024c0-ffffffff817024e0: acpi_device_add_finalize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void acpi_device_add_finalize(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8182f86c)
Location: drivers/acpi/scan.c:1815
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
Direct callers:
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff81830210-ffffffff8183023a: acpi_device_add_finalize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void acpi_device_add_finalize(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819628f3)
Location: drivers/acpi/scan.c:1799
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
Direct callers:
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff81963590-ffffffff819635ba: acpi_device_add_finalize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void acpi_device_add_finalize(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819a8d08)
Location: drivers/acpi/scan.c:1802
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
Direct callers:
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff819a9a40-ffffffff819a9a6a: acpi_device_add_finalize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_device_add_finalize(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819f1747)
Location: drivers/acpi/scan.c:1814
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
Direct callers:
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff819f24e0-ffffffff819f250a: acpi_device_add_finalize (STB_GLOBAL)
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
void acpi_device_add_finalize(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffff80001076d308)
Location: drivers/acpi/scan.c:1600
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
Direct callers:
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffff80001076dfb8-ffff80001076dff4: acpi_device_add_finalize (STB_GLOBAL)
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
void acpi_device_add_finalize(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815d2df1)
Location: drivers/acpi/scan.c:1600
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
Direct callers:
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff815d3970-ffffffff815d3990: acpi_device_add_finalize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void acpi_device_add_finalize(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815bc9b1)
Location: drivers/acpi/scan.c:1600
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
Direct callers:
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff815bd530-ffffffff815bd550: acpi_device_add_finalize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void acpi_device_add_finalize(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815d4cd1)
Location: drivers/acpi/scan.c:1600
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
Direct callers:
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff815d5980-ffffffff815d59a0: acpi_device_add_finalize (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void acpi_device_add_finalize(struct acpi_device *device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815eeb91)
Location: drivers/acpi/scan.c:1600
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_add_single_object
Direct callers:
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff815ef840-ffffffff815ef860: acpi_device_add_finalize (STB_GLOBAL)
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
