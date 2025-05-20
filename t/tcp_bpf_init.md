# Function: <code>tcp_bpf_init</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcp_bpf_init(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81978080)
Location: net/ipv4/tcp_bpf.c:673
Inline: False
```
**Symbols:**

```
ffffffff81978080-ffffffff8197820c: tcp_bpf_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcp_bpf_init(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff819e1b60)
Location: net/ipv4/tcp_bpf.c:678
Inline: False
```
**Symbols:**

```
ffffffff819e1b60-ffffffff819e1cf4: tcp_bpf_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_bpf_init(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81a18b50)
Location: net/ipv4/tcp_bpf.c:675
Inline: False
```
**Symbols:**

```
ffffffff81a18b50-ffffffff81a18ce4: tcp_bpf_init (STB_GLOBAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int tcp_bpf_init(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffff800010cd4650)
Location: net/ipv4/tcp_bpf.c:675
Inline: False
```
**Symbols:**

```
ffff800010cd4650-ffff800010cd4884: tcp_bpf_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_bpf_init(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (c0dde7b0)
Location: net/ipv4/tcp_bpf.c:675
Inline: False
Direct callers:
  - net/core/sock_map.c:sock_map_link
```
**Symbols:**

```
c0dde7b0-c0dde95c: tcp_bpf_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_bpf_init(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (c000000000df3960)
Location: net/ipv4/tcp_bpf.c:675
Inline: False
```
**Symbols:**

```
c000000000df3960-c000000000df3bc0: tcp_bpf_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_bpf_init(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffe00082553c)
Location: net/ipv4/tcp_bpf.c:675
Inline: False
```
**Symbols:**

```
ffffffe00082553c-ffffffe000825718: tcp_bpf_init (STB_GLOBAL)
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
int tcp_bpf_init(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff819b81e0)
Location: net/ipv4/tcp_bpf.c:675
Inline: False
```
**Symbols:**

```
ffffffff819b81e0-ffffffff819b8374: tcp_bpf_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_bpf_init(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81974fd0)
Location: net/ipv4/tcp_bpf.c:675
Inline: False
```
**Symbols:**

```
ffffffff81974fd0-ffffffff81975164: tcp_bpf_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_bpf_init(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81a22c60)
Location: net/ipv4/tcp_bpf.c:675
Inline: False
```
**Symbols:**

```
ffffffff81a22c60-ffffffff81a22df4: tcp_bpf_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_bpf_init(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_bpf.c (ffffffff81a2e030)
Location: net/ipv4/tcp_bpf.c:675
Inline: False
```
**Symbols:**

```
ffffffff81a2e030-ffffffff81a2e1d3: tcp_bpf_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
