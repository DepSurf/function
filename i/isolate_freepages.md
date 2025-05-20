# Function: <code>isolate_freepages</code>

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
In mm/compaction.c (ffffffff811b5b4f)
Location: mm/compaction.c:941
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
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
In mm/compaction.c (ffffffff811cf929)
Location: mm/compaction.c:1035
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
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
In mm/compaction.c (ffffffff811df969)
Location: mm/compaction.c:1030
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
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
In mm/compaction.c (ffffffff811e9649)
Location: mm/compaction.c:1041
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
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
In mm/compaction.c (ffffffff811ff9a9)
Location: mm/compaction.c:1065
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
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
In mm/compaction.c (ffffffff81220dc9)
Location: mm/compaction.c:1066
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
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
In mm/compaction.c (ffffffff81233e19)
Location: mm/compaction.c:1067
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81245289)
Location: mm/compaction.c:1431
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81253749)
Location: mm/compaction.c:1432
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void isolate_freepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812823c0)
Location: mm/compaction.c:1439
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
```
**Symbols:**

```
ffffffff812823c0-ffffffff81282647: isolate_freepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void isolate_freepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128c520)
Location: mm/compaction.c:1507
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
```
**Symbols:**

```
ffffffff8128c520-ffffffff8128c79a: isolate_freepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void isolate_freepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812913e0)
Location: mm/compaction.c:1543
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
```
**Symbols:**

```
ffffffff812913e0-ffffffff81291668: isolate_freepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void isolate_freepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:1535
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
```
**Symbols:**

```
ffffffff812d2d20-ffffffff812d2fec: isolate_freepages (STB_LOCAL)
ffffffff81cbba8e-ffffffff81cbbb0c: isolate_freepages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void isolate_freepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:1568
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
```
**Symbols:**

```
ffffffff8132fe70-ffffffff8133013c: isolate_freepages (STB_LOCAL)
ffffffff81e6d42b-ffffffff81e6d49b: isolate_freepages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void isolate_freepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:1559
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
```
**Symbols:**

```
ffffffff813a6a40-ffffffff813a6d0c: isolate_freepages (STB_LOCAL)
ffffffff82063783-ffffffff820637f3: isolate_freepages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void isolate_freepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:1618
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
```
**Symbols:**

```
ffffffff813da260-ffffffff813da52c: isolate_freepages (STB_LOCAL)
ffffffff820e2e81-ffffffff820e2ef1: isolate_freepages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void isolate_freepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:1659
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
```
**Symbols:**

```
ffffffff81404050-ffffffff81404419: isolate_freepages (STB_LOCAL)
ffffffff821bf8a2-ffffffff821bf905: isolate_freepages.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffff8000102eac14)
Location: mm/compaction.c:1432
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c050eed0)
Location: mm/compaction.c:1432
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c0000000003ada80)
Location: mm/compaction.c:1432
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffe0001ff1b4)
Location: mm/compaction.c:1432
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124bd99)
Location: mm/compaction.c:1432
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8123ed39)
Location: mm/compaction.c:1432
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81249b39)
Location: mm/compaction.c:1432
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812593b9)
Location: mm/compaction.c:1432
Inline: True
Inline callers:
  - mm/compaction.c:compaction_alloc
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
