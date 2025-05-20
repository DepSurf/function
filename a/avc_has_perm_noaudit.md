# Function: <code>avc_has_perm_noaudit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int avc_has_perm_noaudit(u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (ffffffff81340d80)
Location: security/selinux/avc.c:1098
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_perm_flags
Direct callers:
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/ss/services.c:security_get_user_sids
```
**Symbols:**

```
ffffffff81340d80-ffffffff81340d86: avc_has_perm_noaudit.part.5 (STB_LOCAL)
ffffffff813413c0-ffffffff813414db: avc_has_perm_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int avc_has_perm_noaudit(u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (ffffffff81376d4f)
Location: security/selinux/avc.c:1098
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/ss/services.c:security_get_user_sids
```
**Symbols:**

```
ffffffff81376420-ffffffff81376426: avc_has_perm_noaudit.part.5 (STB_LOCAL)
ffffffff81376a60-ffffffff81376b78: avc_has_perm_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int avc_has_perm_noaudit(u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (ffffffff8138d67f)
Location: security/selinux/avc.c:1098
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/ss/services.c:security_get_user_sids
```
**Symbols:**

```
ffffffff8138cd50-ffffffff8138cd56: avc_has_perm_noaudit.part.7 (STB_LOCAL)
ffffffff8138d390-ffffffff8138d4a8: avc_has_perm_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int avc_has_perm_noaudit(u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (ffffffff813a336f)
Location: security/selinux/avc.c:1098
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/ss/services.c:security_get_user_sids
```
**Symbols:**

```
ffffffff813a2a80-ffffffff813a2a86: avc_has_perm_noaudit.part.6 (STB_LOCAL)
ffffffff813a3090-ffffffff813a31a5: avc_has_perm_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int avc_has_perm_noaudit(u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (ffffffff813c916f)
Location: security/selinux/avc.c:1094
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/ss/services.c:security_get_user_sids
```
**Symbols:**

```
ffffffff813c8880-ffffffff813c8886: avc_has_perm_noaudit.part.6 (STB_LOCAL)
ffffffff813c8e90-ffffffff813c8fa5: avc_has_perm_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int avc_has_perm_noaudit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (ffffffff813f8975)
Location: security/selinux/avc.c:1132
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/ss/services.c:security_get_user_sids
```
**Symbols:**

```
ffffffff813f7eb0-ffffffff813f7eb6: avc_has_perm_noaudit.part.14 (STB_LOCAL)
ffffffff813f8650-ffffffff813f8788: avc_has_perm_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int avc_has_perm_noaudit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (ffffffff81414425)
Location: security/selinux/avc.c:1132
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
Direct callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/ss/services.c:security_get_user_sids
```
**Symbols:**

```
ffffffff81413960-ffffffff81413966: avc_has_perm_noaudit.part.14 (STB_LOCAL)
ffffffff81414100-ffffffff81414238: avc_has_perm_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int avc_has_perm_noaudit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (ffffffff81441cd5)
Location: security/selinux/avc.c:1145
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm
Direct callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/ss/services.c:security_get_user_sids
```
**Symbols:**

```
ffffffff81441f21-ffffffff81441f39: avc_has_perm_noaudit.cold (STB_LOCAL)
ffffffff81441b80-ffffffff81441ca6: avc_has_perm_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int avc_has_perm_noaudit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8145b795)
Location: security/selinux/avc.c:1129
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
Direct callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/ss/services.c:security_get_user_sids
```
**Symbols:**

```
ffffffff8145b460-ffffffff8145b58f: avc_has_perm_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int avc_has_perm_noaudit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814ae9ac)
Location: security/selinux/avc.c:1129
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
Direct callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/ss/services.c:security_get_user_sids
```
**Symbols:**

```
ffffffff814ae710-ffffffff814ae7fc: avc_has_perm_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int avc_has_perm_noaudit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814cc48c)
Location: security/selinux/avc.c:1136
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
Direct callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/ss/services.c:security_get_user_sids
```
**Symbols:**

```
ffffffff814cc1d0-ffffffff814cc2bd: avc_has_perm_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int avc_has_perm_noaudit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814d2abc)
Location: security/selinux/avc.c:1137
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
Direct callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/ss/services.c:security_get_user_sids
```
**Symbols:**

```
ffffffff814d2800-ffffffff814d28ed: avc_has_perm_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int avc_has_perm_noaudit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8152b78c)
Location: security/selinux/avc.c:1126
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm
Direct callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/ss/services.c:security_get_user_sids
```
**Symbols:**

```
ffffffff8152b670-ffffffff8152b75d: avc_has_perm_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int avc_has_perm_noaudit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff815c13cc)
Location: security/selinux/avc.c:1136
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm
Direct callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/ss/services.c:security_get_user_sids
```
**Symbols:**

```
ffffffff815c1250-ffffffff815c136d: avc_has_perm_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int avc_has_perm_noaudit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8166d860)
Location: security/selinux/avc.c:1136
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/ss/services.c:security_get_user_sids
```
**Symbols:**

```
ffffffff8166d860-ffffffff8166d97d: avc_has_perm_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int avc_has_perm_noaudit(u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff816a5fa0)
Location: security/selinux/avc.c:1141
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/ss/services.c:security_get_user_sids
```
**Symbols:**

```
ffffffff816a5fa0-ffffffff816a609b: avc_has_perm_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int avc_has_perm_noaudit(u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff816e29e0)
Location: security/selinux/avc.c:1142
Inline: False
Direct callers:
  - security/selinux/avc.c:avc_has_perm
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:selinux_vm_enough_memory
  - security/selinux/ss/services.c:security_get_user_sids
```
**Symbols:**

```
ffffffff816e29e0-ffffffff816e2adb: avc_has_perm_noaudit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int avc_has_perm_noaudit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffff800010547f78)
Location: security/selinux/avc.c:1129
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
Direct callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/ss/services.c:security_get_user_sids
```
**Symbols:**

```
ffff800010547c68-ffff800010547d88: avc_has_perm_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int avc_has_perm_noaudit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (c06fdbb4)
Location: security/selinux/avc.c:1129
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
Direct callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/ss/services.c:security_get_user_sids
```
**Symbols:**

```
c06fd8a8-c06fd9cc: avc_has_perm_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int avc_has_perm_noaudit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (c00000000069f0b8)
Location: security/selinux/avc.c:1129
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
Direct callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/ss/services.c:security_get_user_sids
```
**Symbols:**

```
c00000000069ecc0-c00000000069ee38: avc_has_perm_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int avc_has_perm_noaudit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffe0003a33c0)
Location: security/selinux/avc.c:1129
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
Direct callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/ss/services.c:security_get_user_sids
```
**Symbols:**

```
ffffffe0003a31c2-ffffffe0003a3270: avc_has_perm_noaudit (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int avc_has_perm_noaudit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81453d75)
Location: security/selinux/avc.c:1129
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
Direct callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/ss/services.c:security_get_user_sids
```
**Symbols:**

```
ffffffff81453a40-ffffffff81453b6f: avc_has_perm_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int avc_has_perm_noaudit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814447b5)
Location: security/selinux/avc.c:1129
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
Direct callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/ss/services.c:security_get_user_sids
```
**Symbols:**

```
ffffffff81444480-ffffffff814445af: avc_has_perm_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int avc_has_perm_noaudit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8144fe15)
Location: security/selinux/avc.c:1129
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
Direct callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/ss/services.c:security_get_user_sids
```
**Symbols:**

```
ffffffff8144fae0-ffffffff8144fc0f: avc_has_perm_noaudit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int avc_has_perm_noaudit(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, unsigned int flags, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814672bc)
Location: security/selinux/avc.c:1129
Inline: True
Inline callers:
  - security/selinux/avc.c:avc_has_perm_flags
  - security/selinux/avc.c:avc_has_perm
Direct callers:
  - security/selinux/hooks.c:selinux_inode_permission
  - security/selinux/hooks.c:cred_has_capability
  - security/selinux/ss/services.c:security_get_user_sids
```
**Symbols:**

```
ffffffff81466f20-ffffffff81467079: avc_has_perm_noaudit (STB_GLOBAL)
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
<code>ssid, tsid, tclass, requested, flags, avd</code> ➡️ <code>state, ssid, tsid, tclass, requested, flags, avd</code>
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
<code>state, ssid, tsid, tclass, requested, flags, avd</code> ➡️ <code>ssid, tsid, tclass, requested, flags, avd</code>
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
