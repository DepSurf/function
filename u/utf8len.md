# Function: <code>utf8len</code>

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
ssize_t utf8len(const struct utf8data *data, const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81404910)
Location: fs/unicode/utf8-norm.c:520
Inline: True
```
**Symbols:**

```
ffffffff81404910-ffffffff81404a09: utf8len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t utf8len(const struct utf8data *data, const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff8141e8c0)
Location: fs/unicode/utf8-norm.c:520
Inline: True
```
**Symbols:**

```
ffffffff8141e8c0-ffffffff8141e9b9: utf8len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t utf8len(const struct utf8data *data, const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff8146d4b0)
Location: fs/unicode/utf8-norm.c:520
Inline: True
```
**Symbols:**

```
ffffffff8146d4b0-ffffffff8146d5a0: utf8len.part.0 (STB_LOCAL)
ffffffff8146d5a0-ffffffff8146d5bd: utf8len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t utf8len(const struct utf8data *data, const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81487b90)
Location: fs/unicode/utf8-norm.c:520
Inline: True
```
**Symbols:**

```
ffffffff81487b90-ffffffff81487c8e: utf8len.part.0 (STB_LOCAL)
ffffffff81487c90-ffffffff81487cad: utf8len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t utf8len(const struct utf8data *data, const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff8148d5b0)
Location: fs/unicode/utf8-norm.c:520
Inline: True
```
**Symbols:**

```
ffffffff8148d5b0-ffffffff8148d6b0: utf8len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t utf8len(const struct utf8data *data, const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff814e4ee0)
Location: fs/unicode/utf8-norm.c:520
Inline: True
```
**Symbols:**

```
ffffffff814e4ee0-ffffffff814e5005: utf8len (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
ssize_t utf8len(const struct utf8data *data, const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffff8000105009a8)
Location: fs/unicode/utf8-norm.c:520
Inline: True
```
**Symbols:**

```
ffff8000105009a8-ffff800010500b0c: utf8len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ssize_t utf8len(const struct utf8data *data, const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (c06bd6f0)
Location: fs/unicode/utf8-norm.c:520
Inline: True
```
**Symbols:**

```
c06bd6f0-c06bd808: utf8len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
ssize_t utf8len(const struct utf8data *data, const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (c000000000644a90)
Location: fs/unicode/utf8-norm.c:520
Inline: True
```
**Symbols:**

```
c000000000644a90-c000000000644c58: utf8len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
ssize_t utf8len(const struct utf8data *data, const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffe00036e2a2)
Location: fs/unicode/utf8-norm.c:520
Inline: True
```
**Symbols:**

```
ffffffe00036e2a2-ffffffe00036e38a: utf8len (STB_GLOBAL)
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
ssize_t utf8len(const struct utf8data *data, const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81416ea0)
Location: fs/unicode/utf8-norm.c:520
Inline: True
```
**Symbols:**

```
ffffffff81416ea0-ffffffff81416f99: utf8len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ssize_t utf8len(const struct utf8data *data, const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81407920)
Location: fs/unicode/utf8-norm.c:520
Inline: True
```
**Symbols:**

```
ffffffff81407920-ffffffff81407a19: utf8len (STB_GLOBAL)
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
ssize_t utf8len(const struct utf8data *data, const char *s);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81429e80)
Location: fs/unicode/utf8-norm.c:520
Inline: True
```
**Symbols:**

```
ffffffff81429e80-ffffffff81429f79: utf8len (STB_GLOBAL)
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
