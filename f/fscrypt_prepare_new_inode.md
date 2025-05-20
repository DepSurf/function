# Function: <code>fscrypt_prepare_new_inode</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fscrypt_prepare_new_inode(struct inode *dir, struct inode *inode, bool *encrypt_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff813a52d0)
Location: fs/crypto/keysetup.c:629
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff813a52d0-ffffffff813a53ae: fscrypt_prepare_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fscrypt_prepare_new_inode(struct inode *dir, struct inode *inode, bool *encrypt_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff813ac3b0)
Location: fs/crypto/keysetup.c:653
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff813ac3b0-ffffffff813ac48e: fscrypt_prepare_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fscrypt_prepare_new_inode(struct inode *dir, struct inode *inode, bool *encrypt_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff813fbd20)
Location: fs/crypto/keysetup.c:686
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff813fbd20-ffffffff813fbdfe: fscrypt_prepare_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fscrypt_prepare_new_inode(struct inode *dir, struct inode *inode, bool *encrypt_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff8146f0c0)
Location: fs/crypto/keysetup.c:673
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff8146f0c0-ffffffff8146f1ba: fscrypt_prepare_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fscrypt_prepare_new_inode(struct inode *dir, struct inode *inode, bool *encrypt_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff815007b0)
Location: fs/crypto/keysetup.c:682
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff815007b0-ffffffff815008aa: fscrypt_prepare_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fscrypt_prepare_new_inode(struct inode *dir, struct inode *inode, bool *encrypt_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff81537e40)
Location: fs/crypto/keysetup.c:701
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff81537e40-ffffffff81537f3a: fscrypt_prepare_new_inode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fscrypt_prepare_new_inode(struct inode *dir, struct inode *inode, bool *encrypt_ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/keysetup.c (ffffffff8156cf90)
Location: fs/crypto/keysetup.c:708
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff8156cf90-ffffffff8156d08a: fscrypt_prepare_new_inode (STB_GLOBAL)
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
