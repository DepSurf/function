# Function: <code>crypto_inst_setname</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int crypto_inst_setname(struct crypto_instance *inst, const char *name, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813da760)
Location: crypto/algapi.c:814
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_alloc_instance2
  - crypto/cts.c:crypto_cts_create
```
**Symbols:**

```
ffffffff813da760-ffffffff813da7ce: crypto_inst_setname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int crypto_inst_setname(struct crypto_instance *inst, const char *name, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813f20a0)
Location: crypto/algapi.c:815
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_alloc_instance2
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
```
**Symbols:**

```
ffffffff813f20a0-ffffffff813f210e: crypto_inst_setname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int crypto_inst_setname(struct crypto_instance *inst, const char *name, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff813fe350)
Location: crypto/algapi.c:815
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_alloc_instance2
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
```
**Symbols:**

```
ffffffff813fe350-ffffffff813fe3bf: crypto_inst_setname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int crypto_inst_setname(struct crypto_instance *inst, const char *name, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81426900)
Location: crypto/algapi.c:827
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_alloc_instance2
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
```
**Symbols:**

```
ffffffff81426900-ffffffff8142696f: crypto_inst_setname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int crypto_inst_setname(struct crypto_instance *inst, const char *name, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81459810)
Location: crypto/algapi.c:824
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_alloc_instance2
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
```
**Symbols:**

```
ffffffff81459810-ffffffff8145987f: crypto_inst_setname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int crypto_inst_setname(struct crypto_instance *inst, const char *name, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81476a70)
Location: crypto/algapi.c:833
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_alloc_instance2
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
```
**Symbols:**

```
ffffffff81476a70-ffffffff81476adf: crypto_inst_setname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int crypto_inst_setname(struct crypto_instance *inst, const char *name, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814a47a0)
Location: crypto/algapi.c:844
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_alloc_instance
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
```
**Symbols:**

```
ffffffff814a47a0-ffffffff814a480f: crypto_inst_setname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int crypto_inst_setname(struct crypto_instance *inst, const char *name, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814bf430)
Location: crypto/algapi.c:854
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_alloc_instance
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
```
**Symbols:**

```
ffffffff814bf430-ffffffff814bf49f: crypto_inst_setname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int crypto_inst_setname(struct crypto_instance *inst, const char *name, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8151fae0)
Location: crypto/algapi.c:870
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
```
**Symbols:**

```
ffffffff8151fae0-ffffffff8151fb4f: crypto_inst_setname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int crypto_inst_setname(struct crypto_instance *inst, const char *name, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8153c950)
Location: crypto/algapi.c:889
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/hmac.c:hmac_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:xts_create
```
**Symbols:**

```
ffffffff8153c950-ffffffff8153c9bf: crypto_inst_setname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int crypto_inst_setname(struct crypto_instance *inst, const char *name, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81545030)
Location: crypto/algapi.c:889
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/hmac.c:hmac_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:xts_create
```
**Symbols:**

```
ffffffff81545030-ffffffff8154509f: crypto_inst_setname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int crypto_inst_setname(struct crypto_instance *inst, const char *name, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff815a5790)
Location: crypto/algapi.c:871
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/hmac.c:hmac_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:xts_create
```
**Symbols:**

```
ffffffff815a5790-ffffffff815a57ff: crypto_inst_setname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int crypto_inst_setname(struct crypto_instance *inst, const char *name, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8164c510)
Location: crypto/algapi.c:895
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/dh.c:__dh_safe_prime_create
  - crypto/hmac.c:hmac_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:xts_create
```
**Symbols:**

```
ffffffff8164c510-ffffffff8164c58e: crypto_inst_setname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crypto_inst_setname(struct crypto_instance *inst, const char *name, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff81705740)
Location: crypto/algapi.c:914
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/dh.c:__dh_safe_prime_create
  - crypto/hmac.c:hmac_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:xts_create
```
**Symbols:**

```
ffffffff81705740-ffffffff817057be: crypto_inst_setname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_inst_setname(struct crypto_instance *inst, const char *name, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff8173fa30)
Location: crypto/algapi.c:926
Inline: False
Direct callers:
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/dh.c:__dh_safe_prime_create
  - crypto/hmac.c:hmac_create
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:xts_create
```
**Symbols:**

```
ffffffff8173fa30-ffffffff8173faae: crypto_inst_setname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_inst_setname(struct crypto_instance *inst, const char *name, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff817808b0)
Location: crypto/algapi.c:927
Inline: False
Direct callers:
  - crypto/lskcipher.c:lskcipher_alloc_instance_simple
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/dh.c:__dh_safe_prime_create
  - crypto/hmac.c:hmac_create
  - crypto/ecb.c:lskcipher_alloc_instance_simple2
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:xts_create
```
**Symbols:**

```
ffffffff817808b0-ffffffff8178092e: crypto_inst_setname (STB_GLOBAL)
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
int crypto_inst_setname(struct crypto_instance *inst, const char *name, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffff8000105b89c0)
Location: crypto/algapi.c:854
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_alloc_instance
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
```
**Symbols:**

```
ffff8000105b89c0-ffff8000105b8a4c: crypto_inst_setname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int crypto_inst_setname(struct crypto_instance *inst, const char *name, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (c0767550)
Location: crypto/algapi.c:854
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_alloc_instance
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
```
**Symbols:**

```
c0767550-c07675d8: crypto_inst_setname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int crypto_inst_setname(struct crypto_instance *inst, const char *name, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (c00000000073dcb0)
Location: crypto/algapi.c:854
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_alloc_instance
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
```
**Symbols:**

```
c00000000073dcb0-c00000000073dd58: crypto_inst_setname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int crypto_inst_setname(struct crypto_instance *inst, const char *name, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffe0003feff0)
Location: crypto/algapi.c:854
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_alloc_instance
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
```
**Symbols:**

```
ffffffe0003feff0-ffffffe0003ff072: crypto_inst_setname (STB_GLOBAL)
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
int crypto_inst_setname(struct crypto_instance *inst, const char *name, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814b7a10)
Location: crypto/algapi.c:854
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_alloc_instance
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
```
**Symbols:**

```
ffffffff814b7a10-ffffffff814b7a7f: crypto_inst_setname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int crypto_inst_setname(struct crypto_instance *inst, const char *name, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814a8430)
Location: crypto/algapi.c:854
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_alloc_instance
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
```
**Symbols:**

```
ffffffff814a8430-ffffffff814a849f: crypto_inst_setname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int crypto_inst_setname(struct crypto_instance *inst, const char *name, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814b3aa0)
Location: crypto/algapi.c:854
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_alloc_instance
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
```
**Symbols:**

```
ffffffff814b3aa0-ffffffff814b3b0f: crypto_inst_setname (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int crypto_inst_setname(struct crypto_instance *inst, const char *name, struct crypto_alg *alg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/algapi.c (ffffffff814cc520)
Location: crypto/algapi.c:854
Inline: False
Direct callers:
  - crypto/algapi.c:crypto_alloc_instance
  - crypto/skcipher.c:skcipher_alloc_instance_simple
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
```
**Symbols:**

```
ffffffff814cc520-ffffffff814cc58f: crypto_inst_setname (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
