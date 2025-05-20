# Function: <code>top_trace_array</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct trace_array *top_trace_array();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff8118c37d)
Location: kernel/trace/trace.h:270
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_set_clr_event
  - kernel/trace/trace_events.c:event_enable_func
Direct callers:
  - kernel/trace/trace_events.c:event_trace_enable_again
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:trace_event_init
```
**Symbols:**

```
ffffffff8118c37d-ffffffff8118c3bb: top_trace_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct trace_array *top_trace_array();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff8116b841)
Location: kernel/trace/trace.h:280
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_set_clr_event
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_enable_again
```
**Symbols:**

```
ffffffff8119f0af-ffffffff8119f0ef: top_trace_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct trace_array *top_trace_array();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81176b31)
Location: kernel/trace/trace.h:285
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:event_enable_func
  - kernel/trace/trace_events.c:trace_set_clr_event
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_enable_again
```
**Symbols:**

```
ffffffff811aeb55-ffffffff811aeb95: top_trace_array (STB_LOCAL)
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
In kernel/trace/trace_events.c (ffffffff820cac68)
Location: kernel/trace/trace.h:291
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_enable_again
  - kernel/trace/trace_events.c:trace_set_clr_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct trace_array *top_trace_array();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811867b0)
Location: kernel/trace/trace.h:293
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_set_clr_event
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_enable_again
```
**Symbols:**

```
ffffffff811873c4-ffffffff811873ef: top_trace_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct trace_array *top_trace_array();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81195810)
Location: kernel/trace/trace.h:301
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_set_clr_event
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_enable_again
```
**Symbols:**

```
ffffffff81196430-ffffffff8119645b: top_trace_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct trace_array *top_trace_array();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811a3980)
Location: kernel/trace/trace.h:302
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_set_clr_event
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_enable_again
```
**Symbols:**

```
ffffffff811a0bc0-ffffffff811a0beb: top_trace_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
struct trace_array *top_trace_array();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811b1860)
Location: kernel/trace/trace.h:351
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_set_clr_event
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_enable_again
```
```
In kernel/trace/trace_kprobe.c (ffffffff828cec6b)
Location: kernel/trace/trace.h:351
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
**Symbols:**

```
ffffffff811aec00-ffffffff811aec37: top_trace_array (STB_LOCAL)
ffffffff811b2449-ffffffff811b245c: top_trace_array.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff828d5d52)
Location: kernel/trace/trace.h:352
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_enable_again
  - kernel/trace/trace_events.c:trace_set_clr_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff828d7147)
Location: kernel/trace/trace.h:352
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct trace_array *top_trace_array();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811d6b10)
Location: kernel/trace/trace.h:402
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:trace_set_clr_event
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_enable_again
```
```
In kernel/trace/trace_kprobe.c (ffffffff82cf6c96)
Location: kernel/trace/trace.h:402
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_boot_kprobe_events
```
```
In kernel/trace/trace_boot.c (ffffffff82cf7986)
Location: kernel/trace/trace.h:402
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init
```
**Symbols:**

```
ffffffff811d705e-ffffffff811d7083: top_trace_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct trace_array *top_trace_array();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811d3e90)
Location: kernel/trace/trace.h:403
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:trace_set_clr_event
Direct callers:
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_enable_again
```
```
In kernel/trace/trace_kprobe.c (ffffffff82fe379d)
Location: kernel/trace/trace.h:403
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:enable_boot_kprobe_events
```
```
In kernel/trace/trace_boot.c (ffffffff82fe452c)
Location: kernel/trace/trace.h:403
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init
```
**Symbols:**

```
ffffffff81be5dc3-ffffffff81be5de8: top_trace_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct trace_array *top_trace_array();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811d5580)
Location: kernel/trace/trace.h:398
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:trace_set_clr_event
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_enable_again
```
```
In kernel/trace/trace_kprobe.c (ffffffff831edfc9)
Location: kernel/trace/trace.h:398
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
```
In kernel/trace/trace_boot.c (ffffffff831eebb6)
Location: kernel/trace/trace.h:398
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init
```
**Symbols:**

```
ffffffff81bd7be1-ffffffff81bd7c06: top_trace_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct trace_array *top_trace_array();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812023c0)
Location: kernel/trace/trace.h:402
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:trace_set_clr_event
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_enable_again
```
```
In kernel/trace/trace_kprobe.c (ffffffff832d2c8f)
Location: kernel/trace/trace.h:402
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
```
In kernel/trace/trace_boot.c (ffffffff832d4140)
Location: kernel/trace/trace.h:402
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init
```
**Symbols:**

```
ffffffff81cb619b-ffffffff81cb61c0: top_trace_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct trace_array *top_trace_array();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff8123d7d0)
Location: kernel/trace/trace.h:410
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:trace_set_clr_event
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_enable_again
```
```
In kernel/trace/trace_kprobe.c (ffffffff834870d4)
Location: kernel/trace/trace.h:410
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
```
In kernel/trace/trace_boot.c (ffffffff834886ed)
Location: kernel/trace/trace.h:410
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init
```
**Symbols:**

```
ffffffff81e6718a-ffffffff81e671b5: top_trace_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff83eb58f8)
Location: kernel/trace/trace.h:409
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_enable_again
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:trace_set_clr_event
```
```
In kernel/trace/trace_eprobe.c (ffffffff81293648)
Location: kernel/trace/trace.h:409
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:trace_eprobe_parse_filter
```
```
In kernel/trace/trace_kprobe.c (ffffffff83eb6b22)
Location: kernel/trace/trace.h:409
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
```
In kernel/trace/trace_boot.c (ffffffff83eb8693)
Location: kernel/trace/trace.h:409
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff836daea8)
Location: kernel/trace/trace.h:428
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_enable_again
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:trace_set_clr_event
```
```
In kernel/trace/trace_eprobe.c (ffffffff812b0906)
Location: kernel/trace/trace.h:428
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:trace_eprobe_parse_filter
```
```
In kernel/trace/trace_kprobe.c (ffffffff836dc102)
Location: kernel/trace/trace.h:428
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
```
In kernel/trace/trace_boot.c (ffffffff836ddb83)
Location: kernel/trace/trace.h:428
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff8390d418)
Location: kernel/trace/trace.h:444
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_enable_again
  - kernel/trace/trace_events.c:trace_get_event_file
  - kernel/trace/trace_events.c:trace_set_clr_event
```
```
In kernel/trace/trace_eprobe.c (ffffffff812ccff6)
Location: kernel/trace/trace.h:444
Inline: True
Inline callers:
  - kernel/trace/trace_eprobe.c:trace_eprobe_parse_filter
```
```
In kernel/trace/trace_kprobe.c (ffffffff8390e732)
Location: kernel/trace/trace.h:444
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
```
In kernel/trace/trace_boot.c (ffffffff839101b3)
Location: kernel/trace/trace.h:444
Inline: True
Inline callers:
  - kernel/trace/trace_boot.c:trace_boot_init
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct trace_array *top_trace_array();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffff80001023b8c8)
Location: kernel/trace/trace.h:352
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_set_clr_event
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_enable_again
```
```
In kernel/trace/trace_kprobe.c (ffff80001144fb10)
Location: kernel/trace/trace.h:352
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
**Symbols:**

```
ffff800010238c10-ffff800010238c44: top_trace_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct trace_array *top_trace_array();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (c0477a84)
Location: kernel/trace/trace.h:352
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_set_clr_event
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_enable_again
```
```
In kernel/trace/trace_kprobe.c (c152a2d0)
Location: kernel/trace/trace.h:352
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
**Symbols:**

```
c04747cc-c0474828: top_trace_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
struct trace_array *top_trace_array();
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (c0000000002ca920)
Location: kernel/trace/trace.h:352
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_set_clr_event
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_enable_again
```
```
In kernel/trace/trace_kprobe.c (c000000001376df0)
Location: kernel/trace/trace.h:352
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
**Symbols:**

```
c0000000002cc398-c0000000002cc3d0: top_trace_array (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct trace_array *top_trace_array();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffe0001923d2)
Location: kernel/trace/trace.h:352
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_set_clr_event
Direct callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_enable_again
```
**Symbols:**

```
ffffffe00018f984-ffffffe00018f9b4: top_trace_array (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff828bec03)
Location: kernel/trace/trace.h:352
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_enable_again
  - kernel/trace/trace_events.c:trace_set_clr_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff828bfff8)
Location: kernel/trace/trace.h:352
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff828b72a3)
Location: kernel/trace/trace.h:352
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_enable_again
  - kernel/trace/trace_events.c:trace_set_clr_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff828b8698)
Location: kernel/trace/trace.h:352
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff828d1986)
Location: kernel/trace/trace.h:352
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_enable_again
  - kernel/trace/trace_events.c:trace_set_clr_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff828d2d7b)
Location: kernel/trace/trace.h:352
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff828d6da7)
Location: kernel/trace/trace.h:352
Inline: True
Inline callers:
  - kernel/trace/trace_events.c:trace_event_init
  - kernel/trace/trace_events.c:event_trace_init
  - kernel/trace/trace_events.c:event_trace_enable_again
  - kernel/trace/trace_events.c:trace_set_clr_event
```
```
In kernel/trace/trace_kprobe.c (ffffffff828d819c)
Location: kernel/trace/trace.h:352
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:init_kprobe_trace
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
</ul>
<b>Arch</b>
<ul>
</ul>
