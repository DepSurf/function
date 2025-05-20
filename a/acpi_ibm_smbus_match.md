# Function: <code>acpi_ibm_smbus_match</code>

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
In drivers/acpi/scan.c (ffffffff8148075b)
Location: drivers/acpi/scan.c:1182
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
In drivers/acpi/scan.c (ffffffff814cf0d3)
Location: drivers/acpi/scan.c:1202
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
In drivers/acpi/scan.c (ffffffff814f103d)
Location: drivers/acpi/scan.c:1200
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
In drivers/acpi/scan.c (ffffffff814feaed)
Location: drivers/acpi/scan.c:1191
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
In drivers/acpi/scan.c (ffffffff81540672)
Location: drivers/acpi/scan.c:1195
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
In drivers/acpi/scan.c (ffffffff81576586)
Location: drivers/acpi/scan.c:1196
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
In drivers/acpi/scan.c (ffffffff8158e614)
Location: drivers/acpi/scan.c:1196
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
In drivers/acpi/scan.c (ffffffff815bf36f)
Location: drivers/acpi/scan.c:1194
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
In drivers/acpi/scan.c (ffffffff815e062f)
Location: drivers/acpi/scan.c:1194
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_init_device_object
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool acpi_ibm_smbus_match(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816896d0)
Location: drivers/acpi/scan.c:1203
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_set_pnp_ids
```
**Symbols:**

```
ffffffff816896d0-ffffffff81689794: acpi_ibm_smbus_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool acpi_ibm_smbus_match(acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/scan.c (ffffffff816a7310)
Location: drivers/acpi/scan.c:1272
Inline: False
Direct callers:
  - drivers/acpi/scan.c:acpi_set_pnp_ids
```
**Symbols:**

```
ffffffff816a7310-ffffffff816a73d4: acpi_ibm_smbus_match (STB_LOCAL)
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
In drivers/acpi/scan.c (ffffffff8168bb69)
Location: drivers/acpi/scan.c:1271
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_set_pnp_ids
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
In drivers/acpi/scan.c (ffffffff817012e9)
Location: drivers/acpi/scan.c:1279
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_set_pnp_ids
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
In drivers/acpi/scan.c (ffffffff8182ef25)
Location: drivers/acpi/scan.c:1309
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_set_pnp_ids
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
In drivers/acpi/scan.c (ffffffff81961e7b)
Location: drivers/acpi/scan.c:1292
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_set_pnp_ids
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
In drivers/acpi/scan.c (ffffffff819a8283)
Location: drivers/acpi/scan.c:1294
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_set_pnp_ids
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
In drivers/acpi/scan.c (ffffffff819f0ca3)
Location: drivers/acpi/scan.c:1297
Inline: True
Inline callers:
  - drivers/acpi/scan.c:acpi_set_pnp_ids
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
In drivers/acpi/scan.c (ffff80001076cf24)
Location: drivers/acpi/scan.c:1194
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
In drivers/acpi/scan.c (ffffffff815d2a3d)
Location: drivers/acpi/scan.c:1194
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
In drivers/acpi/scan.c (ffffffff815bc5fd)
Location: drivers/acpi/scan.c:1194
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
In drivers/acpi/scan.c (ffffffff815d490f)
Location: drivers/acpi/scan.c:1194
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
In drivers/acpi/scan.c (ffffffff815ee7cf)
Location: drivers/acpi/scan.c:1194
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
</ul>
