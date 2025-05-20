# Function: <code>gen_pool_for_each_chunk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void gen_pool_for_each_chunk(struct gen_pool *pool, void (*func)(struct gen_pool *, struct gen_pool_chunk *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81406e50)
Location: lib/genalloc.c:392
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_exit
```
**Symbols:**

```
ffffffff81406e50-ffffffff81406e92: gen_pool_for_each_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void gen_pool_for_each_chunk(struct gen_pool *pool, void (*func)(struct gen_pool *, struct gen_pool_chunk *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8144ebe0)
Location: lib/genalloc.c:411
Inline: False
```
**Symbols:**

```
ffffffff8144ebe0-ffffffff8144ec22: gen_pool_for_each_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void gen_pool_for_each_chunk(struct gen_pool *pool, void (*func)(struct gen_pool *, struct gen_pool_chunk *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8146d5a0)
Location: lib/genalloc.c:412
Inline: False
```
**Symbols:**

```
ffffffff8146d5a0-ffffffff8146d5e2: gen_pool_for_each_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void gen_pool_for_each_chunk(struct gen_pool *pool, void (*func)(struct gen_pool *, struct gen_pool_chunk *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81472c70)
Location: lib/genalloc.c:412
Inline: False
```
**Symbols:**

```
ffffffff81472c70-ffffffff81472cb2: gen_pool_for_each_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void gen_pool_for_each_chunk(struct gen_pool *pool, void (*func)(struct gen_pool *, struct gen_pool_chunk *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8149fff0)
Location: lib/genalloc.c:412
Inline: False
```
**Symbols:**

```
ffffffff8149fff0-ffffffff814a0034: gen_pool_for_each_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void gen_pool_for_each_chunk(struct gen_pool *pool, void (*func)(struct gen_pool *, struct gen_pool_chunk *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff814d51b0)
Location: lib/genalloc.c:412
Inline: False
Direct callers:
  - drivers/acpi/apei/ghes.c:ghes_init
```
**Symbols:**

```
ffffffff814d51b0-ffffffff814d51f4: gen_pool_for_each_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void gen_pool_for_each_chunk(struct gen_pool *pool, void (*func)(struct gen_pool *, struct gen_pool_chunk *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff814e9c00)
Location: lib/genalloc.c:413
Inline: False
```
**Symbols:**

```
ffffffff814e9c00-ffffffff814e9c44: gen_pool_for_each_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void gen_pool_for_each_chunk(struct gen_pool *pool, void (*func)(struct gen_pool *, struct gen_pool_chunk *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81516820)
Location: lib/genalloc.c:529
Inline: False
```
**Symbols:**

```
ffffffff81516820-ffffffff81516864: gen_pool_for_each_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void gen_pool_for_each_chunk(struct gen_pool *pool, void (*func)(struct gen_pool *, struct gen_pool_chunk *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81537260)
Location: lib/genalloc.c:529
Inline: False
```
**Symbols:**

```
ffffffff81537260-ffffffff815372a4: gen_pool_for_each_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void gen_pool_for_each_chunk(struct gen_pool *pool, void (*func)(struct gen_pool *, struct gen_pool_chunk *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8159b6d0)
Location: lib/genalloc.c:529
Inline: False
```
**Symbols:**

```
ffffffff8159b6d0-ffffffff8159b714: gen_pool_for_each_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void gen_pool_for_each_chunk(struct gen_pool *pool, void (*func)(struct gen_pool *, struct gen_pool_chunk *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff815b7200)
Location: lib/genalloc.c:530
Inline: False
```
**Symbols:**

```
ffffffff815b7200-ffffffff815b7249: gen_pool_for_each_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void gen_pool_for_each_chunk(struct gen_pool *pool, void (*func)(struct gen_pool *, struct gen_pool_chunk *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff815c2070)
Location: lib/genalloc.c:531
Inline: False
```
**Symbols:**

```
ffffffff815c2070-ffffffff815c20b9: gen_pool_for_each_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void gen_pool_for_each_chunk(struct gen_pool *pool, void (*func)(struct gen_pool *, struct gen_pool_chunk *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81629ef0)
Location: lib/genalloc.c:531
Inline: False
```
**Symbols:**

```
ffffffff81629ef0-ffffffff81629f39: gen_pool_for_each_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void gen_pool_for_each_chunk(struct gen_pool *pool, void (*func)(struct gen_pool *, struct gen_pool_chunk *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff816fb200)
Location: lib/genalloc.c:531
Inline: False
```
**Symbols:**

```
ffffffff816fb200-ffffffff816fb25b: gen_pool_for_each_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gen_pool_for_each_chunk(struct gen_pool *pool, void (*func)(struct gen_pool *, struct gen_pool_chunk *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff817edda0)
Location: lib/genalloc.c:531
Inline: False
```
**Symbols:**

```
ffffffff817edda0-ffffffff817eddfb: gen_pool_for_each_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gen_pool_for_each_chunk(struct gen_pool *pool, void (*func)(struct gen_pool *, struct gen_pool_chunk *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8182e1b0)
Location: lib/genalloc.c:529
Inline: False
```
**Symbols:**

```
ffffffff8182e1b0-ffffffff8182e20b: gen_pool_for_each_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gen_pool_for_each_chunk(struct gen_pool *pool, void (*func)(struct gen_pool *, struct gen_pool_chunk *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8187fd70)
Location: lib/genalloc.c:531
Inline: False
```
**Symbols:**

```
ffffffff8187fd70-ffffffff8187fdcb: gen_pool_for_each_chunk (STB_GLOBAL)
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
void gen_pool_for_each_chunk(struct gen_pool *pool, void (*func)(struct gen_pool *, struct gen_pool_chunk *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffff800010643c48)
Location: lib/genalloc.c:529
Inline: False
```
**Symbols:**

```
ffff800010643c48-ffff800010643ca8: gen_pool_for_each_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void gen_pool_for_each_chunk(struct gen_pool *pool, void (*func)(struct gen_pool *, struct gen_pool_chunk *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (c07ea35c)
Location: lib/genalloc.c:529
Inline: False
```
**Symbols:**

```
c07ea35c-c07ea3a4: gen_pool_for_each_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void gen_pool_for_each_chunk(struct gen_pool *pool, void (*func)(struct gen_pool *, struct gen_pool_chunk *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (c0000000007ef5c0)
Location: lib/genalloc.c:529
Inline: False
```
**Symbols:**

```
c0000000007ef5c0-c0000000007ef65c: gen_pool_for_each_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void gen_pool_for_each_chunk(struct gen_pool *pool, void (*func)(struct gen_pool *, struct gen_pool_chunk *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffe0004706f6)
Location: lib/genalloc.c:529
Inline: False
```
**Symbols:**

```
ffffffe0004706f6-ffffffe000470738: gen_pool_for_each_chunk (STB_GLOBAL)
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
void gen_pool_for_each_chunk(struct gen_pool *pool, void (*func)(struct gen_pool *, struct gen_pool_chunk *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8152f840)
Location: lib/genalloc.c:529
Inline: False
```
**Symbols:**

```
ffffffff8152f840-ffffffff8152f884: gen_pool_for_each_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void gen_pool_for_each_chunk(struct gen_pool *pool, void (*func)(struct gen_pool *, struct gen_pool_chunk *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8151fb20)
Location: lib/genalloc.c:529
Inline: False
```
**Symbols:**

```
ffffffff8151fb20-ffffffff8151fb64: gen_pool_for_each_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void gen_pool_for_each_chunk(struct gen_pool *pool, void (*func)(struct gen_pool *, struct gen_pool_chunk *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8152b580)
Location: lib/genalloc.c:529
Inline: False
```
**Symbols:**

```
ffffffff8152b580-ffffffff8152b5c4: gen_pool_for_each_chunk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void gen_pool_for_each_chunk(struct gen_pool *pool, void (*func)(struct gen_pool *, struct gen_pool_chunk *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81545800)
Location: lib/genalloc.c:529
Inline: False
```
**Symbols:**

```
ffffffff81545800-ffffffff81545850: gen_pool_for_each_chunk (STB_GLOBAL)
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
