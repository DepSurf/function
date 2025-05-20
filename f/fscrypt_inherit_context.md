# Function: <code>fscrypt_inherit_context</code>

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
int fscrypt_inherit_context(struct inode *parent, struct inode *child, void *fs_data, bool preload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81289e40)
Location: fs/crypto/policy.c:207
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff81289e40-ffffffff81289f73: fscrypt_inherit_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fscrypt_inherit_context(struct inode *parent, struct inode *child, void *fs_data, bool preload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff8129eb60)
Location: fs/crypto/policy.c:224
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff8129eb60-ffffffff8129ec93: fscrypt_inherit_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_inherit_context(struct inode *parent, struct inode *child, void *fs_data, bool preload);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff812ad710)
Location: fs/crypto/policy.c:237
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff812ad710-ffffffff812ad7de: fscrypt_inherit_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_inherit_context(struct inode *parent, struct inode *child, void *fs_data, bool preload);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff812d1a30)
Location: fs/crypto/policy.c:238
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff812d1a30-ffffffff812d1b08: fscrypt_inherit_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int fscrypt_inherit_context(struct inode *parent, struct inode *child, void *fs_data, bool preload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff812fc510)
Location: fs/crypto/policy.c:238
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff812fc510-ffffffff812fc5e8: fscrypt_inherit_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int fscrypt_inherit_context(struct inode *parent, struct inode *child, void *fs_data, bool preload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81311d80)
Location: fs/crypto/policy.c:239
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff81311d80-ffffffff81311e4f: fscrypt_inherit_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int fscrypt_inherit_context(struct inode *parent, struct inode *child, void *fs_data, bool preload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff813392f0)
Location: fs/crypto/policy.c:240
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff813392f0-ffffffff813393b9: fscrypt_inherit_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_inherit_context(struct inode *parent, struct inode *child, void *fs_data, bool preload);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff8134e980)
Location: fs/crypto/policy.c:469
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff8134e980-ffffffff8134ea2b: fscrypt_inherit_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fscrypt_inherit_context(struct inode *parent, struct inode *child, void *fs_data, bool preload);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81394890)
Location: fs/crypto/policy.c:618
Inline: False
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff81394890-ffffffff8139493b: fscrypt_inherit_context (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_inherit_context(struct inode *parent, struct inode *child, void *fs_data, bool preload);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffff80001040fd00)
Location: fs/crypto/policy.c:469
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffff80001040fd00-ffff80001040fdc4: fscrypt_inherit_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_inherit_context(struct inode *parent, struct inode *child, void *fs_data, bool preload);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (c05dc760)
Location: fs/crypto/policy.c:469
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
c05dc760-c05dc828: fscrypt_inherit_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_inherit_context(struct inode *parent, struct inode *child, void *fs_data, bool preload);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (c00000000051d840)
Location: fs/crypto/policy.c:469
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
c00000000051d840-c00000000051d940: fscrypt_inherit_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_inherit_context(struct inode *parent, struct inode *child, void *fs_data, bool preload);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffe0002b88ee)
Location: fs/crypto/policy.c:469
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffe0002b88ee-ffffffe0002b897c: fscrypt_inherit_context (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_inherit_context(struct inode *parent, struct inode *child, void *fs_data, bool preload);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81346f60)
Location: fs/crypto/policy.c:469
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff81346f60-ffffffff8134700b: fscrypt_inherit_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_inherit_context(struct inode *parent, struct inode *child, void *fs_data, bool preload);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81337c40)
Location: fs/crypto/policy.c:469
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff81337c40-ffffffff81337ceb: fscrypt_inherit_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_inherit_context(struct inode *parent, struct inode *child, void *fs_data, bool preload);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81344a30)
Location: fs/crypto/policy.c:469
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff81344a30-ffffffff81344adb: fscrypt_inherit_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int fscrypt_inherit_context(struct inode *parent, struct inode *child, void *fs_data, bool preload);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/policy.c (ffffffff81357d10)
Location: fs/crypto/policy.c:469
Inline: True
Direct callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
```
**Symbols:**

```
ffffffff81357d10-ffffffff81357dbb: fscrypt_inherit_context (STB_GLOBAL)
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
