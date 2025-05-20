# Function: <code>kcompactd_run</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kcompactd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811d2570)
Location: mm/compaction.c:2016
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff811d2570-ffffffff811d260e: kcompactd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kcompactd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811e2430)
Location: mm/compaction.c:2001
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff811e2430-ffffffff811e24ce: kcompactd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kcompactd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff811ec250)
Location: mm/compaction.c:2057
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff811ec250-ffffffff811ec2f8: kcompactd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kcompactd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812025c0)
Location: mm/compaction.c:2077
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff812025c0-ffffffff81202668: kcompactd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kcompactd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81223970)
Location: mm/compaction.c:2085
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81223970-ffffffff81223a0e: kcompactd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kcompactd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812369d0)
Location: mm/compaction.c:2090
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff812369d0-ffffffff81236a6e: kcompactd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int kcompactd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2671
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81247fbc-ffffffff81247fe9: kcompactd_run.cold (STB_LOCAL)
ffffffff81247f00-ffffffff81247f7f: kcompactd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int kcompactd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2662
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff8125641c-ffffffff81256449: kcompactd_run.cold (STB_LOCAL)
ffffffff81256360-ffffffff812563df: kcompactd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int kcompactd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2679
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81284abf-ffffffff81284aec: kcompactd_run.cold (STB_LOCAL)
ffffffff81284a00-ffffffff81284a7f: kcompactd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int kcompactd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2898
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81be7435-ffffffff81be7462: kcompactd_run.cold (STB_LOCAL)
ffffffff8128ed10-ffffffff8128ed8f: kcompactd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int kcompactd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2943
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81bd92fb-ffffffff81bd9328: kcompactd_run.cold (STB_LOCAL)
ffffffff81294390-ffffffff8129440f: kcompactd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int kcompactd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2978
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81cbbc6a-ffffffff81cbbc97: kcompactd_run.cold (STB_LOCAL)
ffffffff812d49d0-ffffffff812d4a4f: kcompactd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void kcompactd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2998
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81e6d835-ffffffff81e6d85a: kcompactd_run.cold (STB_LOCAL)
ffffffff81333a30-ffffffff81333ac4: kcompactd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kcompactd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff813aa770)
Location: mm/compaction.c:2997
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff813aa770-ffffffff813aa827: kcompactd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kcompactd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8214c320)
Location: mm/compaction.c:3092
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff8214c320-ffffffff8214c3d2: kcompactd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kcompactd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8222eea0)
Location: mm/compaction.c:3151
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff8222eea0-ffffffff8222ef52: kcompactd_run (STB_GLOBAL)
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
int kcompactd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffff8000102ed9c0)
Location: mm/compaction.c:2662
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffff8000102ed9c0-ffff8000102eda6c: kcompactd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int kcompactd_run(int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c0511968)
Location: mm/compaction.c:2662
Inline: True
Direct callers:
  - mm/compaction.c:kcompactd_init
```
**Symbols:**

```
c0511968-c0511a04: kcompactd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int kcompactd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c0000000003b18b0)
Location: mm/compaction.c:2662
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
c0000000003b18b0-c0000000003b19ac: kcompactd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int kcompactd_run(int nid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffe000201e8a)
Location: mm/compaction.c:2662
Inline: True
Direct callers:
  - mm/compaction.c:kcompactd_init
```
**Symbols:**

```
ffffffe000201e8a-ffffffe000201f2e: kcompactd_run (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int kcompactd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2662
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff8124ea6c-ffffffff8124ea99: kcompactd_run.cold (STB_LOCAL)
ffffffff8124e9b0-ffffffff8124ea2f: kcompactd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int kcompactd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2662
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff81241a0c-ffffffff81241a39: kcompactd_run.cold (STB_LOCAL)
ffffffff81241950-ffffffff812419cf: kcompactd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int kcompactd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2662
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff8124c80c-ffffffff8124c839: kcompactd_run.cold (STB_LOCAL)
ffffffff8124c750-ffffffff8124c7cf: kcompactd_run (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int kcompactd_run(int nid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:2662
Inline: False
Direct callers:
  - mm/compaction.c:kcompactd_init
  - mm/memory_hotplug.c:online_pages
```
**Symbols:**

```
ffffffff8125c1cc-ffffffff8125c1f9: kcompactd_run.cold (STB_LOCAL)
ffffffff8125c110-ffffffff8125c18f: kcompactd_run (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
