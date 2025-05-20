# Function: <code>stats_show</code>

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
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int stats_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/kfence/core.c (0)
Location: mm/kfence/core.c:516
Inline: False
```
**Symbols:**

```
ffffffff8133bc60-ffffffff8133bd08: stats_show (STB_LOCAL)
ffffffff81cc1e4d-ffffffff81cc1e68: stats_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int stats_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/kfence/core.c (0)
Location: mm/kfence/core.c:673
Inline: False
```
**Symbols:**

```
ffffffff813ae600-ffffffff813ae6b4: stats_show (STB_LOCAL)
ffffffff81e74357-ffffffff81e74372: stats_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int stats_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/kfence/core.c (0)
Location: mm/kfence/core.c:672
Inline: False
```
**Symbols:**

```
ffffffff8142e9c0-ffffffff8142ea74: stats_show (STB_LOCAL)
ffffffff820678b7-ffffffff820678d2: stats_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int stats_show(struct seq_file *seq, void *v);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/kfence/core.c (0)
Location: mm/kfence/core.c:700
Inline: False
```
**Symbols:**

```
ffffffff81464100-ffffffff814641b4: stats_show (STB_LOCAL)
ffffffff820e71ac-ffffffff820e71c7: stats_show.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Transformation ⚠️</summary>

```c
int stats_show(struct seq_file *seq, void *v);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/kfence/core.c (0)
Location: mm/kfence/core.c:695
Inline: False
```
```
In lib/stackdepot.c (ffffffff81927f10)
Location: lib/stackdepot.c:824
Inline: False
```
**Symbols:**

```
ffffffff81493480-ffffffff81493534: stats_show (STB_LOCAL)
ffffffff821c3d64-ffffffff821c3d7f: stats_show.cold (STB_LOCAL)
ffffffff81927f10-ffffffff81927faf: stats_show (STB_LOCAL)
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
