# Function: <code>tcp_bpf_send_verdict</code>

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
int tcp_bpf_send_verdict(struct sock *sk, struct sk_psock *psock, struct sk_msg *msg, int *copied, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff819772e0)
Location: net/ipv4/tcp_bpf.c:298
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff819772e0-ffffffff8197768c: tcp_bpf_send_verdict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcp_bpf_send_verdict(struct sock *sk, struct sk_psock *psock, struct sk_msg *msg, int *copied, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff819e0e00)
Location: net/ipv4/tcp_bpf.c:301
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff819e0e00-ffffffff819e11b7: tcp_bpf_send_verdict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_bpf_send_verdict(struct sock *sk, struct sk_psock *psock, struct sk_msg *msg, int *copied, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81a17e30)
Location: net/ipv4/tcp_bpf.c:301
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81a17e30-ffffffff81a181d8: tcp_bpf_send_verdict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_bpf_send_verdict(struct sock *sk, struct sk_psock *psock, struct sk_msg *msg, int *copied, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81b08b70)
Location: net/ipv4/tcp_bpf.c:310
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81b08b70-ffffffff81b08f4c: tcp_bpf_send_verdict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_bpf_send_verdict(struct sock *sk, struct sk_psock *psock, struct sk_msg *msg, int *copied, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81b17290)
Location: net/ipv4/tcp_bpf.c:314
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81b17290-ffffffff81b1766c: tcp_bpf_send_verdict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_bpf_send_verdict(struct sock *sk, struct sk_psock *psock, struct sk_msg *msg, int *copied, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81b04e80)
Location: net/ipv4/tcp_bpf.c:212
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81b04e80-ffffffff81b05249: tcp_bpf_send_verdict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcp_bpf_send_verdict(struct sock *sk, struct sk_psock *psock, struct sk_msg *msg, int *copied, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81bc76e0)
Location: net/ipv4/tcp_bpf.c:278
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81bc76e0-ffffffff81bc7b56: tcp_bpf_send_verdict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcp_bpf_send_verdict(struct sock *sk, struct sk_psock *psock, struct sk_msg *msg, int *copied, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81d5cc20)
Location: net/ipv4/tcp_bpf.c:276
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81d5cc20-ffffffff81d5d0ea: tcp_bpf_send_verdict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tcp_bpf_send_verdict(struct sock *sk, struct sk_psock *psock, struct sk_msg *msg, int *copied, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_bpf.c (0)
Location: net/ipv4/tcp_bpf.c:279
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81f271a0-ffffffff81f276a1: tcp_bpf_send_verdict (STB_LOCAL)
ffffffff820b2e93-ffffffff820b2eac: tcp_bpf_send_verdict.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tcp_bpf_send_verdict(struct sock *sk, struct sk_psock *psock, struct sk_msg *msg, int *copied, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_bpf.c (0)
Location: net/ipv4/tcp_bpf.c:367
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81f86e60-ffffffff81f87366: tcp_bpf_send_verdict (STB_LOCAL)
ffffffff8213403b-ffffffff82134054: tcp_bpf_send_verdict.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tcp_bpf_send_verdict(struct sock *sk, struct sk_psock *psock, struct sk_msg *msg, int *copied, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_bpf.c (0)
Location: net/ipv4/tcp_bpf.c:381
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff8204e4a0-ffffffff8204e9e3: tcp_bpf_send_verdict (STB_LOCAL)
ffffffff82215a1d-ffffffff82215a36: tcp_bpf_send_verdict.cold (STB_LOCAL)
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
int tcp_bpf_send_verdict(struct sock *sk, struct sk_psock *psock, struct sk_msg *msg, int *copied, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffff800010cd39a0)
Location: net/ipv4/tcp_bpf.c:301
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffff800010cd39a0-ffff800010cd3d4c: tcp_bpf_send_verdict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_bpf_send_verdict(struct sock *sk, struct sk_psock *psock, struct sk_msg *msg, int *copied, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (c0ddd880)
Location: net/ipv4/tcp_bpf.c:301
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
c0ddd880-c0dddc4c: tcp_bpf_send_verdict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_bpf_send_verdict(struct sock *sk, struct sk_psock *psock, struct sk_msg *msg, int *copied, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (c000000000df2bf0)
Location: net/ipv4/tcp_bpf.c:301
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
c000000000df2bf0-c000000000df30f0: tcp_bpf_send_verdict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_bpf_send_verdict(struct sock *sk, struct sk_psock *psock, struct sk_msg *msg, int *copied, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffe0008248b4)
Location: net/ipv4/tcp_bpf.c:301
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffe0008248b4-ffffffe000824be2: tcp_bpf_send_verdict (STB_LOCAL)
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
int tcp_bpf_send_verdict(struct sock *sk, struct sk_psock *psock, struct sk_msg *msg, int *copied, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff819b74c0)
Location: net/ipv4/tcp_bpf.c:301
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff819b74c0-ffffffff819b7868: tcp_bpf_send_verdict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_bpf_send_verdict(struct sock *sk, struct sk_psock *psock, struct sk_msg *msg, int *copied, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff819742b0)
Location: net/ipv4/tcp_bpf.c:301
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff819742b0-ffffffff81974658: tcp_bpf_send_verdict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_bpf_send_verdict(struct sock *sk, struct sk_psock *psock, struct sk_msg *msg, int *copied, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81a21f40)
Location: net/ipv4/tcp_bpf.c:301
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81a21f40-ffffffff81a222e8: tcp_bpf_send_verdict (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_bpf_send_verdict(struct sock *sk, struct sk_psock *psock, struct sk_msg *msg, int *copied, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81a2d2d0)
Location: net/ipv4/tcp_bpf.c:301
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendpage
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg
```
**Symbols:**

```
ffffffff81a2d2d0-ffffffff81a2d678: tcp_bpf_send_verdict (STB_LOCAL)
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
