# Function: <code>mlock_fixup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mlock_fixup(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, vm_flags_t newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811c3590)
Location: mm/mlock.c:498
Inline: False
Direct callers:
  - mm/mlock.c:apply_vma_lock_flags
  - mm/mlock.c:apply_mlockall_flags
```
**Symbols:**

```
ffffffff811c3590-ffffffff811c3712: mlock_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mlock_fixup(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, vm_flags_t newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811df370)
Location: mm/mlock.c:511
Inline: False
Direct callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:apply_vma_lock_flags
```
**Symbols:**

```
ffffffff811df370-ffffffff811df4f2: mlock_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mlock_fixup(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, vm_flags_t newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811ef1e0)
Location: mm/mlock.c:513
Inline: False
Direct callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:apply_vma_lock_flags
```
**Symbols:**

```
ffffffff811ef1e0-ffffffff811ef396: mlock_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mlock_fixup(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, vm_flags_t newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff811fa100)
Location: mm/mlock.c:514
Inline: False
Direct callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:apply_vma_lock_flags
```
**Symbols:**

```
ffffffff811fa100-ffffffff811fa294: mlock_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mlock_fixup(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, vm_flags_t newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81212630)
Location: mm/mlock.c:513
Inline: False
Direct callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:apply_vma_lock_flags
```
**Symbols:**

```
ffffffff81212630-ffffffff812127c4: mlock_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mlock_fixup(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, vm_flags_t newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81233350)
Location: mm/mlock.c:519
Inline: False
Direct callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:apply_vma_lock_flags
```
**Symbols:**

```
ffffffff81233350-ffffffff812334fc: mlock_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mlock_fixup(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, vm_flags_t newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81246b20)
Location: mm/mlock.c:519
Inline: False
Direct callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:apply_vma_lock_flags
```
**Symbols:**

```
ffffffff81246b20-ffffffff81246ccc: mlock_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mlock_fixup(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, vm_flags_t newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81258d30)
Location: mm/mlock.c:519
Inline: False
Direct callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:apply_vma_lock_flags
```
**Symbols:**

```
ffffffff81258d30-ffffffff81258edf: mlock_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mlock_fixup(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, vm_flags_t newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81267200)
Location: mm/mlock.c:519
Inline: False
Direct callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:apply_vma_lock_flags
```
**Symbols:**

```
ffffffff81267200-ffffffff812673af: mlock_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mlock_fixup(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, vm_flags_t newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81297330)
Location: mm/mlock.c:519
Inline: False
Direct callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:apply_vma_lock_flags
```
**Symbols:**

```
ffffffff81297330-ffffffff812974e0: mlock_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mlock_fixup(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, vm_flags_t newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812a22e0)
Location: mm/mlock.c:495
Inline: False
Direct callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:apply_vma_lock_flags
```
**Symbols:**

```
ffffffff812a22e0-ffffffff812a2495: mlock_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mlock_fixup(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, vm_flags_t newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812a7b70)
Location: mm/mlock.c:494
Inline: False
Direct callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:apply_vma_lock_flags
```
**Symbols:**

```
ffffffff812a7b70-ffffffff812a7d32: mlock_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mlock_fixup(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, vm_flags_t newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff812e91b0)
Location: mm/mlock.c:495
Inline: False
Direct callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:apply_vma_lock_flags
```
**Symbols:**

```
ffffffff812e91b0-ffffffff812e938b: mlock_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mlock_fixup(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, vm_flags_t newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81349760)
Location: mm/mlock.c:404
Inline: False
Direct callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:apply_vma_lock_flags
```
**Symbols:**

```
ffffffff81349760-ffffffff813499cd: mlock_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mlock_fixup(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, vm_flags_t newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff813c1a70)
Location: mm/mlock.c:404
Inline: False
Direct callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:apply_vma_lock_flags
```
**Symbols:**

```
ffffffff813c1a70-ffffffff813c1cd1: mlock_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mlock_fixup(struct vma_iterator *vmi, struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, vm_flags_t newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff813f7040)
Location: mm/mlock.c:411
Inline: False
Direct callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:apply_vma_lock_flags
```
**Symbols:**

```
ffffffff813f7040-ffffffff813f7392: mlock_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mlock_fixup(struct vma_iterator *vmi, struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, vm_flags_t newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff814225a0)
Location: mm/mlock.c:478
Inline: False
Direct callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:apply_vma_lock_flags
```
**Symbols:**

```
ffffffff814225a0-ffffffff81422812: mlock_fixup (STB_LOCAL)
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
int mlock_fixup(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, vm_flags_t newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffff8000102fe430)
Location: mm/mlock.c:519
Inline: False
Direct callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:apply_vma_lock_flags
```
**Symbols:**

```
ffff8000102fe430-ffff8000102fe5c8: mlock_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mlock_fixup(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, vm_flags_t newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (c051d428)
Location: mm/mlock.c:519
Inline: False
Direct callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:apply_vma_lock_flags
```
**Symbols:**

```
c051d428-c051d5cc: mlock_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mlock_fixup(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, vm_flags_t newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (c0000000003c9d60)
Location: mm/mlock.c:519
Inline: False
Direct callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:apply_vma_lock_flags
```
**Symbols:**

```
c0000000003c9d60-c0000000003c9fb0: mlock_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mlock_fixup(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, vm_flags_t newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffe00020c90a)
Location: mm/mlock.c:519
Inline: False
Direct callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:apply_vma_lock_flags
```
**Symbols:**

```
ffffffe00020c90a-ffffffe00020ca44: mlock_fixup (STB_LOCAL)
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
int mlock_fixup(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, vm_flags_t newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8125f850)
Location: mm/mlock.c:519
Inline: False
Direct callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:apply_vma_lock_flags
```
**Symbols:**

```
ffffffff8125f850-ffffffff8125f9ff: mlock_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mlock_fixup(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, vm_flags_t newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff81251c70)
Location: mm/mlock.c:519
Inline: False
Direct callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:apply_vma_lock_flags
```
**Symbols:**

```
ffffffff81251c70-ffffffff81251e1f: mlock_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mlock_fixup(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, vm_flags_t newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8125d5f0)
Location: mm/mlock.c:519
Inline: False
Direct callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:apply_vma_lock_flags
```
**Symbols:**

```
ffffffff8125d5f0-ffffffff8125d79f: mlock_fixup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mlock_fixup(struct vm_area_struct *vma, struct vm_area_struct **prev, long unsigned int start, long unsigned int end, vm_flags_t newflags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mlock.c (ffffffff8126cfd0)
Location: mm/mlock.c:519
Inline: False
Direct callers:
  - mm/mlock.c:apply_mlockall_flags
  - mm/mlock.c:apply_vma_lock_flags
```
**Symbols:**

```
ffffffff8126cfd0-ffffffff8126d17f: mlock_fixup (STB_LOCAL)
```
</details>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vma_iterator *vmi</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, prev, start, end, newflags</code> ➡️ <code>vmi, vma, prev, start, end, newflags</code>
</li>
</ul>
</details>
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
