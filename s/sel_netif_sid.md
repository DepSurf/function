# Function: <code>sel_netif_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sel_netif_sid(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netif.c (ffffffff8134ce70)
Location: security/selinux/netif.c:203
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
**Symbols:**

```
ffffffff8134ce70-ffffffff8134d041: sel_netif_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sel_netif_sid(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netif.c (ffffffff81382e20)
Location: security/selinux/netif.c:203
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
**Symbols:**

```
ffffffff81382e20-ffffffff8138300a: sel_netif_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sel_netif_sid(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netif.c (ffffffff813998a0)
Location: security/selinux/netif.c:203
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
**Symbols:**

```
ffffffff813998a0-ffffffff81399a8a: sel_netif_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sel_netif_sid(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netif.c (ffffffff813afcb0)
Location: security/selinux/netif.c:203
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
**Symbols:**

```
ffffffff813afcb0-ffffffff813aff0a: sel_netif_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sel_netif_sid(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netif.c (ffffffff813d5d60)
Location: security/selinux/netif.c:203
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
**Symbols:**

```
ffffffff813d5d60-ffffffff813d5fba: sel_netif_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int sel_netif_sid(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netif.c (0)
Location: security/selinux/netif.c:203
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
**Symbols:**

```
ffffffff8140660e-ffffffff81406627: sel_netif_sid.cold.7 (STB_LOCAL)
ffffffff81406370-ffffffff814065aa: sel_netif_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int sel_netif_sid(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netif.c (0)
Location: security/selinux/netif.c:200
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
**Symbols:**

```
ffffffff8142216e-ffffffff8142218f: sel_netif_sid.cold.6 (STB_LOCAL)
ffffffff81421ec0-ffffffff8142210a: sel_netif_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int sel_netif_sid(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netif.c (0)
Location: security/selinux/netif.c:197
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
**Symbols:**

```
ffffffff8144fd66-ffffffff8144fd87: sel_netif_sid.cold (STB_LOCAL)
ffffffff8144fac0-ffffffff8144fd10: sel_netif_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int sel_netif_sid(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netif.c (0)
Location: security/selinux/netif.c:192
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
**Symbols:**

```
ffffffff81469b76-ffffffff81469bd3: sel_netif_sid.cold (STB_LOCAL)
ffffffff81469930-ffffffff81469b1b: sel_netif_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sel_netif_sid(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netif.c (ffffffff814bdcb0)
Location: security/selinux/netif.c:192
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
```
**Symbols:**

```
ffffffff814bdcb0-ffffffff814bdd0f: sel_netif_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sel_netif_sid(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netif.c (ffffffff814db710)
Location: security/selinux/netif.c:192
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
```
**Symbols:**

```
ffffffff814db710-ffffffff814db796: sel_netif_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sel_netif_sid(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netif.c (ffffffff814e2090)
Location: security/selinux/netif.c:191
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
```
**Symbols:**

```
ffffffff814e2090-ffffffff814e210d: sel_netif_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sel_netif_sid(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netif.c (ffffffff8153b090)
Location: security/selinux/netif.c:191
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
```
**Symbols:**

```
ffffffff8153b090-ffffffff8153b119: sel_netif_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sel_netif_sid(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netif.c (ffffffff815d2800)
Location: security/selinux/netif.c:191
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
```
**Symbols:**

```
ffffffff815d2800-ffffffff815d28a0: sel_netif_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sel_netif_sid(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netif.c (ffffffff81680770)
Location: security/selinux/netif.c:191
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
```
**Symbols:**

```
ffffffff81680770-ffffffff81680810: sel_netif_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sel_netif_sid(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netif.c (ffffffff816b8840)
Location: security/selinux/netif.c:191
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
```
**Symbols:**

```
ffffffff816b8840-ffffffff816b88e0: sel_netif_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sel_netif_sid(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netif.c (ffffffff816f5290)
Location: security/selinux/netif.c:191
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
  - security/selinux/hooks.c:selinux_inet_sys_rcv_skb
```
**Symbols:**

```
ffffffff816f5290-ffffffff816f532e: sel_netif_sid (STB_GLOBAL)
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
int sel_netif_sid(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netif.c (ffff800010557f20)
Location: security/selinux/netif.c:192
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
**Symbols:**

```
ffff800010557f20-ffff800010558198: sel_netif_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sel_netif_sid(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netif.c (c070cd90)
Location: security/selinux/netif.c:192
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
**Symbols:**

```
c070cd90-c070cfac: sel_netif_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sel_netif_sid(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netif.c (c0000000006b5f40)
Location: security/selinux/netif.c:192
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
**Symbols:**

```
c0000000006b5f40-c0000000006b623c: sel_netif_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sel_netif_sid(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netif.c (ffffffe0003af7a4)
Location: security/selinux/netif.c:192
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
**Symbols:**

```
ffffffe0003af7a4-ffffffe0003af95c: sel_netif_sid (STB_GLOBAL)
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
int sel_netif_sid(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netif.c (0)
Location: security/selinux/netif.c:192
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
**Symbols:**

```
ffffffff81462156-ffffffff814621b3: sel_netif_sid.cold (STB_LOCAL)
ffffffff81461f10-ffffffff814620fb: sel_netif_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int sel_netif_sid(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netif.c (0)
Location: security/selinux/netif.c:192
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
**Symbols:**

```
ffffffff81452b86-ffffffff81452be3: sel_netif_sid.cold (STB_LOCAL)
ffffffff81452940-ffffffff81452b2b: sel_netif_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int sel_netif_sid(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netif.c (0)
Location: security/selinux/netif.c:192
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
**Symbols:**

```
ffffffff8145e1f6-ffffffff8145e253: sel_netif_sid.cold (STB_LOCAL)
ffffffff8145dfb0-ffffffff8145e19b: sel_netif_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int sel_netif_sid(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netif.c (0)
Location: security/selinux/netif.c:192
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_postroute
```
**Symbols:**

```
ffffffff814759a6-ffffffff814759ff: sel_netif_sid.cold (STB_LOCAL)
ffffffff81475750-ffffffff8147594f: sel_netif_sid (STB_GLOBAL)
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
