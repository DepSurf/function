# Function: <code>xbc_root_node</code>

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
struct xbc_node *xbc_root_node();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff82d09b00)
Location: lib/bootconfig.c:51
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_node_find_child
```
**Symbols:**

```
ffffffff82d09b00-ffffffff82d09b14: xbc_root_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct xbc_node *xbc_root_node();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff82ff70cc)
Location: lib/bootconfig.c:51
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_node_find_child
```
**Symbols:**

```
ffffffff82ff70cc-ffffffff82ff70e0: xbc_root_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xbc_node *xbc_root_node();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83201db1)
Location: lib/bootconfig.c:51
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_node_find_child
```
**Symbols:**

```
ffffffff83201db1-ffffffff83201dc5: xbc_root_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct xbc_node *xbc_root_node();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff832e94e7)
Location: lib/bootconfig.c:51
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_node_find_subkey
```
**Symbols:**

```
ffffffff832e94e7-ffffffff832e94fb: xbc_root_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct xbc_node *xbc_root_node();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff834a0da4)
Location: lib/bootconfig.c:116
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_node_find_subkey
```
**Symbols:**

```
ffffffff834a0da4-ffffffff834a0dbc: xbc_root_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct xbc_node *xbc_root_node();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83edacfb)
Location: lib/bootconfig.c:116
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_node_find_subkey
```
**Symbols:**

```
ffffffff83edaa60-ffffffff83edaa77: xbc_root_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct xbc_node *xbc_root_node();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff8370082b)
Location: lib/bootconfig.c:116
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_node_find_subkey
```
**Symbols:**

```
ffffffff83700590-ffffffff837005a7: xbc_root_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct xbc_node *xbc_root_node();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff8393406b)
Location: lib/bootconfig.c:116
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_node_find_subkey
```
**Symbols:**

```
ffffffff83933dd0-ffffffff83933de7: xbc_root_node (STB_GLOBAL)
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
