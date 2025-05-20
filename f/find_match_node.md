# Function: <code>find_match_node</code>

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
struct xbc_node *find_match_node(struct xbc_node *node, char *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff82d09cdc)
Location: lib/bootconfig.c:528
Inline: False
Direct callers:
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:__xbc_add_key
```
**Symbols:**

```
ffffffff82d09cdc-ffffffff82d09d1a: find_match_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct xbc_node *find_match_node(struct xbc_node *node, char *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff82ff729c)
Location: lib/bootconfig.c:536
Inline: False
Direct callers:
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:__xbc_add_key
```
**Symbols:**

```
ffffffff82ff729c-ffffffff82ff72da: find_match_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xbc_node *find_match_node(struct xbc_node *node, char *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83201f1d)
Location: lib/bootconfig.c:536
Inline: False
Direct callers:
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:__xbc_add_key
```
**Symbols:**

```
ffffffff83201f1d-ffffffff83201f5b: find_match_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct xbc_node *find_match_node(struct xbc_node *node, char *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff832e969d)
Location: lib/bootconfig.c:569
Inline: False
Direct callers:
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:__xbc_add_key
```
**Symbols:**

```
ffffffff832e969d-ffffffff832e96db: find_match_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct xbc_node *find_match_node(struct xbc_node *node, char *k);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff834a0fa1)
Location: lib/bootconfig.c:634
Inline: False
Direct callers:
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:__xbc_add_key
```
**Symbols:**

```
ffffffff834a0fa1-ffffffff834a0fe7: find_match_node (STB_LOCAL)
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
In lib/bootconfig.c (0)
Location: lib/bootconfig.c:634
Inline: True
Inline callers:
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:__xbc_add_key
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
In lib/bootconfig.c (0)
Location: lib/bootconfig.c:634
Inline: True
Inline callers:
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:__xbc_add_key
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
In lib/bootconfig.c (0)
Location: lib/bootconfig.c:634
Inline: True
Inline callers:
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:__xbc_add_key
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
</ul>
