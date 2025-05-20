# Function: <code>netlbl_skbuff_err</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff *skb, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff8180bff0)
Location: net/netlabel/netlabel_kapi.c:1097
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_err
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff8180bff0-ffffffff8180c026: netlbl_skbuff_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff8187dfc0)
Location: net/netlabel/netlabel_kapi.c:1400
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_err
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff8187dfc0-ffffffff8187dffd: netlbl_skbuff_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff818b2870)
Location: net/netlabel/netlabel_kapi.c:1400
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_err
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff818b2870-ffffffff818b28ad: netlbl_skbuff_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff818d9220)
Location: net/netlabel/netlabel_kapi.c:1400
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_err
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff818d9220-ffffffff818d925e: netlbl_skbuff_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff8195ee10)
Location: net/netlabel/netlabel_kapi.c:1400
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_err
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff8195ee10-ffffffff8195ee4e: netlbl_skbuff_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff819b85f0)
Location: net/netlabel/netlabel_kapi.c:1400
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_err
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff819b85f0-ffffffff819b862d: netlbl_skbuff_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff819ef8c0)
Location: net/netlabel/netlabel_kapi.c:1401
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_err
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff819ef8c0-ffffffff819ef8fd: netlbl_skbuff_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81a5eb20)
Location: net/netlabel/netlabel_kapi.c:1387
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_err
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81a5eb20-ffffffff81a5eb5f: netlbl_skbuff_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81a95750)
Location: net/netlabel/netlabel_kapi.c:1387
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_err
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81a95750-ffffffff81a9578f: netlbl_skbuff_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81b90d60)
Location: net/netlabel/netlabel_kapi.c:1393
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_err
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81b90d60-ffffffff81b90d9f: netlbl_skbuff_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81ba0a70)
Location: net/netlabel/netlabel_kapi.c:1393
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_err
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81ba0a70-ffffffff81ba0aaf: netlbl_skbuff_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81b8fb40)
Location: net/netlabel/netlabel_kapi.c:1393
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_err
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81b8fb40-ffffffff81b8fb7f: netlbl_skbuff_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81c5c2e0)
Location: net/netlabel/netlabel_kapi.c:1393
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_err
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81c5c2e0-ffffffff81c5c31f: netlbl_skbuff_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81dfe0b0)
Location: net/netlabel/netlabel_kapi.c:1395
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_err
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81dfe0b0-ffffffff81dfe107: netlbl_skbuff_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81fd2c90)
Location: net/netlabel/netlabel_kapi.c:1395
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_err
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81fd2c90-ffffffff81fd2ce7: netlbl_skbuff_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff8204e8e0)
Location: net/netlabel/netlabel_kapi.c:1396
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_err
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff8204e8e0-ffffffff8204e937: netlbl_skbuff_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff82120f60)
Location: net/netlabel/netlabel_kapi.c:1396
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_err
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff82120f60-ffffffff82120fb7: netlbl_skbuff_err (STB_GLOBAL)
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
void netlbl_skbuff_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffff800010d64468)
Location: net/netlabel/netlabel_kapi.c:1387
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_err
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffff800010d64468-ffff800010d644d4: netlbl_skbuff_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (c0e63038)
Location: net/netlabel/netlabel_kapi.c:1387
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_err
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
c0e63038-c0e63080: netlbl_skbuff_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (c000000000e9fe40)
Location: net/netlabel/netlabel_kapi.c:1387
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_err
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
c000000000e9fe40-c000000000e9feb8: netlbl_skbuff_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffe0008984ce)
Location: net/netlabel/netlabel_kapi.c:1387
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_err
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffe0008984ce-ffffffe000898530: netlbl_skbuff_err (STB_GLOBAL)
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
void netlbl_skbuff_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81a34ae0)
Location: net/netlabel/netlabel_kapi.c:1387
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_err
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81a34ae0-ffffffff81a34b1f: netlbl_skbuff_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff819f1700)
Location: net/netlabel/netlabel_kapi.c:1387
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_err
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff819f1700-ffffffff819f173f: netlbl_skbuff_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81aa0990)
Location: net/netlabel/netlabel_kapi.c:1387
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_err
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81aa0990-ffffffff81aa09cf: netlbl_skbuff_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void netlbl_skbuff_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_kapi.c (ffffffff81aacc70)
Location: net/netlabel/netlabel_kapi.c:1387
Inline: False
Direct callers:
  - security/selinux/netlabel.c:selinux_netlbl_sock_rcv_skb
  - security/selinux/netlabel.c:selinux_netlbl_err
  - security/smack/smack_lsm.c:smack_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81aacc70-ffffffff81aaccaf: netlbl_skbuff_err (STB_GLOBAL)
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
<code>skb, error, gateway</code> ➡️ <code>skb, family, error, gateway</code>
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
