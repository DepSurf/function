# Function: <code>mem_cgroup_move_account</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mem_cgroup_move_account(struct page *page, unsigned int nr_pages, struct mem_cgroup *from, struct mem_cgroup *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811fd270)
Location: mm/memcontrol.c:4541
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffff811fd270-ffffffff811fd43d: mem_cgroup_move_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mem_cgroup_move_account(struct page *page, bool compound, struct mem_cgroup *from, struct mem_cgroup *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81220d30)
Location: mm/memcontrol.c:4497
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffff81220d30-ffffffff81220f7e: mem_cgroup_move_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mem_cgroup_move_account(struct page *page, bool compound, struct mem_cgroup *from, struct mem_cgroup *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81233480)
Location: mm/memcontrol.c:4480
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffff81233480-ffffffff812336ce: mem_cgroup_move_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mem_cgroup_move_account(struct page *page, bool compound, struct mem_cgroup *from, struct mem_cgroup *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8123ed60)
Location: mm/memcontrol.c:4509
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffff8123ed60-ffffffff8123ef86: mem_cgroup_move_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mem_cgroup_move_account(struct page *page, bool compound, struct mem_cgroup *from, struct mem_cgroup *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8125e8e0)
Location: mm/memcontrol.c:4556
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffff8125e8e0-ffffffff8125eb15: mem_cgroup_move_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mem_cgroup_move_account(struct page *page, bool compound, struct mem_cgroup *from, struct mem_cgroup *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81282ae0)
Location: mm/memcontrol.c:4495
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffff81282ae0-ffffffff81282e83: mem_cgroup_move_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mem_cgroup_move_account(struct page *page, bool compound, struct mem_cgroup *from, struct mem_cgroup *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81296c80)
Location: mm/memcontrol.c:4781
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffff81296c80-ffffffff8129702f: mem_cgroup_move_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mem_cgroup_move_account(struct page *page, bool compound, struct mem_cgroup *from, struct mem_cgroup *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b29f0)
Location: mm/memcontrol.c:5143
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffff812b29f0-ffffffff812b2c64: mem_cgroup_move_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mem_cgroup_move_account(struct page *page, bool compound, struct mem_cgroup *from, struct mem_cgroup *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c4430)
Location: mm/memcontrol.c:5477
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffff812c4430-ffffffff812c473a: mem_cgroup_move_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mem_cgroup_move_account(struct page *page, bool compound, struct mem_cgroup *from, struct mem_cgroup *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fa300)
Location: mm/memcontrol.c:5361
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffff812fa300-ffffffff812fa6c1: mem_cgroup_move_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mem_cgroup_move_account(struct page *page, bool compound, struct mem_cgroup *from, struct mem_cgroup *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81306200)
Location: mm/memcontrol.c:5596
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffff81306200-ffffffff8130666f: mem_cgroup_move_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mem_cgroup_move_account(struct page *page, bool compound, struct mem_cgroup *from, struct mem_cgroup *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130c6d0)
Location: mm/memcontrol.c:5417
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffff8130c6d0-ffffffff8130cb54: mem_cgroup_move_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mem_cgroup_move_account(struct page *page, bool compound, struct mem_cgroup *from, struct mem_cgroup *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813578d0)
Location: mm/memcontrol.c:5601
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffff813578d0-ffffffff81357d5b: mem_cgroup_move_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mem_cgroup_move_account(struct page *page, bool compound, struct mem_cgroup *from, struct mem_cgroup *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d0630)
Location: mm/memcontrol.c:5541
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffff813d0630-ffffffff813d0a9f: mem_cgroup_move_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mem_cgroup_move_account(struct page *page, bool compound, struct mem_cgroup *from, struct mem_cgroup *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81455d10)
Location: mm/memcontrol.c:5699
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffff81455d10-ffffffff81456240: mem_cgroup_move_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mem_cgroup_move_account(struct page *page, bool compound, struct mem_cgroup *from, struct mem_cgroup *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148ce00)
Location: mm/memcontrol.c:5739
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffff8148ce00-ffffffff8148d318: mem_cgroup_move_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mem_cgroup_move_account(struct page *page, bool compound, struct mem_cgroup *from, struct mem_cgroup *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bc740)
Location: mm/memcontrol.c:5979
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffff814bc740-ffffffff814bcc53: mem_cgroup_move_account (STB_LOCAL)
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
int mem_cgroup_move_account(struct page *page, bool compound, struct mem_cgroup *from, struct mem_cgroup *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010367008)
Location: mm/memcontrol.c:5477
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffff800010367008-ffff800010367368: mem_cgroup_move_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (c05587c8)
Location: mm/memcontrol.c:5477
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
c05587c8-c0558a8c: mem_cgroup_move_account.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mem_cgroup_move_account(struct page *page, bool compound, struct mem_cgroup *from, struct mem_cgroup *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000454470)
Location: mm/memcontrol.c:5477
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
c000000000454470-c000000000454858: mem_cgroup_move_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memcontrol.c (ffffffe0002452ca)
Location: mm/memcontrol.c:5477
Inline: True
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffe0002452ca-ffffffe000245512: mem_cgroup_move_account.constprop.0 (STB_LOCAL)
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
int mem_cgroup_move_account(struct page *page, bool compound, struct mem_cgroup *from, struct mem_cgroup *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bca10)
Location: mm/memcontrol.c:5477
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffff812bca10-ffffffff812bcd1a: mem_cgroup_move_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mem_cgroup_move_account(struct page *page, bool compound, struct mem_cgroup *from, struct mem_cgroup *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812adb70)
Location: mm/memcontrol.c:5477
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffff812adb70-ffffffff812ade6e: mem_cgroup_move_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mem_cgroup_move_account(struct page *page, bool compound, struct mem_cgroup *from, struct mem_cgroup *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ba820)
Location: mm/memcontrol.c:5477
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffff812ba820-ffffffff812bab2a: mem_cgroup_move_account (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mem_cgroup_move_account(struct page *page, bool compound, struct mem_cgroup *from, struct mem_cgroup *to);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812caf60)
Location: mm/memcontrol.c:5477
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
  - mm/memcontrol.c:mem_cgroup_move_charge_pte_range
```
**Symbols:**

```
ffffffff812caf60-ffffffff812cb26a: mem_cgroup_move_account (STB_LOCAL)
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
<code>unsigned int nr_pages</code>
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
