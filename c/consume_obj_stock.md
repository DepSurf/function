# Function: <code>consume_obj_stock</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813091db)
Location: mm/memcontrol.c:3162
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_charge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8130f805)
Location: mm/memcontrol.c:3006
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_charge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8135aa46)
Location: mm/memcontrol.c:3134
Inline: True
Inline callers:
  - mm/memcontrol.c:obj_cgroup_charge
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool consume_obj_stock(struct obj_cgroup *objcg, unsigned int nr_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff813c8ce0)
Location: mm/memcontrol.c:3122
Inline: False
Direct callers:
  - mm/memcontrol.c:obj_cgroup_charge
```
**Symbols:**

```
ffffffff813c8ce0-ffffffff813c8d3d: consume_obj_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool consume_obj_stock(struct obj_cgroup *objcg, unsigned int nr_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff8144d470)
Location: mm/memcontrol.c:3222
Inline: False
Direct callers:
  - mm/memcontrol.c:obj_cgroup_charge
```
**Symbols:**

```
ffffffff8144d470-ffffffff8144d4e8: consume_obj_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool consume_obj_stock(struct obj_cgroup *objcg, unsigned int nr_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff81482d30)
Location: mm/memcontrol.c:3232
Inline: False
Direct callers:
  - mm/memcontrol.c:obj_cgroup_charge
```
**Symbols:**

```
ffffffff81482d30-ffffffff81482dab: consume_obj_stock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool consume_obj_stock(struct obj_cgroup *objcg, unsigned int nr_bytes);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memcontrol.c (ffffffff814b20b0)
Location: mm/memcontrol.c:3424
Inline: False
Direct callers:
  - mm/memcontrol.c:obj_cgroup_charge
```
**Symbols:**

```
ffffffff814b20b0-ffffffff814b212b: consume_obj_stock (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
