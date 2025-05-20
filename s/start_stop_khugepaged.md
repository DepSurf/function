# Function: <code>start_stop_khugepaged</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int start_stop_khugepaged();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff811f4050)
Location: mm/huge_memory.c:147
Inline: True
Direct callers:
  - mm/huge_memory.c:enabled_store
```
**Symbols:**

```
ffffffff811f4050-ffffffff811f41d9: start_stop_khugepaged (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int start_stop_khugepaged();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8121ccb0)
Location: mm/khugepaged.c:1894
Inline: False
Direct callers:
  - mm/huge_memory.c:enabled_store
```
**Symbols:**

```
ffffffff8121ccb0-ffffffff8121ce4b: start_stop_khugepaged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int start_stop_khugepaged();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8122f2b0)
Location: mm/khugepaged.c:1902
Inline: False
Direct callers:
  - mm/huge_memory.c:enabled_store
```
**Symbols:**

```
ffffffff8122f2b0-ffffffff8122f44b: start_stop_khugepaged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int start_stop_khugepaged();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8123ab10)
Location: mm/khugepaged.c:1903
Inline: False
Direct callers:
  - mm/huge_memory.c:enabled_store
```
**Symbols:**

```
ffffffff8123ab10-ffffffff8123acad: start_stop_khugepaged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int start_stop_khugepaged();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8125a3a0)
Location: mm/khugepaged.c:1909
Inline: False
Direct callers:
  - mm/huge_memory.c:enabled_store
```
**Symbols:**

```
ffffffff8125a3a0-ffffffff8125a53d: start_stop_khugepaged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int start_stop_khugepaged();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:1917
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:enabled_store
```
**Symbols:**

```
ffffffff8127e240-ffffffff8127e27e: start_stop_khugepaged.cold.44 (STB_LOCAL)
ffffffff8127e0c0-ffffffff8127e240: start_stop_khugepaged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int start_stop_khugepaged();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:1906
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:enabled_store
```
**Symbols:**

```
ffffffff81292923-ffffffff81292961: start_stop_khugepaged.cold.45 (STB_LOCAL)
ffffffff812927a0-ffffffff81292923: start_stop_khugepaged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int start_stop_khugepaged();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:1912
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:enabled_store
```
**Symbols:**

```
ffffffff812ad2ff-ffffffff812ad33e: start_stop_khugepaged.cold (STB_LOCAL)
ffffffff812ad170-ffffffff812ad2ff: start_stop_khugepaged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int start_stop_khugepaged();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:2167
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:enabled_store
```
**Symbols:**

```
ffffffff812bee4f-ffffffff812bee8e: start_stop_khugepaged.cold (STB_LOCAL)
ffffffff812becc0-ffffffff812bee4f: start_stop_khugepaged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int start_stop_khugepaged();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:2293
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:enabled_store
```
**Symbols:**

```
ffffffff812f4149-ffffffff812f416c: start_stop_khugepaged.cold (STB_LOCAL)
ffffffff812f4050-ffffffff812f412d: start_stop_khugepaged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int start_stop_khugepaged();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:2330
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:enabled_store
```
**Symbols:**

```
ffffffff81be9b79-ffffffff81be9b9c: start_stop_khugepaged.cold (STB_LOCAL)
ffffffff812ff940-ffffffff812ffa1d: start_stop_khugepaged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int start_stop_khugepaged();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:2318
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:enabled_store
```
**Symbols:**

```
ffffffff81bdbb95-ffffffff81bdbbb8: start_stop_khugepaged.cold (STB_LOCAL)
ffffffff813065e0-ffffffff813066bd: start_stop_khugepaged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int start_stop_khugepaged();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:2340
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:enabled_store
```
**Symbols:**

```
ffffffff81cc26ae-ffffffff81cc26d1: start_stop_khugepaged.cold (STB_LOCAL)
ffffffff81350410-ffffffff813504ed: start_stop_khugepaged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int start_stop_khugepaged();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff813c8680)
Location: mm/khugepaged.c:2360
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:enabled_store
```
**Symbols:**

```
ffffffff813c8680-ffffffff813c8783: start_stop_khugepaged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int start_stop_khugepaged();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8144c810)
Location: mm/khugepaged.c:2560
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:enabled_store
```
**Symbols:**

```
ffffffff8144c810-ffffffff8144c915: start_stop_khugepaged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int start_stop_khugepaged();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff814820c0)
Location: mm/khugepaged.c:2749
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:enabled_store
```
**Symbols:**

```
ffffffff814820c0-ffffffff814821c5: start_stop_khugepaged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int start_stop_khugepaged();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff814b1410)
Location: mm/khugepaged.c:2628
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:enabled_store
```
**Symbols:**

```
ffffffff814b1410-ffffffff814b1522: start_stop_khugepaged (STB_GLOBAL)
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
int start_stop_khugepaged();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffff800010360310)
Location: mm/khugepaged.c:2167
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:enabled_store
```
**Symbols:**

```
ffff800010360310-ffff8000103604d8: start_stop_khugepaged (STB_GLOBAL)
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
int start_stop_khugepaged();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (c00000000044b7f0)
Location: mm/khugepaged.c:2167
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:enabled_store
```
**Symbols:**

```
c00000000044b7f0-c00000000044baac: start_stop_khugepaged (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int start_stop_khugepaged();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:2167
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:enabled_store
```
**Symbols:**

```
ffffffff812b742f-ffffffff812b746e: start_stop_khugepaged.cold (STB_LOCAL)
ffffffff812b72a0-ffffffff812b742f: start_stop_khugepaged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int start_stop_khugepaged();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:2167
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:enabled_store
```
**Symbols:**

```
ffffffff812a85ff-ffffffff812a863e: start_stop_khugepaged.cold (STB_LOCAL)
ffffffff812a8470-ffffffff812a85ff: start_stop_khugepaged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int start_stop_khugepaged();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:2167
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:enabled_store
```
**Symbols:**

```
ffffffff812b523f-ffffffff812b527e: start_stop_khugepaged.cold (STB_LOCAL)
ffffffff812b50b0-ffffffff812b523f: start_stop_khugepaged (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int start_stop_khugepaged();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:2167
Inline: False
Direct callers:
  - mm/huge_memory.c:hugepage_init
  - mm/huge_memory.c:enabled_store
```
**Symbols:**

```
ffffffff812c577f-ffffffff812c57be: start_stop_khugepaged.cold (STB_LOCAL)
ffffffff812c55f0-ffffffff812c577f: start_stop_khugepaged (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
