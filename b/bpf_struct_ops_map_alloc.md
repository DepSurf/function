# Function: <code>bpf_struct_ops_map_alloc</code>

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
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bpf_map *bpf_struct_ops_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff8122fba0)
Location: kernel/bpf/bpf_struct_ops.c:550
Inline: True
```
**Symbols:**

```
ffffffff8122fba0-ffffffff8122fd93: bpf_struct_ops_map_alloc.part.0 (STB_LOCAL)
ffffffff8122fda0-ffffffff8122fde5: bpf_struct_ops_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct bpf_map *bpf_struct_ops_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff812380b0)
Location: kernel/bpf/bpf_struct_ops.c:548
Inline: True
```
**Symbols:**

```
ffffffff812380b0-ffffffff8123824d: bpf_struct_ops_map_alloc.part.0 (STB_LOCAL)
ffffffff81238250-ffffffff81238295: bpf_struct_ops_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *bpf_struct_ops_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff8123c8b0)
Location: kernel/bpf/bpf_struct_ops.c:548
Inline: True
```
**Symbols:**

```
ffffffff8123c8b0-ffffffff8123ca84: bpf_struct_ops_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *bpf_struct_ops_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff81277300)
Location: kernel/bpf/bpf_struct_ops.c:552
Inline: True
```
**Symbols:**

```
ffffffff81277300-ffffffff812774d4: bpf_struct_ops_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *bpf_struct_ops_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff812c6e90)
Location: kernel/bpf/bpf_struct_ops.c:592
Inline: True
```
**Symbols:**

```
ffffffff812c6e90-ffffffff812c704e: bpf_struct_ops_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct bpf_map *bpf_struct_ops_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff8132c700)
Location: kernel/bpf/bpf_struct_ops.c:593
Inline: True
```
**Symbols:**

```
ffffffff8132c700-ffffffff8132c8be: bpf_struct_ops_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct bpf_map *bpf_struct_ops_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff8135c270)
Location: kernel/bpf/bpf_struct_ops.c:650
Inline: False
```
**Symbols:**

```
ffffffff8135c270-ffffffff8135c43b: bpf_struct_ops_map_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct bpf_map *bpf_struct_ops_map_alloc(union bpf_attr *attr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_struct_ops.c (ffffffff81385020)
Location: kernel/bpf/bpf_struct_ops.c:662
Inline: False
```
**Symbols:**

```
ffffffff81385020-ffffffff81385198: bpf_struct_ops_map_alloc (STB_LOCAL)
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
