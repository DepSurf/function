# Function: <code>acpi_ds_init_package_element</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_ds_init_package_element(u8 object_type, union acpi_operand_object *source_object, union acpi_generic_state *state, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffffffff81554ffd)
Location: drivers/acpi/acpica/dspkginit.c:294
Inline: False
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
**Symbols:**

```
ffffffff81554ffd-ffffffff81555255: acpi_ds_init_package_element (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ds_init_package_element(u8 object_type, union acpi_operand_object *source_object, union acpi_generic_state *state, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffffffff8158b95a)
Location: drivers/acpi/acpica/dspkginit.c:298
Inline: True
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
**Symbols:**

```
ffffffff8158b95a-ffffffff8158bcc2: acpi_ds_init_package_element (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ds_init_package_element(u8 object_type, union acpi_operand_object *source_object, union acpi_generic_state *state, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffffffff815a3f29)
Location: drivers/acpi/acpica/dspkginit.c:324
Inline: True
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
**Symbols:**

```
ffffffff815a3f29-ffffffff815a4291: acpi_ds_init_package_element (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ds_init_package_element(u8 object_type, union acpi_operand_object *source_object, union acpi_generic_state *state, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffffffff815d5620)
Location: drivers/acpi/acpica/dspkginit.c:324
Inline: True
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
**Symbols:**

```
ffffffff815d5620-ffffffff815d598e: acpi_ds_init_package_element (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ds_init_package_element(u8 object_type, union acpi_operand_object *source_object, union acpi_generic_state *state, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffffffff815f6898)
Location: drivers/acpi/acpica/dspkginit.c:324
Inline: True
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
**Symbols:**

```
ffffffff815f6898-ffffffff815f6c06: acpi_ds_init_package_element (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ds_init_package_element(u8 object_type, union acpi_operand_object *source_object, union acpi_generic_state *state, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffffffff816a2c82)
Location: drivers/acpi/acpica/dspkginit.c:324
Inline: False
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
**Symbols:**

```
ffffffff816a2c82-ffffffff816a2d23: acpi_ds_init_package_element (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ds_init_package_element(u8 object_type, union acpi_operand_object *source_object, union acpi_generic_state *state, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffffffff816c0478)
Location: drivers/acpi/acpica/dspkginit.c:324
Inline: False
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
**Symbols:**

```
ffffffff816c0478-ffffffff816c0519: acpi_ds_init_package_element (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ds_init_package_element(u8 object_type, union acpi_operand_object *source_object, union acpi_generic_state *state, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffffffff816a250f)
Location: drivers/acpi/acpica/dspkginit.c:324
Inline: False
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
**Symbols:**

```
ffffffff816a250f-ffffffff816a25b0: acpi_ds_init_package_element (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ds_init_package_element(u8 object_type, union acpi_operand_object *source_object, union acpi_generic_state *state, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffffffff81718e45)
Location: drivers/acpi/acpica/dspkginit.c:324
Inline: False
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
**Symbols:**

```
ffffffff81718e45-ffffffff81718ee6: acpi_ds_init_package_element (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ds_init_package_element(u8 object_type, union acpi_operand_object *source_object, union acpi_generic_state *state, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffffffff81848b7d)
Location: drivers/acpi/acpica/dspkginit.c:324
Inline: False
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
**Symbols:**

```
ffffffff81848b7d-ffffffff81848c2d: acpi_ds_init_package_element (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ds_init_package_element(u8 object_type, union acpi_operand_object *source_object, union acpi_generic_state *state, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffffffff81980d20)
Location: drivers/acpi/acpica/dspkginit.c:324
Inline: False
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
**Symbols:**

```
ffffffff81980d20-ffffffff81980de0: acpi_ds_init_package_element (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ds_init_package_element(u8 object_type, union acpi_operand_object *source_object, union acpi_generic_state *state, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffffffff819c77e0)
Location: drivers/acpi/acpica/dspkginit.c:324
Inline: False
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
**Symbols:**

```
ffffffff819c77e0-ffffffff819c78a0: acpi_ds_init_package_element (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ds_init_package_element(u8 object_type, union acpi_operand_object *source_object, union acpi_generic_state *state, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffffffff81a12230)
Location: drivers/acpi/acpica/dspkginit.c:324
Inline: False
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
**Symbols:**

```
ffffffff81a12230-ffffffff81a122f0: acpi_ds_init_package_element (STB_GLOBAL)
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
acpi_status acpi_ds_init_package_element(u8 object_type, union acpi_operand_object *source_object, union acpi_generic_state *state, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffff80001077f450)
Location: drivers/acpi/acpica/dspkginit.c:324
Inline: False
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
**Symbols:**

```
ffff80001077f450-ffff80001077f640: acpi_ds_init_package_element (STB_GLOBAL)
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
acpi_status acpi_ds_init_package_element(u8 object_type, union acpi_operand_object *source_object, union acpi_generic_state *state, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffffffff815e2f94)
Location: drivers/acpi/acpica/dspkginit.c:324
Inline: False
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
**Symbols:**

```
ffffffff815e2f94-ffffffff815e3183: acpi_ds_init_package_element (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_status acpi_ds_init_package_element(u8 object_type, union acpi_operand_object *source_object, union acpi_generic_state *state, void *context);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffffffff815ce605)
Location: drivers/acpi/acpica/dspkginit.c:324
Inline: False
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
**Symbols:**

```
ffffffff815ce605-ffffffff815ce7f4: acpi_ds_init_package_element (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ds_init_package_element(u8 object_type, union acpi_operand_object *source_object, union acpi_generic_state *state, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffffffff815eab78)
Location: drivers/acpi/acpica/dspkginit.c:324
Inline: True
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
**Symbols:**

```
ffffffff815eab78-ffffffff815eaee6: acpi_ds_init_package_element (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_ds_init_package_element(u8 object_type, union acpi_operand_object *source_object, union acpi_generic_state *state, void *context);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dspkginit.c (ffffffff81604a28)
Location: drivers/acpi/acpica/dspkginit.c:324
Inline: True
Direct callers:
  - drivers/acpi/acpica/dspkginit.c:acpi_ds_build_internal_package_obj
```
**Symbols:**

```
ffffffff81604a28-ffffffff81604d96: acpi_ds_init_package_element (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
