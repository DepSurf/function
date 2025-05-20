# Function: <code>security_change_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_change_sid(u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81358590)
Location: security/selinux/ss/services.c:1802
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_relabel
```
**Symbols:**

```
ffffffff81358590-ffffffff813585b9: security_change_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_change_sid(u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138e4e0)
Location: security/selinux/ss/services.c:1796
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_relabel
```
**Symbols:**

```
ffffffff8138e4e0-ffffffff8138e509: security_change_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_change_sid(u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a5100)
Location: security/selinux/ss/services.c:1796
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_relabel
```
**Symbols:**

```
ffffffff813a5100-ffffffff813a5129: security_change_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_change_sid(u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bba80)
Location: security/selinux/ss/services.c:1808
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_relabel
```
**Symbols:**

```
ffffffff813bba80-ffffffff813bbaa0: security_change_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_change_sid(u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e1bf0)
Location: security/selinux/ss/services.c:1811
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_relabel
```
**Symbols:**

```
ffffffff813e1bf0-ffffffff813e1c10: security_change_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_change_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814122c0)
Location: security/selinux/ss/services.c:1878
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_relabel
```
**Symbols:**

```
ffffffff814122c0-ffffffff814122fa: security_change_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_change_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142e7e0)
Location: security/selinux/ss/services.c:1871
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_relabel
```
**Symbols:**

```
ffffffff8142e7e0-ffffffff8142e81a: security_change_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_change_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145c160)
Location: security/selinux/ss/services.c:1884
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_relabel
```
**Symbols:**

```
ffffffff8145c160-ffffffff8145c19a: security_change_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_change_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81475f10)
Location: security/selinux/ss/services.c:1884
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_relabel
```
**Symbols:**

```
ffffffff81475f10-ffffffff81475f4a: security_change_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_change_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814cb6c0)
Location: security/selinux/ss/services.c:1933
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_relabel
```
**Symbols:**

```
ffffffff814cb6c0-ffffffff814cb6fc: security_change_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_change_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e8ed0)
Location: security/selinux/ss/services.c:1957
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_relabel
```
**Symbols:**

```
ffffffff814e8ed0-ffffffff814e8f0c: security_change_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_change_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814ef800)
Location: security/selinux/ss/services.c:1976
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_relabel
```
**Symbols:**

```
ffffffff814ef800-ffffffff814ef83c: security_change_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_change_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1986
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_relabel
```
**Symbols:**

```
ffffffff81cd4fc6-ffffffff81cd4fee: security_change_sid.cold (STB_LOCAL)
ffffffff81549bf0-ffffffff81549c68: security_change_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_change_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff815e2890)
Location: security/selinux/ss/services.c:1987
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_relabel
```
**Symbols:**

```
ffffffff815e2890-ffffffff815e28c2: security_change_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_change_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81691690)
Location: security/selinux/ss/services.c:1981
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_relabel
```
**Symbols:**

```
ffffffff81691690-ffffffff816916c2: security_change_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_change_sid(u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816c9c20)
Location: security/selinux/ss/services.c:1951
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_relabel
```
**Symbols:**

```
ffffffff816c9c20-ffffffff816c9c52: security_change_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_change_sid(u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81706830)
Location: security/selinux/ss/services.c:1961
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_relabel
```
**Symbols:**

```
ffffffff81706830-ffffffff81706862: security_change_sid (STB_GLOBAL)
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
int security_change_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff8000105658d8)
Location: security/selinux/ss/services.c:1884
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_relabel
```
**Symbols:**

```
ffff8000105658d8-ffff800010565984: security_change_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_change_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c071a0c8)
Location: security/selinux/ss/services.c:1884
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_relabel
```
**Symbols:**

```
c071a0c8-c071a134: security_change_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_change_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c8070)
Location: security/selinux/ss/services.c:1884
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_relabel
```
**Symbols:**

```
c0000000006c8070-c0000000006c80cc: security_change_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_change_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bbce6)
Location: security/selinux/ss/services.c:1884
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_relabel
```
**Symbols:**

```
ffffffe0003bbce6-ffffffe0003bbd54: security_change_sid (STB_GLOBAL)
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
int security_change_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146e4f0)
Location: security/selinux/ss/services.c:1884
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_relabel
```
**Symbols:**

```
ffffffff8146e4f0-ffffffff8146e52a: security_change_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_change_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145ef20)
Location: security/selinux/ss/services.c:1884
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_relabel
```
**Symbols:**

```
ffffffff8145ef20-ffffffff8145ef5a: security_change_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_change_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146a590)
Location: security/selinux/ss/services.c:1884
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_relabel
```
**Symbols:**

```
ffffffff8146a590-ffffffff8146a5ca: security_change_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_change_sid(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81481d30)
Location: security/selinux/ss/services.c:1884
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_relabel
```
**Symbols:**

```
ffffffff81481d30-ffffffff81481d6a: security_change_sid (STB_GLOBAL)
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
