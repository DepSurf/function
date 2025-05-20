# Function: <code>bpf_test_run</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 bpf_test_run(struct bpf_prog *prog, void *ctx, u32 repeat, u32 *time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff8180c680)
Location: net/bpf/test_run.c:27
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff8180c680-ffffffff8180c785: bpf_test_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 bpf_test_run(struct bpf_prog *prog, void *ctx, u32 repeat, u32 *time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff8188b660)
Location: net/bpf/test_run.c:27
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff8188b660-ffffffff8188b761: bpf_test_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 bpf_test_run(struct bpf_prog *prog, void *ctx, u32 repeat, u32 *time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff818df0c0)
Location: net/bpf/test_run.c:27
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff818df0c0-ffffffff818df1a9: bpf_test_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_test_run(struct bpf_prog *prog, void *ctx, u32 repeat, u32 *retval, u32 *time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff8190ba90)
Location: net/bpf/test_run.c:16
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff8190ba90-ffffffff8190bc50: bpf_test_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_test_run(struct bpf_prog *prog, void *ctx, u32 repeat, u32 *retval, u32 *time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff8196d140)
Location: net/bpf/test_run.c:17
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff8196d140-ffffffff8196d35c: bpf_test_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_test_run(struct bpf_prog *prog, void *ctx, u32 repeat, u32 *retval, u32 *time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff819a3a40)
Location: net/bpf/test_run.c:17
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff819a3a40-ffffffff819a3c5c: bpf_test_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_test_run(struct bpf_prog *prog, void *ctx, u32 repeat, u32 *retval, u32 *time, bool xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81a7e1d0)
Location: net/bpf/test_run.c:18
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81a7e1d0-ffffffff81a7e437: bpf_test_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_test_run(struct bpf_prog *prog, void *ctx, u32 repeat, u32 *retval, u32 *time, bool xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81a87830)
Location: net/bpf/test_run.c:19
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81a87830-ffffffff81a87ac2: bpf_test_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_test_run(struct bpf_prog *prog, void *ctx, u32 repeat, u32 *retval, u32 *time, bool xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81a70c40)
Location: net/bpf/test_run.c:87
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81a70c40-ffffffff81a70f19: bpf_test_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_test_run(struct bpf_prog *prog, void *ctx, u32 repeat, u32 *retval, u32 *time, bool xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81b2a560)
Location: net/bpf/test_run.c:89
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81b2a560-ffffffff81b2a832: bpf_test_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_test_run(struct bpf_prog *prog, void *ctx, u32 repeat, u32 *retval, u32 *time, bool xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81cb4190)
Location: net/bpf/test_run.c:372
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81cb4190-ffffffff81cb44a2: bpf_test_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_test_run(struct bpf_prog *prog, void *ctx, u32 repeat, u32 *retval, u32 *time, bool xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81e72400)
Location: net/bpf/test_run.c:372
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81e72400-ffffffff81e72712: bpf_test_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_test_run(struct bpf_prog *prog, void *ctx, u32 repeat, u32 *retval, u32 *time, bool xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81ece570)
Location: net/bpf/test_run.c:391
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_nf
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81ece570-ffffffff81ece8b5: bpf_test_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_test_run(struct bpf_prog *prog, void *ctx, u32 repeat, u32 *retval, u32 *time, bool xdp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81f91da0)
Location: net/bpf/test_run.c:392
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_nf
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81f91da0-ffffffff81f920e3: bpf_test_run (STB_LOCAL)
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
int bpf_test_run(struct bpf_prog *prog, void *ctx, u32 repeat, u32 *retval, u32 *time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffff800010c52840)
Location: net/bpf/test_run.c:17
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffff800010c52840-ffff800010c52a8c: bpf_test_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_test_run(struct bpf_prog *prog, void *ctx, u32 repeat, u32 *retval, u32 *time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (c0d629d8)
Location: net/bpf/test_run.c:17
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
c0d629d8-c0d62d18: bpf_test_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_test_run(struct bpf_prog *prog, void *ctx, u32 repeat, u32 *retval, u32 *time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (c000000000d52110)
Location: net/bpf/test_run.c:17
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
c000000000d52110-c000000000d52488: bpf_test_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_test_run(struct bpf_prog *prog, void *ctx, u32 repeat, u32 *retval, u32 *time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffe0007bd7b6)
Location: net/bpf/test_run.c:17
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffe0007bd7b6-ffffffe0007bd9f6: bpf_test_run (STB_LOCAL)
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
int bpf_test_run(struct bpf_prog *prog, void *ctx, u32 repeat, u32 *retval, u32 *time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff819438b0)
Location: net/bpf/test_run.c:17
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff819438b0-ffffffff81943acc: bpf_test_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_test_run(struct bpf_prog *prog, void *ctx, u32 repeat, u32 *retval, u32 *time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff818fd3a0)
Location: net/bpf/test_run.c:17
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff818fd3a0-ffffffff818fd5bc: bpf_test_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_test_run(struct bpf_prog *prog, void *ctx, u32 repeat, u32 *retval, u32 *time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff81994a40)
Location: net/bpf/test_run.c:17
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff81994a40-ffffffff81994c5c: bpf_test_run (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_test_run(struct bpf_prog *prog, void *ctx, u32 repeat, u32 *retval, u32 *time);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/bpf/test_run.c (ffffffff819b7550)
Location: net/bpf/test_run.c:17
Inline: False
Direct callers:
  - net/bpf/test_run.c:bpf_prog_test_run_xdp
  - net/bpf/test_run.c:bpf_prog_test_run_skb
```
**Symbols:**

```
ffffffff819b7550-ffffffff819b77b6: bpf_test_run (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u32 *retval</code>
</li>
<li>
<b>Param reordered. </b>
<code>prog, ctx, repeat, time</code> ➡️ <code>prog, ctx, repeat, retval, time</code>
</li>
<li>
<b>Return type changed. </b>
<code>u32</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool xdp</code>
</li>
</ul>
</details>
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
