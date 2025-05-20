# Function: <code>tcp_recvmsg_locked</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tcp_recvmsg_locked(struct sock *sk, struct msghdr *msg, size_t len, int nonblock, int flags, struct scm_timestamping_internal *tss, int *cmsg_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2254
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:receive_fallback_to_copy
```
**Symbols:**

```
ffffffff81ab5ff0-ffffffff81ab69d1: tcp_recvmsg_locked (STB_LOCAL)
ffffffff81c325b4-ffffffff81c325e7: tcp_recvmsg_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tcp_recvmsg_locked(struct sock *sk, struct msghdr *msg, size_t len, int nonblock, int flags, struct scm_timestamping_internal *tss, int *cmsg_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2297
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:receive_fallback_to_copy
```
**Symbols:**

```
ffffffff81aa11d0-ffffffff81aa1b94: tcp_recvmsg_locked (STB_LOCAL)
ffffffff81c2489f-ffffffff81c248d4: tcp_recvmsg_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tcp_recvmsg_locked(struct sock *sk, struct msghdr *msg, size_t len, int nonblock, int flags, struct scm_timestamping_internal *tss, int *cmsg_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2297
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:receive_fallback_to_copy
```
**Symbols:**

```
ffffffff81b5d160-ffffffff81b5db38: tcp_recvmsg_locked (STB_LOCAL)
ffffffff81d3a4ec-ffffffff81d3a58c: tcp_recvmsg_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tcp_recvmsg_locked(struct sock *sk, struct msghdr *msg, size_t len, int flags, struct scm_timestamping_internal *tss, int *cmsg_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2324
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:receive_fallback_to_copy
```
**Symbols:**

```
ffffffff81cebb70-ffffffff81cec4c1: tcp_recvmsg_locked (STB_LOCAL)
ffffffff81f06d25-ffffffff81f06db3: tcp_recvmsg_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tcp_recvmsg_locked(struct sock *sk, struct msghdr *msg, size_t len, int flags, struct scm_timestamping_internal *tss, int *cmsg_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2424
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:receive_fallback_to_copy
```
**Symbols:**

```
ffffffff81eafa30-ffffffff81eb03bf: tcp_recvmsg_locked (STB_LOCAL)
ffffffff820ae8ba-ffffffff820ae921: tcp_recvmsg_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tcp_recvmsg_locked(struct sock *sk, struct msghdr *msg, size_t len, int flags, struct scm_timestamping_internal *tss, int *cmsg_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2310
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:receive_fallback_to_copy
```
**Symbols:**

```
ffffffff81f0de80-ffffffff81f0e819: tcp_recvmsg_locked (STB_LOCAL)
ffffffff8212fd51-ffffffff8212fdb8: tcp_recvmsg_locked.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tcp_recvmsg_locked(struct sock *sk, struct msghdr *msg, size_t len, int flags, struct scm_timestamping_internal *tss, int *cmsg_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (0)
Location: net/ipv4/tcp.c:2317
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_recvmsg
  - net/ipv4/tcp.c:receive_fallback_to_copy
```
**Symbols:**

```
ffffffff81fd1f90-ffffffff81fd2969: tcp_recvmsg_locked (STB_LOCAL)
ffffffff82211a3d-ffffffff82211aa4: tcp_recvmsg_locked.cold (STB_LOCAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
<code>sk, msg, len, nonblock, flags, tss, cmsg_flags</code> ➡️ <code>sk, msg, len, flags, tss, cmsg_flags</code>
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
