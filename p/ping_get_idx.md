# Function: <code>ping_get_idx</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sock *ping_get_idx(struct seq_file *seq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff817a3890)
Location: net/ipv4/ping.c:1057
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_seq_start
  - net/ipv4/ping.c:ping_seq_next
```
**Symbols:**

```
ffffffff817a3890-ffffffff817a38de: ping_get_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sock *ping_get_idx(struct seq_file *seq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81810ef0)
Location: net/ipv4/ping.c:1060
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_seq_next
  - net/ipv4/ping.c:ping_seq_start
```
**Symbols:**

```
ffffffff81810ef0-ffffffff81810f3e: ping_get_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sock *ping_get_idx(struct seq_file *seq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81842400)
Location: net/ipv4/ping.c:1062
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_seq_next
  - net/ipv4/ping.c:ping_seq_start
```
**Symbols:**

```
ffffffff81842400-ffffffff81842448: ping_get_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sock *ping_get_idx(struct seq_file *seq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81863cd0)
Location: net/ipv4/ping.c:1064
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_seq_next
  - net/ipv4/ping.c:ping_seq_start
```
**Symbols:**

```
ffffffff81863cd0-ffffffff81863d18: ping_get_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sock *ping_get_idx(struct seq_file *seq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff818e3e10)
Location: net/ipv4/ping.c:1064
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_seq_next
  - net/ipv4/ping.c:ping_seq_start
```
**Symbols:**

```
ffffffff818e3e10-ffffffff818e3e58: ping_get_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sock *ping_get_idx(struct seq_file *seq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff8193a6c0)
Location: net/ipv4/ping.c:1067
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_seq_next
  - net/ipv4/ping.c:ping_seq_start
```
**Symbols:**

```
ffffffff8193a6c0-ffffffff8193a708: ping_get_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sock *ping_get_idx(struct seq_file *seq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81969b50)
Location: net/ipv4/ping.c:1057
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_seq_next
  - net/ipv4/ping.c:ping_seq_start
```
**Symbols:**

```
ffffffff81969b50-ffffffff81969b98: ping_get_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *ping_get_idx(struct seq_file *seq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff819d0820)
Location: net/ipv4/ping.c:1052
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_seq_next
  - net/ipv4/ping.c:ping_seq_start
```
**Symbols:**

```
ffffffff819d0820-ffffffff819d086e: ping_get_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *ping_get_idx(struct seq_file *seq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81a07370)
Location: net/ipv4/ping.c:1052
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_seq_next
  - net/ipv4/ping.c:ping_seq_start
```
**Symbols:**

```
ffffffff81a07370-ffffffff81a073be: ping_get_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct sock *ping_get_idx(struct seq_file *seq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81af7af6)
Location: net/ipv4/ping.c:1055
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_seq_next
Direct callers:
  - net/ipv4/ping.c:ping_v4_seq_start
```
**Symbols:**

```
ffffffff81af78c0-ffffffff81af7935: ping_get_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct sock *ping_get_idx(struct seq_file *seq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81b049d6)
Location: net/ipv4/ping.c:1044
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_seq_next
Direct callers:
  - net/ipv4/ping.c:ping_v4_seq_start
```
**Symbols:**

```
ffffffff81b047a0-ffffffff81b04815: ping_get_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct sock *ping_get_idx(struct seq_file *seq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81af0242)
Location: net/ipv4/ping.c:1048
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_seq_next
Direct callers:
  - net/ipv4/ping.c:ping_v4_seq_start
```
**Symbols:**

```
ffffffff81af0020-ffffffff81af0089: ping_get_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct sock *ping_get_idx(struct seq_file *seq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81bb0252)
Location: net/ipv4/ping.c:1055
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_seq_next
Direct callers:
  - net/ipv4/ping.c:ping_v4_seq_start
```
**Symbols:**

```
ffffffff81bb0030-ffffffff81bb0099: ping_get_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct sock *ping_get_idx(struct seq_file *seq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81d4384c)
Location: net/ipv4/ping.c:1072
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_seq_next
Direct callers:
  - net/ipv4/ping.c:ping_v4_seq_start
```
**Symbols:**

```
ffffffff81d436c0-ffffffff81d43741: ping_get_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct sock *ping_get_idx(struct seq_file *seq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81f0c87c)
Location: net/ipv4/ping.c:1081
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_seq_next
Direct callers:
  - net/ipv4/ping.c:ping_v4_seq_start
```
**Symbols:**

```
ffffffff81f0c6c0-ffffffff81f0c741: ping_get_idx (STB_LOCAL)
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
In net/ipv4/ping.c (ffffffff81f6c3bc)
Location: net/ipv4/ping.c:1065
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_seq_next
  - net/ipv4/ping.c:ping_v4_seq_start
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
In net/ipv4/ping.c (ffffffff8203298c)
Location: net/ipv4/ping.c:1065
Inline: True
Inline callers:
  - net/ipv4/ping.c:ping_seq_next
  - net/ipv4/ping.c:ping_v4_seq_start
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
struct sock *ping_get_idx(struct seq_file *seq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffff800010cc02b8)
Location: net/ipv4/ping.c:1052
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_seq_next
  - net/ipv4/ping.c:ping_seq_start
```
**Symbols:**

```
ffff800010cc02b8-ffff800010cc031c: ping_get_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *ping_get_idx(struct seq_file *seq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (c0dcb3f0)
Location: net/ipv4/ping.c:1052
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_seq_next
  - net/ipv4/ping.c:ping_seq_start
```
**Symbols:**

```
c0dcb3f0-c0dcb458: ping_get_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *ping_get_idx(struct seq_file *seq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (c000000000dda8e0)
Location: net/ipv4/ping.c:1052
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_seq_next
  - net/ipv4/ping.c:ping_seq_start
```
**Symbols:**

```
c000000000dda8e0-c000000000dda96c: ping_get_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *ping_get_idx(struct seq_file *seq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffe0008156bc)
Location: net/ipv4/ping.c:1052
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_seq_next
  - net/ipv4/ping.c:ping_seq_start
```
**Symbols:**

```
ffffffe0008156bc-ffffffe000815708: ping_get_idx (STB_LOCAL)
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
struct sock *ping_get_idx(struct seq_file *seq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff819a7110)
Location: net/ipv4/ping.c:1052
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_seq_next
  - net/ipv4/ping.c:ping_seq_start
```
**Symbols:**

```
ffffffff819a7110-ffffffff819a715e: ping_get_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *ping_get_idx(struct seq_file *seq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81960bd0)
Location: net/ipv4/ping.c:1052
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_seq_next
  - net/ipv4/ping.c:ping_seq_start
```
**Symbols:**

```
ffffffff81960bd0-ffffffff81960c1e: ping_get_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *ping_get_idx(struct seq_file *seq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81a119b0)
Location: net/ipv4/ping.c:1052
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_seq_next
  - net/ipv4/ping.c:ping_seq_start
```
**Symbols:**

```
ffffffff81a119b0-ffffffff81a119fe: ping_get_idx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *ping_get_idx(struct seq_file *seq, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ping.c (ffffffff81a1c320)
Location: net/ipv4/ping.c:1052
Inline: False
Direct callers:
  - net/ipv4/ping.c:ping_seq_next
  - net/ipv4/ping.c:ping_seq_start
```
**Symbols:**

```
ffffffff81a1c320-ffffffff81a1c36e: ping_get_idx (STB_LOCAL)
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
