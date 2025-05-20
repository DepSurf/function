# Function: <code>udp_seq_stop</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void udp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81785f20)
Location: net/ipv4/udp.c:2376
Inline: False
```
**Symbols:**

```
ffffffff81785f20-ffffffff81785f52: udp_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void udp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff817f3470)
Location: net/ipv4/udp.c:2306
Inline: False
```
**Symbols:**

```
ffffffff817f3470-ffffffff817f34a2: udp_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void udp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81824270)
Location: net/ipv4/udp.c:2476
Inline: False
```
**Symbols:**

```
ffffffff81824270-ffffffff8182429f: udp_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void udp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81844f80)
Location: net/ipv4/udp.c:2640
Inline: False
```
**Symbols:**

```
ffffffff81844f80-ffffffff81844fb0: udp_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void udp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff818c4a10)
Location: net/ipv4/udp.c:2655
Inline: False
```
**Symbols:**

```
ffffffff818c4a10-ffffffff818c4a40: udp_seq_stop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void udp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8191b150)
Location: net/ipv4/udp.c:2754
Inline: False
```
**Symbols:**

```
ffffffff8191b150-ffffffff8191b193: udp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void udp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819496d0)
Location: net/ipv4/udp.c:2870
Inline: False
```
**Symbols:**

```
ffffffff819496d0-ffffffff81949713: udp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void udp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819add40)
Location: net/ipv4/udp.c:2855
Inline: False
```
**Symbols:**

```
ffffffff819add40-ffffffff819add86: udp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void udp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819e4a50)
Location: net/ipv4/udp.c:2891
Inline: False
```
**Symbols:**

```
ffffffff819e4a50-ffffffff819e4a96: udp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void udp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ad26c0)
Location: net/ipv4/udp.c:2908
Inline: False
```
**Symbols:**

```
ffffffff81ad26c0-ffffffff81ad270c: udp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void udp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81adf8a7)
Location: net/ipv4/udp.c:2952
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_seq_stop
```
**Symbols:**

```
ffffffff81ade5f0-ffffffff81ade644: udp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void udp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81aca7a7)
Location: net/ipv4/udp.c:3023
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_seq_stop
```
**Symbols:**

```
ffffffff81ac9510-ffffffff81ac9561: udp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void udp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81b89087)
Location: net/ipv4/udp.c:3038
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_seq_stop
```
**Symbols:**

```
ffffffff81b87d80-ffffffff81b87dd1: udp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void udp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81d1ab3d)
Location: net/ipv4/udp.c:3053
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_seq_stop
```
**Symbols:**

```
ffffffff81d17ff0-ffffffff81d1804d: udp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void udp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ee251d)
Location: net/ipv4/udp.c:3091
Inline: True
Inline callers:
  - net/ipv4/udp.c:bpf_iter_udp_seq_stop
```
**Symbols:**

```
ffffffff81ede8e0-ffffffff81ede952: udp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void udp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81f3dd20)
Location: net/ipv4/udp.c:3069
Inline: False
```
**Symbols:**

```
ffffffff81f3dd20-ffffffff81f3dd9a: udp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void udp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff82003e50)
Location: net/ipv4/udp.c:3060
Inline: False
```
**Symbols:**

```
ffffffff82003e50-ffffffff82003eca: udp_seq_stop (STB_GLOBAL)
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
void udp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffff800010c990e0)
Location: net/ipv4/udp.c:2891
Inline: False
```
**Symbols:**

```
ffff800010c990e0-ffff800010c99158: udp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void udp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c0da7fec)
Location: net/ipv4/udp.c:2891
Inline: False
```
**Symbols:**

```
c0da7fec-c0da803c: udp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void udp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c000000000dabca0)
Location: net/ipv4/udp.c:2891
Inline: False
```
**Symbols:**

```
c000000000dabca0-c000000000dabd2c: udp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void udp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffe0007f7686)
Location: net/ipv4/udp.c:2891
Inline: False
```
**Symbols:**

```
ffffffe0007f7686-ffffffe0007f76d8: udp_seq_stop (STB_GLOBAL)
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
void udp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819848c0)
Location: net/ipv4/udp.c:2891
Inline: False
```
**Symbols:**

```
ffffffff819848c0-ffffffff81984906: udp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void udp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff8193e380)
Location: net/ipv4/udp.c:2891
Inline: False
```
**Symbols:**

```
ffffffff8193e380-ffffffff8193e3c6: udp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void udp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819ef090)
Location: net/ipv4/udp.c:2891
Inline: False
```
**Symbols:**

```
ffffffff819ef090-ffffffff819ef0d6: udp_seq_stop (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void udp_seq_stop(struct seq_file *seq, void *v);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff819f9880)
Location: net/ipv4/udp.c:2891
Inline: False
```
**Symbols:**

```
ffffffff819f9880-ffffffff819f98c6: udp_seq_stop (STB_GLOBAL)
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
