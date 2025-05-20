# Function: <code>acpi_processor_get_psd</code>

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
In drivers/acpi/processor_perflib.c (ffffffff814af42f)
Location: drivers/acpi/processor_perflib.c:529
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
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
In drivers/acpi/processor_perflib.c (ffffffff814fed8d)
Location: drivers/acpi/processor_perflib.c:529
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
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
In drivers/acpi/processor_perflib.c (ffffffff8152199e)
Location: drivers/acpi/processor_perflib.c:538
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
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
In drivers/acpi/processor_perflib.c (ffffffff81533355)
Location: drivers/acpi/processor_perflib.c:536
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
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
In drivers/acpi/processor_perflib.c (ffffffff81594abb)
Location: drivers/acpi/processor_perflib.c:536
Inline: True
Inline callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package *pdomain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:537
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff815cc501-ffffffff815cc559: acpi_processor_get_psd.cold.8 (STB_LOCAL)
ffffffff815cb540-ffffffff815cb647: acpi_processor_get_psd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package *pdomain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:537
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff815e5ae1-ffffffff815e5b39: acpi_processor_get_psd.cold.9 (STB_LOCAL)
ffffffff815e4b20-ffffffff815e4c27: acpi_processor_get_psd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package *pdomain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:524
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff816176d3-ffffffff8161772f: acpi_processor_get_psd.cold (STB_LOCAL)
ffffffff81616700-ffffffff8161680e: acpi_processor_get_psd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package *pdomain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:510
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff81638ceb-ffffffff81638d47: acpi_processor_get_psd.cold (STB_LOCAL)
ffffffff81637cc0-ffffffff81637dce: acpi_processor_get_psd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package *pdomain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:510
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff816e5ac0-ffffffff816e5b1c: acpi_processor_get_psd.cold (STB_LOCAL)
ffffffff816e4bb0-ffffffff816e4cbe: acpi_processor_get_psd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package *pdomain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:509
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff81c02d2e-ffffffff81c02d8a: acpi_processor_get_psd.cold (STB_LOCAL)
ffffffff81702620-ffffffff8170272e: acpi_processor_get_psd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package *pdomain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:507
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff81bf4775-ffffffff81bf47d1: acpi_processor_get_psd.cold (STB_LOCAL)
ffffffff816e3f00-ffffffff816e400e: acpi_processor_get_psd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package *pdomain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:505
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff81cf1892-ffffffff81cf18ee: acpi_processor_get_psd.cold (STB_LOCAL)
ffffffff8175cb80-ffffffff8175cc8e: acpi_processor_get_psd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package *pdomain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:505
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff81eb982d-ffffffff81eb986d: acpi_processor_get_psd.cold (STB_LOCAL)
ffffffff818901a0-ffffffff818902b2: acpi_processor_get_psd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package *pdomain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff819d75b0)
Location: drivers/acpi/processor_perflib.c:501
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff819d75b0-ffffffff819d76f1: acpi_processor_get_psd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package *pdomain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81a1efb0)
Location: drivers/acpi/processor_perflib.c:523
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff81a1efb0-ffffffff81a1f0f1: acpi_processor_get_psd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package *pdomain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffffffff81a6a2d0)
Location: drivers/acpi/processor_perflib.c:523
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff81a6a2d0-ffffffff81a6a411: acpi_processor_get_psd (STB_GLOBAL)
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
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package *pdomain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/processor_perflib.c (ffff8000107a3278)
Location: drivers/acpi/processor_perflib.c:510
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
**Symbols:**

```
ffff8000107a3278-ffff8000107a33cc: acpi_processor_get_psd (STB_GLOBAL)
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
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package *pdomain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:510
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff81607d10-ffffffff81607d6c: acpi_processor_get_psd.cold (STB_LOCAL)
ffffffff81606ef0-ffffffff81606ffe: acpi_processor_get_psd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package *pdomain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:510
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
```
**Symbols:**

```
ffffffff815f2e10-ffffffff815f2e6c: acpi_processor_get_psd.cold (STB_LOCAL)
ffffffff815f1fc0-ffffffff815f20ce: acpi_processor_get_psd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package *pdomain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:510
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff8162cfcb-ffffffff8162d027: acpi_processor_get_psd.cold (STB_LOCAL)
ffffffff8162bfa0-ffffffff8162c0ae: acpi_processor_get_psd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpi_processor_get_psd(acpi_handle handle, struct acpi_psd_package *pdomain);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/processor_perflib.c (0)
Location: drivers/acpi/processor_perflib.c:510
Inline: False
Direct callers:
  - drivers/acpi/processor_perflib.c:acpi_processor_preregister_performance
  - drivers/xen/xen-acpi-processor.c:read_acpi_id
```
**Symbols:**

```
ffffffff81646e6b-ffffffff81646ec7: acpi_processor_get_psd.cold (STB_LOCAL)
ffffffff81645e40-ffffffff81645f4e: acpi_processor_get_psd (STB_GLOBAL)
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
