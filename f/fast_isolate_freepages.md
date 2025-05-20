# Function: <code>fast_isolate_freepages</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int fast_isolate_freepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81244b10)
Location: mm/compaction.c:1274
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
```
**Symbols:**

```
ffffffff81244b10-ffffffff812451fe: fast_isolate_freepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int fast_isolate_freepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81252fd0)
Location: mm/compaction.c:1275
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
```
**Symbols:**

```
ffffffff81252fd0-ffffffff812536be: fast_isolate_freepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int fast_isolate_freepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81281ca0)
Location: mm/compaction.c:1280
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages
```
**Symbols:**

```
ffffffff81281ca0-ffffffff812823bc: fast_isolate_freepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int fast_isolate_freepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8128bdd0)
Location: mm/compaction.c:1345
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages
```
**Symbols:**

```
ffffffff8128bdd0-ffffffff8128c51e: fast_isolate_freepages (STB_LOCAL)
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
In mm/compaction.c (ffffffff81290c90)
Location: mm/compaction.c:1381
Inline: True
Direct callers:
  - mm/compaction.c:isolate_freepages
```
**Symbols:**

```
ffffffff81290c90-ffffffff812913db: fast_isolate_freepages.isra.0 (STB_LOCAL)
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
In mm/compaction.c (0)
Location: mm/compaction.c:1373
Inline: True
Direct callers:
  - mm/compaction.c:isolate_freepages
```
**Symbols:**

```
ffffffff812d25f0-ffffffff812d2d16: fast_isolate_freepages.isra.0 (STB_LOCAL)
ffffffff81cbba0d-ffffffff81cbba8e: fast_isolate_freepages.isra.0.cold (STB_LOCAL)
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
In mm/compaction.c (0)
Location: mm/compaction.c:1406
Inline: True
Direct callers:
  - mm/compaction.c:isolate_freepages
```
**Symbols:**

```
ffffffff8132f650-ffffffff8132fe6f: fast_isolate_freepages.isra.0 (STB_LOCAL)
ffffffff81e6d3a2-ffffffff81e6d42b: fast_isolate_freepages.isra.0.cold (STB_LOCAL)
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
In mm/compaction.c (0)
Location: mm/compaction.c:1396
Inline: True
Direct callers:
  - mm/compaction.c:isolate_freepages
```
**Symbols:**

```
ffffffff813a6260-ffffffff813a6a2c: fast_isolate_freepages.isra.0 (STB_LOCAL)
ffffffff820636f8-ffffffff82063783: fast_isolate_freepages.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void fast_isolate_freepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:1448
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages
```
**Symbols:**

```
ffffffff813d9a20-ffffffff813da24c: fast_isolate_freepages (STB_LOCAL)
ffffffff820e2dee-ffffffff820e2e81: fast_isolate_freepages.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void fast_isolate_freepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/compaction.c (0)
Location: mm/compaction.c:1486
Inline: False
Direct callers:
  - mm/compaction.c:isolate_freepages
```
**Symbols:**

```
ffffffff81403750-ffffffff81404033: fast_isolate_freepages (STB_LOCAL)
ffffffff821bf7fb-ffffffff821bf8a2: fast_isolate_freepages.cold (STB_LOCAL)
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
long unsigned int fast_isolate_freepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffff8000102ea518)
Location: mm/compaction.c:1275
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
```
**Symbols:**

```
ffff8000102ea518-ffff8000102eab80: fast_isolate_freepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int fast_isolate_freepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c050dd44)
Location: mm/compaction.c:1275
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
```
**Symbols:**

```
c050dd44-c050e49c: fast_isolate_freepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int fast_isolate_freepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (c0000000003ad1e0)
Location: mm/compaction.c:1275
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
```
**Symbols:**

```
c0000000003ad1e0-c0000000003ad9d0: fast_isolate_freepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long unsigned int fast_isolate_freepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffe0001fec98)
Location: mm/compaction.c:1275
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
```
**Symbols:**

```
ffffffe0001fec98-ffffffe0001ff146: fast_isolate_freepages (STB_LOCAL)
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
long unsigned int fast_isolate_freepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8124b620)
Location: mm/compaction.c:1275
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
```
**Symbols:**

```
ffffffff8124b620-ffffffff8124bd0e: fast_isolate_freepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long unsigned int fast_isolate_freepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff8123e5c0)
Location: mm/compaction.c:1275
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
```
**Symbols:**

```
ffffffff8123e5c0-ffffffff8123ecae: fast_isolate_freepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int fast_isolate_freepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff812493c0)
Location: mm/compaction.c:1275
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
```
**Symbols:**

```
ffffffff812493c0-ffffffff81249aae: fast_isolate_freepages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int fast_isolate_freepages(struct compact_control *cc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/compaction.c (ffffffff81258c40)
Location: mm/compaction.c:1275
Inline: False
Direct callers:
  - mm/compaction.c:compaction_alloc
```
**Symbols:**

```
ffffffff81258c40-ffffffff8125932e: fast_isolate_freepages (STB_LOCAL)
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
