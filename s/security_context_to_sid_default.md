# Function: <code>security_context_to_sid_default</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_context_to_sid_default(const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813584b0)
Location: security/selinux/ss/services.c:1499
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff813584b0-ffffffff813584c6: security_context_to_sid_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_context_to_sid_default(const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138e400)
Location: security/selinux/ss/services.c:1493
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff8138e400-ffffffff8138e416: security_context_to_sid_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_context_to_sid_default(const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a5020)
Location: security/selinux/ss/services.c:1493
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff813a5020-ffffffff813a5036: security_context_to_sid_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_context_to_sid_default(const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bb9d0)
Location: security/selinux/ss/services.c:1505
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff813bb9d0-ffffffff813bb9e6: security_context_to_sid_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_context_to_sid_default(const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e1b40)
Location: security/selinux/ss/services.c:1508
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff813e1b40-ffffffff813e1b56: security_context_to_sid_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_context_to_sid_default(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81412190)
Location: security/selinux/ss/services.c:1556
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff81412190-ffffffff814121ba: security_context_to_sid_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_context_to_sid_default(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142e6b0)
Location: security/selinux/ss/services.c:1549
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_with_dentry
```
**Symbols:**

```
ffffffff8142e6b0-ffffffff8142e6da: security_context_to_sid_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_context_to_sid_default(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145c030)
Location: security/selinux/ss/services.c:1559
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_use_xattr
```
**Symbols:**

```
ffffffff8145c030-ffffffff8145c05a: security_context_to_sid_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_context_to_sid_default(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81475de0)
Location: security/selinux/ss/services.c:1559
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_use_xattr
```
**Symbols:**

```
ffffffff81475de0-ffffffff81475e0a: security_context_to_sid_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_context_to_sid_default(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814cb5b0)
Location: security/selinux/ss/services.c:1602
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_use_xattr
```
**Symbols:**

```
ffffffff814cb5b0-ffffffff814cb5c2: security_context_to_sid_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_context_to_sid_default(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e8dc0)
Location: security/selinux/ss/services.c:1621
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_use_xattr
```
**Symbols:**

```
ffffffff814e8dc0-ffffffff814e8dd2: security_context_to_sid_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_context_to_sid_default(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814ef6f0)
Location: security/selinux/ss/services.c:1633
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_use_xattr
```
**Symbols:**

```
ffffffff814ef6f0-ffffffff814ef702: security_context_to_sid_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_context_to_sid_default(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81549a20)
Location: security/selinux/ss/services.c:1639
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_use_xattr
```
**Symbols:**

```
ffffffff81549a20-ffffffff81549a32: security_context_to_sid_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_context_to_sid_default(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff815e2770)
Location: security/selinux/ss/services.c:1638
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_use_xattr
```
**Symbols:**

```
ffffffff815e2770-ffffffff815e2794: security_context_to_sid_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_context_to_sid_default(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81691520)
Location: security/selinux/ss/services.c:1632
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_use_xattr
```
**Symbols:**

```
ffffffff81691520-ffffffff81691544: security_context_to_sid_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_context_to_sid_default(const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816c9ab0)
Location: security/selinux/ss/services.c:1612
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_use_xattr
```
**Symbols:**

```
ffffffff816c9ab0-ffffffff816c9ad8: security_context_to_sid_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_context_to_sid_default(const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff817066c0)
Location: security/selinux/ss/services.c:1623
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_use_xattr
```
**Symbols:**

```
ffffffff817066c0-ffffffff817066e8: security_context_to_sid_default (STB_GLOBAL)
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
int security_context_to_sid_default(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff8000105655f0)
Location: security/selinux/ss/services.c:1559
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_use_xattr
```
**Symbols:**

```
ffff8000105655f0-ffff80001056565c: security_context_to_sid_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_context_to_sid_default(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0719f04)
Location: security/selinux/ss/services.c:1559
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_use_xattr
```
**Symbols:**

```
c0719f04-c0719f40: security_context_to_sid_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_context_to_sid_default(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c7ec0)
Location: security/selinux/ss/services.c:1559
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_use_xattr
```
**Symbols:**

```
c0000000006c7ec0-c0000000006c7f00: security_context_to_sid_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_context_to_sid_default(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bbae4)
Location: security/selinux/ss/services.c:1559
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_use_xattr
```
**Symbols:**

```
ffffffe0003bbae4-ffffffe0003bbb3e: security_context_to_sid_default (STB_GLOBAL)
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
int security_context_to_sid_default(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146e3c0)
Location: security/selinux/ss/services.c:1559
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_use_xattr
```
**Symbols:**

```
ffffffff8146e3c0-ffffffff8146e3ea: security_context_to_sid_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_context_to_sid_default(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145edf0)
Location: security/selinux/ss/services.c:1559
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_use_xattr
```
**Symbols:**

```
ffffffff8145edf0-ffffffff8145ee1a: security_context_to_sid_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_context_to_sid_default(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146a460)
Location: security/selinux/ss/services.c:1559
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_use_xattr
```
**Symbols:**

```
ffffffff8146a460-ffffffff8146a48a: security_context_to_sid_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_context_to_sid_default(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid, u32 def_sid, gfp_t gfp_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81481c00)
Location: security/selinux/ss/services.c:1559
Inline: False
Direct callers:
  - security/selinux/hooks.c:inode_doinit_use_xattr
```
**Symbols:**

```
ffffffff81481c00-ffffffff81481c2a: security_context_to_sid_default (STB_GLOBAL)
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
<code>scontext, scontext_len, sid, def_sid, gfp_flags</code> ➡️ <code>state, scontext, scontext_len, sid, def_sid, gfp_flags</code>
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
<code>state, scontext, scontext_len, sid, def_sid, gfp_flags</code> ➡️ <code>scontext, scontext_len, sid, def_sid, gfp_flags</code>
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
