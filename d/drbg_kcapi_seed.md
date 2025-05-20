# Function: <code>drbg_kcapi_seed</code>

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
int drbg_kcapi_seed(struct crypto_rng *tfm, const u8 *seed, unsigned int slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff813ee2e0)
Location: crypto/drbg.c:1856
Inline: False
```
**Symbols:**

```
ffffffff813ee2e0-ffffffff813ee5b0: drbg_kcapi_seed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int drbg_kcapi_seed(struct crypto_rng *tfm, const u8 *seed, unsigned int slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff81407b20)
Location: crypto/drbg.c:1882
Inline: False
```
**Symbols:**

```
ffffffff81407b20-ffffffff81407df0: drbg_kcapi_seed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int drbg_kcapi_seed(struct crypto_rng *tfm, const u8 *seed, unsigned int slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff81415250)
Location: crypto/drbg.c:1881
Inline: False
```
**Symbols:**

```
ffffffff81415250-ffffffff8141552b: drbg_kcapi_seed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int drbg_kcapi_seed(struct crypto_rng *tfm, const u8 *seed, unsigned int slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff8143fa20)
Location: crypto/drbg.c:1863
Inline: False
```
**Symbols:**

```
ffffffff8143fa20-ffffffff8143fcfb: drbg_kcapi_seed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int drbg_kcapi_seed(struct crypto_rng *tfm, const u8 *seed, unsigned int slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (0)
Location: crypto/drbg.c:1865
Inline: False
```
**Symbols:**

```
ffffffff81472860-ffffffff81472b58: drbg_kcapi_seed (STB_LOCAL)
ffffffff81473447-ffffffff81473458: drbg_kcapi_seed.cold.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int drbg_kcapi_seed(struct crypto_rng *tfm, const u8 *seed, unsigned int slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (0)
Location: crypto/drbg.c:1862
Inline: False
```
**Symbols:**

```
ffffffff8148fcb0-ffffffff8148ffa8: drbg_kcapi_seed (STB_LOCAL)
ffffffff81491000-ffffffff81491011: drbg_kcapi_seed.cold.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int drbg_kcapi_seed(struct crypto_rng *tfm, const u8 *seed, unsigned int slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (0)
Location: crypto/drbg.c:1949
Inline: False
```
**Symbols:**

```
ffffffff814be560-ffffffff814be846: drbg_kcapi_seed (STB_LOCAL)
ffffffff814be8ca-ffffffff814be8db: drbg_kcapi_seed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int drbg_kcapi_seed(struct crypto_rng *tfm, const u8 *seed, unsigned int slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (0)
Location: crypto/drbg.c:1949
Inline: False
```
**Symbols:**

```
ffffffff814d73b0-ffffffff814d7696: drbg_kcapi_seed (STB_LOCAL)
ffffffff814d771a-ffffffff814d772b: drbg_kcapi_seed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int drbg_kcapi_seed(struct crypto_rng *tfm, const u8 *seed, unsigned int slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffff815349e0)
Location: crypto/drbg.c:1965
Inline: False
```
**Symbols:**

```
ffffffff815349e0-ffffffff81534b15: drbg_kcapi_seed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int drbg_kcapi_seed(struct crypto_rng *tfm, const u8 *seed, unsigned int slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (0)
Location: crypto/drbg.c:1965
Inline: False
```
**Symbols:**

```
ffffffff81551930-ffffffff81551a90: drbg_kcapi_seed (STB_LOCAL)
ffffffff81bf219a-ffffffff81bf21b2: drbg_kcapi_seed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int drbg_kcapi_seed(struct crypto_rng *tfm, const u8 *seed, unsigned int slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (0)
Location: crypto/drbg.c:1966
Inline: False
```
**Symbols:**

```
ffffffff81559f50-ffffffff8155a21a: drbg_kcapi_seed (STB_LOCAL)
ffffffff81be4141-ffffffff81be416a: drbg_kcapi_seed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int drbg_kcapi_seed(struct crypto_rng *tfm, const u8 *seed, unsigned int slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (0)
Location: crypto/drbg.c:1966
Inline: False
```
**Symbols:**

```
ffffffff815bb1d0-ffffffff815bb51a: drbg_kcapi_seed (STB_LOCAL)
ffffffff81cd78a6-ffffffff81cd78e3: drbg_kcapi_seed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int drbg_kcapi_seed(struct crypto_rng *tfm, const u8 *seed, unsigned int slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (0)
Location: crypto/drbg.c:1970
Inline: False
```
**Symbols:**

```
ffffffff81664bc0-ffffffff81664db6: drbg_kcapi_seed (STB_LOCAL)
ffffffff81e8ab19-ffffffff81e8ab3f: drbg_kcapi_seed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int drbg_kcapi_seed(struct crypto_rng *tfm, const u8 *seed, unsigned int slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (0)
Location: crypto/drbg.c:1968
Inline: False
```
**Symbols:**

```
ffffffff8171ef40-ffffffff8171f140: drbg_kcapi_seed (STB_LOCAL)
ffffffff82075870-ffffffff82075885: drbg_kcapi_seed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int drbg_kcapi_seed(struct crypto_rng *tfm, const u8 *seed, unsigned int slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (0)
Location: crypto/drbg.c:1968
Inline: False
```
**Symbols:**

```
ffffffff8175a850-ffffffff8175aa42: drbg_kcapi_seed (STB_LOCAL)
ffffffff820f54d8-ffffffff820f54ed: drbg_kcapi_seed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int drbg_kcapi_seed(struct crypto_rng *tfm, const u8 *seed, unsigned int slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (0)
Location: crypto/drbg.c:1952
Inline: False
```
**Symbols:**

```
ffffffff8179c750-ffffffff8179c942: drbg_kcapi_seed (STB_LOCAL)
ffffffff821d276f-ffffffff821d2784: drbg_kcapi_seed.cold (STB_LOCAL)
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
int drbg_kcapi_seed(struct crypto_rng *tfm, const u8 *seed, unsigned int slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffff8000105d1900)
Location: crypto/drbg.c:1949
Inline: False
```
**Symbols:**

```
ffff8000105d1900-ffff8000105d1bac: drbg_kcapi_seed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int drbg_kcapi_seed(struct crypto_rng *tfm, const u8 *seed, unsigned int slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (c0780800)
Location: crypto/drbg.c:1949
Inline: False
```
**Symbols:**

```
c0780800-c0780a9c: drbg_kcapi_seed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int drbg_kcapi_seed(struct crypto_rng *tfm, const u8 *seed, unsigned int slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (c000000000760160)
Location: crypto/drbg.c:1949
Inline: False
```
**Symbols:**

```
c000000000760160-c0000000007604f4: drbg_kcapi_seed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int drbg_kcapi_seed(struct crypto_rng *tfm, const u8 *seed, unsigned int slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/drbg.c (ffffffe00041661a)
Location: crypto/drbg.c:1949
Inline: False
```
**Symbols:**

```
ffffffe00041661a-ffffffe000416844: drbg_kcapi_seed (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int drbg_kcapi_seed(struct crypto_rng *tfm, const u8 *seed, unsigned int slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (0)
Location: crypto/drbg.c:1949
Inline: False
```
**Symbols:**

```
ffffffff814cf990-ffffffff814cfc76: drbg_kcapi_seed (STB_LOCAL)
ffffffff814cfcfa-ffffffff814cfd0b: drbg_kcapi_seed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int drbg_kcapi_seed(struct crypto_rng *tfm, const u8 *seed, unsigned int slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (0)
Location: crypto/drbg.c:1949
Inline: False
```
**Symbols:**

```
ffffffff814c03b0-ffffffff814c0696: drbg_kcapi_seed (STB_LOCAL)
ffffffff814c071a-ffffffff814c072b: drbg_kcapi_seed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int drbg_kcapi_seed(struct crypto_rng *tfm, const u8 *seed, unsigned int slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (0)
Location: crypto/drbg.c:1949
Inline: False
```
**Symbols:**

```
ffffffff814cba20-ffffffff814cbd06: drbg_kcapi_seed (STB_LOCAL)
ffffffff814cbd8a-ffffffff814cbd9b: drbg_kcapi_seed.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int drbg_kcapi_seed(struct crypto_rng *tfm, const u8 *seed, unsigned int slen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In crypto/drbg.c (0)
Location: crypto/drbg.c:1949
Inline: False
```
**Symbols:**

```
ffffffff814e44f0-ffffffff814e47d6: drbg_kcapi_seed (STB_LOCAL)
ffffffff814e485a-ffffffff814e486b: drbg_kcapi_seed.cold (STB_LOCAL)
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
