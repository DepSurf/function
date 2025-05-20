# Function: <code>ftrace_startup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ftrace_startup(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81144f00)
Location: kernel/trace/ftrace.c:2594
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff81144f00-ffffffff8114513f: ftrace_startup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ftrace_startup(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8114d820)
Location: kernel/trace/ftrace.c:2652
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff8114d820-ffffffff8114da2a: ftrace_startup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ftrace_startup(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81157760)
Location: kernel/trace/ftrace.c:2670
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff81157760-ffffffff8115796c: ftrace_startup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ftrace_startup(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8115a9f0)
Location: kernel/trace/ftrace.c:2755
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff8115a9f0-ffffffff8115ac05: ftrace_startup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ftrace_startup(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81167b60)
Location: kernel/trace/ftrace.c:2726
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff81167b60-ffffffff81167ce3: ftrace_startup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ftrace_startup(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81176850)
Location: kernel/trace/ftrace.c:2715
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_graph
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function_probe
```
**Symbols:**

```
ffffffff81176850-ffffffff811769c8: ftrace_startup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ftrace_startup(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81184530)
Location: kernel/trace/ftrace.c:2672
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/fgraph.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff81184530-ffffffff81184611: ftrace_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ftrace_startup(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811912e0)
Location: kernel/trace/ftrace.c:2671
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/fgraph.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff811912e0-ffffffff811913d5: ftrace_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ftrace_startup(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119d300)
Location: kernel/trace/ftrace.c:2672
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/fgraph.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff8119d300-ffffffff8119d3f5: ftrace_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ftrace_startup(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b32ed)
Location: kernel/trace/ftrace.c:2784
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function_probe
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/fgraph.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff811b00e0-ffffffff811b020c: ftrace_startup.part.0 (STB_LOCAL)
ffffffff811b3290-ffffffff811b32ce: ftrace_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ftrace_startup(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b0efd)
Location: kernel/trace/ftrace.c:2858
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function_probe
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/fgraph.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff811adb60-ffffffff811adca0: ftrace_startup.part.0 (STB_LOCAL)
ffffffff811b0ea0-ffffffff811b0ede: ftrace_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ftrace_startup(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b18f0)
Location: kernel/trace/ftrace.c:2864
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/fgraph.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff811b18f0-ffffffff811b1a3d: ftrace_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ftrace_startup(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811db790)
Location: kernel/trace/ftrace.c:2865
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/fgraph.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff811db790-ffffffff811db919: ftrace_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ftrace_startup(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81211850)
Location: kernel/trace/ftrace.c:2901
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_direct_multi
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/fgraph.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff81211850-ffffffff812119c6: ftrace_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ftrace_startup(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8125ae10)
Location: kernel/trace/ftrace.c:2963
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_direct_multi
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/fgraph.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff8125ae10-ffffffff8125af81: ftrace_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ftrace_startup(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812722b0)
Location: kernel/trace/ftrace.c:3046
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:modify_ftrace_direct_nolock
  - kernel/trace/ftrace.c:register_ftrace_direct
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/fgraph.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff812722b0-ffffffff81272421: ftrace_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ftrace_startup(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8128c7a0)
Location: kernel/trace/ftrace.c:3012
Inline: False
Direct callers:
  - kernel/trace/ftrace.c:modify_ftrace_direct
  - kernel/trace/ftrace.c:modify_ftrace_direct_nolock
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/fgraph.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff8128c7a0-ffffffff8128c911: ftrace_startup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int ftrace_startup(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff8000102161e8)
Location: kernel/trace/ftrace.c:2672
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/fgraph.c:register_ftrace_graph
```
**Symbols:**

```
ffff8000102161e8-ffff800010216324: ftrace_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ftrace_startup(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0454f90)
Location: kernel/trace/ftrace.c:2672
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/fgraph.c:register_ftrace_graph
```
**Symbols:**

```
c0454f90-c04550a8: ftrace_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ftrace_startup(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c000000000297f50)
Location: kernel/trace/ftrace.c:2672
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/fgraph.c:register_ftrace_graph
```
**Symbols:**

```
c000000000297f50-c0000000002980f4: ftrace_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ftrace_startup(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe000175ddc)
Location: kernel/trace/ftrace.c:2672
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/fgraph.c:register_ftrace_graph
```
**Symbols:**

```
ffffffe000175ddc-ffffffe000175eb4: ftrace_startup (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int ftrace_startup(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81195920)
Location: kernel/trace/ftrace.c:2672
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/fgraph.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff81195920-ffffffff81195a15: ftrace_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ftrace_startup(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81188a30)
Location: kernel/trace/ftrace.c:2672
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/fgraph.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff81188a30-ffffffff81188b25: ftrace_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ftrace_startup(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811936f0)
Location: kernel/trace/ftrace.c:2672
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/fgraph.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff811936f0-ffffffff811937e5: ftrace_startup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ftrace_startup(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811a12c0)
Location: kernel/trace/ftrace.c:2672
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:register_ftrace_function
  - kernel/trace/ftrace.c:register_ftrace_function_probe
  - kernel/trace/fgraph.c:register_ftrace_graph
```
**Symbols:**

```
ffffffff811a12c0-ffffffff811a13b5: ftrace_startup (STB_GLOBAL)
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
