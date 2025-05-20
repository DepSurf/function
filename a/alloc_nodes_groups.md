# Function: <code>alloc_nodes_groups</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void alloc_nodes_groups(unsigned int numgrps, cpumask_var_t *node_to_cpumask, const struct cpumask *cpu_mask, const nodemask_t nodemsk, struct cpumask *nmsk, struct node_groups *node_groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/group_cpus.c (ffffffff818e6b00)
Location: lib/group_cpus.c:130
Inline: False
Direct callers:
  - lib/group_cpus.c:__group_cpus_evenly
```
**Symbols:**

```
ffffffff818e6b00-ffffffff818e6c76: alloc_nodes_groups (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void alloc_nodes_groups(unsigned int numgrps, cpumask_var_t *node_to_cpumask, const struct cpumask *cpu_mask, const nodemask_t nodemsk, struct cpumask *nmsk, struct node_groups *node_groups);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/group_cpus.c (ffffffff8192db20)
Location: lib/group_cpus.c:130
Inline: False
Direct callers:
  - lib/group_cpus.c:__group_cpus_evenly
```
**Symbols:**

```
ffffffff8192db20-ffffffff8192dc96: alloc_nodes_groups (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
