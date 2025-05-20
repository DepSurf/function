# Function: <code>acpi_device_get_busid</code>

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
In drivers/acpi/scan.c (ffffffff81480597)
Location: drivers/acpi/scan.c:990
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/scan.c (ffffffff814cef15)
Location: drivers/acpi/scan.c:1010
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/scan.c (ffffffff814f0e7f)
Location: drivers/acpi/scan.c:1011
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/scan.c (ffffffff814fe540)
Location: drivers/acpi/scan.c:1002
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/scan.c (ffffffff81540562)
Location: drivers/acpi/scan.c:1003
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/scan.c (ffffffff815764c9)
Location: drivers/acpi/scan.c:1004
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/scan.c (ffffffff8158e0d4)
Location: drivers/acpi/scan.c:1004
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/scan.c (ffffffff815bee1d)
Location: drivers/acpi/scan.c:1002
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/scan.c (ffffffff815e00dd)
Location: drivers/acpi/scan.c:1002
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void acpi_device_get_busid(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1011
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
**Symbols:**

```
ffffffff816895b0-ffffffff816896cc: acpi_device_get_busid (STB_LOCAL)
ffffffff8168c49c-ffffffff8168c4b4: acpi_device_get_busid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void acpi_device_get_busid(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1080
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
**Symbols:**

```
ffffffff816a71e0-ffffffff816a730f: acpi_device_get_busid (STB_LOCAL)
ffffffff81c0106d-ffffffff81c01085: acpi_device_get_busid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void acpi_device_get_busid(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1080
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
**Symbols:**

```
ffffffff81689e60-ffffffff81689f8f: acpi_device_get_busid (STB_LOCAL)
ffffffff81bf2a11-ffffffff81bf2a29: acpi_device_get_busid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void acpi_device_get_busid(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1088
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
**Symbols:**

```
ffffffff816ff340-ffffffff816ff46f: acpi_device_get_busid (STB_LOCAL)
ffffffff81cef39d-ffffffff81cef3b5: acpi_device_get_busid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void acpi_device_get_busid(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1118
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
**Symbols:**

```
ffffffff8182cd00-ffffffff8182ce3d: acpi_device_get_busid (STB_LOCAL)
ffffffff81eb6e04-ffffffff81eb6e1c: acpi_device_get_busid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_device_get_busid(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff8195f9e0)
Location: drivers/acpi/scan.c:1101
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
**Symbols:**

```
ffffffff8195f9e0-ffffffff8195fb37: acpi_device_get_busid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_device_get_busid(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819a5de0)
Location: drivers/acpi/scan.c:1103
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
**Symbols:**

```
ffffffff819a5de0-ffffffff819a5f2e: acpi_device_get_busid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_device_get_busid(struct acpi_device *device);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819ee790)
Location: drivers/acpi/scan.c:1106
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
**Symbols:**

```
ffffffff819ee790-ffffffff819ee8de: acpi_device_get_busid (STB_LOCAL)
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
In drivers/acpi/scan.c (ffff80001076c9fc)
Location: drivers/acpi/scan.c:1002
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/scan.c (ffffffff815d24eb)
Location: drivers/acpi/scan.c:1002
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/scan.c (ffffffff815bc0ab)
Location: drivers/acpi/scan.c:1002
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/scan.c (ffffffff815d43bd)
Location: drivers/acpi/scan.c:1002
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
In drivers/acpi/scan.c (ffffffff815ee27d)
Location: drivers/acpi/scan.c:1002
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
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
