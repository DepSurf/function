# Function: <code>__tcp_sock_set_quickack</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa8f08)
Location: net/ipv4/tcp.c:2918
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_quickack
  - net/ipv4/tcp.c:tcp_sock_set_quickack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab6cb8)
Location: net/ipv4/tcp.c:3176
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_quickack
  - net/ipv4/tcp.c:tcp_sock_set_quickack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa3368)
Location: net/ipv4/tcp.c:3230
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_quickack
  - net/ipv4/tcp.c:tcp_sock_set_quickack
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_sock_set_quickack(struct sock *sk, int val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81b5d059)
Location: net/ipv4/tcp.c:3254
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sock_set_quickack
```
**Symbols:**

```
ffffffff81b5d020-ffffffff81b5d095: __tcp_sock_set_quickack (STB_LOCAL)
ffffffff81d3a4d2-ffffffff81d3a4ec: __tcp_sock_set_quickack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_sock_set_quickack(struct sock *sk, int val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ceba39)
Location: net/ipv4/tcp.c:3272
Inline: True
Direct callers:
  - net/ipv4/tcp.c:tcp_sock_set_quickack
```
**Symbols:**

```
ffffffff81ceba00-ffffffff81ceba8d: __tcp_sock_set_quickack (STB_LOCAL)
ffffffff81f06d0b-ffffffff81f06d25: __tcp_sock_set_quickack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_sock_set_quickack(struct sock *sk, int val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81eaf8c9)
Location: net/ipv4/tcp.c:3371
Inline: True
Direct callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:tcp_sock_set_quickack
```
**Symbols:**

```
ffffffff81eaf890-ffffffff81eaf91d: __tcp_sock_set_quickack (STB_LOCAL)
ffffffff820ae8a0-ffffffff820ae8ba: __tcp_sock_set_quickack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_sock_set_quickack(struct sock *sk, int val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81f0dcf4)
Location: net/ipv4/tcp.c:3263
Inline: True
Direct callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:tcp_sock_set_quickack
```
**Symbols:**

```
ffffffff81f0dcc0-ffffffff81f0dd62: __tcp_sock_set_quickack (STB_LOCAL)
ffffffff8212fd38-ffffffff8212fd51: __tcp_sock_set_quickack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_sock_set_quickack(struct sock *sk, int val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81fd1e00)
Location: net/ipv4/tcp.c:3269
Inline: True
Direct callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:tcp_sock_set_quickack
```
**Symbols:**

```
ffffffff81fd1dd0-ffffffff81fd1e72: __tcp_sock_set_quickack (STB_LOCAL)
ffffffff82211a24-ffffffff82211a3d: __tcp_sock_set_quickack.cold (STB_LOCAL)
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
