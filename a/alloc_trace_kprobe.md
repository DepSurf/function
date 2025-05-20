# Function: <code>alloc_trace_kprobe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81168f3e)
Location: kernel/trace/trace_kprobe.c:263
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81176605)
Location: kernel/trace/trace_kprobe.c:263
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81182094)
Location: kernel/trace/trace_kprobe.c:278
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
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
In kernel/trace/trace_kprobe.c (ffffffff81184e9e)
Location: kernel/trace/trace_kprobe.c:281
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81192b7e)
Location: kernel/trace/trace_kprobe.c:281
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct trace_kprobe *alloc_trace_kprobe(const char *group, const char *event, void *addr, const char *symbol, long unsigned int offs, int maxactive, int nargs, bool is_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811a7ea0)
Location: kernel/trace/trace_kprobe.c:305
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
**Symbols:**

```
ffffffff811a7ea0-ffffffff811a80f6: alloc_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct trace_kprobe *alloc_trace_kprobe(const char *group, const char *event, void *addr, const char *symbol, long unsigned int offs, int maxactive, int nargs, bool is_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811b5070)
Location: kernel/trace/trace_kprobe.c:189
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
ffffffff811b5070-ffffffff811b52d6: alloc_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct trace_kprobe *alloc_trace_kprobe(const char *group, const char *event, void *addr, const char *symbol, long unsigned int offs, int maxactive, int nargs, bool is_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c3f40)
Location: kernel/trace/trace_kprobe.c:219
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
ffffffff811c3f40-ffffffff811c4089: alloc_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct trace_kprobe *alloc_trace_kprobe(const char *group, const char *event, void *addr, const char *symbol, long unsigned int offs, int maxactive, int nargs, bool is_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811cfe60)
Location: kernel/trace/trace_kprobe.c:256
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
ffffffff811cfe60-ffffffff811cffab: alloc_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct trace_kprobe *alloc_trace_kprobe(const char *group, const char *event, void *addr, const char *symbol, long unsigned int offs, int maxactive, int nargs, bool is_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811ed4e0)
Location: kernel/trace/trace_kprobe.c:255
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
ffffffff811ed4e0-ffffffff811ed65e: alloc_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct trace_kprobe *alloc_trace_kprobe(const char *group, const char *event, void *addr, const char *symbol, long unsigned int offs, int maxactive, int nargs, bool is_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811eb630)
Location: kernel/trace/trace_kprobe.c:257
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
ffffffff811eb630-ffffffff811eb7ae: alloc_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct trace_kprobe *alloc_trace_kprobe(const char *group, const char *event, void *addr, const char *symbol, long unsigned int offs, int maxactive, int nargs, bool is_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811eca00)
Location: kernel/trace/trace_kprobe.c:257
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
```
**Symbols:**

```
ffffffff811eca00-ffffffff811ecb7e: alloc_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct trace_kprobe *alloc_trace_kprobe(const char *group, const char *event, void *addr, const char *symbol, long unsigned int offs, int maxactive, int nargs, bool is_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff8121da70)
Location: kernel/trace/trace_kprobe.c:253
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
```
**Symbols:**

```
ffffffff8121da70-ffffffff8121dc0c: alloc_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct trace_kprobe *alloc_trace_kprobe(const char *group, const char *event, void *addr, const char *symbol, long unsigned int offs, int maxactive, int nargs, bool is_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff8125d040)
Location: kernel/trace/trace_kprobe.c:254
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
```
**Symbols:**

```
ffffffff8125d040-ffffffff8125d1f5: alloc_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct trace_kprobe *alloc_trace_kprobe(const char *group, const char *event, void *addr, const char *symbol, long unsigned int offs, int maxactive, int nargs, bool is_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff812ac2e0)
Location: kernel/trace/trace_kprobe.c:256
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
```
**Symbols:**

```
ffffffff812ac2e0-ffffffff812ac498: alloc_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct trace_kprobe *alloc_trace_kprobe(const char *group, const char *event, void *addr, const char *symbol, long unsigned int offs, int maxactive, int nargs, bool is_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff812cff20)
Location: kernel/trace/trace_kprobe.c:256
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
```
**Symbols:**

```
ffffffff812cff20-ffffffff812d00d3: alloc_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct trace_kprobe *alloc_trace_kprobe(const char *group, const char *event, void *addr, const char *symbol, long unsigned int offs, int maxactive, int nargs, bool is_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff812ed920)
Location: kernel/trace/trace_kprobe.c:256
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
```
**Symbols:**

```
ffffffff812ed920-ffffffff812edad3: alloc_trace_kprobe (STB_LOCAL)
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
struct trace_kprobe *alloc_trace_kprobe(const char *group, const char *event, void *addr, const char *symbol, long unsigned int offs, int maxactive, int nargs, bool is_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffff800010250760)
Location: kernel/trace/trace_kprobe.c:256
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
ffff800010250760-ffff800010250898: alloc_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct trace_kprobe *alloc_trace_kprobe(const char *group, const char *event, void *addr, const char *symbol, long unsigned int offs, int maxactive, int nargs, bool is_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c04834cc)
Location: kernel/trace/trace_kprobe.c:256
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
c04834cc-c04835e4: alloc_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct trace_kprobe *alloc_trace_kprobe(const char *group, const char *event, void *addr, const char *symbol, long unsigned int offs, int maxactive, int nargs, bool is_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (c0000000002eeea0)
Location: kernel/trace/trace_kprobe.c:256
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
c0000000002eeea0-c0000000002ef0e4: alloc_trace_kprobe (STB_LOCAL)
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
struct trace_kprobe *alloc_trace_kprobe(const char *group, const char *event, void *addr, const char *symbol, long unsigned int offs, int maxactive, int nargs, bool is_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c8480)
Location: kernel/trace/trace_kprobe.c:256
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
ffffffff811c8480-ffffffff811c85cb: alloc_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct trace_kprobe *alloc_trace_kprobe(const char *group, const char *event, void *addr, const char *symbol, long unsigned int offs, int maxactive, int nargs, bool is_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811bb260)
Location: kernel/trace/trace_kprobe.c:256
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
ffffffff811bb260-ffffffff811bb3ab: alloc_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct trace_kprobe *alloc_trace_kprobe(const char *group, const char *event, void *addr, const char *symbol, long unsigned int offs, int maxactive, int nargs, bool is_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811c6250)
Location: kernel/trace/trace_kprobe.c:256
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
ffffffff811c6250-ffffffff811c639b: alloc_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct trace_kprobe *alloc_trace_kprobe(const char *group, const char *event, void *addr, const char *symbol, long unsigned int offs, int maxactive, int nargs, bool is_return);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811d44b0)
Location: kernel/trace/trace_kprobe.c:256
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
ffffffff811d44b0-ffffffff811d45fb: alloc_trace_kprobe (STB_LOCAL)
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
