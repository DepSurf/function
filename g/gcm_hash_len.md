# Function: <code>gcm_hash_len</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff8143864e)
Location: crypto/gcm.c:245
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff8146b585)
Location: crypto/gcm.c:245
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff81488c05)
Location: crypto/gcm.c:245
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814b6885)
Location: crypto/gcm.c:242
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814cfaa5)
Location: crypto/gcm.c:229
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int gcm_hash_len(struct aead_request *req, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff8152ec70)
Location: crypto/gcm.c:223
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
```
**Symbols:**

```
ffffffff8152ec70-ffffffff8152ed2c: gcm_hash_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int gcm_hash_len(struct aead_request *req, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff8154bbf0)
Location: crypto/gcm.c:223
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
```
**Symbols:**

```
ffffffff8154bbf0-ffffffff8154bcac: gcm_hash_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff8155420b)
Location: crypto/gcm.c:223
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff815b523b)
Location: crypto/gcm.c:223
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (0)
Location: crypto/gcm.c:223
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (0)
Location: crypto/gcm.c:223
Inline: True
Inline callers:
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gcm_hash_len(struct aead_request *req, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff817538c0)
Location: crypto/gcm.c:223
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
```
**Symbols:**

```
ffffffff817538c0-ffffffff817539b1: gcm_hash_len (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gcm_hash_len(struct aead_request *req, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff81795790)
Location: crypto/gcm.c:223
Inline: False
Direct callers:
  - crypto/gcm.c:gcm_hash_crypt_remain_continue
```
**Symbols:**

```
ffffffff81795790-ffffffff81795881: gcm_hash_len (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffff8000105cc86c)
Location: crypto/gcm.c:229
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (c0779de0)
Location: crypto/gcm.c:229
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (c000000000756ef4)
Location: crypto/gcm.c:229
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffe00041074a)
Location: crypto/gcm.c:229
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814c8085)
Location: crypto/gcm.c:229
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814b8aa5)
Location: crypto/gcm.c:229
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814c4115)
Location: crypto/gcm.c:229
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/gcm.c (ffffffff814dcbe5)
Location: crypto/gcm.c:229
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
