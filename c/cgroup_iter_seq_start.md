# Function: <code>cgroup_iter_seq_start</code>

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
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *cgroup_iter_seq_start(struct seq_file *seq, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup_iter.c (0)
Location: kernel/bpf/cgroup_iter.c:57
Inline: False
```
**Symbols:**

```
ffffffff81325270-ffffffff81325302: cgroup_iter_seq_start (STB_LOCAL)
ffffffff82061c07-ffffffff82061c1b: cgroup_iter_seq_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *cgroup_iter_seq_start(struct seq_file *seq, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup_iter.c (0)
Location: kernel/bpf/cgroup_iter.c:57
Inline: False
```
**Symbols:**

```
ffffffff813554c0-ffffffff8135554d: cgroup_iter_seq_start (STB_LOCAL)
ffffffff820e134c-ffffffff820e1360: cgroup_iter_seq_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *cgroup_iter_seq_start(struct seq_file *seq, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/cgroup_iter.c (0)
Location: kernel/bpf/cgroup_iter.c:57
Inline: False
```
**Symbols:**

```
ffffffff8137de90-ffffffff8137df1d: cgroup_iter_seq_start (STB_LOCAL)
ffffffff821bdd5b-ffffffff821bdd6f: cgroup_iter_seq_start.cold (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
