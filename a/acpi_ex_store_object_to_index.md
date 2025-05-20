# Function: <code>acpi_ex_store_object_to_index</code>

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
In drivers/acpi/acpica/exstore.c (ffffffff814997e4)
Location: drivers/acpi/acpica/exstore.c:227
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
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
In drivers/acpi/acpica/exstore.c (ffffffff814e8525)
Location: drivers/acpi/acpica/exstore.c:227
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
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
In drivers/acpi/acpica/exstore.c (ffffffff8150ad79)
Location: drivers/acpi/acpica/exstore.c:227
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
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
In drivers/acpi/acpica/exstore.c (ffffffff8151b3ad)
Location: drivers/acpi/acpica/exstore.c:227
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
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
In drivers/acpi/acpica/exstore.c (ffffffff8156ab03)
Location: drivers/acpi/acpica/exstore.c:227
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
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
In drivers/acpi/acpica/exstore.c (ffffffff815a1759)
Location: drivers/acpi/acpica/exstore.c:193
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
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
In drivers/acpi/acpica/exstore.c (ffffffff815ba419)
Location: drivers/acpi/acpica/exstore.c:193
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
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
In drivers/acpi/acpica/exstore.c (ffffffff815ebfa8)
Location: drivers/acpi/acpica/exstore.c:193
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
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
In drivers/acpi/acpica/exstore.c (ffffffff8160d33d)
Location: drivers/acpi/acpica/exstore.c:193
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ex_store_object_to_index(union acpi_operand_object *source_desc, union acpi_operand_object *index_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exstore.c (ffffffff816b9068)
Location: drivers/acpi/acpica/exstore.c:193
Inline: False
Direct callers:
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
```
**Symbols:**

```
ffffffff816b9068-ffffffff816b928d: acpi_ex_store_object_to_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ex_store_object_to_index(union acpi_operand_object *source_desc, union acpi_operand_object *index_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exstore.c (ffffffff816d6a71)
Location: drivers/acpi/acpica/exstore.c:193
Inline: False
Direct callers:
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
```
**Symbols:**

```
ffffffff816d6a71-ffffffff816d6c96: acpi_ex_store_object_to_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ex_store_object_to_index(union acpi_operand_object *source_desc, union acpi_operand_object *index_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exstore.c (ffffffff816b8a06)
Location: drivers/acpi/acpica/exstore.c:193
Inline: False
Direct callers:
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
```
**Symbols:**

```
ffffffff816b8a06-ffffffff816b8c2b: acpi_ex_store_object_to_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ex_store_object_to_index(union acpi_operand_object *source_desc, union acpi_operand_object *index_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exstore.c (ffffffff8172fa56)
Location: drivers/acpi/acpica/exstore.c:193
Inline: False
Direct callers:
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
```
**Symbols:**

```
ffffffff8172fa56-ffffffff8172fc7b: acpi_ex_store_object_to_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ex_store_object_to_index(union acpi_operand_object *source_desc, union acpi_operand_object *index_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exstore.c (ffffffff818604f0)
Location: drivers/acpi/acpica/exstore.c:193
Inline: False
Direct callers:
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
```
**Symbols:**

```
ffffffff818604f0-ffffffff81860726: acpi_ex_store_object_to_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ex_store_object_to_index(union acpi_operand_object *source_desc, union acpi_operand_object *index_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exstore.c (ffffffff8199d390)
Location: drivers/acpi/acpica/exstore.c:193
Inline: False
Direct callers:
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
```
**Symbols:**

```
ffffffff8199d390-ffffffff8199d605: acpi_ex_store_object_to_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ex_store_object_to_index(union acpi_operand_object *source_desc, union acpi_operand_object *index_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exstore.c (ffffffff819e40a0)
Location: drivers/acpi/acpica/exstore.c:193
Inline: False
Direct callers:
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
```
**Symbols:**

```
ffffffff819e40a0-ffffffff819e4324: acpi_ex_store_object_to_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ex_store_object_to_index(union acpi_operand_object *source_desc, union acpi_operand_object *index_desc, struct acpi_walk_state *walk_state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/exstore.c (ffffffff81a2edf0)
Location: drivers/acpi/acpica/exstore.c:193
Inline: False
Direct callers:
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
```
**Symbols:**

```
ffffffff81a2edf0-ffffffff81a2f074: acpi_ex_store_object_to_index (STB_LOCAL)
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
In drivers/acpi/acpica/exstore.c (ffff800010789b70)
Location: drivers/acpi/acpica/exstore.c:193
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
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
In drivers/acpi/acpica/exstore.c (ffffffff815ef6e4)
Location: drivers/acpi/acpica/exstore.c:193
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
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
In drivers/acpi/acpica/exstore.c (ffffffff815dacdc)
Location: drivers/acpi/acpica/exstore.c:193
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
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
In drivers/acpi/acpica/exstore.c (ffffffff8160161d)
Location: drivers/acpi/acpica/exstore.c:193
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
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
In drivers/acpi/acpica/exstore.c (ffffffff8161b4cd)
Location: drivers/acpi/acpica/exstore.c:193
Inline: True
Inline callers:
  - drivers/acpi/acpica/exstore.c:acpi_ex_store
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
