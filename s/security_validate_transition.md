# Function: <code>security_validate_transition</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_validate_transition(u32 oldsid, u32 newsid, u32 tasksid, u16 orig_tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813575d0)
Location: security/selinux/ss/services.c:781
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff813575d0-ffffffff81357882: security_validate_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_validate_transition(u32 oldsid, u32 newsid, u32 tasksid, u16 orig_tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138d7d0)
Location: security/selinux/ss/services.c:834
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff8138d7d0-ffffffff8138d7f1: security_validate_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_validate_transition(u32 oldsid, u32 newsid, u32 tasksid, u16 orig_tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a43e0)
Location: security/selinux/ss/services.c:834
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff813a43e0-ffffffff813a4401: security_validate_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_validate_transition(u32 oldsid, u32 newsid, u32 tasksid, u16 orig_tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813badd0)
Location: security/selinux/ss/services.c:846
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff813badd0-ffffffff813badf2: security_validate_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_validate_transition(u32 oldsid, u32 newsid, u32 tasksid, u16 orig_tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e0f30)
Location: security/selinux/ss/services.c:848
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff813e0f30-ffffffff813e0f52: security_validate_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_validate_transition(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 orig_tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814115a0)
Location: security/selinux/ss/services.c:848
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff814115a0-ffffffff814115c0: security_validate_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_validate_transition(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 orig_tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142da90)
Location: security/selinux/ss/services.c:845
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff8142da90-ffffffff8142dab0: security_validate_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_validate_transition(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 orig_tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145b370)
Location: security/selinux/ss/services.c:836
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff8145b370-ffffffff8145b390: security_validate_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_validate_transition(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 orig_tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81475120)
Location: security/selinux/ss/services.c:836
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff81475120-ffffffff81475140: security_validate_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_validate_transition(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 orig_tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814ca970)
Location: security/selinux/ss/services.c:843
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff814ca970-ffffffff814ca994: security_validate_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_validate_transition(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 orig_tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e8290)
Location: security/selinux/ss/services.c:846
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff814e8290-ffffffff814e82b4: security_validate_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_validate_transition(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 orig_tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814eea90)
Location: security/selinux/ss/services.c:848
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff814eea90-ffffffff814eeab4: security_validate_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_validate_transition(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 orig_tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:848
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff81cd4d71-ffffffff81cd4d99: security_validate_transition.cold (STB_LOCAL)
ffffffff81548f70-ffffffff81548fb9: security_validate_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int security_validate_transition(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 orig_tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:846
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff81e87c86-ffffffff81e87caf: security_validate_transition.cold (STB_LOCAL)
ffffffff815e1a30-ffffffff815e1a8e: security_validate_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int security_validate_transition(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 orig_tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:840
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff82073ca1-ffffffff82073cca: security_validate_transition.cold (STB_LOCAL)
ffffffff81690640-ffffffff8169069e: security_validate_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int security_validate_transition(u32 oldsid, u32 newsid, u32 tasksid, u16 orig_tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:836
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff820f3872-ffffffff820f3893: security_validate_transition.cold (STB_LOCAL)
ffffffff816c8af0-ffffffff816c8b4b: security_validate_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int security_validate_transition(u32 oldsid, u32 newsid, u32 tasksid, u16 orig_tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:836
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff821d0a38-ffffffff821d0a59: security_validate_transition.cold (STB_LOCAL)
ffffffff81705700-ffffffff8170575b: security_validate_transition (STB_GLOBAL)
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
int security_validate_transition(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 orig_tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010564580)
Location: security/selinux/ss/services.c:836
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffff800010564580-ffff800010564600: security_validate_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_validate_transition(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 orig_tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0719128)
Location: security/selinux/ss/services.c:836
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
c0719128-c071916c: security_validate_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_validate_transition(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 orig_tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c6c40)
Location: security/selinux/ss/services.c:836
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
c0000000006c6c40-c0000000006c6c78: security_validate_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_validate_transition(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 orig_tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bae78)
Location: security/selinux/ss/services.c:836
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffe0003bae78-ffffffe0003baecc: security_validate_transition (STB_GLOBAL)
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
int security_validate_transition(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 orig_tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146d700)
Location: security/selinux/ss/services.c:836
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff8146d700-ffffffff8146d720: security_validate_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_validate_transition(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 orig_tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145e130)
Location: security/selinux/ss/services.c:836
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff8145e130-ffffffff8145e150: security_validate_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_validate_transition(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 orig_tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814697a0)
Location: security/selinux/ss/services.c:836
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff814697a0-ffffffff814697c0: security_validate_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_validate_transition(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 orig_tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81480f60)
Location: security/selinux/ss/services.c:836
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff81480f60-ffffffff81480f80: security_validate_transition (STB_GLOBAL)
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
<code>oldsid, newsid, tasksid, orig_tclass</code> ➡️ <code>state, oldsid, newsid, tasksid, orig_tclass</code>
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
<code>state, oldsid, newsid, tasksid, orig_tclass</code> ➡️ <code>oldsid, newsid, tasksid, orig_tclass</code>
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
