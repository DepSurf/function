# Function: <code>__xbc_add_sibling</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct xbc_node *__xbc_add_sibling(char *data, u32 flag, bool head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff832e957a)
Location: lib/bootconfig.c:388
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_add_child
  - lib/bootconfig.c:xbc_init
```
**Symbols:**

```
ffffffff832e957a-ffffffff832e965f: __xbc_add_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct xbc_node *__xbc_add_sibling(char *data, uint32_t flag, bool head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff834a0e5c)
Location: lib/bootconfig.c:453
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:xbc_add_child
```
**Symbols:**

```
ffffffff834a0e5c-ffffffff834a0f52: __xbc_add_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct xbc_node *__xbc_add_sibling(char *data, uint32_t flag, bool head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83ed9d60)
Location: lib/bootconfig.c:453
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:__xbc_add_key
```
**Symbols:**

```
ffffffff83ed9d60-ffffffff83ed9e83: __xbc_add_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct xbc_node *__xbc_add_sibling(char *data, uint32_t flag, bool head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff836ff820)
Location: lib/bootconfig.c:453
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_parse_kv
  - lib/bootconfig.c:xbc_parse_kv
  - lib/bootconfig.c:__xbc_add_key
```
**Symbols:**

```
ffffffff836ff820-ffffffff836ff943: __xbc_add_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct xbc_node *__xbc_add_sibling(char *data, uint32_t flag, bool head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83933060)
Location: lib/bootconfig.c:453
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_parse_kv
  - lib/bootconfig.c:xbc_parse_kv
  - lib/bootconfig.c:__xbc_add_key
```
**Symbols:**

```
ffffffff83933060-ffffffff83933183: __xbc_add_sibling (STB_LOCAL)
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
