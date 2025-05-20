# Function: <code>get_tcp4_sock</code>

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
In net/ipv4/tcp_ipv4.c (ffffffff8177b3cd)
Location: net/ipv4/tcp_ipv4.c:2158
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
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
In net/ipv4/tcp_ipv4.c (ffffffff817e8c3d)
Location: net/ipv4/tcp_ipv4.c:2175
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
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
In net/ipv4/tcp_ipv4.c (ffffffff81818e2a)
Location: net/ipv4/tcp_ipv4.c:2219
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
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
In net/ipv4/tcp_ipv4.c (ffffffff818395f2)
Location: net/ipv4/tcp_ipv4.c:2275
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
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
In net/ipv4/tcp_ipv4.c (ffffffff818b8d82)
Location: net/ipv4/tcp_ipv4.c:2254
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
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
In net/ipv4/tcp_ipv4.c (ffffffff8190e192)
Location: net/ipv4/tcp_ipv4.c:2297
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
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
In net/ipv4/tcp_ipv4.c (ffffffff8193c582)
Location: net/ipv4/tcp_ipv4.c:2382
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
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
In net/ipv4/tcp_ipv4.c (ffffffff819a09c3)
Location: net/ipv4/tcp_ipv4.c:2401
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
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
In net/ipv4/tcp_ipv4.c (ffffffff819d7593)
Location: net/ipv4/tcp_ipv4.c:2424
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void get_tcp4_sock(struct sock *sk, struct seq_file *f, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ac4530)
Location: net/ipv4/tcp_ipv4.c:2502
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
**Symbols:**

```
ffffffff81ac4530-ffffffff81ac4776: get_tcp4_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void get_tcp4_sock(struct sock *sk, struct seq_file *f, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81acfe70)
Location: net/ipv4/tcp_ipv4.c:2552
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
**Symbols:**

```
ffffffff81acfe70-ffffffff81ad00b6: get_tcp4_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void get_tcp4_sock(struct sock *sk, struct seq_file *f, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81abaed0)
Location: net/ipv4/tcp_ipv4.c:2570
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
**Symbols:**

```
ffffffff81abaed0-ffffffff81abb112: get_tcp4_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void get_tcp4_sock(struct sock *sk, struct seq_file *f, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81b78220)
Location: net/ipv4/tcp_ipv4.c:2603
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
**Symbols:**

```
ffffffff81b78220-ffffffff81b78462: get_tcp4_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void get_tcp4_sock(struct sock *sk, struct seq_file *f, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81d07eb0)
Location: net/ipv4/tcp_ipv4.c:2569
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
**Symbols:**

```
ffffffff81d07eb0-ffffffff81d08119: get_tcp4_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void get_tcp4_sock(struct sock *sk, struct seq_file *f, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ecc970)
Location: net/ipv4/tcp_ipv4.c:2643
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
**Symbols:**

```
ffffffff81ecc970-ffffffff81eccbd9: get_tcp4_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void get_tcp4_sock(struct sock *sk, struct seq_file *f, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81f2b650)
Location: net/ipv4/tcp_ipv4.c:2651
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
**Symbols:**

```
ffffffff81f2b650-ffffffff81f2b8b6: get_tcp4_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void get_tcp4_sock(struct sock *sk, struct seq_file *f, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ff0380)
Location: net/ipv4/tcp_ipv4.c:2855
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
**Symbols:**

```
ffffffff81ff0380-ffffffff81ff05f2: get_tcp4_sock (STB_LOCAL)
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
In net/ipv4/tcp_ipv4.c (ffff800010c8a460)
Location: net/ipv4/tcp_ipv4.c:2424
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
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
In net/ipv4/tcp_ipv4.c (c0d9a59c)
Location: net/ipv4/tcp_ipv4.c:2424
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
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
In net/ipv4/tcp_ipv4.c (c000000000d98a50)
Location: net/ipv4/tcp_ipv4.c:2424
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
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
In net/ipv4/tcp_ipv4.c (ffffffe0007eb6f6)
Location: net/ipv4/tcp_ipv4.c:2424
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
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
In net/ipv4/tcp_ipv4.c (ffffffff81977403)
Location: net/ipv4/tcp_ipv4.c:2424
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
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
In net/ipv4/tcp_ipv4.c (ffffffff81930ec3)
Location: net/ipv4/tcp_ipv4.c:2424
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
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
In net/ipv4/tcp_ipv4.c (ffffffff819e1bd3)
Location: net/ipv4/tcp_ipv4.c:2424
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
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
In net/ipv4/tcp_ipv4.c (ffffffff819eb923)
Location: net/ipv4/tcp_ipv4.c:2424
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
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
