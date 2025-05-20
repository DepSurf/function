# Function: <code>skip_comment</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
char *skip_comment(char *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff815e76d1)
Location: lib/bootconfig.c:408
Inline: True
Direct callers:
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:xbc_init
```
**Symbols:**

```
ffffffff815e76d1-ffffffff815e76fc: skip_comment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
char *skip_comment(char *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff81bf491f)
Location: lib/bootconfig.c:416
Inline: True
Direct callers:
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:xbc_init
```
**Symbols:**

```
ffffffff81bf491f-ffffffff81bf494a: skip_comment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
char *skip_comment(char *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff81be6817)
Location: lib/bootconfig.c:416
Inline: True
Direct callers:
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:xbc_init
```
**Symbols:**

```
ffffffff81be6817-ffffffff81be6842: skip_comment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
char *skip_comment(char *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff81cdf0b2)
Location: lib/bootconfig.c:446
Inline: True
Direct callers:
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:xbc_init
```
**Symbols:**

```
ffffffff81cdf0b2-ffffffff81cdf0dd: skip_comment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
char *skip_comment(char *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/bootconfig.c (ffffffff81ea49e7)
Location: lib/bootconfig.c:511
Inline: True
Direct callers:
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:__xbc_parse_value
```
**Symbols:**

```
ffffffff81ea49e7-ffffffff81ea4a1c: skip_comment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/bootconfig.c (ffffffff83eda570)
Location: lib/bootconfig.c:511
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:__xbc_parse_value
Direct callers:
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:__xbc_parse_value
```
**Symbols:**

```
ffffffff8189f760-ffffffff8189f77c: skip_comment.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/bootconfig.c (ffffffff83700147)
Location: lib/bootconfig.c:511
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:__xbc_parse_value
Direct callers:
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:__xbc_parse_value
```
**Symbols:**

```
ffffffff818e1d20-ffffffff818e1d3c: skip_comment.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/bootconfig.c (ffffffff83933987)
Location: lib/bootconfig.c:511
Inline: True
Inline callers:
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:__xbc_parse_value
Direct callers:
  - lib/bootconfig.c:xbc_parse_tree
  - lib/bootconfig.c:__xbc_parse_value
  - lib/bootconfig.c:__xbc_parse_value
```
**Symbols:**

```
ffffffff81928cb0-ffffffff81928ccc: skip_comment.part.0 (STB_LOCAL)
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
