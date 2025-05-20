# Function: <code>slow_avc_audit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int slow_avc_audit(u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data *a, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81340e10)
Location: security/selinux/avc.c:741
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/hooks.c:audit_inode_permission
```
**Symbols:**

```
ffffffff81340e10-ffffffff81340ea3: slow_avc_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int slow_avc_audit(u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data *a, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813764c0)
Location: security/selinux/avc.c:741
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:cred_has_capability
```
**Symbols:**

```
ffffffff813764c0-ffffffff81376553: slow_avc_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int slow_avc_audit(u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data *a, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8138cdf0)
Location: security/selinux/avc.c:741
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:cred_has_capability
```
**Symbols:**

```
ffffffff8138cdf0-ffffffff8138ce83: slow_avc_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int slow_avc_audit(u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data *a, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813a2b20)
Location: security/selinux/avc.c:741
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:cred_has_capability
```
**Symbols:**

```
ffffffff813a2b20-ffffffff813a2bb3: slow_avc_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int slow_avc_audit(u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data *a, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813c8920)
Location: security/selinux/avc.c:737
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:cred_has_capability
```
**Symbols:**

```
ffffffff813c8920-ffffffff813c89b3: slow_avc_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int slow_avc_audit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data *a, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813f7fe0)
Location: security/selinux/avc.c:766
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:cred_has_capability
```
**Symbols:**

```
ffffffff813f7fe0-ffffffff813f807a: slow_avc_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int slow_avc_audit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data *a, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81413a90)
Location: security/selinux/avc.c:766
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:cred_has_capability
```
**Symbols:**

```
ffffffff81413a90-ffffffff81413b2a: slow_avc_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int slow_avc_audit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data *a, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (0)
Location: security/selinux/avc.c:758
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:cred_has_capability
```
**Symbols:**

```
ffffffff81441ef0-ffffffff81441f08: slow_avc_audit.cold (STB_LOCAL)
ffffffff81441570-ffffffff81441619: slow_avc_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int slow_avc_audit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8145ae50)
Location: security/selinux/avc.c:755
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:cred_has_capability
```
**Symbols:**

```
ffffffff8145ae50-ffffffff8145aeec: slow_avc_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int slow_avc_audit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814ae160)
Location: security/selinux/avc.c:755
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/hooks.c:audit_inode_permission
```
**Symbols:**

```
ffffffff814ae160-ffffffff814ae1fc: slow_avc_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int slow_avc_audit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814cbc10)
Location: security/selinux/avc.c:762
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/hooks.c:audit_inode_permission
```
**Symbols:**

```
ffffffff814cbc10-ffffffff814cbcac: slow_avc_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int slow_avc_audit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814d2240)
Location: security/selinux/avc.c:763
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/hooks.c:audit_inode_permission
```
**Symbols:**

```
ffffffff814d2240-ffffffff814d22dd: slow_avc_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int slow_avc_audit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8152b0b0)
Location: security/selinux/avc.c:767
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/hooks.c:audit_inode_permission
```
**Symbols:**

```
ffffffff8152b0b0-ffffffff8152b14d: slow_avc_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int slow_avc_audit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff815c0ad0)
Location: security/selinux/avc.c:769
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/hooks.c:audit_inode_permission
```
**Symbols:**

```
ffffffff815c0ad0-ffffffff815c0bca: slow_avc_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int slow_avc_audit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8166d0c0)
Location: security/selinux/avc.c:769
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/hooks.c:audit_inode_permission
```
**Symbols:**

```
ffffffff8166d0c0-ffffffff8166d1ba: slow_avc_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int slow_avc_audit(u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff816a5730)
Location: security/selinux/avc.c:756
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/hooks.c:audit_inode_permission
```
**Symbols:**

```
ffffffff816a5730-ffffffff816a5819: slow_avc_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int slow_avc_audit(u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff816e2170)
Location: security/selinux/avc.c:756
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/hooks.c:audit_inode_permission
```
**Symbols:**

```
ffffffff816e2170-ffffffff816e2259: slow_avc_audit (STB_GLOBAL)
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
int slow_avc_audit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffff8000105476f0)
Location: security/selinux/avc.c:755
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:cred_has_capability
```
**Symbols:**

```
ffff8000105476f0-ffff8000105477e4: slow_avc_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int slow_avc_audit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (c06fd330)
Location: security/selinux/avc.c:755
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:cred_has_capability
```
**Symbols:**

```
c06fd330-c06fd424: slow_avc_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int slow_avc_audit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (c00000000069e600)
Location: security/selinux/avc.c:755
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:cred_has_capability
```
**Symbols:**

```
c00000000069e600-c00000000069e720: slow_avc_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int slow_avc_audit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffe0003a2d8e)
Location: security/selinux/avc.c:755
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:cred_has_capability
```
**Symbols:**

```
ffffffe0003a2d8e-ffffffe0003a2e4a: slow_avc_audit (STB_GLOBAL)
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
int slow_avc_audit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81453430)
Location: security/selinux/avc.c:755
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:cred_has_capability
```
**Symbols:**

```
ffffffff81453430-ffffffff814534cc: slow_avc_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int slow_avc_audit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81443e70)
Location: security/selinux/avc.c:755
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:cred_has_capability
```
**Symbols:**

```
ffffffff81443e70-ffffffff81443f0c: slow_avc_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int slow_avc_audit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8144f4d0)
Location: security/selinux/avc.c:755
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:cred_has_capability
```
**Symbols:**

```
ffffffff8144f4d0-ffffffff8144f56c: slow_avc_audit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int slow_avc_audit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u32 audited, u32 denied, int result, struct common_audit_data *a);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81466900)
Location: security/selinux/avc.c:755
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_extended_perms
  - security/selinux/hooks.c:audit_inode_permission
  - security/selinux/hooks.c:cred_has_capability
```
**Symbols:**

```
ffffffff81466900-ffffffff8146699c: slow_avc_audit (STB_GLOBAL)
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
<code>ssid, tsid, tclass, requested, audited, denied, result, a, flags</code> ➡️ <code>state, ssid, tsid, tclass, requested, audited, denied, result, a, flags</code>
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
<code>state, ssid, tsid, tclass, requested, audited, denied, result, a</code> ➡️ <code>ssid, tsid, tclass, requested, audited, denied, result, a</code>
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
