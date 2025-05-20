# Function: <code>fname_decrypt</code>

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
int fname_decrypt(struct inode *inode, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff812897c0)
Location: fs/crypto/fname.c:123
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff812897c0-ffffffff812899d7: fname_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fname_decrypt(struct inode *inode, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff8129e480)
Location: fs/crypto/fname.c:108
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff8129e480-ffffffff8129e697: fname_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fname_decrypt(struct inode *inode, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff812acf10)
Location: fs/crypto/fname.c:108
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff812acf10-ffffffff812ad174: fname_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fname_decrypt(struct inode *inode, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff812d06e0)
Location: fs/crypto/fname.c:89
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff812d06e0-ffffffff812d092f: fname_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (ffffffff812faa50)
Location: fs/crypto/fname.c:90
Inline: True
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff812faa50-ffffffff812fac47: fname_decrypt.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:91
Inline: True
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff8130fdd0-ffffffff8130fff3: fname_decrypt.isra.5 (STB_LOCAL)
ffffffff8131065c-ffffffff81310686: fname_decrypt.isra.5.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:90
Inline: True
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff813372c0-ffffffff8133746c: fname_decrypt.isra.0 (STB_LOCAL)
ffffffff81337a8c-ffffffff81337ac2: fname_decrypt.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:88
Inline: True
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff8134ae80-ffffffff8134b02c: fname_decrypt.isra.0 (STB_LOCAL)
ffffffff8134b63f-ffffffff8134b66d: fname_decrypt.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fname_decrypt(const struct inode *inode, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:166
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff813907c0-ffffffff8139095e: fname_decrypt (STB_LOCAL)
ffffffff81391028-ffffffff81391052: fname_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fname_decrypt(const struct inode *inode, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:140
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff813a1c40-ffffffff813a1dde: fname_decrypt (STB_LOCAL)
ffffffff81bead9e-ffffffff81beadc8: fname_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fname_decrypt(const struct inode *inode, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:140
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff813a8de0-ffffffff813a8f7e: fname_decrypt (STB_LOCAL)
ffffffff81bdcdeb-ffffffff81bdce15: fname_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fname_decrypt(const struct inode *inode, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:144
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff813f8570-ffffffff813f870e: fname_decrypt (STB_LOCAL)
ffffffff81cc62ed-ffffffff81cc6317: fname_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fname_decrypt(const struct inode *inode, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:151
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff8146b210-ffffffff8146b437: fname_decrypt (STB_LOCAL)
ffffffff81e787e4-ffffffff81e7880e: fname_decrypt.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fname_decrypt(const struct inode *inode, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff814fc690)
Location: fs/crypto/fname.c:153
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff814fc690-ffffffff814fc8e1: fname_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fname_decrypt(const struct inode *inode, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff81533c00)
Location: fs/crypto/fname.c:153
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff81533c00-ffffffff81533e51: fname_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fname_decrypt(const struct inode *inode, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (ffffffff81568b90)
Location: fs/crypto/fname.c:153
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff81568b90-ffffffff81568de1: fname_decrypt (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (ffff80001040b810)
Location: fs/crypto/fname.c:88
Inline: True
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffff80001040b810-ffff80001040b9dc: fname_decrypt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fname_decrypt(struct inode *inode, const struct fscrypt_str *iname, struct fscrypt_str *oname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/fname.c (c05d8974)
Location: fs/crypto/fname.c:88
Inline: False
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
c05d8974-c05d8b2c: fname_decrypt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (c000000000518400)
Location: fs/crypto/fname.c:88
Inline: True
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
c000000000518400-c00000000051863c: fname_decrypt.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (ffffffe0002b5382)
Location: fs/crypto/fname.c:88
Inline: True
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffe0002b5382-ffffffe0002b54f6: fname_decrypt.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:88
Inline: True
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff81343460-ffffffff8134360c: fname_decrypt.isra.0 (STB_LOCAL)
ffffffff81343c1f-ffffffff81343c4d: fname_decrypt.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:88
Inline: True
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff81334140-ffffffff813342ec: fname_decrypt.isra.0 (STB_LOCAL)
ffffffff813348ff-ffffffff8133492d: fname_decrypt.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:88
Inline: True
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff81340f30-ffffffff813410dc: fname_decrypt.isra.0 (STB_LOCAL)
ffffffff813416ef-ffffffff8134171d: fname_decrypt.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/fname.c (0)
Location: fs/crypto/fname.c:88
Inline: True
Direct callers:
  - fs/crypto/fname.c:fscrypt_fname_disk_to_usr
```
**Symbols:**

```
ffffffff81354230-ffffffff813543dc: fname_decrypt.isra.0 (STB_LOCAL)
ffffffff813549ef-ffffffff81354a1d: fname_decrypt.isra.0.cold (STB_LOCAL)
```
</details>
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
</ul>
