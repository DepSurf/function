# Function: <code>init_desc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct shash_desc *init_desc(char type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff8139b260)
Location: security/integrity/evm/evm_crypto.c:35
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
```
**Symbols:**

```
ffffffff8139b260-ffffffff8139b3c8: init_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct shash_desc *init_desc(char type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff813d80b0)
Location: security/integrity/evm/evm_crypto.c:74
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff813d80b0-ffffffff813d8248: init_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct shash_desc *init_desc(char type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff813efd60)
Location: security/integrity/evm/evm_crypto.c:74
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff813efd60-ffffffff813efef8: init_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct shash_desc *init_desc(char type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff813fc390)
Location: security/integrity/evm/evm_crypto.c:74
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff813fc390-ffffffff813fc517: init_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct shash_desc *init_desc(char type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff81424860)
Location: security/integrity/evm/evm_crypto.c:74
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff81424860-ffffffff81424a41: init_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct shash_desc *init_desc(char type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:77
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff81456fa0-ffffffff81457143: init_desc (STB_LOCAL)
ffffffff8145773c-ffffffff81457786: init_desc.cold.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct shash_desc *init_desc(char type, uint8_t hash_algo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:77
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff81474440-ffffffff814745f2: init_desc (STB_LOCAL)
ffffffff81474c3c-ffffffff81474c86: init_desc.cold.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct shash_desc *init_desc(char type, uint8_t hash_algo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:74
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff814a2170-ffffffff814a2310: init_desc (STB_LOCAL)
ffffffff814a2933-ffffffff814a297d: init_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct shash_desc *init_desc(char type, uint8_t hash_algo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:74
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff814bce40-ffffffff814bcfe0: init_desc (STB_LOCAL)
ffffffff814bd603-ffffffff814bd64d: init_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct shash_desc *init_desc(char type, uint8_t hash_algo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:72
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff8151d760-ffffffff8151d8f5: init_desc (STB_LOCAL)
ffffffff8151df0f-ffffffff8151df51: init_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct shash_desc *init_desc(char type, uint8_t hash_algo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:72
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff8153a5d0-ffffffff8153a77b: init_desc (STB_LOCAL)
ffffffff81bf1f7f-ffffffff81bf1fc4: init_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct shash_desc *init_desc(char type, uint8_t hash_algo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:72
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff81542c90-ffffffff81542e3b: init_desc (STB_LOCAL)
ffffffff81be3fa3-ffffffff81be3fe8: init_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct shash_desc *init_desc(char type, uint8_t hash_algo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:74
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff815a3380-ffffffff815a357b: init_desc (STB_LOCAL)
ffffffff81cd7517-ffffffff81cd756d: init_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct shash_desc *init_desc(char type, uint8_t hash_algo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:74
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff81649be0-ffffffff81649dda: init_desc (STB_LOCAL)
ffffffff81e8a801-ffffffff81e8a838: init_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct shash_desc *init_desc(char type, uint8_t hash_algo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:74
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff81702c20-ffffffff81702e39: init_desc (STB_LOCAL)
ffffffff82075664-ffffffff82075678: init_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct shash_desc *init_desc(char type, uint8_t hash_algo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:74
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff8173cbb0-ffffffff8173cdc9: init_desc (STB_LOCAL)
ffffffff820f51c6-ffffffff820f51da: init_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct shash_desc *init_desc(char type, uint8_t hash_algo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:74
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff8177da50-ffffffff8177dc69: init_desc (STB_LOCAL)
ffffffff821d239a-ffffffff821d23ae: init_desc.cold (STB_LOCAL)
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
struct shash_desc *init_desc(char type, uint8_t hash_algo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffff8000105b5b28)
Location: security/integrity/evm/evm_crypto.c:74
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffff8000105b5b28-ffff8000105b5d04: init_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct shash_desc *init_desc(char type, uint8_t hash_algo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (c0764c30)
Location: security/integrity/evm/evm_crypto.c:74
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
c0764c30-c0764e08: init_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct shash_desc *init_desc(char type, uint8_t hash_algo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (c000000000739620)
Location: security/integrity/evm/evm_crypto.c:74
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
c000000000739620-c0000000007398d8: init_desc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct shash_desc *init_desc(char type, uint8_t hash_algo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffe0003fc98a)
Location: security/integrity/evm/evm_crypto.c:74
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffe0003fc98a-ffffffe0003fcb36: init_desc (STB_LOCAL)
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
struct shash_desc *init_desc(char type, uint8_t hash_algo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:74
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff814b5420-ffffffff814b55c0: init_desc (STB_LOCAL)
ffffffff814b5be3-ffffffff814b5c2d: init_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct shash_desc *init_desc(char type, uint8_t hash_algo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:74
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff814a5e40-ffffffff814a5fe0: init_desc (STB_LOCAL)
ffffffff814a6603-ffffffff814a664d: init_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct shash_desc *init_desc(char type, uint8_t hash_algo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:74
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff814b14b0-ffffffff814b1650: init_desc (STB_LOCAL)
ffffffff814b1c73-ffffffff814b1cbd: init_desc.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct shash_desc *init_desc(char type, uint8_t hash_algo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:74
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_hmac
  - security/integrity/evm/evm_crypto.c:evm_calc_hmac_or_hash
```
**Symbols:**

```
ffffffff814c9f30-ffffffff814ca0d0: init_desc (STB_LOCAL)
ffffffff814ca6f3-ffffffff814ca73d: init_desc.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>uint8_t hash_algo</code>
</li>
</ul>
</details>
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
