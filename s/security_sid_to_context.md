# Function: <code>security_sid_to_context</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_sid_to_context(u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81358410)
Location: security/selinux/ss/services.c:1302
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_key_getsecurity
  - security/selinux/hooks.c:selinux_secid_to_secctx
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
```
**Symbols:**

```
ffffffff81358410-ffffffff81358422: security_sid_to_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_sid_to_context(u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138e360)
Location: security/selinux/ss/services.c:1296
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_key_getsecurity
  - security/selinux/hooks.c:selinux_secid_to_secctx
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
```
**Symbols:**

```
ffffffff8138e360-ffffffff8138e372: security_sid_to_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_sid_to_context(u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a4f80)
Location: security/selinux/ss/services.c:1296
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_key_getsecurity
  - security/selinux/hooks.c:selinux_secid_to_secctx
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
```
**Symbols:**

```
ffffffff813a4f80-ffffffff813a4f92: security_sid_to_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_sid_to_context(u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bb930)
Location: security/selinux/ss/services.c:1308
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_key_getsecurity
  - security/selinux/hooks.c:selinux_secid_to_secctx
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
```
**Symbols:**

```
ffffffff813bb930-ffffffff813bb942: security_sid_to_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_sid_to_context(u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e1aa0)
Location: security/selinux/ss/services.c:1313
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_key_getsecurity
  - security/selinux/hooks.c:selinux_secid_to_secctx
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
```
**Symbols:**

```
ffffffff813e1aa0-ffffffff813e1ab2: security_sid_to_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_sid_to_context(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814120b0)
Location: security/selinux/ss/services.c:1350
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_key_getsecurity
  - security/selinux/hooks.c:selinux_secid_to_secctx
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/hooks.c:selinux_sb_show_options
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
```
**Symbols:**

```
ffffffff814120b0-ffffffff814120d5: security_sid_to_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_sid_to_context(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142e5d0)
Location: security/selinux/ss/services.c:1347
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_key_getsecurity
  - security/selinux/hooks.c:selinux_secid_to_secctx
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:show_sid
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
```
**Symbols:**

```
ffffffff8142e5d0-ffffffff8142e5f5: security_sid_to_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_sid_to_context(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145bf20)
Location: security/selinux/ss/services.c:1337
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_key_getsecurity
  - security/selinux/hooks.c:selinux_secid_to_secctx
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:show_sid
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
```
**Symbols:**

```
ffffffff8145bf20-ffffffff8145bf49: security_sid_to_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_sid_to_context(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81475cd0)
Location: security/selinux/ss/services.c:1337
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_key_getsecurity
  - security/selinux/hooks.c:selinux_secid_to_secctx
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:show_sid
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
```
**Symbols:**

```
ffffffff81475cd0-ffffffff81475cf9: security_sid_to_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_sid_to_context(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814cb4e0)
Location: security/selinux/ss/services.c:1378
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_key_getsecurity
  - security/selinux/hooks.c:selinux_secid_to_secctx
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:show_sid
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
```
**Symbols:**

```
ffffffff814cb4e0-ffffffff814cb4f6: security_sid_to_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_sid_to_context(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e8cf0)
Location: security/selinux/ss/services.c:1395
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_key_getsecurity
  - security/selinux/hooks.c:selinux_secid_to_secctx
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:show_sid
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
```
**Symbols:**

```
ffffffff814e8cf0-ffffffff814e8d06: security_sid_to_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_sid_to_context(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814ef620)
Location: security/selinux/ss/services.c:1397
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_key_getsecurity
  - security/selinux/hooks.c:selinux_secid_to_secctx
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:show_sid
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
```
**Symbols:**

```
ffffffff814ef620-ffffffff814ef636: security_sid_to_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_sid_to_context(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81549950)
Location: security/selinux/ss/services.c:1400
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_key_getsecurity
  - security/selinux/hooks.c:selinux_secid_to_secctx
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:show_sid
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
```
**Symbols:**

```
ffffffff81549950-ffffffff81549966: security_sid_to_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_sid_to_context(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff815e2650)
Location: security/selinux/ss/services.c:1398
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_key_getsecurity
  - security/selinux/hooks.c:selinux_secid_to_secctx
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:show_sid
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
```
**Symbols:**

```
ffffffff815e2650-ffffffff815e2678: security_sid_to_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_sid_to_context(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816913b0)
Location: security/selinux/ss/services.c:1392
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_key_getsecurity
  - security/selinux/hooks.c:selinux_secid_to_secctx
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:show_sid
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
```
**Symbols:**

```
ffffffff816913b0-ffffffff816913d8: security_sid_to_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_sid_to_context(u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816c9950)
Location: security/selinux/ss/services.c:1379
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_key_getsecurity
  - security/selinux/hooks.c:selinux_secid_to_secctx
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:show_sid
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
```
**Symbols:**

```
ffffffff816c9950-ffffffff816c9974: security_sid_to_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_sid_to_context(u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81706560)
Location: security/selinux/ss/services.c:1390
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_key_getsecurity
  - security/selinux/hooks.c:selinux_lsmblob_to_secctx
  - security/selinux/hooks.c:selinux_lsmblob_to_secctx
  - security/selinux/hooks.c:selinux_lsm_getattr
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:show_sid
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
```
**Symbols:**

```
ffffffff81706560-ffffffff81706584: security_sid_to_context (STB_GLOBAL)
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
int security_sid_to_context(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010565418)
Location: security/selinux/ss/services.c:1337
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_key_getsecurity
  - security/selinux/hooks.c:selinux_secid_to_secctx
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:show_sid
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
```
**Symbols:**

```
ffff800010565418-ffff800010565470: security_sid_to_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_sid_to_context(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0719de8)
Location: security/selinux/ss/services.c:1337
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_key_getsecurity
  - security/selinux/hooks.c:selinux_secid_to_secctx
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:show_sid
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
```
**Symbols:**

```
c0719de8-c0719e18: security_sid_to_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_sid_to_context(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c7d40)
Location: security/selinux/ss/services.c:1337
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_key_getsecurity
  - security/selinux/hooks.c:selinux_secid_to_secctx
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:show_sid
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
```
**Symbols:**

```
c0000000006c7d40-c0000000006c7d74: security_sid_to_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_sid_to_context(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bb952)
Location: security/selinux/ss/services.c:1337
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_key_getsecurity
  - security/selinux/hooks.c:selinux_secid_to_secctx
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:show_sid
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
```
**Symbols:**

```
ffffffe0003bb952-ffffffe0003bb99e: security_sid_to_context (STB_GLOBAL)
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
int security_sid_to_context(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146e2b0)
Location: security/selinux/ss/services.c:1337
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_key_getsecurity
  - security/selinux/hooks.c:selinux_secid_to_secctx
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:show_sid
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
```
**Symbols:**

```
ffffffff8146e2b0-ffffffff8146e2d9: security_sid_to_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_sid_to_context(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145ece0)
Location: security/selinux/ss/services.c:1337
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_key_getsecurity
  - security/selinux/hooks.c:selinux_secid_to_secctx
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:show_sid
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
```
**Symbols:**

```
ffffffff8145ece0-ffffffff8145ed09: security_sid_to_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_sid_to_context(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146a350)
Location: security/selinux/ss/services.c:1337
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_key_getsecurity
  - security/selinux/hooks.c:selinux_secid_to_secctx
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:show_sid
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
```
**Symbols:**

```
ffffffff8146a350-ffffffff8146a379: security_sid_to_context (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_sid_to_context(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81481af0)
Location: security/selinux/ss/services.c:1337
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/hooks.c:selinux_key_getsecurity
  - security/selinux/hooks.c:selinux_secid_to_secctx
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_socket_getpeersec_stream
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_dentry_init_security
  - security/selinux/hooks.c:show_sid
  - security/selinux/selinuxfs.c:sel_read_initcon
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_context
  - security/selinux/xfrm.c:selinux_xfrm_state_alloc_acquire
```
**Symbols:**

```
ffffffff81481af0-ffffffff81481b19: security_sid_to_context (STB_GLOBAL)
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
<code>sid, scontext, scontext_len</code> ➡️ <code>state, sid, scontext, scontext_len</code>
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
<code>state, sid, scontext, scontext_len</code> ➡️ <code>sid, scontext, scontext_len</code>
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
