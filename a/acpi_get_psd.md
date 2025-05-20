# Function: <code>acpi_get_psd</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff8152598e)
Location: drivers/acpi/cppc_acpi.c:353
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
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
In drivers/acpi/cppc_acpi.c (ffffffff81538539)
Location: drivers/acpi/cppc_acpi.c:358
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
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
In drivers/acpi/cppc_acpi.c (ffffffff81599d6a)
Location: drivers/acpi/cppc_acpi.c:365
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
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
In drivers/acpi/cppc_acpi.c (ffffffff815d16f3)
Location: drivers/acpi/cppc_acpi.c:362
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
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
In drivers/acpi/cppc_acpi.c (ffffffff815ead13)
Location: drivers/acpi/cppc_acpi.c:362
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
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
In drivers/acpi/cppc_acpi.c (ffffffff8161caa4)
Location: drivers/acpi/cppc_acpi.c:358
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
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
In drivers/acpi/cppc_acpi.c (ffffffff8163e544)
Location: drivers/acpi/cppc_acpi.c:358
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int acpi_get_psd(struct cpc_desc *cpc_ptr, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff816eaa90)
Location: drivers/acpi/cppc_acpi.c:358
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff816eaa90-ffffffff816eac99: acpi_get_psd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int acpi_get_psd(struct cpc_desc *cpc_ptr, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff817081f0)
Location: drivers/acpi/cppc_acpi.c:359
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff817081f0-ffffffff817083f9: acpi_get_psd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int acpi_get_psd(struct cpc_desc *cpc_ptr, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff816e97f0)
Location: drivers/acpi/cppc_acpi.c:351
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff816e97f0-ffffffff816e99f9: acpi_get_psd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int acpi_get_psd(struct cpc_desc *cpc_ptr, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81762ee0)
Location: drivers/acpi/cppc_acpi.c:351
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff81762ee0-ffffffff817630d6: acpi_get_psd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int acpi_get_psd(struct cpc_desc *cpc_ptr, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81896e10)
Location: drivers/acpi/cppc_acpi.c:364
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff81896e10-ffffffff81897015: acpi_get_psd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_get_psd(struct cpc_desc *cpc_ptr, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff819deb40)
Location: drivers/acpi/cppc_acpi.c:364
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff819deb40-ffffffff819ded3b: acpi_get_psd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_get_psd(struct cpc_desc *cpc_ptr, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81a26850)
Location: drivers/acpi/cppc_acpi.c:364
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff81a26850-ffffffff81a26a4b: acpi_get_psd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_get_psd(struct cpc_desc *cpc_ptr, acpi_handle handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81a71750)
Location: drivers/acpi/cppc_acpi.c:367
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
```
**Symbols:**

```
ffffffff81a71750-ffffffff81a7194b: acpi_get_psd (STB_LOCAL)
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
In drivers/acpi/cppc_acpi.c (ffff8000107a934c)
Location: drivers/acpi/cppc_acpi.c:358
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
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
In drivers/acpi/cppc_acpi.c (ffffffff81609f74)
Location: drivers/acpi/cppc_acpi.c:358
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
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
In drivers/acpi/cppc_acpi.c (ffffffff815fbbb4)
Location: drivers/acpi/cppc_acpi.c:358
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
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
In drivers/acpi/cppc_acpi.c (ffffffff81632384)
Location: drivers/acpi/cppc_acpi.c:358
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
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
In drivers/acpi/cppc_acpi.c (ffffffff8164c6b4)
Location: drivers/acpi/cppc_acpi.c:358
Inline: True
Inline callers:
  - drivers/acpi/cppc_acpi.c:acpi_cppc_processor_probe
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
