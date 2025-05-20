# Function: <code>mem_cgroup_move_charge</code>

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
In mm/memcontrol.c (ffffffff811fb818)
Location: mm/memcontrol.c:4987
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
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
In mm/memcontrol.c (ffffffff8121f4fb)
Location: mm/memcontrol.c:4966
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
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
In mm/memcontrol.c (ffffffff81231b6b)
Location: mm/memcontrol.c:4950
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
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
In mm/memcontrol.c (ffffffff8123db2b)
Location: mm/memcontrol.c:4975
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
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
In mm/memcontrol.c (ffffffff8125d6bb)
Location: mm/memcontrol.c:5058
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
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
In mm/memcontrol.c (ffffffff8128121b)
Location: mm/memcontrol.c:4995
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
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
In mm/memcontrol.c (ffffffff81295c4b)
Location: mm/memcontrol.c:5281
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
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
In mm/memcontrol.c (ffffffff812b1c8c)
Location: mm/memcontrol.c:5642
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
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
In mm/memcontrol.c (ffffffff812c365f)
Location: mm/memcontrol.c:5986
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mem_cgroup_move_charge();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812f9f00)
Location: mm/memcontrol.c:5893
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
**Symbols:**

```
ffffffff812f9f00-ffffffff812f9f7d: mem_cgroup_move_charge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mem_cgroup_move_charge();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813053a0)
Location: mm/memcontrol.c:6127
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
**Symbols:**

```
ffffffff813053a0-ffffffff8130546c: mem_cgroup_move_charge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mem_cgroup_move_charge();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130ac80)
Location: mm/memcontrol.c:5949
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
**Symbols:**

```
ffffffff8130ac80-ffffffff8130ad46: mem_cgroup_move_charge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mem_cgroup_move_charge();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813533a0)
Location: mm/memcontrol.c:6133
Inline: False
Direct callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
**Symbols:**

```
ffffffff813533a0-ffffffff8135345c: mem_cgroup_move_charge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mem_cgroup_move_charge();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813cded0)
Location: mm/memcontrol.c:6079
Inline: False
```
**Symbols:**

```
ffffffff813cded0-ffffffff813cdf9d: mem_cgroup_move_charge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mem_cgroup_move_charge();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81452fb0)
Location: mm/memcontrol.c:6244
Inline: False
```
**Symbols:**

```
ffffffff81452fb0-ffffffff81453080: mem_cgroup_move_charge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mem_cgroup_move_charge();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81488c00)
Location: mm/memcontrol.c:6310
Inline: False
```
**Symbols:**

```
ffffffff81488c00-ffffffff81488cd6: mem_cgroup_move_charge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mem_cgroup_move_charge();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814b8280)
Location: mm/memcontrol.c:6545
Inline: False
```
**Symbols:**

```
ffffffff814b8280-ffffffff814b8356: mem_cgroup_move_charge (STB_LOCAL)
```
</details>
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
In mm/memcontrol.c (ffff800010365f18)
Location: mm/memcontrol.c:5986
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
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
In mm/memcontrol.c (c0557c14)
Location: mm/memcontrol.c:5986
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
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
In mm/memcontrol.c (c000000000453110)
Location: mm/memcontrol.c:5986
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
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
In mm/memcontrol.c (ffffffe000244810)
Location: mm/memcontrol.c:5986
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
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
In mm/memcontrol.c (ffffffff812bbc3f)
Location: mm/memcontrol.c:5986
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
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
In mm/memcontrol.c (ffffffff812acd9f)
Location: mm/memcontrol.c:5986
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
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
In mm/memcontrol.c (ffffffff812b9a4f)
Location: mm/memcontrol.c:5986
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
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
In mm/memcontrol.c (ffffffff812ca0df)
Location: mm/memcontrol.c:5986
Inline: True
Inline callers:
  - mm/memcontrol.c:mem_cgroup_move_task
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
