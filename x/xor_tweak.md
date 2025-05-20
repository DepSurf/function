# Function: <code>xor_tweak</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xor_tweak(struct skcipher_request *req, bool second_pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814875f0)
Location: crypto/xts.c:91
Inline: False
Direct callers:
  - crypto/xts.c:crypt_done
```
**Symbols:**

```
ffffffff814875f0-ffffffff814876da: xor_tweak (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xor_tweak(struct skcipher_request *req, bool second_pass);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814b52e0)
Location: crypto/xts.c:87
Inline: False
Direct callers:
  - crypto/xts.c:crypt_done
```
**Symbols:**

```
ffffffff814b52e0-ffffffff814b53cf: xor_tweak (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xor_tweak(struct skcipher_request *req, bool second_pass, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814ce100)
Location: crypto/xts.c:87
Inline: False
Direct callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
```
**Symbols:**

```
ffffffff814ce100-ffffffff814ce2c0: xor_tweak (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xor_tweak(struct skcipher_request *req, bool second_pass, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff8152d430)
Location: crypto/xts.c:81
Inline: False
Direct callers:
  - crypto/xts.c:decrypt
  - crypto/xts.c:decrypt
  - crypto/xts.c:encrypt
  - crypto/xts.c:encrypt
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
```
**Symbols:**

```
ffffffff8152d430-ffffffff8152d5fa: xor_tweak (STB_LOCAL)
```
</details>
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
int xor_tweak(struct skcipher_request *req, bool second_pass, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffff8000105ca018)
Location: crypto/xts.c:87
Inline: False
Direct callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
```
**Symbols:**

```
ffff8000105ca018-ffff8000105ca1a0: xor_tweak (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xor_tweak(struct skcipher_request *req, bool second_pass, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (c0777b1c)
Location: crypto/xts.c:87
Inline: False
Direct callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
```
**Symbols:**

```
c0777b1c-c0777d64: xor_tweak (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xor_tweak(struct skcipher_request *req, bool second_pass, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (c0000000007549e0)
Location: crypto/xts.c:87
Inline: False
Direct callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
```
**Symbols:**

```
c0000000007549e0-c000000000754c20: xor_tweak (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xor_tweak(struct skcipher_request *req, bool second_pass, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffe00040e636)
Location: crypto/xts.c:87
Inline: False
Direct callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
```
**Symbols:**

```
ffffffe00040e636-ffffffe00040e7a6: xor_tweak (STB_LOCAL)
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
int xor_tweak(struct skcipher_request *req, bool second_pass, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814c66e0)
Location: crypto/xts.c:87
Inline: False
Direct callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
```
**Symbols:**

```
ffffffff814c66e0-ffffffff814c68a0: xor_tweak (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xor_tweak(struct skcipher_request *req, bool second_pass, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814b7100)
Location: crypto/xts.c:87
Inline: False
Direct callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
```
**Symbols:**

```
ffffffff814b7100-ffffffff814b72c0: xor_tweak (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xor_tweak(struct skcipher_request *req, bool second_pass, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814c2770)
Location: crypto/xts.c:87
Inline: False
Direct callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
```
**Symbols:**

```
ffffffff814c2770-ffffffff814c2930: xor_tweak (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xor_tweak(struct skcipher_request *req, bool second_pass, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814db240)
Location: crypto/xts.c:87
Inline: False
Direct callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
```
**Symbols:**

```
ffffffff814db240-ffffffff814db400: xor_tweak (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool enc</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
