# Function: <code>pcpu_reclaim_populated</code>

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
void pcpu_reclaim_populated();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:2135
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
```
**Symbols:**

```
ffffffff812ca270-ffffffff812ca521: pcpu_reclaim_populated (STB_LOCAL)
ffffffff81cbb09c-ffffffff81cbb0c4: pcpu_reclaim_populated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void pcpu_reclaim_populated();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:2133
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
```
**Symbols:**

```
ffffffff81326be0-ffffffff81326eb3: pcpu_reclaim_populated (STB_LOCAL)
ffffffff81e6cbb4-ffffffff81e6cbdc: pcpu_reclaim_populated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void pcpu_reclaim_populated();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:2126
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
```
**Symbols:**

```
ffffffff8139b890-ffffffff8139bb63: pcpu_reclaim_populated (STB_LOCAL)
ffffffff82063054-ffffffff8206307c: pcpu_reclaim_populated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void pcpu_reclaim_populated();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:2126
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
```
**Symbols:**

```
ffffffff813ce870-ffffffff813ceb43: pcpu_reclaim_populated (STB_LOCAL)
ffffffff820e28f1-ffffffff820e2919: pcpu_reclaim_populated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void pcpu_reclaim_populated();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/percpu.c (0)
Location: mm/percpu.c:2126
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_balance_workfn
```
**Symbols:**

```
ffffffff813f93d0-ffffffff813f96a3: pcpu_reclaim_populated (STB_LOCAL)
ffffffff821bf2e2-ffffffff821bf30a: pcpu_reclaim_populated.cold (STB_LOCAL)
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
