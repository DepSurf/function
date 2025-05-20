# Function: <code>security_sid_to_context_inval</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_sid_to_context_inval(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145bf80)
Location: security/selinux/ss/services.c:1364
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
```
**Symbols:**

```
ffffffff8145bf80-ffffffff8145bfac: security_sid_to_context_inval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_sid_to_context_inval(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81475d30)
Location: security/selinux/ss/services.c:1364
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
```
**Symbols:**

```
ffffffff81475d30-ffffffff81475d5c: security_sid_to_context_inval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_sid_to_context_inval(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814cb520)
Location: security/selinux/ss/services.c:1405
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
```
**Symbols:**

```
ffffffff814cb520-ffffffff814cb53c: security_sid_to_context_inval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_sid_to_context_inval(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e8d30)
Location: security/selinux/ss/services.c:1422
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
```
**Symbols:**

```
ffffffff814e8d30-ffffffff814e8d4c: security_sid_to_context_inval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_sid_to_context_inval(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814ef660)
Location: security/selinux/ss/services.c:1424
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
```
**Symbols:**

```
ffffffff814ef660-ffffffff814ef67c: security_sid_to_context_inval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_sid_to_context_inval(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81549990)
Location: security/selinux/ss/services.c:1428
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
```
**Symbols:**

```
ffffffff81549990-ffffffff815499ac: security_sid_to_context_inval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_sid_to_context_inval(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff815e26b0)
Location: security/selinux/ss/services.c:1426
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
```
**Symbols:**

```
ffffffff815e26b0-ffffffff815e26de: security_sid_to_context_inval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_sid_to_context_inval(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81691430)
Location: security/selinux/ss/services.c:1420
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
```
**Symbols:**

```
ffffffff81691430-ffffffff8169145e: security_sid_to_context_inval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_sid_to_context_inval(u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816c99d0)
Location: security/selinux/ss/services.c:1405
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
```
**Symbols:**

```
ffffffff816c99d0-ffffffff816c99fa: security_sid_to_context_inval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_sid_to_context_inval(u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff817065e0)
Location: security/selinux/ss/services.c:1416
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
```
**Symbols:**

```
ffffffff817065e0-ffffffff8170660a: security_sid_to_context_inval (STB_GLOBAL)
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
int security_sid_to_context_inval(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff8000105654c8)
Location: security/selinux/ss/services.c:1364
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
```
**Symbols:**

```
ffff8000105654c8-ffff800010565520: security_sid_to_context_inval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_sid_to_context_inval(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0719e48)
Location: security/selinux/ss/services.c:1364
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
```
**Symbols:**

```
c0719e48-c0719e78: security_sid_to_context_inval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_sid_to_context_inval(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c7dc0)
Location: security/selinux/ss/services.c:1364
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
```
**Symbols:**

```
c0000000006c7dc0-c0000000006c7df4: security_sid_to_context_inval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_sid_to_context_inval(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bb9ea)
Location: security/selinux/ss/services.c:1364
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
```
**Symbols:**

```
ffffffe0003bb9ea-ffffffe0003bba36: security_sid_to_context_inval (STB_GLOBAL)
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
int security_sid_to_context_inval(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146e310)
Location: security/selinux/ss/services.c:1364
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
```
**Symbols:**

```
ffffffff8146e310-ffffffff8146e33c: security_sid_to_context_inval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_sid_to_context_inval(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145ed40)
Location: security/selinux/ss/services.c:1364
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
```
**Symbols:**

```
ffffffff8145ed40-ffffffff8145ed6c: security_sid_to_context_inval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_sid_to_context_inval(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146a3b0)
Location: security/selinux/ss/services.c:1364
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
```
**Symbols:**

```
ffffffff8146a3b0-ffffffff8146a3dc: security_sid_to_context_inval (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_sid_to_context_inval(struct selinux_state *state, u32 sid, char **scontext, u32 *scontext_len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81481b50)
Location: security/selinux/ss/services.c:1364
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_audit_post_callback
  - security/selinux/avc.c:avc_audit_post_callback
```
**Symbols:**

```
ffffffff81481b50-ffffffff81481b7c: security_sid_to_context_inval (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
