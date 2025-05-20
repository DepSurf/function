# Function: <code>fscrypt_get_devices</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff813a777c)
Location: fs/crypto/inline_crypt.c:36
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
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
In fs/crypto/inline_crypt.c (ffffffff813ae7c7)
Location: fs/crypto/inline_crypt.c:36
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
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
In fs/crypto/inline_crypt.c (ffffffff813fe367)
Location: fs/crypto/inline_crypt.c:36
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
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
In fs/crypto/inline_crypt.c (ffffffff81471e96)
Location: fs/crypto/inline_crypt.c:37
Inline: True
Inline callers:
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct block_device **fscrypt_get_devices(struct super_block *sb, unsigned int *num_devs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff815032a0)
Location: fs/crypto/inline_crypt.c:24
Inline: True
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
```
**Symbols:**

```
ffffffff815032a0-ffffffff81503320: fscrypt_get_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct block_device **fscrypt_get_devices(struct super_block *sb, unsigned int *num_devs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff8153ab50)
Location: fs/crypto/inline_crypt.c:24
Inline: True
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
```
**Symbols:**

```
ffffffff8153ab50-ffffffff8153abd0: fscrypt_get_devices (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct block_device **fscrypt_get_devices(struct super_block *sb, unsigned int *num_devs);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff8156fd10)
Location: fs/crypto/inline_crypt.c:24
Inline: True
Direct callers:
  - fs/crypto/inline_crypt.c:fscrypt_destroy_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_prepare_inline_crypt_key
  - fs/crypto/inline_crypt.c:fscrypt_select_encryption_impl
```
**Symbols:**

```
ffffffff8156fd10-ffffffff8156fdc2: fscrypt_get_devices (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
