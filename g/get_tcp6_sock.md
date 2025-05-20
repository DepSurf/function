# Function: <code>get_tcp6_sock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff817ef45f)
Location: net/ipv6/tcp_ipv6.c:1691
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff8185e02f)
Location: net/ipv6/tcp_ipv6.c:1721
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff8189016c)
Location: net/ipv6/tcp_ipv6.c:1737
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff818b6754)
Location: net/ipv6/tcp_ipv6.c:1752
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81939584)
Location: net/ipv6/tcp_ipv6.c:1765
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81991844)
Location: net/ipv6/tcp_ipv6.c:1800
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff819c8084)
Location: net/ipv6/tcp_ipv6.c:1804
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a36b15)
Location: net/ipv6/tcp_ipv6.c:1836
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a6d6c5)
Location: net/ipv6/tcp_ipv6.c:1858
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void get_tcp6_sock(struct seq_file *seq, struct sock *sp, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81b66ce0)
Location: net/ipv6/tcp_ipv6.c:1930
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
**Symbols:**

```
ffffffff81b66ce0-ffffffff81b66f3a: get_tcp6_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void get_tcp6_sock(struct seq_file *seq, struct sock *sp, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81b75240)
Location: net/ipv6/tcp_ipv6.c:1967
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
**Symbols:**

```
ffffffff81b75240-ffffffff81b7549a: get_tcp6_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void get_tcp6_sock(struct seq_file *seq, struct sock *sp, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81b63af0)
Location: net/ipv6/tcp_ipv6.c:1997
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
**Symbols:**

```
ffffffff81b63af0-ffffffff81b63d4a: get_tcp6_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void get_tcp6_sock(struct seq_file *seq, struct sock *sp, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81c2b5b0)
Location: net/ipv6/tcp_ipv6.c:2013
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
**Symbols:**

```
ffffffff81c2b5b0-ffffffff81c2b80a: get_tcp6_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void get_tcp6_sock(struct seq_file *seq, struct sock *sp, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81dc8b30)
Location: net/ipv6/tcp_ipv6.c:1982
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
**Symbols:**

```
ffffffff81dc8b30-ffffffff81dc8d96: get_tcp6_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void get_tcp6_sock(struct seq_file *seq, struct sock *sp, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81f99830)
Location: net/ipv6/tcp_ipv6.c:1987
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
**Symbols:**

```
ffffffff81f99830-ffffffff81f99a96: get_tcp6_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void get_tcp6_sock(struct seq_file *seq, struct sock *sp, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81ffa200)
Location: net/ipv6/tcp_ipv6.c:1988
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
**Symbols:**

```
ffffffff81ffa200-ffffffff81ffa463: get_tcp6_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void get_tcp6_sock(struct seq_file *seq, struct sock *sp, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff820c7e70)
Location: net/ipv6/tcp_ipv6.c:2167
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
**Symbols:**

```
ffffffff820c7e70-ffffffff820c80df: get_tcp6_sock (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffff800010d35fa0)
Location: net/ipv6/tcp_ipv6.c:1858
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (c0e38e6c)
Location: net/ipv6/tcp_ipv6.c:1858
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (c000000000e681d0)
Location: net/ipv6/tcp_ipv6.c:1858
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffe0008734fa)
Location: net/ipv6/tcp_ipv6.c:1858
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a0cd55)
Location: net/ipv6/tcp_ipv6.c:1858
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff819c9b15)
Location: net/ipv6/tcp_ipv6.c:1858
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a777d5)
Location: net/ipv6/tcp_ipv6.c:1858
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81a83f45)
Location: net/ipv6/tcp_ipv6.c:1858
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
