# Function: <code>crypto_gcm_free</code>

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
void crypto_gcm_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff81438da0)
Location: crypto/gcm.c:589
Inline: False
```
**Symbols:**

```
ffffffff81438da0-ffffffff81438dd0: crypto_gcm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void crypto_gcm_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff8146b0b0)
Location: crypto/gcm.c:589
Inline: False
```
**Symbols:**

```
ffffffff8146b0b0-ffffffff8146b0e0: crypto_gcm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void crypto_gcm_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814889b0)
Location: crypto/gcm.c:589
Inline: False
```
**Symbols:**

```
ffffffff814889b0-ffffffff814889e0: crypto_gcm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void crypto_gcm_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814b67a0)
Location: crypto/gcm.c:586
Inline: False
```
**Symbols:**

```
ffffffff814b67a0-ffffffff814b67d3: crypto_gcm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void crypto_gcm_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814cf9c0)
Location: crypto/gcm.c:573
Inline: False
```
**Symbols:**

```
ffffffff814cf9c0-ffffffff814cf9f3: crypto_gcm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void crypto_gcm_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff8152fc0d)
Location: crypto/gcm.c:567
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff8152eb90-ffffffff8152ebc5: crypto_gcm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void crypto_gcm_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff8154ce9f)
Location: crypto/gcm.c:567
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff8154bb10-ffffffff8154bb45: crypto_gcm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void crypto_gcm_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff81554e32)
Location: crypto/gcm.c:567
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff81554110-ffffffff81554145: crypto_gcm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void crypto_gcm_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff815b5e62)
Location: crypto/gcm.c:567
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff815b5140-ffffffff815b5175: crypto_gcm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void crypto_gcm_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff8165f0e9)
Location: crypto/gcm.c:567
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff8165e1f0-ffffffff8165e229: crypto_gcm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void crypto_gcm_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff81719079)
Location: crypto/gcm.c:567
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff81717b80-ffffffff81717bb9: crypto_gcm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void crypto_gcm_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff817549f9)
Location: crypto/gcm.c:565
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff81753560-ffffffff81753599: crypto_gcm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void crypto_gcm_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff81796728)
Location: crypto/gcm.c:565
Inline: True
Inline callers:
  - crypto/gcm.c:crypto_gcm_create_common
```
**Symbols:**

```
ffffffff81795430-ffffffff81795469: crypto_gcm_free (STB_LOCAL)
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
void crypto_gcm_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffff8000105cbf58)
Location: crypto/gcm.c:573
Inline: False
```
**Symbols:**

```
ffff8000105cbf58-ffff8000105cbf94: crypto_gcm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void crypto_gcm_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (c07798c4)
Location: crypto/gcm.c:573
Inline: False
```
**Symbols:**

```
c07798c4-c07798f8: crypto_gcm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void crypto_gcm_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (c000000000756d90)
Location: crypto/gcm.c:573
Inline: False
```
**Symbols:**

```
c000000000756d90-c000000000756dec: crypto_gcm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void crypto_gcm_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffe00040fe7c)
Location: crypto/gcm.c:573
Inline: False
```
**Symbols:**

```
ffffffe00040fe7c-ffffffe00040febe: crypto_gcm_free (STB_LOCAL)
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
void crypto_gcm_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814c7fa0)
Location: crypto/gcm.c:573
Inline: False
```
**Symbols:**

```
ffffffff814c7fa0-ffffffff814c7fd3: crypto_gcm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void crypto_gcm_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814b89c0)
Location: crypto/gcm.c:573
Inline: False
```
**Symbols:**

```
ffffffff814b89c0-ffffffff814b89f3: crypto_gcm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void crypto_gcm_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814c4030)
Location: crypto/gcm.c:573
Inline: False
```
**Symbols:**

```
ffffffff814c4030-ffffffff814c4063: crypto_gcm_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void crypto_gcm_free(struct aead_instance *inst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814dcb00)
Location: crypto/gcm.c:573
Inline: False
```
**Symbols:**

```
ffffffff814dcb00-ffffffff814dcb33: crypto_gcm_free (STB_LOCAL)
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
