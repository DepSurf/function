# Function: <code>fscrypt_drop_inode</code>

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
<summary>In <code>5.4</code>: ✅</summary>

```c
int fscrypt_drop_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff8134d470)
Location: fs/crypto/keysetup.c:566
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_drop_inode
```
**Symbols:**

```
ffffffff8134d470-ffffffff8134d4b5: fscrypt_drop_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fscrypt_drop_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff81393230)
Location: fs/crypto/keysetup.c:563
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_drop_inode
```
**Symbols:**

```
ffffffff81393230-ffffffff81393275: fscrypt_drop_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fscrypt_drop_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff813a4570)
Location: fs/crypto/keysetup.c:702
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_drop_inode
```
**Symbols:**

```
ffffffff813a4570-ffffffff813a45b5: fscrypt_drop_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fscrypt_drop_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff813ab760)
Location: fs/crypto/keysetup.c:726
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_drop_inode
```
**Symbols:**

```
ffffffff813ab760-ffffffff813ab7a5: fscrypt_drop_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fscrypt_drop_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff813faff0)
Location: fs/crypto/keysetup.c:759
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_drop_inode
```
**Symbols:**

```
ffffffff813faff0-ffffffff813fb035: fscrypt_drop_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fscrypt_drop_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff8146e2f0)
Location: fs/crypto/keysetup.c:746
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_drop_inode
```
**Symbols:**

```
ffffffff8146e2f0-ffffffff8146e345: fscrypt_drop_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fscrypt_drop_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff814ff940)
Location: fs/crypto/keysetup.c:755
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_drop_inode
```
**Symbols:**

```
ffffffff814ff940-ffffffff814ff98e: fscrypt_drop_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fscrypt_drop_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff81536f10)
Location: fs/crypto/keysetup.c:774
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_drop_inode
```
**Symbols:**

```
ffffffff81536f10-ffffffff81536f5e: fscrypt_drop_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fscrypt_drop_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/keysetup.c (0)
Location: fs/crypto/keysetup.c:781
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_drop_inode
```
**Symbols:**

```
ffffffff821c6f2e-ffffffff821c6f5e: fscrypt_drop_inode.cold (STB_LOCAL)
ffffffff8156bfc0-ffffffff8156c024: fscrypt_drop_inode (STB_GLOBAL)
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
int fscrypt_drop_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffff80001040e570)
Location: fs/crypto/keysetup.c:566
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_drop_inode
```
**Symbols:**

```
ffff80001040e570-ffff80001040e5d8: fscrypt_drop_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int fscrypt_drop_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (c05db0dc)
Location: fs/crypto/keysetup.c:566
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_drop_inode
```
**Symbols:**

```
c05db0dc-c05db134: fscrypt_drop_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int fscrypt_drop_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (c00000000051b990)
Location: fs/crypto/keysetup.c:566
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_drop_inode
```
**Symbols:**

```
c00000000051b990-c00000000051b9e8: fscrypt_drop_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int fscrypt_drop_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffe0002b7566)
Location: fs/crypto/keysetup.c:566
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_drop_inode
```
**Symbols:**

```
ffffffe0002b7566-ffffffe0002b75b4: fscrypt_drop_inode (STB_GLOBAL)
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
int fscrypt_drop_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff81345a50)
Location: fs/crypto/keysetup.c:566
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_drop_inode
```
**Symbols:**

```
ffffffff81345a50-ffffffff81345a95: fscrypt_drop_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int fscrypt_drop_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff81336730)
Location: fs/crypto/keysetup.c:566
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_drop_inode
```
**Symbols:**

```
ffffffff81336730-ffffffff81336775: fscrypt_drop_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int fscrypt_drop_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff81343520)
Location: fs/crypto/keysetup.c:566
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_drop_inode
```
**Symbols:**

```
ffffffff81343520-ffffffff81343565: fscrypt_drop_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int fscrypt_drop_inode(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff81356800)
Location: fs/crypto/keysetup.c:566
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_drop_inode
```
**Symbols:**

```
ffffffff81356800-ffffffff81356845: fscrypt_drop_inode (STB_GLOBAL)
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
