# Function: <code>uncharge_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void uncharge_list(struct list_head *page_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff811fd900)
Location: mm/memcontrol.c:5449
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge
  - mm/memcontrol.c:mem_cgroup_uncharge_list
```
**Symbols:**

```
ffffffff811fd900-ffffffff811fd9cc: uncharge_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void uncharge_list(struct list_head *page_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81221540)
Location: mm/memcontrol.c:5519
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
```
**Symbols:**

```
ffffffff81221540-ffffffff81221660: uncharge_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void uncharge_list(struct list_head *page_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81233cb0)
Location: mm/memcontrol.c:5504
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
```
**Symbols:**

```
ffffffff81233cb0-ffffffff81233dd0: uncharge_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void uncharge_list(struct list_head *page_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8123f550)
Location: mm/memcontrol.c:5562
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
  - mm/memcontrol.c:mem_cgroup_uncharge
```
**Symbols:**

```
ffffffff8123f550-ffffffff8123f67f: uncharge_list (STB_LOCAL)
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
In mm/memcontrol.c (ffffffff81261e61)
Location: mm/memcontrol.c:5705
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
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
In mm/memcontrol.c (ffffffff81285e71)
Location: mm/memcontrol.c:5773
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8129add1)
Location: mm/memcontrol.c:6104
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b6081)
Location: mm/memcontrol.c:6396
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c7f71)
Location: mm/memcontrol.c:6736
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
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
In mm/memcontrol.c (ffffffff812fd80f)
Location: mm/memcontrol.c:6597
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
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
In mm/memcontrol.c (ffffffff81309c2f)
Location: mm/memcontrol.c:6857
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff80001036ae94)
Location: mm/memcontrol.c:6736
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
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
In mm/memcontrol.c (c055c4f8)
Location: mm/memcontrol.c:6736
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c00000000045a490)
Location: mm/memcontrol.c:6736
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
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
In mm/memcontrol.c (ffffffe0002485fc)
Location: mm/memcontrol.c:6736
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c0551)
Location: mm/memcontrol.c:6736
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b1621)
Location: mm/memcontrol.c:6736
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812be361)
Location: mm/memcontrol.c:6736
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ced51)
Location: mm/memcontrol.c:6736
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_uncharge_list
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
</ul>
