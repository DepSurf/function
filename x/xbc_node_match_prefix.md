# Function: <code>xbc_node_match_prefix</code>

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
bool xbc_node_match_prefix(struct xbc_node *node, const char **prefix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff82d09c78)
Location: lib/bootconfig.c:126
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_node_find_child
```
**Symbols:**

```
ffffffff82d09c78-ffffffff82d09cdc: xbc_node_match_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool xbc_node_match_prefix(struct xbc_node *node, const char **prefix);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff82ff7238)
Location: lib/bootconfig.c:126
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_node_find_child
```
**Symbols:**

```
ffffffff82ff7238-ffffffff82ff729c: xbc_node_match_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff832022e7)
Location: lib/bootconfig.c:126
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_node_find_child
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff832e9a54)
Location: lib/bootconfig.c:126
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_node_find_subkey
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff834a16dc)
Location: lib/bootconfig.c:191
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_node_find_subkey
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83edac3a)
Location: lib/bootconfig.c:191
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_node_find_subkey
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff8370076a)
Location: lib/bootconfig.c:191
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_node_find_subkey
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83933faa)
Location: lib/bootconfig.c:191
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_node_find_subkey
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
</ul>
