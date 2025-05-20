# Function: <code>__tcp_bpf_recvmsg</code>

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
int __tcp_bpf_recvmsg(struct sock *sk, struct sk_psock *psock, struct msghdr *msg, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81976bf0)
Location: net/ipv4/tcp_bpf.c:42
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff81976bf0-ffffffff81976f51: __tcp_bpf_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __tcp_bpf_recvmsg(struct sock *sk, struct sk_psock *psock, struct msghdr *msg, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff819e0760)
Location: net/ipv4/tcp_bpf.c:45
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff819e0760-ffffffff819e0a97: __tcp_bpf_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __tcp_bpf_recvmsg(struct sock *sk, struct sk_psock *psock, struct msghdr *msg, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81a17790)
Location: net/ipv4/tcp_bpf.c:45
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff81a17790-ffffffff81a17ac7: __tcp_bpf_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __tcp_bpf_recvmsg(struct sock *sk, struct sk_psock *psock, struct msghdr *msg, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81b08f50)
Location: net/ipv4/tcp_bpf.c:13
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff81b08f50-ffffffff81b09276: __tcp_bpf_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __tcp_bpf_recvmsg(struct sock *sk, struct sk_psock *psock, struct msghdr *msg, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81b16e50)
Location: net/ipv4/tcp_bpf.c:13
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff81b16e50-ffffffff81b1715b: __tcp_bpf_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __tcp_bpf_recvmsg(struct sock *sk, struct sk_psock *psock, struct msghdr *msg, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffff800010cd31f0)
Location: net/ipv4/tcp_bpf.c:45
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffff800010cd31f0-ffff800010cd3464: __tcp_bpf_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __tcp_bpf_recvmsg(struct sock *sk, struct sk_psock *psock, struct msghdr *msg, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (c0dde1bc)
Location: net/ipv4/tcp_bpf.c:45
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
c0dde1bc-c0dde460: __tcp_bpf_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __tcp_bpf_recvmsg(struct sock *sk, struct sk_psock *psock, struct msghdr *msg, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (c000000000df1f20)
Location: net/ipv4/tcp_bpf.c:45
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
c000000000df1f20-c000000000df22dc: __tcp_bpf_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __tcp_bpf_recvmsg(struct sock *sk, struct sk_psock *psock, struct msghdr *msg, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffe000825088)
Location: net/ipv4/tcp_bpf.c:45
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffe000825088-ffffffe00082529a: __tcp_bpf_recvmsg (STB_GLOBAL)
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
int __tcp_bpf_recvmsg(struct sock *sk, struct sk_psock *psock, struct msghdr *msg, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff819b6e20)
Location: net/ipv4/tcp_bpf.c:45
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff819b6e20-ffffffff819b7157: __tcp_bpf_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __tcp_bpf_recvmsg(struct sock *sk, struct sk_psock *psock, struct msghdr *msg, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81973c10)
Location: net/ipv4/tcp_bpf.c:45
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff81973c10-ffffffff81973f47: __tcp_bpf_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __tcp_bpf_recvmsg(struct sock *sk, struct sk_psock *psock, struct msghdr *msg, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81a218a0)
Location: net/ipv4/tcp_bpf.c:45
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff81a218a0-ffffffff81a21bd7: __tcp_bpf_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __tcp_bpf_recvmsg(struct sock *sk, struct sk_psock *psock, struct msghdr *msg, int len, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81a2cc20)
Location: net/ipv4/tcp_bpf.c:45
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_recvmsg
```
**Symbols:**

```
ffffffff81a2cc20-ffffffff81a2cf57: __tcp_bpf_recvmsg (STB_GLOBAL)
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
