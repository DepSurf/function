# Function: <code>event_trace_add_tracer</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int event_trace_add_tracer(struct dentry *parent, struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff811613a0)
Location: kernel/trace/trace_events.c:2972
Inline: False
Direct callers:
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff811613a0-ffffffff8116144b: event_trace_add_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int event_trace_add_tracer(struct dentry *parent, struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff8116bac0)
Location: kernel/trace/trace_events.c:2877
Inline: False
Direct callers:
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff8116bac0-ffffffff8116bb6b: event_trace_add_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int event_trace_add_tracer(struct dentry *parent, struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81176db0)
Location: kernel/trace/trace_events.c:2858
Inline: False
Direct callers:
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff81176db0-ffffffff81176e5b: event_trace_add_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int event_trace_add_tracer(struct dentry *parent, struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81179b30)
Location: kernel/trace/trace_events.c:2955
Inline: False
Direct callers:
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff81179b30-ffffffff81179bdf: event_trace_add_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int event_trace_add_tracer(struct dentry *parent, struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff81187290)
Location: kernel/trace/trace_events.c:2970
Inline: False
Direct callers:
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff81187290-ffffffff81187328: event_trace_add_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int event_trace_add_tracer(struct dentry *parent, struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2982
Inline: False
Direct callers:
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff811965bf-ffffffff811965de: event_trace_add_tracer.cold.31 (STB_LOCAL)
ffffffff81196320-ffffffff811963a0: event_trace_add_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int event_trace_add_tracer(struct dentry *parent, struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2983
Inline: False
Direct callers:
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff811a4700-ffffffff811a471f: event_trace_add_tracer.cold.30 (STB_LOCAL)
ffffffff811a4480-ffffffff811a4500: event_trace_add_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int event_trace_add_tracer(struct dentry *parent, struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2973
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811b2662-ffffffff811b2686: event_trace_add_tracer.cold (STB_LOCAL)
ffffffff811b2330-ffffffff811b23a4: event_trace_add_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int event_trace_add_tracer(struct dentry *parent, struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2972
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811bdc5a-ffffffff811bdc7e: event_trace_add_tracer.cold (STB_LOCAL)
ffffffff811bd9b0-ffffffff811bda24: event_trace_add_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int event_trace_add_tracer(struct dentry *parent, struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:3267
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811d7432-ffffffff811d7453: event_trace_add_tracer.cold (STB_LOCAL)
ffffffff811d6ee0-ffffffff811d6fb9: event_trace_add_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int event_trace_add_tracer(struct dentry *parent, struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:3281
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create_dir
```
**Symbols:**

```
ffffffff81be61f4-ffffffff81be6214: event_trace_add_tracer.cold (STB_LOCAL)
ffffffff811d4350-ffffffff811d4489: event_trace_add_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int event_trace_add_tracer(struct dentry *parent, struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:3492
Inline: False
```
**Symbols:**

```
ffffffff81bd7eae-ffffffff81bd7ecf: event_trace_add_tracer.cold (STB_LOCAL)
ffffffff811d5a00-ffffffff811d5b15: event_trace_add_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int event_trace_add_tracer(struct dentry *parent, struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:3511
Inline: False
```
**Symbols:**

```
ffffffff81cb65ab-ffffffff81cb65cb: event_trace_add_tracer.cold (STB_LOCAL)
ffffffff81202830-ffffffff812028c2: event_trace_add_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int event_trace_add_tracer(struct dentry *parent, struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:3602
Inline: False
```
**Symbols:**

```
ffffffff81e6757e-ffffffff81e6759e: event_trace_add_tracer.cold (STB_LOCAL)
ffffffff8123dcb0-ffffffff8123dd56: event_trace_add_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int event_trace_add_tracer(struct dentry *parent, struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff8128b5d0)
Location: kernel/trace/trace_events.c:3693
Inline: False
```
**Symbols:**

```
ffffffff8128b5d0-ffffffff8128b6a4: event_trace_add_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int event_trace_add_tracer(struct dentry *parent, struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812a84d0)
Location: kernel/trace/trace_events.c:3687
Inline: False
```
**Symbols:**

```
ffffffff812a84d0-ffffffff812a85a4: event_trace_add_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int event_trace_add_tracer(struct dentry *parent, struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffff812c41e0)
Location: kernel/trace/trace_events.c:3905
Inline: False
```
**Symbols:**

```
ffffffff812c41e0-ffffffff812c42b4: event_trace_add_tracer (STB_GLOBAL)
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
int event_trace_add_tracer(struct dentry *parent, struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffff80001023cd08)
Location: kernel/trace/trace_events.c:2972
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffff80001023cd08-ffff80001023cdcc: event_trace_add_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int event_trace_add_tracer(struct dentry *parent, struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (c04785d8)
Location: kernel/trace/trace_events.c:2972
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
c04785d8-c047867c: event_trace_add_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int event_trace_add_tracer(struct dentry *parent, struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (c0000000002cc180)
Location: kernel/trace/trace_events.c:2972
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
c0000000002cc180-c0000000002cc2a4: event_trace_add_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int event_trace_add_tracer(struct dentry *parent, struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_events.c (ffffffe000192dc6)
Location: kernel/trace/trace_events.c:2972
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffe000192dc6-ffffffe000192e6c: event_trace_add_tracer (STB_GLOBAL)
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
int event_trace_add_tracer(struct dentry *parent, struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2972
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811b627a-ffffffff811b629e: event_trace_add_tracer.cold (STB_LOCAL)
ffffffff811b5fd0-ffffffff811b6044: event_trace_add_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int event_trace_add_tracer(struct dentry *parent, struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2972
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811a907a-ffffffff811a909e: event_trace_add_tracer.cold (STB_LOCAL)
ffffffff811a8dd0-ffffffff811a8e44: event_trace_add_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int event_trace_add_tracer(struct dentry *parent, struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2972
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811b404a-ffffffff811b406e: event_trace_add_tracer.cold (STB_LOCAL)
ffffffff811b3da0-ffffffff811b3e14: event_trace_add_tracer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int event_trace_add_tracer(struct dentry *parent, struct trace_array *tr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_events.c (0)
Location: kernel/trace/trace_events.c:2972
Inline: False
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811c20ea-ffffffff811c210e: event_trace_add_tracer.cold (STB_LOCAL)
ffffffff811c1e40-ffffffff811c1eb4: event_trace_add_tracer (STB_GLOBAL)
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
