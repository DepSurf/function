# Function: <code>ext4_xattr_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff812de150)
Location: fs/ext4/xattr.c:379
Inline: False
Direct callers:
  - fs/ext4/xattr_user.c:ext4_xattr_user_get
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_get
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/xattr_security.c:ext4_xattr_security_get
  - fs/ext4/crypto_policy.c:ext4_process_policy
  - fs/ext4/crypto_policy.c:ext4_process_policy
  - fs/ext4/crypto_policy.c:ext4_get_policy
  - fs/ext4/crypto_key.c:_ext4_get_encryption_info
```
**Symbols:**

```
ffffffff812de150-ffffffff812de363: ext4_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8130dd80)
Location: fs/ext4/xattr.c:399
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_context
  - fs/ext4/xattr_user.c:ext4_xattr_user_get
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_get
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/xattr_security.c:ext4_xattr_security_get
```
**Symbols:**

```
ffffffff8130dd80-ffffffff8130dfaf: ext4_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81323b00)
Location: fs/ext4/xattr.c:404
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_context
  - fs/ext4/xattr_user.c:ext4_xattr_user_get
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_get
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/xattr_security.c:ext4_xattr_security_get
```
**Symbols:**

```
ffffffff81323b00-ffffffff81323d2e: ext4_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8133cfd0)
Location: fs/ext4/xattr.c:596
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_context
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_get
  - fs/ext4/xattr_user.c:ext4_xattr_user_get
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/xattr_security.c:ext4_xattr_security_get
```
**Symbols:**

```
ffffffff8133cfd0-ffffffff8133d24b: ext4_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813615b0)
Location: fs/ext4/xattr.c:606
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_context
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_get
  - fs/ext4/xattr_user.c:ext4_xattr_user_get
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/xattr_security.c:ext4_xattr_security_get
```
**Symbols:**

```
ffffffff813615b0-ffffffff8136182b: ext4_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8138fd80)
Location: fs/ext4/xattr.c:638
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_context
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_get
  - fs/ext4/xattr_user.c:ext4_xattr_user_get
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/xattr_security.c:ext4_xattr_security_get
```
**Symbols:**

```
ffffffff8138fd80-ffffffff81390030: ext4_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813a89d0)
Location: fs/ext4/xattr.c:637
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_context
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_get
  - fs/ext4/xattr_user.c:ext4_xattr_user_get
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/xattr_security.c:ext4_xattr_security_get
```
**Symbols:**

```
ffffffff813a89d0-ffffffff813a8c7c: ext4_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d2be0)
Location: fs/ext4/xattr.c:637
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_context
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_get
  - fs/ext4/xattr_user.c:ext4_xattr_user_get
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/xattr_security.c:ext4_xattr_security_get
```
**Symbols:**

```
ffffffff813d2be0-ffffffff813d2eb9: ext4_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813ec2c0)
Location: fs/ext4/xattr.c:637
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_context
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_get
  - fs/ext4/xattr_user.c:ext4_xattr_user_get
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/xattr_security.c:ext4_xattr_security_get
```
**Symbols:**

```
ffffffff813ec2c0-ffffffff813ec599: ext4_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814395d0)
Location: fs/ext4/xattr.c:639
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_context
  - fs/ext4/xattr_hurd.c:ext4_xattr_hurd_get
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_get
  - fs/ext4/xattr_user.c:ext4_xattr_user_get
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/xattr_security.c:ext4_xattr_security_get
```
**Symbols:**

```
ffffffff814395d0-ffffffff81439694: ext4_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814520f0)
Location: fs/ext4/xattr.c:639
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_context
  - fs/ext4/xattr_hurd.c:ext4_xattr_hurd_get
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_get
  - fs/ext4/xattr_user.c:ext4_xattr_user_get
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/xattr_security.c:ext4_xattr_security_get
```
**Symbols:**

```
ffffffff814520f0-ffffffff814521b4: ext4_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81457830)
Location: fs/ext4/xattr.c:639
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_context
  - fs/ext4/xattr_hurd.c:ext4_xattr_hurd_get
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_get
  - fs/ext4/xattr_user.c:ext4_xattr_user_get
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/xattr_security.c:ext4_xattr_security_get
```
**Symbols:**

```
ffffffff81457830-ffffffff814578f4: ext4_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814ab910)
Location: fs/ext4/xattr.c:639
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_context
  - fs/ext4/xattr_hurd.c:ext4_xattr_hurd_get
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_get
  - fs/ext4/xattr_user.c:ext4_xattr_user_get
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/xattr_security.c:ext4_xattr_security_get
```
**Symbols:**

```
ffffffff814ab910-ffffffff814ab9d4: ext4_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81533780)
Location: fs/ext4/xattr.c:654
Inline: False
Direct callers:
  - fs/ext4/xattr_hurd.c:ext4_xattr_hurd_get
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_get
  - fs/ext4/xattr_user.c:ext4_xattr_user_get
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/xattr_security.c:ext4_xattr_security_get
  - fs/ext4/crypto.c:ext4_get_context
```
**Symbols:**

```
ffffffff81533780-ffffffff81533867: ext4_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff815d1d50)
Location: fs/ext4/xattr.c:670
Inline: False
Direct callers:
  - fs/ext4/xattr_hurd.c:ext4_xattr_hurd_get
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_get
  - fs/ext4/xattr_user.c:ext4_xattr_user_get
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/xattr_security.c:ext4_xattr_security_get
  - fs/ext4/crypto.c:ext4_get_context
```
**Symbols:**

```
ffffffff815d1d50-ffffffff815d1e37: ext4_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff816097f0)
Location: fs/ext4/xattr.c:699
Inline: False
Direct callers:
  - fs/ext4/xattr_hurd.c:ext4_xattr_hurd_get
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_get
  - fs/ext4/xattr_user.c:ext4_xattr_user_get
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/xattr_security.c:ext4_xattr_security_get
  - fs/ext4/crypto.c:ext4_get_context
```
**Symbols:**

```
ffffffff816097f0-ffffffff816098d7: ext4_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81642540)
Location: fs/ext4/xattr.c:699
Inline: False
Direct callers:
  - fs/ext4/xattr_hurd.c:ext4_xattr_hurd_get
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_get
  - fs/ext4/xattr_user.c:ext4_xattr_user_get
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/xattr_security.c:ext4_xattr_security_get
  - fs/ext4/crypto.c:ext4_get_context
```
**Symbols:**

```
ffffffff81642540-ffffffff81642627: ext4_xattr_get (STB_GLOBAL)
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
int ext4_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffff8000104c51c8)
Location: fs/ext4/xattr.c:637
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_context
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_get
  - fs/ext4/xattr_user.c:ext4_xattr_user_get
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/xattr_security.c:ext4_xattr_security_get
```
**Symbols:**

```
ffff8000104c51c8-ffff8000104c5494: ext4_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0689284)
Location: fs/ext4/xattr.c:637
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_context
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_get
  - fs/ext4/xattr_user.c:ext4_xattr_user_get
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/xattr_security.c:ext4_xattr_security_get
```
**Symbols:**

```
c0689284-c0689520: ext4_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0000000005fce80)
Location: fs/ext4/xattr.c:637
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_context
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_get
  - fs/ext4/xattr_user.c:ext4_xattr_user_get
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/xattr_security.c:ext4_xattr_security_get
```
**Symbols:**

```
c0000000005fce80-c0000000005fd220: ext4_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffe00033fa74)
Location: fs/ext4/xattr.c:637
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_context
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_get
  - fs/ext4/xattr_user.c:ext4_xattr_user_get
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/xattr_security.c:ext4_xattr_security_get
```
**Symbols:**

```
ffffffe00033fa74-ffffffe00033fca4: ext4_xattr_get (STB_GLOBAL)
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
int ext4_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e48a0)
Location: fs/ext4/xattr.c:637
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_context
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_get
  - fs/ext4/xattr_user.c:ext4_xattr_user_get
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/xattr_security.c:ext4_xattr_security_get
```
**Symbols:**

```
ffffffff813e48a0-ffffffff813e4b79: ext4_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d5320)
Location: fs/ext4/xattr.c:637
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_context
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_get
  - fs/ext4/xattr_user.c:ext4_xattr_user_get
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/xattr_security.c:ext4_xattr_security_get
```
**Symbols:**

```
ffffffff813d5320-ffffffff813d55f9: ext4_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e1c20)
Location: fs/ext4/xattr.c:637
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_context
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_get
  - fs/ext4/xattr_user.c:ext4_xattr_user_get
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/xattr_security.c:ext4_xattr_security_get
```
**Symbols:**

```
ffffffff813e1c20-ffffffff813e1ef9: ext4_xattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_xattr_get(struct inode *inode, int name_index, const char *name, void *buffer, size_t buffer_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813f7030)
Location: fs/ext4/xattr.c:637
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_get_context
  - fs/ext4/xattr_trusted.c:ext4_xattr_trusted_get
  - fs/ext4/xattr_user.c:ext4_xattr_user_get
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/acl.c:ext4_get_acl
  - fs/ext4/xattr_security.c:ext4_xattr_security_get
```
**Symbols:**

```
ffffffff813f7030-ffffffff813f7309: ext4_xattr_get (STB_GLOBAL)
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
