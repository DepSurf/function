# Function: <code>evm_set_key</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int evm_set_key(void *key, size_t keylen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff813d84c0)
Location: security/integrity/evm/evm_crypto.c:52
Inline: True
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
**Symbols:**

```
ffffffff813d84c0-ffffffff813d852f: evm_set_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int evm_set_key(void *key, size_t keylen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff813f0170)
Location: security/integrity/evm/evm_crypto.c:52
Inline: True
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
**Symbols:**

```
ffffffff813f0170-ffffffff813f01df: evm_set_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int evm_set_key(void *key, size_t keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff813fc320)
Location: security/integrity/evm/evm_crypto.c:52
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
**Symbols:**

```
ffffffff813fc320-ffffffff813fc38c: evm_set_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int evm_set_key(void *key, size_t keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814247f0)
Location: security/integrity/evm/evm_crypto.c:52
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
**Symbols:**

```
ffffffff814247f0-ffffffff8142485c: evm_set_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int evm_set_key(void *key, size_t keylen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:55
Inline: True
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
**Symbols:**

```
ffffffff81457786-ffffffff81457795: evm_set_key.cold.3 (STB_LOCAL)
ffffffff81457470-ffffffff814574dd: evm_set_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int evm_set_key(void *key, size_t keylen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff81474983)
Location: security/integrity/evm/evm_crypto.c:55
Inline: True
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
**Symbols:**

```
ffffffff81474c86-ffffffff81474c95: evm_set_key.cold.3 (STB_LOCAL)
ffffffff81474960-ffffffff814749cd: evm_set_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int evm_set_key(void *key, size_t keylen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814a2988)
Location: security/integrity/evm/evm_crypto.c:52
Inline: True
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
**Symbols:**

```
ffffffff814a297d-ffffffff814a29b7: evm_set_key.cold (STB_LOCAL)
ffffffff814a2680-ffffffff814a26c7: evm_set_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int evm_set_key(void *key, size_t keylen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814bd658)
Location: security/integrity/evm/evm_crypto.c:52
Inline: True
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
**Symbols:**

```
ffffffff814bd64d-ffffffff814bd687: evm_set_key.cold (STB_LOCAL)
ffffffff814bd350-ffffffff814bd397: evm_set_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int evm_set_key(void *key, size_t keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:50
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
**Symbols:**

```
ffffffff8151ded3-ffffffff8151df0f: evm_set_key.cold (STB_LOCAL)
ffffffff8151d710-ffffffff8151d757: evm_set_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int evm_set_key(void *key, size_t keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:50
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
**Symbols:**

```
ffffffff81bf1f43-ffffffff81bf1f7f: evm_set_key.cold (STB_LOCAL)
ffffffff8153a580-ffffffff8153a5c7: evm_set_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int evm_set_key(void *key, size_t keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:50
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
**Symbols:**

```
ffffffff81be3f67-ffffffff81be3fa3: evm_set_key.cold (STB_LOCAL)
ffffffff81542c40-ffffffff81542c87: evm_set_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int evm_set_key(void *key, size_t keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:52
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
**Symbols:**

```
ffffffff81cd74db-ffffffff81cd7517: evm_set_key.cold (STB_LOCAL)
ffffffff815a3160-ffffffff815a31a7: evm_set_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int evm_set_key(void *key, size_t keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (0)
Location: security/integrity/evm/evm_crypto.c:52
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
**Symbols:**

```
ffffffff81e8a7be-ffffffff81e8a801: evm_set_key.cold (STB_LOCAL)
ffffffff816499a0-ffffffff816499e5: evm_set_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int evm_set_key(void *key, size_t keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff81702970)
Location: security/integrity/evm/evm_crypto.c:52
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
**Symbols:**

```
ffffffff81702970-ffffffff817029fa: evm_set_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int evm_set_key(void *key, size_t keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff8173c9a0)
Location: security/integrity/evm/evm_crypto.c:52
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
**Symbols:**

```
ffffffff8173c9a0-ffffffff8173ca2a: evm_set_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int evm_set_key(void *key, size_t keylen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff8177d7a0)
Location: security/integrity/evm/evm_crypto.c:52
Inline: False
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
**Symbols:**

```
ffffffff8177d7a0-ffffffff8177d82a: evm_set_key (STB_GLOBAL)
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
int evm_set_key(void *key, size_t keylen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffff8000105b60b0)
Location: security/integrity/evm/evm_crypto.c:52
Inline: True
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
**Symbols:**

```
ffff8000105b60b0-ffff8000105b61bc: evm_set_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int evm_set_key(void *key, size_t keylen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (c07651c8)
Location: security/integrity/evm/evm_crypto.c:52
Inline: True
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
**Symbols:**

```
c07651c8-c0765264: evm_set_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int evm_set_key(void *key, size_t keylen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (c00000000073a0b0)
Location: security/integrity/evm/evm_crypto.c:52
Inline: True
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
**Symbols:**

```
c00000000073a0b0-c00000000073a190: evm_set_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int evm_set_key(void *key, size_t keylen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffe0003fce42)
Location: security/integrity/evm/evm_crypto.c:52
Inline: True
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
**Symbols:**

```
ffffffe0003fce42-ffffffe0003fced8: evm_set_key (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int evm_set_key(void *key, size_t keylen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814b5c38)
Location: security/integrity/evm/evm_crypto.c:52
Inline: True
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
**Symbols:**

```
ffffffff814b5c2d-ffffffff814b5c67: evm_set_key.cold (STB_LOCAL)
ffffffff814b5930-ffffffff814b5977: evm_set_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int evm_set_key(void *key, size_t keylen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814a6658)
Location: security/integrity/evm/evm_crypto.c:52
Inline: True
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
**Symbols:**

```
ffffffff814a664d-ffffffff814a6687: evm_set_key.cold (STB_LOCAL)
ffffffff814a6350-ffffffff814a6397: evm_set_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int evm_set_key(void *key, size_t keylen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814b1cc8)
Location: security/integrity/evm/evm_crypto.c:52
Inline: True
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
**Symbols:**

```
ffffffff814b1cbd-ffffffff814b1cf7: evm_set_key.cold (STB_LOCAL)
ffffffff814b19c0-ffffffff814b1a07: evm_set_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int evm_set_key(void *key, size_t keylen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/integrity/evm/evm_crypto.c (ffffffff814ca748)
Location: security/integrity/evm/evm_crypto.c:52
Inline: True
Direct callers:
  - security/integrity/evm/evm_crypto.c:evm_init_key
```
**Symbols:**

```
ffffffff814ca73d-ffffffff814ca777: evm_set_key.cold (STB_LOCAL)
ffffffff814ca440-ffffffff814ca487: evm_set_key (STB_GLOBAL)
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
