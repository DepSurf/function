# Function: <code>fscrypt_dio_supported</code>

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
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool fscrypt_dio_supported(struct kiocb *iocb, struct iov_iter *iter);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (0)
Location: fs/crypto/inline_crypt.c:414
Inline: False
Direct callers:
  - fs/ext4/file.c:ext4_dio_supported
```
**Symbols:**

```
ffffffff81e79003-ffffffff81e79041: fscrypt_dio_supported.cold (STB_LOCAL)
ffffffff81471760-ffffffff81471823: fscrypt_dio_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fscrypt_dio_supported(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff8150335a)
Location: fs/crypto/inline_crypt.c:406
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_dio_alignment
```
**Symbols:**

```
ffffffff8206a901-ffffffff8206a91c: fscrypt_dio_supported.cold (STB_LOCAL)
ffffffff81503330-ffffffff815033d4: fscrypt_dio_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fscrypt_dio_supported(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff8153ac0a)
Location: fs/crypto/inline_crypt.c:406
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_dio_alignment
```
**Symbols:**

```
ffffffff820ea742-ffffffff820ea75d: fscrypt_dio_supported.cold (STB_LOCAL)
ffffffff8153abe0-ffffffff8153ac84: fscrypt_dio_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool fscrypt_dio_supported(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff8156fe8a)
Location: fs/crypto/inline_crypt.c:408
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_dio_alignment
```
**Symbols:**

```
ffffffff821c740c-ffffffff821c7427: fscrypt_dio_supported.cold (STB_LOCAL)
ffffffff8156fe60-ffffffff8156ff04: fscrypt_dio_supported (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct inode *inode</code>
</li>
<li>
<b>Param removed. </b>
<code>struct kiocb *iocb</code>
</li>
<li>
<b>Param removed. </b>
<code>struct iov_iter *iter</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
