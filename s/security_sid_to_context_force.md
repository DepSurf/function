# Function: <code>security_sid_to_context_force</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_sid_to_context_force(u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81358430)
Location: security/selinux/ss/services.c:1307
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_init_security
  - security/selinux/hooks.c:selinux_inode_getsecurity
```
**Symbols:**

```
ffffffff81358430-ffffffff81358445: security_sid_to_context_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_sid_to_context_force(u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138e380)
Location: security/selinux/ss/services.c:1301
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_init_security
```
**Symbols:**

```
ffffffff8138e380-ffffffff8138e395: security_sid_to_context_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_sid_to_context_force(u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a4fa0)
Location: security/selinux/ss/services.c:1301
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_init_security
```
**Symbols:**

```
ffffffff813a4fa0-ffffffff813a4fb5: security_sid_to_context_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_sid_to_context_force(u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bb950)
Location: security/selinux/ss/services.c:1313
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_init_security
```
**Symbols:**

```
ffffffff813bb950-ffffffff813bb965: security_sid_to_context_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_sid_to_context_force(u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e1ac0)
Location: security/selinux/ss/services.c:1318
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_init_security
```
**Symbols:**

```
ffffffff813e1ac0-ffffffff813e1ad5: security_sid_to_context_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_sid_to_context_force(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814120e0)
Location: security/selinux/ss/services.c:1357
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_init_security
```
**Symbols:**

```
ffffffff814120e0-ffffffff81412108: security_sid_to_context_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_sid_to_context_force(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142e600)
Location: security/selinux/ss/services.c:1354
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_init_security
```
**Symbols:**

```
ffffffff8142e600-ffffffff8142e628: security_sid_to_context_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_sid_to_context_force(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145bf50)
Location: security/selinux/ss/services.c:1344
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_init_security
```
**Symbols:**

```
ffffffff8145bf50-ffffffff8145bf7c: security_sid_to_context_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_sid_to_context_force(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81475d00)
Location: security/selinux/ss/services.c:1344
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_init_security
```
**Symbols:**

```
ffffffff81475d00-ffffffff81475d2c: security_sid_to_context_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_sid_to_context_force(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814cb500)
Location: security/selinux/ss/services.c:1385
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_init_security
```
**Symbols:**

```
ffffffff814cb500-ffffffff814cb519: security_sid_to_context_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_sid_to_context_force(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e8d10)
Location: security/selinux/ss/services.c:1402
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_init_security
```
**Symbols:**

```
ffffffff814e8d10-ffffffff814e8d29: security_sid_to_context_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_sid_to_context_force(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814ef640)
Location: security/selinux/ss/services.c:1404
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_init_security
```
**Symbols:**

```
ffffffff814ef640-ffffffff814ef659: security_sid_to_context_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_sid_to_context_force(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81549970)
Location: security/selinux/ss/services.c:1407
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_init_security
```
**Symbols:**

```
ffffffff81549970-ffffffff81549989: security_sid_to_context_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_sid_to_context_force(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff815e2680)
Location: security/selinux/ss/services.c:1405
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_init_security
```
**Symbols:**

```
ffffffff815e2680-ffffffff815e26ab: security_sid_to_context_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_sid_to_context_force(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816913f0)
Location: security/selinux/ss/services.c:1399
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_init_security
```
**Symbols:**

```
ffffffff816913f0-ffffffff8169141b: security_sid_to_context_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_sid_to_context_force(u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816c9990)
Location: security/selinux/ss/services.c:1385
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_init_security
```
**Symbols:**

```
ffffffff816c9990-ffffffff816c99b7: security_sid_to_context_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_sid_to_context_force(u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff817065a0)
Location: security/selinux/ss/services.c:1396
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_init_security
```
**Symbols:**

```
ffffffff817065a0-ffffffff817065c7: security_sid_to_context_force (STB_GLOBAL)
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
int security_sid_to_context_force(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010565470)
Location: security/selinux/ss/services.c:1344
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_init_security
```
**Symbols:**

```
ffff800010565470-ffff8000105654c8: security_sid_to_context_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_sid_to_context_force(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0719e18)
Location: security/selinux/ss/services.c:1344
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_init_security
```
**Symbols:**

```
c0719e18-c0719e48: security_sid_to_context_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_sid_to_context_force(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c7d80)
Location: security/selinux/ss/services.c:1344
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_init_security
```
**Symbols:**

```
c0000000006c7d80-c0000000006c7db4: security_sid_to_context_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_sid_to_context_force(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bb99e)
Location: security/selinux/ss/services.c:1344
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_init_security
```
**Symbols:**

```
ffffffe0003bb99e-ffffffe0003bb9ea: security_sid_to_context_force (STB_GLOBAL)
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
int security_sid_to_context_force(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146e2e0)
Location: security/selinux/ss/services.c:1344
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_init_security
```
**Symbols:**

```
ffffffff8146e2e0-ffffffff8146e30c: security_sid_to_context_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_sid_to_context_force(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145ed10)
Location: security/selinux/ss/services.c:1344
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_init_security
```
**Symbols:**

```
ffffffff8145ed10-ffffffff8145ed3c: security_sid_to_context_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_sid_to_context_force(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146a380)
Location: security/selinux/ss/services.c:1344
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_init_security
```
**Symbols:**

```
ffffffff8146a380-ffffffff8146a3ac: security_sid_to_context_force (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_sid_to_context_force(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81481b20)
Location: security/selinux/ss/services.c:1344
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_kernfs_init_security
  - security/selinux/hooks.c:selinux_inode_getsecurity
  - security/selinux/hooks.c:selinux_inode_init_security
```
**Symbols:**

```
ffffffff81481b20-ffffffff81481b4c: security_sid_to_context_force (STB_GLOBAL)
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
