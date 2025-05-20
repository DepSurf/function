# Function: <code>tcp_seek_last_pos</code>

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
In net/ipv4/tcp_ipv4.c (ffffffff8177bc8e)
Location: net/ipv4/tcp_ipv4.c:1990
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_start
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
In net/ipv4/tcp_ipv4.c (ffffffff817e94ce)
Location: net/ipv4/tcp_ipv4.c:2007
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_start
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
In net/ipv4/tcp_ipv4.c (ffffffff818196bb)
Location: net/ipv4/tcp_ipv4.c:2051
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_start
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
In net/ipv4/tcp_ipv4.c (ffffffff8183a8f5)
Location: net/ipv4/tcp_ipv4.c:2107
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_start
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
In net/ipv4/tcp_ipv4.c (ffffffff818ba3f5)
Location: net/ipv4/tcp_ipv4.c:2086
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_start
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
In net/ipv4/tcp_ipv4.c (ffffffff81910d17)
Location: net/ipv4/tcp_ipv4.c:2167
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_start
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
In net/ipv4/tcp_ipv4.c (ffffffff8193ea07)
Location: net/ipv4/tcp_ipv4.c:2252
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_start
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
In net/ipv4/tcp_ipv4.c (ffffffff819a2e37)
Location: net/ipv4/tcp_ipv4.c:2271
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_start
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
In net/ipv4/tcp_ipv4.c (ffffffff819d9a37)
Location: net/ipv4/tcp_ipv4.c:2294
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *tcp_seek_last_pos(struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ac6940)
Location: net/ipv4/tcp_ipv4.c:2372
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_start
```
**Symbols:**

```
ffffffff81ac6940-ffffffff81ac6a3e: tcp_seek_last_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *tcp_seek_last_pos(struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ad2270)
Location: net/ipv4/tcp_ipv4.c:2422
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_start
```
**Symbols:**

```
ffffffff81ad2270-ffffffff81ad2380: tcp_seek_last_pos (STB_LOCAL)
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
In net/ipv4/tcp_ipv4.c (ffffffff81abdf47)
Location: net/ipv4/tcp_ipv4.c:2440
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_start
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *tcp_seek_last_pos(struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81b7b5e0)
Location: net/ipv4/tcp_ipv4.c:2472
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_seq_start
```
**Symbols:**

```
ffffffff81b7b5e0-ffffffff81b7b702: tcp_seek_last_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *tcp_seek_last_pos(struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81d09e10)
Location: net/ipv4/tcp_ipv4.c:2438
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_seq_start
```
**Symbols:**

```
ffffffff81d09e10-ffffffff81d09f18: tcp_seek_last_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *tcp_seek_last_pos(struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ecf790)
Location: net/ipv4/tcp_ipv4.c:2511
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_seq_start
```
**Symbols:**

```
ffffffff81ecf790-ffffffff81ecf89e: tcp_seek_last_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *tcp_seek_last_pos(struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81f2e450)
Location: net/ipv4/tcp_ipv4.c:2519
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_seq_start
```
**Symbols:**

```
ffffffff81f2e450-ffffffff81f2e56e: tcp_seek_last_pos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *tcp_seek_last_pos(struct seq_file *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ff32b0)
Location: net/ipv4/tcp_ipv4.c:2723
Inline: False
Direct callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_batch
  - net/ipv4/tcp_ipv4.c:tcp_seq_start
```
**Symbols:**

```
ffffffff81ff32b0-ffffffff81ff33ce: tcp_seek_last_pos (STB_LOCAL)
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
In net/ipv4/tcp_ipv4.c (ffff800010c8be6c)
Location: net/ipv4/tcp_ipv4.c:2294
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_start
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
In net/ipv4/tcp_ipv4.c (c0d9a2cc)
Location: net/ipv4/tcp_ipv4.c:2294
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_start
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
In net/ipv4/tcp_ipv4.c (c000000000d98618)
Location: net/ipv4/tcp_ipv4.c:2294
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_start
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
In net/ipv4/tcp_ipv4.c (ffffffe0007edbc4)
Location: net/ipv4/tcp_ipv4.c:2294
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_start
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
In net/ipv4/tcp_ipv4.c (ffffffff819798a7)
Location: net/ipv4/tcp_ipv4.c:2294
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_start
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
In net/ipv4/tcp_ipv4.c (ffffffff81933367)
Location: net/ipv4/tcp_ipv4.c:2294
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_start
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
In net/ipv4/tcp_ipv4.c (ffffffff819e4077)
Location: net/ipv4/tcp_ipv4.c:2294
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_start
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
In net/ipv4/tcp_ipv4.c (ffffffff819eca27)
Location: net/ipv4/tcp_ipv4.c:2294
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_seq_start
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
