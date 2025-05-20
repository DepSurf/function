# Function: <code>tcp_seq_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tcp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8177a980)
Location: net/ipv4/tcp_ipv4.c:2075
Inline: False
```
**Symbols:**

```
ffffffff8177a980-ffffffff8177a9d8: tcp_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tcp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff817e7c50)
Location: net/ipv4/tcp_ipv4.c:2092
Inline: False
```
**Symbols:**

```
ffffffff817e7c50-ffffffff817e7ca8: tcp_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tcp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81818410)
Location: net/ipv4/tcp_ipv4.c:2136
Inline: False
```
**Symbols:**

```
ffffffff81818410-ffffffff81818467: tcp_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tcp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff818388e0)
Location: net/ipv4/tcp_ipv4.c:2192
Inline: False
```
**Symbols:**

```
ffffffff818388e0-ffffffff81838937: tcp_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tcp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff818b8030)
Location: net/ipv4/tcp_ipv4.c:2171
Inline: False
```
**Symbols:**

```
ffffffff818b8030-ffffffff818b8087: tcp_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tcp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81910ec0)
Location: net/ipv4/tcp_ipv4.c:2254
Inline: False
```
**Symbols:**

```
ffffffff81910ec0-ffffffff81910f17: tcp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tcp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff8193f390)
Location: net/ipv4/tcp_ipv4.c:2339
Inline: False
```
**Symbols:**

```
ffffffff8193f390-ffffffff8193f3e7: tcp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tcp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819a2fc0)
Location: net/ipv4/tcp_ipv4.c:2358
Inline: False
```
**Symbols:**

```
ffffffff819a2fc0-ffffffff819a3017: tcp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tcp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819d9bc0)
Location: net/ipv4/tcp_ipv4.c:2381
Inline: False
```
**Symbols:**

```
ffffffff819d9bc0-ffffffff819d9c17: tcp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tcp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ac6e20)
Location: net/ipv4/tcp_ipv4.c:2459
Inline: False
```
**Symbols:**

```
ffffffff81ac6e20-ffffffff81ac6e77: tcp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tcp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ad30c5)
Location: net/ipv4/tcp_ipv4.c:2509
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop
```
**Symbols:**

```
ffffffff81ad2760-ffffffff81ad27b7: tcp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tcp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81abe155)
Location: net/ipv4/tcp_ipv4.c:2527
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:bpf_iter_tcp_seq_stop
```
**Symbols:**

```
ffffffff81abe0d0-ffffffff81abe127: tcp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tcp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81b7b820)
Location: net/ipv4/tcp_ipv4.c:2560
Inline: False
```
**Symbols:**

```
ffffffff81b7b820-ffffffff81b7b877: tcp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tcp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81d072d0)
Location: net/ipv4/tcp_ipv4.c:2526
Inline: False
```
**Symbols:**

```
ffffffff81d072d0-ffffffff81d0733d: tcp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tcp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81ecc360)
Location: net/ipv4/tcp_ipv4.c:2599
Inline: False
```
**Symbols:**

```
ffffffff81ecc360-ffffffff81ecc3d2: tcp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tcp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81f2b030)
Location: net/ipv4/tcp_ipv4.c:2607
Inline: False
```
**Symbols:**

```
ffffffff81f2b030-ffffffff81f2b0b2: tcp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tcp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81fefce0)
Location: net/ipv4/tcp_ipv4.c:2811
Inline: False
```
**Symbols:**

```
ffffffff81fefce0-ffffffff81fefd62: tcp_seq_stop (STB_GLOBAL)
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
void tcp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffff800010c8b2c0)
Location: net/ipv4/tcp_ipv4.c:2381
Inline: False
```
**Symbols:**

```
ffff800010c8b2c0-ffff800010c8b374: tcp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tcp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c0d98e20)
Location: net/ipv4/tcp_ipv4.c:2381
Inline: False
```
**Symbols:**

```
c0d98e20-c0d98eb4: tcp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tcp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c000000000d97510)
Location: net/ipv4/tcp_ipv4.c:2381
Inline: False
```
**Symbols:**

```
c000000000d97510-c000000000d975ec: tcp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tcp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffe0007edd16)
Location: net/ipv4/tcp_ipv4.c:2381
Inline: False
```
**Symbols:**

```
ffffffe0007edd16-ffffffe0007eddcc: tcp_seq_stop (STB_GLOBAL)
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
void tcp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff81979a30)
Location: net/ipv4/tcp_ipv4.c:2381
Inline: False
```
**Symbols:**

```
ffffffff81979a30-ffffffff81979a87: tcp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tcp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819334f0)
Location: net/ipv4/tcp_ipv4.c:2381
Inline: False
```
**Symbols:**

```
ffffffff819334f0-ffffffff81933547: tcp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tcp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819e4200)
Location: net/ipv4/tcp_ipv4.c:2381
Inline: False
```
**Symbols:**

```
ffffffff819e4200-ffffffff819e4257: tcp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tcp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (ffffffff819eb0e0)
Location: net/ipv4/tcp_ipv4.c:2381
Inline: False
```
**Symbols:**

```
ffffffff819eb0e0-ffffffff819eb135: tcp_seq_stop (STB_GLOBAL)
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
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
