# Function: <code>ftrace_shutdown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ftrace_shutdown(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811441d0)
Location: kernel/trace/ftrace.c:2636
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:unregister_ftrace_graph
```
**Symbols:**

```
ffffffff811441d0-ffffffff81144451: ftrace_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ftrace_shutdown(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8114ba40)
Location: kernel/trace/ftrace.c:2694
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_graph
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
```
**Symbols:**

```
ffffffff8114ba40-ffffffff8114bcce: ftrace_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ftrace_shutdown(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81155930)
Location: kernel/trace/ftrace.c:2712
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_graph
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:__unregister_ftrace_function_probe
```
**Symbols:**

```
ffffffff81155930-ffffffff81155bc2: ftrace_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ftrace_shutdown(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81158370)
Location: kernel/trace/ftrace.c:2797
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_graph
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
**Symbols:**

```
ffffffff81158370-ffffffff811585ab: ftrace_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ftrace_shutdown(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81164e70)
Location: kernel/trace/ftrace.c:2768
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_graph
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
**Symbols:**

```
ffffffff81164e70-ffffffff81165097: ftrace_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ftrace_shutdown(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81173b70)
Location: kernel/trace/ftrace.c:2757
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_graph
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
```
**Symbols:**

```
ffffffff81173b70-ffffffff81173d77: ftrace_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ftrace_shutdown(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811817c0)
Location: kernel/trace/ftrace.c:2714
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
**Symbols:**

```
ffffffff811817c0-ffffffff811819c7: ftrace_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ftrace_shutdown(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118e5af)
Location: kernel/trace/ftrace.c:2713
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
**Symbols:**

```
ffffffff81192318-ffffffff8119234d: ftrace_shutdown.cold (STB_LOCAL)
ffffffff8118e580-ffffffff8118e766: ftrace_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ftrace_shutdown(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119a52f)
Location: kernel/trace/ftrace.c:2714
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
**Symbols:**

```
ffffffff8119e09e-ffffffff8119e0d3: ftrace_shutdown.cold (STB_LOCAL)
ffffffff8119a500-ffffffff8119a6e6: ftrace_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ftrace_shutdown(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b2911)
Location: kernel/trace/ftrace.c:2826
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
**Symbols:**

```
ffffffff811b0220-ffffffff811b03f1: ftrace_shutdown.part.0 (STB_LOCAL)
ffffffff811b4934-ffffffff811b4969: ftrace_shutdown.part.0.cold (STB_LOCAL)
ffffffff811b0460-ffffffff811b0498: ftrace_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ftrace_shutdown(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b0381)
Location: kernel/trace/ftrace.c:2902
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
**Symbols:**

```
ffffffff811adca0-ffffffff811ade71: ftrace_shutdown.part.0 (STB_LOCAL)
ffffffff81be53ea-ffffffff81be541f: ftrace_shutdown.part.0.cold (STB_LOCAL)
ffffffff811adee0-ffffffff811adf18: ftrace_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ftrace_shutdown(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811b0c91)
Location: kernel/trace/ftrace.c:2908
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
**Symbols:**

```
ffffffff811ae690-ffffffff811ae843: ftrace_shutdown.part.0 (STB_LOCAL)
ffffffff81bd71ee-ffffffff81bd7223: ftrace_shutdown.part.0.cold (STB_LOCAL)
ffffffff811ae8b0-ffffffff811ae8e8: ftrace_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ftrace_shutdown(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811dab11)
Location: kernel/trace/ftrace.c:2909
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
**Symbols:**

```
ffffffff811d8490-ffffffff811d8661: ftrace_shutdown.part.0 (STB_LOCAL)
ffffffff81cb46ae-ffffffff81cb46e3: ftrace_shutdown.part.0.cold (STB_LOCAL)
ffffffff811d86d0-ffffffff811d8708: ftrace_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ftrace_shutdown(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81210a41)
Location: kernel/trace/ftrace.c:2955
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:modify_ftrace_direct_multi
  - kernel/trace/ftrace.c:unregister_ftrace_direct_multi
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
Direct callers:
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:modify_ftrace_direct_multi
  - kernel/trace/ftrace.c:unregister_ftrace_direct_multi
  - kernel/trace/ftrace.c:ftrace_modify_direct_caller
  - kernel/trace/ftrace.c:unregister_ftrace_direct
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
**Symbols:**

```
ffffffff8120dd90-ffffffff8120df43: ftrace_shutdown.part.0 (STB_LOCAL)
ffffffff81e65676-ffffffff81e656a9: ftrace_shutdown.part.0.cold (STB_LOCAL)
ffffffff8120e090-ffffffff8120e0d6: ftrace_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ftrace_shutdown(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81256fd0)
Location: kernel/trace/ftrace.c:3017
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
**Symbols:**

```
ffffffff81256db0-ffffffff81256f92: ftrace_shutdown.part.0 (STB_LOCAL)
ffffffff81257310-ffffffff81257356: ftrace_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ftrace_shutdown(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8126e4c0)
Location: kernel/trace/ftrace.c:3100
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
**Symbols:**

```
ffffffff8126e2a0-ffffffff8126e483: ftrace_shutdown.part.0 (STB_LOCAL)
ffffffff8126e840-ffffffff8126e886: ftrace_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ftrace_shutdown(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff812889a0)
Location: kernel/trace/ftrace.c:3066
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
**Symbols:**

```
ffffffff81288780-ffffffff81288963: ftrace_shutdown.part.0 (STB_LOCAL)
ffffffff81288e30-ffffffff81288e76: ftrace_shutdown (STB_GLOBAL)
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
int ftrace_shutdown(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffff8000102131d0)
Location: kernel/trace/ftrace.c:2714
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
**Symbols:**

```
ffff8000102131d0-ffff800010213420: ftrace_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ftrace_shutdown(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c0451f3c)
Location: kernel/trace/ftrace.c:2714
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
**Symbols:**

```
c0451f3c-c0452218: ftrace_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ftrace_shutdown(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c000000000293440)
Location: kernel/trace/ftrace.c:2714
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
**Symbols:**

```
c000000000293440-c000000000293774: ftrace_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ftrace_shutdown(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe0001734a6)
Location: kernel/trace/ftrace.c:2714
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
**Symbols:**

```
ffffffe0001734a6-ffffffe0001736b8: ftrace_shutdown (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ftrace_shutdown(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81192b4f)
Location: kernel/trace/ftrace.c:2714
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
**Symbols:**

```
ffffffff811966be-ffffffff811966f3: ftrace_shutdown.cold (STB_LOCAL)
ffffffff81192b20-ffffffff81192d06: ftrace_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ftrace_shutdown(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81185c5f)
Location: kernel/trace/ftrace.c:2714
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
**Symbols:**

```
ffffffff811897cd-ffffffff81189802: ftrace_shutdown.cold (STB_LOCAL)
ffffffff81185c30-ffffffff81185e16: ftrace_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ftrace_shutdown(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119091f)
Location: kernel/trace/ftrace.c:2714
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
**Symbols:**

```
ffffffff8119448e-ffffffff811944c3: ftrace_shutdown.cold (STB_LOCAL)
ffffffff811908f0-ffffffff81190ad6: ftrace_shutdown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ftrace_shutdown(struct ftrace_ops *ops, int command);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119e4af)
Location: kernel/trace/ftrace.c:2714
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:unregister_ftrace_function
  - kernel/trace/ftrace.c:ftrace_destroy_filter_files
  - kernel/trace/ftrace.c:unregister_ftrace_function_probe_func
  - kernel/trace/fgraph.c:unregister_ftrace_graph
```
**Symbols:**

```
ffffffff811a207e-ffffffff811a20b3: ftrace_shutdown.cold (STB_LOCAL)
ffffffff8119e480-ffffffff8119e66b: ftrace_shutdown (STB_GLOBAL)
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
