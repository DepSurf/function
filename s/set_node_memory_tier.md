# Function: <code>set_node_memory_tier</code>

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
In <code>5.11</code>: Absent ⚠️
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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct memory_tier *set_node_memory_tier(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-tiers.c (ffffffff81436670)
Location: mm/memory-tiers.c:476
Inline: False
Direct callers:
  - mm/memory-tiers.c:memory_tier_init
  - mm/memory-tiers.c:memtier_hotplug_callback
```
**Symbols:**

```
ffffffff81436670-ffffffff8143682d: set_node_memory_tier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct memory_tier *set_node_memory_tier(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-tiers.c (ffffffff8146c330)
Location: mm/memory-tiers.c:475
Inline: False
Direct callers:
  - mm/memory-tiers.c:memory_tier_init
  - mm/memory-tiers.c:memtier_hotplug_callback
```
**Symbols:**

```
ffffffff8146c330-ffffffff8146c4ed: set_node_memory_tier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct memory_tier *set_node_memory_tier(int node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-tiers.c (ffffffff8149b480)
Location: mm/memory-tiers.c:483
Inline: False
Direct callers:
  - mm/memory-tiers.c:memory_tier_init
  - mm/memory-tiers.c:memtier_hotplug_callback
```
**Symbols:**

```
ffffffff8149b480-ffffffff8149b63d: set_node_memory_tier (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
