# Function: <code>num_to_str</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int num_to_str(char *buf, int size, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff813f5ca0)
Location: lib/vsprintf.c:331
Inline: False
```
**Symbols:**

```
ffffffff813f5ca0-ffffffff813f5d3d: num_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int num_to_str(char *buf, int size, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8143c830)
Location: lib/vsprintf.c:337
Inline: False
```
**Symbols:**

```
ffffffff8143c830-ffffffff8143c8cd: num_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int num_to_str(char *buf, int size, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81459810)
Location: lib/vsprintf.c:337
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_decimal_ull
  - fs/proc/meminfo.c:show_val_kb
```
**Symbols:**

```
ffffffff81459810-ffffffff814598ad: num_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int num_to_str(char *buf, int size, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff818fb1b0)
Location: lib/vsprintf.c:338
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_decimal_ull
  - fs/proc/meminfo.c:show_val_kb
```
**Symbols:**

```
ffffffff818fb1b0-ffffffff818fb24d: num_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int num_to_str(char *buf, int size, long long unsigned int num);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81981e10)
Location: lib/vsprintf.c:340
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_decimal_ull
  - fs/proc/meminfo.c:show_val_kb
```
**Symbols:**

```
ffffffff81981e10-ffffffff81981ead: num_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int num_to_str(char *buf, int size, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff819de330)
Location: lib/vsprintf.c:339
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
```
**Symbols:**

```
ffffffff819de330-ffffffff819de3f9: num_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int num_to_str(char *buf, int size, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a16980)
Location: lib/vsprintf.c:340
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
```
**Symbols:**

```
ffffffff81a16980-ffffffff81a16a49: num_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int num_to_str(char *buf, int size, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a86510)
Location: lib/vsprintf.c:342
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
```
**Symbols:**

```
ffffffff81a86510-ffffffff81a865dc: num_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int num_to_str(char *buf, int size, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81abd790)
Location: lib/vsprintf.c:342
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
```
**Symbols:**

```
ffffffff81abd790-ffffffff81abd85c: num_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int num_to_str(char *buf, int size, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815f97f0)
Location: lib/vsprintf.c:345
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
```
**Symbols:**

```
ffffffff815f97f0-ffffffff815f98b1: num_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int num_to_str(char *buf, int size, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8161deb0)
Location: lib/vsprintf.c:345
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
```
**Symbols:**

```
ffffffff8161deb0-ffffffff8161df71: num_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int num_to_str(char *buf, int size, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81601810)
Location: lib/vsprintf.c:371
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
```
**Symbols:**

```
ffffffff81601810-ffffffff816018cf: num_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int num_to_str(char *buf, int size, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8166f770)
Location: lib/vsprintf.c:372
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
```
**Symbols:**

```
ffffffff8166f770-ffffffff8166f85a: num_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int num_to_str(char *buf, int size, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81789ae0)
Location: lib/vsprintf.c:376
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
```
**Symbols:**

```
ffffffff81789ae0-ffffffff81789bf5: num_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int num_to_str(char *buf, int size, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff82046e80)
Location: lib/vsprintf.c:377
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
```
**Symbols:**

```
ffffffff82046e80-ffffffff82046f95: num_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int num_to_str(char *buf, int size, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff820c5510)
Location: lib/vsprintf.c:377
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
```
**Symbols:**

```
ffffffff820c5510-ffffffff820c5625: num_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int num_to_str(char *buf, int size, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8219fe90)
Location: lib/vsprintf.c:379
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
```
**Symbols:**

```
ffffffff8219fe90-ffffffff8219ffa5: num_to_str (STB_GLOBAL)
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
int num_to_str(char *buf, int size, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffff800010d989a0)
Location: lib/vsprintf.c:342
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
```
**Symbols:**

```
ffff800010d989a0-ffff800010d98a94: num_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int num_to_str(char *buf, int size, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c0e95398)
Location: lib/vsprintf.c:342
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
```
**Symbols:**

```
c0e95398-c0e954d0: num_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int num_to_str(char *buf, int size, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c000000000ede0a0)
Location: lib/vsprintf.c:342
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
```
**Symbols:**

```
c000000000ede0a0-c000000000ede220: num_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int num_to_str(char *buf, int size, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffe0008c17be)
Location: lib/vsprintf.c:342
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
```
**Symbols:**

```
ffffffe0008c17be-ffffffe0008c187a: num_to_str (STB_GLOBAL)
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
int num_to_str(char *buf, int size, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a5c5e0)
Location: lib/vsprintf.c:342
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
```
**Symbols:**

```
ffffffff81a5c5e0-ffffffff81a5c6ac: num_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int num_to_str(char *buf, int size, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81a196c0)
Location: lib/vsprintf.c:342
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
```
**Symbols:**

```
ffffffff81a196c0-ffffffff81a1978c: num_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int num_to_str(char *buf, int size, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ac89d0)
Location: lib/vsprintf.c:342
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
```
**Symbols:**

```
ffffffff81ac89d0-ffffffff81ac8a9c: num_to_str (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int num_to_str(char *buf, int size, long long unsigned int num, unsigned int width);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81ad4eb0)
Location: lib/vsprintf.c:342
Inline: False
Direct callers:
  - fs/seq_file.c:seq_put_decimal_ll
  - fs/seq_file.c:seq_put_decimal_ull_width
```
**Symbols:**

```
ffffffff81ad4eb0-ffffffff81ad4f7c: num_to_str (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int width</code>
</li>
</ul>
</details>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
