# Function: <code>zero_pfn_range</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 zero_pfn_range(long unsigned int spfn, long unsigned int epfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8120d529)
Location: mm/page_alloc.c:6679
Inline: False
Direct callers:
  - mm/page_alloc.c:zero_resv_unavail
  - mm/page_alloc.c:zero_resv_unavail
```
**Symbols:**

```
ffffffff8120d529-ffffffff8120d59c: zero_pfn_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 zero_pfn_range(long unsigned int spfn, long unsigned int epfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812738d1)
Location: mm/page_alloc.c:6875
Inline: False
Direct callers:
  - mm/page_alloc.c:zero_resv_unavail
  - mm/page_alloc.c:zero_resv_unavail
```
**Symbols:**

```
ffffffff812738d1-ffffffff8127396f: zero_pfn_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 zero_pfn_range(long unsigned int spfn, long unsigned int epfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81282741)
Location: mm/page_alloc.c:6895
Inline: False
Direct callers:
  - mm/page_alloc.c:zero_resv_unavail
  - mm/page_alloc.c:zero_resv_unavail
```
**Symbols:**

```
ffffffff81282741-ffffffff812827df: zero_pfn_range (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
u64 zero_pfn_range(long unsigned int spfn, long unsigned int epfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffff80001031b084)
Location: mm/page_alloc.c:6895
Inline: False
Direct callers:
  - mm/page_alloc.c:zero_resv_unavail
  - mm/page_alloc.c:zero_resv_unavail
```
**Symbols:**

```
ffff80001031b084-ffff80001031b114: zero_pfn_range (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 zero_pfn_range(long unsigned int spfn, long unsigned int epfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (c0000000003ee510)
Location: mm/page_alloc.c:6895
Inline: False
Direct callers:
  - mm/page_alloc.c:zero_resv_unavail
  - mm/page_alloc.c:zero_resv_unavail
```
**Symbols:**

```
c0000000003ee510-c0000000003ee60c: zero_pfn_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 zero_pfn_range(long unsigned int spfn, long unsigned int epfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffe0002201dc)
Location: mm/page_alloc.c:6895
Inline: False
Direct callers:
  - mm/page_alloc.c:zero_resv_unavail
  - mm/page_alloc.c:zero_resv_unavail
```
**Symbols:**

```
ffffffe0002201dc-ffffffe00022025e: zero_pfn_range (STB_LOCAL)
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
u64 zero_pfn_range(long unsigned int spfn, long unsigned int epfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8127ad91)
Location: mm/page_alloc.c:6895
Inline: False
Direct callers:
  - mm/page_alloc.c:zero_resv_unavail
  - mm/page_alloc.c:zero_resv_unavail
```
**Symbols:**

```
ffffffff8127ad91-ffffffff8127ae2f: zero_pfn_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 zero_pfn_range(long unsigned int spfn, long unsigned int epfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff8126cc71)
Location: mm/page_alloc.c:6895
Inline: False
Direct callers:
  - mm/page_alloc.c:zero_resv_unavail
  - mm/page_alloc.c:zero_resv_unavail
```
**Symbols:**

```
ffffffff8126cc71-ffffffff8126cd0f: zero_pfn_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 zero_pfn_range(long unsigned int spfn, long unsigned int epfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81278b31)
Location: mm/page_alloc.c:6895
Inline: False
Direct callers:
  - mm/page_alloc.c:zero_resv_unavail
  - mm/page_alloc.c:zero_resv_unavail
```
**Symbols:**

```
ffffffff81278b31-ffffffff81278bcf: zero_pfn_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 zero_pfn_range(long unsigned int spfn, long unsigned int epfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff81288721)
Location: mm/page_alloc.c:6895
Inline: False
Direct callers:
  - mm/page_alloc.c:zero_resv_unavail
  - mm/page_alloc.c:zero_resv_unavail
```
**Symbols:**

```
ffffffff81288721-ffffffff812887bf: zero_pfn_range (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
