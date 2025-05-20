# Function: <code>security_context_to_sid_force</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_context_to_sid_force(const char *scontext, u32 scontext_len, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813584d0)
Location: security/selinux/ss/services.c:1506
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff813584d0-ffffffff813584ee: security_context_to_sid_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_context_to_sid_force(const char *scontext, u32 scontext_len, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138e420)
Location: security/selinux/ss/services.c:1500
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff8138e420-ffffffff8138e43e: security_context_to_sid_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_context_to_sid_force(const char *scontext, u32 scontext_len, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a5040)
Location: security/selinux/ss/services.c:1500
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff813a5040-ffffffff813a505e: security_context_to_sid_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_context_to_sid_force(const char *scontext, u32 scontext_len, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bb9f0)
Location: security/selinux/ss/services.c:1512
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff813bb9f0-ffffffff813bba0e: security_context_to_sid_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_context_to_sid_force(const char *scontext, u32 scontext_len, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e1b60)
Location: security/selinux/ss/services.c:1515
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff813e1b60-ffffffff813e1b7e: security_context_to_sid_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_context_to_sid_force(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814121c0)
Location: security/selinux/ss/services.c:1564
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff814121c0-ffffffff814121ed: security_context_to_sid_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_context_to_sid_force(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142e6e0)
Location: security/selinux/ss/services.c:1557
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff8142e6e0-ffffffff8142e70d: security_context_to_sid_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_context_to_sid_force(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145c060)
Location: security/selinux/ss/services.c:1567
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff8145c060-ffffffff8145c08d: security_context_to_sid_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_context_to_sid_force(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81475e10)
Location: security/selinux/ss/services.c:1567
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff81475e10-ffffffff81475e3d: security_context_to_sid_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_context_to_sid_force(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814cb5d0)
Location: security/selinux/ss/services.c:1610
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff814cb5d0-ffffffff814cb5eb: security_context_to_sid_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_context_to_sid_force(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e8de0)
Location: security/selinux/ss/services.c:1629
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff814e8de0-ffffffff814e8dfb: security_context_to_sid_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_context_to_sid_force(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814ef710)
Location: security/selinux/ss/services.c:1641
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff814ef710-ffffffff814ef72b: security_context_to_sid_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_context_to_sid_force(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81549a40)
Location: security/selinux/ss/services.c:1647
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff81549a40-ffffffff81549a5b: security_context_to_sid_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_context_to_sid_force(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff815e27a0)
Location: security/selinux/ss/services.c:1646
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff815e27a0-ffffffff815e27cd: security_context_to_sid_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_context_to_sid_force(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81691560)
Location: security/selinux/ss/services.c:1640
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff81691560-ffffffff8169158d: security_context_to_sid_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_context_to_sid_force(const char *scontext, u32 scontext_len, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816c9af0)
Location: security/selinux/ss/services.c:1619
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff816c9af0-ffffffff816c9b20: security_context_to_sid_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_context_to_sid_force(const char *scontext, u32 scontext_len, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81706700)
Location: security/selinux/ss/services.c:1630
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_lsm_setattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff81706700-ffffffff81706730: security_context_to_sid_force (STB_GLOBAL)
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
int security_context_to_sid_force(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010565660)
Location: security/selinux/ss/services.c:1567
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffff800010565660-ffff8000105656bc: security_context_to_sid_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_context_to_sid_force(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0719f40)
Location: security/selinux/ss/services.c:1567
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
c0719f40-c0719f78: security_context_to_sid_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_context_to_sid_force(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c7f00)
Location: security/selinux/ss/services.c:1567
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
c0000000006c7f00-c0000000006c7f38: security_context_to_sid_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_context_to_sid_force(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bbb3e)
Location: security/selinux/ss/services.c:1567
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffe0003bbb3e-ffffffe0003bbb90: security_context_to_sid_force (STB_GLOBAL)
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
int security_context_to_sid_force(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146e3f0)
Location: security/selinux/ss/services.c:1567
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff8146e3f0-ffffffff8146e41d: security_context_to_sid_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_context_to_sid_force(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145ee20)
Location: security/selinux/ss/services.c:1567
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff8145ee20-ffffffff8145ee4d: security_context_to_sid_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_context_to_sid_force(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146a490)
Location: security/selinux/ss/services.c:1567
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff8146a490-ffffffff8146a4bd: security_context_to_sid_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_context_to_sid_force(struct selinux_state *state, const char *scontext, u32 scontext_len, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81481c30)
Location: security/selinux/ss/services.c:1567
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_inode_post_setxattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff81481c30-ffffffff81481c5d: security_context_to_sid_force (STB_GLOBAL)
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
<code>scontext, scontext_len, sid</code> ➡️ <code>state, scontext, scontext_len, sid</code>
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
<code>state, scontext, scontext_len, sid</code> ➡️ <code>scontext, scontext_len, sid</code>
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
