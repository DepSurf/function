# Function: <code>selinux_netlbl_sidlookup_cached</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/netlabel.c (ffffffff8135d250)
Location: security/selinux/netlabel.c:56
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
ffffffff8135d250-ffffffff8135d26b: selinux_netlbl_sidlookup_cached.part.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff81393981)
Location: security/selinux/netlabel.c:56
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff813aa5a1)
Location: security/selinux/netlabel.c:56
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff813c0f81)
Location: security/selinux/netlabel.c:57
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff813e7171)
Location: security/selinux/netlabel.c:57
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int selinux_netlbl_sidlookup_cached(struct sk_buff *skb, u16 family, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff81417720)
Location: security/selinux/netlabel.c:55
Inline: True
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffffffff81417720-ffffffff81417779: selinux_netlbl_sidlookup_cached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int selinux_netlbl_sidlookup_cached(struct sk_buff *skb, u16 family, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff81433c50)
Location: security/selinux/netlabel.c:56
Inline: True
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffffffff81433c50-ffffffff81433ca9: selinux_netlbl_sidlookup_cached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int selinux_netlbl_sidlookup_cached(struct sk_buff *skb, u16 family, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff814616f0)
Location: security/selinux/netlabel.c:42
Inline: True
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffffffff814616f0-ffffffff81461749: selinux_netlbl_sidlookup_cached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int selinux_netlbl_sidlookup_cached(struct sk_buff *skb, u16 family, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff8147b4a0)
Location: security/selinux/netlabel.c:42
Inline: True
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffffffff8147b4a0-ffffffff8147b4f9: selinux_netlbl_sidlookup_cached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff814d14e3)
Location: security/selinux/netlabel.c:42
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff814ee9f3)
Location: security/selinux/netlabel.c:42
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff814f5753)
Location: security/selinux/netlabel.c:42
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff81550153)
Location: security/selinux/netlabel.c:42
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff815e95ed)
Location: security/selinux/netlabel.c:43
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff81698f1d)
Location: security/selinux/netlabel.c:43
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff816d13d2)
Location: security/selinux/netlabel.c:43
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff8170da03)
Location: security/selinux/netlabel.c:43
Inline: True
Inline callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int selinux_netlbl_sidlookup_cached(struct sk_buff *skb, u16 family, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffff80001056be88)
Location: security/selinux/netlabel.c:42
Inline: True
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffff80001056be88-ffff80001056bf04: selinux_netlbl_sidlookup_cached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int selinux_netlbl_sidlookup_cached(struct sk_buff *skb, u16 family, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (c071f720)
Location: security/selinux/netlabel.c:42
Inline: True
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
c071f720-c071f78c: selinux_netlbl_sidlookup_cached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int selinux_netlbl_sidlookup_cached(struct sk_buff *skb, u16 family, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (c0000000006cfe00)
Location: security/selinux/netlabel.c:42
Inline: True
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
c0000000006cfe00-c0000000006cfea8: selinux_netlbl_sidlookup_cached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int selinux_netlbl_sidlookup_cached(struct sk_buff *skb, u16 family, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffe0003c0a4e)
Location: security/selinux/netlabel.c:42
Inline: True
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffffffe0003c0a4e-ffffffe0003c0ab8: selinux_netlbl_sidlookup_cached (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int selinux_netlbl_sidlookup_cached(struct sk_buff *skb, u16 family, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff81473a80)
Location: security/selinux/netlabel.c:42
Inline: True
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffffffff81473a80-ffffffff81473ad9: selinux_netlbl_sidlookup_cached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int selinux_netlbl_sidlookup_cached(struct sk_buff *skb, u16 family, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff814644a0)
Location: security/selinux/netlabel.c:42
Inline: True
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffffffff814644a0-ffffffff814644f9: selinux_netlbl_sidlookup_cached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int selinux_netlbl_sidlookup_cached(struct sk_buff *skb, u16 family, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff8146fb20)
Location: security/selinux/netlabel.c:42
Inline: True
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffffffff8146fb20-ffffffff8146fb79: selinux_netlbl_sidlookup_cached (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int selinux_netlbl_sidlookup_cached(struct sk_buff *skb, u16 family, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff81487390)
Location: security/selinux/netlabel.c:42
Inline: True
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffffffff81487390-ffffffff814873e9: selinux_netlbl_sidlookup_cached (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
