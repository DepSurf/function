# Function: <code>refill_obj_stock</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void refill_obj_stock(struct obj_cgroup *objcg, unsigned int nr_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81304480)
Location: mm/memcontrol.c:3230
Inline: False
Direct callers:
  - mm/memcontrol.c:obj_cgroup_uncharge
  - mm/memcontrol.c:obj_cgroup_charge
```
**Symbols:**

```
ffffffff81304480-ffffffff8130452d: refill_obj_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void refill_obj_stock(struct obj_cgroup *objcg, unsigned int nr_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130bf80)
Location: mm/memcontrol.c:3071
Inline: False
Direct callers:
  - mm/memcontrol.c:obj_cgroup_uncharge
  - mm/memcontrol.c:obj_cgroup_charge
```
**Symbols:**

```
ffffffff8130bf80-ffffffff8130c039: refill_obj_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void refill_obj_stock(struct obj_cgroup *objcg, unsigned int nr_bytes, bool allow_uncharge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81357270)
Location: mm/memcontrol.c:3220
Inline: False
Direct callers:
  - mm/memcontrol.c:obj_cgroup_uncharge
  - mm/memcontrol.c:obj_cgroup_charge
```
**Symbols:**

```
ffffffff81357270-ffffffff81357394: refill_obj_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void refill_obj_stock(struct obj_cgroup *objcg, unsigned int nr_bytes, bool allow_uncharge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813d0180)
Location: mm/memcontrol.c:3218
Inline: False
Direct callers:
  - mm/memcontrol.c:obj_cgroup_uncharge_zswap
  - mm/memcontrol.c:obj_cgroup_charge
```
**Symbols:**

```
ffffffff813d0180-ffffffff813d031d: refill_obj_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void refill_obj_stock(struct obj_cgroup *objcg, unsigned int nr_bytes, bool allow_uncharge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814554f0)
Location: mm/memcontrol.c:3318
Inline: False
Direct callers:
  - mm/memcontrol.c:obj_cgroup_uncharge_zswap
  - mm/memcontrol.c:obj_cgroup_charge
```
**Symbols:**

```
ffffffff814554f0-ffffffff814556a4: refill_obj_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void refill_obj_stock(struct obj_cgroup *objcg, unsigned int nr_bytes, bool allow_uncharge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148b310)
Location: mm/memcontrol.c:3329
Inline: False
Direct callers:
  - mm/memcontrol.c:obj_cgroup_uncharge_zswap
  - mm/memcontrol.c:obj_cgroup_charge
```
**Symbols:**

```
ffffffff8148b310-ffffffff8148b4c7: refill_obj_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void refill_obj_stock(struct obj_cgroup *objcg, unsigned int nr_bytes, bool allow_uncharge);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814bac10)
Location: mm/memcontrol.c:3521
Inline: False
Direct callers:
  - mm/memcontrol.c:obj_cgroup_uncharge_zswap
  - mm/memcontrol.c:obj_cgroup_charge
```
**Symbols:**

```
ffffffff814bac10-ffffffff814badc7: refill_obj_stock (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool allow_uncharge</code>
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
