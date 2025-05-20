# Function: <code>mmu_notifier_get_locked</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct mmu_notifier *mmu_notifier_get_locked(const struct mmu_notifier_ops *ops, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8129dc30)
Location: mm/mmu_notifier.c:382
Inline: False
Direct callers:
  - mm/hmm.c:hmm_mirror_register
```
**Symbols:**

```
ffffffff8129dc30-ffffffff8129dd0e: mmu_notifier_get_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct mmu_notifier *mmu_notifier_get_locked(const struct mmu_notifier_ops *ops, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812d2350)
Location: mm/mmu_notifier.c:758
Inline: False
```
**Symbols:**

```
ffffffff812d2350-ffffffff812d242e: mmu_notifier_get_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct mmu_notifier *mmu_notifier_get_locked(const struct mmu_notifier_ops *ops, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812ddd70)
Location: mm/mmu_notifier.c:774
Inline: False
```
**Symbols:**

```
ffffffff812ddd70-ffffffff812dde4e: mmu_notifier_get_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mmu_notifier *mmu_notifier_get_locked(const struct mmu_notifier_ops *ops, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812e5320)
Location: mm/mmu_notifier.c:774
Inline: False
```
**Symbols:**

```
ffffffff812e5320-ffffffff812e53fe: mmu_notifier_get_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mmu_notifier *mmu_notifier_get_locked(const struct mmu_notifier_ops *ops, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8132cf80)
Location: mm/mmu_notifier.c:774
Inline: False
```
**Symbols:**

```
ffffffff8132cf80-ffffffff8132d05e: mmu_notifier_get_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mmu_notifier *mmu_notifier_get_locked(const struct mmu_notifier_ops *ops, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8139d190)
Location: mm/mmu_notifier.c:774
Inline: False
```
**Symbols:**

```
ffffffff8139d190-ffffffff8139d27e: mmu_notifier_get_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mmu_notifier *mmu_notifier_get_locked(const struct mmu_notifier_ops *ops, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8141c5f0)
Location: mm/mmu_notifier.c:774
Inline: False
```
**Symbols:**

```
ffffffff8141c5f0-ffffffff8141c6de: mmu_notifier_get_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mmu_notifier *mmu_notifier_get_locked(const struct mmu_notifier_ops *ops, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8144fba0)
Location: mm/mmu_notifier.c:774
Inline: False
```
**Symbols:**

```
ffffffff8144fba0-ffffffff8144fc8e: mmu_notifier_get_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mmu_notifier *mmu_notifier_get_locked(const struct mmu_notifier_ops *ops, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff814898d0)
Location: mm/mmu_notifier.c:766
Inline: False
```
**Symbols:**

```
ffffffff814898d0-ffffffff814899be: mmu_notifier_get_locked (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct mmu_notifier *mmu_notifier_get_locked(const struct mmu_notifier_ops *ops, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffff80001033d180)
Location: mm/mmu_notifier.c:382
Inline: False
Direct callers:
  - mm/hmm.c:hmm_mirror_register
```
**Symbols:**

```
ffff80001033d180-ffff80001033d2d8: mmu_notifier_get_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct mmu_notifier *mmu_notifier_get_locked(const struct mmu_notifier_ops *ops, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (c05434fc)
Location: mm/mmu_notifier.c:382
Inline: False
Direct callers:
  - mm/hmm.c:hmm_mirror_register
```
**Symbols:**

```
c05434fc-c05435f4: mmu_notifier_get_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct mmu_notifier *mmu_notifier_get_locked(const struct mmu_notifier_ops *ops, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (c0000000004180f0)
Location: mm/mmu_notifier.c:382
Inline: False
Direct callers:
  - mm/hmm.c:hmm_mirror_register
```
**Symbols:**

```
c0000000004180f0-c0000000004182a0: mmu_notifier_get_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct mmu_notifier *mmu_notifier_get_locked(const struct mmu_notifier_ops *ops, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffe0002326f8)
Location: mm/mmu_notifier.c:382
Inline: False
Direct callers:
  - mm/hmm.c:hmm_mirror_register
```
**Symbols:**

```
ffffffe0002326f8-ffffffe000232828: mmu_notifier_get_locked (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct mmu_notifier *mmu_notifier_get_locked(const struct mmu_notifier_ops *ops, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81296210)
Location: mm/mmu_notifier.c:382
Inline: False
Direct callers:
  - mm/hmm.c:hmm_mirror_register
```
**Symbols:**

```
ffffffff81296210-ffffffff812962ee: mmu_notifier_get_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct mmu_notifier *mmu_notifier_get_locked(const struct mmu_notifier_ops *ops, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81287e20)
Location: mm/mmu_notifier.c:382
Inline: False
Direct callers:
  - mm/hmm.c:hmm_mirror_register
```
**Symbols:**

```
ffffffff81287e20-ffffffff81287efe: mmu_notifier_get_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct mmu_notifier *mmu_notifier_get_locked(const struct mmu_notifier_ops *ops, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81294020)
Location: mm/mmu_notifier.c:382
Inline: False
Direct callers:
  - mm/hmm.c:hmm_mirror_register
```
**Symbols:**

```
ffffffff81294020-ffffffff812940fe: mmu_notifier_get_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct mmu_notifier *mmu_notifier_get_locked(const struct mmu_notifier_ops *ops, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812a3e40)
Location: mm/mmu_notifier.c:382
Inline: False
Direct callers:
  - mm/hmm.c:hmm_mirror_register
```
**Symbols:**

```
ffffffff812a3e40-ffffffff812a3f23: mmu_notifier_get_locked (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
