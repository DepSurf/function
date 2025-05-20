# Function: <code>sel_netport_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sel_netport_sid(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffff8134d3c0)
Location: security/selinux/netport.c:197
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_connect
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff8134d3c0-ffffffff8134d598: sel_netport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sel_netport_sid(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffff813833a0)
Location: security/selinux/netport.c:197
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_connect
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff813833a0-ffffffff8138357f: sel_netport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sel_netport_sid(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffff81399e20)
Location: security/selinux/netport.c:197
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_connect
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff81399e20-ffffffff81399fff: sel_netport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sel_netport_sid(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffff813b02c0)
Location: security/selinux/netport.c:197
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_connect
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff813b02c0-ffffffff813b04e0: sel_netport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sel_netport_sid(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffff813d6360)
Location: security/selinux/netport.c:197
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_connect
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff813d6360-ffffffff813d6580: sel_netport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sel_netport_sid(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffff81406980)
Location: security/selinux/netport.c:197
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff81406980-ffffffff81406b8f: sel_netport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sel_netport_sid(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffff814224e0)
Location: security/selinux/netport.c:196
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff814224e0-ffffffff814226f6: sel_netport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sel_netport_sid(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffff81450120)
Location: security/selinux/netport.c:186
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff81450120-ffffffff8145037c: sel_netport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int sel_netport_sid(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netport.c (0)
Location: security/selinux/netport.c:184
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff8146a1e8-ffffffff8146a20c: sel_netport_sid.cold (STB_LOCAL)
ffffffff81469f70-ffffffff8146a13f: sel_netport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sel_netport_sid(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffff814be310)
Location: security/selinux/netport.c:184
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff814be310-ffffffff814be38a: sel_netport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sel_netport_sid(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffff814dbd30)
Location: security/selinux/netport.c:184
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff814dbd30-ffffffff814dbdc2: sel_netport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int sel_netport_sid(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netport.c (0)
Location: security/selinux/netport.c:183
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff81be27ac-ffffffff81be27d0: sel_netport_sid.cold (STB_LOCAL)
ffffffff814e2540-ffffffff814e272a: sel_netport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sel_netport_sid(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netport.c (0)
Location: security/selinux/netport.c:183
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff81cd4215-ffffffff81cd4239: sel_netport_sid.cold (STB_LOCAL)
ffffffff8153b640-ffffffff8153b830: sel_netport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sel_netport_sid(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netport.c (0)
Location: security/selinux/netport.c:183
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff81e871b3-ffffffff81e871dd: sel_netport_sid.cold (STB_LOCAL)
ffffffff815d2e30-ffffffff815d3056: sel_netport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sel_netport_sid(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffff81680df0)
Location: security/selinux/netport.c:183
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff81680df0-ffffffff81681044: sel_netport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sel_netport_sid(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffff816b8ea0)
Location: security/selinux/netport.c:183
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff816b8ea0-ffffffff816b90ff: sel_netport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sel_netport_sid(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffff816f5920)
Location: security/selinux/netport.c:183
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff816f5920-ffffffff816f5bae: sel_netport_sid (STB_GLOBAL)
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
int sel_netport_sid(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffff8000105587f0)
Location: security/selinux/netport.c:184
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffff8000105587f0-ffff800010558a98: sel_netport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sel_netport_sid(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (c070d3b0)
Location: security/selinux/netport.c:184
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_connect_helper
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
c070d3b0-c070d5c8: sel_netport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sel_netport_sid(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (c0000000006b6800)
Location: security/selinux/netport.c:184
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_connect_helper
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
c0000000006b6800-c0000000006b6ac0: sel_netport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sel_netport_sid(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netport.c (ffffffe0003afd32)
Location: security/selinux/netport.c:184
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_connect_helper
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffe0003afd32-ffffffe0003afee8: sel_netport_sid (STB_GLOBAL)
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
int sel_netport_sid(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netport.c (0)
Location: security/selinux/netport.c:184
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff814627c8-ffffffff814627ec: sel_netport_sid.cold (STB_LOCAL)
ffffffff81462550-ffffffff8146271f: sel_netport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int sel_netport_sid(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netport.c (0)
Location: security/selinux/netport.c:184
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff814531f8-ffffffff8145321c: sel_netport_sid.cold (STB_LOCAL)
ffffffff81452f80-ffffffff8145314f: sel_netport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int sel_netport_sid(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netport.c (0)
Location: security/selinux/netport.c:184
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff8145e868-ffffffff8145e88c: sel_netport_sid.cold (STB_LOCAL)
ffffffff8145e5f0-ffffffff8145e7bf: sel_netport_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int sel_netport_sid(u8 protocol, u16 pnum, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netport.c (0)
Location: security/selinux/netport.c:184
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff81476048-ffffffff81476070: sel_netport_sid.cold (STB_LOCAL)
ffffffff81475db0-ffffffff81475f92: sel_netport_sid (STB_GLOBAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
