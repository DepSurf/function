# Function: <code>mmu_interval_notifier_insert_locked</code>

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
int mmu_interval_notifier_insert_locked(struct mmu_interval_notifier *interval_sub, struct mm_struct *mm, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812d2430)
Location: mm/mmu_notifier.c:1000
Inline: False
```
**Symbols:**

```
ffffffff812d2430-ffffffff812d249a: mmu_interval_notifier_insert_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mmu_interval_notifier_insert_locked(struct mmu_interval_notifier *interval_sub, struct mm_struct *mm, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812dde50)
Location: mm/mmu_notifier.c:1017
Inline: False
```
**Symbols:**

```
ffffffff812dde50-ffffffff812ddeba: mmu_interval_notifier_insert_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mmu_interval_notifier_insert_locked(struct mmu_interval_notifier *interval_sub, struct mm_struct *mm, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812e5400)
Location: mm/mmu_notifier.c:1017
Inline: False
```
**Symbols:**

```
ffffffff812e5400-ffffffff812e546a: mmu_interval_notifier_insert_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mmu_interval_notifier_insert_locked(struct mmu_interval_notifier *interval_sub, struct mm_struct *mm, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:1017
Inline: False
```
**Symbols:**

```
ffffffff81cc0816-ffffffff81cc0839: mmu_interval_notifier_insert_locked.cold (STB_LOCAL)
ffffffff8132d160-ffffffff8132d1dc: mmu_interval_notifier_insert_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mmu_interval_notifier_insert_locked(struct mmu_interval_notifier *interval_sub, struct mm_struct *mm, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:1017
Inline: False
```
**Symbols:**

```
ffffffff81e72c91-ffffffff81e72cb4: mmu_interval_notifier_insert_locked.cold (STB_LOCAL)
ffffffff8139d280-ffffffff8139d30d: mmu_interval_notifier_insert_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mmu_interval_notifier_insert_locked(struct mmu_interval_notifier *interval_sub, struct mm_struct *mm, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:1017
Inline: False
```
**Symbols:**

```
ffffffff82067242-ffffffff82067265: mmu_interval_notifier_insert_locked.cold (STB_LOCAL)
ffffffff8141c6f0-ffffffff8141c77d: mmu_interval_notifier_insert_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mmu_interval_notifier_insert_locked(struct mmu_interval_notifier *interval_sub, struct mm_struct *mm, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:1017
Inline: False
```
**Symbols:**

```
ffffffff820e6b04-ffffffff820e6b27: mmu_interval_notifier_insert_locked.cold (STB_LOCAL)
ffffffff8144fca0-ffffffff8144fd2d: mmu_interval_notifier_insert_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mmu_interval_notifier_insert_locked(struct mmu_interval_notifier *interval_sub, struct mm_struct *mm, long unsigned int start, long unsigned int length, const struct mmu_interval_notifier_ops *ops);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/mmu_notifier.c (0)
Location: mm/mmu_notifier.c:1009
Inline: False
```
**Symbols:**

```
ffffffff821c3be6-ffffffff821c3c09: mmu_interval_notifier_insert_locked.cold (STB_LOCAL)
ffffffff814899d0-ffffffff81489a5d: mmu_interval_notifier_insert_locked (STB_GLOBAL)
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
