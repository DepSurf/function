# Function: <code>do_mmu_notifier_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm, int take_mmap_sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff811e3b30)
Location: mm/mmu_notifier.c:245
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_notifier_register
  - mm/mmu_notifier.c:__mmu_notifier_register
```
**Symbols:**

```
ffffffff811e3b30-ffffffff811e3c7e: do_mmu_notifier_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm, int take_mmap_sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812025b0)
Location: mm/mmu_notifier.c:245
Inline: False
Direct callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
  - mm/mmu_notifier.c:mmu_notifier_register
```
**Symbols:**

```
ffffffff812025b0-ffffffff81202715: do_mmu_notifier_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm, int take_mmap_sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812143f0)
Location: mm/mmu_notifier.c:245
Inline: False
Direct callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
  - mm/mmu_notifier.c:mmu_notifier_register
```
**Symbols:**

```
ffffffff812143f0-ffffffff81214555: do_mmu_notifier_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm, int take_mmap_sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8121f880)
Location: mm/mmu_notifier.c:232
Inline: False
Direct callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
  - mm/mmu_notifier.c:mmu_notifier_register
```
**Symbols:**

```
ffffffff8121f880-ffffffff8121f9d5: do_mmu_notifier_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm, int take_mmap_sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8123aa90)
Location: mm/mmu_notifier.c:239
Inline: False
Direct callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
  - mm/mmu_notifier.c:mmu_notifier_register
```
**Symbols:**

```
ffffffff8123aa90-ffffffff8123abe5: do_mmu_notifier_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm, int take_mmap_sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8125e140)
Location: mm/mmu_notifier.c:270
Inline: False
Direct callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
  - mm/mmu_notifier.c:mmu_notifier_register
```
**Symbols:**

```
ffffffff8125e140-ffffffff8125e27e: do_mmu_notifier_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm, int take_mmap_sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff812729c0)
Location: mm/mmu_notifier.c:241
Inline: False
Direct callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
  - mm/mmu_notifier.c:mmu_notifier_register
```
**Symbols:**

```
ffffffff812729c0-ffffffff81272afc: do_mmu_notifier_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_mmu_notifier_register(struct mmu_notifier *mn, struct mm_struct *mm, int take_mmap_sem);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_notifier.c (ffffffff8128df90)
Location: mm/mmu_notifier.c:239
Inline: False
Direct callers:
  - mm/mmu_notifier.c:__mmu_notifier_register
  - mm/mmu_notifier.c:mmu_notifier_register
```
**Symbols:**

```
ffffffff8128df90-ffffffff8128e0e6: do_mmu_notifier_register (STB_LOCAL)
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
