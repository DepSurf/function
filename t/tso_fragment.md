# Function: <code>tso_fragment</code>

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
In net/ipv4/tcp_output.c (ffffffff81776ae8)
Location: net/ipv4/tcp_output.c:1702
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (ffffffff817e36f2)
Location: net/ipv4/tcp_output.c:1717
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (ffffffff81813d9c)
Location: net/ipv4/tcp_output.c:1766
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (ffffffff8183400d)
Location: net/ipv4/tcp_output.c:1847
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (ffffffff818b3418)
Location: net/ipv4/tcp_output.c:1869
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (ffffffff81908b33)
Location: net/ipv4/tcp_output.c:1861
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (ffffffff81936d7d)
Location: net/ipv4/tcp_output.c:1850
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (ffffffff8199c373)
Location: net/ipv4/tcp_output.c:1863
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (ffffffff819d2e13)
Location: net/ipv4/tcp_output.c:1882
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tso_fragment(struct sock *sk, struct sk_buff *skb, unsigned int len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81abd830)
Location: net/ipv4/tcp_output.c:1945
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81abd830-ffffffff81abda16: tso_fragment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tso_fragment(struct sock *sk, struct sk_buff *skb, unsigned int len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ac9050)
Location: net/ipv4/tcp_output.c:2113
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81ac9050-ffffffff81ac92fd: tso_fragment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tso_fragment(struct sock *sk, struct sk_buff *skb, unsigned int len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab3f60)
Location: net/ipv4/tcp_output.c:2114
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81ab3f60-ffffffff81ab4205: tso_fragment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tso_fragment(struct sock *sk, struct sk_buff *skb, unsigned int len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81b70e00)
Location: net/ipv4/tcp_output.c:2114
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81b70e00-ffffffff81b710ba: tso_fragment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tso_fragment(struct sock *sk, struct sk_buff *skb, unsigned int len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81d00270)
Location: net/ipv4/tcp_output.c:2119
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81d00270-ffffffff81d00553: tso_fragment (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tso_fragment(struct sock *sk, struct sk_buff *skb, unsigned int len, unsigned int mss_now, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ec5350)
Location: net/ipv4/tcp_output.c:2121
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81ec5350-ffffffff81ec5633: tso_fragment (STB_LOCAL)
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
In net/ipv4/tcp_output.c (ffffffff81f26719)
Location: net/ipv4/tcp_output.c:2113
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (ffffffff81feb0f9)
Location: net/ipv4/tcp_output.c:2156
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (ffff800010c859bc)
Location: net/ipv4/tcp_output.c:1882
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (c0d94bf0)
Location: net/ipv4/tcp_output.c:1882
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (c000000000d91bf4)
Location: net/ipv4/tcp_output.c:1882
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (ffffffe0007e70a8)
Location: net/ipv4/tcp_output.c:1882
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (ffffffff81972c83)
Location: net/ipv4/tcp_output.c:1882
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (ffffffff8192c753)
Location: net/ipv4/tcp_output.c:1882
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (ffffffff819dd453)
Location: net/ipv4/tcp_output.c:1882
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
In net/ipv4/tcp_output.c (ffffffff819e70d3)
Location: net/ipv4/tcp_output.c:1882
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
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
</ul>
