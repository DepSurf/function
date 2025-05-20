# Function: <code>acpi_set_pnp_ids</code>

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
In drivers/acpi/scan.c (ffffffff81480622)
Location: drivers/acpi/scan.c:1218
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
In drivers/acpi/scan.c (ffffffff814cefa0)
Location: drivers/acpi/scan.c:1238
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
In drivers/acpi/scan.c (ffffffff814f0f0a)
Location: drivers/acpi/scan.c:1236
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
In drivers/acpi/scan.c (ffffffff814fe601)
Location: drivers/acpi/scan.c:1227
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
In drivers/acpi/scan.c (ffffffff81540658)
Location: drivers/acpi/scan.c:1231
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
In drivers/acpi/scan.c (ffffffff8157656c)
Location: drivers/acpi/scan.c:1232
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
In drivers/acpi/scan.c (ffffffff8158e170)
Location: drivers/acpi/scan.c:1232
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
In drivers/acpi/scan.c (ffffffff815beebc)
Location: drivers/acpi/scan.c:1230
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
In drivers/acpi/scan.c (ffffffff815e017c)
Location: drivers/acpi/scan.c:1230
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
void acpi_set_pnp_ids(acpi_handle handle, struct acpi_device_pnp *pnp, int device_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1239
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
**Symbols:**

```
ffffffff8168b410-ffffffff8168b72b: acpi_set_pnp_ids (STB_LOCAL)
ffffffff8168c61a-ffffffff8168c632: acpi_set_pnp_ids.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void acpi_set_pnp_ids(acpi_handle handle, struct acpi_device_pnp *pnp, int device_type, struct acpi_device_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1308
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
**Symbols:**

```
ffffffff816a9230-ffffffff816a9520: acpi_set_pnp_ids (STB_LOCAL)
ffffffff81c011bd-ffffffff81c011d5: acpi_set_pnp_ids.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void acpi_set_pnp_ids(acpi_handle handle, struct acpi_device_pnp *pnp, int device_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1307
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
**Symbols:**

```
ffffffff8168b900-ffffffff8168bca2: acpi_set_pnp_ids (STB_LOCAL)
ffffffff81bf2b46-ffffffff81bf2b5e: acpi_set_pnp_ids.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void acpi_set_pnp_ids(acpi_handle handle, struct acpi_device_pnp *pnp, int device_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1315
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
**Symbols:**

```
ffffffff81701080-ffffffff81701422: acpi_set_pnp_ids (STB_LOCAL)
ffffffff81cef4d9-ffffffff81cef4f1: acpi_set_pnp_ids.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void acpi_set_pnp_ids(acpi_handle handle, struct acpi_device_pnp *pnp, int device_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/scan.c (0)
Location: drivers/acpi/scan.c:1345
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
**Symbols:**

```
ffffffff8182ecb0-ffffffff8182f076: acpi_set_pnp_ids (STB_LOCAL)
ffffffff81eb6f32-ffffffff81eb6f4a: acpi_set_pnp_ids.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_set_pnp_ids(acpi_handle handle, struct acpi_device_pnp *pnp, int device_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff81961c00)
Location: drivers/acpi/scan.c:1328
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
**Symbols:**

```
ffffffff81961c00-ffffffff81961fe4: acpi_set_pnp_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_set_pnp_ids(acpi_handle handle, struct acpi_device_pnp *pnp, int device_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819a8010)
Location: drivers/acpi/scan.c:1330
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
**Symbols:**

```
ffffffff819a8010-ffffffff819a83ec: acpi_set_pnp_ids (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_set_pnp_ids(acpi_handle handle, struct acpi_device_pnp *pnp, int device_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff819f0a30)
Location: drivers/acpi/scan.c:1333
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
**Symbols:**

```
ffffffff819f0a30-ffffffff819f0e0c: acpi_set_pnp_ids (STB_LOCAL)
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
In drivers/acpi/scan.c (ffff80001076ca88)
Location: drivers/acpi/scan.c:1230
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
In drivers/acpi/scan.c (ffffffff815d258a)
Location: drivers/acpi/scan.c:1230
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
In drivers/acpi/scan.c (ffffffff815bc14a)
Location: drivers/acpi/scan.c:1230
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
In drivers/acpi/scan.c (ffffffff815d445c)
Location: drivers/acpi/scan.c:1230
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
In drivers/acpi/scan.c (ffffffff815ee31c)
Location: drivers/acpi/scan.c:1230
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
