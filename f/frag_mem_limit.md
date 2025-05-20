# Function: <code>frag_mem_limit</code>

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
In net/ipv4/inet_fragment.c (0)
Location: include/net/inet_frag.h:150
Inline: True
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
In net/ipv4/inet_fragment.c (0)
Location: include/net/inet_frag.h:150
Inline: True
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
In net/ipv4/inet_fragment.c (0)
Location: include/net/inet_frag.h:150
Inline: True
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
In net/ipv4/inet_fragment.c (ffffffff8186298f)
Location: include/net/inet_frag.h:133
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/inet_fragment.c:inet_frag_find
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
In net/ipv4/inet_fragment.c (ffffffff818e2abf)
Location: include/net/inet_frag.h:134
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
  - net/ipv4/inet_fragment.c:inet_frag_find
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff819392cb)
Location: include/net/inet_frag.h:123
Inline: True
```
```
In net/ipv4/proc.c (ffffffff8193d9ff)
Location: include/net/inet_frag.h:123
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/proc.c (ffffffff819a4103)
Location: include/net/inet_frag.h:123
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81968e8b)
Location: include/net/inet_frag.h:130
Inline: True
```
```
In net/ipv4/proc.c (ffffffff8196d89f)
Location: include/net/inet_frag.h:130
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/proc.c (ffffffff819dac13)
Location: include/net/inet_frag.h:130
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff819cfd6b)
Location: include/net/inet_frag.h:139
Inline: True
```
```
In net/ipv4/proc.c (ffffffff819d7188)
Location: include/net/inet_frag.h:139
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/proc.c (ffffffff81a498aa)
Location: include/net/inet_frag.h:139
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81a068fb)
Location: include/net/inet_frag.h:139
Inline: True
```
```
In net/ipv4/proc.c (ffffffff81a0dc78)
Location: include/net/inet_frag.h:139
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/proc.c (ffffffff81a8046a)
Location: include/net/inet_frag.h:139
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81af651d)
Location: include/net/inet_frag.h:139
Inline: True
```
```
In net/ipv4/proc.c (ffffffff81afec98)
Location: include/net/inet_frag.h:139
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/proc.c (ffffffff81b7b16a)
Location: include/net/inet_frag.h:139
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81b0339d)
Location: include/net/inet_frag.h:140
Inline: True
```
```
In net/ipv4/proc.c (ffffffff81b0cd08)
Location: include/net/inet_frag.h:140
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/proc.c (ffffffff81b8a1aa)
Location: include/net/inet_frag.h:140
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81aeebfd)
Location: include/net/inet_frag.h:140
Inline: True
```
```
In net/ipv4/proc.c (ffffffff81afa84a)
Location: include/net/inet_frag.h:140
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/proc.c (ffffffff81b78ffa)
Location: include/net/inet_frag.h:140
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81baefcd)
Location: include/net/inet_frag.h:147
Inline: True
```
```
In net/ipv4/proc.c (ffffffff81bbb65a)
Location: include/net/inet_frag.h:147
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/proc.c (ffffffff81c43b8a)
Location: include/net/inet_frag.h:147
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81d4204f)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/proc.c (ffffffff81d4f739)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/proc.c (ffffffff81de2bcb)
Location: include/net/inet_frag.h:149
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81f0ae8f)
Location: include/net/inet_frag.h:156
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/proc.c (ffffffff81f19388)
Location: include/net/inet_frag.h:156
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/proc.c (ffffffff81fb4efb)
Location: include/net/inet_frag.h:156
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81f6a9cf)
Location: include/net/inet_frag.h:156
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/proc.c (ffffffff81f79038)
Location: include/net/inet_frag.h:156
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/proc.c (ffffffff8201565b)
Location: include/net/inet_frag.h:156
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff8203107f)
Location: include/net/inet_frag.h:156
Inline: True
Inline callers:
  - net/ipv4/inet_fragment.c:inet_frag_find
```
```
In net/ipv4/proc.c (ffffffff8203f6f8)
Location: include/net/inet_frag.h:156
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/proc.c (ffffffff820e479b)
Location: include/net/inet_frag.h:156
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffff800010cbf78c)
Location: include/net/inet_frag.h:139
Inline: True
```
```
In net/ipv4/proc.c (ffff800010cc7870)
Location: include/net/inet_frag.h:139
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/proc.c (ffff800010d4bbd8)
Location: include/net/inet_frag.h:139
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (c0dcb150)
Location: include/net/inet_frag.h:139
Inline: True
```
```
In net/ipv4/proc.c (c0dd2df8)
Location: include/net/inet_frag.h:139
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/proc.c (c0e4cea4)
Location: include/net/inet_frag.h:139
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (c000000000dda500)
Location: include/net/inet_frag.h:139
Inline: True
```
```
In net/ipv4/proc.c (c000000000de4704)
Location: include/net/inet_frag.h:139
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/proc.c (c000000000e81fd8)
Location: include/net/inet_frag.h:139
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffe00081547e)
Location: include/net/inet_frag.h:139
Inline: True
```
```
In net/ipv4/proc.c (ffffffe00081bdae)
Location: include/net/inet_frag.h:139
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/proc.c (ffffffe000884a7c)
Location: include/net/inet_frag.h:139
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff819a669b)
Location: include/net/inet_frag.h:139
Inline: True
```
```
In net/ipv4/proc.c (ffffffff819ada18)
Location: include/net/inet_frag.h:139
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/proc.c (ffffffff81a1fafa)
Location: include/net/inet_frag.h:139
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff8196015b)
Location: include/net/inet_frag.h:139
Inline: True
```
```
In net/ipv4/proc.c (ffffffff8196a048)
Location: include/net/inet_frag.h:139
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/proc.c (ffffffff819dc8ba)
Location: include/net/inet_frag.h:139
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81a10f3b)
Location: include/net/inet_frag.h:139
Inline: True
```
```
In net/ipv4/proc.c (ffffffff81a182b8)
Location: include/net/inet_frag.h:139
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/proc.c (ffffffff81a8a57a)
Location: include/net/inet_frag.h:139
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81a1b89b)
Location: include/net/inet_frag.h:139
Inline: True
```
```
In net/ipv4/proc.c (ffffffff81a22d38)
Location: include/net/inet_frag.h:139
Inline: True
Inline callers:
  - net/ipv4/proc.c:sockstat_seq_show
```
```
In net/ipv6/proc.c (ffffffff81a971da)
Location: include/net/inet_frag.h:139
Inline: True
Inline callers:
  - net/ipv6/proc.c:sockstat6_seq_show
```
</details>
</li>
</ul>

## Differences
