# Function: <code>utf8ncursor</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int utf8ncursor(struct utf8cursor *u8c, const struct utf8data *data, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81404b95)
Location: fs/unicode/utf8-norm.c:583
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8cursor
  - fs/unicode/utf8-norm.c:utf8cursor
Direct callers:
  - fs/unicode/utf8-core.c:utf8_normalize
  - fs/unicode/utf8-core.c:utf8_casefold
  - fs/unicode/utf8-core.c:utf8_strncasecmp_folded
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncmp
  - fs/unicode/utf8-core.c:utf8_strncmp
```
**Symbols:**

```
ffffffff81404b20-ffffffff81404b89: utf8ncursor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int utf8ncursor(struct utf8cursor *u8c, const struct utf8data *data, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff8141eb45)
Location: fs/unicode/utf8-norm.c:583
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8cursor
  - fs/unicode/utf8-norm.c:utf8cursor
Direct callers:
  - fs/unicode/utf8-core.c:utf8_normalize
  - fs/unicode/utf8-core.c:utf8_casefold
  - fs/unicode/utf8-core.c:utf8_strncasecmp_folded
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncmp
  - fs/unicode/utf8-core.c:utf8_strncmp
```
**Symbols:**

```
ffffffff8141ead0-ffffffff8141eb39: utf8ncursor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int utf8ncursor(struct utf8cursor *u8c, const struct utf8data *data, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff8146d755)
Location: fs/unicode/utf8-norm.c:583
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8cursor
  - fs/unicode/utf8-norm.c:utf8cursor
Direct callers:
  - fs/unicode/utf8-core.c:utf8_normalize
  - fs/unicode/utf8-core.c:utf8_casefold
  - fs/unicode/utf8-core.c:utf8_strncasecmp_folded
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncmp
  - fs/unicode/utf8-core.c:utf8_strncmp
```
**Symbols:**

```
ffffffff8146d6e0-ffffffff8146d749: utf8ncursor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int utf8ncursor(struct utf8cursor *u8c, const struct utf8data *data, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81487e55)
Location: fs/unicode/utf8-norm.c:583
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8cursor
  - fs/unicode/utf8-norm.c:utf8cursor
Direct callers:
  - fs/unicode/utf8-core.c:utf8_normalize
  - fs/unicode/utf8-core.c:utf8_casefold_hash
  - fs/unicode/utf8-core.c:utf8_casefold
  - fs/unicode/utf8-core.c:utf8_strncasecmp_folded
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncmp
  - fs/unicode/utf8-core.c:utf8_strncmp
```
**Symbols:**

```
ffffffff81487de0-ffffffff81487e49: utf8ncursor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int utf8ncursor(struct utf8cursor *u8c, const struct utf8data *data, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff8148d835)
Location: fs/unicode/utf8-norm.c:583
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8cursor
  - fs/unicode/utf8-norm.c:utf8cursor
Direct callers:
  - fs/unicode/utf8-core.c:utf8_normalize
  - fs/unicode/utf8-core.c:utf8_casefold_hash
  - fs/unicode/utf8-core.c:utf8_casefold
  - fs/unicode/utf8-core.c:utf8_strncasecmp_folded
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncmp
  - fs/unicode/utf8-core.c:utf8_strncmp
```
**Symbols:**

```
ffffffff8148d7c0-ffffffff8148d829: utf8ncursor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int utf8ncursor(struct utf8cursor *u8c, const struct utf8data *data, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff814e52a5)
Location: fs/unicode/utf8-norm.c:583
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8cursor
  - fs/unicode/utf8-norm.c:utf8cursor
Direct callers:
  - fs/unicode/utf8-core.c:utf8_normalize
  - fs/unicode/utf8-core.c:utf8_casefold_hash
  - fs/unicode/utf8-core.c:utf8_casefold
  - fs/unicode/utf8-core.c:utf8_strncasecmp_folded
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncmp
  - fs/unicode/utf8-core.c:utf8_strncmp
```
**Symbols:**

```
ffffffff814e5230-ffffffff814e5299: utf8ncursor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int utf8ncursor(struct utf8cursor *u8c, const struct unicode_map *um, enum utf8_normalization n, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81572dd0)
Location: fs/unicode/utf8-norm.c:420
Inline: False
Direct callers:
  - fs/unicode/utf8-core.c:utf8_normalize
  - fs/unicode/utf8-core.c:utf8_casefold_hash
  - fs/unicode/utf8-core.c:utf8_casefold
  - fs/unicode/utf8-core.c:utf8_strncasecmp_folded
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncmp
  - fs/unicode/utf8-core.c:utf8_strncmp
```
**Symbols:**

```
ffffffff81572dd0-ffffffff81572e58: utf8ncursor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int utf8ncursor(struct utf8cursor *u8c, const struct unicode_map *um, enum utf8_normalization n, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81618360)
Location: fs/unicode/utf8-norm.c:420
Inline: False
Direct callers:
  - fs/unicode/utf8-core.c:utf8_normalize
  - fs/unicode/utf8-core.c:utf8_casefold_hash
  - fs/unicode/utf8-core.c:utf8_casefold
  - fs/unicode/utf8-core.c:utf8_strncasecmp_folded
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncmp
  - fs/unicode/utf8-core.c:utf8_strncmp
```
**Symbols:**

```
ffffffff81618360-ffffffff816183e3: utf8ncursor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int utf8ncursor(struct utf8cursor *u8c, const struct unicode_map *um, enum utf8_normalization n, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81650420)
Location: fs/unicode/utf8-norm.c:420
Inline: False
Direct callers:
  - fs/unicode/utf8-core.c:utf8_normalize
  - fs/unicode/utf8-core.c:utf8_casefold_hash
  - fs/unicode/utf8-core.c:utf8_casefold
  - fs/unicode/utf8-core.c:utf8_strncasecmp_folded
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncmp
  - fs/unicode/utf8-core.c:utf8_strncmp
```
**Symbols:**

```
ffffffff81650420-ffffffff816504a3: utf8ncursor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int utf8ncursor(struct utf8cursor *u8c, const struct unicode_map *um, enum utf8_normalization n, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81689a00)
Location: fs/unicode/utf8-norm.c:420
Inline: False
Direct callers:
  - fs/unicode/utf8-core.c:utf8_normalize
  - fs/unicode/utf8-core.c:utf8_casefold_hash
  - fs/unicode/utf8-core.c:utf8_casefold
  - fs/unicode/utf8-core.c:utf8_strncasecmp_folded
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncmp
  - fs/unicode/utf8-core.c:utf8_strncmp
```
**Symbols:**

```
ffffffff81689a00-ffffffff81689a83: utf8ncursor (STB_GLOBAL)
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
int utf8ncursor(struct utf8cursor *u8c, const struct utf8data *data, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffff800010500d2c)
Location: fs/unicode/utf8-norm.c:583
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8cursor
  - fs/unicode/utf8-norm.c:utf8cursor
Direct callers:
  - fs/unicode/utf8-core.c:utf8_normalize
  - fs/unicode/utf8-core.c:utf8_casefold
  - fs/unicode/utf8-core.c:utf8_strncasecmp_folded
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncmp
  - fs/unicode/utf8-core.c:utf8_strncmp
```
**Symbols:**

```
ffff800010500c88-ffff800010500d08: utf8ncursor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int utf8ncursor(struct utf8cursor *u8c, const struct utf8data *data, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (c06bd9bc)
Location: fs/unicode/utf8-norm.c:583
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8cursor
  - fs/unicode/utf8-norm.c:utf8cursor
Direct callers:
  - fs/unicode/utf8-core.c:utf8_normalize
  - fs/unicode/utf8-core.c:utf8_casefold
  - fs/unicode/utf8-core.c:utf8_strncasecmp_folded
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncmp
  - fs/unicode/utf8-core.c:utf8_strncmp
```
**Symbols:**

```
c06bd934-c06bd9a8: utf8ncursor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int utf8ncursor(struct utf8cursor *u8c, const struct utf8data *data, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (c000000000644ec8)
Location: fs/unicode/utf8-norm.c:583
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8cursor
  - fs/unicode/utf8-norm.c:utf8cursor
Direct callers:
  - fs/unicode/utf8-core.c:utf8_normalize
  - fs/unicode/utf8-core.c:utf8_casefold
  - fs/unicode/utf8-core.c:utf8_strncasecmp_folded
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncmp
  - fs/unicode/utf8-core.c:utf8_strncmp
```
**Symbols:**

```
c000000000644e40-c000000000644eb8: utf8ncursor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int utf8ncursor(struct utf8cursor *u8c, const struct utf8data *data, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffe00036e49c)
Location: fs/unicode/utf8-norm.c:583
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8cursor
  - fs/unicode/utf8-norm.c:utf8cursor
Direct callers:
  - fs/unicode/utf8-core.c:utf8_normalize
  - fs/unicode/utf8-core.c:utf8_casefold
  - fs/unicode/utf8-core.c:utf8_strncasecmp_folded
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncmp
  - fs/unicode/utf8-core.c:utf8_strncmp
```
**Symbols:**

```
ffffffe00036e220-ffffffe00036e2a2: utf8ncursor (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int utf8ncursor(struct utf8cursor *u8c, const struct utf8data *data, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81417125)
Location: fs/unicode/utf8-norm.c:583
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8cursor
  - fs/unicode/utf8-norm.c:utf8cursor
Direct callers:
  - fs/unicode/utf8-core.c:utf8_normalize
  - fs/unicode/utf8-core.c:utf8_casefold
  - fs/unicode/utf8-core.c:utf8_strncasecmp_folded
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncmp
  - fs/unicode/utf8-core.c:utf8_strncmp
```
**Symbols:**

```
ffffffff814170b0-ffffffff81417119: utf8ncursor (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int utf8ncursor(struct utf8cursor *u8c, const struct utf8data *data, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81407ba5)
Location: fs/unicode/utf8-norm.c:583
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8cursor
  - fs/unicode/utf8-norm.c:utf8cursor
Direct callers:
  - fs/unicode/utf8-core.c:utf8_normalize
  - fs/unicode/utf8-core.c:utf8_casefold
  - fs/unicode/utf8-core.c:utf8_strncasecmp_folded
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncmp
  - fs/unicode/utf8-core.c:utf8_strncmp
```
**Symbols:**

```
ffffffff81407b30-ffffffff81407b99: utf8ncursor (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int utf8ncursor(struct utf8cursor *u8c, const struct utf8data *data, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff8142a105)
Location: fs/unicode/utf8-norm.c:583
Inline: True
Inline callers:
  - fs/unicode/utf8-norm.c:utf8cursor
  - fs/unicode/utf8-norm.c:utf8cursor
Direct callers:
  - fs/unicode/utf8-core.c:utf8_normalize
  - fs/unicode/utf8-core.c:utf8_casefold
  - fs/unicode/utf8-core.c:utf8_strncasecmp_folded
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncasecmp
  - fs/unicode/utf8-core.c:utf8_strncmp
  - fs/unicode/utf8-core.c:utf8_strncmp
```
**Symbols:**

```
ffffffff8142a090-ffffffff8142a0f9: utf8ncursor (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct unicode_map *um</code>
</li>
<li>
<b>Param added. </b>
<code>enum utf8_normalization n</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct utf8data *data</code>
</li>
<li>
<b>Param reordered. </b>
<code>u8c, data, s, len</code> ➡️ <code>u8c, um, n, s, len</code>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
