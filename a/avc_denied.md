# Function: <code>avc_denied</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int avc_denied(u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81340cf0)
Location: security/selinux/avc.c:981
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_perm_flags
```
**Symbols:**

```
ffffffff81340cf0-ffffffff81340d76: avc_denied (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int avc_denied(u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81376390)
Location: security/selinux/avc.c:981
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff81376390-ffffffff81376416: avc_denied (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int avc_denied(u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8138ccc0)
Location: security/selinux/avc.c:981
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff8138ccc0-ffffffff8138cd46: avc_denied (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int avc_denied(u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813a2a00)
Location: security/selinux/avc.c:981
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff813a2a00-ffffffff813a2a77: avc_denied (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int avc_denied(u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813c8800)
Location: security/selinux/avc.c:977
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff813c8800-ffffffff813c8877: avc_denied (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int avc_denied(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813f7e30)
Location: security/selinux/avc.c:1011
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff813f7e30-ffffffff813f7ea7: avc_denied (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int avc_denied(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814138e0)
Location: security/selinux/avc.c:1011
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff814138e0-ffffffff81413957: avc_denied (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int avc_denied(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814413e0)
Location: security/selinux/avc.c:1023
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff814413e0-ffffffff81441455: avc_denied (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int avc_denied(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8145acc0)
Location: security/selinux/avc.c:1007
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff8145acc0-ffffffff8145ad35: avc_denied (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int avc_denied(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814adfd0)
Location: security/selinux/avc.c:1007
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff814adfd0-ffffffff814ae04a: avc_denied (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int avc_denied(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814cba60)
Location: security/selinux/avc.c:1014
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff814cba60-ffffffff814cbada: avc_denied (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int avc_denied(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814d2080)
Location: security/selinux/avc.c:1015
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff814d2080-ffffffff814d2108: avc_denied (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int avc_denied(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (0)
Location: security/selinux/avc.c:1004
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff8152ae50-ffffffff8152aee1: avc_denied (STB_LOCAL)
ffffffff81cd355b-ffffffff81cd3594: avc_denied.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int avc_denied(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (0)
Location: security/selinux/avc.c:1013
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff815c0610-ffffffff815c06b6: avc_denied (STB_LOCAL)
ffffffff81e86646-ffffffff81e8667f: avc_denied.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int avc_denied(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (0)
Location: security/selinux/avc.c:1013
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_noaudit
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff8166cb70-ffffffff8166cc16: avc_denied (STB_LOCAL)
ffffffff82073289-ffffffff820732c2: avc_denied.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int avc_denied(u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (0)
Location: security/selinux/avc.c:993
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_noaudit
  - security/selinux/avc.c:avc_perm_nonode
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff816a5380-ffffffff816a5422: avc_denied (STB_LOCAL)
ffffffff820f2ed2-ffffffff820f2f05: avc_denied.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int avc_denied(u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (0)
Location: security/selinux/avc.c:994
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_noaudit
  - security/selinux/avc.c:avc_perm_nonode
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff816e1dc0-ffffffff816e1e62: avc_denied (STB_LOCAL)
ffffffff821d0142-ffffffff821d0175: avc_denied.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (ffff8000105474b0)
Location: security/selinux/avc.c:1007
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffff8000105474b0-ffff80001054757c: avc_denied.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int avc_denied(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (c06fd124)
Location: security/selinux/avc.c:1007
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
c06fd124-c06fd1cc: avc_denied (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (c00000000069e3b0)
Location: security/selinux/avc.c:1007
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
c00000000069e3b0-c00000000069e468: avc_denied.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (ffffffe0003a2bb8)
Location: security/selinux/avc.c:1007
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffe0003a2bb8-ffffffe0003a2c4c: avc_denied.isra.0 (STB_LOCAL)
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
int avc_denied(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814532a0)
Location: security/selinux/avc.c:1007
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff814532a0-ffffffff81453315: avc_denied (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int avc_denied(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81443ce0)
Location: security/selinux/avc.c:1007
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff81443ce0-ffffffff81443d55: avc_denied (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int avc_denied(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8144f340)
Location: security/selinux/avc.c:1007
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff8144f340-ffffffff8144f3b5: avc_denied (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int avc_denied(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81466750)
Location: security/selinux/avc.c:1007
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff81466750-ffffffff814667c5: avc_denied (STB_LOCAL)
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
<code>ssid, tsid, tclass, requested, driver, xperm, flags, avd</code> ➡️ <code>state, ssid, tsid, tclass, requested, driver, xperm, flags, avd</code>
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
<code>state, ssid, tsid, tclass, requested, driver, xperm, flags, avd</code> ➡️ <code>ssid, tsid, tclass, requested, driver, xperm, flags, avd</code>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
