# Function: <code>utf8_strncasecmp</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int utf8_strncasecmp(const struct unicode_map *um, const struct qstr *s1, const struct qstr *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff81404d90)
Location: fs/unicode/utf8-core.c:49
Inline: False
```
**Symbols:**

```
ffffffff81404d90-ffffffff81404e59: utf8_strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int utf8_strncasecmp(const struct unicode_map *um, const struct qstr *s1, const struct qstr *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff8141ed40)
Location: fs/unicode/utf8-core.c:49
Inline: False
```
**Symbols:**

```
ffffffff8141ed40-ffffffff8141ee09: utf8_strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int utf8_strncasecmp(const struct unicode_map *um, const struct qstr *s1, const struct qstr *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff8146d950)
Location: fs/unicode/utf8-core.c:49
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_ci_compare
```
**Symbols:**

```
ffffffff8146d950-ffffffff8146da19: utf8_strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int utf8_strncasecmp(const struct unicode_map *um, const struct qstr *s1, const struct qstr *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff81488050)
Location: fs/unicode/utf8-core.c:50
Inline: False
Direct callers:
  - fs/libfs.c:generic_ci_d_compare
  - fs/ext4/namei.c:ext4_ci_compare
```
**Symbols:**

```
ffffffff81488050-ffffffff81488119: utf8_strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int utf8_strncasecmp(const struct unicode_map *um, const struct qstr *s1, const struct qstr *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff8148da30)
Location: fs/unicode/utf8-core.c:50
Inline: False
Direct callers:
  - fs/libfs.c:generic_ci_d_compare
  - fs/ext4/namei.c:ext4_ci_compare
```
**Symbols:**

```
ffffffff8148da30-ffffffff8148daf7: utf8_strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int utf8_strncasecmp(const struct unicode_map *um, const struct qstr *s1, const struct qstr *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff814e54a0)
Location: fs/unicode/utf8-core.c:50
Inline: False
Direct callers:
  - fs/libfs.c:generic_ci_d_compare
  - fs/ext4/namei.c:ext4_ci_compare
```
**Symbols:**

```
ffffffff814e54a0-ffffffff814e5567: utf8_strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int utf8_strncasecmp(const struct unicode_map *um, const struct qstr *s1, const struct qstr *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff81573410)
Location: fs/unicode/utf8-core.c:46
Inline: False
Direct callers:
  - fs/libfs.c:generic_ci_d_compare
  - fs/ext4/namei.c:ext4_ci_compare
```
**Symbols:**

```
ffffffff81573410-ffffffff815734f8: utf8_strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int utf8_strncasecmp(const struct unicode_map *um, const struct qstr *s1, const struct qstr *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff816189d0)
Location: fs/unicode/utf8-core.c:46
Inline: False
Direct callers:
  - fs/libfs.c:generic_ci_d_compare
  - fs/ext4/namei.c:ext4_ci_compare
```
**Symbols:**

```
ffffffff816189d0-ffffffff81618ab8: utf8_strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int utf8_strncasecmp(const struct unicode_map *um, const struct qstr *s1, const struct qstr *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff81650a90)
Location: fs/unicode/utf8-core.c:46
Inline: False
Direct callers:
  - fs/libfs.c:generic_ci_d_compare
  - fs/ext4/namei.c:ext4_ci_compare
```
**Symbols:**

```
ffffffff81650a90-ffffffff81650b78: utf8_strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int utf8_strncasecmp(const struct unicode_map *um, const struct qstr *s1, const struct qstr *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff8168a070)
Location: fs/unicode/utf8-core.c:46
Inline: False
Direct callers:
  - fs/libfs.c:generic_ci_d_compare
  - fs/ext4/namei.c:ext4_ci_compare
```
**Symbols:**

```
ffffffff8168a070-ffffffff8168a158: utf8_strncasecmp (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int utf8_strncasecmp(const struct unicode_map *um, const struct qstr *s1, const struct qstr *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffff800010500f58)
Location: fs/unicode/utf8-core.c:49
Inline: False
```
**Symbols:**

```
ffff800010500f58-ffff800010501030: utf8_strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int utf8_strncasecmp(const struct unicode_map *um, const struct qstr *s1, const struct qstr *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (c06bdbf4)
Location: fs/unicode/utf8-core.c:49
Inline: False
```
**Symbols:**

```
c06bdbf4-c06bdcd0: utf8_strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int utf8_strncasecmp(const struct unicode_map *um, const struct qstr *s1, const struct qstr *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (c0000000006451a0)
Location: fs/unicode/utf8-core.c:49
Inline: False
```
**Symbols:**

```
c0000000006451a0-c0000000006452b0: utf8_strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int utf8_strncasecmp(const struct unicode_map *um, const struct qstr *s1, const struct qstr *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffe00036e66e)
Location: fs/unicode/utf8-core.c:49
Inline: False
```
**Symbols:**

```
ffffffe00036e66e-ffffffe00036e71a: utf8_strncasecmp (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int utf8_strncasecmp(const struct unicode_map *um, const struct qstr *s1, const struct qstr *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff81417320)
Location: fs/unicode/utf8-core.c:49
Inline: False
```
**Symbols:**

```
ffffffff81417320-ffffffff814173e9: utf8_strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int utf8_strncasecmp(const struct unicode_map *um, const struct qstr *s1, const struct qstr *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff81407da0)
Location: fs/unicode/utf8-core.c:49
Inline: False
```
**Symbols:**

```
ffffffff81407da0-ffffffff81407e69: utf8_strncasecmp (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int utf8_strncasecmp(const struct unicode_map *um, const struct qstr *s1, const struct qstr *s2);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-core.c (ffffffff8142a300)
Location: fs/unicode/utf8-core.c:49
Inline: False
```
**Symbols:**

```
ffffffff8142a300-ffffffff8142a3c9: utf8_strncasecmp (STB_GLOBAL)
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
