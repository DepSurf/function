# Function: <code>tcp_bpf_sendmsg_redir</code>

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
int tcp_bpf_sendmsg_redir(struct sock *sk, struct sk_msg *msg, u32 bytes, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81976f60)
Location: net/ipv4/tcp_bpf.c:280
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
```
**Symbols:**

```
ffffffff81976f60-ffffffff819772d9: tcp_bpf_sendmsg_redir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcp_bpf_sendmsg_redir(struct sock *sk, struct sk_msg *msg, u32 bytes, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff819e0aa0)
Location: net/ipv4/tcp_bpf.c:283
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
```
**Symbols:**

```
ffffffff819e0aa0-ffffffff819e0dff: tcp_bpf_sendmsg_redir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_bpf_sendmsg_redir(struct sock *sk, struct sk_msg *msg, u32 bytes, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81a17ad0)
Location: net/ipv4/tcp_bpf.c:283
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
```
**Symbols:**

```
ffffffff81a17ad0-ffffffff81a17e2f: tcp_bpf_sendmsg_redir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_bpf_sendmsg_redir(struct sock *sk, struct sk_msg *msg, u32 bytes, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81b08a50)
Location: net/ipv4/tcp_bpf.c:210
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
```
**Symbols:**

```
ffffffff81b08a50-ffffffff81b08b69: tcp_bpf_sendmsg_redir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_bpf_sendmsg_redir(struct sock *sk, struct sk_msg *msg, u32 bytes, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81b17160)
Location: net/ipv4/tcp_bpf.c:214
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
```
**Symbols:**

```
ffffffff81b17160-ffffffff81b17284: tcp_bpf_sendmsg_redir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_bpf_sendmsg_redir(struct sock *sk, struct sk_msg *msg, u32 bytes, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81b04d50)
Location: net/ipv4/tcp_bpf.c:134
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
```
**Symbols:**

```
ffffffff81b04d50-ffffffff81b04e7b: tcp_bpf_sendmsg_redir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcp_bpf_sendmsg_redir(struct sock *sk, struct sk_msg *msg, u32 bytes, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81bc75b0)
Location: net/ipv4/tcp_bpf.c:134
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
```
**Symbols:**

```
ffffffff81bc75b0-ffffffff81bc76db: tcp_bpf_sendmsg_redir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcp_bpf_sendmsg_redir(struct sock *sk, struct sk_msg *msg, u32 bytes, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81d5cad0)
Location: net/ipv4/tcp_bpf.c:134
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
```
**Symbols:**

```
ffffffff81d5cad0-ffffffff81d5cc17: tcp_bpf_sendmsg_redir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcp_bpf_sendmsg_redir(struct sock *sk, bool ingress, struct sk_msg *msg, u32 bytes, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81f27050)
Location: net/ipv4/tcp_bpf.c:138
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
```
**Symbols:**

```
ffffffff81f27050-ffffffff81f2718f: tcp_bpf_sendmsg_redir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcp_bpf_sendmsg_redir(struct sock *sk, bool ingress, struct sk_msg *msg, u32 bytes, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81f86d10)
Location: net/ipv4/tcp_bpf.c:161
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
```
**Symbols:**

```
ffffffff81f86d10-ffffffff81f86e47: tcp_bpf_sendmsg_redir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcp_bpf_sendmsg_redir(struct sock *sk, bool ingress, struct sk_msg *msg, u32 bytes, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff8204e350)
Location: net/ipv4/tcp_bpf.c:161
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
```
**Symbols:**

```
ffffffff8204e350-ffffffff8204e487: tcp_bpf_sendmsg_redir (STB_GLOBAL)
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
int tcp_bpf_sendmsg_redir(struct sock *sk, struct sk_msg *msg, u32 bytes, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffff800010cd3688)
Location: net/ipv4/tcp_bpf.c:283
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
```
**Symbols:**

```
ffff800010cd3688-ffff800010cd399c: tcp_bpf_sendmsg_redir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_bpf_sendmsg_redir(struct sock *sk, struct sk_msg *msg, u32 bytes, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (c0ddd54c)
Location: net/ipv4/tcp_bpf.c:283
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
```
**Symbols:**

```
c0ddd54c-c0ddd880: tcp_bpf_sendmsg_redir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_bpf_sendmsg_redir(struct sock *sk, struct sk_msg *msg, u32 bytes, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (c000000000df2750)
Location: net/ipv4/tcp_bpf.c:283
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
```
**Symbols:**

```
c000000000df2750-c000000000df2bec: tcp_bpf_sendmsg_redir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_bpf_sendmsg_redir(struct sock *sk, struct sk_msg *msg, u32 bytes, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffe000824634)
Location: net/ipv4/tcp_bpf.c:283
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
```
**Symbols:**

```
ffffffe000824634-ffffffe0008248b4: tcp_bpf_sendmsg_redir (STB_GLOBAL)
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
int tcp_bpf_sendmsg_redir(struct sock *sk, struct sk_msg *msg, u32 bytes, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff819b7160)
Location: net/ipv4/tcp_bpf.c:283
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
```
**Symbols:**

```
ffffffff819b7160-ffffffff819b74bf: tcp_bpf_sendmsg_redir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_bpf_sendmsg_redir(struct sock *sk, struct sk_msg *msg, u32 bytes, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81973f50)
Location: net/ipv4/tcp_bpf.c:283
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
```
**Symbols:**

```
ffffffff81973f50-ffffffff819742af: tcp_bpf_sendmsg_redir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_bpf_sendmsg_redir(struct sock *sk, struct sk_msg *msg, u32 bytes, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81a21be0)
Location: net/ipv4/tcp_bpf.c:283
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
```
**Symbols:**

```
ffffffff81a21be0-ffffffff81a21f3f: tcp_bpf_sendmsg_redir (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_bpf_sendmsg_redir(struct sock *sk, struct sk_msg *msg, u32 bytes, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81a2cf60)
Location: net/ipv4/tcp_bpf.c:283
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
```
**Symbols:**

```
ffffffff81a2cf60-ffffffff81a2d2c7: tcp_bpf_sendmsg_redir (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool ingress</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, msg, bytes, flags</code> ➡️ <code>sk, ingress, msg, bytes, flags</code>
</li>
</ul>
</details>
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
