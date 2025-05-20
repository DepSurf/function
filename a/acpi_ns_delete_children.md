# Function: <code>acpi_ns_delete_children</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_ns_delete_children(struct acpi_namespace_node *parent_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff8149c341)
Location: drivers/acpi/acpica/nsalloc.c:299
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
```
**Symbols:**

```
ffffffff8149c341-ffffffff8149c3a7: acpi_ns_delete_children (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_ns_delete_children(struct acpi_namespace_node *parent_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff814eb3c3)
Location: drivers/acpi/acpica/nsalloc.c:299
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
```
**Symbols:**

```
ffffffff814eb3c3-ffffffff814eb430: acpi_ns_delete_children (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_ns_delete_children(struct acpi_namespace_node *parent_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff8150dc4b)
Location: drivers/acpi/acpica/nsalloc.c:299
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
```
**Symbols:**

```
ffffffff8150dc4b-ffffffff8150dcb8: acpi_ns_delete_children (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void acpi_ns_delete_children(struct acpi_namespace_node *parent_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff8151e2f7)
Location: drivers/acpi/acpica/nsalloc.c:299
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
```
**Symbols:**

```
ffffffff8151e2f7-ffffffff8151e365: acpi_ns_delete_children (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_ns_delete_children(struct acpi_namespace_node *parent_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff8156fa74)
Location: drivers/acpi/acpica/nsalloc.c:299
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
```
**Symbols:**

```
ffffffff8156fa74-ffffffff8156fb38: acpi_ns_delete_children (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void acpi_ns_delete_children(struct acpi_namespace_node *parent_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff815a6753)
Location: drivers/acpi/acpica/nsalloc.c:263
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
```
**Symbols:**

```
ffffffff815a6753-ffffffff815a6817: acpi_ns_delete_children (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void acpi_ns_delete_children(struct acpi_namespace_node *parent_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff815bf498)
Location: drivers/acpi/acpica/nsalloc.c:263
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
```
**Symbols:**

```
ffffffff815bf498-ffffffff815bf55c: acpi_ns_delete_children (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void acpi_ns_delete_children(struct acpi_namespace_node *parent_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff815f111f)
Location: drivers/acpi/acpica/nsalloc.c:267
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
```
**Symbols:**

```
ffffffff815f111f-ffffffff815f11dc: acpi_ns_delete_children (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void acpi_ns_delete_children(struct acpi_namespace_node *parent_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff816125ae)
Location: drivers/acpi/acpica/nsalloc.c:267
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
```
**Symbols:**

```
ffffffff816125ae-ffffffff8161266b: acpi_ns_delete_children (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_ns_delete_children(struct acpi_namespace_node *parent_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff816beadb)
Location: drivers/acpi/acpica/nsalloc.c:267
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
```
**Symbols:**

```
ffffffff816beadb-ffffffff816beb98: acpi_ns_delete_children (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_ns_delete_children(struct acpi_namespace_node *parent_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff816dc64c)
Location: drivers/acpi/acpica/nsalloc.c:267
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
```
**Symbols:**

```
ffffffff816dc64c-ffffffff816dc709: acpi_ns_delete_children (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_ns_delete_children(struct acpi_namespace_node *parent_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff816be524)
Location: drivers/acpi/acpica/nsalloc.c:267
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
```
**Symbols:**

```
ffffffff816be524-ffffffff816be5e1: acpi_ns_delete_children (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_ns_delete_children(struct acpi_namespace_node *parent_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff817357b3)
Location: drivers/acpi/acpica/nsalloc.c:267
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
```
**Symbols:**

```
ffffffff817357b3-ffffffff81735870: acpi_ns_delete_children (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_ns_delete_children(struct acpi_namespace_node *parent_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff81866837)
Location: drivers/acpi/acpica/nsalloc.c:267
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
```
**Symbols:**

```
ffffffff81866837-ffffffff81866903: acpi_ns_delete_children (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_ns_delete_children(struct acpi_namespace_node *parent_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff819a4de0)
Location: drivers/acpi/acpica/nsalloc.c:267
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
```
**Symbols:**

```
ffffffff819a4de0-ffffffff819a4eb4: acpi_ns_delete_children (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_ns_delete_children(struct acpi_namespace_node *parent_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff819ebac0)
Location: drivers/acpi/acpica/nsalloc.c:267
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
```
**Symbols:**

```
ffffffff819ebac0-ffffffff819ebb94: acpi_ns_delete_children (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_ns_delete_children(struct acpi_namespace_node *parent_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff81a36880)
Location: drivers/acpi/acpica/nsalloc.c:267
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
```
**Symbols:**

```
ffffffff81a36880-ffffffff81a36954: acpi_ns_delete_children (STB_GLOBAL)
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
void acpi_ns_delete_children(struct acpi_namespace_node *parent_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffff80001078c350)
Location: drivers/acpi/acpica/nsalloc.c:267
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
```
**Symbols:**

```
ffff80001078c350-ffff80001078c3d8: acpi_ns_delete_children (STB_GLOBAL)
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
void acpi_ns_delete_children(struct acpi_namespace_node *parent_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff815f2721)
Location: drivers/acpi/acpica/nsalloc.c:267
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
```
**Symbols:**

```
ffffffff815f2721-ffffffff815f2788: acpi_ns_delete_children (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void acpi_ns_delete_children(struct acpi_namespace_node *parent_node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff815ddcaf)
Location: drivers/acpi/acpica/nsalloc.c:267
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
```
**Symbols:**

```
ffffffff815ddcaf-ffffffff815ddd16: acpi_ns_delete_children (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void acpi_ns_delete_children(struct acpi_namespace_node *parent_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff8160688e)
Location: drivers/acpi/acpica/nsalloc.c:267
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
```
**Symbols:**

```
ffffffff8160688e-ffffffff8160694b: acpi_ns_delete_children (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void acpi_ns_delete_children(struct acpi_namespace_node *parent_node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff8162073e)
Location: drivers/acpi/acpica/nsalloc.c:267
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_by_owner
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_namespace_subtree
  - drivers/acpi/acpica/nssearch.c:acpi_ns_search_and_enter
  - drivers/acpi/acpica/psobject.c:acpi_ps_complete_op
```
**Symbols:**

```
ffffffff8162073e-ffffffff816207fb: acpi_ns_delete_children (STB_GLOBAL)
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
