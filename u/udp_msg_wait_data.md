# Function: <code>udp_msg_wait_data</code>

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
int udp_msg_wait_data(struct sock *sk, struct sk_psock *psock, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_bpf.c (ffffffff81bc87d0)
Location: net/ipv4/udp_bpf.c:39
Inline: False
Direct callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
**Symbols:**

```
ffffffff81bc87d0-ffffffff81bc897a: udp_msg_wait_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_bpf.c (ffffffff81d5e076)
Location: net/ipv4/udp_bpf.c:38
Inline: True
Inline callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int udp_msg_wait_data(struct sock *sk, struct sk_psock *psock, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_bpf.c (ffffffff81f28550)
Location: net/ipv4/udp_bpf.c:38
Inline: False
Direct callers:
  - net/ipv4/udp_bpf.c:udp_bpf_recvmsg
```
**Symbols:**

```
ffffffff81f28550-ffffffff81f28705: udp_msg_wait_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int udp_msg_wait_data(struct sock *sk, struct sk_psock *psock, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_bpf.c (ffffffff81f880c0)
Location: net/ipv4/udp_bpf.c:38
Inline: False
```
**Symbols:**

```
ffffffff81f880c0-ffffffff81f88275: udp_msg_wait_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int udp_msg_wait_data(struct sock *sk, struct sk_psock *psock, long int timeo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_bpf.c (ffffffff8204f7e0)
Location: net/ipv4/udp_bpf.c:38
Inline: False
```
**Symbols:**

```
ffffffff8204f7e0-ffffffff8204f995: udp_msg_wait_data (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
