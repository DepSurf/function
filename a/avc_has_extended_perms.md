# Function: <code>avc_has_extended_perms</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int avc_has_extended_perms(u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, struct common_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81340f40)
Location: security/selinux/avc.c:1004
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
```
**Symbols:**

```
ffffffff81340f40-ffffffff813413b7: avc_has_extended_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int avc_has_extended_perms(u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, struct common_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813765f0)
Location: security/selinux/avc.c:1004
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
```
**Symbols:**

```
ffffffff813765f0-ffffffff81376a55: avc_has_extended_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int avc_has_extended_perms(u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, struct common_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8138cf20)
Location: security/selinux/avc.c:1004
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
```
**Symbols:**

```
ffffffff8138cf20-ffffffff8138d385: avc_has_extended_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int avc_has_extended_perms(u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, struct common_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813a2c40)
Location: security/selinux/avc.c:1004
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
```
**Symbols:**

```
ffffffff813a2c40-ffffffff813a308b: avc_has_extended_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int avc_has_extended_perms(u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, struct common_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813c8a40)
Location: security/selinux/avc.c:1000
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
```
**Symbols:**

```
ffffffff813c8a40-ffffffff813c8e8b: avc_has_extended_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int avc_has_extended_perms(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, struct common_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813f8110)
Location: security/selinux/avc.c:1036
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
```
**Symbols:**

```
ffffffff813f8110-ffffffff813f8648: avc_has_extended_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int avc_has_extended_perms(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, struct common_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81413bc0)
Location: security/selinux/avc.c:1036
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
```
**Symbols:**

```
ffffffff81413bc0-ffffffff814140f8: avc_has_extended_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int avc_has_extended_perms(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, struct common_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/avc.c (0)
Location: security/selinux/avc.c:1048
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
```
**Symbols:**

```
ffffffff81441f08-ffffffff81441f21: avc_has_extended_perms.cold (STB_LOCAL)
ffffffff814416b0-ffffffff81441b77: avc_has_extended_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int avc_has_extended_perms(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, struct common_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8145af80)
Location: security/selinux/avc.c:1032
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
```
**Symbols:**

```
ffffffff8145af80-ffffffff8145b452: avc_has_extended_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int avc_has_extended_perms(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, struct common_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814ae290)
Location: security/selinux/avc.c:1032
Inline: False
```
**Symbols:**

```
ffffffff814ae290-ffffffff814ae701: avc_has_extended_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int avc_has_extended_perms(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, struct common_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814cbd40)
Location: security/selinux/avc.c:1039
Inline: False
```
**Symbols:**

```
ffffffff814cbd40-ffffffff814cc1c5: avc_has_extended_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int avc_has_extended_perms(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, struct common_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814d2370)
Location: security/selinux/avc.c:1040
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
```
**Symbols:**

```
ffffffff814d2370-ffffffff814d27f5: avc_has_extended_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int avc_has_extended_perms(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, struct common_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8152b1e0)
Location: security/selinux/avc.c:1029
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
```
**Symbols:**

```
ffffffff8152b1e0-ffffffff8152b667: avc_has_extended_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int avc_has_extended_perms(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, struct common_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff815c0c60)
Location: security/selinux/avc.c:1038
Inline: False
```
**Symbols:**

```
ffffffff815c0c60-ffffffff815c124e: avc_has_extended_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int avc_has_extended_perms(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, struct common_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8166d270)
Location: security/selinux/avc.c:1038
Inline: False
```
**Symbols:**

```
ffffffff8166d270-ffffffff8166d845: avc_has_extended_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int avc_has_extended_perms(u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, struct common_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff816a59b0)
Location: security/selinux/avc.c:1017
Inline: False
```
**Symbols:**

```
ffffffff816a59b0-ffffffff816a5f85: avc_has_extended_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int avc_has_extended_perms(u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, struct common_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff816e23f0)
Location: security/selinux/avc.c:1018
Inline: False
```
**Symbols:**

```
ffffffff816e23f0-ffffffff816e29c5: avc_has_extended_perms (STB_GLOBAL)
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
int avc_has_extended_perms(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, struct common_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffff8000105478e8)
Location: security/selinux/avc.c:1032
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
```
**Symbols:**

```
ffff8000105478e8-ffff800010547c68: avc_has_extended_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int avc_has_extended_perms(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, struct common_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (c06fd4c0)
Location: security/selinux/avc.c:1032
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
```
**Symbols:**

```
c06fd4c0-c06fd8a8: avc_has_extended_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int avc_has_extended_perms(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, struct common_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (c00000000069e800)
Location: security/selinux/avc.c:1032
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
```
**Symbols:**

```
c00000000069e800-c00000000069ecb8: avc_has_extended_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int avc_has_extended_perms(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, struct common_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffe0003a2ed8)
Location: security/selinux/avc.c:1032
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
```
**Symbols:**

```
ffffffe0003a2ed8-ffffffe0003a31c2: avc_has_extended_perms (STB_GLOBAL)
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
int avc_has_extended_perms(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, struct common_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81453560)
Location: security/selinux/avc.c:1032
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
```
**Symbols:**

```
ffffffff81453560-ffffffff81453a32: avc_has_extended_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int avc_has_extended_perms(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, struct common_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81443fa0)
Location: security/selinux/avc.c:1032
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
```
**Symbols:**

```
ffffffff81443fa0-ffffffff81444472: avc_has_extended_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int avc_has_extended_perms(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, struct common_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8144f600)
Location: security/selinux/avc.c:1032
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
```
**Symbols:**

```
ffffffff8144f600-ffffffff8144fad2: avc_has_extended_perms (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int avc_has_extended_perms(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, u8 driver, u8 xperm, struct common_audit_data *ad);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81466a30)
Location: security/selinux/avc.c:1032
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_file_ioctl
```
**Symbols:**

```
ffffffff81466a30-ffffffff81466f19: avc_has_extended_perms (STB_GLOBAL)
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
<code>ssid, tsid, tclass, requested, driver, xperm, ad</code> ➡️ <code>state, ssid, tsid, tclass, requested, driver, xperm, ad</code>
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
<code>state, ssid, tsid, tclass, requested, driver, xperm, ad</code> ➡️ <code>ssid, tsid, tclass, requested, driver, xperm, ad</code>
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
