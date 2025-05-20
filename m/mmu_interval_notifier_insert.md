# Function: <code>mmu_interval_notifier_insert</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int mmu_interval_notifier_insert(struct mmu_interval_notifier *interval_sub, struct mm_struct *mm, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812d24f0)
Location: mm/mmu_notifier.c:978
Inline: False
```
**Symbols:**

```
ffffffff812d24f0-ffffffff812d258e: mmu_interval_notifier_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mmu_interval_notifier_insert(struct mmu_interval_notifier *interval_sub, struct mm_struct *mm, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812ddf50)
Location: mm/mmu_notifier.c:995
Inline: False
```
**Symbols:**

```
ffffffff812ddf50-ffffffff812ddfba: mmu_interval_notifier_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mmu_interval_notifier_insert(struct mmu_interval_notifier *interval_sub, struct mm_struct *mm, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812e5500)
Location: mm/mmu_notifier.c:995
Inline: False
```
**Symbols:**

```
ffffffff812e5500-ffffffff812e556a: mmu_interval_notifier_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mmu_interval_notifier_insert(struct mmu_interval_notifier *interval_sub, struct mm_struct *mm, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:995
Inline: False
```
**Symbols:**

```
ffffffff81cc07f3-ffffffff81cc0816: mmu_interval_notifier_insert.cold (STB_LOCAL)
ffffffff8132d0e0-ffffffff8132d15c: mmu_interval_notifier_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mmu_interval_notifier_insert(struct mmu_interval_notifier *interval_sub, struct mm_struct *mm, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:995
Inline: False
```
**Symbols:**

```
ffffffff81e72cb4-ffffffff81e72cd7: mmu_interval_notifier_insert.cold (STB_LOCAL)
ffffffff8139d3a0-ffffffff8139d42d: mmu_interval_notifier_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mmu_interval_notifier_insert(struct mmu_interval_notifier *interval_sub, struct mm_struct *mm, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:995
Inline: False
```
**Symbols:**

```
ffffffff82067265-ffffffff82067288: mmu_interval_notifier_insert.cold (STB_LOCAL)
ffffffff8141c830-ffffffff8141c8bd: mmu_interval_notifier_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mmu_interval_notifier_insert(struct mmu_interval_notifier *interval_sub, struct mm_struct *mm, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:995
Inline: False
```
**Symbols:**

```
ffffffff820e6b27-ffffffff820e6b4a: mmu_interval_notifier_insert.cold (STB_LOCAL)
ffffffff8144fdf0-ffffffff8144fe7d: mmu_interval_notifier_insert (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mmu_interval_notifier_insert(struct mmu_interval_notifier *interval_sub, struct mm_struct *mm, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:987
Inline: False
```
**Symbols:**

```
ffffffff821c3c09-ffffffff821c3c2c: mmu_interval_notifier_insert.cold (STB_LOCAL)
ffffffff81489b20-ffffffff81489bad: mmu_interval_notifier_insert (STB_GLOBAL)
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
