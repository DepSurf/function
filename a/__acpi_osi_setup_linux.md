# Function: <code>__acpi_osi_setup_linux</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff81fcce2f)
Location: drivers/acpi/osi.c:180
Inline: True
Inline callers:
  - drivers/acpi/osi.c:acpi_osi_dmi_linux
  - drivers/acpi/osi.c:acpi_osi_setup_linux
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
In drivers/acpi/osi.c (ffffffff82009e29)
Location: drivers/acpi/osi.c:180
Inline: True
Inline callers:
  - drivers/acpi/osi.c:acpi_osi_dmi_linux
  - drivers/acpi/osi.c:acpi_osi_setup_linux
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
In drivers/acpi/osi.c (ffffffff820eb4f5)
Location: drivers/acpi/osi.c:180
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:acpi_osi_setup_linux
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
In drivers/acpi/osi.c (ffffffff826f4342)
Location: drivers/acpi/osi.c:181
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:acpi_osi_setup_linux
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
In drivers/acpi/osi.c (ffffffff8271e34f)
Location: drivers/acpi/osi.c:198
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:acpi_osi_setup_linux
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
In drivers/acpi/osi.c (ffffffff828d637a)
Location: drivers/acpi/osi.c:205
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:acpi_osi_setup_linux
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
In drivers/acpi/osi.c (ffffffff828f01d8)
Location: drivers/acpi/osi.c:192
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:acpi_osi_setup_linux
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
In drivers/acpi/osi.c (ffffffff828f9349)
Location: drivers/acpi/osi.c:192
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:acpi_osi_setup_linux
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __acpi_osi_setup_linux(bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff82d102de)
Location: drivers/acpi/osi.c:192
Inline: False
Direct callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
```
**Symbols:**

```
ffffffff82d102de-ffffffff82d1031e: __acpi_osi_setup_linux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __acpi_osi_setup_linux(bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff82ffddae)
Location: drivers/acpi/osi.c:192
Inline: False
Direct callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
```
**Symbols:**

```
ffffffff82ffddae-ffffffff82ffddee: __acpi_osi_setup_linux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __acpi_osi_setup_linux(bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff83208adb)
Location: drivers/acpi/osi.c:192
Inline: False
Direct callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
```
**Symbols:**

```
ffffffff83208adb-ffffffff83208b1b: __acpi_osi_setup_linux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __acpi_osi_setup_linux(bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff832f0d57)
Location: drivers/acpi/osi.c:192
Inline: False
Direct callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
```
**Symbols:**

```
ffffffff832f0d57-ffffffff832f0d97: __acpi_osi_setup_linux (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __acpi_osi_setup_linux(bool enable);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff834a8d11)
Location: drivers/acpi/osi.c:192
Inline: False
Direct callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
```
**Symbols:**

```
ffffffff834a8d11-ffffffff834a8d5b: __acpi_osi_setup_linux (STB_LOCAL)
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
In drivers/acpi/osi.c (ffffffff83ee0569)
Location: drivers/acpi/osi.c:168
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
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
In drivers/acpi/osi.c (ffffffff83706009)
Location: drivers/acpi/osi.c:168
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
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
In drivers/acpi/osi.c (ffffffff83939589)
Location: drivers/acpi/osi.c:168
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
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
In drivers/acpi/osi.c (ffff80001147c33c)
Location: drivers/acpi/osi.c:192
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:osi_setup
  - drivers/acpi/osi.c:osi_setup
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
In drivers/acpi/osi.c (ffffffff828e20b5)
Location: drivers/acpi/osi.c:192
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:acpi_osi_setup_linux
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
In drivers/acpi/osi.c (ffffffff828da0e5)
Location: drivers/acpi/osi.c:192
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:acpi_osi_setup_linux
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
In drivers/acpi/osi.c (ffffffff828f4f45)
Location: drivers/acpi/osi.c:192
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:acpi_osi_setup_linux
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
In drivers/acpi/osi.c (ffffffff828fa39d)
Location: drivers/acpi/osi.c:192
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
  - drivers/acpi/osi.c:acpi_osi_setup_linux
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
</ul>
