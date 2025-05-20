# Function: <code>delayed_uprobe_remove</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811f66f2)
Location: kernel/events/uprobes.c:331
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:update_ref_ctr
Direct callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:update_ref_ctr
```
**Symbols:**

```
ffffffff811f4bb0-ffffffff811f4c1c: delayed_uprobe_remove.part.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8120e4a3)
Location: kernel/events/uprobes.c:319
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:update_ref_ctr
Direct callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:update_ref_ctr
```
**Symbols:**

```
ffffffff8120c800-ffffffff8120c86c: delayed_uprobe_remove.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8121bae3)
Location: kernel/events/uprobes.c:328
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:update_ref_ctr
Direct callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:update_ref_ctr
```
**Symbols:**

```
ffffffff81219af0-ffffffff81219b5c: delayed_uprobe_remove.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void delayed_uprobe_remove(struct uprobe *uprobe, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81248194)
Location: kernel/events/uprobes.c:322
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_clear_state
Direct callers:
  - kernel/events/uprobes.c:update_ref_ctr
```
**Symbols:**

```
ffffffff81245b10-ffffffff81245b85: delayed_uprobe_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void delayed_uprobe_remove(struct uprobe *uprobe, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812528a4)
Location: kernel/events/uprobes.c:322
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_clear_state
Direct callers:
  - kernel/events/uprobes.c:update_ref_ctr
```
**Symbols:**

```
ffffffff81250010-ffffffff81250085: delayed_uprobe_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void delayed_uprobe_remove(struct uprobe *uprobe, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81256904)
Location: kernel/events/uprobes.c:322
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_clear_state
Direct callers:
  - kernel/events/uprobes.c:update_ref_ctr
```
**Symbols:**

```
ffffffff81254830-ffffffff812548a5: delayed_uprobe_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void delayed_uprobe_remove(struct uprobe *uprobe, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81292658)
Location: kernel/events/uprobes.c:322
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_clear_state
Direct callers:
  - kernel/events/uprobes.c:update_ref_ctr
```
**Symbols:**

```
ffffffff812902e0-ffffffff81290393: delayed_uprobe_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void delayed_uprobe_remove(struct uprobe *uprobe, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812e7fac)
Location: kernel/events/uprobes.c:316
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_clear_state
Direct callers:
  - kernel/events/uprobes.c:update_ref_ctr
```
**Symbols:**

```
ffffffff812e5460-ffffffff812e552b: delayed_uprobe_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void delayed_uprobe_remove(struct uprobe *uprobe, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81351cdc)
Location: kernel/events/uprobes.c:318
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:uprobe_clear_state
Direct callers:
  - kernel/events/uprobes.c:update_ref_ctr
```
**Symbols:**

```
ffffffff8134ee30-ffffffff8134eefb: delayed_uprobe_remove (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81382f72)
Location: kernel/events/uprobes.c:317
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:update_ref_ctr
Direct callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:update_ref_ctr
```
**Symbols:**

```
ffffffff8137ffd0-ffffffff813800b2: delayed_uprobe_remove.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813ac342)
Location: kernel/events/uprobes.c:317
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:update_ref_ctr
Direct callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:update_ref_ctr
```
**Symbols:**

```
ffffffff813a9380-ffffffff813a9462: delayed_uprobe_remove.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (ffff8000102a7348)
Location: kernel/events/uprobes.c:328
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:update_ref_ctr
Direct callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:update_ref_ctr
```
**Symbols:**

```
ffff8000102a4d68-ffff8000102a4de8: delayed_uprobe_remove.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (c04d647c)
Location: kernel/events/uprobes.c:328
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:update_ref_ctr
Direct callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:update_ref_ctr
```
**Symbols:**

```
c04d43bc-c04d443c: delayed_uprobe_remove.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void delayed_uprobe_remove(struct uprobe *uprobe, struct mm_struct *mm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c0000000003575a0)
Location: kernel/events/uprobes.c:328
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:update_ref_ctr
```
**Symbols:**

```
c0000000003575a0-c0000000003576e0: delayed_uprobe_remove (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81214133)
Location: kernel/events/uprobes.c:328
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:update_ref_ctr
Direct callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:update_ref_ctr
```
**Symbols:**

```
ffffffff81212140-ffffffff812121ac: delayed_uprobe_remove.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81206ea3)
Location: kernel/events/uprobes.c:328
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:update_ref_ctr
Direct callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:update_ref_ctr
```
**Symbols:**

```
ffffffff81204ed0-ffffffff81204f3c: delayed_uprobe_remove.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81211ed3)
Location: kernel/events/uprobes.c:328
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:update_ref_ctr
Direct callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:update_ref_ctr
```
**Symbols:**

```
ffffffff8120fee0-ffffffff8120ff4c: delayed_uprobe_remove.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81220e23)
Location: kernel/events/uprobes.c:328
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:update_ref_ctr
Direct callers:
  - kernel/events/uprobes.c:uprobe_clear_state
  - kernel/events/uprobes.c:update_ref_ctr
```
**Symbols:**

```
ffffffff8121eeb0-ffffffff8121ef1c: delayed_uprobe_remove.part.0 (STB_LOCAL)
```
</details>
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
</ul>
<b>Arch</b>
<ul>
</ul>
