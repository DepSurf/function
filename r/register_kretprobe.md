# Function: <code>register_kretprobe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int register_kretprobe(struct kretprobe *rp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8112f2d0)
Location: kernel/kprobes.c:1837
Inline: True
Direct callers:
  - kernel/kprobes.c:register_kretprobes
  - kernel/trace/trace_kprobe.c:__register_trace_kprobe
```
**Symbols:**

```
ffffffff8112f2d0-ffffffff8112f52c: register_kretprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int register_kretprobe(struct kretprobe *rp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81137560)
Location: kernel/kprobes.c:1837
Inline: True
Direct callers:
  - kernel/kprobes.c:register_kretprobes
  - kernel/trace/trace_kprobe.c:__register_trace_kprobe
```
**Symbols:**

```
ffffffff81137560-ffffffff81137820: register_kretprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int register_kretprobe(struct kretprobe *rp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811412e0)
Location: kernel/kprobes.c:1837
Inline: True
Direct callers:
  - kernel/kprobes.c:register_kretprobes
  - kernel/trace/trace_kprobe.c:__register_trace_kprobe
```
**Symbols:**

```
ffffffff811412e0-ffffffff811415a1: register_kretprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int register_kretprobe(struct kretprobe *rp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81142c40)
Location: kernel/kprobes.c:1916
Inline: False
```
**Symbols:**

```
ffffffff81142c40-ffffffff81142f21: register_kretprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int register_kretprobe(struct kretprobe *rp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8114f8f0)
Location: kernel/kprobes.c:1920
Inline: False
```
**Symbols:**

```
ffffffff8114f8f0-ffffffff8114fbd1: register_kretprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int register_kretprobe(struct kretprobe *rp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8115e430)
Location: kernel/kprobes.c:1964
Inline: False
```
**Symbols:**

```
ffffffff8115e430-ffffffff8115e70b: register_kretprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int register_kretprobe(struct kretprobe *rp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8116afb0)
Location: kernel/kprobes.c:1881
Inline: False
```
**Symbols:**

```
ffffffff8116afb0-ffffffff8116b283: register_kretprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int register_kretprobe(struct kretprobe *rp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81177da0)
Location: kernel/kprobes.c:1885
Inline: False
```
**Symbols:**

```
ffffffff81177da0-ffffffff81177ff8: register_kretprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int register_kretprobe(struct kretprobe *rp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81183cb0)
Location: kernel/kprobes.c:1928
Inline: False
```
**Symbols:**

```
ffffffff81183cb0-ffffffff81183f16: register_kretprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int register_kretprobe(struct kretprobe *rp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81197a70)
Location: kernel/kprobes.c:1972
Inline: False
```
**Symbols:**

```
ffffffff81197a70-ffffffff81197d1a: register_kretprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int register_kretprobe(struct kretprobe *rp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81194ad0)
Location: kernel/kprobes.c:1986
Inline: True
```
**Symbols:**

```
ffffffff81194ad0-ffffffff81194dfa: register_kretprobe.part.0 (STB_LOCAL)
ffffffff81194ec0-ffffffff81194f29: register_kretprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int register_kretprobe(struct kretprobe *rp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81195ad0)
Location: kernel/kprobes.c:1991
Inline: True
```
**Symbols:**

```
ffffffff81195ad0-ffffffff81195df3: register_kretprobe.part.0 (STB_LOCAL)
ffffffff81195ec0-ffffffff81195f32: register_kretprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int register_kretprobe(struct kretprobe *rp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811bea30)
Location: kernel/kprobes.c:1983
Inline: True
```
**Symbols:**

```
ffffffff811bea30-ffffffff811bed67: register_kretprobe.part.0 (STB_LOCAL)
ffffffff811bee30-ffffffff811beea2: register_kretprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int register_kretprobe(struct kretprobe *rp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811f1e40)
Location: kernel/kprobes.c:2172
Inline: True
```
**Symbols:**

```
ffffffff811f1e40-ffffffff811f2053: register_kretprobe.part.0 (STB_LOCAL)
ffffffff81e6476c-ffffffff81e64781: register_kretprobe.cold (STB_LOCAL)
ffffffff811f2150-ffffffff811f21eb: register_kretprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int register_kretprobe(struct kretprobe *rp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81238b10)
Location: kernel/kprobes.c:2180
Inline: True
```
**Symbols:**

```
ffffffff81238b10-ffffffff81238d23: register_kretprobe.part.0 (STB_LOCAL)
ffffffff8205c810-ffffffff8205c825: register_kretprobe.cold (STB_LOCAL)
ffffffff81238e40-ffffffff81238edb: register_kretprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int register_kretprobe(struct kretprobe *rp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8124fc70)
Location: kernel/kprobes.c:2193
Inline: True
```
**Symbols:**

```
ffffffff8124fc70-ffffffff8124fe83: register_kretprobe.part.0 (STB_LOCAL)
ffffffff820db165-ffffffff820db17a: register_kretprobe.cold (STB_LOCAL)
ffffffff8124ff90-ffffffff8125001f: register_kretprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int register_kretprobe(struct kretprobe *rp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81269bff)
Location: kernel/kprobes.c:2194
Inline: True
```
**Symbols:**

```
ffffffff821b6ea0-ffffffff821b6eb5: register_kretprobe.cold (STB_LOCAL)
ffffffff81269ba0-ffffffff81269d9c: register_kretprobe (STB_GLOBAL)
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
int register_kretprobe(struct kretprobe *rp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffff8000101f92f8)
Location: kernel/kprobes.c:1928
Inline: True
```
**Symbols:**

```
ffff8000101f92f8-ffff8000101f94c4: register_kretprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int register_kretprobe(struct kretprobe *rp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (c04395b4)
Location: kernel/kprobes.c:1928
Inline: True
```
**Symbols:**

```
c04395b4-c0439768: register_kretprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int register_kretprobe(struct kretprobe *rp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (c000000000270960)
Location: kernel/kprobes.c:1928
Inline: True
```
**Symbols:**

```
c000000000270960-c000000000270c30: register_kretprobe (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int register_kretprobe(struct kretprobe *rp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8117c2d0)
Location: kernel/kprobes.c:1928
Inline: False
```
**Symbols:**

```
ffffffff8117c2d0-ffffffff8117c536: register_kretprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int register_kretprobe(struct kretprobe *rp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8116f470)
Location: kernel/kprobes.c:1928
Inline: False
```
**Symbols:**

```
ffffffff8116f470-ffffffff8116f6d6: register_kretprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int register_kretprobe(struct kretprobe *rp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8117a0a0)
Location: kernel/kprobes.c:1928
Inline: False
```
**Symbols:**

```
ffffffff8117a0a0-ffffffff8117a306: register_kretprobe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int register_kretprobe(struct kretprobe *rp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811879d0)
Location: kernel/kprobes.c:1928
Inline: False
```
**Symbols:**

```
ffffffff811879d0-ffffffff81187c43: register_kretprobe (STB_GLOBAL)
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
