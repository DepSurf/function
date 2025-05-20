# Function: <code>__sbitmap_get_word</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff814821e7)
Location: lib/sbitmap.c:80
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_get
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int *word, long unsigned int depth, unsigned int hint, bool wrap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8148b3f0)
Location: lib/sbitmap.c:82
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
```
**Symbols:**

```
ffffffff8148b3f0-ffffffff8148b475: __sbitmap_get_word (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int *word, long unsigned int depth, unsigned int hint, bool wrap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff814c7510)
Location: lib/sbitmap.c:82
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
```
**Symbols:**

```
ffffffff814c7510-ffffffff814c7595: __sbitmap_get_word (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int *word, long unsigned int depth, unsigned int hint, bool wrap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff814f81f0)
Location: lib/sbitmap.c:82
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
```
**Symbols:**

```
ffffffff814f81f0-ffffffff814f8275: __sbitmap_get_word (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int *word, long unsigned int depth, unsigned int hint, bool wrap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8150c6b0)
Location: lib/sbitmap.c:120
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
```
**Symbols:**

```
ffffffff8150c6b0-ffffffff8150c735: __sbitmap_get_word (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int *word, long unsigned int depth, unsigned int hint, bool wrap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8153adc0)
Location: lib/sbitmap.c:107
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
```
**Symbols:**

```
ffffffff8153adc0-ffffffff8153ae48: __sbitmap_get_word (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int *word, long unsigned int depth, unsigned int hint, bool wrap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8155bbe0)
Location: lib/sbitmap.c:107
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
```
**Symbols:**

```
ffffffff8155bbe0-ffffffff8155bc68: __sbitmap_get_word (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int *word, long unsigned int depth, unsigned int hint, bool wrap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815e5760)
Location: lib/sbitmap.c:107
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
```
**Symbols:**

```
ffffffff815e5760-ffffffff815e57e8: __sbitmap_get_word (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int *word, long unsigned int depth, unsigned int hint, bool wrap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81609b40)
Location: lib/sbitmap.c:97
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
```
**Symbols:**

```
ffffffff81609b40-ffffffff81609bae: __sbitmap_get_word (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int *word, long unsigned int depth, unsigned int hint, bool wrap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815ecd80)
Location: lib/sbitmap.c:146
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
```
**Symbols:**

```
ffffffff815ecd80-ffffffff815ecdfa: __sbitmap_get_word (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int *word, long unsigned int depth, unsigned int hint, bool wrap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81659ca0)
Location: lib/sbitmap.c:146
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:__sbitmap_get
```
**Symbols:**

```
ffffffff81659ca0-ffffffff81659d1a: __sbitmap_get_word (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int *word, long unsigned int depth, unsigned int hint, bool wrap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff817723f0)
Location: lib/sbitmap.c:136
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:__sbitmap_get
```
**Symbols:**

```
ffffffff817723f0-ffffffff8177247d: __sbitmap_get_word (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int *word, long unsigned int depth, unsigned int hint, bool wrap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff818a2c80)
Location: lib/sbitmap.c:136
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:__sbitmap_get
```
**Symbols:**

```
ffffffff818a2c80-ffffffff818a2cfb: __sbitmap_get_word (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff818e5c89)
Location: lib/sbitmap.c:136
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_find_bit
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8192cc89)
Location: lib/sbitmap.c:136
Inline: True
Inline callers:
  - lib/sbitmap.c:sbitmap_find_bit
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
int __sbitmap_get_word(long unsigned int *word, long unsigned int depth, unsigned int hint, bool wrap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffff800010669ae0)
Location: lib/sbitmap.c:107
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
```
**Symbols:**

```
ffff800010669ae0-ffff800010669c00: __sbitmap_get_word (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int *word, long unsigned int depth, unsigned int hint, bool wrap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (c08119c4)
Location: lib/sbitmap.c:107
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
```
**Symbols:**

```
c08119c4-c0811ab8: __sbitmap_get_word (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int *word, long unsigned int depth, unsigned int hint, bool wrap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (c00000000081e830)
Location: lib/sbitmap.c:107
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
  - lib/sbitmap.c:sbitmap_get
```
**Symbols:**

```
c00000000081e830-c00000000081e944: __sbitmap_get_word (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int *word, long unsigned int depth, unsigned int hint, bool wrap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffe00049412a)
Location: lib/sbitmap.c:107
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
```
**Symbols:**

```
ffffffe00049412a-ffffffe0004941ba: __sbitmap_get_word (STB_LOCAL)
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
int __sbitmap_get_word(long unsigned int *word, long unsigned int depth, unsigned int hint, bool wrap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815541d0)
Location: lib/sbitmap.c:107
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
```
**Symbols:**

```
ffffffff815541d0-ffffffff81554258: __sbitmap_get_word (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int *word, long unsigned int depth, unsigned int hint, bool wrap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81544450)
Location: lib/sbitmap.c:107
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
```
**Symbols:**

```
ffffffff81544450-ffffffff815444d8: __sbitmap_get_word (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int *word, long unsigned int depth, unsigned int hint, bool wrap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8154ff10)
Location: lib/sbitmap.c:107
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
```
**Symbols:**

```
ffffffff8154ff10-ffffffff8154ff98: __sbitmap_get_word (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __sbitmap_get_word(long unsigned int *word, long unsigned int depth, unsigned int hint, bool wrap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81569d50)
Location: lib/sbitmap.c:107
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_get_shallow
  - lib/sbitmap.c:sbitmap_get
```
**Symbols:**

```
ffffffff81569d50-ffffffff81569dd8: __sbitmap_get_word (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
