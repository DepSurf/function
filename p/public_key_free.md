# Function: <code>public_key_free</code>

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
void public_key_free(struct public_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff813f0540)
Location: crypto/asymmetric_keys/public_key.c:42
Inline: False
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_free_certificate
```
**Symbols:**

```
ffffffff813f0540-ffffffff813f0566: public_key_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void public_key_free(struct public_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff81409dc0)
Location: crypto/asymmetric_keys/public_key.c:42
Inline: False
Direct callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/x509_cert_parser.c:x509_free_certificate
```
**Symbols:**

```
ffffffff81409dc0-ffffffff81409de6: public_key_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void public_key_free(struct public_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff81417946)
Location: crypto/asymmetric_keys/public_key.c:42
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
```
**Symbols:**

```
ffffffff81417c40-ffffffff81417c67: public_key_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void public_key_free(struct public_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff81442386)
Location: crypto/asymmetric_keys/public_key.c:44
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
```
**Symbols:**

```
ffffffff81442730-ffffffff81442757: public_key_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void public_key_free(struct public_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff81475265)
Location: crypto/asymmetric_keys/public_key.c:44
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
```
**Symbols:**

```
ffffffff81475600-ffffffff81475626: public_key_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void public_key_free(struct public_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff81492f55)
Location: crypto/asymmetric_keys/public_key.c:44
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
```
**Symbols:**

```
ffffffff814934c0-ffffffff814934e6: public_key_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void public_key_free(struct public_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff814c0675)
Location: crypto/asymmetric_keys/public_key.c:40
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
```
**Symbols:**

```
ffffffff814c0770-ffffffff814c07a2: public_key_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void public_key_free(struct public_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff814d94c5)
Location: crypto/asymmetric_keys/public_key.c:40
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
```
**Symbols:**

```
ffffffff814d95c0-ffffffff814d95f2: public_key_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void public_key_free(struct public_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff81538e55)
Location: crypto/asymmetric_keys/public_key.c:40
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
```
**Symbols:**

```
ffffffff81538e90-ffffffff81538ec4: public_key_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void public_key_free(struct public_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff81555c35)
Location: crypto/asymmetric_keys/public_key.c:42
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
```
**Symbols:**

```
ffffffff81555c70-ffffffff81555ca4: public_key_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void public_key_free(struct public_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff8155e3b5)
Location: crypto/asymmetric_keys/public_key.c:43
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
```
**Symbols:**

```
ffffffff8155e3f0-ffffffff8155e424: public_key_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void public_key_free(struct public_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff815bf6e5)
Location: crypto/asymmetric_keys/public_key.c:43
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
```
**Symbols:**

```
ffffffff815bf720-ffffffff815bf754: public_key_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void public_key_free(struct public_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff81669765)
Location: crypto/asymmetric_keys/public_key.c:43
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
```
**Symbols:**

```
ffffffff816697b0-ffffffff816697ee: public_key_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void public_key_free(struct public_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff817242c5)
Location: crypto/asymmetric_keys/public_key.c:43
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
```
**Symbols:**

```
ffffffff81724320-ffffffff8172435e: public_key_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void public_key_free(struct public_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff81760ed5)
Location: crypto/asymmetric_keys/public_key.c:42
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
```
**Symbols:**

```
ffffffff81760f30-ffffffff81760f6e: public_key_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void public_key_free(struct public_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff817a2835)
Location: crypto/asymmetric_keys/public_key.c:42
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
```
**Symbols:**

```
ffffffff817a2890-ffffffff817a28ce: public_key_free (STB_GLOBAL)
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
void public_key_free(struct public_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffff8000105d56b4)
Location: crypto/asymmetric_keys/public_key.c:40
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
```
**Symbols:**

```
ffff8000105d5978-ffff8000105d59b8: public_key_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void public_key_free(struct public_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (c0782ee4)
Location: crypto/asymmetric_keys/public_key.c:40
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
```
**Symbols:**

```
c0782fd8-c0783010: public_key_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void public_key_free(struct public_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (c000000000763ac4)
Location: crypto/asymmetric_keys/public_key.c:40
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
```
**Symbols:**

```
c000000000763ec0-c000000000763f20: public_key_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void public_key_free(struct public_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffe000419870)
Location: crypto/asymmetric_keys/public_key.c:40
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
```
**Symbols:**

```
ffffffe000419e36-ffffffe000419e76: public_key_free (STB_GLOBAL)
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
void public_key_free(struct public_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff814d1aa5)
Location: crypto/asymmetric_keys/public_key.c:40
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
```
**Symbols:**

```
ffffffff814d1ba0-ffffffff814d1bd2: public_key_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void public_key_free(struct public_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff814c24c5)
Location: crypto/asymmetric_keys/public_key.c:40
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
```
**Symbols:**

```
ffffffff814c25c0-ffffffff814c25f2: public_key_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void public_key_free(struct public_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff814cdb35)
Location: crypto/asymmetric_keys/public_key.c:40
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
```
**Symbols:**

```
ffffffff814cdc30-ffffffff814cdc62: public_key_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void public_key_free(struct public_key *key);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/asymmetric_keys/public_key.c (ffffffff814e6605)
Location: crypto/asymmetric_keys/public_key.c:40
Inline: True
Inline callers:
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
  - crypto/asymmetric_keys/public_key.c:public_key_destroy
```
**Symbols:**

```
ffffffff814e6700-ffffffff814e6732: public_key_free (STB_GLOBAL)
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
