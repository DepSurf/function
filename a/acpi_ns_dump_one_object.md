# Function: <code>acpi_ns_dump_one_object</code>

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
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_ns_dump_one_object(acpi_handle obj_handle, u32 level, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/nsdump.c (ffffffff81570569)
Location: drivers/acpi/acpica/nsdump.c:174
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
**Symbols:**

```
ffffffff81570569-ffffffff81570b88: acpi_ns_dump_one_object.part.0 (STB_LOCAL)
ffffffff81570b88-ffffffff81570be5: acpi_ns_dump_one_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_ns_dump_one_object(acpi_handle obj_handle, u32 level, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/nsdump.c (ffffffff815a7254)
Location: drivers/acpi/acpica/nsdump.c:140
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
**Symbols:**

```
ffffffff815a7254-ffffffff815a7870: acpi_ns_dump_one_object.part.0 (STB_LOCAL)
ffffffff815a7870-ffffffff815a78cd: acpi_ns_dump_one_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_ns_dump_one_object(acpi_handle obj_handle, u32 level, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/nsdump.c (ffffffff815bffa4)
Location: drivers/acpi/acpica/nsdump.c:140
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
**Symbols:**

```
ffffffff815bffa4-ffffffff815c065b: acpi_ns_dump_one_object.part.0 (STB_LOCAL)
ffffffff815c065b-ffffffff815c06b8: acpi_ns_dump_one_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_ns_dump_one_object(acpi_handle obj_handle, u32 level, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/nsdump.c (ffffffff815f1c28)
Location: drivers/acpi/acpica/nsdump.c:140
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
**Symbols:**

```
ffffffff815f1c28-ffffffff815f22d0: acpi_ns_dump_one_object.part.0 (STB_LOCAL)
ffffffff815f22d0-ffffffff815f232d: acpi_ns_dump_one_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_ns_dump_one_object(acpi_handle obj_handle, u32 level, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/nsdump.c (ffffffff816130bc)
Location: drivers/acpi/acpica/nsdump.c:140
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
**Symbols:**

```
ffffffff816130bc-ffffffff81613767: acpi_ns_dump_one_object.part.0 (STB_LOCAL)
ffffffff81613767-ffffffff816137c4: acpi_ns_dump_one_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ns_dump_one_object(acpi_handle obj_handle, u32 level, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsdump.c (ffffffff816bf528)
Location: drivers/acpi/acpica/nsdump.c:140
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
**Symbols:**

```
ffffffff816bf528-ffffffff816bfc2f: acpi_ns_dump_one_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ns_dump_one_object(acpi_handle obj_handle, u32 level, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsdump.c (ffffffff816dd0a1)
Location: drivers/acpi/acpica/nsdump.c:140
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
**Symbols:**

```
ffffffff816dd0a1-ffffffff816dd7a8: acpi_ns_dump_one_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ns_dump_one_object(acpi_handle obj_handle, u32 level, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsdump.c (ffffffff816bef97)
Location: drivers/acpi/acpica/nsdump.c:140
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
**Symbols:**

```
ffffffff816bef97-ffffffff816bf69b: acpi_ns_dump_one_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ns_dump_one_object(acpi_handle obj_handle, u32 level, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsdump.c (ffffffff8173624c)
Location: drivers/acpi/acpica/nsdump.c:140
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
**Symbols:**

```
ffffffff8173624c-ffffffff81736950: acpi_ns_dump_one_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ns_dump_one_object(acpi_handle obj_handle, u32 level, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsdump.c (ffffffff81867426)
Location: drivers/acpi/acpica/nsdump.c:140
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
**Symbols:**

```
ffffffff81867426-ffffffff81867b26: acpi_ns_dump_one_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ns_dump_one_object(acpi_handle obj_handle, u32 level, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsdump.c (ffffffff819a5ca0)
Location: drivers/acpi/acpica/nsdump.c:140
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
**Symbols:**

```
ffffffff819a5ca0-ffffffff819a6452: acpi_ns_dump_one_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ns_dump_one_object(acpi_handle obj_handle, u32 level, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsdump.c (ffffffff819ec990)
Location: drivers/acpi/acpica/nsdump.c:140
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
**Symbols:**

```
ffffffff819ec990-ffffffff819ed176: acpi_ns_dump_one_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ns_dump_one_object(acpi_handle obj_handle, u32 level, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsdump.c (ffffffff81a37750)
Location: drivers/acpi/acpica/nsdump.c:140
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
**Symbols:**

```
ffffffff81a37750-ffffffff81a37f36: acpi_ns_dump_one_object (STB_GLOBAL)
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
acpi_status acpi_ns_dump_one_object(acpi_handle obj_handle, u32 level, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/nsdump.c (ffffffff8160739c)
Location: drivers/acpi/acpica/nsdump.c:140
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
**Symbols:**

```
ffffffff8160739c-ffffffff81607a47: acpi_ns_dump_one_object.part.0 (STB_LOCAL)
ffffffff81607a47-ffffffff81607aa4: acpi_ns_dump_one_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
acpi_status acpi_ns_dump_one_object(acpi_handle obj_handle, u32 level, void *context, void **return_value);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/acpi/acpica/nsdump.c (ffffffff8162124c)
Location: drivers/acpi/acpica/nsdump.c:140
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsdump.c:acpi_ns_dump_entry
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_for_specific_objects
  - drivers/acpi/acpica/dbnames.c:acpi_db_walk_and_match_name
```
**Symbols:**

```
ffffffff8162124c-ffffffff816218f7: acpi_ns_dump_one_object.part.0 (STB_LOCAL)
ffffffff816218f7-ffffffff81621954: acpi_ns_dump_one_object (STB_GLOBAL)
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
