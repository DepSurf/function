# Function: <code>security_compute_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int security_compute_sid(u32 ssid, u32 tsid, u16 orig_tclass, u32 specified, const char *objname, u32 *out_sid, bool kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81355a70)
Location: security/selinux/ss/services.c:1568
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_transition_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_change_sid
```
**Symbols:**

```
ffffffff81355a70-ffffffff8135600a: security_compute_sid.part.12 (STB_LOCAL)
ffffffff81356010-ffffffff81356050: security_compute_sid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int security_compute_sid(u32 ssid, u32 tsid, u16 orig_tclass, u32 specified, const char *objname, u32 *out_sid, bool kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138b790)
Location: security/selinux/ss/services.c:1562
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
```
**Symbols:**

```
ffffffff8138b790-ffffffff8138bd22: security_compute_sid.part.13 (STB_LOCAL)
ffffffff8138bd30-ffffffff8138bd69: security_compute_sid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int security_compute_sid(u32 ssid, u32 tsid, u16 orig_tclass, u32 specified, const char *objname, u32 *out_sid, bool kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a23a0)
Location: security/selinux/ss/services.c:1562
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
```
**Symbols:**

```
ffffffff813a23a0-ffffffff813a2932: security_compute_sid.part.13 (STB_LOCAL)
ffffffff813a2940-ffffffff813a2979: security_compute_sid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int security_compute_sid(u32 ssid, u32 tsid, u16 orig_tclass, u32 specified, const char *objname, u32 *out_sid, bool kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813b9870)
Location: security/selinux/ss/services.c:1574
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
```
**Symbols:**

```
ffffffff813b9870-ffffffff813b9df8: security_compute_sid.part.13 (STB_LOCAL)
ffffffff813b9e00-ffffffff813b9e34: security_compute_sid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int security_compute_sid(u32 ssid, u32 tsid, u16 orig_tclass, u32 specified, const char *objname, u32 *out_sid, bool kern);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813dfc30)
Location: security/selinux/ss/services.c:1577
Inline: True
Direct callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
```
**Symbols:**

```
ffffffff813dfc30-ffffffff813e01c3: security_compute_sid.part.12 (STB_LOCAL)
ffffffff813e01d0-ffffffff813e0204: security_compute_sid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814122c5)
Location: security/selinux/ss/services.c:1630
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
Direct callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
```
**Symbols:**

```
ffffffff8140fdc0-ffffffff81410341: security_compute_sid.part.17 (STB_LOCAL)
ffffffff81414a6d-ffffffff81414ab5: security_compute_sid.part.17.cold.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142e7e5)
Location: security/selinux/ss/services.c:1623
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
Direct callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
```
**Symbols:**

```
ffffffff8142c5e0-ffffffff8142ccb0: security_compute_sid.part.17 (STB_LOCAL)
ffffffff81431050-ffffffff81431096: security_compute_sid.part.17.cold.29 (STB_LOCAL)
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
In security/selinux/ss/services.c (ffffffff8145c165)
Location: security/selinux/ss/services.c:1636
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
Direct callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
```
**Symbols:**

```
ffffffff81459d80-ffffffff8145a3b5: security_compute_sid.part.0 (STB_LOCAL)
ffffffff8145ea82-ffffffff8145eac7: security_compute_sid.part.0.cold (STB_LOCAL)
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
In security/selinux/ss/services.c (ffffffff81475f15)
Location: security/selinux/ss/services.c:1636
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
Direct callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
```
**Symbols:**

```
ffffffff81473b20-ffffffff81474155: security_compute_sid.part.0 (STB_LOCAL)
ffffffff81478832-ffffffff81478877: security_compute_sid.part.0.cold (STB_LOCAL)
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
In security/selinux/ss/services.c (ffffffff814cb6c5)
Location: security/selinux/ss/services.c:1684
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
Direct callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
```
**Symbols:**

```
ffffffff814c95b0-ffffffff814c9c5f: security_compute_sid.part.0 (STB_LOCAL)
ffffffff814cdd60-ffffffff814cdda5: security_compute_sid.part.0.cold (STB_LOCAL)
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
In security/selinux/ss/services.c (ffffffff814e8ed5)
Location: security/selinux/ss/services.c:1704
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
Direct callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
```
**Symbols:**

```
ffffffff814e6930-ffffffff814e6fab: security_compute_sid.part.0 (STB_LOCAL)
ffffffff81bf0d74-ffffffff81bf0db9: security_compute_sid.part.0.cold (STB_LOCAL)
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
In security/selinux/ss/services.c (ffffffff814ef805)
Location: security/selinux/ss/services.c:1716
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
Direct callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
```
**Symbols:**

```
ffffffff814ed390-ffffffff814edbeb: security_compute_sid.part.0 (STB_LOCAL)
ffffffff81be2eeb-ffffffff81be2f31: security_compute_sid.part.0.cold (STB_LOCAL)
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
In security/selinux/ss/services.c (ffffffff81549bfe)
Location: security/selinux/ss/services.c:1724
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
Direct callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
```
**Symbols:**

```
ffffffff815477d0-ffffffff81547f1e: security_compute_sid.part.0 (STB_LOCAL)
ffffffff81cd4b4f-ffffffff81cd4b95: security_compute_sid.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int security_compute_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, u32 specified, const char *objname, u32 *out_sid, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1723
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
```
**Symbols:**

```
ffffffff815df880-ffffffff815e0036: security_compute_sid (STB_LOCAL)
ffffffff81e87a39-ffffffff81e87ad0: security_compute_sid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int security_compute_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 orig_tclass, u32 specified, const char *objname, u32 *out_sid, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1717
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
```
**Symbols:**

```
ffffffff8168e0d0-ffffffff8168e8cb: security_compute_sid (STB_LOCAL)
ffffffff82073bdf-ffffffff82073c39: security_compute_sid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int security_compute_sid(u32 ssid, u32 tsid, u16 orig_tclass, u32 specified, const char *objname, u32 *out_sid, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1694
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
```
**Symbols:**

```
ffffffff816c7550-ffffffff816c7cd4: security_compute_sid (STB_LOCAL)
ffffffff820f37d0-ffffffff820f3828: security_compute_sid.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int security_compute_sid(u32 ssid, u32 tsid, u16 orig_tclass, u16 specified, const char *objname, u32 *out_sid, bool kern);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1705
Inline: False
Direct callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
```
**Symbols:**

```
ffffffff81704160-ffffffff817048f0: security_compute_sid (STB_LOCAL)
ffffffff821d0996-ffffffff821d09ee: security_compute_sid.cold (STB_LOCAL)
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
In security/selinux/ss/services.c (ffff800010565908)
Location: security/selinux/ss/services.c:1636
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
Direct callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
```
**Symbols:**

```
ffff8000105633f0-ffff8000105639a0: security_compute_sid.part.0 (STB_LOCAL)
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
In security/selinux/ss/services.c (c071a0e0)
Location: security/selinux/ss/services.c:1636
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
Direct callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
```
**Symbols:**

```
c0717778-c071801c: security_compute_sid.part.0 (STB_LOCAL)
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
In security/selinux/ss/services.c (c0000000006c8080)
Location: security/selinux/ss/services.c:1636
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
Direct callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
```
**Symbols:**

```
c0000000006c4de0-c0000000006c56e0: security_compute_sid.part.0 (STB_LOCAL)
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
In security/selinux/ss/services.c (ffffffe0003bbd0c)
Location: security/selinux/ss/services.c:1636
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
Direct callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
```
**Symbols:**

```
ffffffe0003b9778-ffffffe0003b9bfe: security_compute_sid.part.0 (STB_LOCAL)
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
In security/selinux/ss/services.c (ffffffff8146e4f5)
Location: security/selinux/ss/services.c:1636
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
Direct callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
```
**Symbols:**

```
ffffffff8146c100-ffffffff8146c735: security_compute_sid.part.0 (STB_LOCAL)
ffffffff81470e12-ffffffff81470e57: security_compute_sid.part.0.cold (STB_LOCAL)
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
In security/selinux/ss/services.c (ffffffff8145ef25)
Location: security/selinux/ss/services.c:1636
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
Direct callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
```
**Symbols:**

```
ffffffff8145cb30-ffffffff8145d165: security_compute_sid.part.0 (STB_LOCAL)
ffffffff81461832-ffffffff81461877: security_compute_sid.part.0.cold (STB_LOCAL)
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
In security/selinux/ss/services.c (ffffffff8146a595)
Location: security/selinux/ss/services.c:1636
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
Direct callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
```
**Symbols:**

```
ffffffff814681a0-ffffffff814687d5: security_compute_sid.part.0 (STB_LOCAL)
ffffffff8146ceb2-ffffffff8146cef7: security_compute_sid.part.0.cold (STB_LOCAL)
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
In security/selinux/ss/services.c (ffffffff81481d35)
Location: security/selinux/ss/services.c:1636
Inline: True
Inline callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
Direct callers:
  - security/selinux/ss/services.c:security_change_sid
  - security/selinux/ss/services.c:security_member_sid
  - security/selinux/ss/services.c:security_transition_sid_user
  - security/selinux/ss/services.c:security_transition_sid
```
**Symbols:**

```
ffffffff8147f960-ffffffff8147ff94: security_compute_sid.part.0 (STB_LOCAL)
ffffffff8148471e-ffffffff81484763: security_compute_sid.part.0.cold (STB_LOCAL)
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
<code>state, ssid, tsid, orig_tclass, specified, objname, out_sid, kern</code> ➡️ <code>ssid, tsid, orig_tclass, specified, objname, out_sid, kern</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u32 specified</code> ➡️ <code>u16 specified</code>
</li>
</ul>
</details>
</li>
</ul>
