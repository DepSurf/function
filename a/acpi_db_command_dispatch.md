# Function: <code>acpi_db_command_dispatch</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
acpi_status acpi_db_command_dispatch(char *input_buffer, struct acpi_walk_state *walk_state, union acpi_parse_object *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff8158b0e8)
Location: drivers/acpi/acpica/dbinput.c:688
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff8158b0e8-ffffffff8158b679: acpi_db_command_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_db_command_dispatch(char *input_buffer, struct acpi_walk_state *walk_state, union acpi_parse_object *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff815c23b6)
Location: drivers/acpi/acpica/dbinput.c:672
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff815c23d5-ffffffff815c296d: acpi_db_command_dispatch.part.0 (STB_LOCAL)
ffffffff815c23b6-ffffffff815c23d5: acpi_db_command_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_db_command_dispatch(char *input_buffer, struct acpi_walk_state *walk_state, union acpi_parse_object *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff815db83c)
Location: drivers/acpi/acpica/dbinput.c:672
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff815db85b-ffffffff815dbfab: acpi_db_command_dispatch.part.0 (STB_LOCAL)
ffffffff815db83c-ffffffff815db85b: acpi_db_command_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_db_command_dispatch(char *input_buffer, struct acpi_walk_state *walk_state, union acpi_parse_object *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff8160d33f)
Location: drivers/acpi/acpica/dbinput.c:672
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff8160d35e-ffffffff8160da8e: acpi_db_command_dispatch.part.0 (STB_LOCAL)
ffffffff8160d33f-ffffffff8160d35e: acpi_db_command_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_db_command_dispatch(char *input_buffer, struct acpi_walk_state *walk_state, union acpi_parse_object *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff8162e7e0)
Location: drivers/acpi/acpica/dbinput.c:672
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff8162e7ff-ffffffff8162ef2f: acpi_db_command_dispatch.part.0 (STB_LOCAL)
ffffffff8162e7e0-ffffffff8162e7ff: acpi_db_command_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_db_command_dispatch(char *input_buffer, struct acpi_walk_state *walk_state, union acpi_parse_object *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff816db03b)
Location: drivers/acpi/acpica/dbinput.c:689
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff816db05a-ffffffff816db7d4: acpi_db_command_dispatch.part.0 (STB_LOCAL)
ffffffff816db03b-ffffffff816db05a: acpi_db_command_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_db_command_dispatch(char *input_buffer, struct acpi_walk_state *walk_state, union acpi_parse_object *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff816f9000)
Location: drivers/acpi/acpica/dbinput.c:692
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff816f901f-ffffffff816f97c3: acpi_db_command_dispatch.part.0 (STB_LOCAL)
ffffffff816f9000-ffffffff816f901f: acpi_db_command_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_db_command_dispatch(char *input_buffer, struct acpi_walk_state *walk_state, union acpi_parse_object *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff816dae3f)
Location: drivers/acpi/acpica/dbinput.c:692
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff816dae5e-ffffffff816db5ff: acpi_db_command_dispatch.part.0 (STB_LOCAL)
ffffffff816dae3f-ffffffff816dae5e: acpi_db_command_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_db_command_dispatch(char *input_buffer, struct acpi_walk_state *walk_state, union acpi_parse_object *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff81752c3a)
Location: drivers/acpi/acpica/dbinput.c:692
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff81752c59-ffffffff81753516: acpi_db_command_dispatch.part.0 (STB_LOCAL)
ffffffff81752c3a-ffffffff81752c59: acpi_db_command_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_db_command_dispatch(char *input_buffer, struct acpi_walk_state *walk_state, union acpi_parse_object *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff81885a6d)
Location: drivers/acpi/acpica/dbinput.c:692
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff81885a6d-ffffffff818862b7: acpi_db_command_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_db_command_dispatch(char *input_buffer, struct acpi_walk_state *walk_state, union acpi_parse_object *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff819cb480)
Location: drivers/acpi/acpica/dbinput.c:692
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff819cb480-ffffffff819cbec0: acpi_db_command_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_db_command_dispatch(char *input_buffer, struct acpi_walk_state *walk_state, union acpi_parse_object *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff81a128e0)
Location: drivers/acpi/acpica/dbinput.c:692
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff81a128e0-ffffffff81a13311: acpi_db_command_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_db_command_dispatch(char *input_buffer, struct acpi_walk_state *walk_state, union acpi_parse_object *op);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff81a5da70)
Location: drivers/acpi/acpica/dbinput.c:695
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
  - drivers/acpi/acpica/dbinput.c:acpi_db_command_dispatch
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff81a5da70-ffffffff81a5e4a1: acpi_db_command_dispatch (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_db_command_dispatch(char *input_buffer, struct acpi_walk_state *walk_state, union acpi_parse_object *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff81622ac0)
Location: drivers/acpi/acpica/dbinput.c:672
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff81622adf-ffffffff8162320f: acpi_db_command_dispatch.part.0 (STB_LOCAL)
ffffffff81622ac0-ffffffff81622adf: acpi_db_command_dispatch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_db_command_dispatch(char *input_buffer, struct acpi_walk_state *walk_state, union acpi_parse_object *op);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/dbinput.c (ffffffff8163c970)
Location: drivers/acpi/acpica/dbinput.c:672
Inline: True
Direct callers:
  - drivers/acpi/acpica/dbinput.c:acpi_db_user_commands
  - drivers/acpi/acpica/dbxface.c:acpi_db_single_step
```
**Symbols:**

```
ffffffff8163c98f-ffffffff8163d0bf: acpi_db_command_dispatch.part.0 (STB_LOCAL)
ffffffff8163c970-ffffffff8163c98f: acpi_db_command_dispatch (STB_GLOBAL)
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
