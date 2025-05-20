# Function: <code>hmm_invalidate_range_end</code>

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
void hmm_invalidate_range_end(struct mmu_notifier *mn, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff8126e070)
Location: mm/hmm.c:175
Inline: False
```
**Symbols:**

```
ffffffff8126e070-ffffffff8126e167: hmm_invalidate_range_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void hmm_invalidate_range_end(struct mmu_notifier *mn, struct mm_struct *mm, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff81293b30)
Location: mm/hmm.c:192
Inline: False
```
**Symbols:**

```
ffffffff81293b30-ffffffff81293c30: hmm_invalidate_range_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void hmm_invalidate_range_end(struct mmu_notifier *mn, const struct mmu_notifier_range *range);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812a8170)
Location: mm/hmm.c:206
Inline: False
```
**Symbols:**

```
ffffffff812a8170-ffffffff812a81d2: hmm_invalidate_range_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void hmm_invalidate_range_end(struct mmu_notifier *mn, const struct mmu_notifier_range *nrange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812c3f80)
Location: mm/hmm.c:218
Inline: False
```
**Symbols:**

```
ffffffff812c3f80-ffffffff812c3fde: hmm_invalidate_range_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void hmm_invalidate_range_end(struct mmu_notifier *mn, const struct mmu_notifier_range *nrange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812d4f00)
Location: mm/hmm.c:143
Inline: False
```
**Symbols:**

```
ffffffff812d4f00-ffffffff812d4f10: hmm_invalidate_range_end (STB_LOCAL)
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
void hmm_invalidate_range_end(struct mmu_notifier *mn, const struct mmu_notifier_range *nrange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffff80001037ade8)
Location: mm/hmm.c:143
Inline: False
```
**Symbols:**

```
ffff80001037ade8-ffff80001037ae14: hmm_invalidate_range_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void hmm_invalidate_range_end(struct mmu_notifier *mn, const struct mmu_notifier_range *nrange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (c0565640)
Location: mm/hmm.c:143
Inline: False
```
**Symbols:**

```
c0565640-c056565c: hmm_invalidate_range_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void hmm_invalidate_range_end(struct mmu_notifier *mn, const struct mmu_notifier_range *nrange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (c00000000046e980)
Location: mm/hmm.c:143
Inline: False
```
**Symbols:**

```
c00000000046e980-c00000000046e994: hmm_invalidate_range_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void hmm_invalidate_range_end(struct mmu_notifier *mn, const struct mmu_notifier_range *nrange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffe0002516ac)
Location: mm/hmm.c:143
Inline: False
```
**Symbols:**

```
ffffffe0002516ac-ffffffe0002516d6: hmm_invalidate_range_end (STB_LOCAL)
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
void hmm_invalidate_range_end(struct mmu_notifier *mn, const struct mmu_notifier_range *nrange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812cd4e0)
Location: mm/hmm.c:143
Inline: False
```
**Symbols:**

```
ffffffff812cd4e0-ffffffff812cd4f0: hmm_invalidate_range_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void hmm_invalidate_range_end(struct mmu_notifier *mn, const struct mmu_notifier_range *nrange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812be350)
Location: mm/hmm.c:143
Inline: False
```
**Symbols:**

```
ffffffff812be350-ffffffff812be360: hmm_invalidate_range_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void hmm_invalidate_range_end(struct mmu_notifier *mn, const struct mmu_notifier_range *nrange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812cb2f0)
Location: mm/hmm.c:143
Inline: False
```
**Symbols:**

```
ffffffff812cb2f0-ffffffff812cb300: hmm_invalidate_range_end (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void hmm_invalidate_range_end(struct mmu_notifier *mn, const struct mmu_notifier_range *nrange);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812dc050)
Location: mm/hmm.c:143
Inline: False
```
**Symbols:**

```
ffffffff812dc050-ffffffff812dc060: hmm_invalidate_range_end (STB_LOCAL)
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
