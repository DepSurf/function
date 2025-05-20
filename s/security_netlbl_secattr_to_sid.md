# Function: <code>security_netlbl_secattr_to_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_netlbl_secattr_to_sid(struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8135a6c0)
Location: security/selinux/ss/services.c:3321
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
```
**Symbols:**

```
ffffffff8135a6c0-ffffffff8135a8a6: security_netlbl_secattr_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_netlbl_secattr_to_sid(struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81390680)
Location: security/selinux/ss/services.c:3315
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffffffff81390680-ffffffff81390857: security_netlbl_secattr_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_netlbl_secattr_to_sid(struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a72a0)
Location: security/selinux/ss/services.c:3315
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffffffff813a72a0-ffffffff813a7477: security_netlbl_secattr_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_netlbl_secattr_to_sid(struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bdc80)
Location: security/selinux/ss/services.c:3431
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffffffff813bdc80-ffffffff813bde57: security_netlbl_secattr_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_netlbl_secattr_to_sid(struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e3e20)
Location: security/selinux/ss/services.c:3441
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffffffff813e3e20-ffffffff813e3ff7: security_netlbl_secattr_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_netlbl_secattr_to_sid(struct selinux_state *state, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81414620)
Location: security/selinux/ss/services.c:3591
Inline: False
```
**Symbols:**

```
ffffffff81414620-ffffffff8141481a: security_netlbl_secattr_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_netlbl_secattr_to_sid(struct selinux_state *state, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81430c00)
Location: security/selinux/ss/services.c:3557
Inline: False
```
**Symbols:**

```
ffffffff81430c00-ffffffff81430e00: security_netlbl_secattr_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_netlbl_secattr_to_sid(struct selinux_state *state, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145e610)
Location: security/selinux/ss/services.c:3575
Inline: False
```
**Symbols:**

```
ffffffff8145e610-ffffffff8145e818: security_netlbl_secattr_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_netlbl_secattr_to_sid(struct selinux_state *state, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814783c0)
Location: security/selinux/ss/services.c:3582
Inline: False
```
**Symbols:**

```
ffffffff814783c0-ffffffff814785c8: security_netlbl_secattr_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_netlbl_secattr_to_sid(struct selinux_state *state, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814cd870)
Location: security/selinux/ss/services.c:3620
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffffffff814cd870-ffffffff814cda91: security_netlbl_secattr_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_netlbl_secattr_to_sid(struct selinux_state *state, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814eaf10)
Location: security/selinux/ss/services.c:3781
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffffffff814eaf10-ffffffff814eb0f0: security_netlbl_secattr_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_netlbl_secattr_to_sid(struct selinux_state *state, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814f1b70)
Location: security/selinux/ss/services.c:3860
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffffffff814f1b70-ffffffff814f1dbd: security_netlbl_secattr_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_netlbl_secattr_to_sid(struct selinux_state *state, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3870
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffffffff81cd5336-ffffffff81cd534b: security_netlbl_secattr_to_sid.cold (STB_LOCAL)
ffffffff8154c240-ffffffff8154c49a: security_netlbl_secattr_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int security_netlbl_secattr_to_sid(struct selinux_state *state, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3873
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffffffff81e8816a-ffffffff81e8817f: security_netlbl_secattr_to_sid.cold (STB_LOCAL)
ffffffff815e50d0-ffffffff815e5331: security_netlbl_secattr_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int security_netlbl_secattr_to_sid(struct selinux_state *state, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3866
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffffffff82073f40-ffffffff82073f55: security_netlbl_secattr_to_sid.cold (STB_LOCAL)
ffffffff81694520-ffffffff81694781: security_netlbl_secattr_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int security_netlbl_secattr_to_sid(struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3805
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffffffff820f3aeb-ffffffff820f3b00: security_netlbl_secattr_to_sid.cold (STB_LOCAL)
ffffffff816cca20-ffffffff816ccc84: security_netlbl_secattr_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int security_netlbl_secattr_to_sid(struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3824
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffffffff821d0c5f-ffffffff821d0c74: security_netlbl_secattr_to_sid.cold (STB_LOCAL)
ffffffff81708ff0-ffffffff81709289: security_netlbl_secattr_to_sid (STB_GLOBAL)
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
int security_netlbl_secattr_to_sid(struct selinux_state *state, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010568438)
Location: security/selinux/ss/services.c:3582
Inline: False
```
**Symbols:**

```
ffff800010568438-ffff8000105686c4: security_netlbl_secattr_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_netlbl_secattr_to_sid(struct selinux_state *state, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c071c708)
Location: security/selinux/ss/services.c:3582
Inline: False
```
**Symbols:**

```
c071c708-c071c970: security_netlbl_secattr_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_netlbl_secattr_to_sid(struct selinux_state *state, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006cba60)
Location: security/selinux/ss/services.c:3582
Inline: False
```
**Symbols:**

```
c0000000006cba60-c0000000006cbd58: security_netlbl_secattr_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_netlbl_secattr_to_sid(struct selinux_state *state, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bdcc8)
Location: security/selinux/ss/services.c:3582
Inline: False
```
**Symbols:**

```
ffffffe0003bdcc8-ffffffe0003bdea0: security_netlbl_secattr_to_sid (STB_GLOBAL)
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
int security_netlbl_secattr_to_sid(struct selinux_state *state, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814709a0)
Location: security/selinux/ss/services.c:3582
Inline: False
```
**Symbols:**

```
ffffffff814709a0-ffffffff81470ba8: security_netlbl_secattr_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_netlbl_secattr_to_sid(struct selinux_state *state, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814613c0)
Location: security/selinux/ss/services.c:3582
Inline: False
```
**Symbols:**

```
ffffffff814613c0-ffffffff814615c8: security_netlbl_secattr_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_netlbl_secattr_to_sid(struct selinux_state *state, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146ca40)
Location: security/selinux/ss/services.c:3582
Inline: False
```
**Symbols:**

```
ffffffff8146ca40-ffffffff8146cc48: security_netlbl_secattr_to_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_netlbl_secattr_to_sid(struct selinux_state *state, struct netlbl_lsm_secattr *secattr, u32 *sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81484260)
Location: security/selinux/ss/services.c:3582
Inline: False
```
**Symbols:**

```
ffffffff81484260-ffffffff8148446c: security_netlbl_secattr_to_sid (STB_GLOBAL)
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
<code>secattr, sid</code> ➡️ <code>state, secattr, sid</code>
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
<code>state, secattr, sid</code> ➡️ <code>secattr, sid</code>
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
