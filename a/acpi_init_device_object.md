# Function: <code>acpi_init_device_object</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_init_device_object(struct acpi_device *device, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814804fe)
Location: drivers/acpi/scan.c:1386
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff814804fe-ffffffff814809a3: acpi_init_device_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_init_device_object(struct acpi_device *device, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814cee75)
Location: drivers/acpi/scan.c:1406
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff814cee75-ffffffff814cf346: acpi_init_device_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_init_device_object(struct acpi_device *device, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814f0ddf)
Location: drivers/acpi/scan.c:1436
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff814f0ddf-ffffffff814f12b0: acpi_init_device_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_init_device_object(struct acpi_device *device, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff814fe4a0)
Location: drivers/acpi/scan.c:1463
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff814fe4a0-ffffffff814feca1: acpi_init_device_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_init_device_object(struct acpi_device *device, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff815404a0)
Location: drivers/acpi/scan.c:1562
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff815404a0-ffffffff81540cae: acpi_init_device_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void acpi_init_device_object(struct acpi_device *device, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1563
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff81577c77-ffffffff81577ca7: acpi_init_device_object.cold.18 (STB_LOCAL)
ffffffff815763f0-ffffffff81576b6e: acpi_init_device_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void acpi_init_device_object(struct acpi_device *device, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1576
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff8158f8b7-ffffffff8158f8e7: acpi_init_device_object.cold.18 (STB_LOCAL)
ffffffff8158e010-ffffffff8158e757: acpi_init_device_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void acpi_init_device_object(struct acpi_device *device, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1575
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff815c05f3-ffffffff815c0623: acpi_init_device_object.cold (STB_LOCAL)
ffffffff815bed60-ffffffff815bf4b2: acpi_init_device_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void acpi_init_device_object(struct acpi_device *device, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1575
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff815e18b3-ffffffff815e18e3: acpi_init_device_object.cold (STB_LOCAL)
ffffffff815e0020-ffffffff815e0772: acpi_init_device_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_init_device_object(struct acpi_device *device, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8168b9f0)
Location: drivers/acpi/scan.c:1584
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff8168b9f0-ffffffff8168bc0c: acpi_init_device_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_init_device_object(struct acpi_device *device, acpi_handle handle, int type, long long unsigned int sta, struct acpi_device_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816a97f0)
Location: drivers/acpi/scan.c:1650
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff816a97f0-ffffffff816a9a61: acpi_init_device_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_init_device_object(struct acpi_device *device, acpi_handle handle, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8168bf80)
Location: drivers/acpi/scan.c:1653
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff8168bf80-ffffffff8168c2a5: acpi_init_device_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void acpi_init_device_object(struct acpi_device *device, acpi_handle handle, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1739
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff81cef50a-ffffffff81cef53a: acpi_init_device_object.cold (STB_LOCAL)
ffffffff81701740-ffffffff81701a7c: acpi_init_device_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void acpi_init_device_object(struct acpi_device *device, acpi_handle handle, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1778
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff81eb6f5e-ffffffff81eb6f8e: acpi_init_device_object.cold (STB_LOCAL)
ffffffff8182f3c0-ffffffff8182f70b: acpi_init_device_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void acpi_init_device_object(struct acpi_device *device, acpi_handle handle, int type, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1758
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff8209193b-ffffffff8209196b: acpi_init_device_object.cold (STB_LOCAL)
ffffffff819623e0-ffffffff81962775: acpi_init_device_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void acpi_init_device_object(struct acpi_device *device, acpi_handle handle, int type, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1761
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff82112246-ffffffff82112276: acpi_init_device_object.cold (STB_LOCAL)
ffffffff819a87e0-ffffffff819a8b75: acpi_init_device_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void acpi_init_device_object(struct acpi_device *device, acpi_handle handle, int type, void (*release)(struct device *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1773
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff821eff5e-ffffffff821eff8e: acpi_init_device_object.cold (STB_LOCAL)
ffffffff819f11f0-ffffffff819f1585: acpi_init_device_object (STB_GLOBAL)
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
void acpi_init_device_object(struct acpi_device *device, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffff80001076c938)
Location: drivers/acpi/scan.c:1575
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffff80001076c938-ffff80001076d088: acpi_init_device_object (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void acpi_init_device_object(struct acpi_device *device, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1575
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff815d3b83-ffffffff815d3bb3: acpi_init_device_object.cold (STB_LOCAL)
ffffffff815d2430-ffffffff815d2b80: acpi_init_device_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void acpi_init_device_object(struct acpi_device *device, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1575
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff815bd743-ffffffff815bd773: acpi_init_device_object.cold (STB_LOCAL)
ffffffff815bbff0-ffffffff815bc740: acpi_init_device_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void acpi_init_device_object(struct acpi_device *device, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1575
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff815d5b93-ffffffff815d5bc3: acpi_init_device_object.cold (STB_LOCAL)
ffffffff815d4300-ffffffff815d4a52: acpi_init_device_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void acpi_init_device_object(struct acpi_device *device, acpi_handle handle, int type, long long unsigned int sta);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1575
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_add_single_object
  - drivers/acpi/power.c:acpi_add_power_resource
```
**Symbols:**

```
ffffffff815efa53-ffffffff815efa83: acpi_init_device_object.cold (STB_LOCAL)
ffffffff815ee1c0-ffffffff815ee912: acpi_init_device_object (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct acpi_device_info *info</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long long unsigned int sta</code>
</li>
<li>
<b>Param removed. </b>
<code>struct acpi_device_info *info</code>
</li>
</ul>
</details>
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
<b>Param added. </b>
<code>void (*release)(struct device *)</code>
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
