# Function: <code>netlbl_cache_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int netlbl_cache_add(const struct sk_buff *skb, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff8180c040)
Location: net/netlabel/netlabel_kapi.c:1128
Inline: False
```
**Symbols:**

```
ffffffff8180c040-ffffffff8180c077: netlbl_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int netlbl_cache_add(const struct sk_buff *skb, u16 family, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff8187e020)
Location: net/netlabel/netlabel_kapi.c:1439
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffffffff8187e020-ffffffff8187e07c: netlbl_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int netlbl_cache_add(const struct sk_buff *skb, u16 family, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff818b28d0)
Location: net/netlabel/netlabel_kapi.c:1439
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffffffff818b28d0-ffffffff818b292c: netlbl_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int netlbl_cache_add(const struct sk_buff *skb, u16 family, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff818d9280)
Location: net/netlabel/netlabel_kapi.c:1439
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffffffff818d9280-ffffffff818d92dc: netlbl_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int netlbl_cache_add(const struct sk_buff *skb, u16 family, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff8195ee70)
Location: net/netlabel/netlabel_kapi.c:1439
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffffffff8195ee70-ffffffff8195eecc: netlbl_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int netlbl_cache_add(const struct sk_buff *skb, u16 family, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff819b8650)
Location: net/netlabel/netlabel_kapi.c:1439
Inline: False
```
**Symbols:**

```
ffffffff819b8650-ffffffff819b86ac: netlbl_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int netlbl_cache_add(const struct sk_buff *skb, u16 family, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff819ef920)
Location: net/netlabel/netlabel_kapi.c:1440
Inline: False
```
**Symbols:**

```
ffffffff819ef920-ffffffff819ef97c: netlbl_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int netlbl_cache_add(const struct sk_buff *skb, u16 family, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81a5eb80)
Location: net/netlabel/netlabel_kapi.c:1426
Inline: False
```
**Symbols:**

```
ffffffff81a5eb80-ffffffff81a5ebe0: netlbl_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int netlbl_cache_add(const struct sk_buff *skb, u16 family, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81a957b0)
Location: net/netlabel/netlabel_kapi.c:1426
Inline: False
```
**Symbols:**

```
ffffffff81a957b0-ffffffff81a95810: netlbl_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int netlbl_cache_add(const struct sk_buff *skb, u16 family, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81b90dc0)
Location: net/netlabel/netlabel_kapi.c:1432
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
```
**Symbols:**

```
ffffffff81b90dc0-ffffffff81b90e26: netlbl_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netlbl_cache_add(const struct sk_buff *skb, u16 family, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81ba0ad0)
Location: net/netlabel/netlabel_kapi.c:1432
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/smack/smack_lsm.c:smack_from_netlbl
```
**Symbols:**

```
ffffffff81ba0ad0-ffffffff81ba0b36: netlbl_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int netlbl_cache_add(const struct sk_buff *skb, u16 family, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81b8fba0)
Location: net/netlabel/netlabel_kapi.c:1432
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/smack/smack_lsm.c:smack_from_netlbl
```
**Symbols:**

```
ffffffff81b8fba0-ffffffff81b8fc06: netlbl_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int netlbl_cache_add(const struct sk_buff *skb, u16 family, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81c5c340)
Location: net/netlabel/netlabel_kapi.c:1432
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/smack/smack_lsm.c:smack_from_netlbl
```
**Symbols:**

```
ffffffff81c5c340-ffffffff81c5c3a6: netlbl_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int netlbl_cache_add(const struct sk_buff *skb, u16 family, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81dfe130)
Location: net/netlabel/netlabel_kapi.c:1434
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/smack/smack_lsm.c:smack_from_netlbl
```
**Symbols:**

```
ffffffff81dfe130-ffffffff81dfe1bd: netlbl_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int netlbl_cache_add(const struct sk_buff *skb, u16 family, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81fd2d30)
Location: net/netlabel/netlabel_kapi.c:1434
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/smack/smack_lsm.c:smack_from_netlbl
```
**Symbols:**

```
ffffffff81fd2d30-ffffffff81fd2dbd: netlbl_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int netlbl_cache_add(const struct sk_buff *skb, u16 family, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff8204e980)
Location: net/netlabel/netlabel_kapi.c:1435
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/smack/smack_lsm.c:smack_from_netlbl
```
**Symbols:**

```
ffffffff8204e980-ffffffff8204ea0d: netlbl_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int netlbl_cache_add(const struct sk_buff *skb, u16 family, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff82121000)
Location: net/netlabel/netlabel_kapi.c:1435
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_skbuff_getsid
  - security/smack/smack_lsm.c:smack_from_netlbl
```
**Symbols:**

```
ffffffff82121000-ffffffff8212108d: netlbl_cache_add (STB_GLOBAL)
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
int netlbl_cache_add(const struct sk_buff *skb, u16 family, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffff800010d644f8)
Location: net/netlabel/netlabel_kapi.c:1426
Inline: False
```
**Symbols:**

```
ffff800010d644f8-ffff800010d64590: netlbl_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int netlbl_cache_add(const struct sk_buff *skb, u16 family, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (c0e630a0)
Location: net/netlabel/netlabel_kapi.c:1426
Inline: False
```
**Symbols:**

```
c0e630a0-c0e6310c: netlbl_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int netlbl_cache_add(const struct sk_buff *skb, u16 family, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (c000000000e9ff00)
Location: net/netlabel/netlabel_kapi.c:1426
Inline: False
```
**Symbols:**

```
c000000000e9ff00-c000000000e9ffe8: netlbl_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int netlbl_cache_add(const struct sk_buff *skb, u16 family, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffe00089855a)
Location: net/netlabel/netlabel_kapi.c:1426
Inline: False
```
**Symbols:**

```
ffffffe00089855a-ffffffe0008985ea: netlbl_cache_add (STB_GLOBAL)
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
int netlbl_cache_add(const struct sk_buff *skb, u16 family, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81a34b40)
Location: net/netlabel/netlabel_kapi.c:1426
Inline: False
```
**Symbols:**

```
ffffffff81a34b40-ffffffff81a34ba0: netlbl_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int netlbl_cache_add(const struct sk_buff *skb, u16 family, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff819f1760)
Location: net/netlabel/netlabel_kapi.c:1426
Inline: False
```
**Symbols:**

```
ffffffff819f1760-ffffffff819f17c0: netlbl_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int netlbl_cache_add(const struct sk_buff *skb, u16 family, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81aa09f0)
Location: net/netlabel/netlabel_kapi.c:1426
Inline: False
```
**Symbols:**

```
ffffffff81aa09f0-ffffffff81aa0a50: netlbl_cache_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int netlbl_cache_add(const struct sk_buff *skb, u16 family, const struct netlbl_lsm_secattr *secattr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81aaccd0)
Location: net/netlabel/netlabel_kapi.c:1426
Inline: False
```
**Symbols:**

```
ffffffff81aaccd0-ffffffff81aacd30: netlbl_cache_add (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u16 family</code>
</li>
<li>
<b>Param reordered. </b>
<code>skb, secattr</code> ➡️ <code>skb, family, secattr</code>
</li>
</ul>
</details>
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
