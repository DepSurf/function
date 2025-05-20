# Function: <code>acpi_ns_search_parent_tree</code>

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
In drivers/acpi/acpica/nssearch.c (ffffffff8149ed5f)
Location: drivers/acpi/acpica/nssearch.c:199
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
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
In drivers/acpi/acpica/nssearch.c (ffffffff814ee086)
Location: drivers/acpi/acpica/nssearch.c:199
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
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
In drivers/acpi/acpica/nssearch.c (ffffffff81510acf)
Location: drivers/acpi/acpica/nssearch.c:199
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
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
In drivers/acpi/acpica/nssearch.c (ffffffff81521187)
Location: drivers/acpi/acpica/nssearch.c:199
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
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
In drivers/acpi/acpica/nssearch.c (ffffffff81574d6d)
Location: drivers/acpi/acpica/nssearch.c:199
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
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
In drivers/acpi/acpica/nssearch.c (ffffffff815abcfd)
Location: drivers/acpi/acpica/nssearch.c:163
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
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
In drivers/acpi/acpica/nssearch.c (ffffffff815c4d03)
Location: drivers/acpi/acpica/nssearch.c:163
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
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
In drivers/acpi/acpica/nssearch.c (ffffffff815f65ea)
Location: drivers/acpi/acpica/nssearch.c:163
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
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
In drivers/acpi/acpica/nssearch.c (ffffffff81617a8f)
Location: drivers/acpi/acpica/nssearch.c:163
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
acpi_status acpi_ns_search_parent_tree(u32 target_name, struct acpi_namespace_node *node, acpi_object_type type, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nssearch.c (ffffffff816c3d8c)
Location: drivers/acpi/acpica/nssearch.c:163
Inline: False
Direct callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
```
**Symbols:**

```
ffffffff816c3d8c-ffffffff816c3f72: acpi_ns_search_parent_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
acpi_status acpi_ns_search_parent_tree(u32 target_name, struct acpi_namespace_node *node, acpi_object_type type, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nssearch.c (ffffffff816e1dde)
Location: drivers/acpi/acpica/nssearch.c:163
Inline: False
Direct callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
```
**Symbols:**

```
ffffffff816e1dde-ffffffff816e1fc4: acpi_ns_search_parent_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
acpi_status acpi_ns_search_parent_tree(u32 target_name, struct acpi_namespace_node *node, acpi_object_type type, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nssearch.c (ffffffff816c3cce)
Location: drivers/acpi/acpica/nssearch.c:163
Inline: False
Direct callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
```
**Symbols:**

```
ffffffff816c3cce-ffffffff816c3eb4: acpi_ns_search_parent_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
acpi_status acpi_ns_search_parent_tree(u32 target_name, struct acpi_namespace_node *node, acpi_object_type type, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nssearch.c (ffffffff8173b002)
Location: drivers/acpi/acpica/nssearch.c:163
Inline: False
Direct callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
```
**Symbols:**

```
ffffffff8173b002-ffffffff8173b1e8: acpi_ns_search_parent_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
acpi_status acpi_ns_search_parent_tree(u32 target_name, struct acpi_namespace_node *node, acpi_object_type type, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nssearch.c (ffffffff8186c611)
Location: drivers/acpi/acpica/nssearch.c:163
Inline: False
Direct callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
```
**Symbols:**

```
ffffffff8186c611-ffffffff8186c80b: acpi_ns_search_parent_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
acpi_status acpi_ns_search_parent_tree(u32 target_name, struct acpi_namespace_node *node, acpi_object_type type, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nssearch.c (ffffffff819abf40)
Location: drivers/acpi/acpica/nssearch.c:163
Inline: False
Direct callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
```
**Symbols:**

```
ffffffff819abf40-ffffffff819ac170: acpi_ns_search_parent_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
acpi_status acpi_ns_search_parent_tree(u32 target_name, struct acpi_namespace_node *node, acpi_object_type type, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nssearch.c (ffffffff819f2e00)
Location: drivers/acpi/acpica/nssearch.c:163
Inline: False
Direct callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
```
**Symbols:**

```
ffffffff819f2e00-ffffffff819f3030: acpi_ns_search_parent_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
acpi_status acpi_ns_search_parent_tree(u32 target_name, struct acpi_namespace_node *node, acpi_object_type type, struct acpi_namespace_node **return_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nssearch.c (ffffffff81a3dc20)
Location: drivers/acpi/acpica/nssearch.c:163
Inline: False
Direct callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
```
**Symbols:**

```
ffffffff81a3dc20-ffffffff81a3de50: acpi_ns_search_parent_tree (STB_LOCAL)
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
In drivers/acpi/acpica/nssearch.c (ffff80001078fcfc)
Location: drivers/acpi/acpica/nssearch.c:163
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
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
In drivers/acpi/acpica/nssearch.c (ffffffff815f5785)
Location: drivers/acpi/acpica/nssearch.c:163
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
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
In drivers/acpi/acpica/nssearch.c (ffffffff815e0d04)
Location: drivers/acpi/acpica/nssearch.c:163
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
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
In drivers/acpi/acpica/nssearch.c (ffffffff8160bd6f)
Location: drivers/acpi/acpica/nssearch.c:163
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
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
In drivers/acpi/acpica/nssearch.c (ffffffff81625c1f)
Location: drivers/acpi/acpica/nssearch.c:163
Inline: True
Inline callers:
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
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
