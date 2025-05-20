# Function: <code>alloc_trace_uprobe</code>

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
In kernel/trace/trace_uprobe.c (ffffffff811704f5)
Location: kernel/trace/trace_uprobe.c:239
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
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
In kernel/trace/trace_uprobe.c (ffffffff8117dc17)
Location: kernel/trace/trace_uprobe.c:239
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
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
In kernel/trace/trace_uprobe.c (ffffffff81189810)
Location: kernel/trace/trace_uprobe.c:243
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
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
In kernel/trace/trace_uprobe.c (ffffffff8118c3a2)
Location: kernel/trace/trace_uprobe.c:245
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
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
In kernel/trace/trace_uprobe.c (ffffffff81199e62)
Location: kernel/trace/trace_uprobe.c:245
Inline: True
Inline callers:
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct trace_uprobe *alloc_trace_uprobe(const char *group, const char *event, int nargs, bool is_ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811af550)
Location: kernel/trace/trace_uprobe.c:248
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:create_trace_uprobe
```
**Symbols:**

```
ffffffff811af550-ffffffff811af702: alloc_trace_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct trace_uprobe *alloc_trace_uprobe(const char *group, const char *event, int nargs, bool is_ret);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811bdb40)
Location: kernel/trace/trace_uprobe.c:272
Inline: True
Direct callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811bdb40-ffffffff811bdd09: alloc_trace_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct trace_uprobe *alloc_trace_uprobe(const char *group, const char *event, int nargs, bool is_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811ccb80)
Location: kernel/trace/trace_uprobe.c:300
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811ccb80-ffffffff811ccc56: alloc_trace_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct trace_uprobe *alloc_trace_uprobe(const char *group, const char *event, int nargs, bool is_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811d9130)
Location: kernel/trace/trace_uprobe.c:338
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811d9130-ffffffff811d9219: alloc_trace_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct trace_uprobe *alloc_trace_uprobe(const char *group, const char *event, int nargs, bool is_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f4e40)
Location: kernel/trace/trace_uprobe.c:338
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811f4e40-ffffffff811f4f29: alloc_trace_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct trace_uprobe *alloc_trace_uprobe(const char *group, const char *event, int nargs, bool is_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f37d0)
Location: kernel/trace/trace_uprobe.c:338
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811f37d0-ffffffff811f38b9: alloc_trace_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct trace_uprobe *alloc_trace_uprobe(const char *group, const char *event, int nargs, bool is_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811f4750)
Location: kernel/trace/trace_uprobe.c:338
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
**Symbols:**

```
ffffffff811f4750-ffffffff811f4839: alloc_trace_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct trace_uprobe *alloc_trace_uprobe(const char *group, const char *event, int nargs, bool is_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff81225ad0)
Location: kernel/trace/trace_uprobe.c:335
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
**Symbols:**

```
ffffffff81225ad0-ffffffff81225bee: alloc_trace_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct trace_uprobe *alloc_trace_uprobe(const char *group, const char *event, int nargs, bool is_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff81265b10)
Location: kernel/trace/trace_uprobe.c:336
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
**Symbols:**

```
ffffffff81265b10-ffffffff81265c2f: alloc_trace_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct trace_uprobe *alloc_trace_uprobe(const char *group, const char *event, int nargs, bool is_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812b7450)
Location: kernel/trace/trace_uprobe.c:338
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
**Symbols:**

```
ffffffff812b7450-ffffffff812b756f: alloc_trace_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct trace_uprobe *alloc_trace_uprobe(const char *group, const char *event, int nargs, bool is_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812daab0)
Location: kernel/trace/trace_uprobe.c:336
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
**Symbols:**

```
ffffffff812daab0-ffffffff812dabc4: alloc_trace_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct trace_uprobe *alloc_trace_uprobe(const char *group, const char *event, int nargs, bool is_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff812f8d00)
Location: kernel/trace/trace_uprobe.c:331
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:__trace_uprobe_create
```
**Symbols:**

```
ffffffff812f8d00-ffffffff812f8e14: alloc_trace_uprobe (STB_LOCAL)
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
struct trace_uprobe *alloc_trace_uprobe(const char *group, const char *event, int nargs, bool is_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffff800010258b90)
Location: kernel/trace/trace_uprobe.c:338
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffff800010258b90-ffff800010258c64: alloc_trace_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct trace_uprobe *alloc_trace_uprobe(const char *group, const char *event, int nargs, bool is_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (c048c260)
Location: kernel/trace/trace_uprobe.c:338
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
c048c260-c048c314: alloc_trace_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct trace_uprobe *alloc_trace_uprobe(const char *group, const char *event, int nargs, bool is_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (c0000000002fc3a0)
Location: kernel/trace/trace_uprobe.c:338
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
c0000000002fc3a0-c0000000002fc4f4: alloc_trace_uprobe (STB_LOCAL)
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
struct trace_uprobe *alloc_trace_uprobe(const char *group, const char *event, int nargs, bool is_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811d1750)
Location: kernel/trace/trace_uprobe.c:338
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811d1750-ffffffff811d1839: alloc_trace_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct trace_uprobe *alloc_trace_uprobe(const char *group, const char *event, int nargs, bool is_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811c4520)
Location: kernel/trace/trace_uprobe.c:338
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811c4520-ffffffff811c4609: alloc_trace_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct trace_uprobe *alloc_trace_uprobe(const char *group, const char *event, int nargs, bool is_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811cf520)
Location: kernel/trace/trace_uprobe.c:338
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811cf520-ffffffff811cf609: alloc_trace_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct trace_uprobe *alloc_trace_uprobe(const char *group, const char *event, int nargs, bool is_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_uprobe.c (ffffffff811dd7c0)
Location: kernel/trace/trace_uprobe.c:338
Inline: False
Direct callers:
  - kernel/trace/trace_uprobe.c:create_local_trace_uprobe
  - kernel/trace/trace_uprobe.c:trace_uprobe_create
```
**Symbols:**

```
ffffffff811dd7c0-ffffffff811dd8a9: alloc_trace_uprobe (STB_LOCAL)
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
