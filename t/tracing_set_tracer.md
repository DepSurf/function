# Function: <code>tracing_set_tracer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tracing_set_tracer(struct trace_array *tr, const char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114e3e0)
Location: kernel/trace/trace.c:4366
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff8114e3e0-ffffffff8114e552: tracing_set_tracer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tracing_set_tracer(struct trace_array *tr, const char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81157060)
Location: kernel/trace/trace.c:4763
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff81157060-ffffffff811571d9: tracing_set_tracer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tracing_set_tracer(struct trace_array *tr, const char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811621a0)
Location: kernel/trace/trace.c:5012
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff811621a0-ffffffff81162319: tracing_set_tracer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tracing_set_tracer(struct trace_array *tr, const char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811655b0)
Location: kernel/trace/trace.c:5329
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff811655b0-ffffffff81165729: tracing_set_tracer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tracing_set_tracer(struct trace_array *tr, const char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811724f0)
Location: kernel/trace/trace.c:5333
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff811724f0-ffffffff811726a4: tracing_set_tracer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int tracing_set_tracer(struct trace_array *tr, const char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:5339
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff811814f0-ffffffff811816a3: tracing_set_tracer (STB_LOCAL)
ffffffff8118653a-ffffffff8118654e: tracing_set_tracer.cold.78 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int tracing_set_tracer(struct trace_array *tr, const char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:5362
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff8118eeb0-ffffffff8118f063: tracing_set_tracer (STB_LOCAL)
ffffffff81193eca-ffffffff81193ede: tracing_set_tracer.cold.78 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tracing_set_tracer(struct trace_array *tr, const char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:5583
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff8119c830-ffffffff8119ca41: tracing_set_tracer (STB_LOCAL)
ffffffff811a1aa7-ffffffff811a1abb: tracing_set_tracer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int tracing_set_tracer(struct trace_array *tr, const char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:5636
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff811a81e0-ffffffff811a83f1: tracing_set_tracer (STB_LOCAL)
ffffffff811ad492-ffffffff811ad4a6: tracing_set_tracer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tracing_set_tracer(struct trace_array *tr, const char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:5839
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
```
**Symbols:**

```
ffffffff811c55d0-ffffffff811c55e4: tracing_set_tracer.cold (STB_LOCAL)
ffffffff811c44f0-ffffffff811c476a: tracing_set_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tracing_set_tracer(struct trace_array *tr, const char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:5912
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace_boot.c:trace_boot_enable_tracer
```
**Symbols:**

```
ffffffff81be58ed-ffffffff81be5901: tracing_set_tracer.cold (STB_LOCAL)
ffffffff811c20f0-ffffffff811c236a: tracing_set_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tracing_set_tracer(struct trace_array *tr, const char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:6249
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
```
**Symbols:**

```
ffffffff81bd7795-ffffffff81bd77a9: tracing_set_tracer.cold (STB_LOCAL)
ffffffff811c3160-ffffffff811c33ea: tracing_set_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tracing_set_tracer(struct trace_array *tr, const char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:6327
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
```
**Symbols:**

```
ffffffff81cb5666-ffffffff81cb572b: tracing_set_tracer.cold (STB_LOCAL)
ffffffff811ee1b0-ffffffff811ee4f9: tracing_set_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tracing_set_tracer(struct trace_array *tr, const char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:6345
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
```
**Symbols:**

```
ffffffff81e66648-ffffffff81e66734: tracing_set_tracer.cold (STB_LOCAL)
ffffffff812264f0-ffffffff8122684d: tracing_set_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tracing_set_tracer(struct trace_array *tr, const char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:6378
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
```
**Symbols:**

```
ffffffff8205d8a3-ffffffff8205d982: tracing_set_tracer.cold (STB_LOCAL)
ffffffff81271780-ffffffff81271a98: tracing_set_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tracing_set_tracer(struct trace_array *tr, const char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:6501
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
```
**Symbols:**

```
ffffffff820dc1c4-ffffffff820dc2a3: tracing_set_tracer.cold (STB_LOCAL)
ffffffff81288a80-ffffffff81288d98: tracing_set_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tracing_set_tracer(struct trace_array *tr, const char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:6515
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:register_tracer
  - kernel/trace/trace_boot.c:trace_boot_init_one_instance
```
**Symbols:**

```
ffffffff821b8023-ffffffff821b80d1: tracing_set_tracer.cold (STB_LOCAL)
ffffffff812a3dd0-ffffffff812a40ef: tracing_set_tracer (STB_GLOBAL)
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
int tracing_set_tracer(struct trace_array *tr, const char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff800010224c28)
Location: kernel/trace/trace.c:5636
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffff800010224c28-ffff800010224e48: tracing_set_tracer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tracing_set_tracer(struct trace_array *tr, const char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c04620b4)
Location: kernel/trace/trace.c:5636
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
c04620b4-c04622fc: tracing_set_tracer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tracing_set_tracer(struct trace_array *tr, const char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a9c70)
Location: kernel/trace/trace.c:5636
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
c0000000002a9c70-c0000000002aa17c: tracing_set_tracer (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tracing_set_tracer(struct trace_array *tr, const char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017fd64)
Location: kernel/trace/trace.c:5636
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffe00017fd64-ffffffe00017ff24: tracing_set_tracer (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int tracing_set_tracer(struct trace_array *tr, const char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:5636
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff811a0800-ffffffff811a0a11: tracing_set_tracer (STB_LOCAL)
ffffffff811a5ab2-ffffffff811a5ac6: tracing_set_tracer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int tracing_set_tracer(struct trace_array *tr, const char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:5636
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff81193810-ffffffff81193a21: tracing_set_tracer (STB_LOCAL)
ffffffff81198a42-ffffffff81198a56: tracing_set_tracer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int tracing_set_tracer(struct trace_array *tr, const char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:5636
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff8119e5d0-ffffffff8119e7e1: tracing_set_tracer (STB_LOCAL)
ffffffff811a3882-ffffffff811a3896: tracing_set_tracer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int tracing_set_tracer(struct trace_array *tr, const char *buf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (0)
Location: kernel/trace/trace.c:5636
Inline: False
Direct callers:
  - kernel/trace/trace.c:tracing_set_trace_write
  - kernel/trace/trace.c:register_tracer
```
**Symbols:**

```
ffffffff811ac2b0-ffffffff811ac4c1: tracing_set_tracer (STB_LOCAL)
ffffffff811b1612-ffffffff811b1626: tracing_set_tracer.cold (STB_LOCAL)
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
