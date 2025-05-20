# Function: <code>filter_irq_stacks</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int filter_irq_stacks(long unsigned int *entries, unsigned int nr_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811948f0)
Location: kernel/stacktrace.c:390
Inline: False
Direct callers:
  - mm/kfence/core.c:__kfence_alloc
  - lib/stackdepot.c:__stack_depot_save
```
**Symbols:**

```
ffffffff811948f0-ffffffff81194963: filter_irq_stacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int filter_irq_stacks(long unsigned int *entries, unsigned int nr_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811d2540)
Location: kernel/stacktrace.c:390
Inline: False
Direct callers:
  - mm/kfence/core.c:__kfence_alloc
  - lib/stackdepot.c:__stack_depot_save
```
**Symbols:**

```
ffffffff811d2540-ffffffff811d25b3: filter_irq_stacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int filter_irq_stacks(long unsigned int *entries, unsigned int nr_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811e6830)
Location: kernel/stacktrace.c:390
Inline: False
Direct callers:
  - mm/kfence/core.c:__kfence_alloc
  - lib/stackdepot.c:__stack_depot_save
```
**Symbols:**

```
ffffffff811e6830-ffffffff811e68a3: filter_irq_stacks (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int filter_irq_stacks(long unsigned int *entries, unsigned int nr_entries);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/stacktrace.c (ffffffff811fc580)
Location: kernel/stacktrace.c:392
Inline: False
Direct callers:
  - mm/kfence/core.c:__kfence_alloc
  - lib/stackdepot.c:stack_depot_save_flags
```
**Symbols:**

```
ffffffff811fc580-ffffffff811fc5f3: filter_irq_stacks (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
