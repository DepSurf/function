# Function: <code>ecryptfs_encrypt_and_encode_filename</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ecryptfs_encrypt_and_encode_filename(char **encoded_name, size_t *encoded_name_size, struct ecryptfs_crypt_stat *crypt_stat, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, const char *name, size_t name_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81307030)
Location: fs/ecryptfs/crypto.c:1944
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_lookup
  - fs/ecryptfs/inode.c:ecryptfs_symlink
```
**Symbols:**

```
ffffffff81307030-ffffffff81307491: ecryptfs_encrypt_and_encode_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ecryptfs_encrypt_and_encode_filename(char **encoded_name, size_t *encoded_name_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, const char *name, size_t name_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8133b250)
Location: fs/ecryptfs/crypto.c:1935
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff8133b250-ffffffff8133b5bf: ecryptfs_encrypt_and_encode_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ecryptfs_encrypt_and_encode_filename(char **encoded_name, size_t *encoded_name_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, const char *name, size_t name_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81350fe0)
Location: fs/ecryptfs/crypto.c:1935
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff81350fe0-ffffffff8135134f: ecryptfs_encrypt_and_encode_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ecryptfs_encrypt_and_encode_filename(char **encoded_name, size_t *encoded_name_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, const char *name, size_t name_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81365b10)
Location: fs/ecryptfs/crypto.c:1935
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff81365b10-ffffffff81365e7a: ecryptfs_encrypt_and_encode_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ecryptfs_encrypt_and_encode_filename(char **encoded_name, size_t *encoded_name_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, const char *name, size_t name_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8138a7d0)
Location: fs/ecryptfs/crypto.c:1912
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff8138a7d0-ffffffff8138aaf8: ecryptfs_encrypt_and_encode_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_and_encode_filename(char **encoded_name, size_t *encoded_name_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, const char *name, size_t name_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1912
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff813b9cde-ffffffff813b9d8c: ecryptfs_encrypt_and_encode_filename.cold.39 (STB_LOCAL)
ffffffff813b94b0-ffffffff813b9723: ecryptfs_encrypt_and_encode_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_and_encode_filename(char **encoded_name, size_t *encoded_name_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, const char *name, size_t name_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1912
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff813d328d-ffffffff813d333b: ecryptfs_encrypt_and_encode_filename.cold.37 (STB_LOCAL)
ffffffff813d2a20-ffffffff813d2c93: ecryptfs_encrypt_and_encode_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_and_encode_filename(char **encoded_name, size_t *encoded_name_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, const char *name, size_t name_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1906
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff813fdd8a-ffffffff813fde39: ecryptfs_encrypt_and_encode_filename.cold (STB_LOCAL)
ffffffff813fd4c0-ffffffff813fd732: ecryptfs_encrypt_and_encode_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_and_encode_filename(char **encoded_name, size_t *encoded_name_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, const char *name, size_t name_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1908
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff81417c76-ffffffff81417d25: ecryptfs_encrypt_and_encode_filename.cold (STB_LOCAL)
ffffffff814173a0-ffffffff81417612: ecryptfs_encrypt_and_encode_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_and_encode_filename(char **encoded_name, size_t *encoded_name_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, const char *name, size_t name_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1893
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff814661ea-ffffffff81466258: ecryptfs_encrypt_and_encode_filename.cold (STB_LOCAL)
ffffffff81465a20-ffffffff81465c19: ecryptfs_encrypt_and_encode_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_and_encode_filename(char **encoded_name, size_t *encoded_name_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, const char *name, size_t name_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1893
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff81bee9a1-ffffffff81beea0f: ecryptfs_encrypt_and_encode_filename.cold (STB_LOCAL)
ffffffff814812c0-ffffffff814814b9: ecryptfs_encrypt_and_encode_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_and_encode_filename(char **encoded_name, size_t *encoded_name_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, const char *name, size_t name_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1888
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff81be0a77-ffffffff81be0ad5: ecryptfs_encrypt_and_encode_filename.cold (STB_LOCAL)
ffffffff81486c60-ffffffff81486e31: ecryptfs_encrypt_and_encode_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_and_encode_filename(char **encoded_name, size_t *encoded_name_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, const char *name, size_t name_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1888
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff81cd1214-ffffffff81cd1272: ecryptfs_encrypt_and_encode_filename.cold (STB_LOCAL)
ffffffff814de3f0-ffffffff814de5c1: ecryptfs_encrypt_and_encode_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_and_encode_filename(char **encoded_name, size_t *encoded_name_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, const char *name, size_t name_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1888
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff81e843de-ffffffff81e84436: ecryptfs_encrypt_and_encode_filename.cold (STB_LOCAL)
ffffffff8156c450-ffffffff8156c612: ecryptfs_encrypt_and_encode_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ecryptfs_encrypt_and_encode_filename(char **encoded_name, size_t *encoded_name_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, const char *name, size_t name_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff816106a0)
Location: fs/ecryptfs/crypto.c:1888
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff816106a0-ffffffff816108b8: ecryptfs_encrypt_and_encode_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ecryptfs_encrypt_and_encode_filename(char **encoded_name, size_t *encoded_name_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, const char *name, size_t name_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff81648520)
Location: fs/ecryptfs/crypto.c:1864
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff81648520-ffffffff81648762: ecryptfs_encrypt_and_encode_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ecryptfs_encrypt_and_encode_filename(char **encoded_name, size_t *encoded_name_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, const char *name, size_t name_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff816819d0)
Location: fs/ecryptfs/crypto.c:1864
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff816819d0-ffffffff81681c3b: ecryptfs_encrypt_and_encode_filename (STB_GLOBAL)
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
int ecryptfs_encrypt_and_encode_filename(char **encoded_name, size_t *encoded_name_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, const char *name, size_t name_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffff8000104f8ec8)
Location: fs/ecryptfs/crypto.c:1908
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffff8000104f8ec8-ffff8000104f91b4: ecryptfs_encrypt_and_encode_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ecryptfs_encrypt_and_encode_filename(char **encoded_name, size_t *encoded_name_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, const char *name, size_t name_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (c06b6764)
Location: fs/ecryptfs/crypto.c:1908
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
c06b6764-c06b6a58: ecryptfs_encrypt_and_encode_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ecryptfs_encrypt_and_encode_filename(char **encoded_name, size_t *encoded_name_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, const char *name, size_t name_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (c00000000063afc0)
Location: fs/ecryptfs/crypto.c:1908
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
c00000000063afc0-c00000000063b394: ecryptfs_encrypt_and_encode_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ecryptfs_encrypt_and_encode_filename(char **encoded_name, size_t *encoded_name_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, const char *name, size_t name_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffe000367722)
Location: fs/ecryptfs/crypto.c:1908
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffe000367722-ffffffe0003679be: ecryptfs_encrypt_and_encode_filename (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_and_encode_filename(char **encoded_name, size_t *encoded_name_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, const char *name, size_t name_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1908
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff81410256-ffffffff81410305: ecryptfs_encrypt_and_encode_filename.cold (STB_LOCAL)
ffffffff8140f980-ffffffff8140fbf2: ecryptfs_encrypt_and_encode_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_and_encode_filename(char **encoded_name, size_t *encoded_name_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, const char *name, size_t name_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1908
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff81400cd6-ffffffff81400d85: ecryptfs_encrypt_and_encode_filename.cold (STB_LOCAL)
ffffffff81400400-ffffffff81400672: ecryptfs_encrypt_and_encode_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_and_encode_filename(char **encoded_name, size_t *encoded_name_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, const char *name, size_t name_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1908
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff8140d5d6-ffffffff8140d685: ecryptfs_encrypt_and_encode_filename.cold (STB_LOCAL)
ffffffff8140cd00-ffffffff8140cf72: ecryptfs_encrypt_and_encode_filename (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ecryptfs_encrypt_and_encode_filename(char **encoded_name, size_t *encoded_name_size, struct ecryptfs_mount_crypt_stat *mount_crypt_stat, const char *name, size_t name_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:1908
Inline: False
Direct callers:
  - fs/ecryptfs/inode.c:ecryptfs_symlink
  - fs/ecryptfs/inode.c:ecryptfs_lookup
```
**Symbols:**

```
ffffffff8142324f-ffffffff814232fe: ecryptfs_encrypt_and_encode_filename.cold (STB_LOCAL)
ffffffff81422980-ffffffff81422bf2: ecryptfs_encrypt_and_encode_filename (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct ecryptfs_crypt_stat *crypt_stat</code>
</li>
<li>
<b>Param reordered. </b>
<code>encoded_name, encoded_name_size, crypt_stat, mount_crypt_stat, name, name_size</code> ➡️ <code>encoded_name, encoded_name_size, mount_crypt_stat, name, name_size</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
