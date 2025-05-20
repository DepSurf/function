# Function: <code>fscrypt_put_master_key_activeref</code>

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
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fscrypt_put_master_key_activeref(struct super_block *sb, struct fscrypt_master_key *mk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (ffffffff814feb12)
Location: fs/crypto/keyring.c:82
Inline: True
Inline callers:
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
Direct callers:
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
  - fs/crypto/keysetup.c:put_crypt_info
```
**Symbols:**

```
ffffffff814fe650-ffffffff814fe7ae: fscrypt_put_master_key_activeref.part.0 (STB_LOCAL)
ffffffff814fe9e0-ffffffff814fea3c: fscrypt_put_master_key_activeref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void fscrypt_put_master_key_activeref(struct super_block *sb, struct fscrypt_master_key *mk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/keyring.c (ffffffff81535ea0)
Location: fs/crypto/keyring.c:82
Inline: True
Direct callers:
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
  - fs/crypto/keysetup.c:put_crypt_info
```
**Symbols:**

```
ffffffff81535ea0-ffffffff8153605d: fscrypt_put_master_key_activeref (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fscrypt_put_master_key_activeref(struct super_block *sb, struct fscrypt_master_key *mk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keyring.c (ffffffff8156af1a)
Location: fs/crypto/keyring.c:82
Inline: True
Direct callers:
  - fs/crypto/keyring.c:fscrypt_destroy_keyring
  - fs/crypto/keysetup.c:put_crypt_info
```
**Symbols:**

```
ffffffff821c6ec7-ffffffff821c6edb: fscrypt_put_master_key_activeref.cold (STB_LOCAL)
ffffffff8156aeb0-ffffffff8156b07b: fscrypt_put_master_key_activeref (STB_GLOBAL)
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
