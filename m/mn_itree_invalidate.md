# Function: <code>mn_itree_invalidate</code>

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
int mn_itree_invalidate(struct mmu_notifier_subscriptions *subscriptions, const struct mmu_notifier_range *range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812d1f90)
Location: mm/mmu_notifier.c:444
Inline: False
Direct callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
```
**Symbols:**

```
ffffffff812d1f90-ffffffff812d204b: mn_itree_invalidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mn_itree_invalidate(struct mmu_notifier_subscriptions *subscriptions, const struct mmu_notifier_range *range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812dd9b0)
Location: mm/mmu_notifier.c:444
Inline: False
Direct callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
```
**Symbols:**

```
ffffffff812dd9b0-ffffffff812dda6b: mn_itree_invalidate (STB_LOCAL)
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
In mm/mmu_notifier.c (ffffffff812e5a06)
Location: mm/mmu_notifier.c:444
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
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
In mm/mmu_notifier.c (ffffffff8132d8de)
Location: mm/mmu_notifier.c:444
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
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
In mm/mmu_notifier.c (ffffffff8139dae3)
Location: mm/mmu_notifier.c:444
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8141d03f)
Location: mm/mmu_notifier.c:444
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff814505fe)
Location: mm/mmu_notifier.c:444
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8148a32e)
Location: mm/mmu_notifier.c:444
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
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
</ul>
