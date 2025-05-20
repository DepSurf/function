# Function: <code>__unix_stream_recvmsg</code>

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
int __unix_stream_recvmsg(struct sock *sk, struct msghdr *msg, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81beacd0)
Location: net/unix/af_unix.c:2802
Inline: False
Direct callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
**Symbols:**

```
ffffffff81beacd0-ffffffff81bead3e: __unix_stream_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __unix_stream_recvmsg(struct sock *sk, struct msghdr *msg, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81d82f70)
Location: net/unix/af_unix.c:2887
Inline: False
Direct callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
**Symbols:**

```
ffffffff81d82f70-ffffffff81d82fea: __unix_stream_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __unix_stream_recvmsg(struct sock *sk, struct msghdr *msg, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81f505b0)
Location: net/unix/af_unix.c:2923
Inline: False
Direct callers:
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
  - net/unix/unix_bpf.c:unix_bpf_recvmsg
```
**Symbols:**

```
ffffffff81f505b0-ffffffff81f5062a: __unix_stream_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __unix_stream_recvmsg(struct sock *sk, struct msghdr *msg, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff81faff20)
Location: net/unix/af_unix.c:2838
Inline: False
```
**Symbols:**

```
ffffffff81faff20-ffffffff81faff9a: __unix_stream_recvmsg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __unix_stream_recvmsg(struct sock *sk, struct msghdr *msg, size_t size, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/af_unix.c (ffffffff8207d580)
Location: net/unix/af_unix.c:2855
Inline: False
```
**Symbols:**

```
ffffffff8207d580-ffffffff8207d5fa: __unix_stream_recvmsg (STB_GLOBAL)
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
