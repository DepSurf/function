# Function: <code>sg_copy_buffer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
size_t sg_copy_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip, bool to_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff813fa4e0)
Location: lib/scatterlist.c:649
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_copy_from_buffer
  - lib/scatterlist.c:sg_copy_to_buffer
  - lib/scatterlist.c:sg_pcopy_from_buffer
  - lib/scatterlist.c:sg_pcopy_to_buffer
```
**Symbols:**

```
ffffffff813fa4e0-ffffffff813fa5f0: sg_copy_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
size_t sg_copy_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip, bool to_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81441560)
Location: lib/scatterlist.c:649
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_pcopy_to_buffer
  - lib/scatterlist.c:sg_pcopy_from_buffer
  - lib/scatterlist.c:sg_copy_to_buffer
  - lib/scatterlist.c:sg_copy_from_buffer
```
**Symbols:**

```
ffffffff81441560-ffffffff81441670: sg_copy_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
size_t sg_copy_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip, bool to_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8145e780)
Location: lib/scatterlist.c:649
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_pcopy_to_buffer
  - lib/scatterlist.c:sg_pcopy_from_buffer
  - lib/scatterlist.c:sg_copy_to_buffer
  - lib/scatterlist.c:sg_copy_from_buffer
```
**Symbols:**

```
ffffffff8145e780-ffffffff8145e890: sg_copy_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
size_t sg_copy_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip, bool to_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81463990)
Location: lib/scatterlist.c:649
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_pcopy_to_buffer
  - lib/scatterlist.c:sg_pcopy_from_buffer
  - lib/scatterlist.c:sg_copy_to_buffer
  - lib/scatterlist.c:sg_copy_from_buffer
```
**Symbols:**

```
ffffffff81463990-ffffffff81463a7f: sg_copy_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
size_t sg_copy_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip, bool to_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8148f930)
Location: lib/scatterlist.c:690
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_pcopy_to_buffer
  - lib/scatterlist.c:sg_pcopy_from_buffer
  - lib/scatterlist.c:sg_copy_to_buffer
  - lib/scatterlist.c:sg_copy_from_buffer
```
**Symbols:**

```
ffffffff8148f930-ffffffff8148fa1f: sg_copy_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
size_t sg_copy_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip, bool to_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814c4610)
Location: lib/scatterlist.c:805
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_pcopy_to_buffer
  - lib/scatterlist.c:sg_pcopy_from_buffer
  - lib/scatterlist.c:sg_copy_to_buffer
  - lib/scatterlist.c:sg_copy_from_buffer
```
**Symbols:**

```
ffffffff814c4610-ffffffff814c4700: sg_copy_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
size_t sg_copy_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip, bool to_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff814d8d00)
Location: lib/scatterlist.c:805
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_pcopy_to_buffer
  - lib/scatterlist.c:sg_pcopy_from_buffer
  - lib/scatterlist.c:sg_copy_to_buffer
  - lib/scatterlist.c:sg_copy_from_buffer
```
**Symbols:**

```
ffffffff814d8d00-ffffffff814d8df0: sg_copy_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
size_t sg_copy_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip, bool to_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81504bb0)
Location: lib/scatterlist.c:840
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_pcopy_to_buffer
  - lib/scatterlist.c:sg_pcopy_from_buffer
  - lib/scatterlist.c:sg_copy_to_buffer
  - lib/scatterlist.c:sg_copy_from_buffer
```
**Symbols:**

```
ffffffff81504bb0-ffffffff81504c9e: sg_copy_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
size_t sg_copy_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip, bool to_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81522cf0)
Location: lib/scatterlist.c:840
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_pcopy_to_buffer
  - lib/scatterlist.c:sg_pcopy_from_buffer
  - lib/scatterlist.c:sg_copy_to_buffer
  - lib/scatterlist.c:sg_copy_from_buffer
```
**Symbols:**

```
ffffffff81522cf0-ffffffff81522dde: sg_copy_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
size_t sg_copy_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip, bool to_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81585f30)
Location: lib/scatterlist.c:840
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_pcopy_to_buffer
  - lib/scatterlist.c:sg_pcopy_from_buffer
  - lib/scatterlist.c:sg_copy_to_buffer
  - lib/scatterlist.c:sg_copy_from_buffer
```
**Symbols:**

```
ffffffff81585f30-ffffffff81586032: sg_copy_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t sg_copy_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip, bool to_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815a3010)
Location: lib/scatterlist.c:921
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_pcopy_to_buffer
  - lib/scatterlist.c:sg_pcopy_from_buffer
  - lib/scatterlist.c:sg_copy_to_buffer
  - lib/scatterlist.c:sg_copy_from_buffer
```
**Symbols:**

```
ffffffff815a3010-ffffffff815a3112: sg_copy_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
size_t sg_copy_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip, bool to_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff815aa3d0)
Location: lib/scatterlist.c:921
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_pcopy_to_buffer
  - lib/scatterlist.c:sg_pcopy_from_buffer
  - lib/scatterlist.c:sg_copy_to_buffer
  - lib/scatterlist.c:sg_copy_from_buffer
```
**Symbols:**

```
ffffffff815aa3d0-ffffffff815aa4d5: sg_copy_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
size_t sg_copy_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip, bool to_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81613530)
Location: lib/scatterlist.c:951
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_pcopy_to_buffer
  - lib/scatterlist.c:sg_pcopy_from_buffer
  - lib/scatterlist.c:sg_copy_to_buffer
  - lib/scatterlist.c:sg_copy_from_buffer
```
**Symbols:**

```
ffffffff81613530-ffffffff81613635: sg_copy_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t sg_copy_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip, bool to_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff816dfd60)
Location: lib/scatterlist.c:948
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_pcopy_to_buffer
  - lib/scatterlist.c:sg_pcopy_from_buffer
  - lib/scatterlist.c:sg_copy_to_buffer
  - lib/scatterlist.c:sg_copy_from_buffer
```
**Symbols:**

```
ffffffff816dfd60-ffffffff816dfe90: sg_copy_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t sg_copy_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip, bool to_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff817d0120)
Location: lib/scatterlist.c:958
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_pcopy_to_buffer
  - lib/scatterlist.c:sg_pcopy_from_buffer
  - lib/scatterlist.c:sg_copy_to_buffer
  - lib/scatterlist.c:sg_copy_from_buffer
```
**Symbols:**

```
ffffffff817d0120-ffffffff817d024e: sg_copy_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t sg_copy_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip, bool to_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8180e570)
Location: lib/scatterlist.c:960
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_pcopy_to_buffer
  - lib/scatterlist.c:sg_pcopy_from_buffer
  - lib/scatterlist.c:sg_copy_to_buffer
  - lib/scatterlist.c:sg_copy_from_buffer
```
**Symbols:**

```
ffffffff8180e570-ffffffff8180e6a5: sg_copy_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t sg_copy_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip, bool to_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff818541f0)
Location: lib/scatterlist.c:962
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_pcopy_to_buffer
  - lib/scatterlist.c:sg_pcopy_from_buffer
  - lib/scatterlist.c:sg_copy_to_buffer
  - lib/scatterlist.c:sg_copy_from_buffer
```
**Symbols:**

```
ffffffff818541f0-ffffffff81854325: sg_copy_buffer (STB_GLOBAL)
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
size_t sg_copy_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip, bool to_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffff80001062c898)
Location: lib/scatterlist.c:840
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_pcopy_to_buffer
  - lib/scatterlist.c:sg_pcopy_from_buffer
  - lib/scatterlist.c:sg_copy_to_buffer
  - lib/scatterlist.c:sg_copy_from_buffer
```
**Symbols:**

```
ffff80001062c898-ffff80001062c9ac: sg_copy_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
size_t sg_copy_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip, bool to_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c07d32f8)
Location: lib/scatterlist.c:840
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_pcopy_to_buffer
  - lib/scatterlist.c:sg_pcopy_from_buffer
  - lib/scatterlist.c:sg_copy_to_buffer
  - lib/scatterlist.c:sg_copy_from_buffer
```
**Symbols:**

```
c07d32f8-c07d33ec: sg_copy_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
size_t sg_copy_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip, bool to_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (c0000000007cf460)
Location: lib/scatterlist.c:840
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_pcopy_to_buffer
  - lib/scatterlist.c:sg_pcopy_from_buffer
  - lib/scatterlist.c:sg_copy_to_buffer
  - lib/scatterlist.c:sg_copy_from_buffer
```
**Symbols:**

```
c0000000007cf460-c0000000007cf5d4: sg_copy_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
size_t sg_copy_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip, bool to_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffe00045ca42)
Location: lib/scatterlist.c:840
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_pcopy_to_buffer
  - lib/scatterlist.c:sg_pcopy_from_buffer
  - lib/scatterlist.c:sg_copy_to_buffer
  - lib/scatterlist.c:sg_copy_from_buffer
```
**Symbols:**

```
ffffffe00045ca42-ffffffe00045cb20: sg_copy_buffer (STB_GLOBAL)
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
size_t sg_copy_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip, bool to_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8151b2d0)
Location: lib/scatterlist.c:840
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_pcopy_to_buffer
  - lib/scatterlist.c:sg_pcopy_from_buffer
  - lib/scatterlist.c:sg_copy_to_buffer
  - lib/scatterlist.c:sg_copy_from_buffer
```
**Symbols:**

```
ffffffff8151b2d0-ffffffff8151b3be: sg_copy_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
size_t sg_copy_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip, bool to_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff8150b5c0)
Location: lib/scatterlist.c:840
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_pcopy_to_buffer
  - lib/scatterlist.c:sg_pcopy_from_buffer
  - lib/scatterlist.c:sg_copy_to_buffer
  - lib/scatterlist.c:sg_copy_from_buffer
```
**Symbols:**

```
ffffffff8150b5c0-ffffffff8150b6ae: sg_copy_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
size_t sg_copy_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip, bool to_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81517360)
Location: lib/scatterlist.c:840
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_pcopy_to_buffer
  - lib/scatterlist.c:sg_pcopy_from_buffer
  - lib/scatterlist.c:sg_copy_to_buffer
  - lib/scatterlist.c:sg_copy_from_buffer
```
**Symbols:**

```
ffffffff81517360-ffffffff8151744e: sg_copy_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
size_t sg_copy_buffer(struct scatterlist *sgl, unsigned int nents, void *buf, size_t buflen, off_t skip, bool to_buffer);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/scatterlist.c (ffffffff81530b00)
Location: lib/scatterlist.c:840
Inline: False
Direct callers:
  - lib/scatterlist.c:sg_pcopy_to_buffer
  - lib/scatterlist.c:sg_pcopy_from_buffer
  - lib/scatterlist.c:sg_copy_to_buffer
  - lib/scatterlist.c:sg_copy_from_buffer
```
**Symbols:**

```
ffffffff81530b00-ffffffff81530bee: sg_copy_buffer (STB_GLOBAL)
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
