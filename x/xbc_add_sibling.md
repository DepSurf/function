# Function: <code>xbc_add_sibling</code>

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
struct xbc_node *xbc_add_sibling(char *data, u32 flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff82d09b74)
Location: lib/bootconfig.c:362
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_parse_kv
  - lib/bootconfig.c:xbc_parse_kv
  - lib/bootconfig.c:__xbc_add_key
```
**Symbols:**

```
ffffffff82d09b74-ffffffff82d09c53: xbc_add_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct xbc_node *xbc_add_sibling(char *data, u32 flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff82ff7140)
Location: lib/bootconfig.c:370
Inline: False
Direct callers:
  - lib/bootconfig.c:xbc_parse_kv
  - lib/bootconfig.c:xbc_parse_kv
  - lib/bootconfig.c:__xbc_add_key
```
**Symbols:**

```
ffffffff82ff7140-ffffffff82ff7213: xbc_add_sibling (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct xbc_node *xbc_add_sibling(char *data, u32 flag);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff83201e25)
Location: lib/bootconfig.c:370
Inline: False
Direct callers:
  - lib/bootconfig.c:__xbc_add_key
  - lib/bootconfig.c:xbc_init
  - lib/bootconfig.c:xbc_init
```
**Symbols:**

```
ffffffff83201e25-ffffffff83201ef8: xbc_add_sibling (STB_LOCAL)
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
In lib/bootconfig.c (ffffffff832e965f)
Location: lib/bootconfig.c:415
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_add_child
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
In lib/bootconfig.c (ffffffff834a0f52)
Location: lib/bootconfig.c:480
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_add_child
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
In lib/bootconfig.c (ffffffff83eda6c9)
Location: lib/bootconfig.c:480
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_parse_tree
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
In lib/bootconfig.c (ffffffff836fff51)
Location: lib/bootconfig.c:480
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_parse_kv
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
In lib/bootconfig.c (ffffffff83933791)
Location: lib/bootconfig.c:480
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_parse_kv
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
</ul>
