# Function: <code>__fscrypt_prepare_setattr</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813a2df0)
Location: fs/crypto/hooks.c:122
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
ffffffff813a2df0-ffffffff813a2e35: __fscrypt_prepare_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813aa030)
Location: fs/crypto/hooks.c:122
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
ffffffff813aa030-ffffffff813aa075: __fscrypt_prepare_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813f9880)
Location: fs/crypto/hooks.c:122
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
ffffffff813f9880-ffffffff813f98c5: __fscrypt_prepare_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff8146c750)
Location: fs/crypto/hooks.c:122
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
ffffffff8146c750-ffffffff8146c7a5: __fscrypt_prepare_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff814fdb50)
Location: fs/crypto/hooks.c:120
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
ffffffff814fdb50-ffffffff814fdba5: __fscrypt_prepare_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81535140)
Location: fs/crypto/hooks.c:150
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
ffffffff81535140-ffffffff81535195: __fscrypt_prepare_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_setattr(struct dentry *dentry, struct iattr *attr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff8156a100)
Location: fs/crypto/hooks.c:150
Inline: True
Direct callers:
  - fs/ext4/inode.c:ext4_setattr
```
**Symbols:**

```
ffffffff8156a100-ffffffff8156a155: __fscrypt_prepare_setattr (STB_GLOBAL)
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
