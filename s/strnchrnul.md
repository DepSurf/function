# Function: <code>strnchrnul</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *strnchrnul(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815f38b0)
Location: lib/string.c:471
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parse
```
**Symbols:**

```
ffffffff815f38b0-ffffffff815f38d4: strnchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *strnchrnul(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81617f40)
Location: lib/string.c:468
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parse
```
**Symbols:**

```
ffffffff81617f40-ffffffff81617f64: strnchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *strnchrnul(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff815fb560)
Location: lib/string.c:468
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parse
```
**Symbols:**

```
ffffffff815fb560-ffffffff815fb582: strnchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *strnchrnul(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81668e30)
Location: lib/string.c:469
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parse
```
**Symbols:**

```
ffffffff81668e30-ffffffff81668e52: strnchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *strnchrnul(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff81782870)
Location: lib/string.c:430
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parse
```
**Symbols:**

```
ffffffff81782870-ffffffff8178289e: strnchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *strnchrnul(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff8203f790)
Location: lib/string.c:365
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parse
```
**Symbols:**

```
ffffffff8203f790-ffffffff8203f7be: strnchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *strnchrnul(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff820bdcb0)
Location: lib/string.c:365
Inline: False
Direct callers:
  - lib/bitmap.c:bitmap_parse
  - drivers/firmware/efi/earlycon.c:efi_earlycon_write
```
**Symbols:**

```
ffffffff820bdcb0-ffffffff820bdcde: strnchrnul (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *strnchrnul(const char *s, size_t count, int c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/string.c (ffffffff82198530)
Location: lib/string.c:350
Inline: False
Direct callers:
  - lib/bitmap-str.c:bitmap_parse
  - drivers/firmware/efi/earlycon.c:efi_earlycon_write
```
**Symbols:**

```
ffffffff82198530-ffffffff8219855e: strnchrnul (STB_GLOBAL)
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
