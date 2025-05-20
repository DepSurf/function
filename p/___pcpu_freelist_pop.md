# Function: <code>___pcpu_freelist_pop</code>

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
struct pcpu_freelist_node *___pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff8121dc20)
Location: kernel/bpf/percpu_freelist.c:124
Inline: False
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
```
**Symbols:**

```
ffffffff8121dc20-ffffffff8121dceb: ___pcpu_freelist_pop (STB_LOCAL)
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
In kernel/bpf/percpu_freelist.c (ffffffff81221a07)
Location: kernel/bpf/percpu_freelist.c:124
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
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
In kernel/bpf/percpu_freelist.c (ffffffff812594a7)
Location: kernel/bpf/percpu_freelist.c:124
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
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
In kernel/bpf/percpu_freelist.c (ffffffff812a241b)
Location: kernel/bpf/percpu_freelist.c:124
Inline: True
Inline callers:
  - kernel/bpf/percpu_freelist.c:__pcpu_freelist_pop
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pcpu_freelist_node *___pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff812ff770)
Location: kernel/bpf/percpu_freelist.c:121
Inline: False
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
```
**Symbols:**

```
ffffffff812ff770-ffffffff812ff92d: ___pcpu_freelist_pop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pcpu_freelist_node *___pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff8132e2d0)
Location: kernel/bpf/percpu_freelist.c:121
Inline: False
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
```
**Symbols:**

```
ffffffff8132e2d0-ffffffff8132e48d: ___pcpu_freelist_pop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pcpu_freelist_node *___pcpu_freelist_pop(struct pcpu_freelist *s);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/percpu_freelist.c (ffffffff813527f0)
Location: kernel/bpf/percpu_freelist.c:121
Inline: False
Direct callers:
  - kernel/bpf/percpu_freelist.c:pcpu_freelist_pop
```
**Symbols:**

```
ffffffff813527f0-ffffffff813529ad: ___pcpu_freelist_pop (STB_LOCAL)
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
