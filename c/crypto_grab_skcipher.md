# Function: <code>crypto_grab_skcipher</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int crypto_grab_skcipher(struct crypto_skcipher_spawn *spawn, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/ablkcipher.c (ffffffff813a06d0)
Location: crypto/ablkcipher.c:662
Inline: False
```
**Symbols:**

```
ffffffff813a06d0-ffffffff813a0730: crypto_grab_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int crypto_grab_skcipher(struct crypto_skcipher_spawn *spawn, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff813de130)
Location: crypto/skcipher.c:328
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/ctr.c:crypto_rfc3686_create
```
**Symbols:**

```
ffffffff813de130-ffffffff813de148: crypto_grab_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int crypto_grab_skcipher(struct crypto_skcipher_spawn *spawn, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff813f5b60)
Location: crypto/skcipher.c:870
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
```
**Symbols:**

```
ffffffff813f5b60-ffffffff813f5b78: crypto_grab_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int crypto_grab_skcipher(struct crypto_skcipher_spawn *spawn, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81401e00)
Location: crypto/skcipher.c:910
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
```
**Symbols:**

```
ffffffff81401e00-ffffffff81401e18: crypto_grab_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int crypto_grab_skcipher(struct crypto_skcipher_spawn *spawn, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8142a460)
Location: crypto/skcipher.c:916
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff8142a460-ffffffff8142a478: crypto_grab_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int crypto_grab_skcipher(struct crypto_skcipher_spawn *spawn, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8145d1b0)
Location: crypto/skcipher.c:939
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff8145d1b0-ffffffff8145d1c8: crypto_grab_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int crypto_grab_skcipher(struct crypto_skcipher_spawn *spawn, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8147aa70)
Location: crypto/skcipher.c:943
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff8147aa70-ffffffff8147aa88: crypto_grab_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int crypto_grab_skcipher(struct crypto_skcipher_spawn *spawn, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814a8bc0)
Location: crypto/skcipher.c:977
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff814a8bc0-ffffffff814a8bd8: crypto_grab_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int crypto_grab_skcipher(struct crypto_skcipher_spawn *spawn, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814c3820)
Location: crypto/skcipher.c:981
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff814c3820-ffffffff814c3838: crypto_grab_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int crypto_grab_skcipher(struct crypto_skcipher_spawn *spawn, struct crypto_instance *inst, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81522a20)
Location: crypto/skcipher.c:749
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff81522a20-ffffffff81522a38: crypto_grab_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int crypto_grab_skcipher(struct crypto_skcipher_spawn *spawn, struct crypto_instance *inst, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8153f8e0)
Location: crypto/skcipher.c:749
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:xts_create
  - crypto/xts.c:xts_create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff8153f8e0-ffffffff8153f8f8: crypto_grab_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int crypto_grab_skcipher(struct crypto_skcipher_spawn *spawn, struct crypto_instance *inst, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81547e70)
Location: crypto/skcipher.c:744
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:xts_create
  - crypto/xts.c:xts_create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff81547e70-ffffffff81547e88: crypto_grab_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int crypto_grab_skcipher(struct crypto_skcipher_spawn *spawn, struct crypto_instance *inst, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff815a8650)
Location: crypto/skcipher.c:744
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:xts_create
  - crypto/xts.c:xts_create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff815a8650-ffffffff815a8668: crypto_grab_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int crypto_grab_skcipher(struct crypto_skcipher_spawn *spawn, struct crypto_instance *inst, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff8164f9f0)
Location: crypto/skcipher.c:744
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:xts_create
  - crypto/xts.c:xts_create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff8164f9f0-ffffffff8164fa17: crypto_grab_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int crypto_grab_skcipher(struct crypto_skcipher_spawn *spawn, struct crypto_instance *inst, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81708e40)
Location: crypto/skcipher.c:744
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:xts_create
  - crypto/xts.c:xts_create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff81708e40-ffffffff81708e67: crypto_grab_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int crypto_grab_skcipher(struct crypto_skcipher_spawn *spawn, struct crypto_instance *inst, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81742510)
Location: crypto/skcipher.c:791
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:xts_create
  - crypto/xts.c:xts_create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff81742510-ffffffff81742537: crypto_grab_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int crypto_grab_skcipher(struct crypto_skcipher_spawn *spawn, struct crypto_instance *inst, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff81784b20)
Location: crypto/skcipher.c:890
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:xts_create
  - crypto/xts.c:xts_create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff81784b20-ffffffff81784b47: crypto_grab_skcipher (STB_GLOBAL)
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
int crypto_grab_skcipher(struct crypto_skcipher_spawn *spawn, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffff8000105be0d0)
Location: crypto/skcipher.c:981
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffff8000105be0d0-ffff8000105be128: crypto_grab_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int crypto_grab_skcipher(struct crypto_skcipher_spawn *spawn, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c076beb4)
Location: crypto/skcipher.c:981
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
c076beb4-c076bedc: crypto_grab_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int crypto_grab_skcipher(struct crypto_skcipher_spawn *spawn, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (c000000000745780)
Location: crypto/skcipher.c:981
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
c000000000745780-c0000000007457c0: crypto_grab_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int crypto_grab_skcipher(struct crypto_skcipher_spawn *spawn, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffe00040356e)
Location: crypto/skcipher.c:981
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffe00040356e-ffffffe0004035ba: crypto_grab_skcipher (STB_GLOBAL)
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
int crypto_grab_skcipher(struct crypto_skcipher_spawn *spawn, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814bbe00)
Location: crypto/skcipher.c:981
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff814bbe00-ffffffff814bbe18: crypto_grab_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int crypto_grab_skcipher(struct crypto_skcipher_spawn *spawn, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814ac820)
Location: crypto/skcipher.c:981
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff814ac820-ffffffff814ac838: crypto_grab_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int crypto_grab_skcipher(struct crypto_skcipher_spawn *spawn, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814b7e90)
Location: crypto/skcipher.c:981
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff814b7e90-ffffffff814b7ea8: crypto_grab_skcipher (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int crypto_grab_skcipher(struct crypto_skcipher_spawn *spawn, const char *name, u32 type, u32 mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/skcipher.c (ffffffff814d0970)
Location: crypto/skcipher.c:981
Inline: False
Direct callers:
  - crypto/cts.c:crypto_cts_create
  - crypto/xts.c:create
  - crypto/xts.c:create
  - crypto/ctr.c:crypto_rfc3686_create
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff814d0970-ffffffff814d0988: crypto_grab_skcipher (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct crypto_instance *inst</code>
</li>
<li>
<b>Param reordered. </b>
<code>spawn, name, type, mask</code> ➡️ <code>spawn, inst, name, type, mask</code>
</li>
</ul>
</details>
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
