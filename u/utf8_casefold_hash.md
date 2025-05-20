# Function: <code>utf8_casefold_hash</code>

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
int utf8_casefold_hash(const struct unicode_map *um, const void *salt, struct qstr *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff81488260)
Location: fs/unicode/utf8-core.c:128
Inline: False
Direct callers:
  - fs/libfs.c:generic_ci_d_hash
```
**Symbols:**

```
ffffffff81488260-ffffffff8148830e: utf8_casefold_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int utf8_casefold_hash(const struct unicode_map *um, const void *salt, struct qstr *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff8148dc40)
Location: fs/unicode/utf8-core.c:128
Inline: False
Direct callers:
  - fs/libfs.c:generic_ci_d_hash
```
**Symbols:**

```
ffffffff8148dc40-ffffffff8148dcee: utf8_casefold_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int utf8_casefold_hash(const struct unicode_map *um, const void *salt, struct qstr *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff814e56b0)
Location: fs/unicode/utf8-core.c:128
Inline: False
Direct callers:
  - fs/libfs.c:generic_ci_d_hash
```
**Symbols:**

```
ffffffff814e56b0-ffffffff814e575e: utf8_casefold_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int utf8_casefold_hash(const struct unicode_map *um, const void *salt, struct qstr *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff81573680)
Location: fs/unicode/utf8-core.c:121
Inline: False
Direct callers:
  - fs/libfs.c:generic_ci_d_hash
```
**Symbols:**

```
ffffffff81573680-ffffffff8157374f: utf8_casefold_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int utf8_casefold_hash(const struct unicode_map *um, const void *salt, struct qstr *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff81618c70)
Location: fs/unicode/utf8-core.c:121
Inline: False
Direct callers:
  - fs/libfs.c:generic_ci_d_hash
```
**Symbols:**

```
ffffffff81618c70-ffffffff81618d3f: utf8_casefold_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int utf8_casefold_hash(const struct unicode_map *um, const void *salt, struct qstr *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff81650d30)
Location: fs/unicode/utf8-core.c:121
Inline: False
Direct callers:
  - fs/libfs.c:generic_ci_d_hash
```
**Symbols:**

```
ffffffff81650d30-ffffffff81650dff: utf8_casefold_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int utf8_casefold_hash(const struct unicode_map *um, const void *salt, struct qstr *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff8168a310)
Location: fs/unicode/utf8-core.c:121
Inline: False
Direct callers:
  - fs/libfs.c:generic_ci_d_hash
```
**Symbols:**

```
ffffffff8168a310-ffffffff8168a3df: utf8_casefold_hash (STB_GLOBAL)
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
