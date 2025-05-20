# Function: <code>tcp_read_sock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tcp_read_sock(struct sock *sk, read_descriptor_t *desc, sk_read_actor_t recv_actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81766030)
Location: net/ipv4/tcp.c:1494
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
**Symbols:**

```
ffffffff81766030-ffffffff81766217: tcp_read_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tcp_read_sock(struct sock *sk, read_descriptor_t *desc, sk_read_actor_t recv_actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff817d25a0)
Location: net/ipv4/tcp.c:1501
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
**Symbols:**

```
ffffffff817d25a0-ffffffff817d277d: tcp_read_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tcp_read_sock(struct sock *sk, read_descriptor_t *desc, sk_read_actor_t recv_actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81802390)
Location: net/ipv4/tcp.c:1533
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
**Symbols:**

```
ffffffff81802390-ffffffff8180256d: tcp_read_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tcp_read_sock(struct sock *sk, read_descriptor_t *desc, sk_read_actor_t recv_actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818224f0)
Location: net/ipv4/tcp.c:1577
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
**Symbols:**

```
ffffffff818224f0-ffffffff818226b1: tcp_read_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tcp_read_sock(struct sock *sk, read_descriptor_t *desc, sk_read_actor_t recv_actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818a15f0)
Location: net/ipv4/tcp.c:1641
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
**Symbols:**

```
ffffffff818a15f0-ffffffff818a17b4: tcp_read_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tcp_read_sock(struct sock *sk, read_descriptor_t *desc, sk_read_actor_t recv_actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff818f60d0)
Location: net/ipv4/tcp.c:1627
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
**Symbols:**

```
ffffffff818f60d0-ffffffff818f6285: tcp_read_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tcp_read_sock(struct sock *sk, read_descriptor_t *desc, sk_read_actor_t recv_actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81923c90)
Location: net/ipv4/tcp.c:1623
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
**Symbols:**

```
ffffffff81923c90-ffffffff81923e3f: tcp_read_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tcp_read_sock(struct sock *sk, read_descriptor_t *desc, sk_read_actor_t recv_actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81988bb0)
Location: net/ipv4/tcp.c:1613
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
**Symbols:**

```
ffffffff81988bb0-ffffffff81988e16: tcp_read_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tcp_read_sock(struct sock *sk, read_descriptor_t *desc, sk_read_actor_t recv_actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819c0010)
Location: net/ipv4/tcp.c:1614
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
**Symbols:**

```
ffffffff819c0010-ffffffff819c0276: tcp_read_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tcp_read_sock(struct sock *sk, read_descriptor_t *desc, sk_read_actor_t recv_actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa9fd0)
Location: net/ipv4/tcp.c:1621
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_read
  - net/mptcp/subflow.c:subflow_check_data_avail
```
**Symbols:**

```
ffffffff81aa9fd0-ffffffff81aaa236: tcp_read_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tcp_read_sock(struct sock *sk, read_descriptor_t *desc, sk_read_actor_t recv_actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab5aa0)
Location: net/ipv4/tcp.c:1637
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
**Symbols:**

```
ffffffff81ab5aa0-ffffffff81ab5d06: tcp_read_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tcp_read_sock(struct sock *sk, read_descriptor_t *desc, sk_read_actor_t recv_actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa0c80)
Location: net/ipv4/tcp.c:1639
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
**Symbols:**

```
ffffffff81aa0c80-ffffffff81aa0ee4: tcp_read_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tcp_read_sock(struct sock *sk, read_descriptor_t *desc, sk_read_actor_t recv_actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81b5cad0)
Location: net/ipv4/tcp.c:1636
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
**Symbols:**

```
ffffffff81b5cad0-ffffffff81b5cd3f: tcp_read_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tcp_read_sock(struct sock *sk, read_descriptor_t *desc, sk_read_actor_t recv_actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ceb4a0)
Location: net/ipv4/tcp.c:1664
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
**Symbols:**

```
ffffffff81ceb4a0-ffffffff81ceb6fe: tcp_read_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tcp_read_sock(struct sock *sk, read_descriptor_t *desc, sk_read_actor_t recv_actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81eaf130)
Location: net/ipv4/tcp.c:1680
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
**Symbols:**

```
ffffffff81eaf130-ffffffff81eaf38e: tcp_read_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tcp_read_sock(struct sock *sk, read_descriptor_t *desc, sk_read_actor_t recv_actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81f0d540)
Location: net/ipv4/tcp.c:1545
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
**Symbols:**

```
ffffffff81f0d540-ffffffff81f0d79a: tcp_read_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tcp_read_sock(struct sock *sk, read_descriptor_t *desc, sk_read_actor_t recv_actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81fd1650)
Location: net/ipv4/tcp.c:1553
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
**Symbols:**

```
ffffffff81fd1650-ffffffff81fd18aa: tcp_read_sock (STB_GLOBAL)
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
int tcp_read_sock(struct sock *sk, read_descriptor_t *desc, sk_read_actor_t recv_actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffff800010c70230)
Location: net/ipv4/tcp.c:1614
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
**Symbols:**

```
ffff800010c70230-ffff800010c70494: tcp_read_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tcp_read_sock(struct sock *sk, read_descriptor_t *desc, sk_read_actor_t recv_actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c0d7f4a4)
Location: net/ipv4/tcp.c:1614
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
**Symbols:**

```
c0d7f4a4-c0d7f740: tcp_read_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tcp_read_sock(struct sock *sk, read_descriptor_t *desc, sk_read_actor_t recv_actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (c000000000d77360)
Location: net/ipv4/tcp.c:1614
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
**Symbols:**

```
c000000000d77360-c000000000d776a4: tcp_read_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tcp_read_sock(struct sock *sk, read_descriptor_t *desc, sk_read_actor_t recv_actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffe0007d5e80)
Location: net/ipv4/tcp.c:1614
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
**Symbols:**

```
ffffffe0007d5e80-ffffffe0007d608e: tcp_read_sock (STB_GLOBAL)
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
int tcp_read_sock(struct sock *sk, read_descriptor_t *desc, sk_read_actor_t recv_actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff8195fe80)
Location: net/ipv4/tcp.c:1614
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
**Symbols:**

```
ffffffff8195fe80-ffffffff819600e6: tcp_read_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tcp_read_sock(struct sock *sk, read_descriptor_t *desc, sk_read_actor_t recv_actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81919970)
Location: net/ipv4/tcp.c:1614
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
**Symbols:**

```
ffffffff81919970-ffffffff81919bd6: tcp_read_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tcp_read_sock(struct sock *sk, read_descriptor_t *desc, sk_read_actor_t recv_actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819ca650)
Location: net/ipv4/tcp.c:1614
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
**Symbols:**

```
ffffffff819ca650-ffffffff819ca8b6: tcp_read_sock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tcp_read_sock(struct sock *sk, read_descriptor_t *desc, sk_read_actor_t recv_actor);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff819d41c0)
Location: net/ipv4/tcp.c:1614
Inline: False
Direct callers:
  - net/ipv4/tcp.c:tcp_splice_read
```
**Symbols:**

```
ffffffff819d41c0-ffffffff819d4426: tcp_read_sock (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
