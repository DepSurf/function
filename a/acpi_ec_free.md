# Function: <code>acpi_ec_free</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_ec_free(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff814f3c8b)
Location: drivers/acpi/ec.c:1311
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff814f3c8b-ffffffff814f3cc3: acpi_ec_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_ec_free(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81501bc0)
Location: drivers/acpi/ec.c:1322
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff81501bc0-ffffffff81501bfa: acpi_ec_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void acpi_ec_free(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81543ee0)
Location: drivers/acpi/ec.c:1324
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff81543ee0-ffffffff81543f1a: acpi_ec_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_ec_free(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81579ea0)
Location: drivers/acpi/ec.c:1330
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff81579ea0-ffffffff81579ee8: acpi_ec_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_ec_free(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81591bd0)
Location: drivers/acpi/ec.c:1342
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff81591bd0-ffffffff81591c18: acpi_ec_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_ec_free(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815c2aa0)
Location: drivers/acpi/ec.c:1356
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff815c2aa0-ffffffff815c2ae8: acpi_ec_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_ec_free(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815e3e50)
Location: drivers/acpi/ec.c:1330
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff815e3e50-ffffffff815e3e98: acpi_ec_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_free(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff8168fea9)
Location: drivers/acpi/ec.c:1328
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
```
**Symbols:**

```
ffffffff816918ff-ffffffff81691937: acpi_ec_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_free(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff816adb79)
Location: drivers/acpi/ec.c:1315
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
```
**Symbols:**

```
ffffffff81c01540-ffffffff81c01578: acpi_ec_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_free(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81690077)
Location: drivers/acpi/ec.c:1316
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
```
**Symbols:**

```
ffffffff81bf2dd6-ffffffff81bf2e0e: acpi_ec_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_free(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81705a27)
Location: drivers/acpi/ec.c:1333
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
```
**Symbols:**

```
ffffffff81cef7e6-ffffffff81cef81e: acpi_ec_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void acpi_ec_free(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff81833c2b)
Location: drivers/acpi/ec.c:1347
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
```
**Symbols:**

```
ffffffff81eb7348-ffffffff81eb7386: acpi_ec_free (STB_LOCAL)
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
In drivers/acpi/ec.c (ffffffff83ee29de)
Location: drivers/acpi/ec.c:1344
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
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
In drivers/acpi/ec.c (ffffffff8370841e)
Location: drivers/acpi/ec.c:1363
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
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
In drivers/acpi/ec.c (ffffffff8393b7ee)
Location: drivers/acpi/ec.c:1363
Inline: True
Inline callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
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
void acpi_ec_free(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffff80001076ffe8)
Location: drivers/acpi/ec.c:1330
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffff80001076ffe8-ffff800010770060: acpi_ec_free (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void acpi_ec_free(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d5d40)
Location: drivers/acpi/ec.c:1330
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff815d5d40-ffffffff815d5d88: acpi_ec_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_ec_free(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815bf900)
Location: drivers/acpi/ec.c:1330
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff815bf900-ffffffff815bf948: acpi_ec_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_ec_free(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815d8130)
Location: drivers/acpi/ec.c:1330
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff815d8130-ffffffff815d8178: acpi_ec_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_ec_free(struct acpi_ec *ec);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/ec.c (ffffffff815f1ff0)
Location: drivers/acpi/ec.c:1330
Inline: False
Direct callers:
  - drivers/acpi/ec.c:acpi_ec_ecdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_dsdt_probe
  - drivers/acpi/ec.c:acpi_ec_remove
  - drivers/acpi/ec.c:acpi_ec_add
  - drivers/acpi/ec.c:acpi_ec_add
```
**Symbols:**

```
ffffffff815f1ff0-ffffffff815f2038: acpi_ec_free (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
