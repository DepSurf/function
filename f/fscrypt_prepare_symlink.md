# Function: <code>fscrypt_prepare_symlink</code>

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
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff8136f7ff)
Location: include/linux/fscrypt.h:213
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81387c8f)
Location: include/linux/fscrypt.h:213
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813b1cf9)
Location: include/linux/fscrypt.h:679
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813cad49)
Location: include/linux/fscrypt.h:728
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff81416d27)
Location: include/linux/fscrypt.h:711
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int fscrypt_prepare_symlink(struct inode *dir, const char *target, unsigned int len, unsigned int max_len, struct fscrypt_str *disk_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813a2950)
Location: fs/crypto/hooks.c:197
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
ffffffff813a2950-ffffffff813a29ce: fscrypt_prepare_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fscrypt_prepare_symlink(struct inode *dir, const char *target, unsigned int len, unsigned int max_len, struct fscrypt_str *disk_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813a9ae0)
Location: fs/crypto/hooks.c:197
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
ffffffff813a9ae0-ffffffff813a9b5e: fscrypt_prepare_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fscrypt_prepare_symlink(struct inode *dir, const char *target, unsigned int len, unsigned int max_len, struct fscrypt_str *disk_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813f9320)
Location: fs/crypto/hooks.c:197
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
ffffffff813f9320-ffffffff813f939e: fscrypt_prepare_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fscrypt_prepare_symlink(struct inode *dir, const char *target, unsigned int len, unsigned int max_len, struct fscrypt_str *disk_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff8146c210)
Location: fs/crypto/hooks.c:197
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
ffffffff8146c210-ffffffff8146c290: fscrypt_prepare_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fscrypt_prepare_symlink(struct inode *dir, const char *target, unsigned int len, unsigned int max_len, struct fscrypt_str *disk_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff814fd590)
Location: fs/crypto/hooks.c:193
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
ffffffff814fd590-ffffffff814fd610: fscrypt_prepare_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fscrypt_prepare_symlink(struct inode *dir, const char *target, unsigned int len, unsigned int max_len, struct fscrypt_str *disk_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81534af0)
Location: fs/crypto/hooks.c:223
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
ffffffff81534af0-ffffffff81534b70: fscrypt_prepare_symlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fscrypt_prepare_symlink(struct inode *dir, const char *target, unsigned int len, unsigned int max_len, struct fscrypt_str *disk_link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81569ab0)
Location: fs/crypto/hooks.c:223
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_symlink
```
**Symbols:**

```
ffffffff81569ab0-ffffffff81569b30: fscrypt_prepare_symlink (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffff8000104a2970)
Location: include/linux/fscrypt.h:728
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0664bc4)
Location: include/linux/fscrypt.h:728
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (c0000000005cf8f4)
Location: include/linux/fscrypt.h:728
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffe00032457e)
Location: include/linux/fscrypt.h:728
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c3329)
Location: include/linux/fscrypt.h:728
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813b3db9)
Location: include/linux/fscrypt.h:728
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813c07b9)
Location: include/linux/fscrypt.h:728
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/namei.c (ffffffff813d58e9)
Location: include/linux/fscrypt.h:728
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_symlink
```
</details>
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
