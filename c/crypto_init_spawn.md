# Function: <code>crypto_init_spawn</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int crypto_init_spawn(struct crypto_spawn *spawn, struct crypto_alg *alg, struct crypto_instance *inst, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8139d3e0)
Location: crypto/algapi.c:588
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_init_spawn2
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_alloc_instance
  - crypto/ablkcipher.c:crypto_grab_skcipher
  - crypto/blkcipher.c:skcipher_geniv_alloc
```
**Symbols:**

```
ffffffff8139d3e0-ffffffff8139d447: crypto_init_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int crypto_init_spawn(struct crypto_spawn *spawn, struct crypto_alg *alg, struct crypto_instance *inst, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813da2a0)
Location: crypto/algapi.c:587
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_alloc_instance
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_init_spawn2
```
**Symbols:**

```
ffffffff813da2a0-ffffffff813da30e: crypto_init_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int crypto_init_spawn(struct crypto_spawn *spawn, struct crypto_alg *alg, struct crypto_instance *inst, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813f1be0)
Location: crypto/algapi.c:588
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_alloc_instance
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_init_spawn2
```
**Symbols:**

```
ffffffff813f1be0-ffffffff813f1c4e: crypto_init_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int crypto_init_spawn(struct crypto_spawn *spawn, struct crypto_alg *alg, struct crypto_instance *inst, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813fdde0)
Location: crypto/algapi.c:588
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_alloc_instance
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_init_spawn2
```
**Symbols:**

```
ffffffff813fdde0-ffffffff813fde4e: crypto_init_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int crypto_init_spawn(struct crypto_spawn *spawn, struct crypto_alg *alg, struct crypto_instance *inst, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81426390)
Location: crypto/algapi.c:600
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_alloc_instance
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_init_spawn2
```
**Symbols:**

```
ffffffff81426390-ffffffff814263fe: crypto_init_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int crypto_init_spawn(struct crypto_spawn *spawn, struct crypto_alg *alg, struct crypto_instance *inst, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81459290)
Location: crypto/algapi.c:597
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_alloc_instance
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_init_spawn2
```
**Symbols:**

```
ffffffff81459290-ffffffff814592fe: crypto_init_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int crypto_init_spawn(struct crypto_spawn *spawn, struct crypto_alg *alg, struct crypto_instance *inst, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814767b0)
Location: crypto/algapi.c:606
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_alloc_instance
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_init_spawn2
```
**Symbols:**

```
ffffffff814767b0-ffffffff8147681e: crypto_init_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int crypto_init_spawn(struct crypto_spawn *spawn, struct crypto_alg *alg, struct crypto_instance *inst, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814a4590)
Location: crypto/algapi.c:614
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_init_spawn2
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
**Symbols:**

```
ffffffff814a4590-ffffffff814a4615: crypto_init_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int crypto_init_spawn(struct crypto_spawn *spawn, struct crypto_alg *alg, struct crypto_instance *inst, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814bf1c0)
Location: crypto/algapi.c:632
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_init_spawn2
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
**Symbols:**

```
ffffffff814bf1c0-ffffffff814bf245: crypto_init_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int crypto_init_spawn(struct crypto_spawn *spawn, struct crypto_alg *alg, struct crypto_instance *inst, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffff8000105b8578)
Location: crypto/algapi.c:632
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_init_spawn2
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
**Symbols:**

```
ffff8000105b8578-ffff8000105b862c: crypto_init_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int crypto_init_spawn(struct crypto_spawn *spawn, struct crypto_alg *alg, struct crypto_instance *inst, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (c0767184)
Location: crypto/algapi.c:632
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_init_spawn2
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
**Symbols:**

```
c0767184-c0767238: crypto_init_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int crypto_init_spawn(struct crypto_spawn *spawn, struct crypto_alg *alg, struct crypto_instance *inst, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (c00000000073d620)
Location: crypto/algapi.c:632
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_init_spawn2
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
**Symbols:**

```
c00000000073d620-c00000000073d6e8: crypto_init_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int crypto_init_spawn(struct crypto_spawn *spawn, struct crypto_alg *alg, struct crypto_instance *inst, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffe0003fecf6)
Location: crypto/algapi.c:632
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_init_spawn2
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
**Symbols:**

```
ffffffe0003fecf6-ffffffe0003fed82: crypto_init_spawn (STB_GLOBAL)
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
int crypto_init_spawn(struct crypto_spawn *spawn, struct crypto_alg *alg, struct crypto_instance *inst, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814b77a0)
Location: crypto/algapi.c:632
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_init_spawn2
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
**Symbols:**

```
ffffffff814b77a0-ffffffff814b7825: crypto_init_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int crypto_init_spawn(struct crypto_spawn *spawn, struct crypto_alg *alg, struct crypto_instance *inst, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814a81c0)
Location: crypto/algapi.c:632
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_init_spawn2
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
**Symbols:**

```
ffffffff814a81c0-ffffffff814a8245: crypto_init_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int crypto_init_spawn(struct crypto_spawn *spawn, struct crypto_alg *alg, struct crypto_instance *inst, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814b3830)
Location: crypto/algapi.c:632
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_init_spawn2
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
**Symbols:**

```
ffffffff814b3830-ffffffff814b38b5: crypto_init_spawn (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int crypto_init_spawn(struct crypto_spawn *spawn, struct crypto_alg *alg, struct crypto_instance *inst, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814cc2b0)
Location: crypto/algapi.c:632
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_init_spawn2
  - crypto/skcipher.c:skcipher_alloc_instance_simple
```
**Symbols:**

```
ffffffff814cc2b0-ffffffff814cc335: crypto_init_spawn (STB_GLOBAL)
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
