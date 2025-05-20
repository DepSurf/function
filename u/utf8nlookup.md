# Function: <code>utf8nlookup</code>

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
utf8leaf_t *utf8nlookup(const struct utf8data *data, unsigned char *hangul, const char *s, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81403f70)
Location: fs/unicode/utf8-norm.c:319
Inline: False
Direct callers:
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8nagemin
  - fs/unicode/utf8-norm.c:utf8agemin
```
**Symbols:**

```
ffffffff81403f70-ffffffff81404187: utf8nlookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
utf8leaf_t *utf8nlookup(const struct utf8data *data, unsigned char *hangul, const char *s, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff8141df20)
Location: fs/unicode/utf8-norm.c:319
Inline: False
Direct callers:
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8nagemin
  - fs/unicode/utf8-norm.c:utf8agemin
```
**Symbols:**

```
ffffffff8141df20-ffffffff8141e137: utf8nlookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
utf8leaf_t *utf8nlookup(const struct utf8data *data, unsigned char *hangul, const char *s, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff8146cc10)
Location: fs/unicode/utf8-norm.c:319
Inline: False
Direct callers:
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8nagemin
  - fs/unicode/utf8-norm.c:utf8agemin
```
**Symbols:**

```
ffffffff8146cc10-ffffffff8146cd0a: utf8nlookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
utf8leaf_t *utf8nlookup(const struct utf8data *data, unsigned char *hangul, const char *s, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff814872f0)
Location: fs/unicode/utf8-norm.c:319
Inline: False
Direct callers:
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8nagemin
  - fs/unicode/utf8-norm.c:utf8agemin
```
**Symbols:**

```
ffffffff814872f0-ffffffff814873ea: utf8nlookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
utf8leaf_t *utf8nlookup(const struct utf8data *data, unsigned char *hangul, const char *s, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff8148cc10)
Location: fs/unicode/utf8-norm.c:319
Inline: False
Direct callers:
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8nagemin
  - fs/unicode/utf8-norm.c:utf8agemin
```
**Symbols:**

```
ffffffff8148cc10-ffffffff8148ce20: utf8nlookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
utf8leaf_t *utf8nlookup(const struct utf8data *data, unsigned char *hangul, const char *s, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff814e4490)
Location: fs/unicode/utf8-norm.c:319
Inline: False
Direct callers:
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8nagemin
  - fs/unicode/utf8-norm.c:utf8agemin
```
**Symbols:**

```
ffffffff814e4490-ffffffff814e46a0: utf8nlookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
utf8leaf_t *utf8nlookup(const struct unicode_map *um, enum utf8_normalization n, unsigned char *hangul, const char *s, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81572930)
Location: fs/unicode/utf8-norm.c:302
Inline: False
Direct callers:
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8nlen
```
**Symbols:**

```
ffffffff81572930-ffffffff81572b81: utf8nlookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
utf8leaf_t *utf8nlookup(const struct unicode_map *um, enum utf8_normalization n, unsigned char *hangul, const char *s, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81617e90)
Location: fs/unicode/utf8-norm.c:302
Inline: False
Direct callers:
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8nlen
```
**Symbols:**

```
ffffffff81617e90-ffffffff816180e1: utf8nlookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
utf8leaf_t *utf8nlookup(const struct unicode_map *um, enum utf8_normalization n, unsigned char *hangul, const char *s, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff8164ff60)
Location: fs/unicode/utf8-norm.c:302
Inline: False
Direct callers:
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8nlen
```
**Symbols:**

```
ffffffff8164ff60-ffffffff816501af: utf8nlookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
utf8leaf_t *utf8nlookup(const struct unicode_map *um, enum utf8_normalization n, unsigned char *hangul, const char *s, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81689540)
Location: fs/unicode/utf8-norm.c:302
Inline: False
Direct callers:
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8nlen
```
**Symbols:**

```
ffffffff81689540-ffffffff8168978f: utf8nlookup (STB_LOCAL)
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
utf8leaf_t *utf8nlookup(const struct utf8data *data, unsigned char *hangul, const char *s, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffff8000104fff40)
Location: fs/unicode/utf8-norm.c:319
Inline: False
Direct callers:
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8nagemin
  - fs/unicode/utf8-norm.c:utf8agemin
```
**Symbols:**

```
ffff8000104fff40-ffff800010500148: utf8nlookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
utf8leaf_t *utf8nlookup(const struct utf8data *data, unsigned char *hangul, const char *s, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (c06bccdc)
Location: fs/unicode/utf8-norm.c:319
Inline: False
Direct callers:
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8nagemin
  - fs/unicode/utf8-norm.c:utf8agemin
```
**Symbols:**

```
c06bccdc-c06bcecc: utf8nlookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
utf8leaf_t *utf8nlookup(const struct utf8data *data, unsigned char *hangul, const char *s, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (c000000000643c20)
Location: fs/unicode/utf8-norm.c:319
Inline: False
Direct callers:
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8nagemin
  - fs/unicode/utf8-norm.c:utf8agemin
```
**Symbols:**

```
c000000000643c20-c000000000643e50: utf8nlookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
utf8leaf_t *utf8nlookup(const struct utf8data *data, unsigned char *hangul, const char *s, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffe00036da16)
Location: fs/unicode/utf8-norm.c:319
Inline: False
Direct callers:
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8nagemin
  - fs/unicode/utf8-norm.c:utf8agemin
```
**Symbols:**

```
ffffffe00036da16-ffffffe00036dbda: utf8nlookup (STB_LOCAL)
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
utf8leaf_t *utf8nlookup(const struct utf8data *data, unsigned char *hangul, const char *s, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81416500)
Location: fs/unicode/utf8-norm.c:319
Inline: False
Direct callers:
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8nagemin
  - fs/unicode/utf8-norm.c:utf8agemin
```
**Symbols:**

```
ffffffff81416500-ffffffff81416717: utf8nlookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
utf8leaf_t *utf8nlookup(const struct utf8data *data, unsigned char *hangul, const char *s, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81406f80)
Location: fs/unicode/utf8-norm.c:319
Inline: False
Direct callers:
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8nagemin
  - fs/unicode/utf8-norm.c:utf8agemin
```
**Symbols:**

```
ffffffff81406f80-ffffffff81407197: utf8nlookup (STB_LOCAL)
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
utf8leaf_t *utf8nlookup(const struct utf8data *data, unsigned char *hangul, const char *s, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff814294e0)
Location: fs/unicode/utf8-norm.c:319
Inline: False
Direct callers:
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8byte
  - fs/unicode/utf8-norm.c:utf8nagemin
  - fs/unicode/utf8-norm.c:utf8agemin
```
**Symbols:**

```
ffffffff814294e0-ffffffff814296f7: utf8nlookup (STB_LOCAL)
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
<code>data, hangul, s, len</code> ➡️ <code>um, n, hangul, s, len</code>
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
