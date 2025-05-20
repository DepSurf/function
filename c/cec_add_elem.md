# Function: <code>cec_add_elem</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cec_add_elem(u64 pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/cec.c (ffffffff817a4eb0)
Location: drivers/ras/cec.c:277
Inline: False
Direct callers:
  - drivers/ras/cec.c:pfn_set
```
**Symbols:**

```
ffffffff817a4eb0-ffffffff817a5141: cec_add_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cec_add_elem(u64 pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/cec.c (ffffffff8181c010)
Location: drivers/ras/cec.c:276
Inline: False
Direct callers:
  - drivers/ras/cec.c:pfn_set
```
**Symbols:**

```
ffffffff8181c010-ffffffff8181c2b1: cec_add_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int cec_add_elem(u64 pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:276
Inline: False
Direct callers:
  - drivers/ras/cec.c:pfn_set
```
**Symbols:**

```
ffffffff81866316-ffffffff818663ac: cec_add_elem.cold.7 (STB_LOCAL)
ffffffff81866100-ffffffff818662f8: cec_add_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int cec_add_elem(u64 pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:276
Inline: False
Direct callers:
  - drivers/ras/cec.c:pfn_set
```
**Symbols:**

```
ffffffff81885ee6-ffffffff81885f7c: cec_add_elem.cold.7 (STB_LOCAL)
ffffffff81885cd0-ffffffff81885ec8: cec_add_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cec_add_elem(u64 pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:311
Inline: False
```
**Symbols:**

```
ffffffff818d05c7-ffffffff818d069e: cec_add_elem.cold (STB_LOCAL)
ffffffff818d02c0-ffffffff818d05c7: cec_add_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int cec_add_elem(u64 pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:312
Inline: False
```
**Symbols:**

```
ffffffff819029b7-ffffffff81902a6e: cec_add_elem.cold (STB_LOCAL)
ffffffff819026b0-ffffffff819029b7: cec_add_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int cec_add_elem(u64 pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:312
Inline: False
```
**Symbols:**

```
ffffffff819d9690-ffffffff819d9942: cec_add_elem (STB_LOCAL)
ffffffff819d9a5e-ffffffff819d9aa6: cec_add_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int cec_add_elem(u64 pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:312
Inline: False
```
**Symbols:**

```
ffffffff819d89f0-ffffffff819d8ca0: cec_add_elem (STB_LOCAL)
ffffffff81c300c0-ffffffff81c30108: cec_add_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int cec_add_elem(u64 pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:321
Inline: False
```
**Symbols:**

```
ffffffff819beb60-ffffffff819bedfe: cec_add_elem (STB_LOCAL)
ffffffff81c2232e-ffffffff81c223d6: cec_add_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cec_add_elem(u64 pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:321
Inline: False
```
**Symbols:**

```
ffffffff81a6e0f0-ffffffff81a6e38e: cec_add_elem (STB_LOCAL)
ffffffff81d342d8-ffffffff81d34380: cec_add_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cec_add_elem(u64 pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:321
Inline: False
Direct callers:
  - drivers/ras/cec.c:cec_notifier
```
**Symbols:**

```
ffffffff81bdef30-ffffffff81bdf24a: cec_add_elem (STB_LOCAL)
ffffffff81f006cf-ffffffff81f0076f: cec_add_elem.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cec_add_elem(u64 pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/cec.c (ffffffff81d8a450)
Location: drivers/ras/cec.c:321
Inline: False
Direct callers:
  - drivers/ras/cec.c:cec_notifier
```
**Symbols:**

```
ffffffff81d8a450-ffffffff81d8a7f8: cec_add_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int cec_add_elem(u64 pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/cec.c (ffffffff81df8a50)
Location: drivers/ras/cec.c:321
Inline: False
Direct callers:
  - drivers/ras/cec.c:cec_notifier
```
**Symbols:**

```
ffffffff81df8a50-ffffffff81df8df8: cec_add_elem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int cec_add_elem(u64 pfn);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ras/cec.c (ffffffff81eaf0e0)
Location: drivers/ras/cec.c:321
Inline: False
Direct callers:
  - drivers/ras/cec.c:cec_notifier
```
**Symbols:**

```
ffffffff81eaf0e0-ffffffff81eaf4b8: cec_add_elem (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
int cec_add_elem(u64 pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:312
Inline: False
```
**Symbols:**

```
ffffffff818a1de7-ffffffff818a1e9e: cec_add_elem.cold (STB_LOCAL)
ffffffff818a1ae0-ffffffff818a1de7: cec_add_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int cec_add_elem(u64 pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:312
Inline: False
```
**Symbols:**

```
ffffffff8185d557-ffffffff8185d60e: cec_add_elem.cold (STB_LOCAL)
ffffffff8185d250-ffffffff8185d557: cec_add_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int cec_add_elem(u64 pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:312
Inline: False
```
**Symbols:**

```
ffffffff818f33d7-ffffffff818f348e: cec_add_elem.cold (STB_LOCAL)
ffffffff818f30d0-ffffffff818f33d7: cec_add_elem (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int cec_add_elem(u64 pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ras/cec.c (0)
Location: drivers/ras/cec.c:312
Inline: False
```
**Symbols:**

```
ffffffff81914477-ffffffff8191452e: cec_add_elem.cold (STB_LOCAL)
ffffffff81914170-ffffffff81914477: cec_add_elem (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
