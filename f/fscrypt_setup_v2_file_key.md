# Function: <code>fscrypt_setup_v2_file_key</code>

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
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int fscrypt_setup_v2_file_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:248
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff8134da00-ffffffff8134dabe: fscrypt_setup_v2_file_key (STB_LOCAL)
ffffffff8134e05d-ffffffff8134e08f: fscrypt_setup_v2_file_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int fscrypt_setup_v2_file_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:238
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
```
**Symbols:**

```
ffffffff81393740-ffffffff813938ac: fscrypt_setup_v2_file_key (STB_LOCAL)
ffffffff81393f67-ffffffff81393f73: fscrypt_setup_v2_file_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fscrypt_setup_v2_file_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk, bool need_dirhash_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:279
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
```
**Symbols:**

```
ffffffff813a4cb0-ffffffff813a4e26: fscrypt_setup_v2_file_key (STB_LOCAL)
ffffffff81beaf52-ffffffff81beaf5e: fscrypt_setup_v2_file_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fscrypt_setup_v2_file_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk, bool need_dirhash_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:303
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
```
**Symbols:**

```
ffffffff813abd20-ffffffff813abf15: fscrypt_setup_v2_file_key (STB_LOCAL)
ffffffff81bdcfab-ffffffff81bdcfb7: fscrypt_setup_v2_file_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fscrypt_setup_v2_file_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk, bool need_dirhash_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:308
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
```
**Symbols:**

```
ffffffff813fb600-ffffffff813fb80f: fscrypt_setup_v2_file_key (STB_LOCAL)
ffffffff81cc663b-ffffffff81cc6671: fscrypt_setup_v2_file_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fscrypt_setup_v2_file_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk, bool need_dirhash_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:309
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
```
**Symbols:**

```
ffffffff8146e9c0-ffffffff8146ebf5: fscrypt_setup_v2_file_key (STB_LOCAL)
ffffffff81e78ab2-ffffffff81e78ada: fscrypt_setup_v2_file_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int fscrypt_setup_v2_file_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk, bool need_dirhash_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:332
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
**Symbols:**

```
ffffffff81500100-ffffffff81500338: fscrypt_setup_v2_file_key (STB_LOCAL)
ffffffff8206a6c0-ffffffff8206a6e8: fscrypt_setup_v2_file_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int fscrypt_setup_v2_file_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk, bool need_dirhash_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:332
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
```
**Symbols:**

```
ffffffff815376d0-ffffffff81537908: fscrypt_setup_v2_file_key (STB_LOCAL)
ffffffff820ea4ce-ffffffff820ea4f6: fscrypt_setup_v2_file_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fscrypt_setup_v2_file_key(struct fscrypt_inode_info *ci, struct fscrypt_master_key *mk, bool need_dirhash_key);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:333
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:setup_file_encryption_key
```
**Symbols:**

```
ffffffff8156c7a0-ffffffff8156c9d8: fscrypt_setup_v2_file_key (STB_LOCAL)
ffffffff821c702f-ffffffff821c7057: fscrypt_setup_v2_file_key.cold (STB_LOCAL)
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
int fscrypt_setup_v2_file_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffff80001040ecd0)
Location: fs/crypto/keysetup.c:248
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffff80001040ecd0-ffff80001040eddc: fscrypt_setup_v2_file_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fscrypt_setup_v2_file_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (c05db7f0)
Location: fs/crypto/keysetup.c:248
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
c05db7f0-c05db8fc: fscrypt_setup_v2_file_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fscrypt_setup_v2_file_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (c00000000051c360)
Location: fs/crypto/keysetup.c:248
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
c00000000051c360-c00000000051c4ac: fscrypt_setup_v2_file_key (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fscrypt_setup_v2_file_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffe0002b7af2)
Location: fs/crypto/keysetup.c:248
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffe0002b7af2-ffffffe0002b7baa: fscrypt_setup_v2_file_key (STB_LOCAL)
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
int fscrypt_setup_v2_file_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:248
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff81345fe0-ffffffff8134609e: fscrypt_setup_v2_file_key (STB_LOCAL)
ffffffff8134663d-ffffffff8134666f: fscrypt_setup_v2_file_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int fscrypt_setup_v2_file_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:248
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff81336cc0-ffffffff81336d7e: fscrypt_setup_v2_file_key (STB_LOCAL)
ffffffff8133731d-ffffffff8133734f: fscrypt_setup_v2_file_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int fscrypt_setup_v2_file_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:248
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff81343ab0-ffffffff81343b6e: fscrypt_setup_v2_file_key (STB_LOCAL)
ffffffff8134410d-ffffffff8134413f: fscrypt_setup_v2_file_key.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int fscrypt_setup_v2_file_key(struct fscrypt_info *ci, struct fscrypt_master_key *mk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:248
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff81356d90-ffffffff81356e4e: fscrypt_setup_v2_file_key (STB_LOCAL)
ffffffff813573eb-ffffffff8135741d: fscrypt_setup_v2_file_key.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool need_dirhash_key</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fscrypt_info *ci</code> ➡️ <code>struct fscrypt_inode_info *ci</code>
</li>
</ul>
</details>
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
