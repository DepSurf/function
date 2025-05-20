# Function: <code>print_wakeup_source_stats</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int print_wakeup_source_stats(struct seq_file *m, struct wakeup_source *ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff8155bd30)
Location: drivers/base/power/wakeup.c:982
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_show
```
**Symbols:**

```
ffffffff8155bd30-ffffffff8155bea8: print_wakeup_source_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int print_wakeup_source_stats(struct seq_file *m, struct wakeup_source *ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815adf30)
Location: drivers/base/power/wakeup.c:980
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_show
```
**Symbols:**

```
ffffffff815adf30-ffffffff815ae0a5: print_wakeup_source_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int print_wakeup_source_stats(struct seq_file *m, struct wakeup_source *ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815dcd30)
Location: drivers/base/power/wakeup.c:980
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_show
```
**Symbols:**

```
ffffffff815dcd30-ffffffff815dcea5: print_wakeup_source_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int print_wakeup_source_stats(struct seq_file *m, struct wakeup_source *ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff815f16e0)
Location: drivers/base/power/wakeup.c:988
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_show
```
**Symbols:**

```
ffffffff815f16e0-ffffffff815f1834: print_wakeup_source_stats (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int print_wakeup_source_stats(struct seq_file *m, struct wakeup_source *ws);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81658cd0)
Location: drivers/base/power/wakeup.c:989
Inline: False
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_show
```
**Symbols:**

```
ffffffff81658cd0-ffffffff81658e21: print_wakeup_source_stats (STB_LOCAL)
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
In drivers/base/power/wakeup.c (ffffffff81694835)
Location: drivers/base/power/wakeup.c:988
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
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
In drivers/base/power/wakeup.c (ffffffff816b4ec5)
Location: drivers/base/power/wakeup.c:994
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
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
In drivers/base/power/wakeup.c (ffffffff816ef515)
Location: drivers/base/power/wakeup.c:976
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
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
In drivers/base/power/wakeup.c (ffffffff81712d65)
Location: drivers/base/power/wakeup.c:996
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817ce9d0)
Location: drivers/base/power/wakeup.c:1055
Inline: True
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_next
```
**Symbols:**

```
ffffffff817ce9d0-ffffffff817ceb25: print_wakeup_source_stats.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817e3090)
Location: drivers/base/power/wakeup.c:1055
Inline: True
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_next
```
**Symbols:**

```
ffffffff817e3090-ffffffff817e31e5: print_wakeup_source_stats.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff817c7450)
Location: drivers/base/power/wakeup.c:1056
Inline: True
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_next
```
**Symbols:**

```
ffffffff817c7450-ffffffff817c75a5: print_wakeup_source_stats.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81851830)
Location: drivers/base/power/wakeup.c:1083
Inline: True
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_next
```
**Symbols:**

```
ffffffff81851830-ffffffff81851985: print_wakeup_source_stats.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81997570)
Location: drivers/base/power/wakeup.c:1084
Inline: True
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_next
```
**Symbols:**

```
ffffffff81997570-ffffffff819976df: print_wakeup_source_stats.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff81b08570)
Location: drivers/base/power/wakeup.c:1056
Inline: True
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_next
```
**Symbols:**

```
ffffffff81b08570-ffffffff81b086df: print_wakeup_source_stats.isra.0 (STB_LOCAL)
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
In drivers/base/power/wakeup.c (ffffffff81b565a0)
Location: drivers/base/power/wakeup.c:1051
Inline: True
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_next
```
**Symbols:**

```
ffffffff81b565a0-ffffffff81b5670f: print_wakeup_source_stats.isra.0 (STB_LOCAL)
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
In drivers/base/power/wakeup.c (ffffffff81baeb90)
Location: drivers/base/power/wakeup.c:1051
Inline: True
Direct callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_next
```
**Symbols:**

```
ffffffff81baeb90-ffffffff81baecff: print_wakeup_source_stats.isra.0 (STB_LOCAL)
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
In drivers/base/power/wakeup.c (ffff800010903e34)
Location: drivers/base/power/wakeup.c:996
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
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
In drivers/base/power/wakeup.c (c09ee750)
Location: drivers/base/power/wakeup.c:996
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
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
In drivers/base/power/wakeup.c (c0000000009a21f8)
Location: drivers/base/power/wakeup.c:996
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/power/wakeup.c (ffffffff816d90e5)
Location: drivers/base/power/wakeup.c:996
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
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
In drivers/base/power/wakeup.c (ffffffff816b3725)
Location: drivers/base/power/wakeup.c:996
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
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
In drivers/base/power/wakeup.c (ffffffff81706a25)
Location: drivers/base/power/wakeup.c:996
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
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
In drivers/base/power/wakeup.c (ffffffff81721435)
Location: drivers/base/power/wakeup.c:996
Inline: True
Inline callers:
  - drivers/base/power/wakeup.c:wakeup_sources_stats_seq_show
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
</ul>
