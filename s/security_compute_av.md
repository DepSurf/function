# Function: <code>security_compute_av</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void security_compute_av(u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81358010)
Location: security/selinux/ss/services.c:1084
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_compute_av
```
**Symbols:**

```
ffffffff81358010-ffffffff813582c1: security_compute_av (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void security_compute_av(u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138df50)
Location: security/selinux/ss/services.c:1078
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_compute_av
```
**Symbols:**

```
ffffffff8138df50-ffffffff8138e216: security_compute_av (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void security_compute_av(u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a4b60)
Location: security/selinux/ss/services.c:1078
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_compute_av
```
**Symbols:**

```
ffffffff813a4b60-ffffffff813a4e31: security_compute_av (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void security_compute_av(u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bb520)
Location: security/selinux/ss/services.c:1090
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_compute_av
```
**Symbols:**

```
ffffffff813bb520-ffffffff813bb7e7: security_compute_av (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void security_compute_av(u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e1690)
Location: security/selinux/ss/services.c:1095
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_compute_av
```
**Symbols:**

```
ffffffff813e1690-ffffffff813e1957: security_compute_av (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void security_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1109
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_compute_av
```
**Symbols:**

```
ffffffff81414c8c-ffffffff81414cca: security_compute_av.cold.35 (STB_LOCAL)
ffffffff81411ce0-ffffffff81411f64: security_compute_av (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void security_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1106
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_compute_av
```
**Symbols:**

```
ffffffff81431242-ffffffff81431280: security_compute_av.cold.35 (STB_LOCAL)
ffffffff8142e1f0-ffffffff8142e48d: security_compute_av (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void security_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1092
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_compute_av
```
**Symbols:**

```
ffffffff8145ecdb-ffffffff8145ed19: security_compute_av.cold (STB_LOCAL)
ffffffff8145bb30-ffffffff8145bdcf: security_compute_av (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void security_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1092
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_compute_av
```
**Symbols:**

```
ffffffff81478a8d-ffffffff81478acb: security_compute_av.cold (STB_LOCAL)
ffffffff814758e0-ffffffff81475b7f: security_compute_av (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void security_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1099
Inline: False
```
**Symbols:**

```
ffffffff814cdf44-ffffffff814cdf82: security_compute_av.cold (STB_LOCAL)
ffffffff814cb180-ffffffff814cb323: security_compute_av (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void security_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1108
Inline: False
```
**Symbols:**

```
ffffffff81bf0f9f-ffffffff81bf0fd4: security_compute_av.cold (STB_LOCAL)
ffffffff814e8a00-ffffffff814e8b72: security_compute_av (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void security_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1110
Inline: False
```
**Symbols:**

```
ffffffff81be30c1-ffffffff81be30f6: security_compute_av.cold (STB_LOCAL)
ffffffff814ef220-ffffffff814ef4a3: security_compute_av (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void security_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1112
Inline: False
```
**Symbols:**

```
ffffffff81cd4e5d-ffffffff81cd4eb8: security_compute_av.cold (STB_LOCAL)
ffffffff815495f0-ffffffff81549783: security_compute_av (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void security_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1110
Inline: False
```
**Symbols:**

```
ffffffff81e87d62-ffffffff81e87dad: security_compute_av.cold (STB_LOCAL)
ffffffff815e22c0-ffffffff815e2458: security_compute_av (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void security_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1104
Inline: False
```
**Symbols:**

```
ffffffff82073cfa-ffffffff82073d0f: security_compute_av.cold (STB_LOCAL)
ffffffff81690f70-ffffffff8169114a: security_compute_av (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void security_compute_av(u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1095
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_compute_av
```
**Symbols:**

```
ffffffff820f38bd-ffffffff820f38d2: security_compute_av.cold (STB_LOCAL)
ffffffff816c9510-ffffffff816c96e7: security_compute_av (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void security_compute_av(u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1095
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_compute_av
```
**Symbols:**

```
ffffffff821d0a83-ffffffff821d0a98: security_compute_av.cold (STB_LOCAL)
ffffffff81706120-ffffffff817062f7: security_compute_av (STB_GLOBAL)
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
void security_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010564ea0)
Location: security/selinux/ss/services.c:1092
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_compute_av
```
**Symbols:**

```
ffff800010564ea0-ffff8000105651dc: security_compute_av (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void security_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c071998c)
Location: security/selinux/ss/services.c:1092
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_compute_av
```
**Symbols:**

```
c071998c-c0719c44: security_compute_av (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void security_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c7730)
Location: security/selinux/ss/services.c:1092
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_compute_av
```
**Symbols:**

```
c0000000006c7730-c0000000006c7b2c: security_compute_av (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void security_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bb582)
Location: security/selinux/ss/services.c:1092
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_compute_av
```
**Symbols:**

```
ffffffe0003bb582-ffffffe0003bb7e2: security_compute_av (STB_GLOBAL)
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
void security_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1092
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_compute_av
```
**Symbols:**

```
ffffffff8147106d-ffffffff814710ab: security_compute_av.cold (STB_LOCAL)
ffffffff8146dec0-ffffffff8146e15f: security_compute_av (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void security_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1092
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_compute_av
```
**Symbols:**

```
ffffffff81461a8d-ffffffff81461acb: security_compute_av.cold (STB_LOCAL)
ffffffff8145e8f0-ffffffff8145eb8f: security_compute_av (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void security_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1092
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_compute_av
```
**Symbols:**

```
ffffffff8146d10d-ffffffff8146d14b: security_compute_av.cold (STB_LOCAL)
ffffffff81469f60-ffffffff8146a1ff: security_compute_av (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void security_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, struct av_decision *avd, struct extended_perms *xperms);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1092
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_compute_av
```
**Symbols:**

```
ffffffff81484979-ffffffff814849b7: security_compute_av.cold (STB_LOCAL)
ffffffff81481700-ffffffff8148199d: security_compute_av (STB_GLOBAL)
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
<code>ssid, tsid, orig_tclass, avd, xperms</code> ➡️ <code>state, ssid, tsid, orig_tclass, avd, xperms</code>
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
<code>state, ssid, tsid, orig_tclass, avd, xperms</code> ➡️ <code>ssid, tsid, orig_tclass, avd, xperms</code>
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
