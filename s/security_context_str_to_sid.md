# Function: <code>security_context_str_to_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_context_str_to_sid(const char *scontext, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81358470)
Location: security/selinux/ss/services.c:1476
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
ffffffff81358470-ffffffff813584a8: security_context_str_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_context_str_to_sid(const char *scontext, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138e3c0)
Location: security/selinux/ss/services.c:1470
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff8138e3c0-ffffffff8138e3f8: security_context_str_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_context_str_to_sid(const char *scontext, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a4fe0)
Location: security/selinux/ss/services.c:1470
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff813a4fe0-ffffffff813a5018: security_context_str_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_context_str_to_sid(const char *scontext, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bb990)
Location: security/selinux/ss/services.c:1482
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff813bb990-ffffffff813bb9c8: security_context_str_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_context_str_to_sid(const char *scontext, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e1b00)
Location: security/selinux/ss/services.c:1485
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff813e1b00-ffffffff813e1b38: security_context_str_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_context_str_to_sid(struct selinux_state *state, const char *scontext, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81412140)
Location: security/selinux/ss/services.c:1531
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff81412140-ffffffff8141218d: security_context_str_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_context_str_to_sid(struct selinux_state *state, const char *scontext, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142e660)
Location: security/selinux/ss/services.c:1524
Inline: False
Direct callers:
  - security/selinux/hooks.c:parse_sid
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff8142e660-ffffffff8142e6ad: security_context_str_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_context_str_to_sid(struct selinux_state *state, const char *scontext, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145bfe0)
Location: security/selinux/ss/services.c:1534
Inline: False
Direct callers:
  - security/selinux/hooks.c:parse_sid
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff8145bfe0-ffffffff8145c02e: security_context_str_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_context_str_to_sid(struct selinux_state *state, const char *scontext, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81475d90)
Location: security/selinux/ss/services.c:1534
Inline: False
Direct callers:
  - security/selinux/hooks.c:parse_sid
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff81475d90-ffffffff81475dde: security_context_str_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_context_str_to_sid(struct selinux_state *state, const char *scontext, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814cb560)
Location: security/selinux/ss/services.c:1577
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff814cb560-ffffffff814cb5a9: security_context_str_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_context_str_to_sid(struct selinux_state *state, const char *scontext, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e8d70)
Location: security/selinux/ss/services.c:1596
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff814e8d70-ffffffff814e8db9: security_context_str_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_context_str_to_sid(struct selinux_state *state, const char *scontext, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814ef6a0)
Location: security/selinux/ss/services.c:1608
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_mnt_opts_compat
  - security/selinux/hooks.c:selinux_sb_mnt_opts_compat
  - security/selinux/hooks.c:selinux_sb_mnt_opts_compat
  - security/selinux/hooks.c:selinux_sb_mnt_opts_compat
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff814ef6a0-ffffffff814ef6e8: security_context_str_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_context_str_to_sid(struct selinux_state *state, const char *scontext, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff815499d0)
Location: security/selinux/ss/services.c:1613
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_remount
  - security/selinux/hooks.c:selinux_sb_mnt_opts_compat
  - security/selinux/hooks.c:selinux_sb_mnt_opts_compat
  - security/selinux/hooks.c:selinux_sb_mnt_opts_compat
  - security/selinux/hooks.c:selinux_sb_mnt_opts_compat
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/hooks.c:selinux_set_mnt_opts
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff815499d0-ffffffff81549a18: security_context_str_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_context_str_to_sid(struct selinux_state *state, const char *scontext, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff815e2710)
Location: security/selinux/ss/services.c:1611
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_add_opt
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff815e2710-ffffffff815e276b: security_context_str_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_context_str_to_sid(struct selinux_state *state, const char *scontext, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816914b0)
Location: security/selinux/ss/services.c:1605
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_add_opt
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff816914b0-ffffffff8169150b: security_context_str_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_context_str_to_sid(const char *scontext, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816c9a50)
Location: security/selinux/ss/services.c:1587
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_add_opt
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff816c9a50-ffffffff816c9a9a: security_context_str_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_context_str_to_sid(const char *scontext, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81706660)
Location: security/selinux/ss/services.c:1598
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_add_opt
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff81706660-ffffffff817066aa: security_context_str_to_sid (STB_GLOBAL)
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
int security_context_str_to_sid(struct selinux_state *state, const char *scontext, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010565588)
Location: security/selinux/ss/services.c:1534
Inline: False
Direct callers:
  - security/selinux/hooks.c:parse_sid
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffff800010565588-ffff8000105655ec: security_context_str_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_context_str_to_sid(struct selinux_state *state, const char *scontext, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0719eac)
Location: security/selinux/ss/services.c:1534
Inline: False
Direct callers:
  - security/selinux/hooks.c:parse_sid
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
c0719eac-c0719f04: security_context_str_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_context_str_to_sid(struct selinux_state *state, const char *scontext, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c7e40)
Location: security/selinux/ss/services.c:1534
Inline: False
Direct callers:
  - security/selinux/hooks.c:parse_sid
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
c0000000006c7e40-c0000000006c7ebc: security_context_str_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_context_str_to_sid(struct selinux_state *state, const char *scontext, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bba8a)
Location: security/selinux/ss/services.c:1534
Inline: False
Direct callers:
  - security/selinux/hooks.c:parse_sid
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffe0003bba8a-ffffffe0003bbae4: security_context_str_to_sid (STB_GLOBAL)
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
int security_context_str_to_sid(struct selinux_state *state, const char *scontext, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146e370)
Location: security/selinux/ss/services.c:1534
Inline: False
Direct callers:
  - security/selinux/hooks.c:parse_sid
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff8146e370-ffffffff8146e3be: security_context_str_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_context_str_to_sid(struct selinux_state *state, const char *scontext, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145eda0)
Location: security/selinux/ss/services.c:1534
Inline: False
Direct callers:
  - security/selinux/hooks.c:parse_sid
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff8145eda0-ffffffff8145edee: security_context_str_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_context_str_to_sid(struct selinux_state *state, const char *scontext, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146a410)
Location: security/selinux/ss/services.c:1534
Inline: False
Direct callers:
  - security/selinux/hooks.c:parse_sid
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff8146a410-ffffffff8146a45e: security_context_str_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_context_str_to_sid(struct selinux_state *state, const char *scontext, u32 *sid, gfp_t gfp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81481bb0)
Location: security/selinux/ss/services.c:1534
Inline: False
Direct callers:
  - security/selinux/hooks.c:parse_sid
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_member
  - security/selinux/selinuxfs.c:sel_write_user
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_relabel
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_create
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_access
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff81481bb0-ffffffff81481bfe: security_context_str_to_sid (STB_GLOBAL)
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
<code>scontext, sid, gfp</code> ➡️ <code>state, scontext, sid, gfp</code>
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
<code>state, scontext, sid, gfp</code> ➡️ <code>scontext, sid, gfp</code>
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
