# Function: <code>acpi_db_single_step</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswexec.c (0)
Location: drivers/acpi/acpica/acdebug.h:83
Inline: True
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
In drivers/acpi/acpica/dswexec.c (0)
Location: drivers/acpi/acpica/acdebug.h:83
Inline: True
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
In drivers/acpi/acpica/dswexec.c (0)
Location: drivers/acpi/acpica/acdebug.h:83
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_status acpi_db_single_step(struct acpi_walk_state *walk_state, union acpi_parse_object *op, u32 opcode_class);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbxface.c (ffffffff8158d8b8)
Location: drivers/acpi/acpica/dbxface.c:166
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
```
**Symbols:**

```
ffffffff8158d8b8-ffffffff8158db55: acpi_db_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_status acpi_db_single_step(struct acpi_walk_state *walk_state, union acpi_parse_object *op, u32 opcode_class);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbxface.c (ffffffff815c4c00)
Location: drivers/acpi/acpica/dbxface.c:130
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
```
**Symbols:**

```
ffffffff815c4c00-ffffffff815c4e9a: acpi_db_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_status acpi_db_single_step(struct acpi_walk_state *walk_state, union acpi_parse_object *op, u32 opcode_class);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbxface.c (ffffffff815de156)
Location: drivers/acpi/acpica/dbxface.c:202
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
```
**Symbols:**

```
ffffffff815de156-ffffffff815de3b6: acpi_db_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_status acpi_db_single_step(struct acpi_walk_state *walk_state, union acpi_parse_object *op, u32 opcode_class);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbxface.c (ffffffff8160fc5c)
Location: drivers/acpi/acpica/dbxface.c:202
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
```
**Symbols:**

```
ffffffff8160fc5c-ffffffff8160feae: acpi_db_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_status acpi_db_single_step(struct acpi_walk_state *walk_state, union acpi_parse_object *op, u32 opcode_class);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbxface.c (ffffffff81631105)
Location: drivers/acpi/acpica/dbxface.c:202
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
```
**Symbols:**

```
ffffffff81631105-ffffffff81631357: acpi_db_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_db_single_step(struct acpi_walk_state *walk_state, union acpi_parse_object *op, u32 opcode_class);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbxface.c (ffffffff816ddb74)
Location: drivers/acpi/acpica/dbxface.c:202
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
```
**Symbols:**

```
ffffffff816ddb74-ffffffff816dddc6: acpi_db_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_db_single_step(struct acpi_walk_state *walk_state, union acpi_parse_object *op, u32 opcode_class);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbxface.c (ffffffff816fbc0a)
Location: drivers/acpi/acpica/dbxface.c:202
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
```
**Symbols:**

```
ffffffff816fbc0a-ffffffff816fbe5c: acpi_db_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_db_single_step(struct acpi_walk_state *walk_state, union acpi_parse_object *op, u32 opcode_class);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbxface.c (ffffffff816dda2d)
Location: drivers/acpi/acpica/dbxface.c:202
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
```
**Symbols:**

```
ffffffff816dda2d-ffffffff816ddc85: acpi_db_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_db_single_step(struct acpi_walk_state *walk_state, union acpi_parse_object *op, u32 opcode_class);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbxface.c (ffffffff81755b1d)
Location: drivers/acpi/acpica/dbxface.c:202
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
```
**Symbols:**

```
ffffffff81755b1d-ffffffff81755d75: acpi_db_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_db_single_step(struct acpi_walk_state *walk_state, union acpi_parse_object *op, u32 opcode_class);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbxface.c (ffffffff81888bd0)
Location: drivers/acpi/acpica/dbxface.c:202
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
```
**Symbols:**

```
ffffffff81888bd0-ffffffff81888e2e: acpi_db_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_db_single_step(struct acpi_walk_state *walk_state, union acpi_parse_object *op, u32 opcode_class);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbxface.c (ffffffff819cf200)
Location: drivers/acpi/acpica/dbxface.c:202
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
```
**Symbols:**

```
ffffffff819cf200-ffffffff819cf50b: acpi_db_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_db_single_step(struct acpi_walk_state *walk_state, union acpi_parse_object *op, u32 opcode_class);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbxface.c (ffffffff81a166d0)
Location: drivers/acpi/acpica/dbxface.c:202
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
```
**Symbols:**

```
ffffffff81a166d0-ffffffff81a169d9: acpi_db_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_db_single_step(struct acpi_walk_state *walk_state, union acpi_parse_object *op, u32 opcode_class);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbxface.c (ffffffff81a618b0)
Location: drivers/acpi/acpica/dbxface.c:202
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
```
**Symbols:**

```
ffffffff81a618b0-ffffffff81a61bb9: acpi_db_single_step (STB_GLOBAL)
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
In drivers/acpi/acpica/dswexec.c (0)
Location: drivers/acpi/acpica/acdebug.h:50
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswexec.c (0)
Location: drivers/acpi/acpica/acdebug.h:50
Inline: True
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
In drivers/acpi/acpica/dswexec.c (0)
Location: drivers/acpi/acpica/acdebug.h:50
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_status acpi_db_single_step(struct acpi_walk_state *walk_state, union acpi_parse_object *op, u32 opcode_class);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbxface.c (ffffffff816253e5)
Location: drivers/acpi/acpica/dbxface.c:202
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
```
**Symbols:**

```
ffffffff816253e5-ffffffff81625637: acpi_db_single_step (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_status acpi_db_single_step(struct acpi_walk_state *walk_state, union acpi_parse_object *op, u32 opcode_class);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbxface.c (ffffffff8163f295)
Location: drivers/acpi/acpica/dbxface.c:202
Inline: False
Direct callers:
  - drivers/acpi/acpica/dswexec.c:acpi_ds_exec_end_op
```
**Symbols:**

```
ffffffff8163f295-ffffffff8163f4e7: acpi_db_single_step (STB_GLOBAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
