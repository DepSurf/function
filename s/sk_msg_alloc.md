# Function: <code>sk_msg_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sk_msg_alloc(struct sock *sk, struct sk_msg *msg, int len, int elem_first_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff818e6040)
Location: net/core/skmsg.c:25
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff818e6040-ffffffff818e6251: sk_msg_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sk_msg_alloc(struct sock *sk, struct sk_msg *msg, int len, int elem_first_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81935780)
Location: net/core/skmsg.c:25
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81935780-ffffffff819359a4: sk_msg_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sk_msg_alloc(struct sock *sk, struct sk_msg *msg, int len, int elem_first_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81968540)
Location: net/core/skmsg.c:25
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81968540-ffffffff819687b9: sk_msg_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sk_msg_alloc(struct sock *sk, struct sk_msg *msg, int len, int elem_first_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a3c0d0)
Location: net/core/skmsg.c:26
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81a3c0d0-ffffffff81a3c32b: sk_msg_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sk_msg_alloc(struct sock *sk, struct sk_msg *msg, int len, int elem_first_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a3e790)
Location: net/core/skmsg.c:26
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81a3e790-ffffffff81a3e9eb: sk_msg_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sk_msg_alloc(struct sock *sk, struct sk_msg *msg, int len, int elem_first_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81a4c990)
Location: net/core/skmsg.c:26
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81a4c990-ffffffff81a4cbeb: sk_msg_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sk_msg_alloc(struct sock *sk, struct sk_msg *msg, int len, int elem_first_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81b052d0)
Location: net/core/skmsg.c:26
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81b052d0-ffffffff81b05592: sk_msg_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sk_msg_alloc(struct sock *sk, struct sk_msg *msg, int len, int elem_first_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81c8c610)
Location: net/core/skmsg.c:26
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff81c8c610-ffffffff81c8c97e: sk_msg_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sk_msg_alloc(struct sock *sk, struct sk_msg *msg, int len, int elem_first_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skmsg.c (0)
Location: net/core/skmsg.c:26
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff820ad346-ffffffff820ad35a: sk_msg_alloc.cold (STB_LOCAL)
ffffffff81e468a0-ffffffff81e46bfc: sk_msg_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sk_msg_alloc(struct sock *sk, struct sk_msg *msg, int len, int elem_first_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skmsg.c (0)
Location: net/core/skmsg.c:27
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff8212e4f5-ffffffff8212e509: sk_msg_alloc.cold (STB_LOCAL)
ffffffff81ea22f0-ffffffff81ea265a: sk_msg_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sk_msg_alloc(struct sock *sk, struct sk_msg *msg, int len, int elem_first_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skmsg.c (0)
Location: net/core/skmsg.c:27
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
  - net/xfrm/espintcp.c:espintcp_sendmsg
```
**Symbols:**

```
ffffffff822102a1-ffffffff822102b5: sk_msg_alloc.cold (STB_LOCAL)
ffffffff81f648e0-ffffffff81f64c50: sk_msg_alloc (STB_GLOBAL)
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
int sk_msg_alloc(struct sock *sk, struct sk_msg *msg, int len, int elem_first_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffff800010c0efd8)
Location: net/core/skmsg.c:25
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffff800010c0efd8-ffff800010c0f288: sk_msg_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sk_msg_alloc(struct sock *sk, struct sk_msg *msg, int len, int elem_first_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (c0d26a80)
Location: net/core/skmsg.c:25
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
c0d26a80-c0d26cec: sk_msg_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sk_msg_alloc(struct sock *sk, struct sk_msg *msg, int len, int elem_first_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (c000000000cfa1c0)
Location: net/core/skmsg.c:25
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
c000000000cfa1c0-c000000000cfa54c: sk_msg_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sk_msg_alloc(struct sock *sk, struct sk_msg *msg, int len, int elem_first_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffe00078b0ee)
Location: net/core/skmsg.c:25
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffe00078b0ee-ffffffe00078b2fe: sk_msg_alloc (STB_GLOBAL)
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
int sk_msg_alloc(struct sock *sk, struct sk_msg *msg, int len, int elem_first_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81908510)
Location: net/core/skmsg.c:25
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81908510-ffffffff81908789: sk_msg_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sk_msg_alloc(struct sock *sk, struct sk_msg *msg, int len, int elem_first_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff818c2320)
Location: net/core/skmsg.c:25
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff818c2320-ffffffff818c2599: sk_msg_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sk_msg_alloc(struct sock *sk, struct sk_msg *msg, int len, int elem_first_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff81959540)
Location: net/core/skmsg.c:25
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81959540-ffffffff819597b9: sk_msg_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sk_msg_alloc(struct sock *sk, struct sk_msg *msg, int len, int elem_first_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skmsg.c (ffffffff8197b710)
Location: net/core/skmsg.c:25
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff8197b710-ffffffff8197b989: sk_msg_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
