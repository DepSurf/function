# Function: <code>xbc_init_node</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xbc_init_node(struct xbc_node *node, char *data, u32 flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff82ff6f07)
Location: lib/bootconfig.c:334
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_parse_kv
  - lib/bootconfig.c:xbc_add_sibling
```
**Symbols:**

```
ffffffff82ff6f07-ffffffff82ff6f2e: xbc_init_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xbc_init_node(struct xbc_node *node, char *data, u32 flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83201bec)
Location: lib/bootconfig.c:334
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_add_sibling
  - lib/bootconfig.c:xbc_init
```
**Symbols:**

```
ffffffff83201bec-ffffffff83201c13: xbc_init_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xbc_init_node(struct xbc_node *node, char *data, u32 flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff832e9322)
Location: lib/bootconfig.c:344
Inline: False
Direct callers:
  - lib/bootconfig.c:__xbc_add_sibling
  - lib/bootconfig.c:xbc_init
```
**Symbols:**

```
ffffffff832e9322-ffffffff832e9349: xbc_init_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xbc_init_node(struct xbc_node *node, char *data, uint32_t flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff834a0bc5)
Location: lib/bootconfig.c:409
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:__xbc_add_sibling
```
**Symbols:**

```
ffffffff834a0bc5-ffffffff834a0bfe: xbc_init_node (STB_LOCAL)
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
In lib/bootconfig.c (ffffffff83eda71b)
Location: lib/bootconfig.c:409
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:__xbc_add_sibling
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
In lib/bootconfig.c (ffffffff836fffc3)
Location: lib/bootconfig.c:409
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_parse_kv
  - lib/bootconfig.c:__xbc_add_sibling
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
In lib/bootconfig.c (ffffffff83933803)
Location: lib/bootconfig.c:409
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_parse_kv
  - lib/bootconfig.c:__xbc_add_sibling
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32 flag</code> ➡️ <code>uint32_t flag</code>
</li>
</ul>
</details>
</li>
</ul>
