# Function: <code>security_bounded_transition</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_bounded_transition(u32 old_sid, u32 new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81357890)
Location: security/selinux/ss/services.c:856
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff81357890-ffffffff81357a18: security_bounded_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_bounded_transition(u32 old_sid, u32 new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138d800)
Location: security/selinux/ss/services.c:850
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff8138d800-ffffffff8138d988: security_bounded_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_bounded_transition(u32 old_sid, u32 new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a4410)
Location: security/selinux/ss/services.c:850
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff813a4410-ffffffff813a4598: security_bounded_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_bounded_transition(u32 old_sid, u32 new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bae00)
Location: security/selinux/ss/services.c:862
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff813bae00-ffffffff813baf88: security_bounded_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_bounded_transition(u32 old_sid, u32 new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e0f60)
Location: security/selinux/ss/services.c:864
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff813e0f60-ffffffff813e10f7: security_bounded_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int security_bounded_transition(struct selinux_state *state, u32 old_sid, u32 new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:865
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff81414be9-ffffffff81414c29: security_bounded_transition.cold.33 (STB_LOCAL)
ffffffff814115c0-ffffffff81411730: security_bounded_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int security_bounded_transition(struct selinux_state *state, u32 old_sid, u32 new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:862
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff8143119f-ffffffff814311df: security_bounded_transition.cold.33 (STB_LOCAL)
ffffffff8142dab0-ffffffff8142dc29: security_bounded_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int security_bounded_transition(struct selinux_state *state, u32 old_sid, u32 new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:853
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff8145ec36-ffffffff8145ec78: security_bounded_transition.cold (STB_LOCAL)
ffffffff8145b390-ffffffff8145b516: security_bounded_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int security_bounded_transition(struct selinux_state *state, u32 old_sid, u32 new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:853
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff814789e8-ffffffff81478a2a: security_bounded_transition.cold (STB_LOCAL)
ffffffff81475140-ffffffff814752c6: security_bounded_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int security_bounded_transition(struct selinux_state *state, u32 old_sid, u32 new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:860
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff814cde9f-ffffffff814cdee1: security_bounded_transition.cold (STB_LOCAL)
ffffffff814ca9a0-ffffffff814cab33: security_bounded_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int security_bounded_transition(struct selinux_state *state, u32 old_sid, u32 new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:863
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff81bf0f12-ffffffff81bf0f54: security_bounded_transition.cold (STB_LOCAL)
ffffffff814e82c0-ffffffff814e8421: security_bounded_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int security_bounded_transition(struct selinux_state *state, u32 old_sid, u32 new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:865
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff81be3034-ffffffff81be3076: security_bounded_transition.cold (STB_LOCAL)
ffffffff814eeac0-ffffffff814eec21: security_bounded_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_bounded_transition(struct selinux_state *state, u32 old_sid, u32 new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:866
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff81cd4d99-ffffffff81cd4df7: security_bounded_transition.cold (STB_LOCAL)
ffffffff81548fc0-ffffffff8154913c: security_bounded_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int security_bounded_transition(struct selinux_state *state, u32 old_sid, u32 new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:864
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff81e87caf-ffffffff81e87cfc: security_bounded_transition.cold (STB_LOCAL)
ffffffff815e1a90-ffffffff815e1c22: security_bounded_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int security_bounded_transition(struct selinux_state *state, u32 old_sid, u32 new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:858
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff82073cca-ffffffff82073cdf: security_bounded_transition.cold (STB_LOCAL)
ffffffff816906b0-ffffffff81690872: security_bounded_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int security_bounded_transition(u32 old_sid, u32 new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:852
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff820f3893-ffffffff820f38a8: security_bounded_transition.cold (STB_LOCAL)
ffffffff816c8b60-ffffffff816c8d24: security_bounded_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int security_bounded_transition(u32 old_sid, u32 new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:852
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_lsm_setattr
```
**Symbols:**

```
ffffffff821d0a59-ffffffff821d0a6e: security_bounded_transition.cold (STB_LOCAL)
ffffffff81705770-ffffffff81705932: security_bounded_transition (STB_GLOBAL)
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
int security_bounded_transition(struct selinux_state *state, u32 old_sid, u32 new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010564600)
Location: security/selinux/ss/services.c:853
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffff800010564600-ffff80001056480c: security_bounded_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_bounded_transition(struct selinux_state *state, u32 old_sid, u32 new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c071916c)
Location: security/selinux/ss/services.c:853
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:check_nnp_nosuid
```
**Symbols:**

```
c071916c-c0719354: security_bounded_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_bounded_transition(struct selinux_state *state, u32 old_sid, u32 new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c6c80)
Location: security/selinux/ss/services.c:853
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
c0000000006c6c80-c0000000006c6f08: security_bounded_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_bounded_transition(struct selinux_state *state, u32 old_sid, u32 new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003baecc)
Location: security/selinux/ss/services.c:853
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffe0003baecc-ffffffe0003bb030: security_bounded_transition (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int security_bounded_transition(struct selinux_state *state, u32 old_sid, u32 new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:853
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff81470fc8-ffffffff8147100a: security_bounded_transition.cold (STB_LOCAL)
ffffffff8146d720-ffffffff8146d8a6: security_bounded_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int security_bounded_transition(struct selinux_state *state, u32 old_sid, u32 new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:853
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff814619e8-ffffffff81461a2a: security_bounded_transition.cold (STB_LOCAL)
ffffffff8145e150-ffffffff8145e2d6: security_bounded_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int security_bounded_transition(struct selinux_state *state, u32 old_sid, u32 new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:853
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff8146d068-ffffffff8146d0aa: security_bounded_transition.cold (STB_LOCAL)
ffffffff814697c0-ffffffff81469946: security_bounded_transition (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int security_bounded_transition(struct selinux_state *state, u32 old_sid, u32 new_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:853
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff814848d4-ffffffff81484916: security_bounded_transition.cold (STB_LOCAL)
ffffffff81480f80-ffffffff81481100: security_bounded_transition (STB_GLOBAL)
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
<code>old_sid, new_sid</code> ➡️ <code>state, old_sid, new_sid</code>
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
<code>state, old_sid, new_sid</code> ➡️ <code>old_sid, new_sid</code>
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
