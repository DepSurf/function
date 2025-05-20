# Function: <code>acpi_get_gpe_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_gpe_device(u32 index, acpi_handle *gpe_device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff814937a9)
Location: drivers/acpi/acpica/evxfgpe.c:920
Inline: True
```
**Symbols:**

```
ffffffff814937a9-ffffffff81493832: acpi_get_gpe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_gpe_device(u32 index, acpi_handle *gpe_device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff814e25a1)
Location: drivers/acpi/acpica/evxfgpe.c:920
Inline: True
```
**Symbols:**

```
ffffffff814e25a1-ffffffff814e262a: acpi_get_gpe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_gpe_device(u32 index, acpi_handle *gpe_device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81504f5a)
Location: drivers/acpi/acpica/evxfgpe.c:963
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
```
**Symbols:**

```
ffffffff81504f5a-ffffffff81504fe3: acpi_get_gpe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_gpe_device(u32 index, acpi_handle *gpe_device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815154ce)
Location: drivers/acpi/acpica/evxfgpe.c:971
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
```
**Symbols:**

```
ffffffff815154ce-ffffffff81515557: acpi_get_gpe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_gpe_device(u32 index, acpi_handle *gpe_device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8155fbb8)
Location: drivers/acpi/acpica/evxfgpe.c:971
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
```
**Symbols:**

```
ffffffff8155fbb8-ffffffff8155fcf3: acpi_get_gpe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_device(u32 index, acpi_handle *gpe_device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815960f6)
Location: drivers/acpi/acpica/evxfgpe.c:978
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
```
**Symbols:**

```
ffffffff815960f6-ffffffff81596230: acpi_get_gpe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_device(u32 index, acpi_handle *gpe_device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815ae7fa)
Location: drivers/acpi/acpica/evxfgpe.c:978
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
```
**Symbols:**

```
ffffffff815ae7fa-ffffffff815ae934: acpi_get_gpe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_device(u32 index, acpi_handle *gpe_device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815e0033)
Location: drivers/acpi/acpica/evxfgpe.c:978
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
```
**Symbols:**

```
ffffffff815e0033-ffffffff815e0174: acpi_get_gpe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_device(u32 index, acpi_handle *gpe_device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81601376)
Location: drivers/acpi/acpica/evxfgpe.c:1010
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
```
**Symbols:**

```
ffffffff81601376-ffffffff816014b7: acpi_get_gpe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_device(u32 index, acpi_handle *gpe_device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816ad5bb)
Location: drivers/acpi/acpica/evxfgpe.c:1017
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:get_status
```
**Symbols:**

```
ffffffff816ad5bb-ffffffff816ad6fc: acpi_get_gpe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_device(u32 index, acpi_handle *gpe_device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816caefa)
Location: drivers/acpi/acpica/evxfgpe.c:1017
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:get_status
```
**Symbols:**

```
ffffffff816caefa-ffffffff816cb03b: acpi_get_gpe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_device(u32 index, acpi_handle *gpe_device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff816acec6)
Location: drivers/acpi/acpica/evxfgpe.c:1017
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:get_status
```
**Symbols:**

```
ffffffff816acec6-ffffffff816ad007: acpi_get_gpe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_device(u32 index, acpi_handle *gpe_device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81723c85)
Location: drivers/acpi/acpica/evxfgpe.c:1017
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:get_status
```
**Symbols:**

```
ffffffff81723c85-ffffffff81723dc6: acpi_get_gpe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_device(u32 index, acpi_handle *gpe_device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff818541ec)
Location: drivers/acpi/acpica/evxfgpe.c:1017
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:get_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_any_gpe_status_set
```
**Symbols:**

```
ffffffff818541ec-ffffffff81854344: acpi_get_gpe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_device(u32 index, acpi_handle *gpe_device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8198ea50)
Location: drivers/acpi/acpica/evxfgpe.c:1017
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:get_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_any_gpe_status_set
```
**Symbols:**

```
ffffffff8198ea50-ffffffff8198ebc3: acpi_get_gpe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_device(u32 index, acpi_handle *gpe_device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff819d54e0)
Location: drivers/acpi/acpica/evxfgpe.c:1017
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:get_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_any_gpe_status_set
```
**Symbols:**

```
ffffffff819d54e0-ffffffff819d5653: acpi_get_gpe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_device(u32 index, acpi_handle *gpe_device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff81a20170)
Location: drivers/acpi/acpica/evxfgpe.c:1017
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
  - drivers/acpi/sysfs.c:get_status
  - drivers/acpi/acpica/evxfgpe.c:acpi_any_gpe_status_set
```
**Symbols:**

```
ffffffff81a20170-ffffffff81a202e3: acpi_get_gpe_device (STB_GLOBAL)
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
In drivers/acpi/sysfs.c (0)
Location: include/acpi/acpixf.h:754
Inline: True
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_gpe_device(u32 index, acpi_handle *gpe_device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815e936b)
Location: drivers/acpi/acpica/evxfgpe.c:1010
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
```
**Symbols:**

```
ffffffff815e936b-ffffffff815e93f3: acpi_get_gpe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_get_gpe_device(u32 index, acpi_handle *gpe_device);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815d4993)
Location: drivers/acpi/acpica/evxfgpe.c:1010
Inline: True
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
```
**Symbols:**

```
ffffffff815d4993-ffffffff815d4a1b: acpi_get_gpe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_device(u32 index, acpi_handle *gpe_device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff815f5656)
Location: drivers/acpi/acpica/evxfgpe.c:1010
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
```
**Symbols:**

```
ffffffff815f5656-ffffffff815f5797: acpi_get_gpe_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_get_gpe_device(u32 index, acpi_handle *gpe_device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evxfgpe.c (ffffffff8160f506)
Location: drivers/acpi/acpica/evxfgpe.c:1010
Inline: False
Direct callers:
  - drivers/acpi/sysfs.c:acpi_gpe_apply_masked_gpes
```
**Symbols:**

```
ffffffff8160f506-ffffffff8160f647: acpi_get_gpe_device (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
