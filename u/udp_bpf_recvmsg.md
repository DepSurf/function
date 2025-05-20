# Function: <code>udp_bpf_recvmsg</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int udp_bpf_recvmsg(struct sock *sk, struct msghdr *msg, size_t len, int nonblock, int flags, int *addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_bpf.c (ffffffff81b05c70)
Location: net/ipv4/udp_bpf.c:24
Inline: False
```
**Symbols:**

```
ffffffff81b05c70-ffffffff81b05e7a: udp_bpf_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int udp_bpf_recvmsg(struct sock *sk, struct msghdr *msg, size_t len, int nonblock, int flags, int *addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_bpf.c (ffffffff81bc8980)
Location: net/ipv4/udp_bpf.c:63
Inline: False
```
**Symbols:**

```
ffffffff81bc8980-ffffffff81bc8b64: udp_bpf_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int udp_bpf_recvmsg(struct sock *sk, struct msghdr *msg, size_t len, int flags, int *addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_bpf.c (ffffffff81d5df10)
Location: net/ipv4/udp_bpf.c:62
Inline: False
```
**Symbols:**

```
ffffffff81d5df10-ffffffff81d5e305: udp_bpf_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int udp_bpf_recvmsg(struct sock *sk, struct msghdr *msg, size_t len, int flags, int *addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_bpf.c (ffffffff81f28720)
Location: net/ipv4/udp_bpf.c:62
Inline: False
```
**Symbols:**

```
ffffffff81f28720-ffffffff81f2894c: udp_bpf_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int udp_bpf_recvmsg(struct sock *sk, struct msghdr *msg, size_t len, int flags, int *addr_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp_bpf.c (ffffffff81f88290)
Location: net/ipv4/udp_bpf.c:62
Inline: True
```
**Symbols:**

```
ffffffff81f884a0-ffffffff81f88500: udp_bpf_recvmsg (STB_LOCAL)
ffffffff81f88290-ffffffff81f88482: udp_bpf_recvmsg.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int udp_bpf_recvmsg(struct sock *sk, struct msghdr *msg, size_t len, int flags, int *addr_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp_bpf.c (ffffffff8204f9b0)
Location: net/ipv4/udp_bpf.c:62
Inline: True
```
**Symbols:**

```
ffffffff8204fbc0-ffffffff8204fc20: udp_bpf_recvmsg (STB_LOCAL)
ffffffff8204f9b0-ffffffff8204fba2: udp_bpf_recvmsg.part.0 (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
