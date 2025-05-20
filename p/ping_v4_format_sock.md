# Function: <code>ping_v4_format_sock</code>

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
In net/ipv4/ping.c (ffffffff817a2206)
Location: net/ipv4/ping.c:1104
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
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
In net/ipv4/ping.c (ffffffff8180ff06)
Location: net/ipv4/ping.c:1109
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
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
In net/ipv4/ping.c (ffffffff81841453)
Location: net/ipv4/ping.c:1111
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
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
In net/ipv4/ping.c (ffffffff81862cc3)
Location: net/ipv4/ping.c:1113
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
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
In net/ipv4/ping.c (ffffffff818e2df3)
Location: net/ipv4/ping.c:1113
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
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
In net/ipv4/ping.c (ffffffff8193976d)
Location: net/ipv4/ping.c:1116
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
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
In net/ipv4/ping.c (ffffffff819693fd)
Location: net/ipv4/ping.c:1106
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
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
In net/ipv4/ping.c (ffffffff819d0079)
Location: net/ipv4/ping.c:1101
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
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
In net/ipv4/ping.c (ffffffff81a06bc9)
Location: net/ipv4/ping.c:1101
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ping_v4_format_sock(struct sock *sp, struct seq_file *f, int bucket);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81af65c0)
Location: net/ipv4/ping.c:1104
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
**Symbols:**

```
ffffffff81af65c0-ffffffff81af66ae: ping_v4_format_sock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ping_v4_format_sock(struct sock *sp, struct seq_file *f, int bucket);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81b03440)
Location: net/ipv4/ping.c:1093
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_v4_seq_show
```
**Symbols:**

```
ffffffff81b03440-ffffffff81b0352e: ping_v4_format_sock (STB_LOCAL)
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
In net/ipv4/ping.c (ffffffff81aeed09)
Location: net/ipv4/ping.c:1097
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
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
In net/ipv4/ping.c (ffffffff81baf0d9)
Location: net/ipv4/ping.c:1104
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
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
In net/ipv4/ping.c (ffffffff81d423ff)
Location: net/ipv4/ping.c:1121
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
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
In net/ipv4/ping.c (ffffffff81f0b26f)
Location: net/ipv4/ping.c:1130
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
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
In net/ipv4/ping.c (ffffffff81f6ae4f)
Location: net/ipv4/ping.c:1114
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
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
In net/ipv4/ping.c (ffffffff820314ff)
Location: net/ipv4/ping.c:1114
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
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
In net/ipv4/ping.c (ffff800010cbfb8c)
Location: net/ipv4/ping.c:1101
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
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
In net/ipv4/ping.c (c0dcb64c)
Location: net/ipv4/ping.c:1101
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
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
In net/ipv4/ping.c (c000000000ddac34)
Location: net/ipv4/ping.c:1101
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
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
In net/ipv4/ping.c (ffffffe0008158da)
Location: net/ipv4/ping.c:1101
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
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
In net/ipv4/ping.c (ffffffff819a6969)
Location: net/ipv4/ping.c:1101
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
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
In net/ipv4/ping.c (ffffffff81960429)
Location: net/ipv4/ping.c:1101
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
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
In net/ipv4/ping.c (ffffffff81a11209)
Location: net/ipv4/ping.c:1101
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
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
In net/ipv4/ping.c (ffffffff81a1bb79)
Location: net/ipv4/ping.c:1101
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_v4_seq_show
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
