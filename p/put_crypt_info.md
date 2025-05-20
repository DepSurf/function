# Function: <code>put_crypt_info</code>

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
void put_crypt_info(struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff8128a090)
Location: fs/crypto/keyinfo.c:142
Inline: False
Direct callers:
  - fs/crypto/keyinfo.c:fscrypt_put_encryption_info
```
**Symbols:**

```
ffffffff8128a090-ffffffff8128a0cb: put_crypt_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void put_crypt_info(struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff8129edd0)
Location: fs/crypto/keyinfo.c:164
Inline: False
Direct callers:
  - fs/crypto/keyinfo.c:fscrypt_put_encryption_info
```
**Symbols:**

```
ffffffff8129edd0-ffffffff8129ee02: put_crypt_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff812ad86e)
Location: fs/crypto/keyinfo.c:175
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:fscrypt_put_encryption_info
Direct callers:
  - fs/crypto/keyinfo.c:fscrypt_put_encryption_info
```
**Symbols:**

```
ffffffff812ad800-ffffffff812ad838: put_crypt_info.part.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff812d0d61)
Location: fs/crypto/keyinfo.c:166
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:fscrypt_put_encryption_info
Direct callers:
  - fs/crypto/keyinfo.c:fscrypt_put_encryption_info
```
**Symbols:**

```
ffffffff812d0cf0-ffffffff812d0d28: put_crypt_info.part.5 (STB_LOCAL)
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
In fs/crypto/keyinfo.c (ffffffff812fb894)
Location: fs/crypto/keyinfo.c:211
Inline: True
Inline callers:
  - fs/crypto/keyinfo.c:fscrypt_put_encryption_info
Direct callers:
  - fs/crypto/keyinfo.c:fscrypt_put_encryption_info
```
**Symbols:**

```
ffffffff812fb840-ffffffff812fb878: put_crypt_info.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void put_crypt_info(struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff81311010)
Location: fs/crypto/keyinfo.c:490
Inline: False
Direct callers:
  - fs/crypto/keyinfo.c:fscrypt_put_encryption_info
```
**Symbols:**

```
ffffffff81311010-ffffffff813110b6: put_crypt_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void put_crypt_info(struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keyinfo.c (ffffffff81338390)
Location: fs/crypto/keyinfo.c:488
Inline: False
Direct callers:
  - fs/crypto/keyinfo.c:fscrypt_put_encryption_info
```
**Symbols:**

```
ffffffff81338390-ffffffff81338436: put_crypt_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void put_crypt_info(struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff8134d5e0)
Location: fs/crypto/keysetup.c:384
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_put_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff8134d5e0-ffffffff8134d6e0: put_crypt_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void put_crypt_info(struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff813932d0)
Location: fs/crypto/keysetup.c:395
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_put_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff813932d0-ffffffff813933ee: put_crypt_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void put_crypt_info(struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff813a46c0)
Location: fs/crypto/keysetup.c:441
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_put_encryption_info
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
**Symbols:**

```
ffffffff813a46c0-ffffffff813a47fa: put_crypt_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void put_crypt_info(struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff813ab800)
Location: fs/crypto/keysetup.c:465
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_put_encryption_info
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
**Symbols:**

```
ffffffff813ab800-ffffffff813ab93a: put_crypt_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void put_crypt_info(struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:498
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_put_encryption_info
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
**Symbols:**

```
ffffffff813fb090-ffffffff813fb1d6: put_crypt_info (STB_LOCAL)
ffffffff81cc64fd-ffffffff81cc6511: put_crypt_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void put_crypt_info(struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:485
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_put_encryption_info
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
**Symbols:**

```
ffffffff8146e3b0-ffffffff8146e50a: put_crypt_info (STB_LOCAL)
ffffffff81e7896c-ffffffff81e78981: put_crypt_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void put_crypt_info(struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:503
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_put_encryption_info
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
**Symbols:**

```
ffffffff814ffa10-ffffffff814ffb3f: put_crypt_info (STB_LOCAL)
ffffffff8206a5ef-ffffffff8206a604: put_crypt_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void put_crypt_info(struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:522
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_put_encryption_info
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
**Symbols:**

```
ffffffff81536fe0-ffffffff8153710f: put_crypt_info (STB_LOCAL)
ffffffff820ea3fd-ffffffff820ea412: put_crypt_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void put_crypt_info(struct fscrypt_inode_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:524
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_put_encryption_info
  - fs/crypto/keysetup.c:fscrypt_setup_encryption_info
```
**Symbols:**

```
ffffffff8156c0b0-ffffffff8156c1df: put_crypt_info (STB_LOCAL)
ffffffff821c6f5e-ffffffff821c6f73: put_crypt_info.cold (STB_LOCAL)
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
void put_crypt_info(struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffff80001040e630)
Location: fs/crypto/keysetup.c:384
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_put_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffff80001040e630-ffff80001040e76c: put_crypt_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void put_crypt_info(struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (c05db134)
Location: fs/crypto/keysetup.c:384
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_put_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
c05db134-c05db23c: put_crypt_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void put_crypt_info(struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (c00000000051bba0)
Location: fs/crypto/keysetup.c:384
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_put_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
c00000000051bba0-c00000000051bd50: put_crypt_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void put_crypt_info(struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffe0002b76ec)
Location: fs/crypto/keysetup.c:384
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_put_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffe0002b76ec-ffffffe0002b7800: put_crypt_info (STB_LOCAL)
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
void put_crypt_info(struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff81345bc0)
Location: fs/crypto/keysetup.c:384
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_put_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff81345bc0-ffffffff81345cc0: put_crypt_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void put_crypt_info(struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff813368a0)
Location: fs/crypto/keysetup.c:384
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_put_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff813368a0-ffffffff813369a0: put_crypt_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void put_crypt_info(struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff81343690)
Location: fs/crypto/keysetup.c:384
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_put_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff81343690-ffffffff81343790: put_crypt_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void put_crypt_info(struct fscrypt_info *ci);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff81356930)
Location: fs/crypto/keysetup.c:384
Inline: False
Direct callers:
  - fs/crypto/keysetup.c:fscrypt_put_encryption_info
  - fs/crypto/keysetup.c:fscrypt_get_encryption_info
```
**Symbols:**

```
ffffffff81356930-ffffffff81356a2e: put_crypt_info (STB_LOCAL)
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
