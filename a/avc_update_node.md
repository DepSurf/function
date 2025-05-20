# Function: <code>avc_update_node</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int avc_update_node(u32 event, u32 perms, u8 driver, u8 xperm, u32 ssid, u32 tsid, u16 tclass, u32 seqno, struct extended_perms_decision *xpd, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813409d0)
Location: security/selinux/avc.c:820
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_denied
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffff813409d0-ffffffff81340ce9: avc_update_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int avc_update_node(u32 event, u32 perms, u8 driver, u8 xperm, u32 ssid, u32 tsid, u16 tclass, u32 seqno, struct extended_perms_decision *xpd, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81376080)
Location: security/selinux/avc.c:820
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
```
**Symbols:**

```
ffffffff81376080-ffffffff8137638d: avc_update_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int avc_update_node(u32 event, u32 perms, u8 driver, u8 xperm, u32 ssid, u32 tsid, u16 tclass, u32 seqno, struct extended_perms_decision *xpd, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8138c9b0)
Location: security/selinux/avc.c:820
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
```
**Symbols:**

```
ffffffff8138c9b0-ffffffff8138ccbd: avc_update_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int avc_update_node(u32 event, u32 perms, u8 driver, u8 xperm, u32 ssid, u32 tsid, u16 tclass, u32 seqno, struct extended_perms_decision *xpd, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813a26f0)
Location: security/selinux/avc.c:820
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
```
**Symbols:**

```
ffffffff813a26f0-ffffffff813a29fc: avc_update_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int avc_update_node(u32 event, u32 perms, u8 driver, u8 xperm, u32 ssid, u32 tsid, u16 tclass, u32 seqno, struct extended_perms_decision *xpd, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813c84f0)
Location: security/selinux/avc.c:816
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
```
**Symbols:**

```
ffffffff813c84f0-ffffffff813c87fc: avc_update_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int avc_update_node(struct selinux_avc *avc, u32 event, u32 perms, u8 driver, u8 xperm, u32 ssid, u32 tsid, u16 tclass, u32 seqno, struct extended_perms_decision *xpd, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813f7b70)
Location: security/selinux/avc.c:847
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
```
**Symbols:**

```
ffffffff813f7b70-ffffffff813f7e21: avc_update_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int avc_update_node(struct selinux_avc *avc, u32 event, u32 perms, u8 driver, u8 xperm, u32 ssid, u32 tsid, u16 tclass, u32 seqno, struct extended_perms_decision *xpd, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81413620)
Location: security/selinux/avc.c:847
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
```
**Symbols:**

```
ffffffff81413620-ffffffff814138d1: avc_update_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (ffffffff81441b00)
Location: security/selinux/avc.c:843
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
```
**Symbols:**

```
ffffffff814410c0-ffffffff814413d1: avc_update_node.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (ffffffff8145b3db)
Location: security/selinux/avc.c:828
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
```
**Symbols:**

```
ffffffff8145a9d0-ffffffff8145acc0: avc_update_node.part.0 (STB_LOCAL)
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
In security/selinux/avc.c (ffffffff814ae6a0)
Location: security/selinux/avc.c:828
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
```
**Symbols:**

```
ffffffff814add60-ffffffff814adfc1: avc_update_node.part.0.isra.0 (STB_LOCAL)
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
In security/selinux/avc.c (ffffffff814cc167)
Location: security/selinux/avc.c:835
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
```
**Symbols:**

```
ffffffff814cb7f0-ffffffff814cba51: avc_update_node.part.0.isra.0 (STB_LOCAL)
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
In security/selinux/avc.c (ffffffff814d2797)
Location: security/selinux/avc.c:836
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
```
**Symbols:**

```
ffffffff814d1e10-ffffffff814d2074: avc_update_node.part.0.isra.0 (STB_LOCAL)
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
In security/selinux/avc.c (ffffffff8152abd0)
Location: security/selinux/avc.c:840
Inline: True
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
```
**Symbols:**

```
ffffffff8152abd0-ffffffff8152ae43: avc_update_node.isra.0 (STB_LOCAL)
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
In security/selinux/avc.c (ffffffff815c0380)
Location: security/selinux/avc.c:847
Inline: True
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
```
**Symbols:**

```
ffffffff815c0380-ffffffff815c0609: avc_update_node.isra.0 (STB_LOCAL)
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
In security/selinux/avc.c (ffffffff8166c8d0)
Location: security/selinux/avc.c:847
Inline: True
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
```
**Symbols:**

```
ffffffff8166c8d0-ffffffff8166cb59: avc_update_node.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (ffffffff816a5100)
Location: security/selinux/avc.c:831
Inline: True
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
```
**Symbols:**

```
ffffffff816a5100-ffffffff816a5368: avc_update_node.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (ffffffff816e1b50)
Location: security/selinux/avc.c:831
Inline: True
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
```
**Symbols:**

```
ffffffff816e1b50-ffffffff816e1dad: avc_update_node.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (ffff800010547c1c)
Location: security/selinux/avc.c:828
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_extended_perms
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffff800010547188-ffff8000105474b0: avc_update_node.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (c06fd85c)
Location: security/selinux/avc.c:828
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
```
**Symbols:**

```
c06fcdc4-c06fd124: avc_update_node.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (c00000000069ec3c)
Location: security/selinux/avc.c:828
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_extended_perms
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
c00000000069df80-c00000000069e3a8: avc_update_node.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (ffffffe0003a3194)
Location: security/selinux/avc.c:828
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_extended_perms
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
```
**Symbols:**

```
ffffffe0003a2920-ffffffe0003a2bb8: avc_update_node.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (ffffffff814539bb)
Location: security/selinux/avc.c:828
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
```
**Symbols:**

```
ffffffff81452fb0-ffffffff814532a0: avc_update_node.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (ffffffff814443fb)
Location: security/selinux/avc.c:828
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
```
**Symbols:**

```
ffffffff814439f0-ffffffff81443ce0: avc_update_node.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (ffffffff8144fa5b)
Location: security/selinux/avc.c:828
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
```
**Symbols:**

```
ffffffff8144f050-ffffffff8144f340: avc_update_node.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (ffffffff81466eb7)
Location: security/selinux/avc.c:828
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_denied
```
**Symbols:**

```
ffffffff81466460-ffffffff81466750: avc_update_node.part.0 (STB_LOCAL)
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
<code>struct selinux_avc *avc</code>
</li>
<li>
<b>Param reordered. </b>
<code>event, perms, driver, xperm, ssid, tsid, tclass, seqno, xpd, flags</code> ➡️ <code>avc, event, perms, driver, xperm, ssid, tsid, tclass, seqno, xpd, flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
