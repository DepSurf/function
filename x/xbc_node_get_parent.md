# Function: <code>xbc_node_get_parent</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct xbc_node *xbc_node_get_parent(struct xbc_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff82d09b23)
Location: lib/bootconfig.c:77
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_find_next_leaf
```
**Symbols:**

```
ffffffff82d09b23-ffffffff82d09b3f: xbc_node_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct xbc_node *xbc_node_get_parent(struct xbc_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff82ff70ef)
Location: lib/bootconfig.c:77
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_find_next_leaf
```
**Symbols:**

```
ffffffff82ff70ef-ffffffff82ff710b: xbc_node_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xbc_node *xbc_node_get_parent(struct xbc_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83201dd4)
Location: lib/bootconfig.c:77
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_find_next_leaf
```
**Symbols:**

```
ffffffff83201dd4-ffffffff83201df0: xbc_node_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct xbc_node *xbc_node_get_parent(struct xbc_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff832e950a)
Location: lib/bootconfig.c:77
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_find_next_leaf
```
**Symbols:**

```
ffffffff832e950a-ffffffff832e9526: xbc_node_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct xbc_node *xbc_node_get_parent(struct xbc_node *node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff834a0dd1)
Location: lib/bootconfig.c:142
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_find_next_leaf
```
**Symbols:**

```
ffffffff834a0dd1-ffffffff834a0df4: xbc_node_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct xbc_node *xbc_node_get_parent(struct xbc_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83eda90b)
Location: lib/bootconfig.c:142
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_find_next_leaf
```
**Symbols:**

```
ffffffff83edaac0-ffffffff83edaae9: xbc_node_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct xbc_node *xbc_node_get_parent(struct xbc_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff8370043b)
Location: lib/bootconfig.c:142
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_find_next_leaf
```
**Symbols:**

```
ffffffff837005f0-ffffffff83700619: xbc_node_get_parent (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct xbc_node *xbc_node_get_parent(struct xbc_node *node);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83933c7b)
Location: lib/bootconfig.c:142
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_verify_tree
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_compose_key_after
  - lib/bootconfig.c:xbc_node_find_next_leaf
```
**Symbols:**

```
ffffffff83933e30-ffffffff83933e59: xbc_node_get_parent (STB_GLOBAL)
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
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
