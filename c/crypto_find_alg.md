# Function: <code>crypto_find_alg</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct crypto_alg *crypto_find_alg(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8139c0e0)
Location: crypto/api.c:499
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
Direct callers:
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/algapi.c:crypto_attr_alg2
```
**Symbols:**

```
ffffffff8139c0e0-ffffffff8139c122: crypto_find_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct crypto_alg *crypto_find_alg(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff813d921e)
Location: crypto/api.c:499
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_attr_alg2
  - crypto/algapi.c:crypto_grab_spawn
```
**Symbols:**

```
ffffffff813d8fd0-ffffffff813d9012: crypto_find_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct crypto_alg *crypto_find_alg(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff813f0b2e)
Location: crypto/api.c:483
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_attr_alg2
  - crypto/algapi.c:crypto_grab_spawn
```
**Symbols:**

```
ffffffff813f0920-ffffffff813f0962: crypto_find_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct crypto_alg *crypto_find_alg(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff813fcdbe)
Location: crypto/api.c:483
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_attr_alg2
  - crypto/algapi.c:crypto_grab_spawn
```
**Symbols:**

```
ffffffff813fcbc0-ffffffff813fcc02: crypto_find_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct crypto_alg *crypto_find_alg(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81425312)
Location: crypto/api.c:484
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_attr_alg2
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff814250f0-ffffffff81425135: crypto_find_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct crypto_alg *crypto_find_alg(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81458b62)
Location: crypto/api.c:493
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_attr_alg2
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff814588f0-ffffffff81458918: crypto_find_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct crypto_alg *crypto_find_alg(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81475d82)
Location: crypto/api.c:493
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_attr_alg2
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff81475d30-ffffffff81475d58: crypto_find_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct crypto_alg *crypto_find_alg(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814a3dbf)
Location: crypto/api.c:488
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_attr_alg2
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff814a3c20-ffffffff814a3c49: crypto_find_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct crypto_alg *crypto_find_alg(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814be9ef)
Location: crypto/api.c:489
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_attr_alg2
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff814be850-ffffffff814be879: crypto_find_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct crypto_alg *crypto_find_alg(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8151f1bf)
Location: crypto/api.c:477
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_grab_spawn
```
**Symbols:**

```
ffffffff8151ee70-ffffffff8151ee98: crypto_find_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct crypto_alg *crypto_find_alg(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8153c041)
Location: crypto/api.c:479
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_grab_spawn
```
**Symbols:**

```
ffffffff8153bcc0-ffffffff8153bce8: crypto_find_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct crypto_alg *crypto_find_alg(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81544731)
Location: crypto/api.c:479
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_grab_spawn
```
**Symbols:**

```
ffffffff815443b0-ffffffff815443d8: crypto_find_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct crypto_alg *crypto_find_alg(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff815a4ed1)
Location: crypto/api.c:479
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_grab_spawn
```
**Symbols:**

```
ffffffff815a4b50-ffffffff815a4b78: crypto_find_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct crypto_alg *crypto_find_alg(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8164bb06)
Location: crypto/api.c:534
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_grab_spawn
```
**Symbols:**

```
ffffffff8164b9b0-ffffffff8164b9e5: crypto_find_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct crypto_alg *crypto_find_alg(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff81704d06)
Location: crypto/api.c:533
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_grab_spawn
```
**Symbols:**

```
ffffffff81704a60-ffffffff81704a95: crypto_find_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct crypto_alg *crypto_find_alg(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8173ef26)
Location: crypto/api.c:569
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_grab_spawn
```
**Symbols:**

```
ffffffff8173eda0-ffffffff8173edd5: crypto_find_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct crypto_alg *crypto_find_alg(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8177fda6)
Location: crypto/api.c:569
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm_node
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_grab_spawn
```
**Symbols:**

```
ffffffff8177fce0-ffffffff8177fd15: crypto_find_alg (STB_GLOBAL)
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
struct crypto_alg *crypto_find_alg(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffff8000105b7a5c)
Location: crypto/api.c:489
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_attr_alg2
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffff8000105b7850-ffff8000105b78b4: crypto_find_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct crypto_alg *crypto_find_alg(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (c07665e4)
Location: crypto/api.c:489
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_attr_alg2
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
c07664fc-c0766544: crypto_find_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct crypto_alg *crypto_find_alg(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (c00000000073c5e4)
Location: crypto/api.c:489
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_attr_alg2
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
c00000000073c530-c00000000073c578: crypto_find_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct crypto_alg *crypto_find_alg(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffe0003fe038)
Location: crypto/api.c:489
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_attr_alg2
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffe0003fdfae-ffffffe0003fe00a: crypto_find_alg (STB_GLOBAL)
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
struct crypto_alg *crypto_find_alg(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814b6fcf)
Location: crypto/api.c:489
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_attr_alg2
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff814b6e30-ffffffff814b6e59: crypto_find_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct crypto_alg *crypto_find_alg(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814a79ef)
Location: crypto/api.c:489
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_attr_alg2
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff814a7850-ffffffff814a7879: crypto_find_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct crypto_alg *crypto_find_alg(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814b305f)
Location: crypto/api.c:489
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_attr_alg2
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff814b2ec0-ffffffff814b2ee9: crypto_find_alg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct crypto_alg *crypto_find_alg(const char *alg_name, const struct crypto_type *frontend, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff814cbadf)
Location: crypto/api.c:489
Inline: True
Inline callers:
  - crypto/api.c:crypto_alloc_tfm
Direct callers:
  - crypto/algapi.c:crypto_type_has_alg
  - crypto/algapi.c:crypto_attr_alg2
  - crypto/algapi.c:crypto_grab_spawn
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff814cb940-ffffffff814cb969: crypto_find_alg (STB_GLOBAL)
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
