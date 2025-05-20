# Function: <code>compact_lock_irqsave</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/compaction.c (ffffffff81243c40)
Location: mm/compaction.c:481
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff81243c40-ffffffff81243ca5: compact_lock_irqsave.isra.0 (STB_LOCAL)
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
In mm/compaction.c (ffffffff81252100)
Location: mm/compaction.c:482
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff81252100-ffffffff81252165: compact_lock_irqsave.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool compact_lock_irqsave(spinlock_t *lock, long unsigned int *flags, struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8127f430)
Location: mm/compaction.c:482
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff8127f430-ffffffff8127f49a: compact_lock_irqsave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool compact_lock_irqsave(spinlock_t *lock, long unsigned int *flags, struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812894d0)
Location: mm/compaction.c:499
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff812894d0-ffffffff8128953a: compact_lock_irqsave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool compact_lock_irqsave(spinlock_t *lock, long unsigned int *flags, struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128eb20)
Location: mm/compaction.c:498
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff8128eb20-ffffffff8128eb98: compact_lock_irqsave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool compact_lock_irqsave(spinlock_t *lock, long unsigned int *flags, struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:496
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff812cfcc0-ffffffff812cfd49: compact_lock_irqsave (STB_LOCAL)
ffffffff81cbb61d-ffffffff81cbb632: compact_lock_irqsave.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool compact_lock_irqsave(spinlock_t *lock, long unsigned int *flags, struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:495
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff8132e730-ffffffff8132e7be: compact_lock_irqsave (STB_LOCAL)
ffffffff81e6d1dd-ffffffff81e6d1f2: compact_lock_irqsave.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool compact_lock_irqsave(spinlock_t *lock, long unsigned int *flags, struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:490
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff813a4f10-ffffffff813a4fa3: compact_lock_irqsave (STB_LOCAL)
ffffffff82063535-ffffffff8206354a: compact_lock_irqsave.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool compact_lock_irqsave(spinlock_t *lock, long unsigned int *flags, struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:508
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff813d8480-ffffffff813d8513: compact_lock_irqsave (STB_LOCAL)
ffffffff820e2c3b-ffffffff820e2c50: compact_lock_irqsave.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool compact_lock_irqsave(spinlock_t *lock, long unsigned int *flags, struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:532
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff81402160-ffffffff814021f3: compact_lock_irqsave (STB_LOCAL)
ffffffff821bf563-ffffffff821bf578: compact_lock_irqsave.cold (STB_LOCAL)
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
In mm/compaction.c (ffff8000102ea090)
Location: mm/compaction.c:482
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffff8000102ea090-ffff8000102ea1b4: compact_lock_irqsave.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool compact_lock_irqsave(spinlock_t *lock, long unsigned int *flags, struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c050bf9c)
Location: mm/compaction.c:482
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
c050bf9c-c050c014: compact_lock_irqsave (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/compaction.c (c0000000003ac080)
Location: mm/compaction.c:482
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
c0000000003ac080-c0000000003ac16c: compact_lock_irqsave.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/compaction.c (ffffffe0001fe850)
Location: mm/compaction.c:482
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffe0001fe850-ffffffe0001fe8bc: compact_lock_irqsave.isra.0 (STB_LOCAL)
```
</details>
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
In mm/compaction.c (ffffffff8124a750)
Location: mm/compaction.c:482
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff8124a750-ffffffff8124a7b5: compact_lock_irqsave.isra.0 (STB_LOCAL)
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
In mm/compaction.c (ffffffff8123d700)
Location: mm/compaction.c:482
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff8123d700-ffffffff8123d756: compact_lock_irqsave.isra.0 (STB_LOCAL)
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
In mm/compaction.c (ffffffff812484f0)
Location: mm/compaction.c:482
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff812484f0-ffffffff81248555: compact_lock_irqsave.isra.0 (STB_LOCAL)
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
In mm/compaction.c (ffffffff81257d20)
Location: mm/compaction.c:482
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff81257d20-ffffffff81257d85: compact_lock_irqsave.isra.0 (STB_LOCAL)
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
