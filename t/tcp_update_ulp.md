# Function: <code>tcp_update_ulp</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_update_ulp(struct sock *sk, struct proto *proto);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff819aa270)
Location: net/ipv4/tcp_ulp.c:99
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
```
**Symbols:**

```
ffffffff819aa270-ffffffff819aa29b: tcp_update_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_update_ulp(struct sock *sk, struct proto *proto, void (*write_space)(struct sock *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff819e0f30)
Location: net/ipv4/tcp_ulp.c:99
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
```
**Symbols:**

```
ffffffff819e0f30-ffffffff819e0f62: tcp_update_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_update_ulp(struct sock *sk, struct proto *proto, void (*write_space)(struct sock *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff81ace530)
Location: net/ipv4/tcp_ulp.c:103
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
```
**Symbols:**

```
ffffffff81ace530-ffffffff81ace551: tcp_update_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tcp_update_ulp(struct sock *sk, struct proto *proto, void (*write_space)(struct sock *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff81ada540)
Location: net/ipv4/tcp_ulp.c:103
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
```
**Symbols:**

```
ffffffff81ada540-ffffffff81ada561: tcp_update_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tcp_update_ulp(struct sock *sk, struct proto *proto, void (*write_space)(struct sock *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff81ac55a0)
Location: net/ipv4/tcp_ulp.c:103
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
```
**Symbols:**

```
ffffffff81ac55a0-ffffffff81ac55c1: tcp_update_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_update_ulp(struct sock *sk, struct proto *proto, void (*write_space)(struct sock *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff81b83db0)
Location: net/ipv4/tcp_ulp.c:103
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
```
**Symbols:**

```
ffffffff81b83db0-ffffffff81b83dd1: tcp_update_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_update_ulp(struct sock *sk, struct proto *proto, void (*write_space)(struct sock *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff81d14520)
Location: net/ipv4/tcp_ulp.c:103
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
```
**Symbols:**

```
ffffffff81d14520-ffffffff81d14559: tcp_update_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_update_ulp(struct sock *sk, struct proto *proto, void (*write_space)(struct sock *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff81eda5e0)
Location: net/ipv4/tcp_ulp.c:103
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
```
**Symbols:**

```
ffffffff81eda5e0-ffffffff81eda619: tcp_update_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_update_ulp(struct sock *sk, struct proto *proto, void (*write_space)(struct sock *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff81f396c0)
Location: net/ipv4/tcp_ulp.c:103
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
```
**Symbols:**

```
ffffffff81f396c0-ffffffff81f396f9: tcp_update_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_update_ulp(struct sock *sk, struct proto *proto, void (*write_space)(struct sock *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff81fff7b0)
Location: net/ipv4/tcp_ulp.c:103
Inline: False
Direct callers:
  - net/ipv4/tcp_bpf.c:tcp_bpf_update_proto
```
**Symbols:**

```
ffffffff81fff7b0-ffffffff81fff7e9: tcp_update_ulp (STB_GLOBAL)
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
void tcp_update_ulp(struct sock *sk, struct proto *proto, void (*write_space)(struct sock *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffff800010c94e98)
Location: net/ipv4/tcp_ulp.c:99
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
```
**Symbols:**

```
ffff800010c94e98-ffff800010c94f04: tcp_update_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_update_ulp(struct sock *sk, struct proto *proto, void (*write_space)(struct sock *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (c0da3698)
Location: net/ipv4/tcp_ulp.c:99
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
```
**Symbols:**

```
c0da3698-c0da36dc: tcp_update_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_update_ulp(struct sock *sk, struct proto *proto, void (*write_space)(struct sock *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (c000000000da5a50)
Location: net/ipv4/tcp_ulp.c:99
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
```
**Symbols:**

```
c000000000da5a50-c000000000da5abc: tcp_update_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_update_ulp(struct sock *sk, struct proto *proto, void (*write_space)(struct sock *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffe0007f41ac)
Location: net/ipv4/tcp_ulp.c:99
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
```
**Symbols:**

```
ffffffe0007f41ac-ffffffe0007f4200: tcp_update_ulp (STB_GLOBAL)
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
void tcp_update_ulp(struct sock *sk, struct proto *proto, void (*write_space)(struct sock *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff81980da0)
Location: net/ipv4/tcp_ulp.c:99
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
```
**Symbols:**

```
ffffffff81980da0-ffffffff81980dd2: tcp_update_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_update_ulp(struct sock *sk, struct proto *proto, void (*write_space)(struct sock *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff8193a860)
Location: net/ipv4/tcp_ulp.c:99
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
```
**Symbols:**

```
ffffffff8193a860-ffffffff8193a892: tcp_update_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_update_ulp(struct sock *sk, struct proto *proto, void (*write_space)(struct sock *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff819eb570)
Location: net/ipv4/tcp_ulp.c:99
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
```
**Symbols:**

```
ffffffff819eb570-ffffffff819eb5a2: tcp_update_ulp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_update_ulp(struct sock *sk, struct proto *proto, void (*write_space)(struct sock *));
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ulp.c (ffffffff819f5400)
Location: net/ipv4/tcp_ulp.c:99
Inline: False
Direct callers:
  - net/core/skmsg.c:sk_psock_drop
```
**Symbols:**

```
ffffffff819f5400-ffffffff819f5432: tcp_update_ulp (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void (*write_space)(struct sock *)</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
