# Function: <code>fscrypt_fname_usr_to_disk</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_fname_usr_to_disk(struct inode *inode, const struct qstr *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff81289480)
Location: fs/crypto/fname.c:328
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
ffffffff81289480-ffffffff812894e1: fscrypt_fname_usr_to_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_fname_usr_to_disk(struct inode *inode, const struct qstr *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff8129e140)
Location: fs/crypto/fname.c:318
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
ffffffff8129e140-ffffffff8129e1a3: fscrypt_fname_usr_to_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_fname_usr_to_disk(struct inode *inode, const struct qstr *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff812acbb0)
Location: fs/crypto/fname.c:331
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
ffffffff812acbb0-ffffffff812acc13: fscrypt_fname_usr_to_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_fname_usr_to_disk(struct inode *inode, const struct qstr *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff812d0380)
Location: fs/crypto/fname.c:308
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
ffffffff812d0380-ffffffff812d03e3: fscrypt_fname_usr_to_disk (STB_GLOBAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
