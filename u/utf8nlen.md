# Function: <code>utf8nlen</code>

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
ssize_t utf8nlen(const struct utf8data *data, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81404a10)
Location: fs/unicode/utf8-norm.c:548
Inline: True
Direct callers:
  - fs/unicode/utf8-core.c:utf8_validate
```
**Symbols:**

```
ffffffff81404a10-ffffffff81404b18: utf8nlen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t utf8nlen(const struct utf8data *data, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff8141e9c0)
Location: fs/unicode/utf8-norm.c:548
Inline: True
Direct callers:
  - fs/unicode/utf8-core.c:utf8_validate
```
**Symbols:**

```
ffffffff8141e9c0-ffffffff8141eac8: utf8nlen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t utf8nlen(const struct utf8data *data, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff8146d5c0)
Location: fs/unicode/utf8-norm.c:548
Inline: True
Direct callers:
  - fs/unicode/utf8-core.c:utf8_validate
```
**Symbols:**

```
ffffffff8146d5c0-ffffffff8146d6b5: utf8nlen.part.0 (STB_LOCAL)
ffffffff8146d6c0-ffffffff8146d6dd: utf8nlen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t utf8nlen(const struct utf8data *data, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81487cb0)
Location: fs/unicode/utf8-norm.c:548
Inline: True
Direct callers:
  - fs/unicode/utf8-core.c:utf8_validate
```
**Symbols:**

```
ffffffff81487cb0-ffffffff81487db5: utf8nlen.part.0 (STB_LOCAL)
ffffffff81487dc0-ffffffff81487ddd: utf8nlen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t utf8nlen(const struct utf8data *data, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff8148d6b0)
Location: fs/unicode/utf8-norm.c:548
Inline: True
Direct callers:
  - fs/unicode/utf8-core.c:utf8_validate
```
**Symbols:**

```
ffffffff8148d6b0-ffffffff8148d7b8: utf8nlen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t utf8nlen(const struct utf8data *data, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff814e5100)
Location: fs/unicode/utf8-norm.c:548
Inline: True
Direct callers:
  - fs/unicode/utf8-core.c:utf8_validate
```
**Symbols:**

```
ffffffff814e5100-ffffffff814e522d: utf8nlen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t utf8nlen(const struct unicode_map *um, enum utf8_normalization n, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81572c00)
Location: fs/unicode/utf8-norm.c:386
Inline: False
Direct callers:
  - fs/unicode/utf8-core.c:utf8_validate
```
**Symbols:**

```
ffffffff81572c00-ffffffff81572dd0: utf8nlen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t utf8nlen(const struct unicode_map *um, enum utf8_normalization n, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81618180)
Location: fs/unicode/utf8-norm.c:386
Inline: False
Direct callers:
  - fs/unicode/utf8-core.c:utf8_validate
```
**Symbols:**

```
ffffffff81618180-ffffffff81618350: utf8nlen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t utf8nlen(const struct unicode_map *um, enum utf8_normalization n, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81650240)
Location: fs/unicode/utf8-norm.c:386
Inline: False
Direct callers:
  - fs/unicode/utf8-core.c:utf8_validate
```
**Symbols:**

```
ffffffff81650240-ffffffff8165040f: utf8nlen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t utf8nlen(const struct unicode_map *um, enum utf8_normalization n, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81689820)
Location: fs/unicode/utf8-norm.c:386
Inline: False
Direct callers:
  - fs/unicode/utf8-core.c:utf8_validate
```
**Symbols:**

```
ffffffff81689820-ffffffff816899ef: utf8nlen (STB_GLOBAL)
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
ssize_t utf8nlen(const struct utf8data *data, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffff800010500b10)
Location: fs/unicode/utf8-norm.c:548
Inline: True
Direct callers:
  - fs/unicode/utf8-core.c:utf8_validate
```
**Symbols:**

```
ffff800010500b10-ffff800010500c84: utf8nlen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ssize_t utf8nlen(const struct utf8data *data, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (c06bd808)
Location: fs/unicode/utf8-norm.c:548
Inline: True
Direct callers:
  - fs/unicode/utf8-core.c:utf8_validate
```
**Symbols:**

```
c06bd808-c06bd934: utf8nlen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
ssize_t utf8nlen(const struct utf8data *data, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (c000000000644c60)
Location: fs/unicode/utf8-norm.c:548
Inline: True
Direct callers:
  - fs/unicode/utf8-core.c:utf8_validate
```
**Symbols:**

```
c000000000644c60-c000000000644e40: utf8nlen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
ssize_t utf8nlen(const struct utf8data *data, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffe00036e38a)
Location: fs/unicode/utf8-norm.c:548
Inline: True
Direct callers:
  - fs/unicode/utf8-core.c:utf8_validate
```
**Symbols:**

```
ffffffe00036e38a-ffffffe00036e47e: utf8nlen (STB_GLOBAL)
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
ssize_t utf8nlen(const struct utf8data *data, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81416fa0)
Location: fs/unicode/utf8-norm.c:548
Inline: True
Direct callers:
  - fs/unicode/utf8-core.c:utf8_validate
```
**Symbols:**

```
ffffffff81416fa0-ffffffff814170a8: utf8nlen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ssize_t utf8nlen(const struct utf8data *data, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81407a20)
Location: fs/unicode/utf8-norm.c:548
Inline: True
Direct callers:
  - fs/unicode/utf8-core.c:utf8_validate
```
**Symbols:**

```
ffffffff81407a20-ffffffff81407b28: utf8nlen (STB_GLOBAL)
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
ssize_t utf8nlen(const struct utf8data *data, const char *s, size_t len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81429f80)
Location: fs/unicode/utf8-norm.c:548
Inline: True
Direct callers:
  - fs/unicode/utf8-core.c:utf8_validate
```
**Symbols:**

```
ffffffff81429f80-ffffffff8142a088: utf8nlen (STB_GLOBAL)
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
<code>data, s, len</code> ➡️ <code>um, n, s, len</code>
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
