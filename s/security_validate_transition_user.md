# Function: <code>security_validate_transition_user</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_validate_transition_user(u32 oldsid, u32 newsid, u32 tasksid, u16 tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138d7a0)
Location: security/selinux/ss/services.c:827
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff8138d7a0-ffffffff8138d7c4: security_validate_transition_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_validate_transition_user(u32 oldsid, u32 newsid, u32 tasksid, u16 tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a43b0)
Location: security/selinux/ss/services.c:827
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff813a43b0-ffffffff813a43d4: security_validate_transition_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_validate_transition_user(u32 oldsid, u32 newsid, u32 tasksid, u16 tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bada0)
Location: security/selinux/ss/services.c:839
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff813bada0-ffffffff813badc5: security_validate_transition_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_validate_transition_user(u32 oldsid, u32 newsid, u32 tasksid, u16 tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e0f00)
Location: security/selinux/ss/services.c:841
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff813e0f00-ffffffff813e0f25: security_validate_transition_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_validate_transition_user(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81411570)
Location: security/selinux/ss/services.c:840
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff81411570-ffffffff81411593: security_validate_transition_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_validate_transition_user(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142da60)
Location: security/selinux/ss/services.c:837
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff8142da60-ffffffff8142da83: security_validate_transition_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_validate_transition_user(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145b340)
Location: security/selinux/ss/services.c:828
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff8145b340-ffffffff8145b363: security_validate_transition_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_validate_transition_user(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814750f0)
Location: security/selinux/ss/services.c:828
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff814750f0-ffffffff81475113: security_validate_transition_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_validate_transition_user(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814ca940)
Location: security/selinux/ss/services.c:835
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff814ca940-ffffffff814ca967: security_validate_transition_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_validate_transition_user(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e8260)
Location: security/selinux/ss/services.c:838
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff814e8260-ffffffff814e8287: security_validate_transition_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_validate_transition_user(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814eea60)
Location: security/selinux/ss/services.c:840
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff814eea60-ffffffff814eea87: security_validate_transition_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_validate_transition_user(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass);
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
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff81cd4d49-ffffffff81cd4d71: security_validate_transition_user.cold (STB_LOCAL)
ffffffff81548f20-ffffffff81548f6c: security_validate_transition_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int security_validate_transition_user(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:838
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff81e87c5d-ffffffff81e87c86: security_validate_transition_user.cold (STB_LOCAL)
ffffffff815e19c0-ffffffff815e1a21: security_validate_transition_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int security_validate_transition_user(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:832
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff82073c78-ffffffff82073ca1: security_validate_transition_user.cold (STB_LOCAL)
ffffffff816905c0-ffffffff81690621: security_validate_transition_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int security_validate_transition_user(u32 oldsid, u32 newsid, u32 tasksid, u16 tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:829
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff820f3851-ffffffff820f3872: security_validate_transition_user.cold (STB_LOCAL)
ffffffff816c8a80-ffffffff816c8ade: security_validate_transition_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int security_validate_transition_user(u32 oldsid, u32 newsid, u32 tasksid, u16 tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:829
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff821d0a17-ffffffff821d0a38: security_validate_transition_user.cold (STB_LOCAL)
ffffffff81705690-ffffffff817056ee: security_validate_transition_user (STB_GLOBAL)
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
int security_validate_transition_user(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010564500)
Location: security/selinux/ss/services.c:828
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffff800010564500-ffff800010564580: security_validate_transition_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_validate_transition_user(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c07190e4)
Location: security/selinux/ss/services.c:828
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
c07190e4-c0719128: security_validate_transition_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_validate_transition_user(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c6c00)
Location: security/selinux/ss/services.c:828
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
c0000000006c6c00-c0000000006c6c38: security_validate_transition_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_validate_transition_user(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bae24)
Location: security/selinux/ss/services.c:828
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffe0003bae24-ffffffe0003bae78: security_validate_transition_user (STB_GLOBAL)
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
int security_validate_transition_user(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146d6d0)
Location: security/selinux/ss/services.c:828
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff8146d6d0-ffffffff8146d6f3: security_validate_transition_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_validate_transition_user(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145e100)
Location: security/selinux/ss/services.c:828
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff8145e100-ffffffff8145e123: security_validate_transition_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_validate_transition_user(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81469770)
Location: security/selinux/ss/services.c:828
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff81469770-ffffffff81469793: security_validate_transition_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_validate_transition_user(struct selinux_state *state, u32 oldsid, u32 newsid, u32 tasksid, u16 tclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81480f30)
Location: security/selinux/ss/services.c:828
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_validatetrans
```
**Symbols:**

```
ffffffff81480f30-ffffffff81480f53: security_validate_transition_user (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>oldsid, newsid, tasksid, tclass</code> ➡️ <code>state, oldsid, newsid, tasksid, tclass</code>
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
<code>state, oldsid, newsid, tasksid, tclass</code> ➡️ <code>oldsid, newsid, tasksid, tclass</code>
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
