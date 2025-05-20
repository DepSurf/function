# Function: <code>kvasprintf_const</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
const char *kvasprintf_const(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff813f8d40)
Location: lib/kasprintf.c:40
Inline: True
Direct callers:
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff813f8d40-ffffffff813f8dcb: kvasprintf_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const char *kvasprintf_const(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff8143fb80)
Location: lib/kasprintf.c:42
Inline: False
Direct callers:
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff8143fb80-ffffffff8143fc0f: kvasprintf_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const char *kvasprintf_const(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff8145cc80)
Location: lib/kasprintf.c:42
Inline: False
Direct callers:
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff8145cc80-ffffffff8145cd0f: kvasprintf_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const char *kvasprintf_const(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff81461ec0)
Location: lib/kasprintf.c:42
Inline: False
Direct callers:
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff81461ec0-ffffffff81461f54: kvasprintf_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const char *kvasprintf_const(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff8148dda0)
Location: lib/kasprintf.c:43
Inline: False
Direct callers:
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff8148dda0-ffffffff8148de34: kvasprintf_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const char *kvasprintf_const(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff814c2b20)
Location: lib/kasprintf.c:43
Inline: False
Direct callers:
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff814c2b20-ffffffff814c2bb6: kvasprintf_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const char *kvasprintf_const(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff814d71d0)
Location: lib/kasprintf.c:43
Inline: False
Direct callers:
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff814d71d0-ffffffff814d7266: kvasprintf_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const char *kvasprintf_const(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff81503030)
Location: lib/kasprintf.c:43
Inline: False
Direct callers:
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff81503030-ffffffff815030c6: kvasprintf_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const char *kvasprintf_const(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff81520fd0)
Location: lib/kasprintf.c:43
Inline: False
Direct callers:
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff81520fd0-ffffffff81521066: kvasprintf_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char *kvasprintf_const(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff815841d0)
Location: lib/kasprintf.c:43
Inline: False
Direct callers:
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff815841d0-ffffffff81584266: kvasprintf_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char *kvasprintf_const(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff815a12e0)
Location: lib/kasprintf.c:43
Inline: False
Direct callers:
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff815a12e0-ffffffff815a1376: kvasprintf_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char *kvasprintf_const(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff815a8190)
Location: lib/kasprintf.c:43
Inline: False
Direct callers:
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff815a8190-ffffffff815a8226: kvasprintf_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char *kvasprintf_const(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff81611150)
Location: lib/kasprintf.c:43
Inline: False
Direct callers:
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff81611150-ffffffff816111e6: kvasprintf_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char *kvasprintf_const(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff816dd170)
Location: lib/kasprintf.c:43
Inline: False
Direct callers:
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff816dd170-ffffffff816dd214: kvasprintf_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *kvasprintf_const(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff817ccfd0)
Location: lib/kasprintf.c:43
Inline: False
Direct callers:
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff817ccfd0-ffffffff817cd074: kvasprintf_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *kvasprintf_const(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff8180b3e0)
Location: lib/kasprintf.c:43
Inline: False
Direct callers:
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff8180b3e0-ffffffff8180b484: kvasprintf_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *kvasprintf_const(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff81851bc0)
Location: lib/kasprintf.c:43
Inline: False
Direct callers:
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff81851bc0-ffffffff81851c64: kvasprintf_const (STB_GLOBAL)
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
const char *kvasprintf_const(gfp_t gfp, const char *fmt, va_list ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffff80001062a630)
Location: lib/kasprintf.c:43
Inline: False
Direct callers:
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffff80001062a630-ffff80001062a6fc: kvasprintf_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const char *kvasprintf_const(gfp_t gfp, const char *fmt, va_list ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (c07d1860)
Location: lib/kasprintf.c:43
Inline: False
Direct callers:
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
c07d1860-c07d18e4: kvasprintf_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const char *kvasprintf_const(gfp_t gfp, const char *fmt, va_list ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (c0000000007cc610)
Location: lib/kasprintf.c:43
Inline: False
Direct callers:
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
c0000000007cc610-c0000000007cc704: kvasprintf_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const char *kvasprintf_const(gfp_t gfp, const char *fmt, va_list ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffe00045b006)
Location: lib/kasprintf.c:43
Inline: False
Direct callers:
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffe00045b006-ffffffe00045b08a: kvasprintf_const (STB_GLOBAL)
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
const char *kvasprintf_const(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff815195b0)
Location: lib/kasprintf.c:43
Inline: False
Direct callers:
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff815195b0-ffffffff81519646: kvasprintf_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const char *kvasprintf_const(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff815098a0)
Location: lib/kasprintf.c:43
Inline: False
Direct callers:
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff815098a0-ffffffff81509936: kvasprintf_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const char *kvasprintf_const(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff81515640)
Location: lib/kasprintf.c:43
Inline: False
Direct callers:
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff81515640-ffffffff815156d6: kvasprintf_const (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const char *kvasprintf_const(gfp_t gfp, const char *fmt, struct __va_list_tag *ap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/kasprintf.c (ffffffff8152edd0)
Location: lib/kasprintf.c:43
Inline: False
Direct callers:
  - lib/kobject.c:kobject_set_name_vargs
```
**Symbols:**

```
ffffffff8152edd0-ffffffff8152ee66: kvasprintf_const (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *ap</code> ➡️ <code>va_list ap</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *ap</code> ➡️ <code>va_list ap</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *ap</code> ➡️ <code>va_list ap</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct __va_list_tag *ap</code> ➡️ <code>va_list ap</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
