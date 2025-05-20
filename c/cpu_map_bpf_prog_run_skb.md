# Function: <code>cpu_map_bpf_prog_run_skb</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cpu_map_bpf_prog_run_skb(struct bpf_cpu_map_entry *rcpu, struct list_head *listp, struct xdp_cpumap_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff8126d100)
Location: kernel/bpf/cpumap.c:172
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffffffff8126d100-ffffffff8126d24b: cpu_map_bpf_prog_run_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cpu_map_bpf_prog_run_skb(struct bpf_cpu_map_entry *rcpu, struct list_head *listp, struct xdp_cpumap_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff812bc200)
Location: kernel/bpf/cpumap.c:173
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffffffff812bc200-ffffffff812bc388: cpu_map_bpf_prog_run_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cpu_map_bpf_prog_run_skb(struct bpf_cpu_map_entry *rcpu, struct list_head *listp, struct xdp_cpumap_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff8131f5f0)
Location: kernel/bpf/cpumap.c:172
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffffffff8131f5f0-ffffffff8131f778: cpu_map_bpf_prog_run_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cpu_map_bpf_prog_run_skb(struct bpf_cpu_map_entry *rcpu, struct list_head *listp, struct xdp_cpumap_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff8134f450)
Location: kernel/bpf/cpumap.c:176
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffffffff8134f450-ffffffff8134f5dc: cpu_map_bpf_prog_run_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cpu_map_bpf_prog_run_skb(struct bpf_cpu_map_entry *rcpu, struct list_head *listp, struct xdp_cpumap_stats *stats);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/cpumap.c (ffffffff81376ac0)
Location: kernel/bpf/cpumap.c:137
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffffffff81376ac0-ffffffff81376c4c: cpu_map_bpf_prog_run_skb (STB_LOCAL)
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
