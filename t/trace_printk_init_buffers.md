# Function: <code>trace_printk_init_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void trace_printk_init_buffers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81152180)
Location: kernel/trace/trace.c:2064
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace_printk.c:module_trace_bprintk_format_notify
  - kernel/trace/bpf_trace.c:kprobe_prog_func_proto
```
**Symbols:**

```
ffffffff81152180-ffffffff81152318: trace_printk_init_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void trace_printk_init_buffers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8115b3f0)
Location: kernel/trace/trace.c:2394
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace_printk.c:module_trace_bprintk_format_notify
  - kernel/trace/bpf_trace.c:tracing_func_proto
```
**Symbols:**

```
ffffffff8115b3f0-ffffffff8115b502: trace_printk_init_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void trace_printk_init_buffers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81165c00)
Location: kernel/trace/trace.c:2618
Inline: True
Direct callers:
  - kernel/trace/trace.c:trace_init
  - kernel/trace/trace_printk.c:module_trace_bprintk_format_notify
  - kernel/trace/bpf_trace.c:tracing_func_proto
```
**Symbols:**

```
ffffffff81165c00-ffffffff81165d12: trace_printk_init_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void trace_printk_init_buffers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811691e0)
Location: kernel/trace/trace.c:2830
Inline: True
Direct callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace_printk.c:module_trace_bprintk_format_notify
  - kernel/trace/bpf_trace.c:tracing_func_proto
```
**Symbols:**

```
ffffffff811691e0-ffffffff811692e7: trace_printk_init_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void trace_printk_init_buffers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811761a0)
Location: kernel/trace/trace.c:2839
Inline: True
Direct callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace_printk.c:module_trace_bprintk_format_notify
  - kernel/trace/bpf_trace.c:tracing_func_proto
```
**Symbols:**

```
ffffffff811761a0-ffffffff811762a7: trace_printk_init_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_printk_init_buffers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:2840
Inline: True
Direct callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace_printk.c:hold_module_trace_bprintk_format
```
**Symbols:**

```
ffffffff8118654e-ffffffff81186558: trace_printk_init_buffers.cold.79 (STB_LOCAL)
ffffffff81185130-ffffffff81185235: trace_printk_init_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_printk_init_buffers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81192a95)
Location: kernel/trace/trace.c:2842
Inline: True
Direct callers:
  - kernel/trace/trace.c:early_trace_init
  - kernel/trace/trace_printk.c:hold_module_trace_bprintk_format
```
**Symbols:**

```
ffffffff81193ede-ffffffff81193ee8: trace_printk_init_buffers.cold.79 (STB_LOCAL)
ffffffff81192a60-ffffffff81192b65: trace_printk_init_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_printk_init_buffers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a1ac9)
Location: kernel/trace/trace.c:3013
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace_printk.c:hold_module_trace_bprintk_format
```
**Symbols:**

```
ffffffff811a1abb-ffffffff811a1b91: trace_printk_init_buffers.cold (STB_LOCAL)
ffffffff811a0430-ffffffff811a0467: trace_printk_init_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_printk_init_buffers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ad4b4)
Location: kernel/trace/trace.c:3039
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace_printk.c:hold_module_trace_bprintk_format
```
**Symbols:**

```
ffffffff811ad4a6-ffffffff811ad57c: trace_printk_init_buffers.cold (STB_LOCAL)
ffffffff811abe60-ffffffff811abe97: trace_printk_init_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_printk_init_buffers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811c54db)
Location: kernel/trace/trace.c:3150
Inline: True
Direct callers:
  - kernel/trace/trace_printk.c:hold_module_trace_bprintk_format
  - kernel/trace/bpf_trace.c:bpf_tracing_func_proto
```
**Symbols:**

```
ffffffff811c54db-ffffffff811c55a7: trace_printk_init_buffers.part.0 (STB_LOCAL)
ffffffff811c55a7-ffffffff811c55d0: trace_printk_init_buffers.cold (STB_LOCAL)
ffffffff811c44b0-ffffffff811c44e6: trace_printk_init_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_printk_init_buffers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81be5817)
Location: kernel/trace/trace.c:3173
Inline: True
Direct callers:
  - kernel/trace/trace_printk.c:hold_module_trace_bprintk_format
```
**Symbols:**

```
ffffffff81be5817-ffffffff81be58e3: trace_printk_init_buffers.part.0 (STB_LOCAL)
ffffffff81be58e3-ffffffff81be58ed: trace_printk_init_buffers.cold (STB_LOCAL)
ffffffff811c20c0-ffffffff811c20ec: trace_printk_init_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_printk_init_buffers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81bd76c5)
Location: kernel/trace/trace.c:3224
Inline: True
Direct callers:
  - kernel/trace/trace_printk.c:hold_module_trace_bprintk_format
```
**Symbols:**

```
ffffffff81bd76c5-ffffffff81bd7795: trace_printk_init_buffers.cold (STB_LOCAL)
ffffffff811c3130-ffffffff811c315d: trace_printk_init_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_printk_init_buffers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81cb5505)
Location: kernel/trace/trace.c:3284
Inline: True
Direct callers:
  - kernel/trace/trace_printk.c:hold_module_trace_bprintk_format
```
**Symbols:**

```
ffffffff81cb5505-ffffffff81cb55d5: trace_printk_init_buffers.cold (STB_LOCAL)
ffffffff811ede40-ffffffff811ede6d: trace_printk_init_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_printk_init_buffers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81226098)
Location: kernel/trace/trace.c:3282
Inline: True
Direct callers:
  - kernel/trace/trace_printk.c:hold_module_trace_bprintk_format
```
**Symbols:**

```
ffffffff81e66583-ffffffff81e665b9: trace_printk_init_buffers.cold (STB_LOCAL)
ffffffff81226070-ffffffff812261a7: trace_printk_init_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_printk_init_buffers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81271358)
Location: kernel/trace/trace.c:3306
Inline: True
Direct callers:
  - kernel/trace/trace_printk.c:hold_module_trace_bprintk_format
```
**Symbols:**

```
ffffffff8205d806-ffffffff8205d81a: trace_printk_init_buffers.cold (STB_LOCAL)
ffffffff81271330-ffffffff81271478: trace_printk_init_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_printk_init_buffers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81288648)
Location: kernel/trace/trace.c:3397
Inline: True
Direct callers:
  - kernel/trace/trace_printk.c:hold_module_trace_bprintk_format
```
**Symbols:**

```
ffffffff820dc127-ffffffff820dc13b: trace_printk_init_buffers.cold (STB_LOCAL)
ffffffff81288620-ffffffff81288768: trace_printk_init_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_printk_init_buffers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff812a39a8)
Location: kernel/trace/trace.c:3374
Inline: True
Direct callers:
  - kernel/trace/trace_printk.c:hold_module_trace_bprintk_format
```
**Symbols:**

```
ffffffff821b7fb8-ffffffff821b7fcc: trace_printk_init_buffers.cold (STB_LOCAL)
ffffffff812a3980-ffffffff812a3acf: trace_printk_init_buffers (STB_GLOBAL)
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
void trace_printk_init_buffers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010228d00)
Location: kernel/trace/trace.c:3039
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace_printk.c:hold_module_trace_bprintk_format
```
**Symbols:**

```
ffff800010228d00-ffff800010228e24: trace_printk_init_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void trace_printk_init_buffers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c04662d8)
Location: kernel/trace/trace.c:3039
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace_printk.c:hold_module_trace_bprintk_format
```
**Symbols:**

```
c04662d8-c0466400: trace_printk_init_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void trace_printk_init_buffers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002afd90)
Location: kernel/trace/trace.c:3039
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace_printk.c:hold_module_trace_bprintk_format
```
**Symbols:**

```
c0000000002afd90-c0000000002aff40: trace_printk_init_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void trace_printk_init_buffers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe000183532)
Location: kernel/trace/trace.c:3039
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace_printk.c:module_trace_bprintk_format_notify
```
**Symbols:**

```
ffffffe000183532-ffffffe000183684: trace_printk_init_buffers (STB_GLOBAL)
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
void trace_printk_init_buffers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a5ad4)
Location: kernel/trace/trace.c:3039
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace_printk.c:hold_module_trace_bprintk_format
```
**Symbols:**

```
ffffffff811a5ac6-ffffffff811a5b9c: trace_printk_init_buffers.cold (STB_LOCAL)
ffffffff811a4480-ffffffff811a44b7: trace_printk_init_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_printk_init_buffers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81198a64)
Location: kernel/trace/trace.c:3039
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace_printk.c:hold_module_trace_bprintk_format
```
**Symbols:**

```
ffffffff81198a56-ffffffff81198b2c: trace_printk_init_buffers.cold (STB_LOCAL)
ffffffff81197450-ffffffff81197487: trace_printk_init_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_printk_init_buffers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a38a4)
Location: kernel/trace/trace.c:3039
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace_printk.c:hold_module_trace_bprintk_format
```
**Symbols:**

```
ffffffff811a3896-ffffffff811a396c: trace_printk_init_buffers.cold (STB_LOCAL)
ffffffff811a2250-ffffffff811a2287: trace_printk_init_buffers (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void trace_printk_init_buffers();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b1634)
Location: kernel/trace/trace.c:3039
Inline: True
Direct callers:
  - kernel/trace/trace.c:tracer_alloc_buffers
  - kernel/trace/trace_printk.c:hold_module_trace_bprintk_format
```
**Symbols:**

```
ffffffff811b1626-ffffffff811b16fc: trace_printk_init_buffers.cold (STB_LOCAL)
ffffffff811affe0-ffffffff811b0017: trace_printk_init_buffers (STB_GLOBAL)
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
