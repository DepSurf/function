# Function: <code>free_trace_buffers</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_trace_buffers(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8114cdc0)
Location: kernel/trace/trace.c:6586
Inline: False
Direct callers:
  - kernel/trace/trace.c:instance_rmdir
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff8114cdc0-ffffffff8114ce1f: free_trace_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_trace_buffers(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81155700)
Location: kernel/trace/trace.c:6986
Inline: False
Direct callers:
  - kernel/trace/trace.c:instance_rmdir
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff81155700-ffffffff8115575f: free_trace_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_trace_buffers(struct trace_array *tr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8115fbd0)
Location: kernel/trace/trace.c:7269
Inline: False
Direct callers:
  - kernel/trace/trace.c:instance_rmdir
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff8115fbd0-ffffffff8115fc2f: free_trace_buffers (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811690dd)
Location: kernel/trace/trace.c:7633
Inline: True
Inline callers:
  - kernel/trace/trace.c:instance_rmdir
  - kernel/trace/trace.c:instance_mkdir
Direct callers:
  - kernel/trace/trace.c:instance_rmdir
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff81163070-ffffffff811630c9: free_trace_buffers.part.44 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81176098)
Location: kernel/trace/trace.c:7639
Inline: True
Inline callers:
  - kernel/trace/trace.c:instance_rmdir
  - kernel/trace/trace.c:instance_mkdir
Direct callers:
  - kernel/trace/trace.c:instance_rmdir
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff81170030-ffffffff81170089: free_trace_buffers.part.43 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81185028)
Location: kernel/trace/trace.c:7729
Inline: True
Inline callers:
  - kernel/trace/trace.c:instance_rmdir
  - kernel/trace/trace.c:instance_mkdir
Direct callers:
  - kernel/trace/trace.c:instance_rmdir
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff8117f0f0-ffffffff8117f149: free_trace_buffers.part.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff81192958)
Location: kernel/trace/trace.c:7798
Inline: True
Inline callers:
  - kernel/trace/trace.c:instance_rmdir
  - kernel/trace/trace.c:instance_mkdir
Direct callers:
  - kernel/trace/trace.c:instance_rmdir
  - kernel/trace/trace.c:instance_mkdir
```
**Symbols:**

```
ffffffff8118c9e0-ffffffff8118ca39: free_trace_buffers.part.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a14b8)
Location: kernel/trace/trace.c:8283
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff8119a2b0-ffffffff8119a309: free_trace_buffers.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811acefa)
Location: kernel/trace/trace.c:8334
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811a5b60-ffffffff811a5bb9: free_trace_buffers.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811beee5)
Location: kernel/trace/trace.c:8538
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:trace_array_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bcb6d)
Location: kernel/trace/trace.c:8612
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:trace_array_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bc66d)
Location: kernel/trace/trace.c:8948
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:trace_array_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e70ce)
Location: kernel/trace/trace.c:9112
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:trace_array_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8121f04c)
Location: kernel/trace/trace.c:9144
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:trace_array_create
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81269a81)
Location: kernel/trace/trace.c:9235
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:trace_array_create
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81280c0f)
Location: kernel/trace/trace.c:9394
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
  - kernel/trace/trace.c:trace_array_create
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129ae33)
Location: kernel/trace/trace.c:9573
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create_systems
  - kernel/trace/trace.c:trace_array_create_systems
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffff800010229ed4)
Location: kernel/trace/trace.c:8334
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffff800010220b70-ffff800010220bc4: free_trace_buffers.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (c046755c)
Location: kernel/trace/trace.c:8334
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
c045e938-c045e994: free_trace_buffers.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (c0000000002b1964)
Location: kernel/trace/trace.c:8334
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
c0000000002a4eb0-c0000000002a4f40: free_trace_buffers.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffe00018454c)
Location: kernel/trace/trace.c:8334
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffe00017d7a0-ffffffe00017d7f2: free_trace_buffers.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a551a)
Location: kernel/trace/trace.c:8334
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff8119e180-ffffffff8119e1d9: free_trace_buffers.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811984ca)
Location: kernel/trace/trace.c:8334
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811911e0-ffffffff81191239: free_trace_buffers.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a32ea)
Location: kernel/trace/trace.c:8334
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff8119bf50-ffffffff8119bfa9: free_trace_buffers.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b107a)
Location: kernel/trace/trace.c:8334
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_array_create
Direct callers:
  - kernel/trace/trace.c:trace_array_create
```
**Symbols:**

```
ffffffff811a9bf0-ffffffff811a9c49: free_trace_buffers.part.0 (STB_LOCAL)
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
</ul>
