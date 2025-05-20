# Function: <code>cap_inode_setxattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cap_inode_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8133b240)
Location: security/commoncap.c:658
Inline: False
Direct callers:
  - security/security.c:security_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
```
**Symbols:**

```
ffffffff8133b240-ffffffff8133b2a2: cap_inode_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cap_inode_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff813707c0)
Location: security/commoncap.c:664
Inline: False
Direct callers:
  - security/security.c:security_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
```
**Symbols:**

```
ffffffff813707c0-ffffffff81370822: cap_inode_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cap_inode_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81386fd0)
Location: security/commoncap.c:659
Inline: False
Direct callers:
  - security/security.c:security_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
```
**Symbols:**

```
ffffffff81386fd0-ffffffff81387032: cap_inode_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cap_inode_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8139bc80)
Location: security/commoncap.c:880
Inline: False
Direct callers:
  - security/security.c:security_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
```
**Symbols:**

```
ffffffff8139bc80-ffffffff8139bcec: cap_inode_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cap_inode_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff813c1360)
Location: security/commoncap.c:917
Inline: False
Direct callers:
  - security/security.c:security_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
```
**Symbols:**

```
ffffffff813c1360-ffffffff813c13cc: cap_inode_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cap_inode_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff813f2280)
Location: security/commoncap.c:919
Inline: False
Direct callers:
  - security/security.c:security_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
```
**Symbols:**

```
ffffffff813f2280-ffffffff813f22e6: cap_inode_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cap_inode_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8140d540)
Location: security/commoncap.c:914
Inline: False
Direct callers:
  - security/security.c:security_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
```
**Symbols:**

```
ffffffff8140d540-ffffffff8140d5a6: cap_inode_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cap_inode_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8143a6b0)
Location: security/commoncap.c:911
Inline: False
Direct callers:
  - security/security.c:security_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
```
**Symbols:**

```
ffffffff8143a6b0-ffffffff8143a716: cap_inode_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cap_inode_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81454540)
Location: security/commoncap.c:911
Inline: False
Direct callers:
  - security/security.c:security_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
```
**Symbols:**

```
ffffffff81454540-ffffffff814545a6: cap_inode_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cap_inode_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff814a6e90)
Location: security/commoncap.c:913
Inline: False
Direct callers:
  - security/security.c:security_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
```
**Symbols:**

```
ffffffff814a6e90-ffffffff814a6ef6: cap_inode_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cap_inode_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff814c4440)
Location: security/commoncap.c:931
Inline: False
Direct callers:
  - security/security.c:security_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
```
**Symbols:**

```
ffffffff814c4440-ffffffff814c44a6: cap_inode_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cap_inode_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff814ca8d0)
Location: security/commoncap.c:992
Inline: False
Direct callers:
  - security/security.c:security_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
```
**Symbols:**

```
ffffffff814ca8d0-ffffffff814ca938: cap_inode_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cap_inode_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff815235e0)
Location: security/commoncap.c:992
Inline: False
Direct callers:
  - security/security.c:security_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
```
**Symbols:**

```
ffffffff815235e0-ffffffff81523648: cap_inode_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cap_inode_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff815b72c0)
Location: security/commoncap.c:995
Inline: False
Direct callers:
  - security/security.c:security_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
```
**Symbols:**

```
ffffffff815b72c0-ffffffff815b733b: cap_inode_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cap_inode_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81662580)
Location: security/commoncap.c:995
Inline: False
Direct callers:
  - security/security.c:security_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
```
**Symbols:**

```
ffffffff81662580-ffffffff816625fb: cap_inode_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cap_inode_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8169aa80)
Location: security/commoncap.c:990
Inline: False
Direct callers:
  - security/security.c:security_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
```
**Symbols:**

```
ffffffff8169aa80-ffffffff8169aafb: cap_inode_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cap_inode_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff816d71c0)
Location: security/commoncap.c:990
Inline: False
Direct callers:
  - security/security.c:security_inode_setxattr
```
**Symbols:**

```
ffffffff816d71c0-ffffffff816d723b: cap_inode_setxattr (STB_GLOBAL)
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
int cap_inode_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffff80001053f648)
Location: security/commoncap.c:911
Inline: False
Direct callers:
  - security/security.c:security_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
```
**Symbols:**

```
ffff80001053f648-ffff80001053f6d4: cap_inode_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cap_inode_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (c06f5784)
Location: security/commoncap.c:911
Inline: False
Direct callers:
  - security/security.c:security_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
```
**Symbols:**

```
c06f5784-c06f57fc: cap_inode_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cap_inode_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (c0000000006901c0)
Location: security/commoncap.c:911
Inline: False
Direct callers:
  - security/security.c:security_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
```
**Symbols:**

```
c0000000006901c0-c000000000690434: cap_inode_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cap_inode_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffe00039cb32)
Location: security/commoncap.c:911
Inline: False
Direct callers:
  - security/security.c:security_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
```
**Symbols:**

```
ffffffe00039cb32-ffffffe00039cbba: cap_inode_setxattr (STB_GLOBAL)
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
int cap_inode_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8144cb20)
Location: security/commoncap.c:911
Inline: False
Direct callers:
  - security/security.c:security_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
```
**Symbols:**

```
ffffffff8144cb20-ffffffff8144cb86: cap_inode_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cap_inode_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8143d570)
Location: security/commoncap.c:911
Inline: False
Direct callers:
  - security/security.c:security_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
```
**Symbols:**

```
ffffffff8143d570-ffffffff8143d5d6: cap_inode_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cap_inode_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff81448bc0)
Location: security/commoncap.c:911
Inline: False
Direct callers:
  - security/security.c:security_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
```
**Symbols:**

```
ffffffff81448bc0-ffffffff81448c26: cap_inode_setxattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cap_inode_setxattr(struct dentry *dentry, const char *name, const void *value, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/commoncap.c (ffffffff8145ff90)
Location: security/commoncap.c:911
Inline: False
Direct callers:
  - security/security.c:security_inode_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/smack/smack_lsm.c:smack_inode_setxattr
```
**Symbols:**

```
ffffffff8145ff90-ffffffff8145fff6: cap_inode_setxattr (STB_GLOBAL)
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
