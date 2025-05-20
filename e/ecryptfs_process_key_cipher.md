# Function: <code>ecryptfs_process_key_cipher</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81306d2e)
Location: fs/ecryptfs/crypto.c:1594
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8133af4e)
Location: fs/ecryptfs/crypto.c:1589
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81350ce2)
Location: fs/ecryptfs/crypto.c:1589
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81365802)
Location: fs/ecryptfs/crypto.c:1589
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8138a4c2)
Location: fs/ecryptfs/crypto.c:1568
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
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
In fs/ecryptfs/crypto.c (ffffffff813b925a)
Location: fs/ecryptfs/crypto.c:1568
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
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
In fs/ecryptfs/crypto.c (ffffffff813d27ca)
Location: fs/ecryptfs/crypto.c:1568
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
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
In fs/ecryptfs/crypto.c (ffffffff813fd26e)
Location: fs/ecryptfs/crypto.c:1562
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
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
In fs/ecryptfs/crypto.c (ffffffff8141714f)
Location: fs/ecryptfs/crypto.c:1564
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ecryptfs_process_key_cipher(struct crypto_skcipher **key_tfm, char *cipher_name, size_t *key_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1549
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
**Symbols:**

```
ffffffff81463790-ffffffff8146387a: ecryptfs_process_key_cipher (STB_LOCAL)
ffffffff81465e69-ffffffff81465ec2: ecryptfs_process_key_cipher.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ecryptfs_process_key_cipher(struct crypto_skcipher **key_tfm, char *cipher_name, size_t *key_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1549
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
**Symbols:**

```
ffffffff8147ef50-ffffffff8147f03a: ecryptfs_process_key_cipher (STB_LOCAL)
ffffffff81bee5d8-ffffffff81bee631: ecryptfs_process_key_cipher.cold (STB_LOCAL)
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
In fs/ecryptfs/crypto.c (ffffffff81486a0f)
Location: fs/ecryptfs/crypto.c:1544
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
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
In fs/ecryptfs/crypto.c (ffffffff814de19f)
Location: fs/ecryptfs/crypto.c:1544
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
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
In fs/ecryptfs/crypto.c (ffffffff8156c1ac)
Location: fs/ecryptfs/crypto.c:1544
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
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
In fs/ecryptfs/crypto.c (ffffffff8161033c)
Location: fs/ecryptfs/crypto.c:1544
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff816481cc)
Location: fs/ecryptfs/crypto.c:1520
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8168167c)
Location: fs/ecryptfs/crypto.c:1520
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
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
In fs/ecryptfs/crypto.c (ffff8000104f8bb0)
Location: fs/ecryptfs/crypto.c:1564
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
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
In fs/ecryptfs/crypto.c (c06b6450)
Location: fs/ecryptfs/crypto.c:1564
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
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
In fs/ecryptfs/crypto.c (c00000000063a9bc)
Location: fs/ecryptfs/crypto.c:1564
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
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
In fs/ecryptfs/crypto.c (ffffffe00036747a)
Location: fs/ecryptfs/crypto.c:1564
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
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
In fs/ecryptfs/crypto.c (ffffffff8140f72f)
Location: fs/ecryptfs/crypto.c:1564
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
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
In fs/ecryptfs/crypto.c (ffffffff814001af)
Location: fs/ecryptfs/crypto.c:1564
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
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
In fs/ecryptfs/crypto.c (ffffffff8140caaf)
Location: fs/ecryptfs/crypto.c:1564
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
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
In fs/ecryptfs/crypto.c (ffffffff8142272f)
Location: fs/ecryptfs/crypto.c:1564
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_add_new_key_tfm
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
</ul>
