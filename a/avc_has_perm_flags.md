# Function: <code>avc_has_perm_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int avc_has_perm_flags(u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81341680)
Location: security/selinux/avc.c:1156
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
ffffffff81341680-ffffffff8134182a: avc_has_perm_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int avc_has_perm_flags(u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81376d20)
Location: security/selinux/avc.c:1156
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
ffffffff81376d20-ffffffff81376ec5: avc_has_perm_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int avc_has_perm_flags(u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8138d650)
Location: security/selinux/avc.c:1156
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
ffffffff8138d650-ffffffff8138d7f5: avc_has_perm_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int avc_has_perm_flags(u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813a3340)
Location: security/selinux/avc.c:1156
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
ffffffff813a3340-ffffffff813a34d7: avc_has_perm_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int avc_has_perm_flags(u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813c9140)
Location: security/selinux/avc.c:1152
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
ffffffff813c9140-ffffffff813c92d7: avc_has_perm_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int avc_has_perm_flags(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff813f8950)
Location: security/selinux/avc.c:1194
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
ffffffff813f8950-ffffffff813f8b0e: avc_has_perm_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int avc_has_perm_flags(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81414400)
Location: security/selinux/avc.c:1194
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
ffffffff81414400-ffffffff814145be: avc_has_perm_flags (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int avc_has_perm_flags(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8145b770)
Location: security/selinux/avc.c:1192
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
ffffffff8145b770-ffffffff8145b95d: avc_has_perm_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int avc_has_perm_flags(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814ae980)
Location: security/selinux/avc.c:1192
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
ffffffff814ae980-ffffffff814aeb15: avc_has_perm_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int avc_has_perm_flags(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814cc460)
Location: security/selinux/avc.c:1199
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
ffffffff814cc460-ffffffff814cc60a: avc_has_perm_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int avc_has_perm_flags(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff814d2a90)
Location: security/selinux/avc.c:1200
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
ffffffff814d2a90-ffffffff814d2c3a: avc_has_perm_flags (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int avc_has_perm_flags(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffff800010547f28)
Location: security/selinux/avc.c:1192
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
ffff800010547f28-ffff800010548100: avc_has_perm_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int avc_has_perm_flags(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (c06fdb78)
Location: security/selinux/avc.c:1192
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
c06fdb78-c06fdd40: avc_has_perm_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int avc_has_perm_flags(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (c00000000069f090)
Location: security/selinux/avc.c:1192
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
c00000000069f090-c00000000069f2f4: avc_has_perm_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int avc_has_perm_flags(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffe0003a3390)
Location: security/selinux/avc.c:1192
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
ffffffe0003a3390-ffffffe0003a34cc: avc_has_perm_flags (STB_GLOBAL)
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
int avc_has_perm_flags(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81453d50)
Location: security/selinux/avc.c:1192
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
ffffffff81453d50-ffffffff81453f3d: avc_has_perm_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int avc_has_perm_flags(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81444790)
Location: security/selinux/avc.c:1192
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
ffffffff81444790-ffffffff8144497d: avc_has_perm_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int avc_has_perm_flags(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff8144fdf0)
Location: security/selinux/avc.c:1192
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
ffffffff8144fdf0-ffffffff8144ffdd: avc_has_perm_flags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int avc_has_perm_flags(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 requested, struct common_audit_data *auditdata, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/avc.c (ffffffff81467290)
Location: security/selinux/avc.c:1192
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_follow_link
```
**Symbols:**

```
ffffffff81467290-ffffffff814674ae: avc_has_perm_flags (STB_GLOBAL)
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
<code>ssid, tsid, tclass, requested, auditdata, flags</code> ➡️ <code>state, ssid, tsid, tclass, requested, auditdata, flags</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
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
