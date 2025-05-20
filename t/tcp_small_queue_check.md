# Function: <code>tcp_small_queue_check</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool tcp_small_queue_check(struct sock *sk, const struct sk_buff *skb, unsigned int factor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81811760)
Location: net/ipv4/tcp_output.c:2085
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81811760-ffffffff818117ca: tcp_small_queue_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool tcp_small_queue_check(struct sock *sk, const struct sk_buff *skb, unsigned int factor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818319d0)
Location: net/ipv4/tcp_output.c:2171
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff818319d0-ffffffff81831a3a: tcp_small_queue_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818b17f0)
Location: net/ipv4/tcp_output.c:2222
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff818b17f0-ffffffff818b1851: tcp_small_queue_check.isra.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81906a40)
Location: net/ipv4/tcp_output.c:2205
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81906a40-ffffffff81906aa0: tcp_small_queue_check.isra.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81934d40)
Location: net/ipv4/tcp_output.c:2228
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81934d40-ffffffff81934db4: tcp_small_queue_check.isra.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81998b00)
Location: net/ipv4/tcp_output.c:2244
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81998b00-ffffffff81998b9c: tcp_small_queue_check.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819cf630)
Location: net/ipv4/tcp_output.c:2263
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff819cf630-ffffffff819cf6c7: tcp_small_queue_check.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81abbee0)
Location: net/ipv4/tcp_output.c:2326
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81abbee0-ffffffff81abbf77: tcp_small_queue_check.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ac7460)
Location: net/ipv4/tcp_output.c:2496
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81ac7460-ffffffff81ac74f7: tcp_small_queue_check.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab2480)
Location: net/ipv4/tcp_output.c:2497
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81ab2480-ffffffff81ab251a: tcp_small_queue_check.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:2497
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81b6f300-ffffffff81b6f3b9: tcp_small_queue_check.isra.0 (STB_LOCAL)
ffffffff81d3aed4-ffffffff81d3aefa: tcp_small_queue_check.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:2497
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81cfe980-ffffffff81cfea42: tcp_small_queue_check.isra.0 (STB_LOCAL)
ffffffff81f077ab-ffffffff81f077d1: tcp_small_queue_check.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:2499
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81ec38a0-ffffffff81ec3962: tcp_small_queue_check.isra.0 (STB_LOCAL)
ffffffff820af23d-ffffffff820af263: tcp_small_queue_check.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:2541
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81f21ae0-ffffffff81f21ba2: tcp_small_queue_check.isra.0 (STB_LOCAL)
ffffffff82130605-ffffffff8213062b: tcp_small_queue_check.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (0)
Location: net/ipv4/tcp_output.c:2597
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81fe5a70-ffffffff81fe5b45: tcp_small_queue_check.isra.0 (STB_LOCAL)
ffffffff82211f01-ffffffff82211f27: tcp_small_queue_check.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffff800010c821a8)
Location: net/ipv4/tcp_output.c:2263
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffff800010c821a8-ffff800010c82284: tcp_small_queue_check.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool tcp_small_queue_check(struct sock *sk, const struct sk_buff *skb, unsigned int factor);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c0d90bec)
Location: net/ipv4/tcp_output.c:2263
Inline: False
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
c0d90bec-c0d90cb4: tcp_small_queue_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (c000000000d8d440)
Location: net/ipv4/tcp_output.c:2263
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
c000000000d8d440-c000000000d8d518: tcp_small_queue_check.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffe0007e3fcc)
Location: net/ipv4/tcp_output.c:2263
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffe0007e3fcc-ffffffe0007e4088: tcp_small_queue_check.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8196f4a0)
Location: net/ipv4/tcp_output.c:2263
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff8196f4a0-ffffffff8196f537: tcp_small_queue_check.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81928f70)
Location: net/ipv4/tcp_output.c:2263
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff81928f70-ffffffff81929007: tcp_small_queue_check.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819d9c70)
Location: net/ipv4/tcp_output.c:2263
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff819d9c70-ffffffff819d9d07: tcp_small_queue_check.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819e38d0)
Location: net/ipv4/tcp_output.c:2263
Inline: True
Direct callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
```
**Symbols:**

```
ffffffff819e38d0-ffffffff819e3967: tcp_small_queue_check.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
