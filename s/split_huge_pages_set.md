# Function: <code>split_huge_pages_set</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int split_huge_pages_set(void *data, u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81218520)
Location: mm/huge_memory.c:2197
Inline: True
```
**Symbols:**

```
ffffffff81218520-ffffffff812186e5: split_huge_pages_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int split_huge_pages_set(void *data, u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8122aab0)
Location: mm/huge_memory.c:2328
Inline: True
```
**Symbols:**

```
ffffffff8122aab0-ffffffff8122ac81: split_huge_pages_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int split_huge_pages_set(void *data, u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81236660)
Location: mm/huge_memory.c:2663
Inline: True
```
**Symbols:**

```
ffffffff81236660-ffffffff81236817: split_huge_pages_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int split_huge_pages_set(void *data, u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81255620)
Location: mm/huge_memory.c:2825
Inline: True
```
**Symbols:**

```
ffffffff81255620-ffffffff812557ef: split_huge_pages_set (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int split_huge_pages_set(void *data, u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (0)
Location: mm/huge_memory.c:2817
Inline: True
```
**Symbols:**

```
ffffffff81279470-ffffffff8127968b: split_huge_pages_set (STB_LOCAL)
ffffffff81279bf1-ffffffff81279c12: split_huge_pages_set.cold.77 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int split_huge_pages_set(void *data, u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (ffffffff8128db01)
Location: mm/huge_memory.c:2844
Inline: True
```
**Symbols:**

```
ffffffff8128daf0-ffffffff8128dd10: split_huge_pages_set (STB_LOCAL)
ffffffff8128e1f1-ffffffff8128e212: split_huge_pages_set.cold.75 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int split_huge_pages_set(void *data, u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (ffffffff812a8491)
Location: mm/huge_memory.c:2905
Inline: True
```
**Symbols:**

```
ffffffff812a8480-ffffffff812a868d: split_huge_pages_set (STB_LOCAL)
ffffffff812a8b8d-ffffffff812a8bae: split_huge_pages_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int split_huge_pages_set(void *data, u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (ffffffff812b9971)
Location: mm/huge_memory.c:2968
Inline: True
```
**Symbols:**

```
ffffffff812b9960-ffffffff812b9b6d: split_huge_pages_set (STB_LOCAL)
ffffffff812ba0f8-ffffffff812ba119: split_huge_pages_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int split_huge_pages_set(void *data, u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (ffffffff812ee6f0)
Location: mm/huge_memory.c:2872
Inline: True
```
**Symbols:**

```
ffffffff812ee6f0-ffffffff812ee70c: split_huge_pages_set (STB_LOCAL)
ffffffff812ee4c0-ffffffff812ee6f0: split_huge_pages_set.part.0 (STB_LOCAL)
ffffffff812eecd7-ffffffff812eed0a: split_huge_pages_set.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int split_huge_pages_set(void *data, u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (ffffffff812f9d60)
Location: mm/huge_memory.c:2921
Inline: True
```
**Symbols:**

```
ffffffff812f9d60-ffffffff812f9d7c: split_huge_pages_set (STB_LOCAL)
ffffffff812f9b30-ffffffff812f9d60: split_huge_pages_set.part.0 (STB_LOCAL)
ffffffff81be9b2a-ffffffff81be9b5d: split_huge_pages_set.part.0.cold (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int split_huge_pages_set(void *data, u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (ffff80001035a0c0)
Location: mm/huge_memory.c:2968
Inline: True
```
**Symbols:**

```
ffff80001035a340-ffff80001035a378: split_huge_pages_set (STB_LOCAL)
ffff80001035a0c0-ffff80001035a340: split_huge_pages_set.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int split_huge_pages_set(void *data, u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c000000000443ad0)
Location: mm/huge_memory.c:2968
Inline: True
```
**Symbols:**

```
c000000000443ad0-c000000000443e40: split_huge_pages_set (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int split_huge_pages_set(void *data, u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (ffffffff812b1f51)
Location: mm/huge_memory.c:2968
Inline: True
```
**Symbols:**

```
ffffffff812b1f40-ffffffff812b214d: split_huge_pages_set (STB_LOCAL)
ffffffff812b26d8-ffffffff812b26f9: split_huge_pages_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int split_huge_pages_set(void *data, u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (ffffffff812a32e1)
Location: mm/huge_memory.c:2968
Inline: True
```
**Symbols:**

```
ffffffff812a32d0-ffffffff812a34dd: split_huge_pages_set (STB_LOCAL)
ffffffff812a3a57-ffffffff812a3a78: split_huge_pages_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int split_huge_pages_set(void *data, u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (ffffffff812afd61)
Location: mm/huge_memory.c:2968
Inline: True
```
**Symbols:**

```
ffffffff812afd50-ffffffff812aff5d: split_huge_pages_set (STB_LOCAL)
ffffffff812b04e8-ffffffff812b0509: split_huge_pages_set.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int split_huge_pages_set(void *data, u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (ffffffff812c00a1)
Location: mm/huge_memory.c:2968
Inline: True
```
**Symbols:**

```
ffffffff812c0090-ffffffff812c0298: split_huge_pages_set (STB_LOCAL)
ffffffff812c0828-ffffffff812c0849: split_huge_pages_set.cold (STB_LOCAL)
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
