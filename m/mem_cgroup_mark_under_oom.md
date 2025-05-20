# Function: <code>mem_cgroup_mark_under_oom</code>

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
In mm/memcontrol.c (ffffffff811ff513)
Location: mm/memcontrol.c:1625
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
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
In mm/memcontrol.c (ffffffff81223291)
Location: mm/memcontrol.c:1490
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
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
In mm/memcontrol.c (ffffffff8123578b)
Location: mm/memcontrol.c:1461
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
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
In mm/memcontrol.c (ffffffff81241197)
Location: mm/memcontrol.c:1453
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
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
In mm/memcontrol.c (ffffffff81260ed7)
Location: mm/memcontrol.c:1467
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
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
In mm/memcontrol.c (ffffffff81284eb8)
Location: mm/memcontrol.c:1424
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mem_cgroup_mark_under_oom(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81298110)
Location: mm/memcontrol.c:1605
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff81298110-ffffffff81298164: mem_cgroup_mark_under_oom (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mem_cgroup_mark_under_oom(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b33f0)
Location: mm/memcontrol.c:1806
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812b33f0-ffffffff812b3447: mem_cgroup_mark_under_oom (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mem_cgroup_mark_under_oom(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c4ec0)
Location: mm/memcontrol.c:1822
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812c4ec0-ffffffff812c4f17: mem_cgroup_mark_under_oom (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mem_cgroup_mark_under_oom(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fa990)
Location: mm/memcontrol.c:1688
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812fa990-ffffffff812fa9ea: mem_cgroup_mark_under_oom (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mem_cgroup_mark_under_oom(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81306940)
Location: mm/memcontrol.c:1877
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff81306940-ffffffff8130699a: mem_cgroup_mark_under_oom (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mem_cgroup_mark_under_oom(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130d160)
Location: mm/memcontrol.c:1700
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff8130d160-ffffffff8130d1ba: mem_cgroup_mark_under_oom (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mem_cgroup_mark_under_oom(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81358010)
Location: mm/memcontrol.c:1752
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff81358010-ffffffff8135806a: mem_cgroup_mark_under_oom (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mem_cgroup_mark_under_oom(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d1150)
Location: mm/memcontrol.c:1769
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff813d1150-ffffffff813d11b4: mem_cgroup_mark_under_oom (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mem_cgroup_mark_under_oom(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81456550)
Location: mm/memcontrol.c:1829
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff81456550-ffffffff814565b4: mem_cgroup_mark_under_oom (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mem_cgroup_mark_under_oom(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148bde0)
Location: mm/memcontrol.c:1863
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff8148bde0-ffffffff8148be44: mem_cgroup_mark_under_oom (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mem_cgroup_mark_under_oom(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bb730)
Location: mm/memcontrol.c:1935
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff814bb730-ffffffff814bb794: mem_cgroup_mark_under_oom (STB_LOCAL)
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
void mem_cgroup_mark_under_oom(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010367b08)
Location: mm/memcontrol.c:1822
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffff800010367b08-ffff800010367bcc: mem_cgroup_mark_under_oom (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mem_cgroup_mark_under_oom(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055916c)
Location: mm/memcontrol.c:1822
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
c055916c-c05591ec: mem_cgroup_mark_under_oom (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mem_cgroup_mark_under_oom(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000455500)
Location: mm/memcontrol.c:1822
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
c000000000455500-c0000000004555ec: mem_cgroup_mark_under_oom (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mem_cgroup_mark_under_oom(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000245a80)
Location: mm/memcontrol.c:1822
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffe000245a80-ffffffe000245b1e: mem_cgroup_mark_under_oom (STB_LOCAL)
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
void mem_cgroup_mark_under_oom(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bd4a0)
Location: mm/memcontrol.c:1822
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812bd4a0-ffffffff812bd4f7: mem_cgroup_mark_under_oom (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mem_cgroup_mark_under_oom(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ae5e0)
Location: mm/memcontrol.c:1822
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812ae5e0-ffffffff812ae637: mem_cgroup_mark_under_oom (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mem_cgroup_mark_under_oom(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bb2b0)
Location: mm/memcontrol.c:1822
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812bb2b0-ffffffff812bb307: mem_cgroup_mark_under_oom (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mem_cgroup_mark_under_oom(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cba60)
Location: mm/memcontrol.c:1822
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812cba60-ffffffff812cbab5: mem_cgroup_mark_under_oom (STB_LOCAL)
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
