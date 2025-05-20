# Function: <code>dup_mmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8107f8c7)
Location: kernel/fork.c:402
Inline: True
Inline callers:
  - kernel/fork.c:copy_process
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81080d1f)
Location: kernel/fork.c:412
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81085727)
Location: kernel/fork.c:560
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81082d83)
Location: kernel/fork.c:595
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81088e63)
Location: kernel/fork.c:603
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8108b7d3)
Location: kernel/fork.c:425
Inline: True
Inline callers:
  - kernel/fork.c:copy_mm
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81095264)
Location: kernel/fork.c:468
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dup_mmap(struct mm_struct *mm, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810976a0)
Location: kernel/fork.c:474
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
```
**Symbols:**

```
ffffffff810976a0-ffffffff81097b82: dup_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dup_mmap(struct mm_struct *mm, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109dd60)
Location: kernel/fork.c:483
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
```
**Symbols:**

```
ffffffff8109dd60-ffffffff8109e242: dup_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dup_mmap(struct mm_struct *mm, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a5380)
Location: kernel/fork.c:490
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
```
**Symbols:**

```
ffffffff810a5380-ffffffff810a5833: dup_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dup_mmap(struct mm_struct *mm, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a0ae0)
Location: kernel/fork.c:475
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
```
**Symbols:**

```
ffffffff810a0ae0-ffffffff810a102b: dup_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dup_mmap(struct mm_struct *mm, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff810a1870)
Location: kernel/fork.c:479
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
```
**Symbols:**

```
ffffffff810a1870-ffffffff810a1da2: dup_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int dup_mmap(struct mm_struct *mm, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/fork.c (0)
Location: kernel/fork.c:494
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
```
**Symbols:**

```
ffffffff810b3410-ffffffff810b397f: dup_mmap (STB_LOCAL)
ffffffff81ca3935-ffffffff81ca3968: dup_mmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int dup_mmap(struct mm_struct *mm, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/fork.c (0)
Location: kernel/fork.c:585
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
```
**Symbols:**

```
ffffffff810c9640-ffffffff810c9bca: dup_mmap (STB_LOCAL)
ffffffff81e53051-ffffffff81e53085: dup_mmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int dup_mmap(struct mm_struct *mm, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/fork.c (0)
Location: kernel/fork.c:586
Inline: False
```
**Symbols:**

```
ffffffff810e6bc0-ffffffff810e71b6: dup_mmap (STB_LOCAL)
ffffffff82055a95-ffffffff82055aa9: dup_mmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int dup_mmap(struct mm_struct *mm, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/fork.c (0)
Location: kernel/fork.c:651
Inline: False
```
**Symbols:**

```
ffffffff810f2580-ffffffff810f2cc3: dup_mmap (STB_LOCAL)
ffffffff820d407a-ffffffff820d408f: dup_mmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int dup_mmap(struct mm_struct *mm, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/fork.c (0)
Location: kernel/fork.c:631
Inline: False
```
**Symbols:**

```
ffffffff810fb080-ffffffff810fb821: dup_mmap (STB_LOCAL)
ffffffff821aef4e-ffffffff821aef63: dup_mmap.cold (STB_LOCAL)
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
int dup_mmap(struct mm_struct *mm, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffff8000100f2990)
Location: kernel/fork.c:483
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
```
**Symbols:**

```
ffff8000100f2990-ffff8000100f2df4: dup_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dup_mmap(struct mm_struct *mm, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c0351254)
Location: kernel/fork.c:483
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
```
**Symbols:**

```
c0351254-c03516a0: dup_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dup_mmap(struct mm_struct *mm, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (c000000000138560)
Location: kernel/fork.c:483
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
```
**Symbols:**

```
c000000000138560-c000000000138adc: dup_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dup_mmap(struct mm_struct *mm, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffe0000bf5d0)
Location: kernel/fork.c:483
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
```
**Symbols:**

```
ffffffe0000bf5d0-ffffffe0000bf928: dup_mmap (STB_LOCAL)
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
int dup_mmap(struct mm_struct *mm, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097680)
Location: kernel/fork.c:483
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
```
**Symbols:**

```
ffffffff81097680-ffffffff81097b62: dup_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dup_mmap(struct mm_struct *mm, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81086100)
Location: kernel/fork.c:483
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
```
**Symbols:**

```
ffffffff81086100-ffffffff810865d5: dup_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dup_mmap(struct mm_struct *mm, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff81097630)
Location: kernel/fork.c:483
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
```
**Symbols:**

```
ffffffff81097630-ffffffff81097b12: dup_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dup_mmap(struct mm_struct *mm, struct mm_struct *oldmm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/fork.c (ffffffff8109f230)
Location: kernel/fork.c:483
Inline: False
Direct callers:
  - kernel/fork.c:dup_mm
```
**Symbols:**

```
ffffffff8109f230-ffffffff8109f712: dup_mmap (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
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
