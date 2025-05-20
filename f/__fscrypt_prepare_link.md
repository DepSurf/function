# Function: <code>__fscrypt_prepare_link</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __fscrypt_prepare_link(struct inode *inode, struct inode *dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff812d0bd0)
Location: fs/crypto/hooks.c:51
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff812d0bd0-ffffffff812d0c1f: __fscrypt_prepare_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __fscrypt_prepare_link(struct inode *inode, struct inode *dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff812fb580)
Location: fs/crypto/hooks.c:52
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff812fb580-ffffffff812fb5cf: __fscrypt_prepare_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __fscrypt_prepare_link(struct inode *inode, struct inode *dir);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81310990)
Location: fs/crypto/hooks.c:52
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff81310990-ffffffff813109df: __fscrypt_prepare_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __fscrypt_prepare_link(struct inode *inode, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81337ea0)
Location: fs/crypto/hooks.c:52
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff81337ea0-ffffffff81337f00: __fscrypt_prepare_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __fscrypt_prepare_link(struct inode *inode, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff8134bf20)
Location: fs/crypto/hooks.c:52
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff8134bf20-ffffffff8134bf80: __fscrypt_prepare_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __fscrypt_prepare_link(struct inode *inode, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81391740)
Location: fs/crypto/hooks.c:54
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff81391740-ffffffff813917a0: __fscrypt_prepare_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __fscrypt_prepare_link(struct inode *inode, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813a2900)
Location: fs/crypto/hooks.c:54
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff813a2900-ffffffff813a2930: __fscrypt_prepare_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __fscrypt_prepare_link(struct inode *inode, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813a9a90)
Location: fs/crypto/hooks.c:54
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff813a9a90-ffffffff813a9ac0: __fscrypt_prepare_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __fscrypt_prepare_link(struct inode *inode, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813f92d0)
Location: fs/crypto/hooks.c:54
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff813f92d0-ffffffff813f9300: __fscrypt_prepare_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __fscrypt_prepare_link(struct inode *inode, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff8146c0f0)
Location: fs/crypto/hooks.c:54
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff8146c0f0-ffffffff8146c135: __fscrypt_prepare_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __fscrypt_prepare_link(struct inode *inode, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff814fd440)
Location: fs/crypto/hooks.c:52
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff814fd440-ffffffff814fd485: __fscrypt_prepare_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __fscrypt_prepare_link(struct inode *inode, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff815349a0)
Location: fs/crypto/hooks.c:52
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff815349a0-ffffffff815349e5: __fscrypt_prepare_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __fscrypt_prepare_link(struct inode *inode, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81569960)
Location: fs/crypto/hooks.c:52
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff81569960-ffffffff815699a5: __fscrypt_prepare_link (STB_GLOBAL)
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
int __fscrypt_prepare_link(struct inode *inode, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffff80001040c8d0)
Location: fs/crypto/hooks.c:52
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffff80001040c8d0-ffff80001040c948: __fscrypt_prepare_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __fscrypt_prepare_link(struct inode *inode, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (c05d9a4c)
Location: fs/crypto/hooks.c:52
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
c05d9a4c-c05d9ac4: __fscrypt_prepare_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __fscrypt_prepare_link(struct inode *inode, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (c000000000519bd0)
Location: fs/crypto/hooks.c:52
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
c000000000519bd0-c000000000519c88: __fscrypt_prepare_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __fscrypt_prepare_link(struct inode *inode, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffe0002b61de)
Location: fs/crypto/hooks.c:52
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffe0002b61de-ffffffe0002b624e: __fscrypt_prepare_link (STB_GLOBAL)
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
int __fscrypt_prepare_link(struct inode *inode, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81344500)
Location: fs/crypto/hooks.c:52
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff81344500-ffffffff81344560: __fscrypt_prepare_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __fscrypt_prepare_link(struct inode *inode, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813351e0)
Location: fs/crypto/hooks.c:52
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff813351e0-ffffffff81335240: __fscrypt_prepare_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __fscrypt_prepare_link(struct inode *inode, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff81341fd0)
Location: fs/crypto/hooks.c:52
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff81341fd0-ffffffff81342030: __fscrypt_prepare_link (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __fscrypt_prepare_link(struct inode *inode, struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/crypto/hooks.c (ffffffff813552d0)
Location: fs/crypto/hooks.c:52
Inline: False
Direct callers:
  - fs/ext4/namei.c:ext4_link
```
**Symbols:**

```
ffffffff813552d0-ffffffff81355330: __fscrypt_prepare_link (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dentry *dentry</code>
</li>
</ul>
</details>
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
