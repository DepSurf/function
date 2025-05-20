# Function: <code>lzo_alloc_ctx</code>

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
<summary>In <code>4.10</code>: ✅</summary>

```c
void *lzo_alloc_ctx(struct crypto_scomp *tfm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/lzo.c (ffffffff814049c0)
Location: crypto/lzo.c:31
Inline: False
Direct callers:
  - crypto/lzo.c:lzo_init
```
**Symbols:**

```
ffffffff814049c0-ffffffff814049fe: lzo_alloc_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void *lzo_alloc_ctx(struct crypto_scomp *tfm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/lzo.c (ffffffff81412136)
Location: crypto/lzo.c:31
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
**Symbols:**

```
ffffffff81412100-ffffffff8141212d: lzo_alloc_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void *lzo_alloc_ctx(struct crypto_scomp *tfm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/lzo.c (ffffffff8143c8a6)
Location: crypto/lzo.c:31
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
**Symbols:**

```
ffffffff8143c870-ffffffff8143c89d: lzo_alloc_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void *lzo_alloc_ctx(struct crypto_scomp *tfm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/lzo.c (ffffffff8146f6e5)
Location: crypto/lzo.c:31
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
**Symbols:**

```
ffffffff8146f6b0-ffffffff8146f6dd: lzo_alloc_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void *lzo_alloc_ctx(struct crypto_scomp *tfm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/lzo.c (ffffffff8148d095)
Location: crypto/lzo.c:31
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
**Symbols:**

```
ffffffff8148d060-ffffffff8148d08d: lzo_alloc_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void *lzo_alloc_ctx(struct crypto_scomp *tfm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/lzo.c (ffffffff814ba785)
Location: crypto/lzo.c:18
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
**Symbols:**

```
ffffffff814ba750-ffffffff814ba77d: lzo_alloc_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *lzo_alloc_ctx(struct crypto_scomp *tfm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/lzo.c (ffffffff814d3555)
Location: crypto/lzo.c:18
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
**Symbols:**

```
ffffffff814d3520-ffffffff814d354d: lzo_alloc_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *lzo_alloc_ctx(struct crypto_scomp *tfm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/lzo.c (ffffffff81532815)
Location: crypto/lzo.c:18
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
**Symbols:**

```
ffffffff81532700-ffffffff8153272d: lzo_alloc_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *lzo_alloc_ctx(struct crypto_scomp *tfm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/lzo.c (ffffffff8154f777)
Location: crypto/lzo.c:18
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
**Symbols:**

```
ffffffff8154f650-ffffffff8154f67d: lzo_alloc_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *lzo_alloc_ctx(struct crypto_scomp *tfm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/lzo.c (ffffffff81557fe7)
Location: crypto/lzo.c:18
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
**Symbols:**

```
ffffffff81557ec0-ffffffff81557eed: lzo_alloc_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *lzo_alloc_ctx(struct crypto_scomp *tfm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/lzo.c (ffffffff815b9297)
Location: crypto/lzo.c:18
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
**Symbols:**

```
ffffffff815b9170-ffffffff815b919d: lzo_alloc_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void *lzo_alloc_ctx(struct crypto_scomp *tfm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/lzo.c (ffffffff81662797)
Location: crypto/lzo.c:18
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
**Symbols:**

```
ffffffff81662630-ffffffff81662671: lzo_alloc_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void *lzo_alloc_ctx(struct crypto_scomp *tfm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/lzo.c (ffffffff8171c8a7)
Location: crypto/lzo.c:18
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
**Symbols:**

```
ffffffff8171c710-ffffffff8171c751: lzo_alloc_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void *lzo_alloc_ctx(struct crypto_scomp *tfm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/lzo.c (ffffffff81758047)
Location: crypto/lzo.c:18
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
**Symbols:**

```
ffffffff81757eb0-ffffffff81757ef1: lzo_alloc_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void *lzo_alloc_ctx(struct crypto_scomp *tfm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/lzo.c (ffffffff81799f47)
Location: crypto/lzo.c:18
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
**Symbols:**

```
ffffffff81799db0-ffffffff81799df1: lzo_alloc_ctx (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void *lzo_alloc_ctx(struct crypto_scomp *tfm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/lzo.c (ffff8000105cfde0)
Location: crypto/lzo.c:18
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
**Symbols:**

```
ffff8000105cfd90-ffff8000105cfdc4: lzo_alloc_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *lzo_alloc_ctx(struct crypto_scomp *tfm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/lzo.c (c077d94c)
Location: crypto/lzo.c:18
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
**Symbols:**

```
c077d908-c077d938: lzo_alloc_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void *lzo_alloc_ctx(struct crypto_scomp *tfm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/lzo.c (c00000000075be90)
Location: crypto/lzo.c:18
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
**Symbols:**

```
c00000000075be00-c00000000075be64: lzo_alloc_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void *lzo_alloc_ctx(struct crypto_scomp *tfm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/lzo.c (ffffffe000414bf4)
Location: crypto/lzo.c:18
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
**Symbols:**

```
ffffffe000414ba6-ffffffe000414bde: lzo_alloc_ctx (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void *lzo_alloc_ctx(struct crypto_scomp *tfm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/lzo.c (ffffffff814cbb35)
Location: crypto/lzo.c:18
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
**Symbols:**

```
ffffffff814cbb00-ffffffff814cbb2d: lzo_alloc_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *lzo_alloc_ctx(struct crypto_scomp *tfm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/lzo.c (ffffffff814bc555)
Location: crypto/lzo.c:18
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
**Symbols:**

```
ffffffff814bc520-ffffffff814bc54d: lzo_alloc_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *lzo_alloc_ctx(struct crypto_scomp *tfm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/lzo.c (ffffffff814c7bc5)
Location: crypto/lzo.c:18
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
**Symbols:**

```
ffffffff814c7b90-ffffffff814c7bbd: lzo_alloc_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *lzo_alloc_ctx(struct crypto_scomp *tfm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/lzo.c (ffffffff814e0695)
Location: crypto/lzo.c:18
Inline: True
Inline callers:
  - crypto/lzo.c:lzo_init
```
**Symbols:**

```
ffffffff814e0660-ffffffff814e068d: lzo_alloc_ctx (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
