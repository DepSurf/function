# Function: <code>fscrypt_zeroout_range</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fscrypt_zeroout_range(struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff81288d60)
Location: fs/crypto/crypto.c:286
Inline: False
```
**Symbols:**

```
ffffffff81288d60-ffffffff81288f95: fscrypt_zeroout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fscrypt_zeroout_range(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/crypto.c (ffffffff8129da20)
Location: fs/crypto/crypto.c:328
Inline: False
```
**Symbols:**

```
ffffffff8129da20-ffffffff8129dc54: fscrypt_zeroout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fscrypt_zeroout_range(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff812ae220)
Location: fs/crypto/bio.c:86
Inline: False
```
**Symbols:**

```
ffffffff812ae220-ffffffff812ae42e: fscrypt_zeroout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fscrypt_zeroout_range(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff812d1c20)
Location: fs/crypto/bio.c:87
Inline: False
```
**Symbols:**

```
ffffffff812d1c20-ffffffff812d1e63: fscrypt_zeroout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fscrypt_zeroout_range(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff812fc750)
Location: fs/crypto/bio.c:96
Inline: False
```
**Symbols:**

```
ffffffff812fc750-ffffffff812fc987: fscrypt_zeroout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fscrypt_zeroout_range(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff81311fb0)
Location: fs/crypto/bio.c:96
Inline: False
```
**Symbols:**

```
ffffffff81311fb0-ffffffff813121f2: fscrypt_zeroout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int fscrypt_zeroout_range(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/bio.c (0)
Location: fs/crypto/bio.c:71
Inline: False
```
**Symbols:**

```
ffffffff8133971f-ffffffff8133973f: fscrypt_zeroout_range.cold (STB_LOCAL)
ffffffff81339520-ffffffff8133971f: fscrypt_zeroout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int fscrypt_zeroout_range(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff8134f3a0)
Location: fs/crypto/bio.c:71
Inline: False
```
**Symbols:**

```
ffffffff8134f3a0-ffffffff8134f5af: fscrypt_zeroout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fscrypt_zeroout_range(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff81395840)
Location: fs/crypto/bio.c:61
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_issue_zeroout
```
**Symbols:**

```
ffffffff81395840-ffffffff81395bc1: fscrypt_zeroout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fscrypt_zeroout_range(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff813a6db0)
Location: fs/crypto/bio.c:108
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_issue_zeroout
```
**Symbols:**

```
ffffffff813a6db0-ffffffff813a7182: fscrypt_zeroout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fscrypt_zeroout_range(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff813ade20)
Location: fs/crypto/bio.c:108
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_issue_zeroout
```
**Symbols:**

```
ffffffff813ade20-ffffffff813ae1e3: fscrypt_zeroout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fscrypt_zeroout_range(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/bio.c (0)
Location: fs/crypto/bio.c:108
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_issue_zeroout
```
**Symbols:**

```
ffffffff81cc6a70-ffffffff81cc6ae2: fscrypt_zeroout_range.cold (STB_LOCAL)
ffffffff813fd7c0-ffffffff813fdcd6: fscrypt_zeroout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fscrypt_zeroout_range(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/bio.c (0)
Location: fs/crypto/bio.c:109
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_issue_zeroout
```
**Symbols:**

```
ffffffff81e78e9b-ffffffff81e78f8b: fscrypt_zeroout_range.cold (STB_LOCAL)
ffffffff81470fa0-ffffffff814714b4: fscrypt_zeroout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fscrypt_zeroout_range(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/bio.c (0)
Location: fs/crypto/bio.c:113
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_issue_zeroout
```
**Symbols:**

```
ffffffff8206a799-ffffffff8206a889: fscrypt_zeroout_range.cold (STB_LOCAL)
ffffffff81502a90-ffffffff81502fa4: fscrypt_zeroout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fscrypt_zeroout_range(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/bio.c (0)
Location: fs/crypto/bio.c:111
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_issue_zeroout
```
**Symbols:**

```
ffffffff820ea5a7-ffffffff820ea65d: fscrypt_zeroout_range.cold (STB_LOCAL)
ffffffff8153a070-ffffffff8153a589: fscrypt_zeroout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fscrypt_zeroout_range(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/bio.c (0)
Location: fs/crypto/bio.c:111
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_issue_zeroout
```
**Symbols:**

```
ffffffff821c7148-ffffffff821c7314: fscrypt_zeroout_range.cold (STB_LOCAL)
ffffffff8156f3b0-ffffffff8156f933: fscrypt_zeroout_range (STB_GLOBAL)
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
int fscrypt_zeroout_range(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffff800010410b80)
Location: fs/crypto/bio.c:71
Inline: False
```
**Symbols:**

```
ffff800010410b80-ffff800010410dac: fscrypt_zeroout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fscrypt_zeroout_range(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (c05dd35c)
Location: fs/crypto/bio.c:71
Inline: False
```
**Symbols:**

```
c05dd35c-c05dd574: fscrypt_zeroout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fscrypt_zeroout_range(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (c00000000051e7b0)
Location: fs/crypto/bio.c:71
Inline: False
```
**Symbols:**

```
c00000000051e7b0-c00000000051ea60: fscrypt_zeroout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fscrypt_zeroout_range(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffe0002b91e8)
Location: fs/crypto/bio.c:71
Inline: False
```
**Symbols:**

```
ffffffe0002b91e8-ffffffe0002b93c2: fscrypt_zeroout_range (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int fscrypt_zeroout_range(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff81347980)
Location: fs/crypto/bio.c:71
Inline: False
```
**Symbols:**

```
ffffffff81347980-ffffffff81347b8f: fscrypt_zeroout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fscrypt_zeroout_range(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff81338660)
Location: fs/crypto/bio.c:71
Inline: False
```
**Symbols:**

```
ffffffff81338660-ffffffff8133886f: fscrypt_zeroout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fscrypt_zeroout_range(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff81345450)
Location: fs/crypto/bio.c:71
Inline: False
```
**Symbols:**

```
ffffffff81345450-ffffffff8134565f: fscrypt_zeroout_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fscrypt_zeroout_range(const struct inode *inode, long unsigned int lblk, sector_t pblk, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/bio.c (ffffffff81358730)
Location: fs/crypto/bio.c:71
Inline: False
```
**Symbols:**

```
ffffffff81358730-ffffffff8135893f: fscrypt_zeroout_range (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct inode *inode</code> ➡️ <code>const struct inode *inode</code>
</li>
</ul>
</details>
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
