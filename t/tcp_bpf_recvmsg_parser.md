# Function: <code>tcp_bpf_recvmsg_parser</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcp_bpf_recvmsg_parser(struct sock *sk, struct msghdr *msg, size_t len, int nonblock, int flags, int *addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81bc7f70)
Location: net/ipv4/tcp_bpf.c:175
Inline: False
```
**Symbols:**

```
ffffffff81bc7f70-ffffffff81bc81a2: tcp_bpf_recvmsg_parser (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcp_bpf_recvmsg_parser(struct sock *sk, struct msghdr *msg, size_t len, int flags, int *addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81d5d560)
Location: net/ipv4/tcp_bpf.c:174
Inline: False
```
**Symbols:**

```
ffffffff81d5d560-ffffffff81d5d7de: tcp_bpf_recvmsg_parser (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcp_bpf_recvmsg_parser(struct sock *sk, struct msghdr *msg, size_t len, int flags, int *addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81f27c60)
Location: net/ipv4/tcp_bpf.c:177
Inline: False
```
**Symbols:**

```
ffffffff81f27c60-ffffffff81f27ede: tcp_bpf_recvmsg_parser (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcp_bpf_recvmsg_parser(struct sock *sk, struct msghdr *msg, size_t len, int flags, int *addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81f877e0)
Location: net/ipv4/tcp_bpf.c:218
Inline: False
```
**Symbols:**

```
ffffffff81f877e0-ffffffff81f87b9c: tcp_bpf_recvmsg_parser (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcp_bpf_recvmsg_parser(struct sock *sk, struct msghdr *msg, size_t len, int flags, int *addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff8204ee60)
Location: net/ipv4/tcp_bpf.c:218
Inline: False
```
**Symbols:**

```
ffffffff8204ee60-ffffffff8204f2aa: tcp_bpf_recvmsg_parser (STB_LOCAL)
```
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int nonblock</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, msg, len, nonblock, flags, addr_len</code> ➡️ <code>sk, msg, len, flags, addr_len</code>
</li>
</ul>
</details>
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
