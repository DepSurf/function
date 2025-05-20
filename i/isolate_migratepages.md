# Function: <code>isolate_migratepages</code>

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
In mm/compaction.c (ffffffff811b7686)
Location: mm/compaction.c:1103
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
In mm/compaction.c (ffffffff811d107a)
Location: mm/compaction.c:1194
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
In mm/compaction.c (ffffffff811e10a2)
Location: mm/compaction.c:1189
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
In mm/compaction.c (ffffffff811ead8b)
Location: mm/compaction.c:1200
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
In mm/compaction.c (ffffffff8120119a)
Location: mm/compaction.c:1224
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
In mm/compaction.c (ffffffff81222570)
Location: mm/compaction.c:1224
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
In mm/compaction.c (ffffffff812355c0)
Location: mm/compaction.c:1225
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
In mm/compaction.c (ffffffff812466da)
Location: mm/compaction.c:1740
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
In mm/compaction.c (ffffffff81254be0)
Location: mm/compaction.c:1741
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
isolate_migrate_t isolate_migratepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812831a0)
Location: mm/compaction.c:1752
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff812831a0-ffffffff812833df: isolate_migratepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
isolate_migrate_t isolate_migratepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128d400)
Location: mm/compaction.c:1817
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff8128d400-ffffffff8128d635: isolate_migratepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
isolate_migrate_t isolate_migratepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812923a0)
Location: mm/compaction.c:1853
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff812923a0-ffffffff812925c3: isolate_migratepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
isolate_migrate_t isolate_migratepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:1845
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff812d1d30-ffffffff812d1f50: isolate_migratepages (STB_LOCAL)
ffffffff81cbb9bf-ffffffff81cbba0d: isolate_migratepages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
isolate_migrate_t isolate_migratepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:1880
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff81331ad0-ffffffff81331dab: isolate_migratepages (STB_LOCAL)
ffffffff81e6d686-ffffffff81e6d6d3: isolate_migratepages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
isolate_migrate_t isolate_migratepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:1867
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff813a8800-ffffffff813a8a28: isolate_migratepages (STB_LOCAL)
ffffffff820639cc-ffffffff82063a19: isolate_migratepages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
isolate_migrate_t isolate_migratepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:1939
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff813db880-ffffffff813dbba2: isolate_migratepages (STB_LOCAL)
ffffffff820e30eb-ffffffff820e3148: isolate_migratepages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
isolate_migrate_t isolate_migratepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:1988
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff814057e0-ffffffff81405b02: isolate_migratepages (STB_LOCAL)
ffffffff821bfb0a-ffffffff821bfb67: isolate_migratepages.cold (STB_LOCAL)
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
In mm/compaction.c (ffff8000102ec13c)
Location: mm/compaction.c:1741
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
In mm/compaction.c (c05101d4)
Location: mm/compaction.c:1741
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
In mm/compaction.c (c0000000003af90c)
Location: mm/compaction.c:1741
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
In mm/compaction.c (ffffffe000200a02)
Location: mm/compaction.c:1741
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
In mm/compaction.c (ffffffff8124d230)
Location: mm/compaction.c:1741
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
In mm/compaction.c (ffffffff812401d0)
Location: mm/compaction.c:1741
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
In mm/compaction.c (ffffffff8124afd0)
Location: mm/compaction.c:1741
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
In mm/compaction.c (ffffffff8125a864)
Location: mm/compaction.c:1741
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
