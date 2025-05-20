# Function: <code>security_netlbl_sid_to_secattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_netlbl_sid_to_secattr(u32 sid, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8135a8b0)
Location: security/selinux/ss/services.c:3388
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
```
**Symbols:**

```
ffffffff8135a8b0-ffffffff8135a95d: security_netlbl_sid_to_secattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_netlbl_sid_to_secattr(u32 sid, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81390860)
Location: security/selinux/ss/services.c:3382
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
**Symbols:**

```
ffffffff81390860-ffffffff8139090d: security_netlbl_sid_to_secattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_netlbl_sid_to_secattr(u32 sid, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a7480)
Location: security/selinux/ss/services.c:3382
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
**Symbols:**

```
ffffffff813a7480-ffffffff813a752d: security_netlbl_sid_to_secattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_netlbl_sid_to_secattr(u32 sid, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bde60)
Location: security/selinux/ss/services.c:3498
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
**Symbols:**

```
ffffffff813bde60-ffffffff813bdf0f: security_netlbl_sid_to_secattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_netlbl_sid_to_secattr(u32 sid, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e4000)
Location: security/selinux/ss/services.c:3508
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
**Symbols:**

```
ffffffff813e4000-ffffffff813e40af: security_netlbl_sid_to_secattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_netlbl_sid_to_secattr(struct selinux_state *state, u32 sid, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81414820)
Location: security/selinux/ss/services.c:3661
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
**Symbols:**

```
ffffffff81414820-ffffffff814148e8: security_netlbl_sid_to_secattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_netlbl_sid_to_secattr(struct selinux_state *state, u32 sid, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81430e00)
Location: security/selinux/ss/services.c:3627
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
**Symbols:**

```
ffffffff81430e00-ffffffff81430ecb: security_netlbl_sid_to_secattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_netlbl_sid_to_secattr(struct selinux_state *state, u32 sid, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145e820)
Location: security/selinux/ss/services.c:3645
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
**Symbols:**

```
ffffffff8145e820-ffffffff8145e8e6: security_netlbl_sid_to_secattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_netlbl_sid_to_secattr(struct selinux_state *state, u32 sid, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814785d0)
Location: security/selinux/ss/services.c:3652
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
**Symbols:**

```
ffffffff814785d0-ffffffff81478696: security_netlbl_sid_to_secattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_netlbl_sid_to_secattr(struct selinux_state *state, u32 sid, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814cdaa0)
Location: security/selinux/ss/services.c:3690
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
**Symbols:**

```
ffffffff814cdaa0-ffffffff814cdb85: security_netlbl_sid_to_secattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_netlbl_sid_to_secattr(struct selinux_state *state, u32 sid, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814eb0f0)
Location: security/selinux/ss/services.c:3855
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
**Symbols:**

```
ffffffff814eb0f0-ffffffff814eb1b8: security_netlbl_sid_to_secattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_netlbl_sid_to_secattr(struct selinux_state *state, u32 sid, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814f1dc0)
Location: security/selinux/ss/services.c:3937
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
**Symbols:**

```
ffffffff814f1dc0-ffffffff814f1e88: security_netlbl_sid_to_secattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_netlbl_sid_to_secattr(struct selinux_state *state, u32 sid, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3948
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
**Symbols:**

```
ffffffff81cd534b-ffffffff81cd5360: security_netlbl_sid_to_secattr.cold (STB_LOCAL)
ffffffff8154c4a0-ffffffff8154c57b: security_netlbl_sid_to_secattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int security_netlbl_sid_to_secattr(struct selinux_state *state, u32 sid, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3951
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
**Symbols:**

```
ffffffff81e8817f-ffffffff81e88194: security_netlbl_sid_to_secattr.cold (STB_LOCAL)
ffffffff815e5340-ffffffff815e5432: security_netlbl_sid_to_secattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int security_netlbl_sid_to_secattr(struct selinux_state *state, u32 sid, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3944
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
**Symbols:**

```
ffffffff82073f55-ffffffff82073f6a: security_netlbl_sid_to_secattr.cold (STB_LOCAL)
ffffffff816947a0-ffffffff81694892: security_netlbl_sid_to_secattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int security_netlbl_sid_to_secattr(u32 sid, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3881
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
**Symbols:**

```
ffffffff820f3b00-ffffffff820f3b15: security_netlbl_sid_to_secattr.cold (STB_LOCAL)
ffffffff816ccca0-ffffffff816ccdab: security_netlbl_sid_to_secattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int security_netlbl_sid_to_secattr(u32 sid, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:3900
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
**Symbols:**

```
ffffffff821d0c74-ffffffff821d0c89: security_netlbl_sid_to_secattr.cold (STB_LOCAL)
ffffffff817092a0-ffffffff8170938c: security_netlbl_sid_to_secattr (STB_GLOBAL)
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
int security_netlbl_sid_to_secattr(struct selinux_state *state, u32 sid, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff8000105686c8)
Location: security/selinux/ss/services.c:3652
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
**Symbols:**

```
ffff8000105686c8-ffff80001056880c: security_netlbl_sid_to_secattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_netlbl_sid_to_secattr(struct selinux_state *state, u32 sid, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c071c970)
Location: security/selinux/ss/services.c:3652
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
**Symbols:**

```
c071c970-c071ca60: security_netlbl_sid_to_secattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_netlbl_sid_to_secattr(struct selinux_state *state, u32 sid, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006cbd60)
Location: security/selinux/ss/services.c:3652
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
**Symbols:**

```
c0000000006cbd60-c0000000006cbea8: security_netlbl_sid_to_secattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_netlbl_sid_to_secattr(struct selinux_state *state, u32 sid, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bdea0)
Location: security/selinux/ss/services.c:3652
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
**Symbols:**

```
ffffffe0003bdea0-ffffffe0003bdf70: security_netlbl_sid_to_secattr (STB_GLOBAL)
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
int security_netlbl_sid_to_secattr(struct selinux_state *state, u32 sid, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81470bb0)
Location: security/selinux/ss/services.c:3652
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
**Symbols:**

```
ffffffff81470bb0-ffffffff81470c76: security_netlbl_sid_to_secattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_netlbl_sid_to_secattr(struct selinux_state *state, u32 sid, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814615d0)
Location: security/selinux/ss/services.c:3652
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
**Symbols:**

```
ffffffff814615d0-ffffffff81461696: security_netlbl_sid_to_secattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_netlbl_sid_to_secattr(struct selinux_state *state, u32 sid, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146cc50)
Location: security/selinux/ss/services.c:3652
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
**Symbols:**

```
ffffffff8146cc50-ffffffff8146cd16: security_netlbl_sid_to_secattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_netlbl_sid_to_secattr(struct selinux_state *state, u32 sid, struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81484470)
Location: security/selinux/ss/services.c:3652
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_inet_conn_request
  - security/selinux/netlabel.c:selinux_netlbl_sctp_assoc_request
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_setsid
  - security/selinux/netlabel.c:selinux_netlbl_sock_genattr
```
**Symbols:**

```
ffffffff81484470-ffffffff81484555: security_netlbl_sid_to_secattr (STB_GLOBAL)
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
<code>sid, secattr</code> ➡️ <code>state, sid, secattr</code>
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
<code>state, sid, secattr</code> ➡️ <code>sid, secattr</code>
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
