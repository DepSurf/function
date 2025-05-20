# Function: <code>ext4_xattr_set</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_xattr_set(struct inode *inode, int name_index, const char *name, const void *value, size_t value_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff812de980)
Location: fs/ext4/xattr.c:1199
Inline: False
Direct callers:
  - fs/ext4/xattr_user.c:ext4_xattr_user_set
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set
  - fs/ext4/xattr_security.c:ext4_xattr_security_set
  - fs/ext4/crypto_policy.c:ext4_process_policy
  - fs/ext4/crypto_policy.c:ext4_inherit_context
```
**Symbols:**

```
ffffffff812de980-ffffffff812deabd: ext4_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_xattr_set(struct inode *inode, int name_index, const char *name, const void *value, size_t value_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8130e670)
Location: fs/ext4/xattr.c:1288
Inline: False
Direct callers:
  - fs/ext4/xattr_user.c:ext4_xattr_user_set
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set
  - fs/ext4/xattr_security.c:ext4_xattr_security_set
```
**Symbols:**

```
ffffffff8130e670-ffffffff8130e7bd: ext4_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_xattr_set(struct inode *inode, int name_index, const char *name, const void *value, size_t value_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813243b0)
Location: fs/ext4/xattr.c:1289
Inline: False
Direct callers:
  - fs/ext4/xattr_user.c:ext4_xattr_user_set
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set
  - fs/ext4/xattr_security.c:ext4_xattr_security_set
```
**Symbols:**

```
ffffffff813243b0-ffffffff813244fd: ext4_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_xattr_set(struct inode *inode, int name_index, const char *name, const void *value, size_t value_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8133e0e0)
Location: fs/ext4/xattr.c:2428
Inline: False
Direct callers:
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set
  - fs/ext4/xattr_user.c:ext4_xattr_user_set
  - fs/ext4/xattr_security.c:ext4_xattr_security_set
```
**Symbols:**

```
ffffffff8133e0e0-ffffffff8133e21e: ext4_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_xattr_set(struct inode *inode, int name_index, const char *name, const void *value, size_t value_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813626c0)
Location: fs/ext4/xattr.c:2464
Inline: False
Direct callers:
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set
  - fs/ext4/xattr_user.c:ext4_xattr_user_set
  - fs/ext4/xattr_security.c:ext4_xattr_security_set
```
**Symbols:**

```
ffffffff813626c0-ffffffff813627fe: ext4_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_xattr_set(struct inode *inode, int name_index, const char *name, const void *value, size_t value_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81390e50)
Location: fs/ext4/xattr.c:2480
Inline: False
Direct callers:
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set
  - fs/ext4/xattr_user.c:ext4_xattr_user_set
  - fs/ext4/xattr_security.c:ext4_xattr_security_set
```
**Symbols:**

```
ffffffff81390e50-ffffffff81390f8e: ext4_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_xattr_set(struct inode *inode, int name_index, const char *name, const void *value, size_t value_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813a9a50)
Location: fs/ext4/xattr.c:2479
Inline: False
Direct callers:
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set
  - fs/ext4/xattr_user.c:ext4_xattr_user_set
  - fs/ext4/xattr_security.c:ext4_xattr_security_set
```
**Symbols:**

```
ffffffff813a9a50-ffffffff813a9b8e: ext4_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_xattr_set(struct inode *inode, int name_index, const char *name, const void *value, size_t value_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d3fd0)
Location: fs/ext4/xattr.c:2480
Inline: False
Direct callers:
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set
  - fs/ext4/xattr_user.c:ext4_xattr_user_set
  - fs/ext4/xattr_security.c:ext4_xattr_security_set
```
**Symbols:**

```
ffffffff813d3fd0-ffffffff813d4112: ext4_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_xattr_set(struct inode *inode, int name_index, const char *name, const void *value, size_t value_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813ed6b0)
Location: fs/ext4/xattr.c:2480
Inline: False
Direct callers:
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set
  - fs/ext4/xattr_user.c:ext4_xattr_user_set
  - fs/ext4/xattr_security.c:ext4_xattr_security_set
```
**Symbols:**

```
ffffffff813ed6b0-ffffffff813ed7f2: ext4_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_xattr_set(struct inode *inode, int name_index, const char *name, const void *value, size_t value_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8143a6e0)
Location: fs/ext4/xattr.c:2467
Inline: False
Direct callers:
  - fs/ext4/xattr_hurd.c:ext4_xattr_hurd_set
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set
  - fs/ext4/xattr_user.c:ext4_xattr_user_set
  - fs/ext4/xattr_security.c:ext4_xattr_security_set
```
**Symbols:**

```
ffffffff8143a6e0-ffffffff8143a812: ext4_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_xattr_set(struct inode *inode, int name_index, const char *name, const void *value, size_t value_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81453250)
Location: fs/ext4/xattr.c:2473
Inline: False
Direct callers:
  - fs/ext4/xattr_hurd.c:ext4_xattr_hurd_set
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set
  - fs/ext4/xattr_user.c:ext4_xattr_user_set
  - fs/ext4/xattr_security.c:ext4_xattr_security_set
```
**Symbols:**

```
ffffffff81453250-ffffffff8145338d: ext4_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_xattr_set(struct inode *inode, int name_index, const char *name, const void *value, size_t value_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81458ab0)
Location: fs/ext4/xattr.c:2473
Inline: False
Direct callers:
  - fs/ext4/xattr_hurd.c:ext4_xattr_hurd_set
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set
  - fs/ext4/xattr_user.c:ext4_xattr_user_set
  - fs/ext4/xattr_security.c:ext4_xattr_security_set
```
**Symbols:**

```
ffffffff81458ab0-ffffffff81458bed: ext4_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_xattr_set(struct inode *inode, int name_index, const char *name, const void *value, size_t value_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814acbc0)
Location: fs/ext4/xattr.c:2456
Inline: False
Direct callers:
  - fs/ext4/xattr_hurd.c:ext4_xattr_hurd_set
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set
  - fs/ext4/xattr_user.c:ext4_xattr_user_set
  - fs/ext4/xattr_security.c:ext4_xattr_security_set
```
**Symbols:**

```
ffffffff814acbc0-ffffffff814accff: ext4_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_xattr_set(struct inode *inode, int name_index, const char *name, const void *value, size_t value_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81534b90)
Location: fs/ext4/xattr.c:2471
Inline: False
Direct callers:
  - fs/ext4/xattr_hurd.c:ext4_xattr_hurd_set
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set
  - fs/ext4/xattr_user.c:ext4_xattr_user_set
  - fs/ext4/xattr_security.c:ext4_xattr_security_set
```
**Symbols:**

```
ffffffff81534b90-ffffffff81534cf5: ext4_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_xattr_set(struct inode *inode, int name_index, const char *name, const void *value, size_t value_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff815d30d0)
Location: fs/ext4/xattr.c:2491
Inline: False
Direct callers:
  - fs/ext4/xattr_hurd.c:ext4_xattr_hurd_set
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set
  - fs/ext4/xattr_user.c:ext4_xattr_user_set
  - fs/ext4/xattr_security.c:ext4_xattr_security_set
```
**Symbols:**

```
ffffffff815d30d0-ffffffff815d3236: ext4_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_xattr_set(struct inode *inode, int name_index, const char *name, const void *value, size_t value_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8160ac40)
Location: fs/ext4/xattr.c:2534
Inline: False
Direct callers:
  - fs/ext4/xattr_hurd.c:ext4_xattr_hurd_set
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set
  - fs/ext4/xattr_user.c:ext4_xattr_user_set
  - fs/ext4/xattr_security.c:ext4_xattr_security_set
```
**Symbols:**

```
ffffffff8160ac40-ffffffff8160ada0: ext4_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_xattr_set(struct inode *inode, int name_index, const char *name, const void *value, size_t value_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81643a00)
Location: fs/ext4/xattr.c:2534
Inline: False
Direct callers:
  - fs/ext4/xattr_hurd.c:ext4_xattr_hurd_set
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set
  - fs/ext4/xattr_user.c:ext4_xattr_user_set
  - fs/ext4/xattr_security.c:ext4_xattr_security_set
```
**Symbols:**

```
ffffffff81643a00-ffffffff81643b60: ext4_xattr_set (STB_GLOBAL)
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
int ext4_xattr_set(struct inode *inode, int name_index, const char *name, const void *value, size_t value_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffff8000104c6338)
Location: fs/ext4/xattr.c:2480
Inline: False
Direct callers:
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set
  - fs/ext4/xattr_user.c:ext4_xattr_user_set
  - fs/ext4/xattr_security.c:ext4_xattr_security_set
```
**Symbols:**

```
ffff8000104c6338-ffff8000104c64bc: ext4_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_xattr_set(struct inode *inode, int name_index, const char *name, const void *value, size_t value_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c068a31c)
Location: fs/ext4/xattr.c:2480
Inline: False
Direct callers:
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set
  - fs/ext4/xattr_user.c:ext4_xattr_user_set
  - fs/ext4/xattr_security.c:ext4_xattr_security_set
```
**Symbols:**

```
c068a31c-c068a470: ext4_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_xattr_set(struct inode *inode, int name_index, const char *name, const void *value, size_t value_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0000000005fe8c0)
Location: fs/ext4/xattr.c:2480
Inline: False
Direct callers:
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set
  - fs/ext4/xattr_user.c:ext4_xattr_user_set
  - fs/ext4/xattr_security.c:ext4_xattr_security_set
```
**Symbols:**

```
c0000000005fe8c0-c0000000005feae4: ext4_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_xattr_set(struct inode *inode, int name_index, const char *name, const void *value, size_t value_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffe00034086e)
Location: fs/ext4/xattr.c:2480
Inline: False
Direct callers:
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set
  - fs/ext4/xattr_user.c:ext4_xattr_user_set
  - fs/ext4/xattr_security.c:ext4_xattr_security_set
```
**Symbols:**

```
ffffffe00034086e-ffffffe000340984: ext4_xattr_set (STB_GLOBAL)
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
int ext4_xattr_set(struct inode *inode, int name_index, const char *name, const void *value, size_t value_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e5c90)
Location: fs/ext4/xattr.c:2480
Inline: False
Direct callers:
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set
  - fs/ext4/xattr_user.c:ext4_xattr_user_set
  - fs/ext4/xattr_security.c:ext4_xattr_security_set
```
**Symbols:**

```
ffffffff813e5c90-ffffffff813e5dd2: ext4_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_xattr_set(struct inode *inode, int name_index, const char *name, const void *value, size_t value_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d6710)
Location: fs/ext4/xattr.c:2480
Inline: False
Direct callers:
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set
  - fs/ext4/xattr_user.c:ext4_xattr_user_set
  - fs/ext4/xattr_security.c:ext4_xattr_security_set
```
**Symbols:**

```
ffffffff813d6710-ffffffff813d6852: ext4_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_xattr_set(struct inode *inode, int name_index, const char *name, const void *value, size_t value_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e3010)
Location: fs/ext4/xattr.c:2480
Inline: False
Direct callers:
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set
  - fs/ext4/xattr_user.c:ext4_xattr_user_set
  - fs/ext4/xattr_security.c:ext4_xattr_security_set
```
**Symbols:**

```
ffffffff813e3010-ffffffff813e3152: ext4_xattr_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_xattr_set(struct inode *inode, int name_index, const char *name, const void *value, size_t value_len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813f8420)
Location: fs/ext4/xattr.c:2480
Inline: False
Direct callers:
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_set
  - fs/ext4/xattr_user.c:ext4_xattr_user_set
  - fs/ext4/xattr_security.c:ext4_xattr_security_set
```
**Symbols:**

```
ffffffff813f8420-ffffffff813f8562: ext4_xattr_set (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
