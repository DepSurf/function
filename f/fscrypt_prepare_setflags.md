# Function: <code>fscrypt_prepare_setflags</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int fscrypt_prepare_setflags(struct inode *inode, unsigned int oldflags, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81391a60)
Location: fs/crypto/hooks.c:138
Inline: False
Direct callers:
  - fs/inode.c:vfs_ioc_setflags_prepare
```
**Symbols:**

```
ffffffff81391a60-ffffffff81391b0e: fscrypt_prepare_setflags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fscrypt_prepare_setflags(struct inode *inode, unsigned int oldflags, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813a2e40)
Location: fs/crypto/hooks.c:141
Inline: False
Direct callers:
  - fs/inode.c:vfs_ioc_setflags_prepare
```
**Symbols:**

```
ffffffff813a2e40-ffffffff813a2eef: fscrypt_prepare_setflags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fscrypt_prepare_setflags(struct inode *inode, unsigned int oldflags, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813aa080)
Location: fs/crypto/hooks.c:141
Inline: False
Direct callers:
  - fs/ioctl.c:vfs_fileattr_set
```
**Symbols:**

```
ffffffff813aa080-ffffffff813aa12f: fscrypt_prepare_setflags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fscrypt_prepare_setflags(struct inode *inode, unsigned int oldflags, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813f98d0)
Location: fs/crypto/hooks.c:141
Inline: False
Direct callers:
  - fs/ioctl.c:fileattr_set_prepare
```
**Symbols:**

```
ffffffff813f98d0-ffffffff813f997f: fscrypt_prepare_setflags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fscrypt_prepare_setflags(struct inode *inode, unsigned int oldflags, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff8146c7b0)
Location: fs/crypto/hooks.c:141
Inline: False
Direct callers:
  - fs/ioctl.c:fileattr_set_prepare
```
**Symbols:**

```
ffffffff8146c7b0-ffffffff8146c872: fscrypt_prepare_setflags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fscrypt_prepare_setflags(struct inode *inode, unsigned int oldflags, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff814fdbc0)
Location: fs/crypto/hooks.c:139
Inline: False
Direct callers:
  - fs/ioctl.c:fileattr_set_prepare
```
**Symbols:**

```
ffffffff814fdbc0-ffffffff814fdc7a: fscrypt_prepare_setflags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fscrypt_prepare_setflags(struct inode *inode, unsigned int oldflags, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff815351b0)
Location: fs/crypto/hooks.c:169
Inline: False
Direct callers:
  - fs/ioctl.c:fileattr_set_prepare
```
**Symbols:**

```
ffffffff815351b0-ffffffff8153526a: fscrypt_prepare_setflags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int fscrypt_prepare_setflags(struct inode *inode, unsigned int oldflags, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/crypto/hooks.c (0)
Location: fs/crypto/hooks.c:169
Inline: False
Direct callers:
  - fs/ioctl.c:fileattr_set_prepare
```
**Symbols:**

```
ffffffff821c6e95-ffffffff821c6eaa: fscrypt_prepare_setflags.cold (STB_LOCAL)
ffffffff8156a170-ffffffff8156a23e: fscrypt_prepare_setflags (STB_GLOBAL)
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
