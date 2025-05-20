# Function: <code>get_openreq4</code>

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
In net/ipv4/tcp_ipv4.c (ffffffff8177b62b)
Location: net/ipv4/tcp_ipv4.c:2132
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
In net/ipv4/tcp_ipv4.c (ffffffff817e8ea9)
Location: net/ipv4/tcp_ipv4.c:2149
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
In net/ipv4/tcp_ipv4.c (ffffffff81819096)
Location: net/ipv4/tcp_ipv4.c:2193
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
In net/ipv4/tcp_ipv4.c (ffffffff818397aa)
Location: net/ipv4/tcp_ipv4.c:2249
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
In net/ipv4/tcp_ipv4.c (ffffffff818b8f3a)
Location: net/ipv4/tcp_ipv4.c:2228
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
In net/ipv4/tcp_ipv4.c (ffffffff8190e35b)
Location: net/ipv4/tcp_ipv4.c:2271
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
In net/ipv4/tcp_ipv4.c (ffffffff8193c74b)
Location: net/ipv4/tcp_ipv4.c:2356
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
In net/ipv4/tcp_ipv4.c (ffffffff819a0b96)
Location: net/ipv4/tcp_ipv4.c:2375
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
In net/ipv4/tcp_ipv4.c (ffffffff819d7769)
Location: net/ipv4/tcp_ipv4.c:2398
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
void get_openreq4(const struct request_sock *req, struct seq_file *f, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ac4460)
Location: net/ipv4/tcp_ipv4.c:2476
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
**Symbols:**

```
ffffffff81ac4460-ffffffff81ac452b: get_openreq4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void get_openreq4(const struct request_sock *req, struct seq_file *f, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81acfda0)
Location: net/ipv4/tcp_ipv4.c:2526
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
**Symbols:**

```
ffffffff81acfda0-ffffffff81acfe6b: get_openreq4 (STB_LOCAL)
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
In net/ipv4/tcp_ipv4.c (ffffffff81abb19c)
Location: net/ipv4/tcp_ipv4.c:2544
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81b784ec)
Location: net/ipv4/tcp_ipv4.c:2577
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81d081b8)
Location: net/ipv4/tcp_ipv4.c:2543
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81eccc88)
Location: net/ipv4/tcp_ipv4.c:2617
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81f2b968)
Location: net/ipv4/tcp_ipv4.c:2625
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ff06a8)
Location: net/ipv4/tcp_ipv4.c:2829
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp4_seq_show
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
In net/ipv4/tcp_ipv4.c (ffff800010c8a628)
Location: net/ipv4/tcp_ipv4.c:2398
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
In net/ipv4/tcp_ipv4.c (c0d9a7a4)
Location: net/ipv4/tcp_ipv4.c:2398
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
In net/ipv4/tcp_ipv4.c (c000000000d98ac0)
Location: net/ipv4/tcp_ipv4.c:2398
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
In net/ipv4/tcp_ipv4.c (ffffffe0007eb73e)
Location: net/ipv4/tcp_ipv4.c:2398
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
In net/ipv4/tcp_ipv4.c (ffffffff819775d9)
Location: net/ipv4/tcp_ipv4.c:2398
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
In net/ipv4/tcp_ipv4.c (ffffffff81931099)
Location: net/ipv4/tcp_ipv4.c:2398
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
In net/ipv4/tcp_ipv4.c (ffffffff819e1da9)
Location: net/ipv4/tcp_ipv4.c:2398
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
In net/ipv4/tcp_ipv4.c (ffffffff819ebaf9)
Location: net/ipv4/tcp_ipv4.c:2398
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
</ul>
