# Function: <code>tracing_wait_pipe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81150b30)
Location: kernel/trace/trace.c:4684
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
```
**Symbols:**

```
ffffffff81150b30-ffffffff81150bd4: tracing_wait_pipe.isra.58 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81159b80)
Location: kernel/trace/trace.c:5081
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
```
**Symbols:**

```
ffffffff81159b80-ffffffff81159c20: tracing_wait_pipe.isra.63 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811643a0)
Location: kernel/trace/trace.c:5330
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
```
**Symbols:**

```
ffffffff811643a0-ffffffff81164440: tracing_wait_pipe.isra.60 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811676d0)
Location: kernel/trace/trace.c:5647
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
```
**Symbols:**

```
ffffffff811676d0-ffffffff81167770: tracing_wait_pipe.isra.66 (STB_LOCAL)
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
In kernel/trace/trace.c (ffffffff81174640)
Location: kernel/trace/trace.c:5658
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
```
**Symbols:**

```
ffffffff81174640-ffffffff811746e2: tracing_wait_pipe.isra.65 (STB_LOCAL)
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
In kernel/trace/trace.c (ffffffff81183680)
Location: kernel/trace/trace.c:5664
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
```
**Symbols:**

```
ffffffff81183680-ffffffff81183722: tracing_wait_pipe.isra.64 (STB_LOCAL)
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
In kernel/trace/trace.c (ffffffff81190fe0)
Location: kernel/trace/trace.c:5686
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
```
**Symbols:**

```
ffffffff81190fe0-ffffffff8119107f: tracing_wait_pipe.isra.65 (STB_LOCAL)
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
In kernel/trace/trace.c (ffffffff8119e980)
Location: kernel/trace/trace.c:5917
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
```
**Symbols:**

```
ffffffff8119e980-ffffffff8119ea1e: tracing_wait_pipe.isra.0 (STB_LOCAL)
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
In kernel/trace/trace.c (ffffffff811aa340)
Location: kernel/trace/trace.c:5968
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
```
**Symbols:**

```
ffffffff811aa340-ffffffff811aa3de: tracing_wait_pipe.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tracing_wait_pipe(struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c2950)
Location: kernel/trace/trace.c:6171
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
```
**Symbols:**

```
ffffffff811c2950-ffffffff811c2a31: tracing_wait_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tracing_wait_pipe(struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c0560)
Location: kernel/trace/trace.c:6244
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
```
**Symbols:**

```
ffffffff811c0560-ffffffff811c0641: tracing_wait_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tracing_wait_pipe(struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c1260)
Location: kernel/trace/trace.c:6581
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
```
**Symbols:**

```
ffffffff811c1260-ffffffff811c1341: tracing_wait_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tracing_wait_pipe(struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ebd90)
Location: kernel/trace/trace.c:6659
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
```
**Symbols:**

```
ffffffff811ebd90-ffffffff811ebe71: tracing_wait_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tracing_wait_pipe(struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81223ef0)
Location: kernel/trace/trace.c:6673
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
```
**Symbols:**

```
ffffffff81223ef0-ffffffff81223fe5: tracing_wait_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tracing_wait_pipe(struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126f030)
Location: kernel/trace/trace.c:6711
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
```
**Symbols:**

```
ffffffff8126f030-ffffffff8126f125: tracing_wait_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tracing_wait_pipe(struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81286290)
Location: kernel/trace/trace.c:6867
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
```
**Symbols:**

```
ffffffff81286290-ffffffff81286385: tracing_wait_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tracing_wait_pipe(struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff812a13a0)
Location: kernel/trace/trace.c:6882
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
```
**Symbols:**

```
ffffffff812a13a0-ffffffff812a1455: tracing_wait_pipe (STB_LOCAL)
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
In kernel/trace/trace.c (ffff800010227108)
Location: kernel/trace/trace.c:5968
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
```
**Symbols:**

```
ffff800010227108-ffff8000102271c0: tracing_wait_pipe.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tracing_wait_pipe(struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0464764)
Location: kernel/trace/trace.c:5968
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
```
**Symbols:**

```
c0464764-c046481c: tracing_wait_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tracing_wait_pipe(struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002ad350)
Location: kernel/trace/trace.c:5968
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
```
**Symbols:**

```
c0000000002ad350-c0000000002ad47c: tracing_wait_pipe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tracing_wait_pipe(struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe000181ccc)
Location: kernel/trace/trace.c:5968
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
```
**Symbols:**

```
ffffffe000181ccc-ffffffe000181d70: tracing_wait_pipe (STB_LOCAL)
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
In kernel/trace/trace.c (ffffffff811a2960)
Location: kernel/trace/trace.c:5968
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
```
**Symbols:**

```
ffffffff811a2960-ffffffff811a29fe: tracing_wait_pipe.isra.0 (STB_LOCAL)
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
In kernel/trace/trace.c (ffffffff81195930)
Location: kernel/trace/trace.c:5968
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
```
**Symbols:**

```
ffffffff81195930-ffffffff811959ce: tracing_wait_pipe.isra.0 (STB_LOCAL)
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
In kernel/trace/trace.c (ffffffff811a0730)
Location: kernel/trace/trace.c:5968
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
```
**Symbols:**

```
ffffffff811a0730-ffffffff811a07ce: tracing_wait_pipe.isra.0 (STB_LOCAL)
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
In kernel/trace/trace.c (ffffffff811ae4c0)
Location: kernel/trace/trace.c:5968
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracing_splice_read_pipe
  - kernel/trace/trace.c:tracing_read_pipe
```
**Symbols:**

```
ffffffff811ae4c0-ffffffff811ae55e: tracing_wait_pipe.isra.0 (STB_LOCAL)
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
