# Function: <code>mem_cgroup_oom_unlock</code>

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
In mm/memcontrol.c (ffffffff811ff6e2)
Location: mm/memcontrol.c:1614
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
In mm/memcontrol.c (ffffffff81223459)
Location: mm/memcontrol.c:1479
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
In mm/memcontrol.c (ffffffff8123593a)
Location: mm/memcontrol.c:1450
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
In mm/memcontrol.c (ffffffff81241314)
Location: mm/memcontrol.c:1442
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
In mm/memcontrol.c (ffffffff81261054)
Location: mm/memcontrol.c:1456
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
In mm/memcontrol.c (ffffffff81285079)
Location: mm/memcontrol.c:1413
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
void mem_cgroup_oom_unlock(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81298260)
Location: mm/memcontrol.c:1594
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff81298260-ffffffff812982b4: mem_cgroup_oom_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void mem_cgroup_oom_unlock(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812b3550)
Location: mm/memcontrol.c:1795
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812b3550-ffffffff812b35a7: mem_cgroup_oom_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void mem_cgroup_oom_unlock(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812c5020)
Location: mm/memcontrol.c:1811
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812c5020-ffffffff812c5077: mem_cgroup_oom_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mem_cgroup_oom_unlock(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812faaf0)
Location: mm/memcontrol.c:1677
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812faaf0-ffffffff812fab4a: mem_cgroup_oom_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mem_cgroup_oom_unlock(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81306aa0)
Location: mm/memcontrol.c:1866
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff81306aa0-ffffffff81306afa: mem_cgroup_oom_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mem_cgroup_oom_unlock(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130d2c0)
Location: mm/memcontrol.c:1689
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff8130d2c0-ffffffff8130d31a: mem_cgroup_oom_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mem_cgroup_oom_unlock(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81358170)
Location: mm/memcontrol.c:1741
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff81358170-ffffffff813581ca: mem_cgroup_oom_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mem_cgroup_oom_unlock(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d12c0)
Location: mm/memcontrol.c:1758
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff813d12c0-ffffffff813d1324: mem_cgroup_oom_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mem_cgroup_oom_unlock(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814566f0)
Location: mm/memcontrol.c:1818
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff814566f0-ffffffff81456754: mem_cgroup_oom_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mem_cgroup_oom_unlock(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148bf80)
Location: mm/memcontrol.c:1852
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff8148bf80-ffffffff8148bfe4: mem_cgroup_oom_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mem_cgroup_oom_unlock(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bb8d0)
Location: mm/memcontrol.c:1924
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge_memcg
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff814bb8d0-ffffffff814bb934: mem_cgroup_oom_unlock (STB_LOCAL)
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
void mem_cgroup_oom_unlock(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffff800010367da0)
Location: mm/memcontrol.c:1811
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffff800010367da0-ffff800010367e5c: mem_cgroup_oom_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void mem_cgroup_oom_unlock(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c055930c)
Location: mm/memcontrol.c:1811
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
c055930c-c0559388: mem_cgroup_oom_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void mem_cgroup_oom_unlock(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (c000000000455810)
Location: mm/memcontrol.c:1811
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
c000000000455810-c00000000045590c: mem_cgroup_oom_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void mem_cgroup_oom_unlock(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffe000245c98)
Location: mm/memcontrol.c:1811
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffe000245c98-ffffffe000245d32: mem_cgroup_oom_unlock (STB_LOCAL)
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
void mem_cgroup_oom_unlock(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bd600)
Location: mm/memcontrol.c:1811
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812bd600-ffffffff812bd657: mem_cgroup_oom_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void mem_cgroup_oom_unlock(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812ae740)
Location: mm/memcontrol.c:1811
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812ae740-ffffffff812ae797: mem_cgroup_oom_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void mem_cgroup_oom_unlock(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812bb410)
Location: mm/memcontrol.c:1811
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812bb410-ffffffff812bb467: mem_cgroup_oom_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void mem_cgroup_oom_unlock(struct mem_cgroup *memcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff812cbbc0)
Location: mm/memcontrol.c:1811
Inline: False
Direct callers:
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:try_charge
  - mm/memcontrol.c:mem_cgroup_oom_synchronize
```
**Symbols:**

```
ffffffff812cbbc0-ffffffff812cbc15: mem_cgroup_oom_unlock (STB_LOCAL)
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
