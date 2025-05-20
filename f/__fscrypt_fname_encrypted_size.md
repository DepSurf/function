# Function: <code>__fscrypt_fname_encrypted_size</code>

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
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool __fscrypt_fname_encrypted_size(const union fscrypt_policy *policy, u32 orig_len, u32 max_len, u32 *encrypted_len_ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff814fcc1d)
Location: fs/crypto/fname.c:269
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
Direct callers:
  - fs/crypto/hooks.c:fscrypt_prepare_symlink
```
**Symbols:**

```
ffffffff814fced0-ffffffff814fcf30: __fscrypt_fname_encrypted_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool __fscrypt_fname_encrypted_size(const union fscrypt_policy *policy, u32 orig_len, u32 max_len, u32 *encrypted_len_ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff8153419d)
Location: fs/crypto/fname.c:269
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
Direct callers:
  - fs/crypto/hooks.c:fscrypt_prepare_symlink
```
**Symbols:**

```
ffffffff81534430-ffffffff81534490: __fscrypt_fname_encrypted_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool __fscrypt_fname_encrypted_size(const union fscrypt_policy *policy, u32 orig_len, u32 max_len, u32 *encrypted_len_ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff8156912d)
Location: fs/crypto/fname.c:269
Inline: True
Inline callers:
  - fs/crypto/fname.c:fscrypt_setup_filename
Direct callers:
  - fs/crypto/hooks.c:fscrypt_prepare_symlink
```
**Symbols:**

```
ffffffff815693f0-ffffffff81569450: __fscrypt_fname_encrypted_size (STB_GLOBAL)
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
