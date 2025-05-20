# Function: <code>fscrypt_limit_io_blocks</code>

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
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
u64 fscrypt_limit_io_blocks(const struct inode *inode, u64 lblk, u64 nr_blocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff81471b1d)
Location: fs/crypto/inline_crypt.c:467
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff81e7906b-ffffffff81e79088: fscrypt_limit_io_blocks.cold (STB_LOCAL)
ffffffff81471aa0-ffffffff81471b69: fscrypt_limit_io_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
u64 fscrypt_limit_io_blocks(const struct inode *inode, u64 lblk, u64 nr_blocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff8150370d)
Location: fs/crypto/inline_crypt.c:457
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff8206a946-ffffffff8206a963: fscrypt_limit_io_blocks.cold (STB_LOCAL)
ffffffff81503690-ffffffff81503759: fscrypt_limit_io_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
u64 fscrypt_limit_io_blocks(const struct inode *inode, u64 lblk, u64 nr_blocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff8153afbd)
Location: fs/crypto/inline_crypt.c:457
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff820ea787-ffffffff820ea7a4: fscrypt_limit_io_blocks.cold (STB_LOCAL)
ffffffff8153af40-ffffffff8153b009: fscrypt_limit_io_blocks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
u64 fscrypt_limit_io_blocks(const struct inode *inode, u64 lblk, u64 nr_blocks);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/inline_crypt.c (ffffffff815702dd)
Location: fs/crypto/inline_crypt.c:459
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff821c7451-ffffffff821c746e: fscrypt_limit_io_blocks.cold (STB_LOCAL)
ffffffff81570260-ffffffff81570329: fscrypt_limit_io_blocks (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
