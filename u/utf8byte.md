# Function: <code>utf8byte</code>

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
int utf8byte(struct utf8cursor *u8c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81404320)
Location: fs/unicode/utf8-norm.c:652
Inline: False
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
ffffffff81404320-ffffffff814046c7: utf8byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int utf8byte(struct utf8cursor *u8c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff8141e2d0)
Location: fs/unicode/utf8-norm.c:652
Inline: False
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
ffffffff8141e2d0-ffffffff8141e677: utf8byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int utf8byte(struct utf8cursor *u8c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff8146cea0)
Location: fs/unicode/utf8-norm.c:652
Inline: False
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
ffffffff8146cea0-ffffffff8146d267: utf8byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int utf8byte(struct utf8cursor *u8c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81487580)
Location: fs/unicode/utf8-norm.c:652
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
ffffffff81487580-ffffffff81487947: utf8byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int utf8byte(struct utf8cursor *u8c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff8148cfb0)
Location: fs/unicode/utf8-norm.c:652
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
ffffffff8148cfb0-ffffffff8148d370: utf8byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int utf8byte(struct utf8cursor *u8c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff814e4880)
Location: fs/unicode/utf8-norm.c:652
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
ffffffff814e4880-ffffffff814e4c7b: utf8byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int utf8byte(struct utf8cursor *u8c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81572e60)
Location: fs/unicode/utf8-norm.c:471
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
ffffffff81572e60-ffffffff815732e2: utf8byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int utf8byte(struct utf8cursor *u8c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81618400)
Location: fs/unicode/utf8-norm.c:471
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
ffffffff81618400-ffffffff81618878: utf8byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int utf8byte(struct utf8cursor *u8c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff816504c0)
Location: fs/unicode/utf8-norm.c:471
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
ffffffff816504c0-ffffffff81650938: utf8byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int utf8byte(struct utf8cursor *u8c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81689aa0)
Location: fs/unicode/utf8-norm.c:471
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
ffffffff81689aa0-ffffffff81689f18: utf8byte (STB_GLOBAL)
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
int utf8byte(struct utf8cursor *u8c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffff800010500328)
Location: fs/unicode/utf8-norm.c:652
Inline: False
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
ffff800010500328-ffff80001050069c: utf8byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int utf8byte(struct utf8cursor *u8c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (c06bd0b4)
Location: fs/unicode/utf8-norm.c:652
Inline: False
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
c06bd0b4-c06bd424: utf8byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int utf8byte(struct utf8cursor *u8c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (c000000000644160)
Location: fs/unicode/utf8-norm.c:652
Inline: False
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
c000000000644160-c00000000064465c: utf8byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int utf8byte(struct utf8cursor *u8c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffe00036dd4a)
Location: fs/unicode/utf8-norm.c:652
Inline: False
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
ffffffe00036dd4a-ffffffe00036dfe8: utf8byte (STB_GLOBAL)
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
int utf8byte(struct utf8cursor *u8c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff814168b0)
Location: fs/unicode/utf8-norm.c:652
Inline: False
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
ffffffff814168b0-ffffffff81416c57: utf8byte (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int utf8byte(struct utf8cursor *u8c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81407330)
Location: fs/unicode/utf8-norm.c:652
Inline: False
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
ffffffff81407330-ffffffff814076d7: utf8byte (STB_GLOBAL)
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
int utf8byte(struct utf8cursor *u8c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/unicode/utf8-norm.c (ffffffff81429890)
Location: fs/unicode/utf8-norm.c:652
Inline: False
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
ffffffff81429890-ffffffff81429c37: utf8byte (STB_GLOBAL)
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
