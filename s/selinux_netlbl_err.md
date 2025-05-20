# Function: <code>selinux_netlbl_err</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void selinux_netlbl_err(struct sk_buff *skb, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff8135d360)
Location: security/selinux/netlabel.c:154
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff8135d360-ffffffff8135d370: selinux_netlbl_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void selinux_netlbl_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff81393310)
Location: security/selinux/netlabel.c:155
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81393310-ffffffff81393323: selinux_netlbl_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void selinux_netlbl_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff813a9f30)
Location: security/selinux/netlabel.c:155
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff813a9f30-ffffffff813a9f43: selinux_netlbl_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void selinux_netlbl_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff813c0910)
Location: security/selinux/netlabel.c:156
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff813c0910-ffffffff813c0923: selinux_netlbl_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void selinux_netlbl_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff813e6ac0)
Location: security/selinux/netlabel.c:156
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff813e6ac0-ffffffff813e6ad3: selinux_netlbl_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void selinux_netlbl_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff814178f0)
Location: security/selinux/netlabel.c:155
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff814178f0-ffffffff81417903: selinux_netlbl_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void selinux_netlbl_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff81433e20)
Location: security/selinux/netlabel.c:156
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81433e20-ffffffff81433e33: selinux_netlbl_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void selinux_netlbl_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff814618d0)
Location: security/selinux/netlabel.c:142
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff814618d0-ffffffff814618e3: selinux_netlbl_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void selinux_netlbl_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff8147b680)
Location: security/selinux/netlabel.c:142
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff8147b680-ffffffff8147b693: selinux_netlbl_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void selinux_netlbl_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff814d0b90)
Location: security/selinux/netlabel.c:142
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff814d0b90-ffffffff814d0ba3: selinux_netlbl_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void selinux_netlbl_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff814ee0a0)
Location: security/selinux/netlabel.c:142
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff814ee0a0-ffffffff814ee0b3: selinux_netlbl_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void selinux_netlbl_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff814f4e10)
Location: security/selinux/netlabel.c:142
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff814f4e10-ffffffff814f4e23: selinux_netlbl_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void selinux_netlbl_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff8154f810)
Location: security/selinux/netlabel.c:142
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff8154f810-ffffffff8154f823: selinux_netlbl_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void selinux_netlbl_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff815e8b60)
Location: security/selinux/netlabel.c:144
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff815e8b60-ffffffff815e8b7f: selinux_netlbl_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void selinux_netlbl_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff816983f0)
Location: security/selinux/netlabel.c:144
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff816983f0-ffffffff8169840f: selinux_netlbl_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void selinux_netlbl_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff816d0880)
Location: security/selinux/netlabel.c:143
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff816d0880-ffffffff816d089f: selinux_netlbl_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void selinux_netlbl_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff8170ced0)
Location: security/selinux/netlabel.c:143
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff8170ced0-ffffffff8170ceef: selinux_netlbl_err (STB_GLOBAL)
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
void selinux_netlbl_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffff80001056c0e0)
Location: security/selinux/netlabel.c:142
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffff80001056c0e0-ffff80001056c12c: selinux_netlbl_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void selinux_netlbl_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (c071f934)
Location: security/selinux/netlabel.c:142
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
c071f934-c071f950: selinux_netlbl_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void selinux_netlbl_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (c0000000006d01b0)
Location: security/selinux/netlabel.c:142
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
c0000000006d01b0-c0000000006d01e4: selinux_netlbl_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void selinux_netlbl_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffe0003c0c58)
Location: security/selinux/netlabel.c:142
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffe0003c0c58-ffffffe0003c0c9a: selinux_netlbl_err (STB_GLOBAL)
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
void selinux_netlbl_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff81473c60)
Location: security/selinux/netlabel.c:142
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81473c60-ffffffff81473c73: selinux_netlbl_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void selinux_netlbl_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff81464680)
Location: security/selinux/netlabel.c:142
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81464680-ffffffff81464693: selinux_netlbl_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void selinux_netlbl_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff8146fd00)
Location: security/selinux/netlabel.c:142
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff8146fd00-ffffffff8146fd13: selinux_netlbl_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void selinux_netlbl_err(struct sk_buff *skb, u16 family, int error, int gateway);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netlabel.c (ffffffff81487570)
Location: security/selinux/netlabel.c:142
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_ip_forward
  - security/selinux/hooks.c:selinux_socket_sock_rcv_skb
```
**Symbols:**

```
ffffffff81487570-ffffffff81487583: selinux_netlbl_err (STB_GLOBAL)
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
