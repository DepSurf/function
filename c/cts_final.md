# Function: <code>cts_final</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cts_final(struct skcipher_request *req, int (*crypt)(struct skcipher_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814ce360)
Location: crypto/xts.c:163
Inline: False
Direct callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
```
**Symbols:**

```
ffffffff814ce360-ffffffff814ce595: cts_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cts_final(struct skcipher_request *req, int (*crypt)(struct skcipher_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff8152d6a0)
Location: crypto/xts.c:157
Inline: False
Direct callers:
  - crypto/xts.c:decrypt
  - crypto/xts.c:encrypt
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
```
**Symbols:**

```
ffffffff8152d6a0-ffffffff8152d8af: cts_final (STB_LOCAL)
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
int cts_final(struct skcipher_request *req, int (*crypt)(struct skcipher_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffff8000105ca258)
Location: crypto/xts.c:163
Inline: False
Direct callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
```
**Symbols:**

```
ffff8000105ca258-ffff8000105ca3e0: cts_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cts_final(struct skcipher_request *req, int (*crypt)(struct skcipher_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (c0777e48)
Location: crypto/xts.c:163
Inline: False
Direct callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
```
**Symbols:**

```
c0777e48-c0778030: cts_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cts_final(struct skcipher_request *req, int (*crypt)(struct skcipher_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (c000000000754d20)
Location: crypto/xts.c:163
Inline: False
Direct callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
```
**Symbols:**

```
c000000000754d20-c000000000754f1c: cts_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cts_final(struct skcipher_request *req, int (*crypt)(struct skcipher_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffe00040e82a)
Location: crypto/xts.c:163
Inline: False
Direct callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
```
**Symbols:**

```
ffffffe00040e82a-ffffffe00040e964: cts_final (STB_LOCAL)
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
int cts_final(struct skcipher_request *req, int (*crypt)(struct skcipher_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814c6940)
Location: crypto/xts.c:163
Inline: False
Direct callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
```
**Symbols:**

```
ffffffff814c6940-ffffffff814c6b75: cts_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cts_final(struct skcipher_request *req, int (*crypt)(struct skcipher_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814b7360)
Location: crypto/xts.c:163
Inline: False
Direct callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
```
**Symbols:**

```
ffffffff814b7360-ffffffff814b7595: cts_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cts_final(struct skcipher_request *req, int (*crypt)(struct skcipher_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814c29d0)
Location: crypto/xts.c:163
Inline: False
Direct callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
```
**Symbols:**

```
ffffffff814c29d0-ffffffff814c2c05: cts_final (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cts_final(struct skcipher_request *req, int (*crypt)(struct skcipher_request *));
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/xts.c (ffffffff814db4a0)
Location: crypto/xts.c:163
Inline: False
Direct callers:
  - crypto/xts.c:decrypt_done
  - crypto/xts.c:encrypt_done
```
**Symbols:**

```
ffffffff814db4a0-ffffffff814db6d5: cts_final (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
