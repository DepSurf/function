# Function: <code>copy_bpf_fprog_from_user</code>

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
int copy_bpf_fprog_from_user(struct sock_fprog *dst, sockptr_t src, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2f010)
Location: net/core/filter.c:84
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/packet/af_packet.c:fanout_set_data
```
**Symbols:**

```
ffffffff81a2f010-ffffffff81a2f101: copy_bpf_fprog_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int copy_bpf_fprog_from_user(struct sock_fprog *dst, sockptr_t src, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a15670)
Location: net/core/filter.c:84
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81a15670-ffffffff81a15761: copy_bpf_fprog_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int copy_bpf_fprog_from_user(struct sock_fprog *dst, sockptr_t src, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac70c0)
Location: net/core/filter.c:85
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81ac70c0-ffffffff81ac71b1: copy_bpf_fprog_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int copy_bpf_fprog_from_user(struct sock_fprog *dst, sockptr_t src, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c42ab0)
Location: net/core/filter.c:86
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/sock.c:sock_setsockopt
  - net/packet/af_packet.c:packet_setsockopt
```
**Symbols:**

```
ffffffff81c42ab0-ffffffff81c42b97: copy_bpf_fprog_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int copy_bpf_fprog_from_user(struct sock_fprog *dst, sockptr_t src, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81dfa020)
Location: net/core/filter.c:88
Inline: False
Direct callers:
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/packet/af_packet.c:fanout_set_data
```
**Symbols:**

```
ffffffff81dfa020-ffffffff81dfa110: copy_bpf_fprog_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int copy_bpf_fprog_from_user(struct sock_fprog *dst, sockptr_t src, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e6d400)
Location: net/core/filter.c:88
Inline: False
Direct callers:
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/packet/af_packet.c:fanout_set_data
```
**Symbols:**

```
ffffffff81e6d400-ffffffff81e6d4f0: copy_bpf_fprog_from_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int copy_bpf_fprog_from_user(struct sock_fprog *dst, sockptr_t src, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f2ce00)
Location: net/core/filter.c:93
Inline: False
Direct callers:
  - net/core/sock.c:sk_setsockopt
  - net/core/sock.c:sk_setsockopt
  - net/packet/af_packet.c:fanout_set_data
```
**Symbols:**

```
ffffffff81f2ce00-ffffffff81f2cef0: copy_bpf_fprog_from_user (STB_GLOBAL)
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
