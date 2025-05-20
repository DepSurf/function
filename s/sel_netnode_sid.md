# Function: <code>sel_netnode_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sel_netnode_sid(void *addr, u16 family, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff8134d140)
Location: security/selinux/netnode.c:263
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_socket_bind
  - security/selinux/hooks.c:selinux_ip_postroute
```
**Symbols:**

```
ffffffff8134d140-ffffffff8134d31b: sel_netnode_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sel_netnode_sid(void *addr, u16 family, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff81383110)
Location: security/selinux/netnode.c:263
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff81383110-ffffffff813832f6: sel_netnode_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sel_netnode_sid(void *addr, u16 family, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff81399b90)
Location: security/selinux/netnode.c:263
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff81399b90-ffffffff81399d76: sel_netnode_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sel_netnode_sid(void *addr, u16 family, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff813b0010)
Location: security/selinux/netnode.c:263
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff813b0010-ffffffff813b0220: sel_netnode_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sel_netnode_sid(void *addr, u16 family, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff813d60b0)
Location: security/selinux/netnode.c:263
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff813d60b0-ffffffff813d62c0: sel_netnode_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sel_netnode_sid(void *addr, u16 family, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff814066c0)
Location: security/selinux/netnode.c:263
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff814066c0-ffffffff814068d5: sel_netnode_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sel_netnode_sid(void *addr, u16 family, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff81422220)
Location: security/selinux/netnode.c:262
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff81422220-ffffffff8142243c: sel_netnode_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sel_netnode_sid(void *addr, u16 family, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff8144fe30)
Location: security/selinux/netnode.c:252
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff8144fe30-ffffffff8145006d: sel_netnode_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int sel_netnode_sid(void *addr, u16 family, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netnode.c (0)
Location: security/selinux/netnode.c:250
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff81469f38-ffffffff81469f64: sel_netnode_sid.cold (STB_LOCAL)
ffffffff81469c80-ffffffff81469e82: sel_netnode_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int sel_netnode_sid(void *addr, u16 family, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netnode.c (0)
Location: security/selinux/netnode.c:250
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff814be148-ffffffff814be174: sel_netnode_sid.cold (STB_LOCAL)
ffffffff814bde90-ffffffff814be094: sel_netnode_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sel_netnode_sid(void *addr, u16 family, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netnode.c (0)
Location: security/selinux/netnode.c:250
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff81bf0636-ffffffff81bf0662: sel_netnode_sid.cold (STB_LOCAL)
ffffffff814db8c0-ffffffff814dbae4: sel_netnode_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sel_netnode_sid(void *addr, u16 family, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff814e2430)
Location: security/selinux/netnode.c:249
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff814e2430-ffffffff814e2487: sel_netnode_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sel_netnode_sid(void *addr, u16 family, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netnode.c (0)
Location: security/selinux/netnode.c:249
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff81cd41e9-ffffffff81cd4215: sel_netnode_sid.cold (STB_LOCAL)
ffffffff8153b2b0-ffffffff8153b4de: sel_netnode_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sel_netnode_sid(void *addr, u16 family, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff815d2a60)
Location: security/selinux/netnode.c:250
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff815d2a60-ffffffff815d2cb4: sel_netnode_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sel_netnode_sid(void *addr, u16 family, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff81680a00)
Location: security/selinux/netnode.c:250
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff81680a00-ffffffff81680c54: sel_netnode_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sel_netnode_sid(void *addr, u16 family, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff816b8ac0)
Location: security/selinux/netnode.c:250
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff816b8ac0-ffffffff816b8d09: sel_netnode_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sel_netnode_sid(void *addr, u16 family, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffff816f5510)
Location: security/selinux/netnode.c:250
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff816f5510-ffffffff816f5788: sel_netnode_sid (STB_GLOBAL)
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
int sel_netnode_sid(void *addr, u16 family, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffff8000105583c8)
Location: security/selinux/netnode.c:250
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffff8000105583c8-ffff800010558684: sel_netnode_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sel_netnode_sid(void *addr, u16 family, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (c070d10c)
Location: security/selinux/netnode.c:250
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
c070d10c-c070d310: sel_netnode_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sel_netnode_sid(void *addr, u16 family, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (c0000000006b63e0)
Location: security/selinux/netnode.c:250
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
c0000000006b63e0-c0000000006b66dc: sel_netnode_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sel_netnode_sid(void *addr, u16 family, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netnode.c (ffffffe0003afaa4)
Location: security/selinux/netnode.c:250
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffe0003afaa4-ffffffe0003afc8c: sel_netnode_sid (STB_GLOBAL)
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
int sel_netnode_sid(void *addr, u16 family, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netnode.c (0)
Location: security/selinux/netnode.c:250
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff81462518-ffffffff81462544: sel_netnode_sid.cold (STB_LOCAL)
ffffffff81462260-ffffffff81462462: sel_netnode_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int sel_netnode_sid(void *addr, u16 family, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netnode.c (0)
Location: security/selinux/netnode.c:250
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff81452f48-ffffffff81452f74: sel_netnode_sid.cold (STB_LOCAL)
ffffffff81452c90-ffffffff81452e92: sel_netnode_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int sel_netnode_sid(void *addr, u16 family, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netnode.c (0)
Location: security/selinux/netnode.c:250
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff8145e5b8-ffffffff8145e5e4: sel_netnode_sid.cold (STB_LOCAL)
ffffffff8145e300-ffffffff8145e502: sel_netnode_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int sel_netnode_sid(void *addr, u16 family, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netnode.c (0)
Location: security/selinux/netnode.c:250
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_socket_bind
```
**Symbols:**

```
ffffffff81475d78-ffffffff81475da4: sel_netnode_sid.cold (STB_LOCAL)
ffffffff81475aa0-ffffffff81475cc2: sel_netnode_sid (STB_GLOBAL)
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
