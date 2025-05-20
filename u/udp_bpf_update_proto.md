# Function: <code>udp_bpf_update_proto</code>

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
int udp_bpf_update_proto(struct sock *sk, struct sk_psock *psock, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_bpf.c (ffffffff81b05b60)
Location: net/ipv4/udp_bpf.c:106
Inline: False
```
**Symbols:**

```
ffffffff81b05b60-ffffffff81b05c3f: udp_bpf_update_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int udp_bpf_update_proto(struct sock *sk, struct sk_psock *psock, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_bpf.c (ffffffff81bc86c0)
Location: net/ipv4/udp_bpf.c:139
Inline: False
```
**Symbols:**

```
ffffffff81bc86c0-ffffffff81bc879f: udp_bpf_update_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int udp_bpf_update_proto(struct sock *sk, struct sk_psock *psock, bool restore);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_bpf.c (ffffffff81d5ddc0)
Location: net/ipv4/udp_bpf.c:138
Inline: False
```
**Symbols:**

```
ffffffff81d5ddc0-ffffffff81d5deba: udp_bpf_update_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int udp_bpf_update_proto(struct sock *sk, struct sk_psock *psock, bool restore);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_bpf.c (ffffffff81f28420)
Location: net/ipv4/udp_bpf.c:138
Inline: True
```
**Symbols:**

```
ffffffff81f28420-ffffffff81f2853a: udp_bpf_update_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int udp_bpf_update_proto(struct sock *sk, struct sk_psock *psock, bool restore);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_bpf.c (ffffffff81f87f70)
Location: net/ipv4/udp_bpf.c:141
Inline: True
```
**Symbols:**

```
ffffffff81f87f70-ffffffff81f880a3: udp_bpf_update_proto (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int udp_bpf_update_proto(struct sock *sk, struct sk_psock *psock, bool restore);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp_bpf.c (ffffffff8204f690)
Location: net/ipv4/udp_bpf.c:141
Inline: True
```
**Symbols:**

```
ffffffff8204f690-ffffffff8204f7c3: udp_bpf_update_proto (STB_GLOBAL)
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
