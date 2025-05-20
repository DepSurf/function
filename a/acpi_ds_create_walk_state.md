# Function: <code>acpi_ds_create_walk_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct acpi_walk_state *acpi_ds_create_walk_state(acpi_owner_id owner_id, union acpi_parse_object *origin, union acpi_operand_object *method_desc, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff8148fb5f)
Location: drivers/acpi/acpica/dswstate.c:540
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff8148fb5f-ffffffff8148fc08: acpi_ds_create_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct acpi_walk_state *acpi_ds_create_walk_state(acpi_owner_id owner_id, union acpi_parse_object *origin, union acpi_operand_object *method_desc, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff814de963)
Location: drivers/acpi/acpica/dswstate.c:540
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff814de963-ffffffff814dea0c: acpi_ds_create_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct acpi_walk_state *acpi_ds_create_walk_state(acpi_owner_id owner_id, union acpi_parse_object *origin, union acpi_operand_object *method_desc, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff8150122b)
Location: drivers/acpi/acpica/dswstate.c:540
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff8150122b-ffffffff815012d4: acpi_ds_create_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct acpi_walk_state *acpi_ds_create_walk_state(acpi_owner_id owner_id, union acpi_parse_object *origin, union acpi_operand_object *method_desc, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff81511706)
Location: drivers/acpi/acpica/dswstate.c:540
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff81511706-ffffffff815117a9: acpi_ds_create_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct acpi_walk_state *acpi_ds_create_walk_state(acpi_owner_id owner_id, union acpi_parse_object *origin, union acpi_operand_object *method_desc, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff8155906d)
Location: drivers/acpi/acpica/dswstate.c:540
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
  - drivers/acpi/acpica/dbmethod.c:acpi_db_disassemble_method
```
**Symbols:**

```
ffffffff8155906d-ffffffff81559169: acpi_ds_create_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct acpi_walk_state *acpi_ds_create_walk_state(acpi_owner_id owner_id, union acpi_parse_object *origin, union acpi_operand_object *method_desc, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff8158fb88)
Location: drivers/acpi/acpica/dswstate.c:506
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
  - drivers/acpi/acpica/dbmethod.c:acpi_db_disassemble_method
```
**Symbols:**

```
ffffffff8158fb88-ffffffff8158fc84: acpi_ds_create_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct acpi_walk_state *acpi_ds_create_walk_state(acpi_owner_id owner_id, union acpi_parse_object *origin, union acpi_operand_object *method_desc, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff815a820d)
Location: drivers/acpi/acpica/dswstate.c:506
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff815a820d-ffffffff815a8309: acpi_ds_create_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct acpi_walk_state *acpi_ds_create_walk_state(acpi_owner_id owner_id, union acpi_parse_object *origin, union acpi_operand_object *method_desc, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff815d996c)
Location: drivers/acpi/acpica/dswstate.c:506
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff815d996c-ffffffff815d9a68: acpi_ds_create_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct acpi_walk_state *acpi_ds_create_walk_state(acpi_owner_id owner_id, union acpi_parse_object *origin, union acpi_operand_object *method_desc, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff815fac24)
Location: drivers/acpi/acpica/dswstate.c:506
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff815fac24-ffffffff815fad21: acpi_ds_create_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct acpi_walk_state *acpi_ds_create_walk_state(acpi_owner_id owner_id, union acpi_parse_object *origin, union acpi_operand_object *method_desc, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff816a6d46)
Location: drivers/acpi/acpica/dswstate.c:506
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff816a6d46-ffffffff816a6e43: acpi_ds_create_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct acpi_walk_state *acpi_ds_create_walk_state(acpi_owner_id owner_id, union acpi_parse_object *origin, union acpi_operand_object *method_desc, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff816c453c)
Location: drivers/acpi/acpica/dswstate.c:506
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff816c453c-ffffffff816c4639: acpi_ds_create_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct acpi_walk_state *acpi_ds_create_walk_state(acpi_owner_id owner_id, union acpi_parse_object *origin, union acpi_operand_object *method_desc, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff816a65cf)
Location: drivers/acpi/acpica/dswstate.c:506
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff816a65cf-ffffffff816a66cc: acpi_ds_create_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct acpi_walk_state *acpi_ds_create_walk_state(acpi_owner_id owner_id, union acpi_parse_object *origin, union acpi_operand_object *method_desc, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff8171d0c2)
Location: drivers/acpi/acpica/dswstate.c:506
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff8171d0c2-ffffffff8171d1bf: acpi_ds_create_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct acpi_walk_state *acpi_ds_create_walk_state(acpi_owner_id owner_id, union acpi_parse_object *origin, union acpi_operand_object *method_desc, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff8184d0cd)
Location: drivers/acpi/acpica/dswstate.c:506
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff8184d0cd-ffffffff8184d1d8: acpi_ds_create_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct acpi_walk_state *acpi_ds_create_walk_state(acpi_owner_id owner_id, union acpi_parse_object *origin, union acpi_operand_object *method_desc, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff81986080)
Location: drivers/acpi/acpica/dswstate.c:506
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff81986080-ffffffff819861ca: acpi_ds_create_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct acpi_walk_state *acpi_ds_create_walk_state(acpi_owner_id owner_id, union acpi_parse_object *origin, union acpi_operand_object *method_desc, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff819ccab0)
Location: drivers/acpi/acpica/dswstate.c:506
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff819ccab0-ffffffff819ccc15: acpi_ds_create_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct acpi_walk_state *acpi_ds_create_walk_state(acpi_owner_id owner_id, union acpi_parse_object *origin, union acpi_operand_object *method_desc, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff81a17580)
Location: drivers/acpi/acpica/dswstate.c:506
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff81a17580-ffffffff81a176bc: acpi_ds_create_walk_state (STB_GLOBAL)
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
struct acpi_walk_state *acpi_ds_create_walk_state(acpi_owner_id owner_id, union acpi_parse_object *origin, union acpi_operand_object *method_desc, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffff8000107819e0)
Location: drivers/acpi/acpica/dswstate.c:506
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffff8000107819e0-ffff800010781a88: acpi_ds_create_walk_state (STB_GLOBAL)
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
struct acpi_walk_state *acpi_ds_create_walk_state(acpi_owner_id owner_id, union acpi_parse_object *origin, union acpi_operand_object *method_desc, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff815e5241)
Location: drivers/acpi/acpica/dswstate.c:506
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff815e5241-ffffffff815e52e5: acpi_ds_create_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct acpi_walk_state *acpi_ds_create_walk_state(acpi_owner_id owner_id, union acpi_parse_object *origin, union acpi_operand_object *method_desc, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff815d08ad)
Location: drivers/acpi/acpica/dswstate.c:506
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff815d08ad-ffffffff815d094c: acpi_ds_create_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct acpi_walk_state *acpi_ds_create_walk_state(acpi_owner_id owner_id, union acpi_parse_object *origin, union acpi_operand_object *method_desc, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff815eef04)
Location: drivers/acpi/acpica/dswstate.c:506
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff815eef04-ffffffff815ef001: acpi_ds_create_walk_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct acpi_walk_state *acpi_ds_create_walk_state(acpi_owner_id owner_id, union acpi_parse_object *origin, union acpi_operand_object *method_desc, struct acpi_thread_state *thread);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dswstate.c (ffffffff81608db4)
Location: drivers/acpi/acpica/dswstate.c:506
Inline: False
Direct callers:
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsargs.c:acpi_ds_execute_arguments
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_call_control_method
  - drivers/acpi/acpica/dsmethod.c:acpi_ds_auto_serialize_method
  - drivers/acpi/acpica/nsparse.c:acpi_ns_one_complete_parse
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_table
  - drivers/acpi/acpica/psxface.c:acpi_ps_execute_method
```
**Symbols:**

```
ffffffff81608db4-ffffffff81608eb1: acpi_ds_create_walk_state (STB_GLOBAL)
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
