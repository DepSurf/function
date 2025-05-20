# Function: <code>ndisc_fill_addr_option</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void ndisc_fill_addr_option(struct sk_buff *skb, int type, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff817de370)
Location: net/ipv6/ndisc.c:153
Inline: False
Direct callers:
  - net/ipv6/ndisc.c:ndisc_send_na
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_redirect
```
**Symbols:**

```
ffffffff817de370-ffffffff817de552: ndisc_fill_addr_option (STB_LOCAL)
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
In net/ipv6/ndisc.c (ffffffff8184f8d4)
Location: net/ipv6/ndisc.c:166
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff81881856)
Location: net/ipv6/ndisc.c:165
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff818a791f)
Location: net/ipv6/ndisc.c:165
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff8192a3aa)
Location: net/ipv6/ndisc.c:166
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff819825f2)
Location: net/ipv6/ndisc.c:166
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff819b8c9f)
Location: net/ipv6/ndisc.c:166
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff81a2776b)
Location: net/ipv6/ndisc.c:165
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff81a5e1cb)
Location: net/ipv6/ndisc.c:165
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/ndisc.c (ffffffff81b56fcb)
Location: net/ipv6/ndisc.c:165
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff81b6563b)
Location: net/ipv6/ndisc.c:167
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff81b5390e)
Location: net/ipv6/ndisc.c:167
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff81c1ae1e)
Location: net/ipv6/ndisc.c:167
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff81db7432)
Location: net/ipv6/ndisc.c:167
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_ns_create
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff81f87107)
Location: net/ipv6/ndisc.c:168
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_ns_create
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff81fe7447)
Location: net/ipv6/ndisc.c:168
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_ns_create
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff820b52a6)
Location: net/ipv6/ndisc.c:168
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_ns_create
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffff800010d23228)
Location: net/ipv6/ndisc.c:165
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (c0e278b4)
Location: net/ipv6/ndisc.c:165
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (c000000000e5318c)
Location: net/ipv6/ndisc.c:165
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffe000864c46)
Location: net/ipv6/ndisc.c:165
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff819fd85b)
Location: net/ipv6/ndisc.c:165
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff819ba61b)
Location: net/ipv6/ndisc.c:165
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff81a682db)
Location: net/ipv6/ndisc.c:165
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
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
In net/ipv6/ndisc.c (ffffffff81a748cb)
Location: net/ipv6/ndisc.c:165
Inline: True
Inline callers:
  - net/ipv6/ndisc.c:ndisc_send_redirect
  - net/ipv6/ndisc.c:ndisc_send_rs
  - net/ipv6/ndisc.c:ndisc_send_ns
  - net/ipv6/ndisc.c:ndisc_send_na
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
