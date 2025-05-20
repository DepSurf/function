# Function: <code>smaps_account</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void smaps_account(struct mem_size_stats *mss, struct page *page, long unsigned int size, bool young, bool dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81276920)
Location: fs/proc/task_mmu.c:450
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81276920-ffffffff812769b0: smaps_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void smaps_account(struct mem_size_stats *mss, struct page *page, bool compound, bool young, bool dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff812a44e0)
Location: fs/proc/task_mmu.c:463
Inline: False
```
**Symbols:**

```
ffffffff812a44e0-ffffffff812a46ad: smaps_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void smaps_account(struct mem_size_stats *mss, struct page *page, bool compound, bool young, bool dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff812b9e40)
Location: fs/proc/task_mmu.c:456
Inline: False
```
**Symbols:**

```
ffffffff812b9e40-ffffffff812ba00d: smaps_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void smaps_account(struct mem_size_stats *mss, struct page *page, bool compound, bool young, bool dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff812c7530)
Location: fs/proc/task_mmu.c:454
Inline: False
```
**Symbols:**

```
ffffffff812c7530-ffffffff812c7745: smaps_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void smaps_account(struct mem_size_stats *mss, struct page *page, bool compound, bool young, bool dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff812eae10)
Location: fs/proc/task_mmu.c:460
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff812eae10-ffffffff812eb026: smaps_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void smaps_account(struct mem_size_stats *mss, struct page *page, bool compound, bool young, bool dirty);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81318460)
Location: fs/proc/task_mmu.c:460
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81318460-ffffffff8131867f: smaps_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void smaps_account(struct mem_size_stats *mss, struct page *page, bool compound, bool young, bool dirty, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8132f330)
Location: fs/proc/task_mmu.c:428
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8132f330-ffffffff8132f582: smaps_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void smaps_account(struct mem_size_stats *mss, struct page *page, bool compound, bool young, bool dirty, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81356e10)
Location: fs/proc/task_mmu.c:464
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81356e10-ffffffff81356fd8: smaps_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void smaps_account(struct mem_size_stats *mss, struct page *page, bool compound, bool young, bool dirty, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8136f3e0)
Location: fs/proc/task_mmu.c:465
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8136f3e0-ffffffff8136f5b0: smaps_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void smaps_account(struct mem_size_stats *mss, struct page *page, bool compound, bool young, bool dirty, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813b6ab0)
Location: fs/proc/task_mmu.c:435
Inline: False
```
**Symbols:**

```
ffffffff813b6ab0-ffffffff813b6c77: smaps_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void smaps_account(struct mem_size_stats *mss, struct page *page, bool compound, bool young, bool dirty, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813c8150)
Location: fs/proc/task_mmu.c:435
Inline: False
```
**Symbols:**

```
ffffffff813c8150-ffffffff813c8307: smaps_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void smaps_account(struct mem_size_stats *mss, struct page *page, bool compound, bool young, bool dirty, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813cf290)
Location: fs/proc/task_mmu.c:432
Inline: False
```
**Symbols:**

```
ffffffff813cf290-ffffffff813cf44c: smaps_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void smaps_account(struct mem_size_stats *mss, struct page *page, bool compound, bool young, bool dirty, bool locked, bool migration);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81420650)
Location: fs/proc/task_mmu.c:435
Inline: False
```
**Symbols:**

```
ffffffff81420650-ffffffff81420821: smaps_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void smaps_account(struct mem_size_stats *mss, struct page *page, bool compound, bool young, bool dirty, bool locked, bool migration);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81499cc0)
Location: fs/proc/task_mmu.c:445
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_entry
```
**Symbols:**

```
ffffffff81499cc0-ffffffff8149a075: smaps_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void smaps_account(struct mem_size_stats *mss, struct page *page, bool compound, bool young, bool dirty, bool locked, bool migration);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8152df10)
Location: fs/proc/task_mmu.c:457
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_entry
```
**Symbols:**

```
ffffffff8152df10-ffffffff8152e311: smaps_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void smaps_account(struct mem_size_stats *mss, struct page *page, bool compound, bool young, bool dirty, bool locked, bool migration);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81566280)
Location: fs/proc/task_mmu.c:454
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_entry
```
**Symbols:**

```
ffffffff81566280-ffffffff81566649: smaps_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void smaps_account(struct mem_size_stats *mss, struct page *page, bool compound, bool young, bool dirty, bool locked, bool migration);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff8159e290)
Location: fs/proc/task_mmu.c:443
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_entry
```
**Symbols:**

```
ffffffff8159e290-ffffffff8159e69d: smaps_account (STB_LOCAL)
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
void smaps_account(struct mem_size_stats *mss, struct page *page, bool compound, bool young, bool dirty, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffff800010438aa0)
Location: fs/proc/task_mmu.c:465
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffff800010438aa0-ffff800010438c9c: smaps_account (STB_LOCAL)
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
In fs/proc/task_mmu.c (c0600a8c)
Location: fs/proc/task_mmu.c:465
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_entry
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void smaps_account(struct mem_size_stats *mss, struct page *page, bool compound, bool young, bool dirty, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (c00000000054c2a0)
Location: fs/proc/task_mmu.c:465
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
c00000000054c2a0-c00000000054c55c: smaps_account (STB_LOCAL)
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
In fs/proc/task_mmu.c (ffffffe0002d319e)
Location: fs/proc/task_mmu.c:465
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_pte_range
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
void smaps_account(struct mem_size_stats *mss, struct page *page, bool compound, bool young, bool dirty, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff813679c0)
Location: fs/proc/task_mmu.c:465
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff813679c0-ffffffff81367b90: smaps_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void smaps_account(struct mem_size_stats *mss, struct page *page, bool compound, bool young, bool dirty, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81358660)
Location: fs/proc/task_mmu.c:465
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81358660-ffffffff81358830: smaps_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void smaps_account(struct mem_size_stats *mss, struct page *page, bool compound, bool young, bool dirty, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81365490)
Location: fs/proc/task_mmu.c:465
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81365490-ffffffff81365660: smaps_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void smaps_account(struct mem_size_stats *mss, struct page *page, bool compound, bool young, bool dirty, bool locked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/task_mmu.c (ffffffff81378b70)
Location: fs/proc/task_mmu.c:465
Inline: False
```
**Symbols:**

```
ffffffff81378b70-ffffffff81378d40: smaps_account (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool compound</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int size</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool locked</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool migration</code>
</li>
</ul>
</details>
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
