# Function: <code>acpi_db_set_output_destination</code>

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
void acpi_db_set_output_destination(u32 output_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbutils.c (ffffffff8158d3b9)
Location: drivers/acpi/acpica/dbutils.c:108
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
```
**Symbols:**

```
ffffffff8158d3b9-ffffffff8158d3ec: acpi_db_set_output_destination (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void acpi_db_set_output_destination(u32 output_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbutils.c (ffffffff815c46fd)
Location: drivers/acpi/acpica/dbutils.c:72
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
```
**Symbols:**

```
ffffffff815c46fd-ffffffff815c4730: acpi_db_set_output_destination (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void acpi_db_set_output_destination(u32 output_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbutils.c (ffffffff815ddc25)
Location: drivers/acpi/acpica/dbutils.c:72
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
```
**Symbols:**

```
ffffffff815ddc25-ffffffff815ddc58: acpi_db_set_output_destination (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void acpi_db_set_output_destination(u32 output_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbutils.c (ffffffff8160f730)
Location: drivers/acpi/acpica/dbutils.c:72
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
```
**Symbols:**

```
ffffffff8160f730-ffffffff8160f763: acpi_db_set_output_destination (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void acpi_db_set_output_destination(u32 output_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbutils.c (ffffffff81630bd9)
Location: drivers/acpi/acpica/dbutils.c:72
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
```
**Symbols:**

```
ffffffff81630bd9-ffffffff81630c0c: acpi_db_set_output_destination (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_db_set_output_destination(u32 output_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbutils.c (ffffffff816dd636)
Location: drivers/acpi/acpica/dbutils.c:72
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
```
**Symbols:**

```
ffffffff816dd636-ffffffff816dd669: acpi_db_set_output_destination (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_db_set_output_destination(u32 output_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbutils.c (ffffffff816fb6da)
Location: drivers/acpi/acpica/dbutils.c:72
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
```
**Symbols:**

```
ffffffff816fb6da-ffffffff816fb70d: acpi_db_set_output_destination (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_db_set_output_destination(u32 output_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbutils.c (ffffffff816dd4fe)
Location: drivers/acpi/acpica/dbutils.c:72
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
```
**Symbols:**

```
ffffffff816dd4fe-ffffffff816dd531: acpi_db_set_output_destination (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_db_set_output_destination(u32 output_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbutils.c (ffffffff817555ee)
Location: drivers/acpi/acpica/dbutils.c:72
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
```
**Symbols:**

```
ffffffff817555ee-ffffffff81755621: acpi_db_set_output_destination (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_db_set_output_destination(u32 output_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbutils.c (ffffffff81888647)
Location: drivers/acpi/acpica/dbutils.c:72
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
```
**Symbols:**

```
ffffffff81888647-ffffffff81888682: acpi_db_set_output_destination (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_db_set_output_destination(u32 output_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbutils.c (ffffffff819cead0)
Location: drivers/acpi/acpica/dbutils.c:72
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
```
**Symbols:**

```
ffffffff819cead0-ffffffff819ceb0a: acpi_db_set_output_destination (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_db_set_output_destination(u32 output_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbutils.c (ffffffff81a15fa0)
Location: drivers/acpi/acpica/dbutils.c:72
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
```
**Symbols:**

```
ffffffff81a15fa0-ffffffff81a15fda: acpi_db_set_output_destination (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_db_set_output_destination(u32 output_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbutils.c (ffffffff81a61180)
Location: drivers/acpi/acpica/dbutils.c:72
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
```
**Symbols:**

```
ffffffff81a61180-ffffffff81a611ba: acpi_db_set_output_destination (STB_GLOBAL)
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
<summary>In <code>gcp</code>: ✅</summary>

```c
void acpi_db_set_output_destination(u32 output_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbutils.c (ffffffff81624eb9)
Location: drivers/acpi/acpica/dbutils.c:72
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
```
**Symbols:**

```
ffffffff81624eb9-ffffffff81624eec: acpi_db_set_output_destination (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void acpi_db_set_output_destination(u32 output_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/dbutils.c (ffffffff8163ed69)
Location: drivers/acpi/acpica/dbutils.c:72
Inline: False
Direct callers:
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_resources
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbcmds.c:acpi_db_display_template
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_create_execution_threads
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbexec.c:acpi_db_execute
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_display_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_find_name_in_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_by_owner
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace_paths
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
  - drivers/acpi/acpica/dbnames.c:acpi_db_dump_namespace
```
**Symbols:**

```
ffffffff8163ed69-ffffffff8163ed9c: acpi_db_set_output_destination (STB_GLOBAL)
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
