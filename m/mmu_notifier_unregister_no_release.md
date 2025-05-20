# Function: <code>mmu_notifier_unregister_no_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void mmu_notifier_unregister_no_release(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff811e3da0)
Location: mm/mmu_notifier.c:393
Inline: True
```
**Symbols:**

```
ffffffff811e3da0-ffffffff811e3e18: mmu_notifier_unregister_no_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void mmu_notifier_unregister_no_release(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81202830)
Location: mm/mmu_notifier.c:393
Inline: True
```
**Symbols:**

```
ffffffff81202830-ffffffff812028a5: mmu_notifier_unregister_no_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void mmu_notifier_unregister_no_release(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81214670)
Location: mm/mmu_notifier.c:393
Inline: True
```
**Symbols:**

```
ffffffff81214670-ffffffff812146e5: mmu_notifier_unregister_no_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void mmu_notifier_unregister_no_release(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8121faf0)
Location: mm/mmu_notifier.c:374
Inline: True
```
**Symbols:**

```
ffffffff8121faf0-ffffffff8121fb65: mmu_notifier_unregister_no_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void mmu_notifier_unregister_no_release(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8123ad00)
Location: mm/mmu_notifier.c:381
Inline: True
```
**Symbols:**

```
ffffffff8123ad00-ffffffff8123ad75: mmu_notifier_unregister_no_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void mmu_notifier_unregister_no_release(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8125e0c0)
Location: mm/mmu_notifier.c:412
Inline: True
Direct callers:
  - mm/hmm.c:hmm_mirror_unregister
```
**Symbols:**

```
ffffffff8125e0c0-ffffffff8125e135: mmu_notifier_unregister_no_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void mmu_notifier_unregister_no_release(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff81272940)
Location: mm/mmu_notifier.c:383
Inline: True
Direct callers:
  - mm/hmm.c:hmm_mirror_unregister
```
**Symbols:**

```
ffffffff81272940-ffffffff812729b5: mmu_notifier_unregister_no_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void mmu_notifier_unregister_no_release(struct mmu_notifier *mn, struct mm_struct *mm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8128df10)
Location: mm/mmu_notifier.c:381
Inline: True
Direct callers:
  - mm/hmm.c:hmm_free
```
**Symbols:**

```
ffffffff8128df10-ffffffff8128df87: mmu_notifier_unregister_no_release (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
