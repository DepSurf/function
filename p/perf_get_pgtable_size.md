# Function: <code>perf_get_pgtable_size</code>

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
u64 perf_get_pgtable_size(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123ca00)
Location: kernel/events/core.c:7046
Inline: False
```
**Symbols:**

```
ffffffff8123ca00-ffffffff8123cc1b: perf_get_pgtable_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 perf_get_pgtable_size(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81243d40)
Location: kernel/events/core.c:7157
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff81243d40-ffffffff81243f25: perf_get_pgtable_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 perf_get_pgtable_size(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:7281
Inline: False
Direct callers:
  - kernel/events/core.c:perf_prepare_sample
  - kernel/events/core.c:perf_prepare_sample
```
**Symbols:**

```
ffffffff8127e6a0-ffffffff8127e895: perf_get_pgtable_size (STB_LOCAL)
ffffffff81cb98eb-ffffffff81cb9904: perf_get_pgtable_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
u64 perf_get_pgtable_size(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:7186
Inline: False
```
**Symbols:**

```
ffffffff812d3300-ffffffff812d3502: perf_get_pgtable_size (STB_LOCAL)
ffffffff81e6aeef-ffffffff81e6af08: perf_get_pgtable_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 perf_get_pgtable_size(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:7453
Inline: False
```
**Symbols:**

```
ffffffff8133b570-ffffffff8133b780: perf_get_pgtable_size (STB_LOCAL)
ffffffff82061de0-ffffffff82061df9: perf_get_pgtable_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 perf_get_pgtable_size(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:7462
Inline: False
```
**Symbols:**

```
ffffffff8136cf40-ffffffff8136d11d: perf_get_pgtable_size (STB_LOCAL)
ffffffff820e159a-ffffffff820e15b3: perf_get_pgtable_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 perf_get_pgtable_size(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/core.c (0)
Location: kernel/events/core.c:7543
Inline: False
```
**Symbols:**

```
ffffffff81396180-ffffffff8139636a: perf_get_pgtable_size (STB_LOCAL)
ffffffff821bdfd3-ffffffff821bdfec: perf_get_pgtable_size.cold (STB_LOCAL)
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
