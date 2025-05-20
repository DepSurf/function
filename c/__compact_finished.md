# Function: <code>__compact_finished</code>

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
In mm/compaction.c (ffffffff811b75e3)
Location: mm/compaction.c:1198
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
In mm/compaction.c (ffffffff811d106d)
Location: mm/compaction.c:1286
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
In mm/compaction.c (ffffffff811e1095)
Location: mm/compaction.c:1278
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
In mm/compaction.c (ffffffff811ead7e)
Location: mm/compaction.c:1288
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
In mm/compaction.c (ffffffff812010fe)
Location: mm/compaction.c:1312
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
In mm/compaction.c (ffffffff81222520)
Location: mm/compaction.c:1312
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
In mm/compaction.c (ffffffff81235570)
Location: mm/compaction.c:1313
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
In mm/compaction.c (ffffffff81246629)
Location: mm/compaction.c:1849
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
In mm/compaction.c (ffffffff81254b3b)
Location: mm/compaction.c:1849
Inline: True
Inline callers:
  - mm/compaction.c:compact_zone
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
In mm/compaction.c (ffffffff81281690)
Location: mm/compaction.c:1860
Inline: True
Inline callers:
  - mm/compaction.c:compact_finished
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
enum compact_result __compact_finished(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128ac70)
Location: mm/compaction.c:1995
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff8128ac70-ffffffff8128aead: __compact_finished (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
enum compact_result __compact_finished(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81290a70)
Location: mm/compaction.c:2034
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff81290a70-ffffffff81290c85: __compact_finished (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum compact_result __compact_finished(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2026
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff812d0bf0-ffffffff812d0eba: __compact_finished (STB_LOCAL)
ffffffff81cbb794-ffffffff81cbb7e6: __compact_finished.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum compact_result __compact_finished(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2061
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff8132f3a0-ffffffff8132f641: __compact_finished (STB_LOCAL)
ffffffff81e6d350-ffffffff81e6d3a2: __compact_finished.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
enum compact_result __compact_finished(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2060
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff813a5ad0-ffffffff813a5d94: __compact_finished (STB_LOCAL)
ffffffff820635c4-ffffffff82063614: __compact_finished.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
enum compact_result __compact_finished(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2141
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff813d9740-ffffffff813d9a04: __compact_finished (STB_LOCAL)
ffffffff820e2d9e-ffffffff820e2dee: __compact_finished.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
enum compact_result __compact_finished(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2192
Inline: False
Direct callers:
  - mm/compaction.c:compact_zone
```
**Symbols:**

```
ffffffff81403470-ffffffff81403734: __compact_finished (STB_LOCAL)
ffffffff821bf7ab-ffffffff821bf7fb: __compact_finished.cold (STB_LOCAL)
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
In mm/compaction.c (ffff8000102ec080)
Location: mm/compaction.c:1849
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
In mm/compaction.c (c0510114)
Location: mm/compaction.c:1849
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
In mm/compaction.c (c0000000003af84c)
Location: mm/compaction.c:1849
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
In mm/compaction.c (ffffffe000200a1a)
Location: mm/compaction.c:1849
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
In mm/compaction.c (ffffffff8124d18b)
Location: mm/compaction.c:1849
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
In mm/compaction.c (ffffffff8124012b)
Location: mm/compaction.c:1849
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
In mm/compaction.c (ffffffff8124af2b)
Location: mm/compaction.c:1849
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
In mm/compaction.c (ffffffff8125a7bb)
Location: mm/compaction.c:1849
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
