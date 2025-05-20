# Function: <code>unzstd</code>

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
int unzstd(unsigned char *buf, long int len, long int (*fill)(void *, long unsigned int), long int (*flush)(void *, long unsigned int), unsigned char *out_buf, long int *pos, void (*error)(char *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/decompress_unzstd.c (ffffffff82ffa998)
Location: lib/decompress_unzstd.c:331
Inline: False
```
**Symbols:**

```
ffffffff82ffa998-ffffffff82ffa9a6: unzstd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int unzstd(unsigned char *buf, long int len, long int (*fill)(void *, long unsigned int), long int (*flush)(void *, long unsigned int), unsigned char *out_buf, long int *pos, void (*error)(char *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/decompress_unzstd.c (ffffffff832055af)
Location: lib/decompress_unzstd.c:331
Inline: False
```
**Symbols:**

```
ffffffff832055af-ffffffff832055bd: unzstd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int unzstd(unsigned char *buf, long int len, long int (*fill)(void *, long unsigned int), long int (*flush)(void *, long unsigned int), unsigned char *out_buf, long int *pos, void (*error)(char *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/decompress_unzstd.c (ffffffff832ed289)
Location: lib/decompress_unzstd.c:331
Inline: False
```
**Symbols:**

```
ffffffff832ed289-ffffffff832ed297: unzstd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int unzstd(unsigned char *buf, long int len, long int (*fill)(void *, long unsigned int), long int (*flush)(void *, long unsigned int), unsigned char *out_buf, long int *pos, void (*error)(char *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/decompress_unzstd.c (ffffffff834a5018)
Location: lib/decompress_unzstd.c:331
Inline: False
```
**Symbols:**

```
ffffffff834a5018-ffffffff834a5038: unzstd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int unzstd(unsigned char *buf, long int len, long int (*fill)(void *, long unsigned int), long int (*flush)(void *, long unsigned int), unsigned char *out_buf, long int *pos, void (*error)(char *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/decompress_unzstd.c (ffffffff83f1c230)
Location: lib/decompress_unzstd.c:331
Inline: False
```
**Symbols:**

```
ffffffff83f1c230-ffffffff83f1c250: unzstd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int unzstd(unsigned char *buf, long int len, long int (*fill)(void *, long unsigned int), long int (*flush)(void *, long unsigned int), unsigned char *out_buf, long int *pos, void (*error)(char *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/decompress_unzstd.c (ffffffff83742ac0)
Location: lib/decompress_unzstd.c:333
Inline: False
```
**Symbols:**

```
ffffffff83742ac0-ffffffff83742ae0: unzstd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int unzstd(unsigned char *buf, long int len, long int (*fill)(void *, long unsigned int), long int (*flush)(void *, long unsigned int), unsigned char *out_buf, long int *pos, void (*error)(char *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/decompress_unzstd.c (ffffffff839775b0)
Location: lib/decompress_unzstd.c:333
Inline: False
```
**Symbols:**

```
ffffffff839775b0-ffffffff839775d0: unzstd (STB_GLOBAL)
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
