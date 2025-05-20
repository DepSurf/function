# Function: <code>security_compute_xperms_decision</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void security_compute_xperms_decision(u32 ssid, u32 tsid, u16 orig_tclass, u8 driver, struct extended_perms_decision *xpermd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81357bc0)
Location: security/selinux/ss/services.c:993
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff81357bc0-ffffffff81358001: security_compute_xperms_decision (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void security_compute_xperms_decision(u32 ssid, u32 tsid, u16 orig_tclass, u8 driver, struct extended_perms_decision *xpermd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138db10)
Location: security/selinux/ss/services.c:987
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff8138db10-ffffffff8138df47: security_compute_xperms_decision (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void security_compute_xperms_decision(u32 ssid, u32 tsid, u16 orig_tclass, u8 driver, struct extended_perms_decision *xpermd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a4720)
Location: security/selinux/ss/services.c:987
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff813a4720-ffffffff813a4b57: security_compute_xperms_decision (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void security_compute_xperms_decision(u32 ssid, u32 tsid, u16 orig_tclass, u8 driver, struct extended_perms_decision *xpermd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bb100)
Location: security/selinux/ss/services.c:999
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff813bb100-ffffffff813bb516: security_compute_xperms_decision (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void security_compute_xperms_decision(u32 ssid, u32 tsid, u16 orig_tclass, u8 driver, struct extended_perms_decision *xpermd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e1270)
Location: security/selinux/ss/services.c:1004
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff813e1270-ffffffff813e1686: security_compute_xperms_decision (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void security_compute_xperms_decision(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, u8 driver, struct extended_perms_decision *xpermd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1011
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff81414c29-ffffffff81414c8c: security_compute_xperms_decision.cold.34 (STB_LOCAL)
ffffffff814118b0-ffffffff81411cdf: security_compute_xperms_decision (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void security_compute_xperms_decision(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, u8 driver, struct extended_perms_decision *xpermd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1008
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff814311df-ffffffff81431242: security_compute_xperms_decision.cold.34 (STB_LOCAL)
ffffffff8142ddb0-ffffffff8142e1e9: security_compute_xperms_decision (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void security_compute_xperms_decision(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, u8 driver, struct extended_perms_decision *xpermd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:998
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff8145ec78-ffffffff8145ecdb: security_compute_xperms_decision.cold (STB_LOCAL)
ffffffff8145b6c0-ffffffff8145bb21: security_compute_xperms_decision (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void security_compute_xperms_decision(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, u8 driver, struct extended_perms_decision *xpermd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:998
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff81478a2a-ffffffff81478a8d: security_compute_xperms_decision.cold (STB_LOCAL)
ffffffff81475470-ffffffff814758d1: security_compute_xperms_decision (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void security_compute_xperms_decision(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, u8 driver, struct extended_perms_decision *xpermd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1005
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff814cdee1-ffffffff814cdf44: security_compute_xperms_decision.cold (STB_LOCAL)
ffffffff814cacf0-ffffffff814cb174: security_compute_xperms_decision (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void security_compute_xperms_decision(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, u8 driver, struct extended_perms_decision *xpermd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1012
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff81bf0f54-ffffffff81bf0f9f: security_compute_xperms_decision.cold (STB_LOCAL)
ffffffff814e85e0-ffffffff814e89fd: security_compute_xperms_decision (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void security_compute_xperms_decision(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, u8 driver, struct extended_perms_decision *xpermd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1014
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff81be3076-ffffffff81be30c1: security_compute_xperms_decision.cold (STB_LOCAL)
ffffffff814eedf0-ffffffff814ef21a: security_compute_xperms_decision (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void security_compute_xperms_decision(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, u8 driver, struct extended_perms_decision *xpermd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1015
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff81cd4df7-ffffffff81cd4e5d: security_compute_xperms_decision.cold (STB_LOCAL)
ffffffff81549190-ffffffff815495ec: security_compute_xperms_decision (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void security_compute_xperms_decision(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, u8 driver, struct extended_perms_decision *xpermd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1013
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff81e87cfc-ffffffff81e87d62: security_compute_xperms_decision.cold (STB_LOCAL)
ffffffff815e1e60-ffffffff815e22b3: security_compute_xperms_decision (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void security_compute_xperms_decision(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, u8 driver, struct extended_perms_decision *xpermd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1007
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff82073cdf-ffffffff82073cfa: security_compute_xperms_decision.cold (STB_LOCAL)
ffffffff81690ad0-ffffffff81690f60: security_compute_xperms_decision (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void security_compute_xperms_decision(u32 ssid, u32 tsid, u16 orig_tclass, u8 driver, struct extended_perms_decision *xpermd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1000
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff820f38a8-ffffffff820f38bd: security_compute_xperms_decision.cold (STB_LOCAL)
ffffffff816c9060-ffffffff816c94f4: security_compute_xperms_decision (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void security_compute_xperms_decision(u32 ssid, u32 tsid, u16 orig_tclass, u8 driver, struct extended_perms_decision *xpermd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1000
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff821d0a6e-ffffffff821d0a83: security_compute_xperms_decision.cold (STB_LOCAL)
ffffffff81705c70-ffffffff81706104: security_compute_xperms_decision (STB_GLOBAL)
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
void security_compute_xperms_decision(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, u8 driver, struct extended_perms_decision *xpermd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010564a18)
Location: security/selinux/ss/services.c:998
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffff800010564a18-ffff800010564ea0: security_compute_xperms_decision (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void security_compute_xperms_decision(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, u8 driver, struct extended_perms_decision *xpermd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0719538)
Location: security/selinux/ss/services.c:998
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
c0719538-c071998c: security_compute_xperms_decision (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void security_compute_xperms_decision(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, u8 driver, struct extended_perms_decision *xpermd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c71a0)
Location: security/selinux/ss/services.c:998
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
c0000000006c71a0-c0000000006c7724: security_compute_xperms_decision (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void security_compute_xperms_decision(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, u8 driver, struct extended_perms_decision *xpermd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bb1de)
Location: security/selinux/ss/services.c:998
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffe0003bb1de-ffffffe0003bb582: security_compute_xperms_decision (STB_GLOBAL)
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
void security_compute_xperms_decision(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, u8 driver, struct extended_perms_decision *xpermd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:998
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff8147100a-ffffffff8147106d: security_compute_xperms_decision.cold (STB_LOCAL)
ffffffff8146da50-ffffffff8146deb1: security_compute_xperms_decision (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void security_compute_xperms_decision(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, u8 driver, struct extended_perms_decision *xpermd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:998
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff81461a2a-ffffffff81461a8d: security_compute_xperms_decision.cold (STB_LOCAL)
ffffffff8145e480-ffffffff8145e8e1: security_compute_xperms_decision (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void security_compute_xperms_decision(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, u8 driver, struct extended_perms_decision *xpermd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:998
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff8146d0aa-ffffffff8146d10d: security_compute_xperms_decision.cold (STB_LOCAL)
ffffffff81469af0-ffffffff81469f51: security_compute_xperms_decision (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void security_compute_xperms_decision(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, u8 driver, struct extended_perms_decision *xpermd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:998
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff81484916-ffffffff81484979: security_compute_xperms_decision.cold (STB_LOCAL)
ffffffff814812a0-ffffffff81481700: security_compute_xperms_decision (STB_GLOBAL)
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
<code>ssid, tsid, orig_tclass, driver, xpermd</code> ➡️ <code>state, ssid, tsid, orig_tclass, driver, xpermd</code>
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
<code>state, ssid, tsid, orig_tclass, driver, xpermd</code> ➡️ <code>ssid, tsid, orig_tclass, driver, xpermd</code>
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
