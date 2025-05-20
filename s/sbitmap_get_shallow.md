# Function: <code>sbitmap_get_shallow</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sbitmap_get_shallow(struct sbitmap *sb, unsigned int alloc_hint, long unsigned int shallow_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8148b530)
Location: lib/sbitmap.c:145
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
```
**Symbols:**

```
ffffffff8148b530-ffffffff8148b5dd: sbitmap_get_shallow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sbitmap_get_shallow(struct sbitmap *sb, unsigned int alloc_hint, long unsigned int shallow_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff814c7650)
Location: lib/sbitmap.c:145
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
```
**Symbols:**

```
ffffffff814c7650-ffffffff814c76fd: sbitmap_get_shallow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sbitmap_get_shallow(struct sbitmap *sb, unsigned int alloc_hint, long unsigned int shallow_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff814f8330)
Location: lib/sbitmap.c:145
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
```
**Symbols:**

```
ffffffff814f8330-ffffffff814f83dd: sbitmap_get_shallow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sbitmap_get_shallow(struct sbitmap *sb, unsigned int alloc_hint, long unsigned int shallow_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8150d530)
Location: lib/sbitmap.c:205
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
```
**Symbols:**

```
ffffffff8150d530-ffffffff8150d6aa: sbitmap_get_shallow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sbitmap_get_shallow(struct sbitmap *sb, unsigned int alloc_hint, long unsigned int shallow_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8153bc00)
Location: lib/sbitmap.c:192
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
```
**Symbols:**

```
ffffffff8153bc00-ffffffff8153bd5c: sbitmap_get_shallow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sbitmap_get_shallow(struct sbitmap *sb, unsigned int alloc_hint, long unsigned int shallow_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8155ca10)
Location: lib/sbitmap.c:192
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
```
**Symbols:**

```
ffffffff8155ca10-ffffffff8155cb6c: sbitmap_get_shallow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sbitmap_get_shallow(struct sbitmap *sb, unsigned int alloc_hint, long unsigned int shallow_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815e6420)
Location: lib/sbitmap.c:192
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
```
**Symbols:**

```
ffffffff815e6420-ffffffff815e6582: sbitmap_get_shallow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sbitmap_get_shallow(struct sbitmap *sb, unsigned int alloc_hint, long unsigned int shallow_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8160a650)
Location: lib/sbitmap.c:184
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
```
**Symbols:**

```
ffffffff8160a650-ffffffff8160a745: sbitmap_get_shallow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sbitmap_get_shallow(struct sbitmap *sb, long unsigned int shallow_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff815ed280)
Location: lib/sbitmap.c:283
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
```
**Symbols:**

```
ffffffff815ed280-ffffffff815ed3fc: sbitmap_get_shallow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sbitmap_get_shallow(struct sbitmap *sb, long unsigned int shallow_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:283
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
```
**Symbols:**

```
ffffffff81cdee73-ffffffff81cdef0c: sbitmap_get_shallow.cold (STB_LOCAL)
ffffffff8165a3d0-ffffffff8165a5a2: sbitmap_get_shallow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sbitmap_get_shallow(struct sbitmap *sb, long unsigned int shallow_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:275
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_queue_get_shallow
  - lib/sbitmap.c:sbitmap_queue_get_shallow
```
**Symbols:**

```
ffffffff81ea556b-ffffffff81ea565e: sbitmap_get_shallow.cold (STB_LOCAL)
ffffffff81773560-ffffffff81773769: sbitmap_get_shallow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sbitmap_get_shallow(struct sbitmap *sb, long unsigned int shallow_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:275
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_queue_get_shallow
  - lib/sbitmap.c:sbitmap_queue_get_shallow
```
**Symbols:**

```
ffffffff8208dae0-ffffffff8208dbd3: sbitmap_get_shallow.cold (STB_LOCAL)
ffffffff818a3ec0-ffffffff818a40c4: sbitmap_get_shallow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sbitmap_get_shallow(struct sbitmap *sb, long unsigned int shallow_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:268
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_queue_get_shallow
  - lib/sbitmap.c:sbitmap_queue_get_shallow
```
**Symbols:**

```
ffffffff8210dde5-ffffffff8210de3e: sbitmap_get_shallow.cold (STB_LOCAL)
ffffffff818e6260-ffffffff818e63a0: sbitmap_get_shallow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sbitmap_get_shallow(struct sbitmap *sb, long unsigned int shallow_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/sbitmap.c (0)
Location: lib/sbitmap.c:268
Inline: False
Direct callers:
  - lib/sbitmap.c:sbitmap_queue_get_shallow
  - lib/sbitmap.c:sbitmap_queue_get_shallow
```
**Symbols:**

```
ffffffff821eba22-ffffffff821eba7b: sbitmap_get_shallow.cold (STB_LOCAL)
ffffffff8192d280-ffffffff8192d3c0: sbitmap_get_shallow (STB_GLOBAL)
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
int sbitmap_get_shallow(struct sbitmap *sb, unsigned int alloc_hint, long unsigned int shallow_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffff800010669f10)
Location: lib/sbitmap.c:192
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
```
**Symbols:**

```
ffff800010669f10-ffff80001066a020: sbitmap_get_shallow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sbitmap_get_shallow(struct sbitmap *sb, unsigned int alloc_hint, long unsigned int shallow_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (c0812b30)
Location: lib/sbitmap.c:192
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
```
**Symbols:**

```
c0812b30-c0812cb4: sbitmap_get_shallow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sbitmap_get_shallow(struct sbitmap *sb, unsigned int alloc_hint, long unsigned int shallow_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (c000000000820120)
Location: lib/sbitmap.c:192
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
```
**Symbols:**

```
c000000000820120-c000000000820354: sbitmap_get_shallow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sbitmap_get_shallow(struct sbitmap *sb, unsigned int alloc_hint, long unsigned int shallow_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffe000495054)
Location: lib/sbitmap.c:192
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
```
**Symbols:**

```
ffffffe000495054-ffffffe00049518c: sbitmap_get_shallow (STB_GLOBAL)
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
int sbitmap_get_shallow(struct sbitmap *sb, unsigned int alloc_hint, long unsigned int shallow_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81555000)
Location: lib/sbitmap.c:192
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
```
**Symbols:**

```
ffffffff81555000-ffffffff8155515c: sbitmap_get_shallow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sbitmap_get_shallow(struct sbitmap *sb, unsigned int alloc_hint, long unsigned int shallow_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81545280)
Location: lib/sbitmap.c:192
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
```
**Symbols:**

```
ffffffff81545280-ffffffff815453dc: sbitmap_get_shallow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sbitmap_get_shallow(struct sbitmap *sb, unsigned int alloc_hint, long unsigned int shallow_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff81550d40)
Location: lib/sbitmap.c:192
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
```
**Symbols:**

```
ffffffff81550d40-ffffffff81550e9c: sbitmap_get_shallow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sbitmap_get_shallow(struct sbitmap *sb, unsigned int alloc_hint, long unsigned int shallow_depth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/sbitmap.c (ffffffff8156ab80)
Location: lib/sbitmap.c:192
Inline: False
Direct callers:
  - lib/sbitmap.c:__sbitmap_queue_get_shallow
```
**Symbols:**

```
ffffffff8156ab80-ffffffff8156acdc: sbitmap_get_shallow (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int alloc_hint</code>
</li>
<li>
<b>Param reordered. </b>
<code>sb, alloc_hint, shallow_depth</code> ➡️ <code>sb, shallow_depth</code>
</li>
</ul>
</details>
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
