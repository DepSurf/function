# Function: <code>mn_hlist_release</code>

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
void mn_hlist_release(struct mmu_notifier_subscriptions *subscriptions, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812d1a50)
Location: mm/mmu_notifier.c:299
Inline: False
Direct callers:
  - mm/mmu_notifier.c:__mmu_notifier_release
```
**Symbols:**

```
ffffffff812d1a50-ffffffff812d1b13: mn_hlist_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mn_hlist_release(struct mmu_notifier_subscriptions *subscriptions, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812dd450)
Location: mm/mmu_notifier.c:299
Inline: False
Direct callers:
  - mm/mmu_notifier.c:__mmu_notifier_release
```
**Symbols:**

```
ffffffff812dd450-ffffffff812dd513: mn_hlist_release (STB_LOCAL)
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
In mm/mmu_notifier.c (ffffffff812e55b6)
Location: mm/mmu_notifier.c:299
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_release
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
In mm/mmu_notifier.c (ffffffff8132d3e2)
Location: mm/mmu_notifier.c:299
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_release
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
In mm/mmu_notifier.c (ffffffff8139d5bf)
Location: mm/mmu_notifier.c:299
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_release
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
In mm/mmu_notifier.c (ffffffff8141ca7f)
Location: mm/mmu_notifier.c:299
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_release
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
In mm/mmu_notifier.c (ffffffff8145003f)
Location: mm/mmu_notifier.c:299
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_release
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
In mm/mmu_notifier.c (ffffffff81489d6f)
Location: mm/mmu_notifier.c:299
Inline: True
Inline callers:
  - mm/mmu_notifier.c:__mmu_notifier_release
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
