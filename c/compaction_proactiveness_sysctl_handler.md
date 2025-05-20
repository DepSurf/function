# Function: <code>compaction_proactiveness_sysctl_handler</code>

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
int compaction_proactiveness_sysctl_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2703
Inline: False
```
**Symbols:**

```
ffffffff81cbbc55-ffffffff81cbbc6a: compaction_proactiveness_sysctl_handler.cold (STB_LOCAL)
ffffffff812d4720-ffffffff812d47ea: compaction_proactiveness_sysctl_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int compaction_proactiveness_sysctl_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2723
Inline: False
```
**Symbols:**

```
ffffffff81e6d820-ffffffff81e6d835: compaction_proactiveness_sysctl_handler.cold (STB_LOCAL)
ffffffff81333710-ffffffff813337fe: compaction_proactiveness_sysctl_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int compaction_proactiveness_sysctl_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2722
Inline: False
```
**Symbols:**

```
ffffffff82063b60-ffffffff82063b75: compaction_proactiveness_sysctl_handler.cold (STB_LOCAL)
ffffffff813aa420-ffffffff813aa500: compaction_proactiveness_sysctl_handler (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int compaction_proactiveness_sysctl_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/compaction.c (ffffffff813d90c7)
Location: mm/compaction.c:2799
Inline: True
```
**Symbols:**

```
ffffffff813d9080-ffffffff813d91be: compaction_proactiveness_sysctl_handler (STB_LOCAL)
ffffffff820e2cc1-ffffffff820e2cd6: compaction_proactiveness_sysctl_handler.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int compaction_proactiveness_sysctl_handler(struct ctl_table *table, int write, void *buffer, size_t *length, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/compaction.c (ffffffff81402e47)
Location: mm/compaction.c:2862
Inline: True
```
**Symbols:**

```
ffffffff81402e00-ffffffff81402f3e: compaction_proactiveness_sysctl_handler (STB_LOCAL)
ffffffff821bf604-ffffffff821bf619: compaction_proactiveness_sysctl_handler.cold (STB_LOCAL)
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
