# Function: <code>bpf_get_stack</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811d14e0)
Location: kernel/bpf/stackmap.c:438
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stack_tp
```
**Symbols:**

```
ffffffff811d14e0-ffffffff811d163c: bpf_get_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811e1060)
Location: kernel/bpf/stackmap.c:450
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stack_tp
```
**Symbols:**

```
ffffffff811e1060-ffffffff811e11bc: bpf_get_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811f6c40)
Location: kernel/bpf/stackmap.c:445
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stack_tp
```
**Symbols:**

```
ffffffff811f6c40-ffffffff811f6d99: bpf_get_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81203c00)
Location: kernel/bpf/stackmap.c:446
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stack_tp
```
**Symbols:**

```
ffffffff81203c00-ffffffff81203d59: bpf_get_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff8122ba80)
Location: kernel/bpf/stackmap.c:451
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stack_tp
```
**Symbols:**

```
ffffffff8122ba80-ffffffff8122bbdb: bpf_get_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81233e80)
Location: kernel/bpf/stackmap.c:636
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stack_tp
```
**Symbols:**

```
ffffffff81233e80-ffffffff81233e9d: bpf_get_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81237c40)
Location: kernel/bpf/stackmap.c:501
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stack_tp
```
**Symbols:**

```
ffffffff81237c40-ffffffff81237c5d: bpf_get_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81272210)
Location: kernel/bpf/stackmap.c:508
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stack_tp
```
**Symbols:**

```
ffffffff81272210-ffffffff8127222d: bpf_get_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff812c13d0)
Location: kernel/bpf/stackmap.c:455
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stack_tp
```
**Symbols:**

```
ffffffff812c13d0-ffffffff812c13ff: bpf_get_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81324cb0)
Location: kernel/bpf/stackmap.c:455
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stack_tp
```
**Symbols:**

```
ffffffff81324cb0-ffffffff81324cdf: bpf_get_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81354f10)
Location: kernel/bpf/stackmap.c:452
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stack_tp
```
**Symbols:**

```
ffffffff81354f10-ffffffff81354f3f: bpf_get_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff8137d8e0)
Location: kernel/bpf/stackmap.c:461
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stack_tp
```
**Symbols:**

```
ffffffff8137d8e0-ffffffff8137d90f: bpf_get_stack (STB_GLOBAL)
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
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffff80001028c338)
Location: kernel/bpf/stackmap.c:446
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stack_tp
```
**Symbols:**

```
ffff80001028c338-ffff80001028c4cc: bpf_get_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (c04bba1c)
Location: kernel/bpf/stackmap.c:446
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stack_tp
```
**Symbols:**

```
c04bba1c-c04bbba0: bpf_get_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (c0000000003385b0)
Location: kernel/bpf/stackmap.c:446
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stack_tp
```
**Symbols:**

```
c0000000003385b0-c000000000338810: bpf_get_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffe0001bfd7a)
Location: kernel/bpf/stackmap.c:446
Inline: False
```
**Symbols:**

```
ffffffe0001bfd7a-ffffffe0001bfec0: bpf_get_stack (STB_GLOBAL)
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
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811fc220)
Location: kernel/bpf/stackmap.c:446
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stack_tp
```
**Symbols:**

```
ffffffff811fc220-ffffffff811fc379: bpf_get_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811eef70)
Location: kernel/bpf/stackmap.c:446
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stack_tp
```
**Symbols:**

```
ffffffff811eef70-ffffffff811ef0c9: bpf_get_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff811f9ff0)
Location: kernel/bpf/stackmap.c:446
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stack_tp
```
**Symbols:**

```
ffffffff811f9ff0-ffffffff811fa149: bpf_get_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_get_stack(u64 regs, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81208ab0)
Location: kernel/bpf/stackmap.c:446
Inline: False
Direct callers:
  - kernel/trace/bpf_trace.c:bpf_get_stack_raw_tp
  - kernel/trace/bpf_trace.c:bpf_get_stack_tp
```
**Symbols:**

```
ffffffff81208ab0-ffffffff81208c09: bpf_get_stack (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
