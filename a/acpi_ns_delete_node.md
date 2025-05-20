# Function: <code>acpi_ns_delete_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff8149c23c)
Location: drivers/acpi/acpica/nsalloc.c:106
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
```
**Symbols:**

```
ffffffff8149c23c-ffffffff8149c2a2: acpi_ns_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff814eb2bc)
Location: drivers/acpi/acpica/nsalloc.c:106
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
```
**Symbols:**

```
ffffffff814eb2bc-ffffffff814eb322: acpi_ns_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff8150db44)
Location: drivers/acpi/acpica/nsalloc.c:106
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
```
**Symbols:**

```
ffffffff8150db44-ffffffff8150dbaa: acpi_ns_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff8151e1f0)
Location: drivers/acpi/acpica/nsalloc.c:106
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
```
**Symbols:**

```
ffffffff8151e1f0-ffffffff8151e256: acpi_ns_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff8156f802)
Location: drivers/acpi/acpica/nsalloc.c:106
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
```
**Symbols:**

```
ffffffff8156f802-ffffffff8156f8b6: acpi_ns_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff815a64dd)
Location: drivers/acpi/acpica/nsalloc.c:70
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
```
**Symbols:**

```
ffffffff815a64dd-ffffffff815a6591: acpi_ns_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff815bf222)
Location: drivers/acpi/acpica/nsalloc.c:70
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
```
**Symbols:**

```
ffffffff815bf222-ffffffff815bf2d6: acpi_ns_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff815f0e7d)
Location: drivers/acpi/acpica/nsalloc.c:70
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
```
**Symbols:**

```
ffffffff815f0e7d-ffffffff815f0f5b: acpi_ns_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff8161230b)
Location: drivers/acpi/acpica/nsalloc.c:70
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
```
**Symbols:**

```
ffffffff8161230b-ffffffff816123e9: acpi_ns_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff816be838)
Location: drivers/acpi/acpica/nsalloc.c:70
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
```
**Symbols:**

```
ffffffff816be838-ffffffff816be916: acpi_ns_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff816dc3a6)
Location: drivers/acpi/acpica/nsalloc.c:70
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
```
**Symbols:**

```
ffffffff816dc3a6-ffffffff816dc484: acpi_ns_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff816be27e)
Location: drivers/acpi/acpica/nsalloc.c:70
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
```
**Symbols:**

```
ffffffff816be27e-ffffffff816be35c: acpi_ns_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff8173550d)
Location: drivers/acpi/acpica/nsalloc.c:70
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
```
**Symbols:**

```
ffffffff8173550d-ffffffff817355eb: acpi_ns_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff8186655d)
Location: drivers/acpi/acpica/nsalloc.c:70
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
```
**Symbols:**

```
ffffffff8186655d-ffffffff8186664f: acpi_ns_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff819a4a80)
Location: drivers/acpi/acpica/nsalloc.c:70
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
```
**Symbols:**

```
ffffffff819a4a80-ffffffff819a4b94: acpi_ns_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff819eb760)
Location: drivers/acpi/acpica/nsalloc.c:70
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
```
**Symbols:**

```
ffffffff819eb760-ffffffff819eb874: acpi_ns_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff81a36520)
Location: drivers/acpi/acpica/nsalloc.c:70
Inline: False
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
```
**Symbols:**

```
ffffffff81a36520-ffffffff81a36634: acpi_ns_delete_node (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffff80001078c1c4)
Location: drivers/acpi/acpica/nsalloc.c:70
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
```
**Symbols:**

```
ffff80001078c1c4-ffff80001078c258: acpi_ns_delete_node (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff815f2612)
Location: drivers/acpi/acpica/nsalloc.c:70
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
```
**Symbols:**

```
ffffffff815f2612-ffffffff815f2683: acpi_ns_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff815ddba0)
Location: drivers/acpi/acpica/nsalloc.c:70
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_delete_children
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
```
**Symbols:**

```
ffffffff815ddba0-ffffffff815ddc11: acpi_ns_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff816065eb)
Location: drivers/acpi/acpica/nsalloc.c:70
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
```
**Symbols:**

```
ffffffff816065eb-ffffffff816066c9: acpi_ns_delete_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void acpi_ns_delete_node(struct acpi_namespace_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff8162049b)
Location: drivers/acpi/acpica/nsalloc.c:70
Inline: True
Direct callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_remove_node
  - drivers/acpi/acpica/nsutils.c:acpi_ns_terminate
```
**Symbols:**

```
ffffffff8162049b-ffffffff81620579: acpi_ns_delete_node (STB_GLOBAL)
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
