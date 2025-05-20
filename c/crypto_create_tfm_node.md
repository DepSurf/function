# Function: <code>crypto_create_tfm_node</code>

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
void *crypto_create_tfm_node(struct crypto_alg *alg, const struct crypto_type *frontend, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8153bf00)
Location: crypto/api.c:436
Inline: False
Direct callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff8153bf00-ffffffff8153c00a: crypto_create_tfm_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *crypto_create_tfm_node(struct crypto_alg *alg, const struct crypto_type *frontend, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff815445f0)
Location: crypto/api.c:436
Inline: False
Direct callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff815445f0-ffffffff815446fa: crypto_create_tfm_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *crypto_create_tfm_node(struct crypto_alg *alg, const struct crypto_type *frontend, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff815a4d90)
Location: crypto/api.c:436
Inline: False
Direct callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff815a4d90-ffffffff815a4e9a: crypto_create_tfm_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *crypto_create_tfm_node(struct crypto_alg *alg, const struct crypto_type *frontend, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8164b520)
Location: crypto/api.c:491
Inline: False
Direct callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff8164b520-ffffffff8164b62d: crypto_create_tfm_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *crypto_create_tfm_node(struct crypto_alg *alg, const struct crypto_type *frontend, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81704bc0)
Location: crypto/api.c:490
Inline: False
Direct callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff81704bc0-ffffffff81704ccd: crypto_create_tfm_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *crypto_create_tfm_node(struct crypto_alg *alg, const struct crypto_type *frontend, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8173e800)
Location: crypto/api.c:508
Inline: False
Direct callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/akcipher.c:crypto_init_akcipher_ops_sig
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff8173e800-ffffffff8173e8f3: crypto_create_tfm_node (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *crypto_create_tfm_node(struct crypto_alg *alg, const struct crypto_type *frontend, int node);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8177f680)
Location: crypto/api.c:508
Inline: False
Direct callers:
  - crypto/api.c:crypto_alloc_tfm_node
  - crypto/algapi.c:crypto_spawn_tfm2
  - crypto/lskcipher.c:crypto_init_lskcipher_ops_sg
  - crypto/ahash.c:crypto_ahash_init_tfm
  - crypto/akcipher.c:crypto_init_akcipher_ops_sig
  - crypto/scompress.c:crypto_init_scomp_ops_async
```
**Symbols:**

```
ffffffff8177f680-ffffffff8177f773: crypto_create_tfm_node (STB_GLOBAL)
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
