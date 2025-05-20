# Function: <code>security_compute_av_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void security_compute_av_user(u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813582d0)
Location: security/selinux/ss/services.c:1133
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_access
```
**Symbols:**

```
ffffffff813582d0-ffffffff813583ef: security_compute_av_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void security_compute_av_user(u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138e220)
Location: security/selinux/ss/services.c:1127
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_access
```
**Symbols:**

```
ffffffff8138e220-ffffffff8138e33f: security_compute_av_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void security_compute_av_user(u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a4e40)
Location: security/selinux/ss/services.c:1127
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_access
```
**Symbols:**

```
ffffffff813a4e40-ffffffff813a4f5f: security_compute_av_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void security_compute_av_user(u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bb7f0)
Location: security/selinux/ss/services.c:1139
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_access
```
**Symbols:**

```
ffffffff813bb7f0-ffffffff813bb909: security_compute_av_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void security_compute_av_user(u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e1960)
Location: security/selinux/ss/services.c:1144
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_access
```
**Symbols:**

```
ffffffff813e1960-ffffffff813e1a79: security_compute_av_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void security_compute_av_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1166
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_access
```
**Symbols:**

```
ffffffff81414cca-ffffffff81414d00: security_compute_av_user.cold.36 (STB_LOCAL)
ffffffff81411f70-ffffffff81412081: security_compute_av_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void security_compute_av_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1163
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_access
```
**Symbols:**

```
ffffffff81431280-ffffffff814312b6: security_compute_av_user.cold.36 (STB_LOCAL)
ffffffff8142e490-ffffffff8142e5aa: security_compute_av_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void security_compute_av_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1149
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_access
```
**Symbols:**

```
ffffffff8145ed19-ffffffff8145ed4f: security_compute_av_user.cold (STB_LOCAL)
ffffffff8145bdd0-ffffffff8145bef5: security_compute_av_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void security_compute_av_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1149
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_access
```
**Symbols:**

```
ffffffff81478acb-ffffffff81478b01: security_compute_av_user.cold (STB_LOCAL)
ffffffff81475b80-ffffffff81475ca5: security_compute_av_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void security_compute_av_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1156
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_access
```
**Symbols:**

```
ffffffff814cdf82-ffffffff814cdfb8: security_compute_av_user.cold (STB_LOCAL)
ffffffff814cb330-ffffffff814cb45d: security_compute_av_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void security_compute_av_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1167
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_access
```
**Symbols:**

```
ffffffff81bf0fd4-ffffffff81bf1009: security_compute_av_user.cold (STB_LOCAL)
ffffffff814e8b80-ffffffff814e8c8c: security_compute_av_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void security_compute_av_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1169
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_access
```
**Symbols:**

```
ffffffff81be30f6-ffffffff81be312b: security_compute_av_user.cold (STB_LOCAL)
ffffffff814ef4b0-ffffffff814ef5bf: security_compute_av_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void security_compute_av_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1171
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_access
```
**Symbols:**

```
ffffffff81cd4eb8-ffffffff81cd4f0b: security_compute_av_user.cold (STB_LOCAL)
ffffffff81549790-ffffffff815498b4: security_compute_av_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void security_compute_av_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1169
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_access
```
**Symbols:**

```
ffffffff81e87dad-ffffffff81e87df8: security_compute_av_user.cold (STB_LOCAL)
ffffffff815e2460-ffffffff815e259b: security_compute_av_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void security_compute_av_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1163
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_access
```
**Symbols:**

```
ffffffff82073d0f-ffffffff82073d24: security_compute_av_user.cold (STB_LOCAL)
ffffffff81691160-ffffffff816912b7: security_compute_av_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void security_compute_av_user(u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1153
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_access
```
**Symbols:**

```
ffffffff820f38d2-ffffffff820f38e7: security_compute_av_user.cold (STB_LOCAL)
ffffffff816c9700-ffffffff816c985a: security_compute_av_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void security_compute_av_user(u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1153
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_access
```
**Symbols:**

```
ffffffff821d0a98-ffffffff821d0aad: security_compute_av_user.cold (STB_LOCAL)
ffffffff81706310-ffffffff8170646a: security_compute_av_user (STB_GLOBAL)
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
void security_compute_av_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff8000105651e0)
Location: security/selinux/ss/services.c:1149
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_access
```
**Symbols:**

```
ffff8000105651e0-ffff8000105653c8: security_compute_av_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void security_compute_av_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0719c44)
Location: security/selinux/ss/services.c:1149
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_access
```
**Symbols:**

```
c0719c44-c0719dbc: security_compute_av_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void security_compute_av_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c7b30)
Location: security/selinux/ss/services.c:1149
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_access
```
**Symbols:**

```
c0000000006c7b30-c0000000006c7d00: security_compute_av_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void security_compute_av_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bb7e2)
Location: security/selinux/ss/services.c:1149
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_access
```
**Symbols:**

```
ffffffe0003bb7e2-ffffffe0003bb910: security_compute_av_user (STB_GLOBAL)
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
void security_compute_av_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1149
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_access
```
**Symbols:**

```
ffffffff814710ab-ffffffff814710e1: security_compute_av_user.cold (STB_LOCAL)
ffffffff8146e160-ffffffff8146e285: security_compute_av_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void security_compute_av_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1149
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_access
```
**Symbols:**

```
ffffffff81461acb-ffffffff81461b01: security_compute_av_user.cold (STB_LOCAL)
ffffffff8145eb90-ffffffff8145ecb5: security_compute_av_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void security_compute_av_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1149
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_access
```
**Symbols:**

```
ffffffff8146d14b-ffffffff8146d181: security_compute_av_user.cold (STB_LOCAL)
ffffffff8146a200-ffffffff8146a325: security_compute_av_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void security_compute_av_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, struct av_decision *avd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1149
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_access
```
**Symbols:**

```
ffffffff814849b7-ffffffff814849ed: security_compute_av_user.cold (STB_LOCAL)
ffffffff814819a0-ffffffff81481ac4: security_compute_av_user (STB_GLOBAL)
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
<code>ssid, tsid, tclass, avd</code> ➡️ <code>state, ssid, tsid, tclass, avd</code>
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
<code>state, ssid, tsid, tclass, avd</code> ➡️ <code>ssid, tsid, tclass, avd</code>
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
