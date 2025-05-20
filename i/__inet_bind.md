# Function: <code>__inet_bind</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __inet_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8192b230)
Location: net/ipv4/af_inet.c:456
Inline: False
Direct callers:
  - net/core/filter.c:bpf_bind
  - net/ipv4/af_inet.c:inet_bind
```
**Symbols:**

```
ffffffff8192b230-ffffffff8192b4ae: __inet_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __inet_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8195a6c0)
Location: net/ipv4/af_inet.c:457
Inline: False
Direct callers:
  - net/core/filter.c:bpf_bind
  - net/ipv4/af_inet.c:inet_bind
```
**Symbols:**

```
ffffffff8195a6c0-ffffffff8195a940: __inet_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __inet_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819bf280)
Location: net/ipv4/af_inet.c:457
Inline: False
Direct callers:
  - net/core/filter.c:bpf_bind
  - net/ipv4/af_inet.c:inet_bind
```
**Symbols:**

```
ffffffff819bf280-ffffffff819bf527: __inet_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __inet_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff819f5ec0)
Location: net/ipv4/af_inet.c:457
Inline: False
Direct callers:
  - net/core/filter.c:bpf_bind
  - net/ipv4/af_inet.c:inet_bind
```
**Symbols:**

```
ffffffff819f5ec0-ffffffff819f6167: __inet_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __inet_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ae43b0)
Location: net/ipv4/af_inet.c:458
Inline: False
Direct callers:
  - net/core/filter.c:bpf_bind
  - net/ipv4/af_inet.c:inet_bind
```
**Symbols:**

```
ffffffff81ae43b0-ffffffff81ae4661: __inet_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __inet_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81af12e0)
Location: net/ipv4/af_inet.c:461
Inline: False
Direct callers:
  - net/core/filter.c:bpf_bind
  - net/ipv4/af_inet.c:inet_bind
```
**Symbols:**

```
ffffffff81af12e0-ffffffff81af1591: __inet_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __inet_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81adcaa0)
Location: net/ipv4/af_inet.c:463
Inline: False
Direct callers:
  - net/core/filter.c:bpf_bind
  - net/ipv4/af_inet.c:inet_bind
```
**Symbols:**

```
ffffffff81adcaa0-ffffffff81adcd5c: __inet_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __inet_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81b9be90)
Location: net/ipv4/af_inet.c:463
Inline: False
Direct callers:
  - net/core/filter.c:bpf_bind
  - net/ipv4/af_inet.c:inet_bind
```
**Symbols:**

```
ffffffff81b9be90-ffffffff81b9c149: __inet_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __inet_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81d2ddb0)
Location: net/ipv4/af_inet.c:460
Inline: False
Direct callers:
  - net/core/filter.c:bpf_bind
  - net/ipv4/af_inet.c:inet_bind
```
**Symbols:**

```
ffffffff81d2ddb0-ffffffff81d2e08e: __inet_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __inet_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81ef5ce0)
Location: net/ipv4/af_inet.c:461
Inline: False
Direct callers:
  - net/core/filter.c:bpf_bind
  - net/ipv4/af_inet.c:inet_bind
```
**Symbols:**

```
ffffffff81ef5ce0-ffffffff81ef5fbb: __inet_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __inet_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81f55540)
Location: net/ipv4/af_inet.c:459
Inline: False
Direct callers:
  - net/core/filter.c:bpf_bind
  - net/ipv4/af_inet.c:inet_bind
```
**Symbols:**

```
ffffffff81f55540-ffffffff81f5581b: __inet_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __inet_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, u32 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8201b9a0)
Location: net/ipv4/af_inet.c:472
Inline: False
Direct callers:
  - net/core/filter.c:bpf_bind
  - net/ipv4/af_inet.c:inet_bind_sk
```
**Symbols:**

```
ffffffff8201b9a0-ffffffff8201bcc5: __inet_bind (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int __inet_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffff800010cac7a0)
Location: net/ipv4/af_inet.c:457
Inline: False
Direct callers:
  - net/core/filter.c:bpf_bind
  - net/ipv4/af_inet.c:inet_bind
```
**Symbols:**

```
ffff800010cac7a0-ffff800010caca24: __inet_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __inet_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c0db8d70)
Location: net/ipv4/af_inet.c:457
Inline: False
Direct callers:
  - net/core/filter.c:bpf_bind
  - net/ipv4/af_inet.c:inet_bind
```
**Symbols:**

```
c0db8d70-c0db8fec: __inet_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __inet_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (c000000000dc2610)
Location: net/ipv4/af_inet.c:457
Inline: False
Direct callers:
  - net/core/filter.c:bpf_bind
  - net/ipv4/af_inet.c:inet_bind
  - net/ipv4/af_inet.c:inet_bind
```
**Symbols:**

```
c000000000dc2610-c000000000dc2a08: __inet_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __inet_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffe00080671a)
Location: net/ipv4/af_inet.c:457
Inline: False
Direct callers:
  - net/core/filter.c:bpf_bind
  - net/ipv4/af_inet.c:inet_bind
```
**Symbols:**

```
ffffffe00080671a-ffffffe000806962: __inet_bind (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int __inet_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81995c60)
Location: net/ipv4/af_inet.c:457
Inline: False
Direct callers:
  - net/core/filter.c:bpf_bind
  - net/ipv4/af_inet.c:inet_bind
```
**Symbols:**

```
ffffffff81995c60-ffffffff81995f07: __inet_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __inet_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff8194f720)
Location: net/ipv4/af_inet.c:457
Inline: False
Direct callers:
  - net/core/filter.c:bpf_bind
  - net/ipv4/af_inet.c:inet_bind
```
**Symbols:**

```
ffffffff8194f720-ffffffff8194f9c7: __inet_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __inet_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81a00500)
Location: net/ipv4/af_inet.c:457
Inline: False
Direct callers:
  - net/core/filter.c:bpf_bind
  - net/ipv4/af_inet.c:inet_bind
```
**Symbols:**

```
ffffffff81a00500-ffffffff81a007a7: __inet_bind (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __inet_bind(struct sock *sk, struct sockaddr *uaddr, int addr_len, bool force_bind_address_no_port, bool with_lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/af_inet.c (ffffffff81a0a9c0)
Location: net/ipv4/af_inet.c:457
Inline: False
Direct callers:
  - net/core/filter.c:bpf_bind
  - net/ipv4/af_inet.c:inet_bind
```
**Symbols:**

```
ffffffff81a0a9c0-ffffffff81a0ac67: __inet_bind (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool force_bind_address_no_port</code>
</li>
<li>
<b>Param removed. </b>
<code>bool with_lock</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
