# Function: <code>dmar_acpi_insert_dev_scope</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81faa953)
Location: drivers/iommu/dmar.c:686
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_dev_scope_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff81fd7454)
Location: drivers/iommu/dmar.c:698
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_dev_scope_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff8201507c)
Location: drivers/iommu/dmar.c:697
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_dev_scope_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff820f6cde)
Location: drivers/iommu/dmar.c:701
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_dev_scope_init
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
In drivers/iommu/dmar.c (ffffffff8270045c)
Location: drivers/iommu/dmar.c:701
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_dev_scope_init
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
In drivers/iommu/dmar.c (ffffffff8272a1e8)
Location: drivers/iommu/dmar.c:701
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_dev_scope_init
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
In drivers/iommu/dmar.c (ffffffff828e2aa6)
Location: drivers/iommu/dmar.c:701
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_dev_scope_init
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
In drivers/iommu/dmar.c (ffffffff828fd563)
Location: drivers/iommu/dmar.c:690
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_dev_scope_init
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
In drivers/iommu/dmar.c (ffffffff829065a0)
Location: drivers/iommu/dmar.c:700
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_dev_scope_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dmar_acpi_insert_dev_scope(u8 device_number, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff82d1ca2a)
Location: drivers/iommu/intel/dmar.c:700
Inline: False
```
**Symbols:**

```
ffffffff82d1ca2a-ffffffff82d1cb57: dmar_acpi_insert_dev_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dmar_acpi_insert_dev_scope(u8 device_number, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8300a7a9)
Location: drivers/iommu/intel/dmar.c:722
Inline: False
```
**Symbols:**

```
ffffffff8300a7a9-ffffffff8300a8d6: dmar_acpi_insert_dev_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dmar_acpi_insert_dev_scope(u8 device_number, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff83215409)
Location: drivers/iommu/intel/dmar.c:729
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
```
**Symbols:**

```
ffffffff83215409-ffffffff83215531: dmar_acpi_insert_dev_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dmar_acpi_insert_dev_scope(u8 device_number, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff832fec63)
Location: drivers/iommu/intel/dmar.c:728
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
```
**Symbols:**

```
ffffffff832fec63-ffffffff832fed8a: dmar_acpi_insert_dev_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dmar_acpi_insert_dev_scope(u8 device_number, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff834b78f3)
Location: drivers/iommu/intel/dmar.c:725
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
```
**Symbols:**

```
ffffffff834b78f3-ffffffff834b7a28: dmar_acpi_insert_dev_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dmar_acpi_insert_dev_scope(u8 device_number, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff83ef43d0)
Location: drivers/iommu/intel/dmar.c:725
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
```
**Symbols:**

```
ffffffff83ef43d0-ffffffff83ef4514: dmar_acpi_insert_dev_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dmar_acpi_insert_dev_scope(u8 device_number, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff83719fa0)
Location: drivers/iommu/intel/dmar.c:727
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
```
**Symbols:**

```
ffffffff83719fa0-ffffffff8371a0e4: dmar_acpi_insert_dev_scope (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dmar_acpi_insert_dev_scope(u8 device_number, struct acpi_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/dmar.c (ffffffff8394da80)
Location: drivers/iommu/intel/dmar.c:727
Inline: False
Direct callers:
  - drivers/iommu/intel/dmar.c:dmar_dev_scope_init
```
**Symbols:**

```
ffffffff8394da80-ffffffff8394dbc4: dmar_acpi_insert_dev_scope (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/dmar.c (ffffffff828edd87)
Location: drivers/iommu/dmar.c:700
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_dev_scope_init
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
In drivers/iommu/dmar.c (ffffffff828e5214)
Location: drivers/iommu/dmar.c:700
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_dev_scope_init
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
In drivers/iommu/dmar.c (ffffffff829018c3)
Location: drivers/iommu/dmar.c:700
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_dev_scope_init
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
In drivers/iommu/dmar.c (ffffffff82907602)
Location: drivers/iommu/dmar.c:700
Inline: True
Inline callers:
  - drivers/iommu/dmar.c:dmar_dev_scope_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
