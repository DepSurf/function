# Function: <code>tcp_build_frag</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *tcp_build_frag(struct sock *sk, int size_goal, int flags, struct page *page, int offset, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab51d0)
Location: net/ipv4/tcp.c:967
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
**Symbols:**

```
ffffffff81ab51d0-ffffffff81ab554d: tcp_build_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *tcp_build_frag(struct sock *sk, int size_goal, int flags, struct page *page, int offset, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa03c0)
Location: net/ipv4/tcp.c:966
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
**Symbols:**

```
ffffffff81aa03c0-ffffffff81aa0737: tcp_build_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *tcp_build_frag(struct sock *sk, int size_goal, int flags, struct page *page, int offset, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81b5c1e0)
Location: net/ipv4/tcp.c:963
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_sendpages
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
**Symbols:**

```
ffffffff81b5c1e0-ffffffff81b5c557: tcp_build_frag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *tcp_build_frag(struct sock *sk, int size_goal, int flags, struct page *page, int offset, size_t *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ce9c70)
Location: net/ipv4/tcp.c:972
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_sendpages
```
**Symbols:**

```
ffffffff81ce9c70-ffffffff81cea013: tcp_build_frag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *tcp_build_frag(struct sock *sk, int size_goal, int flags, struct page *page, int offset, size_t *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ead900)
Location: net/ipv4/tcp.c:974
Inline: False
Direct callers:
  - net/ipv4/tcp.c:do_tcp_sendpages
```
**Symbols:**

```
ffffffff81ead900-ffffffff81eadc43: tcp_build_frag (STB_LOCAL)
```
</details>
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
