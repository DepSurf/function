# Function: <code>security_port_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_port_sid(u8 protocol, u16 port, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813585f0)
Location: security/selinux/ss/services.c:2177
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid
```
**Symbols:**

```
ffffffff813585f0-ffffffff81358695: security_port_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_port_sid(u8 protocol, u16 port, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138e540)
Location: security/selinux/ss/services.c:2171
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid
```
**Symbols:**

```
ffffffff8138e540-ffffffff8138e5e5: security_port_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_port_sid(u8 protocol, u16 port, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a5160)
Location: security/selinux/ss/services.c:2171
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid
```
**Symbols:**

```
ffffffff813a5160-ffffffff813a5205: security_port_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_port_sid(u8 protocol, u16 port, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bbad0)
Location: security/selinux/ss/services.c:2206
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid
```
**Symbols:**

```
ffffffff813bbad0-ffffffff813bbb75: security_port_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_port_sid(u8 protocol, u16 port, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e1c40)
Location: security/selinux/ss/services.c:2216
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid
```
**Symbols:**

```
ffffffff813e1c40-ffffffff813e1ce5: security_port_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_port_sid(struct selinux_state *state, u8 protocol, u16 port, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81412970)
Location: security/selinux/ss/services.c:2273
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid
```
**Symbols:**

```
ffffffff81412970-ffffffff81412a21: security_port_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_port_sid(struct selinux_state *state, u8 protocol, u16 port, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142eea0)
Location: security/selinux/ss/services.c:2239
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid
```
**Symbols:**

```
ffffffff8142eea0-ffffffff8142ef54: security_port_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_port_sid(struct selinux_state *state, u8 protocol, u16 port, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145c850)
Location: security/selinux/ss/services.c:2252
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid
```
**Symbols:**

```
ffffffff8145c850-ffffffff8145c904: security_port_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_port_sid(struct selinux_state *state, u8 protocol, u16 port, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81476600)
Location: security/selinux/ss/services.c:2259
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid
```
**Symbols:**

```
ffffffff81476600-ffffffff814766b4: security_port_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_port_sid(struct selinux_state *state, u8 protocol, u16 port, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814cbc50)
Location: security/selinux/ss/services.c:2306
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid_slow
```
**Symbols:**

```
ffffffff814cbc50-ffffffff814cbd0c: security_port_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_port_sid(struct selinux_state *state, u8 protocol, u16 port, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e9080)
Location: security/selinux/ss/services.c:2351
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid_slow
```
**Symbols:**

```
ffffffff814e9080-ffffffff814e9131: security_port_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_port_sid(struct selinux_state *state, u8 protocol, u16 port, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814efb00)
Location: security/selinux/ss/services.c:2378
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid
```
**Symbols:**

```
ffffffff814efb00-ffffffff814efbd6: security_port_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_port_sid(struct selinux_state *state, u8 protocol, u16 port, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2423
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid
```
**Symbols:**

```
ffffffff81cd503d-ffffffff81cd5051: security_port_sid.cold (STB_LOCAL)
ffffffff81549f90-ffffffff8154a093: security_port_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int security_port_sid(struct selinux_state *state, u8 protocol, u16 port, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2425
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid
```
**Symbols:**

```
ffffffff81e87e79-ffffffff81e87e95: security_port_sid.cold (STB_LOCAL)
ffffffff815e2c10-ffffffff815e2d39: security_port_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int security_port_sid(struct selinux_state *state, u8 protocol, u16 port, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2418
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid
```
**Symbols:**

```
ffffffff82073d62-ffffffff82073d7e: security_port_sid.cold (STB_LOCAL)
ffffffff81691e30-ffffffff81691f59: security_port_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int security_port_sid(u8 protocol, u16 port, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2380
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid
```
**Symbols:**

```
ffffffff820f3925-ffffffff820f3939: security_port_sid.cold (STB_LOCAL)
ffffffff816ca3b0-ffffffff816ca4c8: security_port_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int security_port_sid(u8 protocol, u16 port, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2390
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid
```
**Symbols:**

```
ffffffff821d0aeb-ffffffff821d0aff: security_port_sid.cold (STB_LOCAL)
ffffffff81706fc0-ffffffff817070d8: security_port_sid (STB_GLOBAL)
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
int security_port_sid(struct selinux_state *state, u8 protocol, u16 port, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010566040)
Location: security/selinux/ss/services.c:2259
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid
```
**Symbols:**

```
ffff800010566040-ffff800010566174: security_port_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_port_sid(struct selinux_state *state, u8 protocol, u16 port, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c071a778)
Location: security/selinux/ss/services.c:2259
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid
```
**Symbols:**

```
c071a778-c071a868: security_port_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_port_sid(struct selinux_state *state, u8 protocol, u16 port, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c88e0)
Location: security/selinux/ss/services.c:2259
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid
```
**Symbols:**

```
c0000000006c88e0-c0000000006c8a20: security_port_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_port_sid(struct selinux_state *state, u8 protocol, u16 port, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bc2e0)
Location: security/selinux/ss/services.c:2259
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid
```
**Symbols:**

```
ffffffe0003bc2e0-ffffffe0003bc394: security_port_sid (STB_GLOBAL)
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
int security_port_sid(struct selinux_state *state, u8 protocol, u16 port, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146ebe0)
Location: security/selinux/ss/services.c:2259
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid
```
**Symbols:**

```
ffffffff8146ebe0-ffffffff8146ec94: security_port_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_port_sid(struct selinux_state *state, u8 protocol, u16 port, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145f600)
Location: security/selinux/ss/services.c:2259
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid
```
**Symbols:**

```
ffffffff8145f600-ffffffff8145f6b4: security_port_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_port_sid(struct selinux_state *state, u8 protocol, u16 port, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146ac80)
Location: security/selinux/ss/services.c:2259
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid
```
**Symbols:**

```
ffffffff8146ac80-ffffffff8146ad34: security_port_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_port_sid(struct selinux_state *state, u8 protocol, u16 port, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81482410)
Location: security/selinux/ss/services.c:2259
Inline: False
Direct callers:
  - security/selinux/netport.c:sel_netport_sid
```
**Symbols:**

```
ffffffff81482410-ffffffff814824cb: security_port_sid (STB_GLOBAL)
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
<code>protocol, port, out_sid</code> ➡️ <code>state, protocol, port, out_sid</code>
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
<code>state, protocol, port, out_sid</code> ➡️ <code>protocol, port, out_sid</code>
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
