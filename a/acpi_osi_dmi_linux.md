# Function: <code>acpi_osi_dmi_linux</code>

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
void acpi_osi_dmi_linux(bool enable, const struct dmi_system_id *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff81fcce12)
Location: drivers/acpi/osi.c:268
Inline: False
Direct callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
```
**Symbols:**

```
ffffffff81fcce12-ffffffff81fcce5c: acpi_osi_dmi_linux (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_osi_dmi_linux(bool enable, const struct dmi_system_id *d);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/osi.c (ffffffff82009e0c)
Location: drivers/acpi/osi.c:268
Inline: False
Direct callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
```
**Symbols:**

```
ffffffff82009e0c-ffffffff82009e56: acpi_osi_dmi_linux (STB_GLOBAL)
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
In drivers/acpi/osi.c (ffffffff820eb4e2)
Location: drivers/acpi/osi.c:268
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
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
In drivers/acpi/osi.c (ffffffff826f432f)
Location: drivers/acpi/osi.c:268
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
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
In drivers/acpi/osi.c (ffffffff8271e33b)
Location: drivers/acpi/osi.c:285
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
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
In drivers/acpi/osi.c (ffffffff828d6366)
Location: drivers/acpi/osi.c:292
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
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
In drivers/acpi/osi.c (ffffffff828f01c4)
Location: drivers/acpi/osi.c:279
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
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
In drivers/acpi/osi.c (ffffffff828f9335)
Location: drivers/acpi/osi.c:279
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
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
In drivers/acpi/osi.c (ffffffff82d10323)
Location: drivers/acpi/osi.c:279
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
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
In drivers/acpi/osi.c (ffffffff82ffddf3)
Location: drivers/acpi/osi.c:279
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
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
In drivers/acpi/osi.c (ffffffff83208b20)
Location: drivers/acpi/osi.c:279
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
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
In drivers/acpi/osi.c (ffffffff832f0d9c)
Location: drivers/acpi/osi.c:279
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
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
In drivers/acpi/osi.c (ffffffff834a8d60)
Location: drivers/acpi/osi.c:279
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
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
In drivers/acpi/osi.c (ffffffff83ee0555)
Location: drivers/acpi/osi.c:255
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
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
In drivers/acpi/osi.c (ffffffff83705ff5)
Location: drivers/acpi/osi.c:255
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
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
In drivers/acpi/osi.c (ffffffff83939575)
Location: drivers/acpi/osi.c:255
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
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
In drivers/acpi/osi.c (ffff80001147c32c)
Location: drivers/acpi/osi.c:279
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
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
In drivers/acpi/osi.c (ffffffff828e20a1)
Location: drivers/acpi/osi.c:279
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
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
In drivers/acpi/osi.c (ffffffff828da0d1)
Location: drivers/acpi/osi.c:279
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
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
In drivers/acpi/osi.c (ffffffff828f4f31)
Location: drivers/acpi/osi.c:279
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
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
In drivers/acpi/osi.c (ffffffff828fa389)
Location: drivers/acpi/osi.c:279
Inline: True
Inline callers:
  - drivers/acpi/osi.c:dmi_enable_osi_linux
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
</ul>
