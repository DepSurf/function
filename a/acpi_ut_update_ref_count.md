# Function: <code>acpi_ut_update_ref_count</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_ut_update_ref_count(union acpi_operand_object *object, u32 action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff814a72a2)
Location: drivers/acpi/acpica/utdelete.c:386
Inline: False
Direct callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
```
**Symbols:**

```
ffffffff814a72a2-ffffffff814a7592: acpi_ut_update_ref_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_ut_update_ref_count(union acpi_operand_object *object, u32 action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff814f6625)
Location: drivers/acpi/acpica/utdelete.c:387
Inline: False
Direct callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
```
**Symbols:**

```
ffffffff814f6625-ffffffff814f6913: acpi_ut_update_ref_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_ut_update_ref_count(union acpi_operand_object *object, u32 action);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff815191e8)
Location: drivers/acpi/acpica/utdelete.c:387
Inline: False
Direct callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
```
**Symbols:**

```
ffffffff815191e8-ffffffff815194d6: acpi_ut_update_ref_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff81529d5e)
Location: drivers/acpi/acpica/utdelete.c:387
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
Direct callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
```
**Symbols:**

```
ffffffff815299ff-ffffffff81529cec: acpi_ut_update_ref_count.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff81582dc5)
Location: drivers/acpi/acpica/utdelete.c:387
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
Direct callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
```
**Symbols:**

```
ffffffff8158262e-ffffffff81582d0f: acpi_ut_update_ref_count.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff815b9f81)
Location: drivers/acpi/acpica/utdelete.c:353
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
Direct callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
```
**Symbols:**

```
ffffffff815b97e6-ffffffff815b9ecb: acpi_ut_update_ref_count.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff815d33f0)
Location: drivers/acpi/acpica/utdelete.c:353
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
Direct callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
```
**Symbols:**

```
ffffffff815d2bb7-ffffffff815d3302: acpi_ut_update_ref_count.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff81604d67)
Location: drivers/acpi/acpica/utdelete.c:357
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
Direct callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
```
**Symbols:**

```
ffffffff81604a91-ffffffff81604c7c: acpi_ut_update_ref_count.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff81626211)
Location: drivers/acpi/acpica/utdelete.c:357
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
Direct callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
```
**Symbols:**

```
ffffffff81625f3b-ffffffff81626126: acpi_ut_update_ref_count.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_ut_update_ref_count(union acpi_operand_object *object, u32 action);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff816d26d9)
Location: drivers/acpi/acpica/utdelete.c:357
Inline: True
Direct callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
```
**Symbols:**

```
ffffffff816d26d9-ffffffff816d28c4: acpi_ut_update_ref_count.part.0 (STB_LOCAL)
ffffffff816d28c4-ffffffff816d28da: acpi_ut_update_ref_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_ut_update_ref_count(union acpi_operand_object *object, u32 action);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff816f06b7)
Location: drivers/acpi/acpica/utdelete.c:357
Inline: True
Direct callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
```
**Symbols:**

```
ffffffff816f06b7-ffffffff816f08a2: acpi_ut_update_ref_count.part.0 (STB_LOCAL)
ffffffff816f08a2-ffffffff816f08b8: acpi_ut_update_ref_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_ut_update_ref_count(union acpi_operand_object *object, u32 action);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff816d2561)
Location: drivers/acpi/acpica/utdelete.c:365
Inline: True
Direct callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
```
**Symbols:**

```
ffffffff816d2561-ffffffff816d274c: acpi_ut_update_ref_count.part.0 (STB_LOCAL)
ffffffff816d274c-ffffffff816d2762: acpi_ut_update_ref_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_ut_update_ref_count(union acpi_operand_object *object, u32 action);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff81749da0)
Location: drivers/acpi/acpica/utdelete.c:365
Inline: True
Direct callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
```
**Symbols:**

```
ffffffff81749da0-ffffffff81749f90: acpi_ut_update_ref_count.part.0 (STB_LOCAL)
ffffffff81749f90-ffffffff81749fa6: acpi_ut_update_ref_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void acpi_ut_update_ref_count(union acpi_operand_object *object, u32 action);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff8187c173)
Location: drivers/acpi/acpica/utdelete.c:365
Inline: True
Direct callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
```
**Symbols:**

```
ffffffff8187c173-ffffffff8187c36a: acpi_ut_update_ref_count.part.0 (STB_LOCAL)
ffffffff8187c36a-ffffffff8187c390: acpi_ut_update_ref_count (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff819bf848)
Location: drivers/acpi/acpica/utdelete.c:365
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
Direct callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
```
**Symbols:**

```
ffffffff819bf580-ffffffff819bf7be: acpi_ut_update_ref_count.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff81a06a43)
Location: drivers/acpi/acpica/utdelete.c:365
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
Direct callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
```
**Symbols:**

```
ffffffff81a06740-ffffffff81a06998: acpi_ut_update_ref_count.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff81a518e3)
Location: drivers/acpi/acpica/utdelete.c:365
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
Direct callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
```
**Symbols:**

```
ffffffff81a515e0-ffffffff81a51838: acpi_ut_update_ref_count.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffff80001079b658)
Location: drivers/acpi/acpica/utdelete.c:357
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
Direct callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
```
**Symbols:**

```
ffff80001079b2c0-ffff80001079b5b8: acpi_ut_update_ref_count.part.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff815feabc)
Location: drivers/acpi/acpica/utdelete.c:357
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
Direct callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
```
**Symbols:**

```
ffffffff815fe69c-ffffffff815fea11: acpi_ut_update_ref_count.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff815e9fb3)
Location: drivers/acpi/acpica/utdelete.c:357
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
Direct callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
```
**Symbols:**

```
ffffffff815e9b93-ffffffff815e9f08: acpi_ut_update_ref_count.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff8161a4f1)
Location: drivers/acpi/acpica/utdelete.c:357
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
Direct callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
```
**Symbols:**

```
ffffffff8161a21b-ffffffff8161a406: acpi_ut_update_ref_count.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/utdelete.c (ffffffff816343a1)
Location: drivers/acpi/acpica/utdelete.c:357
Inline: True
Inline callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
Direct callers:
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
  - drivers/acpi/acpica/utdelete.c:acpi_ut_update_object_reference
```
**Symbols:**

```
ffffffff816340cb-ffffffff816342b6: acpi_ut_update_ref_count.part.0 (STB_LOCAL)
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
