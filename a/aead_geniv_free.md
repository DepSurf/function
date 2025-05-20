# Function: <code>aead_geniv_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void aead_geniv_free(struct aead_instance *inst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff8139f090)
Location: crypto/aead.c:271
Inline: False
```
**Symbols:**

```
ffffffff8139f090-ffffffff8139f0b4: aead_geniv_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void aead_geniv_free(struct aead_instance *inst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff813dbe30)
Location: crypto/aead.c:271
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_free
  - crypto/seqiv.c:seqiv_create
```
**Symbols:**

```
ffffffff813dbe30-ffffffff813dbe54: aead_geniv_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void aead_geniv_free(struct aead_instance *inst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff813f3710)
Location: crypto/aead.c:271
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_free
  - crypto/seqiv.c:seqiv_create
```
**Symbols:**

```
ffffffff813f3710-ffffffff813f3734: aead_geniv_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void aead_geniv_free(struct aead_instance *inst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff813ffa30)
Location: crypto/aead.c:272
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_free
  - crypto/seqiv.c:seqiv_create
```
**Symbols:**

```
ffffffff813ffa30-ffffffff813ffa54: aead_geniv_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void aead_geniv_free(struct aead_instance *inst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff81428020)
Location: crypto/aead.c:272
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_free
  - crypto/seqiv.c:seqiv_create
```
**Symbols:**

```
ffffffff81428020-ffffffff81428044: aead_geniv_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void aead_geniv_free(struct aead_instance *inst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff8145ae60)
Location: crypto/aead.c:281
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_free
  - crypto/seqiv.c:seqiv_create
```
**Symbols:**

```
ffffffff8145ae60-ffffffff8145ae84: aead_geniv_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void aead_geniv_free(struct aead_instance *inst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814789e0)
Location: crypto/aead.c:279
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_free
  - crypto/seqiv.c:seqiv_create
```
**Symbols:**

```
ffffffff814789e0-ffffffff81478a04: aead_geniv_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void aead_geniv_free(struct aead_instance *inst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814a6800)
Location: crypto/aead.c:310
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_free
  - crypto/seqiv.c:seqiv_create
```
**Symbols:**

```
ffffffff814a6800-ffffffff814a6826: aead_geniv_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void aead_geniv_free(struct aead_instance *inst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814c1470)
Location: crypto/aead.c:311
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_free
  - crypto/seqiv.c:seqiv_create
```
**Symbols:**

```
ffffffff814c1470-ffffffff814c1496: aead_geniv_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void aead_geniv_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/geniv.c (ffffffff81522492)
Location: crypto/geniv.c:35
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
**Symbols:**

```
ffffffff81522270-ffffffff81522298: aead_geniv_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void aead_geniv_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/geniv.c (ffffffff8153f36a)
Location: crypto/geniv.c:35
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
**Symbols:**

```
ffffffff8153f150-ffffffff8153f178: aead_geniv_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void aead_geniv_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/geniv.c (ffffffff815479f2)
Location: crypto/geniv.c:35
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
**Symbols:**

```
ffffffff815477d0-ffffffff815477f8: aead_geniv_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void aead_geniv_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/geniv.c (ffffffff815a81d2)
Location: crypto/geniv.c:35
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
**Symbols:**

```
ffffffff815a7fb0-ffffffff815a7fd8: aead_geniv_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void aead_geniv_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/geniv.c (ffffffff8164f597)
Location: crypto/geniv.c:35
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
**Symbols:**

```
ffffffff8164f340-ffffffff8164f36d: aead_geniv_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void aead_geniv_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/geniv.c (ffffffff81708ba7)
Location: crypto/geniv.c:35
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
**Symbols:**

```
ffffffff81708920-ffffffff8170894d: aead_geniv_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void aead_geniv_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/geniv.c (ffffffff81742377)
Location: crypto/geniv.c:35
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
**Symbols:**

```
ffffffff817420d0-ffffffff817420fd: aead_geniv_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void aead_geniv_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/geniv.c (ffffffff81783286)
Location: crypto/geniv.c:35
Inline: True
Inline callers:
  - crypto/geniv.c:aead_geniv_alloc
```
**Symbols:**

```
ffffffff81782fb0-ffffffff81782fdd: aead_geniv_free (STB_LOCAL)
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
void aead_geniv_free(struct aead_instance *inst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffff8000105bb7c8)
Location: crypto/aead.c:311
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_free
  - crypto/seqiv.c:seqiv_create
```
**Symbols:**

```
ffff8000105bb7c8-ffff8000105bb7fc: aead_geniv_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void aead_geniv_free(struct aead_instance *inst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (c07699f4)
Location: crypto/aead.c:311
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_free
  - crypto/seqiv.c:seqiv_create
```
**Symbols:**

```
c07699f4-c0769a20: aead_geniv_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void aead_geniv_free(struct aead_instance *inst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (c000000000742170)
Location: crypto/aead.c:311
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_free
  - crypto/seqiv.c:seqiv_create
```
**Symbols:**

```
c000000000742170-c0000000007421c0: aead_geniv_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void aead_geniv_free(struct aead_instance *inst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffe0004011fa)
Location: crypto/aead.c:311
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_free
  - crypto/seqiv.c:seqiv_create
```
**Symbols:**

```
ffffffe0004011fa-ffffffe000401230: aead_geniv_free (STB_GLOBAL)
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
void aead_geniv_free(struct aead_instance *inst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814b9a50)
Location: crypto/aead.c:311
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_free
  - crypto/seqiv.c:seqiv_create
```
**Symbols:**

```
ffffffff814b9a50-ffffffff814b9a76: aead_geniv_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void aead_geniv_free(struct aead_instance *inst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814aa470)
Location: crypto/aead.c:311
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_free
  - crypto/seqiv.c:seqiv_create
```
**Symbols:**

```
ffffffff814aa470-ffffffff814aa496: aead_geniv_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void aead_geniv_free(struct aead_instance *inst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814b5ae0)
Location: crypto/aead.c:311
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_free
  - crypto/seqiv.c:seqiv_create
```
**Symbols:**

```
ffffffff814b5ae0-ffffffff814b5b06: aead_geniv_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void aead_geniv_free(struct aead_instance *inst);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/aead.c (ffffffff814ce580)
Location: crypto/aead.c:311
Inline: False
Direct callers:
  - crypto/seqiv.c:seqiv_free
  - crypto/seqiv.c:seqiv_create
```
**Symbols:**

```
ffffffff814ce580-ffffffff814ce5a6: aead_geniv_free (STB_GLOBAL)
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
