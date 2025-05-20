# Function: <code>tcp_bpf_update_proto</code>

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
int tcp_bpf_update_proto(struct sock *sk, struct sk_psock *psock, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81b048d0)
Location: net/ipv4/tcp_bpf.c:502
Inline: False
```
**Symbols:**

```
ffffffff81b048d0-ffffffff81b04a95: tcp_bpf_update_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcp_bpf_update_proto(struct sock *sk, struct sk_psock *psock, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81bc6c40)
Location: net/ipv4/tcp_bpf.c:587
Inline: False
```
**Symbols:**

```
ffffffff81bc6c40-ffffffff81bc6eab: tcp_bpf_update_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcp_bpf_update_proto(struct sock *sk, struct sk_psock *psock, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81d5bda0)
Location: net/ipv4/tcp_bpf.c:588
Inline: False
```
**Symbols:**

```
ffffffff81d5bda0-ffffffff81d5bfe2: tcp_bpf_update_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcp_bpf_update_proto(struct sock *sk, struct sk_psock *psock, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81f26790)
Location: net/ipv4/tcp_bpf.c:597
Inline: False
```
**Symbols:**

```
ffffffff81f26790-ffffffff81f269d7: tcp_bpf_update_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcp_bpf_update_proto(struct sock *sk, struct sk_psock *psock, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81f86460)
Location: net/ipv4/tcp_bpf.c:635
Inline: False
```
**Symbols:**

```
ffffffff81f86460-ffffffff81f8669e: tcp_bpf_update_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcp_bpf_update_proto(struct sock *sk, struct sk_psock *psock, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff8204da60)
Location: net/ipv4/tcp_bpf.c:649
Inline: False
```
**Symbols:**

```
ffffffff8204da60-ffffffff8204dca3: tcp_bpf_update_proto (STB_GLOBAL)
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
