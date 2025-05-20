# Function: <code>__unix_dgram_recvmsg</code>

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
int __unix_dgram_recvmsg(struct sock *sk, struct msghdr *msg, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81bea680)
Location: net/unix/af_unix.c:2282
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
**Symbols:**

```
ffffffff81bea680-ffffffff81beac34: __unix_dgram_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __unix_dgram_recvmsg(struct sock *sk, struct msghdr *msg, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81d82a20)
Location: net/unix/af_unix.c:2369
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
**Symbols:**

```
ffffffff81d82a20-ffffffff81d82eab: __unix_dgram_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __unix_dgram_recvmsg(struct sock *sk, struct msghdr *msg, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81f50030)
Location: net/unix/af_unix.c:2424
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
**Symbols:**

```
ffffffff81f50030-ffffffff81f504bb: __unix_dgram_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __unix_dgram_recvmsg(struct sock *sk, struct msghdr *msg, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81faf880)
Location: net/unix/af_unix.c:2341
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_recvmsg
```
**Symbols:**

```
ffffffff81faf880-ffffffff81fafe2c: __unix_dgram_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __unix_dgram_recvmsg(struct sock *sk, struct msghdr *msg, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8207ce80)
Location: net/unix/af_unix.c:2347
Inline: False
Direct callers:
  - net/unix/af_unix.c:unix_seqpacket_recvmsg
```
**Symbols:**

```
ffffffff8207ce80-ffffffff8207d48b: __unix_dgram_recvmsg (STB_GLOBAL)
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
