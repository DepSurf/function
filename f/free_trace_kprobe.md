# Function: <code>free_trace_kprobe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81167ba0)
Location: kernel/trace/trace_kprobe.c:320
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:probes_open
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
**Symbols:**

```
ffffffff81167ba0-ffffffff81167c0e: free_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811751c0)
Location: kernel/trace/trace_kprobe.c:325
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:probes_open
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
**Symbols:**

```
ffffffff811751c0-ffffffff8117523b: free_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81180bb0)
Location: kernel/trace/trace_kprobe.c:340
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:probes_open
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
**Symbols:**

```
ffffffff81180bb0-ffffffff81180c2b: free_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811839c0)
Location: kernel/trace/trace_kprobe.c:346
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:probes_open
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
**Symbols:**

```
ffffffff811839c0-ffffffff81183a3b: free_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff81191710)
Location: kernel/trace/trace_kprobe.c:346
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:probes_open
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
**Symbols:**

```
ffffffff81191710-ffffffff8119178b: free_trace_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_trace_kprobe(struct trace_kprobe *tk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811a7090)
Location: kernel/trace/trace_kprobe.c:370
Inline: False
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:probes_open
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_trace_kprobe
```
**Symbols:**

```
ffffffff811a7090-ffffffff811a710b: free_trace_kprobe (STB_LOCAL)
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
In kernel/trace/trace_kprobe.c (ffffffff811b6fdf)
Location: kernel/trace/trace_kprobe.c:254
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
```
**Symbols:**

```
ffffffff811b4b10-ffffffff811b4b92: free_trace_kprobe.part.10 (STB_LOCAL)
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
In kernel/trace/trace_kprobe.c (ffffffff811c604f)
Location: kernel/trace/trace_kprobe.c:206
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
**Symbols:**

```
ffffffff811c3ba0-ffffffff811c3bdb: free_trace_kprobe.part.0 (STB_LOCAL)
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
In kernel/trace/trace_kprobe.c (ffffffff811d1db5)
Location: kernel/trace/trace_kprobe.c:243
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
**Symbols:**

```
ffffffff811cf690-ffffffff811cf6cb: free_trace_kprobe.part.0 (STB_LOCAL)
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
In kernel/trace/trace_kprobe.c (ffffffff811ee7a7)
Location: kernel/trace/trace_kprobe.c:242
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
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
In kernel/trace/trace_kprobe.c (ffffffff811ec9f7)
Location: kernel/trace/trace_kprobe.c:244
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
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
In kernel/trace/trace_kprobe.c (ffffffff811ed757)
Location: kernel/trace/trace_kprobe.c:244
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
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
In kernel/trace/trace_kprobe.c (ffffffff8121e7c7)
Location: kernel/trace/trace_kprobe.c:240
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
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
In kernel/trace/trace_kprobe.c (ffffffff8125de2f)
Location: kernel/trace/trace_kprobe.c:241
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
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
In kernel/trace/trace_kprobe.c (ffffffff812ae8ef)
Location: kernel/trace/trace_kprobe.c:243
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
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
In kernel/trace/trace_kprobe.c (ffffffff812d0e07)
Location: kernel/trace/trace_kprobe.c:243
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
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
In kernel/trace/trace_kprobe.c (ffffffff812ee907)
Location: kernel/trace/trace_kprobe.c:243
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:__trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
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
In kernel/trace/trace_kprobe.c (ffff800010251f8c)
Location: kernel/trace/trace_kprobe.c:243
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
**Symbols:**

```
ffff80001024fe50-ffff80001024fe8c: free_trace_kprobe.part.0 (STB_LOCAL)
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
In kernel/trace/trace_kprobe.c (c0484e70)
Location: kernel/trace/trace_kprobe.c:243
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
**Symbols:**

```
c0482cec-c0482d20: free_trace_kprobe.part.0 (STB_LOCAL)
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
In kernel/trace/trace_kprobe.c (c0000000002f0480)
Location: kernel/trace/trace_kprobe.c:243
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
**Symbols:**

```
c0000000002ed9e0-c0000000002eda40: free_trace_kprobe.part.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/trace_kprobe.c (ffffffff811ca3d5)
Location: kernel/trace/trace_kprobe.c:243
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
**Symbols:**

```
ffffffff811c7cb0-ffffffff811c7ceb: free_trace_kprobe.part.0 (STB_LOCAL)
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
In kernel/trace/trace_kprobe.c (ffffffff811bd1a5)
Location: kernel/trace/trace_kprobe.c:243
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
**Symbols:**

```
ffffffff811baa90-ffffffff811baacb: free_trace_kprobe.part.0 (STB_LOCAL)
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
In kernel/trace/trace_kprobe.c (ffffffff811c81a5)
Location: kernel/trace/trace_kprobe.c:243
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
**Symbols:**

```
ffffffff811c5a80-ffffffff811c5abb: free_trace_kprobe.part.0 (STB_LOCAL)
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
In kernel/trace/trace_kprobe.c (ffffffff811d6405)
Location: kernel/trace/trace_kprobe.c:243
Inline: True
Inline callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
Direct callers:
  - kernel/trace/trace_kprobe.c:destroy_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:create_local_trace_kprobe
  - kernel/trace/trace_kprobe.c:trace_kprobe_create
  - kernel/trace/trace_kprobe.c:alloc_trace_kprobe
```
**Symbols:**

```
ffffffff811d3ce0-ffffffff811d3d1b: free_trace_kprobe.part.0 (STB_LOCAL)
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
</ul>
