# Function: <code>fscrypt_fname_siphash</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 fscrypt_fname_siphash(const struct inode *dir, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813906f0)
Location: fs/crypto/fname.c:551
Inline: False
```
**Symbols:**

```
ffffffff813906f0-ffffffff81390720: fscrypt_fname_siphash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 fscrypt_fname_siphash(const struct inode *dir, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813a1b70)
Location: fs/crypto/fname.c:519
Inline: False
```
**Symbols:**

```
ffffffff813a1b70-ffffffff813a1ba0: fscrypt_fname_siphash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 fscrypt_fname_siphash(const struct inode *dir, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff813a8d10)
Location: fs/crypto/fname.c:515
Inline: False
Direct callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
```
**Symbols:**

```
ffffffff813a8d10-ffffffff813a8d40: fscrypt_fname_siphash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 fscrypt_fname_siphash(const struct inode *dir, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:539
Inline: False
Direct callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
```
**Symbols:**

```
ffffffff81cc62d0-ffffffff81cc62ed: fscrypt_fname_siphash.cold (STB_LOCAL)
ffffffff813f8480-ffffffff813f84cc: fscrypt_fname_siphash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 fscrypt_fname_siphash(const struct inode *dir, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:545
Inline: False
Direct callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
```
**Symbols:**

```
ffffffff81e787c7-ffffffff81e787e4: fscrypt_fname_siphash.cold (STB_LOCAL)
ffffffff8146b100-ffffffff8146b156: fscrypt_fname_siphash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 fscrypt_fname_siphash(const struct inode *dir, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:569
Inline: False
Direct callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
```
**Symbols:**

```
ffffffff8206a585-ffffffff8206a5a2: fscrypt_fname_siphash.cold (STB_LOCAL)
ffffffff814fc2b0-ffffffff814fc306: fscrypt_fname_siphash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 fscrypt_fname_siphash(const struct inode *dir, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:569
Inline: False
Direct callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
```
**Symbols:**

```
ffffffff820ea304-ffffffff820ea321: fscrypt_fname_siphash.cold (STB_LOCAL)
ffffffff81533820-ffffffff81533876: fscrypt_fname_siphash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 fscrypt_fname_siphash(const struct inode *dir, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:569
Inline: False
Direct callers:
  - fs/ext4/hash.c:__ext4fs_dirhash
```
**Symbols:**

```
ffffffff821c6db9-ffffffff821c6dd6: fscrypt_fname_siphash.cold (STB_LOCAL)
ffffffff815687b0-ffffffff81568806: fscrypt_fname_siphash (STB_GLOBAL)
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
