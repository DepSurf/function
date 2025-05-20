# Function: <code>security_transition_sid_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_transition_sid_user(u32 ssid, u32 tsid, u16 tclass, const char *objname, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81358530)
Location: security/selinux/ss/services.c:1760
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
ffffffff81358530-ffffffff81358559: security_transition_sid_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_transition_sid_user(u32 ssid, u32 tsid, u16 tclass, const char *objname, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138e480)
Location: security/selinux/ss/services.c:1754
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
ffffffff8138e480-ffffffff8138e4a9: security_transition_sid_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_transition_sid_user(u32 ssid, u32 tsid, u16 tclass, const char *objname, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a50a0)
Location: security/selinux/ss/services.c:1754
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
ffffffff813a50a0-ffffffff813a50c9: security_transition_sid_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_transition_sid_user(u32 ssid, u32 tsid, u16 tclass, const char *objname, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bba40)
Location: security/selinux/ss/services.c:1766
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
ffffffff813bba40-ffffffff813bba60: security_transition_sid_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_transition_sid_user(u32 ssid, u32 tsid, u16 tclass, const char *objname, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e1bb0)
Location: security/selinux/ss/services.c:1769
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
ffffffff813e1bb0-ffffffff813e1bd0: security_transition_sid_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_transition_sid_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const char *objname, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81412240)
Location: security/selinux/ss/services.c:1832
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
ffffffff81412240-ffffffff8141227c: security_transition_sid_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_transition_sid_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const char *objname, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142e760)
Location: security/selinux/ss/services.c:1825
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
ffffffff8142e760-ffffffff8142e79c: security_transition_sid_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_transition_sid_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const char *objname, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145c0e0)
Location: security/selinux/ss/services.c:1838
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
ffffffff8145c0e0-ffffffff8145c11a: security_transition_sid_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_transition_sid_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const char *objname, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81475e90)
Location: security/selinux/ss/services.c:1838
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
ffffffff81475e90-ffffffff81475eca: security_transition_sid_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_transition_sid_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const char *objname, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814cb640)
Location: security/selinux/ss/services.c:1887
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
ffffffff814cb640-ffffffff814cb67c: security_transition_sid_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_transition_sid_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const char *objname, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e8e50)
Location: security/selinux/ss/services.c:1911
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
ffffffff814e8e50-ffffffff814e8e8c: security_transition_sid_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_transition_sid_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const char *objname, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814ef780)
Location: security/selinux/ss/services.c:1930
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
ffffffff814ef780-ffffffff814ef7bc: security_transition_sid_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_transition_sid_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const char *objname, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:1939
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
ffffffff81cd4f6e-ffffffff81cd4f9e: security_transition_sid_user.cold (STB_LOCAL)
ffffffff81549af0-ffffffff81549b68: security_transition_sid_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_transition_sid_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const char *objname, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff815e2810)
Location: security/selinux/ss/services.c:1939
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
ffffffff815e2810-ffffffff815e2842: security_transition_sid_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_transition_sid_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const char *objname, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816915f0)
Location: security/selinux/ss/services.c:1933
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
ffffffff816915f0-ffffffff81691622: security_transition_sid_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_transition_sid_user(u32 ssid, u32 tsid, u16 tclass, const char *objname, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff816c9b80)
Location: security/selinux/ss/services.c:1907
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
ffffffff816c9b80-ffffffff816c9bb2: security_transition_sid_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_transition_sid_user(u32 ssid, u32 tsid, u16 tclass, const char *objname, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81706790)
Location: security/selinux/ss/services.c:1917
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
ffffffff81706790-ffffffff817067c2: security_transition_sid_user (STB_GLOBAL)
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
int security_transition_sid_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const char *objname, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010565778)
Location: security/selinux/ss/services.c:1838
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
ffff800010565778-ffff800010565828: security_transition_sid_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_transition_sid_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const char *objname, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0719fec)
Location: security/selinux/ss/services.c:1838
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
c0719fec-c071a05c: security_transition_sid_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_transition_sid_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const char *objname, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c7fb0)
Location: security/selinux/ss/services.c:1838
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
c0000000006c7fb0-c0000000006c800c: security_transition_sid_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_transition_sid_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const char *objname, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bbc06)
Location: security/selinux/ss/services.c:1838
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
ffffffe0003bbc06-ffffffe0003bbc78: security_transition_sid_user (STB_GLOBAL)
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
int security_transition_sid_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const char *objname, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146e470)
Location: security/selinux/ss/services.c:1838
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
ffffffff8146e470-ffffffff8146e4aa: security_transition_sid_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_transition_sid_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const char *objname, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145eea0)
Location: security/selinux/ss/services.c:1838
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
ffffffff8145eea0-ffffffff8145eeda: security_transition_sid_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_transition_sid_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const char *objname, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146a510)
Location: security/selinux/ss/services.c:1838
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
ffffffff8146a510-ffffffff8146a54a: security_transition_sid_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_transition_sid_user(struct selinux_state *state, u32 ssid, u32 tsid, u16 tclass, const char *objname, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81481cb0)
Location: security/selinux/ss/services.c:1838
Inline: False
Direct callers:
  - security/selinux/selinuxfs.c:sel_write_create
```
**Symbols:**

```
ffffffff81481cb0-ffffffff81481cea: security_transition_sid_user (STB_GLOBAL)
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
<code>ssid, tsid, tclass, objname, out_sid</code> ➡️ <code>state, ssid, tsid, tclass, objname, out_sid</code>
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
<code>state, ssid, tsid, tclass, objname, out_sid</code> ➡️ <code>ssid, tsid, tclass, objname, out_sid</code>
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
