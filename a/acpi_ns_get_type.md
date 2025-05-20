# Function: <code>acpi_ns_get_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
acpi_object_type acpi_ns_get_type(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff8149ee9f)
Location: drivers/acpi/acpica/nsutils.c:109
Inline: False
Direct callers:
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffffffff8149ee9f-ffffffff8149eece: acpi_ns_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
acpi_object_type acpi_ns_get_type(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff814ee1b4)
Location: drivers/acpi/acpica/nsutils.c:109
Inline: False
Direct callers:
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffffffff814ee1b4-ffffffff814ee1e3: acpi_ns_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
acpi_object_type acpi_ns_get_type(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff81510c1c)
Location: drivers/acpi/acpica/nsutils.c:109
Inline: False
Direct callers:
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffffffff81510c1c-ffffffff81510c4b: acpi_ns_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
acpi_object_type acpi_ns_get_type(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff815212d0)
Location: drivers/acpi/acpica/nsutils.c:109
Inline: False
Direct callers:
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffffffff815212d0-ffffffff815212ff: acpi_ns_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
acpi_object_type acpi_ns_get_type(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff81575118)
Location: drivers/acpi/acpica/nsutils.c:109
Inline: False
Direct callers:
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffffffff81575118-ffffffff815751ae: acpi_ns_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
acpi_object_type acpi_ns_get_type(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff815ac08d)
Location: drivers/acpi/acpica/nsutils.c:75
Inline: False
Direct callers:
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffffffff815ac08d-ffffffff815ac123: acpi_ns_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
acpi_object_type acpi_ns_get_type(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff815c5084)
Location: drivers/acpi/acpica/nsutils.c:75
Inline: False
Direct callers:
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_exec_module_code_list
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffffffff815c5084-ffffffff815c511a: acpi_ns_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
acpi_object_type acpi_ns_get_type(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff815f696d)
Location: drivers/acpi/acpica/nsutils.c:75
Inline: False
Direct callers:
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffffffff815f696d-ffffffff815f6a03: acpi_ns_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
acpi_object_type acpi_ns_get_type(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff81617e13)
Location: drivers/acpi/acpica/nsutils.c:75
Inline: False
Direct callers:
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffffffff81617e13-ffffffff81617ea9: acpi_ns_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_object_type acpi_ns_get_type(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff816c434b)
Location: drivers/acpi/acpica/nsutils.c:75
Inline: False
Direct callers:
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffffffff816c434b-ffffffff816c43e1: acpi_ns_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_object_type acpi_ns_get_type(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff816e238c)
Location: drivers/acpi/acpica/nsutils.c:75
Inline: False
Direct callers:
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffffffff816e238c-ffffffff816e2422: acpi_ns_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_object_type acpi_ns_get_type(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff816c427c)
Location: drivers/acpi/acpica/nsutils.c:75
Inline: False
Direct callers:
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffffffff816c427c-ffffffff816c4312: acpi_ns_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_object_type acpi_ns_get_type(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff8173b5b0)
Location: drivers/acpi/acpica/nsutils.c:75
Inline: False
Direct callers:
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffffffff8173b5b0-ffffffff8173b646: acpi_ns_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_object_type acpi_ns_get_type(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff8186cc01)
Location: drivers/acpi/acpica/nsutils.c:75
Inline: False
Direct callers:
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffffffff8186cc01-ffffffff8186cca6: acpi_ns_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_object_type acpi_ns_get_type(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff819ac5e0)
Location: drivers/acpi/acpica/nsutils.c:75
Inline: False
Direct callers:
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffffffff819ac5e0-ffffffff819ac69b: acpi_ns_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_object_type acpi_ns_get_type(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff819f34a0)
Location: drivers/acpi/acpica/nsutils.c:75
Inline: False
Direct callers:
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffffffff819f34a0-ffffffff819f355b: acpi_ns_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_object_type acpi_ns_get_type(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff81a3e2c0)
Location: drivers/acpi/acpica/nsutils.c:75
Inline: False
Direct callers:
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffffffff81a3e2c0-ffffffff81a3e37b: acpi_ns_get_type (STB_GLOBAL)
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
acpi_object_type acpi_ns_get_type(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffff80001078feb0)
Location: drivers/acpi/acpica/nsutils.c:75
Inline: False
Direct callers:
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffff80001078feb0-ffff80001078fefc: acpi_ns_get_type (STB_GLOBAL)
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
acpi_object_type acpi_ns_get_type(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff815f58de)
Location: drivers/acpi/acpica/nsutils.c:75
Inline: False
Direct callers:
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffffffff815f58de-ffffffff815f590d: acpi_ns_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
acpi_object_type acpi_ns_get_type(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff815e0e69)
Location: drivers/acpi/acpica/nsutils.c:75
Inline: False
Direct callers:
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffffffff815e0e69-ffffffff815e0e98: acpi_ns_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
acpi_object_type acpi_ns_get_type(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff8160c0f3)
Location: drivers/acpi/acpica/nsutils.c:75
Inline: False
Direct callers:
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffffffff8160c0f3-ffffffff8160c189: acpi_ns_get_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
acpi_object_type acpi_ns_get_type(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsutils.c (ffffffff81625fa3)
Location: drivers/acpi/acpica/nsutils.c:75
Inline: False
Direct callers:
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exprep.c:acpi_ex_prep_field_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresnte.c:acpi_ex_resolve_node_to_value
  - drivers/acpi/acpica/exresolv.c:acpi_ex_resolve_multiple
  - drivers/acpi/acpica/exstore.c:acpi_ex_store_object_to_node
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nseval.c:acpi_ns_evaluate
  - drivers/acpi/acpica/nsinit.c:acpi_ns_init_one_object
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_one_scope
  - drivers/acpi/acpica/utcopy.c:acpi_ut_copy_isimple_to_esimple
```
**Symbols:**

```
ffffffff81625fa3-ffffffff81626039: acpi_ns_get_type (STB_GLOBAL)
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
