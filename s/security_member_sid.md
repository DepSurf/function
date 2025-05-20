# Function: <code>security_member_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_member_sid(u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81358560)
Location: security/selinux/ss/services.c:1780
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_member
```
**Symbols:**

```
ffffffff81358560-ffffffff81358589: security_member_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_member_sid(u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138e4b0)
Location: security/selinux/ss/services.c:1774
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_member
```
**Symbols:**

```
ffffffff8138e4b0-ffffffff8138e4d9: security_member_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_member_sid(u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a50d0)
Location: security/selinux/ss/services.c:1774
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_member
```
**Symbols:**

```
ffffffff813a50d0-ffffffff813a50f9: security_member_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_member_sid(u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bba60)
Location: security/selinux/ss/services.c:1786
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_member
```
**Symbols:**

```
ffffffff813bba60-ffffffff813bba80: security_member_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_member_sid(u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e1bd0)
Location: security/selinux/ss/services.c:1789
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_member
```
**Symbols:**

```
ffffffff813e1bd0-ffffffff813e1bf0: security_member_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_member_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81412280)
Location: security/selinux/ss/services.c:1854
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_member
```
**Symbols:**

```
ffffffff81412280-ffffffff814122ba: security_member_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_member_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142e7a0)
Location: security/selinux/ss/services.c:1847
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_member
```
**Symbols:**

```
ffffffff8142e7a0-ffffffff8142e7da: security_member_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_member_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145c120)
Location: security/selinux/ss/services.c:1860
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_member
```
**Symbols:**

```
ffffffff8145c120-ffffffff8145c15a: security_member_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_member_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81475ed0)
Location: security/selinux/ss/services.c:1860
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_member
```
**Symbols:**

```
ffffffff81475ed0-ffffffff81475f0a: security_member_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_member_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814cb680)
Location: security/selinux/ss/services.c:1909
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_member
```
**Symbols:**

```
ffffffff814cb680-ffffffff814cb6bc: security_member_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_member_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e8e90)
Location: security/selinux/ss/services.c:1933
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_member
```
**Symbols:**

```
ffffffff814e8e90-ffffffff814e8ecc: security_member_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_member_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814ef7c0)
Location: security/selinux/ss/services.c:1952
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_member
```
**Symbols:**

```
ffffffff814ef7c0-ffffffff814ef7fc: security_member_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_member_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1961
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_member
```
**Symbols:**

```
ffffffff81cd4f9e-ffffffff81cd4fc6: security_member_sid.cold (STB_LOCAL)
ffffffff81549b70-ffffffff81549be8: security_member_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_member_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff815e2850)
Location: security/selinux/ss/services.c:1962
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_member
```
**Symbols:**

```
ffffffff815e2850-ffffffff815e2882: security_member_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_member_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81691640)
Location: security/selinux/ss/services.c:1956
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_member
```
**Symbols:**

```
ffffffff81691640-ffffffff81691672: security_member_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_member_sid(u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816c9bd0)
Location: security/selinux/ss/services.c:1928
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_member
```
**Symbols:**

```
ffffffff816c9bd0-ffffffff816c9c02: security_member_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_member_sid(u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff817067e0)
Location: security/selinux/ss/services.c:1938
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_member
```
**Symbols:**

```
ffffffff817067e0-ffffffff81706812: security_member_sid (STB_GLOBAL)
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
int security_member_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010565828)
Location: security/selinux/ss/services.c:1860
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_member
```
**Symbols:**

```
ffff800010565828-ffff8000105658d4: security_member_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_member_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c071a05c)
Location: security/selinux/ss/services.c:1860
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_member
```
**Symbols:**

```
c071a05c-c071a0c8: security_member_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_member_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c8010)
Location: security/selinux/ss/services.c:1860
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_member
```
**Symbols:**

```
c0000000006c8010-c0000000006c806c: security_member_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_member_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bbc78)
Location: security/selinux/ss/services.c:1860
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_member
```
**Symbols:**

```
ffffffe0003bbc78-ffffffe0003bbce6: security_member_sid (STB_GLOBAL)
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
int security_member_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146e4b0)
Location: security/selinux/ss/services.c:1860
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_member
```
**Symbols:**

```
ffffffff8146e4b0-ffffffff8146e4ea: security_member_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_member_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145eee0)
Location: security/selinux/ss/services.c:1860
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_member
```
**Symbols:**

```
ffffffff8145eee0-ffffffff8145ef1a: security_member_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_member_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146a550)
Location: security/selinux/ss/services.c:1860
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_member
```
**Symbols:**

```
ffffffff8146a550-ffffffff8146a58a: security_member_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_member_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81481cf0)
Location: security/selinux/ss/services.c:1860
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_member
```
**Symbols:**

```
ffffffff81481cf0-ffffffff81481d2a: security_member_sid (STB_GLOBAL)
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
<code>ssid, tsid, tclass, out_sid</code> ➡️ <code>state, ssid, tsid, tclass, out_sid</code>
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
<code>state, ssid, tsid, tclass, out_sid</code> ➡️ <code>ssid, tsid, tclass, out_sid</code>
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
