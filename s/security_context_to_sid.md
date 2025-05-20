# Function: <code>security_context_to_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid(const char *scontext, u32 scontext_len, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81358450)
Location: security/selinux/ss/services.c:1469
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_context_str_to_sid
Direct callers:
  - security/selinux/hooks.c:selinux_secctx_to_secid
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
**Symbols:**

```
ffffffff81358450-ffffffff81358468: security_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid(const char *scontext, u32 scontext_len, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138e3dc)
Location: security/selinux/ss/services.c:1463
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_context_str_to_sid
Direct callers:
  - security/selinux/hooks.c:selinux_secctx_to_secid
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
**Symbols:**

```
ffffffff8138e3a0-ffffffff8138e3b8: security_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid(const char *scontext, u32 scontext_len, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a4ffc)
Location: security/selinux/ss/services.c:1463
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_context_str_to_sid
Direct callers:
  - security/selinux/hooks.c:selinux_secctx_to_secid
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
**Symbols:**

```
ffffffff813a4fc0-ffffffff813a4fd8: security_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid(const char *scontext, u32 scontext_len, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bb9ac)
Location: security/selinux/ss/services.c:1475
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_context_str_to_sid
Direct callers:
  - security/selinux/hooks.c:selinux_secctx_to_secid
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
**Symbols:**

```
ffffffff813bb970-ffffffff813bb988: security_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid(const char *scontext, u32 scontext_len, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e1b1c)
Location: security/selinux/ss/services.c:1478
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_context_str_to_sid
Direct callers:
  - security/selinux/hooks.c:selinux_secctx_to_secid
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
**Symbols:**

```
ffffffff813e1ae0-ffffffff813e1af8: security_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81412164)
Location: security/selinux/ss/services.c:1523
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_context_str_to_sid
Direct callers:
  - security/selinux/hooks.c:selinux_secctx_to_secid
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
**Symbols:**

```
ffffffff81412110-ffffffff8141213a: security_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142e684)
Location: security/selinux/ss/services.c:1516
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_context_str_to_sid
Direct callers:
  - security/selinux/hooks.c:selinux_secctx_to_secid
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
**Symbols:**

```
ffffffff8142e630-ffffffff8142e65a: security_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145c017)
Location: security/selinux/ss/services.c:1526
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_context_str_to_sid
Direct callers:
  - security/selinux/hooks.c:selinux_secctx_to_secid
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
**Symbols:**

```
ffffffff8145bfb0-ffffffff8145bfda: security_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81475dc7)
Location: security/selinux/ss/services.c:1526
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_context_str_to_sid
Direct callers:
  - security/selinux/hooks.c:selinux_secctx_to_secid
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
**Symbols:**

```
ffffffff81475d60-ffffffff81475d8a: security_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814cb594)
Location: security/selinux/ss/services.c:1569
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_context_str_to_sid
Direct callers:
  - security/selinux/hooks.c:selinux_secctx_to_secid
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
**Symbols:**

```
ffffffff814cb540-ffffffff814cb558: security_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e8da4)
Location: security/selinux/ss/services.c:1588
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_context_str_to_sid
Direct callers:
  - security/selinux/hooks.c:selinux_secctx_to_secid
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
**Symbols:**

```
ffffffff814e8d50-ffffffff814e8d68: security_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814ef6c3)
Location: security/selinux/ss/services.c:1600
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_context_str_to_sid
Direct callers:
  - security/selinux/hooks.c:selinux_secctx_to_secid
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
**Symbols:**

```
ffffffff814ef680-ffffffff814ef698: security_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff815499f3)
Location: security/selinux/ss/services.c:1605
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_context_str_to_sid
Direct callers:
  - security/selinux/hooks.c:selinux_secctx_to_secid
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
**Symbols:**

```
ffffffff815499b0-ffffffff815499c8: security_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff815e2734)
Location: security/selinux/ss/services.c:1603
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_context_str_to_sid
Direct callers:
  - security/selinux/hooks.c:selinux_secctx_to_secid
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
**Symbols:**

```
ffffffff815e26e0-ffffffff815e270a: security_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816914d4)
Location: security/selinux/ss/services.c:1597
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_context_str_to_sid
Direct callers:
  - security/selinux/hooks.c:selinux_secctx_to_secid
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
**Symbols:**

```
ffffffff81691470-ffffffff8169149a: security_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid(const char *scontext, u32 scontext_len, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816c9a6c)
Location: security/selinux/ss/services.c:1580
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_context_str_to_sid
Direct callers:
  - security/selinux/hooks.c:selinux_secctx_to_secid
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
**Symbols:**

```
ffffffff816c9a10-ffffffff816c9a3a: security_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid(const char *scontext, u32 scontext_len, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8170667c)
Location: security/selinux/ss/services.c:1591
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_context_str_to_sid
Direct callers:
  - security/selinux/hooks.c:selinux_secctx_to_secid
  - security/selinux/hooks.c:selinux_lsm_setattr
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
**Symbols:**

```
ffffffff81706620-ffffffff8170664a: security_context_to_sid (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff8000105655b8)
Location: security/selinux/ss/services.c:1526
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_context_str_to_sid
Direct callers:
  - security/selinux/hooks.c:selinux_secctx_to_secid
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
**Symbols:**

```
ffff800010565520-ffff800010565588: security_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0719edc)
Location: security/selinux/ss/services.c:1526
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_context_str_to_sid
Direct callers:
  - security/selinux/hooks.c:selinux_secctx_to_secid
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
**Symbols:**

```
c0719e78-c0719eac: security_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c7e80)
Location: security/selinux/ss/services.c:1526
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_context_str_to_sid
Direct callers:
  - security/selinux/hooks.c:selinux_secctx_to_secid
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
**Symbols:**

```
c0000000006c7e00-c0000000006c7e3c: security_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bbab6)
Location: security/selinux/ss/services.c:1526
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_context_str_to_sid
Direct callers:
  - security/selinux/hooks.c:selinux_secctx_to_secid
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
**Symbols:**

```
ffffffe0003bba36-ffffffe0003bba8a: security_context_to_sid (STB_GLOBAL)
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
int security_context_to_sid(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146e3a7)
Location: security/selinux/ss/services.c:1526
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_context_str_to_sid
Direct callers:
  - security/selinux/hooks.c:selinux_secctx_to_secid
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
**Symbols:**

```
ffffffff8146e340-ffffffff8146e36a: security_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145edd7)
Location: security/selinux/ss/services.c:1526
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_context_str_to_sid
Direct callers:
  - security/selinux/hooks.c:selinux_secctx_to_secid
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
**Symbols:**

```
ffffffff8145ed70-ffffffff8145ed9a: security_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146a447)
Location: security/selinux/ss/services.c:1526
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_context_str_to_sid
Direct callers:
  - security/selinux/hooks.c:selinux_secctx_to_secid
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
**Symbols:**

```
ffffffff8146a3e0-ffffffff8146a40a: security_context_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int security_context_to_sid(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81481be7)
Location: security/selinux/ss/services.c:1526
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_context_str_to_sid
Direct callers:
  - security/selinux/hooks.c:selinux_secctx_to_secid
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_setsecurity
  - security/selinux/hooks.c:selinux_inode_setxattr
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_alloc_user
```
**Symbols:**

```
ffffffff81481b80-ffffffff81481baa: security_context_to_sid (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct selinux_state *state</code>
</li>
<li>
<b>Param reordered. </b>
<code>scontext, scontext_len, sid, gfp</code> ➡️ <code>state, scontext, scontext_len, sid, gfp</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_state *state</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, scontext, scontext_len, sid, gfp</code> ➡️ <code>scontext, scontext_len, sid, gfp</code>
</li>
</ul>
</details>
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
