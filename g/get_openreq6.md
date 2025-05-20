# Function: <code>get_openreq6</code>

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
In net/ipv6/tcp_ipv6.c (ffffffff817ef6ca)
Location: net/ipv6/tcp_ipv6.c:1659
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
In net/ipv6/tcp_ipv6.c (ffffffff8185e2a9)
Location: net/ipv6/tcp_ipv6.c:1689
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
In net/ipv6/tcp_ipv6.c (ffffffff818903e6)
Location: net/ipv6/tcp_ipv6.c:1705
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
In net/ipv6/tcp_ipv6.c (ffffffff818b6915)
Location: net/ipv6/tcp_ipv6.c:1720
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
In net/ipv6/tcp_ipv6.c (ffffffff81939745)
Location: net/ipv6/tcp_ipv6.c:1733
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
In net/ipv6/tcp_ipv6.c (ffffffff81991a14)
Location: net/ipv6/tcp_ipv6.c:1768
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
In net/ipv6/tcp_ipv6.c (ffffffff819c8254)
Location: net/ipv6/tcp_ipv6.c:1772
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
In net/ipv6/tcp_ipv6.c (ffffffff81a36cf0)
Location: net/ipv6/tcp_ipv6.c:1804
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
In net/ipv6/tcp_ipv6.c (ffffffff81a6d8a2)
Location: net/ipv6/tcp_ipv6.c:1826
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
void get_openreq6(struct seq_file *seq, const struct request_sock *req, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81b66bf0)
Location: net/ipv6/tcp_ipv6.c:1898
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
**Symbols:**

```
ffffffff81b66bf0-ffffffff81b66cd7: get_openreq6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void get_openreq6(struct seq_file *seq, const struct request_sock *req, int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/tcp_ipv6.c (ffffffff81b75150)
Location: net/ipv6/tcp_ipv6.c:1935
Inline: False
Direct callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
```
**Symbols:**

```
ffffffff81b75150-ffffffff81b75237: get_openreq6 (STB_LOCAL)
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
In net/ipv6/tcp_ipv6.c (ffffffff81b63dab)
Location: net/ipv6/tcp_ipv6.c:1965
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv6/tcp_ipv6.c (ffffffff81c2b86b)
Location: net/ipv6/tcp_ipv6.c:1981
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv6/tcp_ipv6.c (ffffffff81dc8e0d)
Location: net/ipv6/tcp_ipv6.c:1950
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv6/tcp_ipv6.c (ffffffff81f99b1d)
Location: net/ipv6/tcp_ipv6.c:1955
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv6/tcp_ipv6.c (ffffffff81ffa4ed)
Location: net/ipv6/tcp_ipv6.c:1956
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv6/tcp_ipv6.c (ffffffff820c815d)
Location: net/ipv6/tcp_ipv6.c:2135
Inline: True
Inline callers:
  - net/ipv6/tcp_ipv6.c:tcp6_seq_show
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
In net/ipv6/tcp_ipv6.c (ffff800010d361b4)
Location: net/ipv6/tcp_ipv6.c:1826
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
In net/ipv6/tcp_ipv6.c (c0e390c4)
Location: net/ipv6/tcp_ipv6.c:1826
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
In net/ipv6/tcp_ipv6.c (c000000000e68240)
Location: net/ipv6/tcp_ipv6.c:1826
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
In net/ipv6/tcp_ipv6.c (ffffffe000873542)
Location: net/ipv6/tcp_ipv6.c:1826
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
In net/ipv6/tcp_ipv6.c (ffffffff81a0cf32)
Location: net/ipv6/tcp_ipv6.c:1826
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
In net/ipv6/tcp_ipv6.c (ffffffff819c9cf2)
Location: net/ipv6/tcp_ipv6.c:1826
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
In net/ipv6/tcp_ipv6.c (ffffffff81a779b2)
Location: net/ipv6/tcp_ipv6.c:1826
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
In net/ipv6/tcp_ipv6.c (ffffffff81a84122)
Location: net/ipv6/tcp_ipv6.c:1826
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
</ul>
