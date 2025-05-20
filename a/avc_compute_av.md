# Function: <code>avc_compute_av</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct avc_node *avc_compute_av(u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd, struct avc_xperms_node *xp_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813407f0)
Location: security/selinux/avc.c:970
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_perm_flags
```
**Symbols:**

```
ffffffff813407f0-ffffffff813409c5: avc_compute_av (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct avc_node *avc_compute_av(u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd, struct avc_xperms_node *xp_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81375ea0)
Location: security/selinux/avc.c:970
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff81375ea0-ffffffff81376071: avc_compute_av (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct avc_node *avc_compute_av(u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd, struct avc_xperms_node *xp_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8138c7d0)
Location: security/selinux/avc.c:970
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff8138c7d0-ffffffff8138c9a1: avc_compute_av (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct avc_node *avc_compute_av(u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd, struct avc_xperms_node *xp_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813a2540)
Location: security/selinux/avc.c:970
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff813a2540-ffffffff813a26e8: avc_compute_av (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct avc_node *avc_compute_av(u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd, struct avc_xperms_node *xp_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813c8340)
Location: security/selinux/avc.c:966
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff813c8340-ffffffff813c84e8: avc_compute_av (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct avc_node *avc_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd, struct avc_xperms_node *xp_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (0)
Location: security/selinux/avc.c:999
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff813f79c0-ffffffff813f7b70: avc_compute_av (STB_LOCAL)
ffffffff813f8b52-ffffffff813f8b80: avc_compute_av.cold.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct avc_node *avc_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd, struct avc_xperms_node *xp_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (0)
Location: security/selinux/avc.c:999
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff81413470-ffffffff81413620: avc_compute_av (STB_LOCAL)
ffffffff81414602-ffffffff81414630: avc_compute_av.cold.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct avc_node *avc_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd, struct avc_xperms_node *xp_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (0)
Location: security/selinux/avc.c:1011
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff81440f10-ffffffff814410bf: avc_compute_av (STB_LOCAL)
ffffffff81441ec2-ffffffff81441ef0: avc_compute_av.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct avc_node *avc_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd, struct avc_xperms_node *xp_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (0)
Location: security/selinux/avc.c:995
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff8145a820-ffffffff8145a9cf: avc_compute_av (STB_LOCAL)
ffffffff8145b9a2-ffffffff8145b9d0: avc_compute_av.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (ffffffff814adcf0)
Location: security/selinux/avc.c:995
Inline: True
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff814adcf0-ffffffff814add59: avc_compute_av.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (ffffffff814cb770)
Location: security/selinux/avc.c:1002
Inline: True
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff814cb770-ffffffff814cb7ee: avc_compute_av.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (ffffffff814d1d90)
Location: security/selinux/avc.c:1003
Inline: True
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff814d1d90-ffffffff814d1e0e: avc_compute_av.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (ffffffff8152ab50)
Location: security/selinux/avc.c:992
Inline: True
Direct callers:
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff8152ab50-ffffffff8152abce: avc_compute_av.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (0)
Location: security/selinux/avc.c:1001
Inline: True
Direct callers:
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff815c06c0-ffffffff815c08de: avc_compute_av.isra.0 (STB_LOCAL)
ffffffff81e8667f-ffffffff81e866a7: avc_compute_av.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (ffffffff8166cc30)
Location: security/selinux/avc.c:1001
Inline: True
Direct callers:
  - security/selinux/avc.c:avc_has_perm_noaudit
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff8166cc30-ffffffff8166ce76: avc_compute_av.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void avc_compute_av(u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd, struct avc_xperms_node *xp_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff816a4ed0)
Location: security/selinux/avc.c:984
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_perm_nonode
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff816a4ed0-ffffffff816a50eb: avc_compute_av (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void avc_compute_av(u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd, struct avc_xperms_node *xp_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff816e1930)
Location: security/selinux/avc.c:985
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_perm_nonode
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff816e1930-ffffffff816e1b3f: avc_compute_av (STB_LOCAL)
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
struct avc_node *avc_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd, struct avc_xperms_node *xp_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffff800010546e88)
Location: security/selinux/avc.c:995
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffff800010546e88-ffff800010547188: avc_compute_av (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct avc_node *avc_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd, struct avc_xperms_node *xp_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (c06fcbe8)
Location: security/selinux/avc.c:995
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
c06fcbe8-c06fcdc4: avc_compute_av (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct avc_node *avc_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd, struct avc_xperms_node *xp_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (c00000000069dd30)
Location: security/selinux/avc.c:995
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
c00000000069dd30-c00000000069df78: avc_compute_av (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct avc_node *avc_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd, struct avc_xperms_node *xp_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffe0003a2742)
Location: security/selinux/avc.c:995
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffe0003a2742-ffffffe0003a2920: avc_compute_av (STB_LOCAL)
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
struct avc_node *avc_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd, struct avc_xperms_node *xp_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (0)
Location: security/selinux/avc.c:995
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff81452e00-ffffffff81452faf: avc_compute_av (STB_LOCAL)
ffffffff81453f82-ffffffff81453fb0: avc_compute_av.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct avc_node *avc_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd, struct avc_xperms_node *xp_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (0)
Location: security/selinux/avc.c:995
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff81443840-ffffffff814439ef: avc_compute_av (STB_LOCAL)
ffffffff814449c2-ffffffff814449f0: avc_compute_av.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct avc_node *avc_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd, struct avc_xperms_node *xp_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (0)
Location: security/selinux/avc.c:995
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff8144eea0-ffffffff8144f04f: avc_compute_av (STB_LOCAL)
ffffffff81450022-ffffffff81450050: avc_compute_av.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct avc_node *avc_compute_av(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd, struct avc_xperms_node *xp_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (0)
Location: security/selinux/avc.c:995
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff81466290-ffffffff8146645a: avc_compute_av (STB_LOCAL)
ffffffff814674f2-ffffffff81467520: avc_compute_av.cold (STB_LOCAL)
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
<code>ssid, tsid, tclass, avd, xp_node</code> ➡️ <code>state, ssid, tsid, tclass, avd, xp_node</code>
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
