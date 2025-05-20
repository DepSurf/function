# Function: <code>mem_cgroup_clear_mc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mem_cgroup_clear_mc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811fb780)
Location: mm/memcontrol.c:4800
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_cancel_attach
  - mm/memcontrol.c:mem_cgroup_can_attach
```
**Symbols:**

```
ffffffff811fb780-ffffffff811fb7cc: mem_cgroup_clear_mc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mem_cgroup_clear_mc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8121f460)
Location: mm/memcontrol.c:4772
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_cancel_attach
```
**Symbols:**

```
ffffffff8121f460-ffffffff8121f4ca: mem_cgroup_clear_mc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mem_cgroup_clear_mc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81231ad0)
Location: mm/memcontrol.c:4756
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_cancel_attach
```
**Symbols:**

```
ffffffff81231ad0-ffffffff81231b3a: mem_cgroup_clear_mc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void mem_cgroup_clear_mc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8123da90)
Location: mm/memcontrol.c:4781
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_cancel_attach
```
**Symbols:**

```
ffffffff8123da90-ffffffff8123dafa: mem_cgroup_clear_mc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void mem_cgroup_clear_mc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8125d620)
Location: mm/memcontrol.c:4851
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_cancel_attach
```
**Symbols:**

```
ffffffff8125d620-ffffffff8125d68a: mem_cgroup_clear_mc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void mem_cgroup_clear_mc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81281180)
Location: mm/memcontrol.c:4788
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_cancel_attach
```
**Symbols:**

```
ffffffff81281180-ffffffff812811ea: mem_cgroup_clear_mc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void mem_cgroup_clear_mc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81295bb0)
Location: mm/memcontrol.c:5074
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_cancel_attach
```
**Symbols:**

```
ffffffff81295bb0-ffffffff81295c1a: mem_cgroup_clear_mc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mem_cgroup_clear_mc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b1bf0)
Location: mm/memcontrol.c:5435
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_cancel_attach
```
**Symbols:**

```
ffffffff812b1bf0-ffffffff812b1c59: mem_cgroup_clear_mc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mem_cgroup_clear_mc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c35e0)
Location: mm/memcontrol.c:5775
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_cancel_attach
```
**Symbols:**

```
ffffffff812c35e0-ffffffff812c3649: mem_cgroup_clear_mc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812fa01a)
Location: mm/memcontrol.c:5681
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_cancel_attach
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130550a)
Location: mm/memcontrol.c:5915
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_cancel_attach
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_clear_mc();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130ae5a)
Location: mm/memcontrol.c:5737
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_cancel_attach
```
**Symbols:**

```
ffffffff8130ad50-ffffffff8130adbb: mem_cgroup_clear_mc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mem_cgroup_clear_mc();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813537aa)
Location: mm/memcontrol.c:5921
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_cancel_attach
```
**Symbols:**

```
ffffffff81353460-ffffffff813534cb: mem_cgroup_clear_mc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813cdfaf)
Location: mm/memcontrol.c:5867
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_cancel_attach
  - mm/memcontrol.c:mem_cgroup_can_attach
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8145309f)
Location: mm/memcontrol.c:6032
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_cancel_attach
  - mm/memcontrol.c:mem_cgroup_can_attach
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81488cff)
Location: mm/memcontrol.c:6094
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_cancel_attach
  - mm/memcontrol.c:mem_cgroup_can_attach
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814b837f)
Location: mm/memcontrol.c:6329
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_cancel_attach
  - mm/memcontrol.c:mem_cgroup_can_attach
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
void mem_cgroup_clear_mc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010365e50)
Location: mm/memcontrol.c:5775
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_cancel_attach
```
**Symbols:**

```
ffff800010365e50-ffff800010365eec: mem_cgroup_clear_mc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mem_cgroup_clear_mc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c0557b80)
Location: mm/memcontrol.c:5775
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_cancel_attach
```
**Symbols:**

```
c0557b80-c0557be8: mem_cgroup_clear_mc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mem_cgroup_clear_mc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000453000)
Location: mm/memcontrol.c:5775
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_cancel_attach
```
**Symbols:**

```
c000000000453000-c0000000004530dc: mem_cgroup_clear_mc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mem_cgroup_clear_mc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000244742)
Location: mm/memcontrol.c:5775
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_cancel_attach
```
**Symbols:**

```
ffffffe000244742-ffffffe0002447ee: mem_cgroup_clear_mc (STB_LOCAL)
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
void mem_cgroup_clear_mc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bbbc0)
Location: mm/memcontrol.c:5775
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_cancel_attach
```
**Symbols:**

```
ffffffff812bbbc0-ffffffff812bbc29: mem_cgroup_clear_mc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mem_cgroup_clear_mc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812acd20)
Location: mm/memcontrol.c:5775
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_cancel_attach
```
**Symbols:**

```
ffffffff812acd20-ffffffff812acd89: mem_cgroup_clear_mc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mem_cgroup_clear_mc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b99d0)
Location: mm/memcontrol.c:5775
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_cancel_attach
```
**Symbols:**

```
ffffffff812b99d0-ffffffff812b9a39: mem_cgroup_clear_mc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mem_cgroup_clear_mc();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ca060)
Location: mm/memcontrol.c:5775
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_task
  - mm/memcontrol.c:mem_cgroup_cancel_attach
```
**Symbols:**

```
ffffffff812ca060-ffffffff812ca0c7: mem_cgroup_clear_mc (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
