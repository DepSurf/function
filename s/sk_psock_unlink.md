# Function: <code>sk_psock_unlink</code>

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
void sk_psock_unlink(struct sock *sk, struct sk_psock_link *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818f33a0)
Location: net/core/sock_map.c:991
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_remove
```
**Symbols:**

```
ffffffff818f33a0-ffffffff818f3478: sk_psock_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sk_psock_unlink(struct sock *sk, struct sk_psock_link *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff81945870)
Location: net/core/sock_map.c:998
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_remove
```
**Symbols:**

```
ffffffff81945870-ffffffff81945948: sk_psock_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sk_psock_unlink(struct sock *sk, struct sk_psock_link *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8197a890)
Location: net/core/sock_map.c:1018
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_remove
```
**Symbols:**

```
ffffffff8197a890-ffffffff8197a968: sk_psock_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
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
void sk_psock_unlink(struct sock *sk, struct sk_psock_link *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffff800010c21c30)
Location: net/core/sock_map.c:1018
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_remove
```
**Symbols:**

```
ffff800010c21c30-ffff800010c21d80: sk_psock_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sk_psock_unlink(struct sock *sk, struct sk_psock_link *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c0d39214)
Location: net/core/sock_map.c:1018
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_remove
```
**Symbols:**

```
c0d39214-c0d392ec: sk_psock_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sk_psock_unlink(struct sock *sk, struct sk_psock_link *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (c000000000d14290)
Location: net/core/sock_map.c:1018
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_remove
```
**Symbols:**

```
c000000000d14290-c000000000d143e4: sk_psock_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sk_psock_unlink(struct sock *sk, struct sk_psock_link *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffe00079a9f8)
Location: net/core/sock_map.c:1018
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_remove
```
**Symbols:**

```
ffffffe00079a9f8-ffffffe00079ab06: sk_psock_unlink (STB_GLOBAL)
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
void sk_psock_unlink(struct sock *sk, struct sk_psock_link *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8191a700)
Location: net/core/sock_map.c:1018
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_remove
```
**Symbols:**

```
ffffffff8191a700-ffffffff8191a7d8: sk_psock_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sk_psock_unlink(struct sock *sk, struct sk_psock_link *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff818d44b0)
Location: net/core/sock_map.c:1018
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_remove
```
**Symbols:**

```
ffffffff818d44b0-ffffffff818d4588: sk_psock_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sk_psock_unlink(struct sock *sk, struct sk_psock_link *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8196b890)
Location: net/core/sock_map.c:1018
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_remove
```
**Symbols:**

```
ffffffff8196b890-ffffffff8196b968: sk_psock_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sk_psock_unlink(struct sock *sk, struct sk_psock_link *link);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock_map.c (ffffffff8198dd00)
Location: net/core/sock_map.c:1018
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_remove
```
**Symbols:**

```
ffffffff8198dd00-ffffffff8198ddd8: sk_psock_unlink (STB_GLOBAL)
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
