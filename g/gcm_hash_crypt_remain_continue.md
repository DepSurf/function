# Function: <code>gcm_hash_crypt_remain_continue</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int gcm_hash_crypt_remain_continue(struct aead_request *req, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff81438630)
Location: crypto/gcm.c:286
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_done
```
**Symbols:**

```
ffffffff81438630-ffffffff81438734: gcm_hash_crypt_remain_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int gcm_hash_crypt_remain_continue(struct aead_request *req, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff8146b580)
Location: crypto/gcm.c:286
Inline: True
Direct callers:
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_done
```
**Symbols:**

```
ffffffff8146b580-ffffffff8146b675: gcm_hash_crypt_remain_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int gcm_hash_crypt_remain_continue(struct aead_request *req, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff81488c00)
Location: crypto/gcm.c:286
Inline: True
Direct callers:
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_done
```
**Symbols:**

```
ffffffff81488c00-ffffffff81488cf5: gcm_hash_crypt_remain_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int gcm_hash_crypt_remain_continue(struct aead_request *req, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814b6880)
Location: crypto/gcm.c:283
Inline: True
Direct callers:
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_done
```
**Symbols:**

```
ffffffff814b6880-ffffffff814b6976: gcm_hash_crypt_remain_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int gcm_hash_crypt_remain_continue(struct aead_request *req, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814cfaa0)
Location: crypto/gcm.c:270
Inline: True
Direct callers:
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_done
```
**Symbols:**

```
ffffffff814cfaa0-ffffffff814cfb96: gcm_hash_crypt_remain_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gcm_hash_crypt_remain_continue(struct aead_request *req, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff8152ed30)
Location: crypto/gcm.c:264
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_done
```
**Symbols:**

```
ffffffff8152ed30-ffffffff8152ed81: gcm_hash_crypt_remain_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gcm_hash_crypt_remain_continue(struct aead_request *req, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff8154bcb0)
Location: crypto/gcm.c:264
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_done
```
**Symbols:**

```
ffffffff8154bcb0-ffffffff8154bd01: gcm_hash_crypt_remain_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int gcm_hash_crypt_remain_continue(struct aead_request *req, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff815541f0)
Location: crypto/gcm.c:264
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_done
```
**Symbols:**

```
ffffffff815541f0-ffffffff815542f4: gcm_hash_crypt_remain_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int gcm_hash_crypt_remain_continue(struct aead_request *req, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff815b5220)
Location: crypto/gcm.c:264
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_done
```
**Symbols:**

```
ffffffff815b5220-ffffffff815b5324: gcm_hash_crypt_remain_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int gcm_hash_crypt_remain_continue(struct aead_request *req, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff8165e2e0)
Location: crypto/gcm.c:264
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_done
```
**Symbols:**

```
ffffffff8165e2e0-ffffffff8165e409: gcm_hash_crypt_remain_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gcm_hash_crypt_remain_continue(struct aead_request *req, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff81717fa0)
Location: crypto/gcm.c:264
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_done
```
**Symbols:**

```
ffffffff81717fa0-ffffffff817180c9: gcm_hash_crypt_remain_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gcm_hash_crypt_remain_continue(struct aead_request *req, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff817539d0)
Location: crypto/gcm.c:264
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_done
```
**Symbols:**

```
ffffffff817539d0-ffffffff81753a31: gcm_hash_crypt_remain_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gcm_hash_crypt_remain_continue(struct aead_request *req, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff817958a0)
Location: crypto/gcm.c:264
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_done
```
**Symbols:**

```
ffffffff817958a0-ffffffff81795901: gcm_hash_crypt_remain_continue (STB_LOCAL)
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
int gcm_hash_crypt_remain_continue(struct aead_request *req, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffff8000105cc848)
Location: crypto/gcm.c:270
Inline: True
Direct callers:
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_done
```
**Symbols:**

```
ffff8000105cc848-ffff8000105cc954: gcm_hash_crypt_remain_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int gcm_hash_crypt_remain_continue(struct aead_request *req, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (c0779d98)
Location: crypto/gcm.c:270
Inline: True
Direct callers:
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_done
```
**Symbols:**

```
c0779d98-c0779ebc: gcm_hash_crypt_remain_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int gcm_hash_crypt_remain_continue(struct aead_request *req, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (c000000000756ec0)
Location: crypto/gcm.c:270
Inline: True
Direct callers:
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_done
```
**Symbols:**

```
c000000000756ec0-c000000000757020: gcm_hash_crypt_remain_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int gcm_hash_crypt_remain_continue(struct aead_request *req, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffe000410728)
Location: crypto/gcm.c:270
Inline: True
Direct callers:
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_done
```
**Symbols:**

```
ffffffe000410728-ffffffe00041085a: gcm_hash_crypt_remain_continue (STB_LOCAL)
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
int gcm_hash_crypt_remain_continue(struct aead_request *req, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814c8080)
Location: crypto/gcm.c:270
Inline: True
Direct callers:
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_done
```
**Symbols:**

```
ffffffff814c8080-ffffffff814c8176: gcm_hash_crypt_remain_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int gcm_hash_crypt_remain_continue(struct aead_request *req, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814b8aa0)
Location: crypto/gcm.c:270
Inline: True
Direct callers:
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_done
```
**Symbols:**

```
ffffffff814b8aa0-ffffffff814b8b96: gcm_hash_crypt_remain_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int gcm_hash_crypt_remain_continue(struct aead_request *req, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814c4110)
Location: crypto/gcm.c:270
Inline: True
Direct callers:
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_done
```
**Symbols:**

```
ffffffff814c4110-ffffffff814c4206: gcm_hash_crypt_remain_continue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int gcm_hash_crypt_remain_continue(struct aead_request *req, u32 flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814dcbe0)
Location: crypto/gcm.c:270
Inline: True
Direct callers:
  - crypto/gcm.c:gcm_hash_assoc_remain_continue
  - crypto/gcm.c:gcm_hash_crypt_continue
  - crypto/gcm.c:gcm_hash_crypt_remain_done
```
**Symbols:**

```
ffffffff814dcbe0-ffffffff814dccd6: gcm_hash_crypt_remain_continue (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
