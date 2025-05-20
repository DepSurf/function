# Function: <code>mn_hlist_invalidate_range_start</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mn_hlist_invalidate_range_start(struct mmu_notifier_subscriptions *subscriptions, struct mmu_notifier_range *range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:475
Inline: False
Direct callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
```
**Symbols:**

```
ffffffff812d18f0-ffffffff812d197e: mn_hlist_invalidate_range_start (STB_LOCAL)
ffffffff812d2a3a-ffffffff812d2a8d: mn_hlist_invalidate_range_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mn_hlist_invalidate_range_start(struct mmu_notifier_subscriptions *subscriptions, struct mmu_notifier_range *range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:475
Inline: False
Direct callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
```
**Symbols:**

```
ffffffff812dd2b0-ffffffff812dd374: mn_hlist_invalidate_range_start (STB_LOCAL)
ffffffff81be8c3f-ffffffff81be8c93: mn_hlist_invalidate_range_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mn_hlist_invalidate_range_start(struct mmu_notifier_subscriptions *subscriptions, struct mmu_notifier_range *range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:475
Inline: False
Direct callers:
  - mm/mmu_notifier.c:__mmu_notifier_invalidate_range_start
```
**Symbols:**

```
ffffffff812e4b00-ffffffff812e4bc4: mn_hlist_invalidate_range_start (STB_LOCAL)
ffffffff81bdad8e-ffffffff81bdade2: mn_hlist_invalidate_range_start.cold (STB_LOCAL)
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
In mm/mmu_notifier.c (ffffffff8132d84a)
Location: mm/mmu_notifier.c:475
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
In mm/mmu_notifier.c (ffffffff8139da55)
Location: mm/mmu_notifier.c:475
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
In mm/mmu_notifier.c (ffffffff8141cf68)
Location: mm/mmu_notifier.c:475
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
In mm/mmu_notifier.c (ffffffff81450527)
Location: mm/mmu_notifier.c:475
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
In mm/mmu_notifier.c (ffffffff8148a257)
Location: mm/mmu_notifier.c:475
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
