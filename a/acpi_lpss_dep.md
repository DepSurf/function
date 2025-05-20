# Function: <code>acpi_lpss_dep</code>

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
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool acpi_lpss_dep(struct acpi_device *adev, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81580640)
Location: drivers/acpi/acpi_lpss.c:503
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
**Symbols:**

```
ffffffff81580640-ffffffff81580670: acpi_lpss_dep.part.10 (STB_LOCAL)
ffffffff81580670-ffffffff81580723: acpi_lpss_dep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool acpi_lpss_dep(struct acpi_device *adev, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815985a0)
Location: drivers/acpi/acpi_lpss.c:541
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
**Symbols:**

```
ffffffff815985a0-ffffffff815985d0: acpi_lpss_dep.part.10 (STB_LOCAL)
ffffffff815985d0-ffffffff81598689: acpi_lpss_dep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool acpi_lpss_dep(struct acpi_device *adev, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815c97b0)
Location: drivers/acpi/acpi_lpss.c:538
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
**Symbols:**

```
ffffffff815c97b0-ffffffff815c97df: acpi_lpss_dep.part.0 (STB_LOCAL)
ffffffff815c97e0-ffffffff815c988f: acpi_lpss_dep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool acpi_lpss_dep(struct acpi_device *adev, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815ea9d0)
Location: drivers/acpi/acpi_lpss.c:561
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
**Symbols:**

```
ffffffff815ea9d0-ffffffff815ea9ff: acpi_lpss_dep.part.0 (STB_LOCAL)
ffffffff815eaa00-ffffffff815eaaaf: acpi_lpss_dep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81696c30)
Location: drivers/acpi/acpi_lpss.c:539
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer
```
**Symbols:**

```
ffffffff81695e50-ffffffff81695f00: acpi_lpss_dep.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff816b3ba0)
Location: drivers/acpi/acpi_lpss.c:546
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_supplier
  - drivers/acpi/acpi_lpss.c:acpi_lpss_link_consumer
```
**Symbols:**

```
ffffffff816b2fa0-ffffffff816b3050: acpi_lpss_dep.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81695ef9)
Location: drivers/acpi/acpi_lpss.c:547
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
```
**Symbols:**

```
ffffffff81695220-ffffffff816952d0: acpi_lpss_dep.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff8170bc83)
Location: drivers/acpi/acpi_lpss.c:548
Inline: True
Inline callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
```
**Symbols:**

```
ffffffff8170af10-ffffffff8170afd7: acpi_lpss_dep.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool acpi_lpss_dep(struct acpi_device *adev, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff81839050)
Location: drivers/acpi/acpi_lpss.c:570
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
```
**Symbols:**

```
ffffffff81839050-ffffffff81839154: acpi_lpss_dep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool acpi_lpss_dep(struct acpi_device *adev, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff8196e510)
Location: drivers/acpi/acpi_lpss.c:562
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
```
**Symbols:**

```
ffffffff8196e510-ffffffff8196e614: acpi_lpss_dep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool acpi_lpss_dep(struct acpi_device *adev, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff819b4a50)
Location: drivers/acpi/acpi_lpss.c:577
Inline: False
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device_links
```
**Symbols:**

```
ffffffff819b4a50-ffffffff819b4b54: acpi_lpss_dep (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool acpi_lpss_dep(struct acpi_device *adev, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815c5440)
Location: drivers/acpi/acpi_lpss.c:561
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
**Symbols:**

```
ffffffff815c5440-ffffffff815c546f: acpi_lpss_dep.part.0 (STB_LOCAL)
ffffffff815c5470-ffffffff815c551f: acpi_lpss_dep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool acpi_lpss_dep(struct acpi_device *adev, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815decb0)
Location: drivers/acpi/acpi_lpss.c:561
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
**Symbols:**

```
ffffffff815decb0-ffffffff815decdf: acpi_lpss_dep.part.0 (STB_LOCAL)
ffffffff815dece0-ffffffff815ded8f: acpi_lpss_dep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool acpi_lpss_dep(struct acpi_device *adev, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpi_lpss.c (ffffffff815f8b70)
Location: drivers/acpi/acpi_lpss.c:561
Inline: True
Direct callers:
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
  - drivers/acpi/acpi_lpss.c:acpi_lpss_create_device
```
**Symbols:**

```
ffffffff815f8b70-ffffffff815f8b9f: acpi_lpss_dep.part.0 (STB_LOCAL)
ffffffff815f8ba0-ffffffff815f8c4f: acpi_lpss_dep (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
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
