# Function: <code>acpi_ev_execute_reg_method</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_status acpi_ev_execute_reg_method(union acpi_operand_object *region_obj, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evregion.c (ffffffff81491bec)
Location: drivers/acpi/acpica/evregion.c:539
Inline: False
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
```
**Symbols:**

```
ffffffff81491bec-ffffffff81491d11: acpi_ev_execute_reg_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ev_execute_reg_method(union acpi_operand_object *region_obj, u32 function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evregion.c (ffffffff814e09d3)
Location: drivers/acpi/acpica/evregion.c:541
Inline: True
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
```
**Symbols:**

```
ffffffff814e09d3-ffffffff814e0b76: acpi_ev_execute_reg_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ev_execute_reg_method(union acpi_operand_object *region_obj, u32 function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evregion.c (ffffffff81503339)
Location: drivers/acpi/acpica/evregion.c:541
Inline: True
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
```
**Symbols:**

```
ffffffff81503339-ffffffff815034dc: acpi_ev_execute_reg_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ev_execute_reg_method(union acpi_operand_object *region_obj, u32 function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evregion.c (ffffffff81513876)
Location: drivers/acpi/acpica/evregion.c:541
Inline: True
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
```
**Symbols:**

```
ffffffff81513876-ffffffff81513a21: acpi_ev_execute_reg_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ev_execute_reg_method(union acpi_operand_object *region_obj, u32 function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evregion.c (ffffffff8155c787)
Location: drivers/acpi/acpica/evregion.c:541
Inline: True
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
```
**Symbols:**

```
ffffffff8155c787-ffffffff8155ca13: acpi_ev_execute_reg_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ev_execute_reg_method(union acpi_operand_object *region_obj, u32 function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evregion.c (ffffffff8159332f)
Location: drivers/acpi/acpica/evregion.c:517
Inline: True
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
```
**Symbols:**

```
ffffffff8159332f-ffffffff815935bb: acpi_ev_execute_reg_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ev_execute_reg_method(union acpi_operand_object *region_obj, u32 function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evregion.c (ffffffff815ab9cd)
Location: drivers/acpi/acpica/evregion.c:517
Inline: True
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
```
**Symbols:**

```
ffffffff815ab9cd-ffffffff815abc59: acpi_ev_execute_reg_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ev_execute_reg_method(union acpi_operand_object *region_obj, u32 function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evregion.c (ffffffff815dd1d7)
Location: drivers/acpi/acpica/evregion.c:517
Inline: True
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
```
**Symbols:**

```
ffffffff815dd1d7-ffffffff815dd465: acpi_ev_execute_reg_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ev_execute_reg_method(union acpi_operand_object *region_obj, u32 function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evregion.c (ffffffff815fe51a)
Location: drivers/acpi/acpica/evregion.c:517
Inline: True
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
```
**Symbols:**

```
ffffffff815fe51a-ffffffff815fe7a8: acpi_ev_execute_reg_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_ev_execute_reg_method(union acpi_operand_object *region_obj, u32 function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evregion.c (ffffffff816aa27d)
Location: drivers/acpi/acpica/evregion.c:517
Inline: True
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
```
**Symbols:**

```
ffffffff816aa27d-ffffffff816aa4bb: acpi_ev_execute_reg_method.part.0 (STB_LOCAL)
ffffffff816aa95f-ffffffff816aa9d5: acpi_ev_execute_reg_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_ev_execute_reg_method(union acpi_operand_object *region_obj, u32 function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evregion.c (ffffffff816c7b2f)
Location: drivers/acpi/acpica/evregion.c:548
Inline: True
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
```
**Symbols:**

```
ffffffff816c7b2f-ffffffff816c7d6d: acpi_ev_execute_reg_method.part.0 (STB_LOCAL)
ffffffff816c8282-ffffffff816c82f8: acpi_ev_execute_reg_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_ev_execute_reg_method(union acpi_operand_object *region_obj, u32 function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evregion.c (ffffffff816a9b48)
Location: drivers/acpi/acpica/evregion.c:535
Inline: True
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
```
**Symbols:**

```
ffffffff816a9b48-ffffffff816a9d86: acpi_ev_execute_reg_method.part.0 (STB_LOCAL)
ffffffff816aa260-ffffffff816aa2d6: acpi_ev_execute_reg_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_ev_execute_reg_method(union acpi_operand_object *region_obj, u32 function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/evregion.c (ffffffff817207a2)
Location: drivers/acpi/acpica/evregion.c:535
Inline: True
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
```
**Symbols:**

```
ffffffff817207a2-ffffffff817209e0: acpi_ev_execute_reg_method.part.0 (STB_LOCAL)
ffffffff81720eba-ffffffff81720f30: acpi_ev_execute_reg_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ev_execute_reg_method(union acpi_operand_object *region_obj, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evregion.c (ffffffff81850f02)
Location: drivers/acpi/acpica/evregion.c:545
Inline: False
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
```
**Symbols:**

```
ffffffff81850f02-ffffffff818511ad: acpi_ev_execute_reg_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ev_execute_reg_method(union acpi_operand_object *region_obj, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evregion.c (ffffffff8198ad60)
Location: drivers/acpi/acpica/evregion.c:554
Inline: False
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
```
**Symbols:**

```
ffffffff8198ad60-ffffffff8198b047: acpi_ev_execute_reg_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ev_execute_reg_method(union acpi_operand_object *region_obj, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evregion.c (ffffffff819d17e0)
Location: drivers/acpi/acpica/evregion.c:554
Inline: False
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
```
**Symbols:**

```
ffffffff819d17e0-ffffffff819d1ac7: acpi_ev_execute_reg_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ev_execute_reg_method(union acpi_operand_object *region_obj, u32 function);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evregion.c (ffffffff81a1c340)
Location: drivers/acpi/acpica/evregion.c:554
Inline: False
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
```
**Symbols:**

```
ffffffff81a1c340-ffffffff81a1c656: acpi_ev_execute_reg_method (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ev_execute_reg_method(union acpi_operand_object *region_obj, u32 function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evregion.c (ffff800010782568)
Location: drivers/acpi/acpica/evregion.c:517
Inline: True
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
```
**Symbols:**

```
ffff800010782568-ffff80001078271c: acpi_ev_execute_reg_method (STB_GLOBAL)
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
acpi_status acpi_ev_execute_reg_method(union acpi_operand_object *region_obj, u32 function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evregion.c (ffffffff815e753b)
Location: drivers/acpi/acpica/evregion.c:517
Inline: True
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
```
**Symbols:**

```
ffffffff815e753b-ffffffff815e76f1: acpi_ev_execute_reg_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ev_execute_reg_method(union acpi_operand_object *region_obj, u32 function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evregion.c (ffffffff815d2b8e)
Location: drivers/acpi/acpica/evregion.c:517
Inline: True
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
```
**Symbols:**

```
ffffffff815d2b8e-ffffffff815d2d3f: acpi_ev_execute_reg_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ev_execute_reg_method(union acpi_operand_object *region_obj, u32 function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evregion.c (ffffffff815f27fa)
Location: drivers/acpi/acpica/evregion.c:517
Inline: True
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
```
**Symbols:**

```
ffffffff815f27fa-ffffffff815f2a88: acpi_ev_execute_reg_method (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ev_execute_reg_method(union acpi_operand_object *region_obj, u32 function);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/evregion.c (ffffffff8160c6aa)
Location: drivers/acpi/acpica/evregion.c:517
Inline: True
Direct callers:
  - drivers/acpi/acpica/evregion.c:acpi_ev_reg_run
  - drivers/acpi/acpica/evregion.c:acpi_ev_detach_region
  - drivers/acpi/acpica/evrgnini.c:acpi_ev_initialize_region
```
**Symbols:**

```
ffffffff8160c6aa-ffffffff8160c938: acpi_ev_execute_reg_method (STB_GLOBAL)
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
