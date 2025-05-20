# Function: <code>bpf_get_task_stack</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_get_task_stack(u64 task, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81233ea0)
Location: kernel/bpf/stackmap.c:652
Inline: False
```
**Symbols:**

```
ffffffff81233ea0-ffffffff81233ecc: bpf_get_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_get_task_stack(u64 task, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81237c60)
Location: kernel/bpf/stackmap.c:517
Inline: False
```
**Symbols:**

```
ffffffff81237c60-ffffffff81237d01: bpf_get_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_get_task_stack(u64 task, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81272230)
Location: kernel/bpf/stackmap.c:524
Inline: False
```
**Symbols:**

```
ffffffff81272230-ffffffff812722d3: bpf_get_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_get_task_stack(u64 task, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff812c1560)
Location: kernel/bpf/stackmap.c:471
Inline: False
```
**Symbols:**

```
ffffffff812c1560-ffffffff812c1646: bpf_get_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_get_task_stack(u64 task, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff81324e60)
Location: kernel/bpf/stackmap.c:471
Inline: False
```
**Symbols:**

```
ffffffff81324e60-ffffffff81324f46: bpf_get_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_get_task_stack(u64 task, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff813550c0)
Location: kernel/bpf/stackmap.c:468
Inline: False
```
**Symbols:**

```
ffffffff813550c0-ffffffff8135519e: bpf_get_task_stack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_get_task_stack(u64 task, u64 buf, u64 size, u64 flags, u64 __ur_1);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/stackmap.c (ffffffff8137da90)
Location: kernel/bpf/stackmap.c:477
Inline: False
```
**Symbols:**

```
ffffffff8137da90-ffffffff8137db6e: bpf_get_task_stack (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
