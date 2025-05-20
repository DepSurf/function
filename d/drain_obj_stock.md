# Function: <code>drain_obj_stock</code>

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
void drain_obj_stock(struct memcg_stock_pcp *stock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813043c0)
Location: mm/memcontrol.c:3181
Inline: False
Direct callers:
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff813043c0-ffffffff81304471: drain_obj_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void drain_obj_stock(struct memcg_stock_pcp *stock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130b490)
Location: mm/memcontrol.c:3025
Inline: False
Direct callers:
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff8130b490-ffffffff8130b518: drain_obj_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void drain_obj_stock(struct obj_stock *stock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81356550)
Location: mm/memcontrol.c:3150
Inline: False
Direct callers:
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:drain_local_stock
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff81356550-ffffffff81356737: drain_obj_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct obj_cgroup *drain_obj_stock(struct memcg_stock_pcp *stock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813cf410)
Location: mm/memcontrol.c:3141
Inline: False
Direct callers:
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff813cf410-ffffffff813cf643: drain_obj_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct obj_cgroup *drain_obj_stock(struct memcg_stock_pcp *stock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814546e0)
Location: mm/memcontrol.c:3241
Inline: False
Direct callers:
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff814546e0-ffffffff81454913: drain_obj_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct obj_cgroup *drain_obj_stock(struct memcg_stock_pcp *stock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8148a4d0)
Location: mm/memcontrol.c:3251
Inline: False
Direct callers:
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff8148a4d0-ffffffff8148a703: drain_obj_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct obj_cgroup *drain_obj_stock(struct memcg_stock_pcp *stock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814b9d80)
Location: mm/memcontrol.c:3443
Inline: False
Direct callers:
  - mm/memcontrol.c:refill_obj_stock
  - mm/memcontrol.c:mod_objcg_state
  - mm/memcontrol.c:drain_local_stock
```
**Symbols:**

```
ffffffff814b9d80-ffffffff814b9fb3: drain_obj_stock (STB_LOCAL)
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
<b>Param type changed. </b>
<code>struct memcg_stock_pcp *stock</code> ➡️ <code>struct obj_stock *stock</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct obj_stock *stock</code> ➡️ <code>struct memcg_stock_pcp *stock</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>struct obj_cgroup *</code>
</li>
</ul>
</details>
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
