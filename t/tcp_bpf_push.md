# Function: <code>tcp_bpf_push</code>

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
int tcp_bpf_push(struct sock *sk, struct sk_msg *msg, u32 apply_bytes, int flags, bool uncharge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81976880)
Location: net/ipv4/tcp_bpf.c:212
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81976880-ffffffff81976ab6: tcp_bpf_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcp_bpf_push(struct sock *sk, struct sk_msg *msg, u32 apply_bytes, int flags, bool uncharge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff819e03f0)
Location: net/ipv4/tcp_bpf.c:215
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff819e03f0-ffffffff819e0643: tcp_bpf_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_bpf_push(struct sock *sk, struct sk_msg *msg, u32 apply_bytes, int flags, bool uncharge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81a17420)
Location: net/ipv4/tcp_bpf.c:215
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81a17420-ffffffff81a17673: tcp_bpf_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_bpf_push(struct sock *sk, struct sk_msg *msg, u32 apply_bytes, int flags, bool uncharge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81b08400)
Location: net/ipv4/tcp_bpf.c:142
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81b08400-ffffffff81b08656: tcp_bpf_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_bpf_push(struct sock *sk, struct sk_msg *msg, u32 apply_bytes, int flags, bool uncharge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81b16960)
Location: net/ipv4/tcp_bpf.c:146
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81b16960-ffffffff81b16bb3: tcp_bpf_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_bpf_push(struct sock *sk, struct sk_msg *msg, u32 apply_bytes, int flags, bool uncharge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81b04680)
Location: net/ipv4/tcp_bpf.c:66
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81b04680-ffffffff81b048cb: tcp_bpf_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcp_bpf_push(struct sock *sk, struct sk_msg *msg, u32 apply_bytes, int flags, bool uncharge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81bc69d0)
Location: net/ipv4/tcp_bpf.c:66
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81bc69d0-ffffffff81bc6c3c: tcp_bpf_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcp_bpf_push(struct sock *sk, struct sk_msg *msg, u32 apply_bytes, int flags, bool uncharge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81d5c160)
Location: net/ipv4/tcp_bpf.c:66
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81d5c160-ffffffff81d5c461: tcp_bpf_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcp_bpf_push(struct sock *sk, struct sk_msg *msg, u32 apply_bytes, int flags, bool uncharge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81f262e0)
Location: net/ipv4/tcp_bpf.c:70
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81f262e0-ffffffff81f265fd: tcp_bpf_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcp_bpf_push(struct sock *sk, struct sk_msg *msg, u32 apply_bytes, int flags, bool uncharge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81f85e70)
Location: net/ipv4/tcp_bpf.c:88
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81f85e70-ffffffff81f862be: tcp_bpf_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcp_bpf_push(struct sock *sk, struct sk_msg *msg, u32 apply_bytes, int flags, bool uncharge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff8204d450)
Location: net/ipv4/tcp_bpf.c:88
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff8204d450-ffffffff8204d89b: tcp_bpf_push (STB_LOCAL)
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
int tcp_bpf_push(struct sock *sk, struct sk_msg *msg, u32 apply_bytes, int flags, bool uncharge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffff800010cd3468)
Location: net/ipv4/tcp_bpf.c:215
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffff800010cd3468-ffff800010cd3688: tcp_bpf_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_bpf_push(struct sock *sk, struct sk_msg *msg, u32 apply_bytes, int flags, bool uncharge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (c0ddd1f0)
Location: net/ipv4/tcp_bpf.c:215
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
c0ddd1f0-c0ddd440: tcp_bpf_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_bpf_push(struct sock *sk, struct sk_msg *msg, u32 apply_bytes, int flags, bool uncharge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (c000000000df19d0)
Location: net/ipv4/tcp_bpf.c:215
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
c000000000df19d0-c000000000df1cf4: tcp_bpf_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_bpf_push(struct sock *sk, struct sk_msg *msg, u32 apply_bytes, int flags, bool uncharge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffe00082433a)
Location: net/ipv4/tcp_bpf.c:215
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffe00082433a-ffffffe000824520: tcp_bpf_push (STB_LOCAL)
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
int tcp_bpf_push(struct sock *sk, struct sk_msg *msg, u32 apply_bytes, int flags, bool uncharge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff819b6ab0)
Location: net/ipv4/tcp_bpf.c:215
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff819b6ab0-ffffffff819b6d03: tcp_bpf_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_bpf_push(struct sock *sk, struct sk_msg *msg, u32 apply_bytes, int flags, bool uncharge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff819738a0)
Location: net/ipv4/tcp_bpf.c:215
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff819738a0-ffffffff81973af3: tcp_bpf_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_bpf_push(struct sock *sk, struct sk_msg *msg, u32 apply_bytes, int flags, bool uncharge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81a21530)
Location: net/ipv4/tcp_bpf.c:215
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81a21530-ffffffff81a21783: tcp_bpf_push (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_bpf_push(struct sock *sk, struct sk_msg *msg, u32 apply_bytes, int flags, bool uncharge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81a2c880)
Location: net/ipv4/tcp_bpf.c:215
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_send_verdict
  - net/ipv4/tcp_bpf.c:tcp_bpf_sendmsg_redir
```
**Symbols:**

```
ffffffff81a2c880-ffffffff81a2cad3: tcp_bpf_push (STB_LOCAL)
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
