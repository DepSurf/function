# Function: <code>ecryptfs_hash_digest</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff8133926b)
Location: fs/ecryptfs/crypto.c:78
Inline: True
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
In fs/ecryptfs/crypto.c (ffffffff8134f00b)
Location: fs/ecryptfs/crypto.c:78
Inline: True
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
In fs/ecryptfs/crypto.c (ffffffff81363abb)
Location: fs/ecryptfs/crypto.c:78
Inline: True
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
In fs/ecryptfs/crypto.c (ffffffff8138882b)
Location: fs/ecryptfs/crypto.c:64
Inline: True
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
In fs/ecryptfs/crypto.c (ffffffff813b76ab)
Location: fs/ecryptfs/crypto.c:64
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ecryptfs_hash_digest(struct crypto_shash *tfm, char *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff813d08c0)
Location: fs/ecryptfs/crypto.c:64
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
```
**Symbols:**

```
ffffffff813d08c0-ffffffff813d0938: ecryptfs_hash_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ecryptfs_hash_digest(struct crypto_shash *tfm, char *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffff813fb4e0)
Location: fs/ecryptfs/crypto.c:51
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
```
**Symbols:**

```
ffffffff813fb4e0-ffffffff813fb552: ecryptfs_hash_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ecryptfs_hash_digest(struct crypto_shash *tfm, char *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:51
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
```
**Symbols:**

```
ffffffff814153b0-ffffffff81415432: ecryptfs_hash_digest (STB_LOCAL)
ffffffff81417949-ffffffff81417955: ecryptfs_hash_digest.cold (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ecryptfs_hash_digest(struct crypto_shash *tfm, char *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffff8000104f6a00)
Location: fs/ecryptfs/crypto.c:51
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
```
**Symbols:**

```
ffff8000104f6a00-ffff8000104f6ac8: ecryptfs_hash_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ecryptfs_hash_digest(struct crypto_shash *tfm, char *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (c06b4470)
Location: fs/ecryptfs/crypto.c:51
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
```
**Symbols:**

```
c06b4470-c06b4510: ecryptfs_hash_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ecryptfs_hash_digest(struct crypto_shash *tfm, char *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (c000000000637a10)
Location: fs/ecryptfs/crypto.c:51
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
```
**Symbols:**

```
c000000000637a10-c000000000637acc: ecryptfs_hash_digest (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ecryptfs_hash_digest(struct crypto_shash *tfm, char *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ecryptfs/crypto.c (ffffffe00036567c)
Location: fs/ecryptfs/crypto.c:51
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
```
**Symbols:**

```
ffffffe00036567c-ffffffe0003656e4: ecryptfs_hash_digest (STB_LOCAL)
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
int ecryptfs_hash_digest(struct crypto_shash *tfm, char *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:51
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
```
**Symbols:**

```
ffffffff8140d990-ffffffff8140da12: ecryptfs_hash_digest (STB_LOCAL)
ffffffff8140ff29-ffffffff8140ff35: ecryptfs_hash_digest.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ecryptfs_hash_digest(struct crypto_shash *tfm, char *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:51
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
```
**Symbols:**

```
ffffffff813fe410-ffffffff813fe492: ecryptfs_hash_digest (STB_LOCAL)
ffffffff814009a9-ffffffff814009b5: ecryptfs_hash_digest.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ecryptfs_hash_digest(struct crypto_shash *tfm, char *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:51
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
```
**Symbols:**

```
ffffffff8140ad10-ffffffff8140ad92: ecryptfs_hash_digest (STB_LOCAL)
ffffffff8140d2a9-ffffffff8140d2b5: ecryptfs_hash_digest.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ecryptfs_hash_digest(struct crypto_shash *tfm, char *src, int len, char *dst);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ecryptfs/crypto.c (0)
Location: fs/ecryptfs/crypto.c:51
Inline: False
Direct callers:
  - fs/ecryptfs/crypto.c:ecryptfs_compute_root_iv
  - fs/ecryptfs/crypto.c:ecryptfs_derive_iv
```
**Symbols:**

```
ffffffff814209b0-ffffffff81420a32: ecryptfs_hash_digest (STB_LOCAL)
ffffffff81422f29-ffffffff81422f35: ecryptfs_hash_digest.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
