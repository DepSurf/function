# Function: <code>compact_unlock_should_abort</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/compaction.c (ffffffff811b5680)
Location: mm/compaction.c:341
Inline: True
Direct callers:
  - mm/compaction.c:isolate_freepages_block
  - mm/compaction.c:isolate_migratepages_block
```
**Symbols:**

```
ffffffff811b5680-ffffffff811b5708: compact_unlock_should_abort.isra.32 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/compaction.c (ffffffff811cf470)
Location: mm/compaction.c:359
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff811cf470-ffffffff811cf4f5: compact_unlock_should_abort.isra.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/compaction.c (ffffffff811df4c0)
Location: mm/compaction.c:359
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff811df4c0-ffffffff811df53c: compact_unlock_should_abort.isra.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/compaction.c (ffffffff811e9170)
Location: mm/compaction.c:354
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff811e9170-ffffffff811e91f9: compact_unlock_should_abort.isra.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/compaction.c (ffffffff811ff4d0)
Location: mm/compaction.c:380
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff811ff4d0-ffffffff811ff559: compact_unlock_should_abort.isra.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/compaction.c (ffffffff812208f0)
Location: mm/compaction.c:380
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff812208f0-ffffffff81220975: compact_unlock_should_abort.isra.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/compaction.c (ffffffff81233940)
Location: mm/compaction.c:381
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff81233940-ffffffff812339c5: compact_unlock_should_abort.isra.30 (STB_LOCAL)
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
In mm/compaction.c (ffffffff81243cf0)
Location: mm/compaction.c:511
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff81243cf0-ffffffff81243d43: compact_unlock_should_abort.isra.0 (STB_LOCAL)
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
In mm/compaction.c (ffffffff812521b0)
Location: mm/compaction.c:512
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff812521b0-ffffffff81252203: compact_unlock_should_abort.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128290e)
Location: mm/compaction.c:513
Inline: True
Inline callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128bc20)
Location: mm/compaction.c:530
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81290818)
Location: mm/compaction.c:529
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812d099b)
Location: mm/compaction.c:527
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8132f0a3)
Location: mm/compaction.c:523
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813a613e)
Location: mm/compaction.c:518
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813d948a)
Location: mm/compaction.c:536
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff814032cc)
Location: mm/compaction.c:560
Inline: True
Inline callers:
  - mm/compaction.c:isolate_freepages_block
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
In mm/compaction.c (ffff8000102ea000)
Location: mm/compaction.c:512
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffff8000102ea000-ffff8000102ea08c: compact_unlock_should_abort.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool compact_unlock_should_abort(spinlock_t *lock, long unsigned int flags, bool *locked, struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c050d918)
Location: mm/compaction.c:512
Inline: False
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
c050d918-c050d994: compact_unlock_should_abort (STB_LOCAL)
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
In mm/compaction.c (c0000000003ac170)
Location: mm/compaction.c:512
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
c0000000003ac170-c0000000003ac218: compact_unlock_should_abort.isra.0 (STB_LOCAL)
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
In mm/compaction.c (ffffffe0001fe968)
Location: mm/compaction.c:512
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffe0001fe968-ffffffe0001fe9e2: compact_unlock_should_abort.isra.0 (STB_LOCAL)
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
In mm/compaction.c (ffffffff8124a800)
Location: mm/compaction.c:512
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff8124a800-ffffffff8124a853: compact_unlock_should_abort.isra.0 (STB_LOCAL)
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
In mm/compaction.c (ffffffff8123d7a0)
Location: mm/compaction.c:512
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff8123d7a0-ffffffff8123d7f3: compact_unlock_should_abort.isra.0 (STB_LOCAL)
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
In mm/compaction.c (ffffffff812485a0)
Location: mm/compaction.c:512
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff812485a0-ffffffff812485f3: compact_unlock_should_abort.isra.0 (STB_LOCAL)
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
In mm/compaction.c (ffffffff81257dd0)
Location: mm/compaction.c:512
Inline: True
Direct callers:
  - mm/compaction.c:isolate_migratepages_block
  - mm/compaction.c:isolate_freepages_block
```
**Symbols:**

```
ffffffff81257dd0-ffffffff81257e23: compact_unlock_should_abort.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
