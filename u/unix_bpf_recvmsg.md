# Function: <code>unix_bpf_recvmsg</code>

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
int unix_bpf_recvmsg(struct sock *sk, struct msghdr *msg, size_t len, int nonblock, int flags, int *addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/unix_bpf.c (ffffffff81beb710)
Location: net/unix/unix_bpf.c:50
Inline: False
```
**Symbols:**

```
ffffffff81beb710-ffffffff81beb8f8: unix_bpf_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int unix_bpf_recvmsg(struct sock *sk, struct msghdr *msg, size_t len, int flags, int *addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/unix_bpf.c (ffffffff81d838c0)
Location: net/unix/unix_bpf.c:50
Inline: False
```
**Symbols:**

```
ffffffff81d838c0-ffffffff81d83d7f: unix_bpf_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int unix_bpf_recvmsg(struct sock *sk, struct msghdr *msg, size_t len, int flags, int *addr_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/unix/unix_bpf.c (ffffffff81f510c0)
Location: net/unix/unix_bpf.c:50
Inline: False
```
**Symbols:**

```
ffffffff81f510c0-ffffffff81f5157f: unix_bpf_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int unix_bpf_recvmsg(struct sock *sk, struct msghdr *msg, size_t len, int flags, int *addr_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/unix/unix_bpf.c (ffffffff81fb0a20)
Location: net/unix/unix_bpf.c:50
Inline: True
```
**Symbols:**

```
ffffffff81fb0a20-ffffffff81fb0ebb: unix_bpf_recvmsg.part.0 (STB_LOCAL)
ffffffff81fb0ed0-ffffffff81fb0f00: unix_bpf_recvmsg (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int unix_bpf_recvmsg(struct sock *sk, struct msghdr *msg, size_t len, int flags, int *addr_len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/unix/unix_bpf.c (ffffffff8207e0c0)
Location: net/unix/unix_bpf.c:50
Inline: True
```
**Symbols:**

```
ffffffff8207e0c0-ffffffff8207e55b: unix_bpf_recvmsg.part.0 (STB_LOCAL)
ffffffff8207e570-ffffffff8207e5a0: unix_bpf_recvmsg (STB_LOCAL)
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
