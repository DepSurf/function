# Function: <code>hmm_invalidate_range_start</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void hmm_invalidate_range_start(struct mmu_notifier *mn, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff8126cec0)
Location: mm/hmm.c:163
Inline: False
```
**Symbols:**

```
ffffffff8126cec0-ffffffff8126ced6: hmm_invalidate_range_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void hmm_invalidate_range_start(struct mmu_notifier *mn, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff81291ba0)
Location: mm/hmm.c:180
Inline: False
```
**Symbols:**

```
ffffffff81291ba0-ffffffff81291bb6: hmm_invalidate_range_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hmm_invalidate_range_start(struct mmu_notifier *mn, const struct mmu_notifier_range *range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812a8100)
Location: mm/hmm.c:191
Inline: False
```
**Symbols:**

```
ffffffff812a8100-ffffffff812a8168: hmm_invalidate_range_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int hmm_invalidate_range_start(struct mmu_notifier *mn, const struct mmu_notifier_range *nrange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hmm.c (0)
Location: mm/hmm.c:163
Inline: False
```
**Symbols:**

```
ffffffff812c39f0-ffffffff812c3b9d: hmm_invalidate_range_start (STB_LOCAL)
ffffffff812c5046-ffffffff812c5059: hmm_invalidate_range_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hmm_invalidate_range_start(struct mmu_notifier *mn, const struct mmu_notifier_range *nrange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812d4f10)
Location: mm/hmm.c:97
Inline: False
```
**Symbols:**

```
ffffffff812d4f10-ffffffff812d5011: hmm_invalidate_range_start (STB_LOCAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int hmm_invalidate_range_start(struct mmu_notifier *mn, const struct mmu_notifier_range *nrange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffff80001037ae18)
Location: mm/hmm.c:97
Inline: False
```
**Symbols:**

```
ffff80001037ae18-ffff80001037afc8: hmm_invalidate_range_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int hmm_invalidate_range_start(struct mmu_notifier *mn, const struct mmu_notifier_range *nrange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (c056565c)
Location: mm/hmm.c:97
Inline: False
```
**Symbols:**

```
c056565c-c05657b0: hmm_invalidate_range_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hmm_invalidate_range_start(struct mmu_notifier *mn, const struct mmu_notifier_range *nrange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (c00000000046e9a0)
Location: mm/hmm.c:97
Inline: False
```
**Symbols:**

```
c00000000046e9a0-c00000000046eb4c: hmm_invalidate_range_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int hmm_invalidate_range_start(struct mmu_notifier *mn, const struct mmu_notifier_range *nrange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffe0002516d6)
Location: mm/hmm.c:97
Inline: False
```
**Symbols:**

```
ffffffe0002516d6-ffffffe0002517e0: hmm_invalidate_range_start (STB_LOCAL)
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
int hmm_invalidate_range_start(struct mmu_notifier *mn, const struct mmu_notifier_range *nrange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812cd4f0)
Location: mm/hmm.c:97
Inline: False
```
**Symbols:**

```
ffffffff812cd4f0-ffffffff812cd5f1: hmm_invalidate_range_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hmm_invalidate_range_start(struct mmu_notifier *mn, const struct mmu_notifier_range *nrange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812be360)
Location: mm/hmm.c:97
Inline: False
```
**Symbols:**

```
ffffffff812be360-ffffffff812be461: hmm_invalidate_range_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hmm_invalidate_range_start(struct mmu_notifier *mn, const struct mmu_notifier_range *nrange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812cb300)
Location: mm/hmm.c:97
Inline: False
```
**Symbols:**

```
ffffffff812cb300-ffffffff812cb401: hmm_invalidate_range_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hmm_invalidate_range_start(struct mmu_notifier *mn, const struct mmu_notifier_range *nrange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812dc060)
Location: mm/hmm.c:97
Inline: False
```
**Symbols:**

```
ffffffff812dc060-ffffffff812dc161: hmm_invalidate_range_start (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct mmu_notifier_range *range</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct *mm</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int start</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int end</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct mmu_notifier_range *nrange</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct mmu_notifier_range *range</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
