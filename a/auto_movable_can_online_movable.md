# Function: <code>auto_movable_can_online_movable</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool auto_movable_can_online_movable(int nid, struct memory_group *group, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:785
Inline: False
Direct callers:
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
```
**Symbols:**

```
ffffffff8130aa00-ffffffff8130aba0: auto_movable_can_online_movable (STB_LOCAL)
ffffffff81cbe638-ffffffff81cbe64d: auto_movable_can_online_movable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool auto_movable_can_online_movable(int nid, struct memory_group *group, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:784
Inline: False
Direct callers:
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
```
**Symbols:**

```
ffffffff81373820-ffffffff813739d3: auto_movable_can_online_movable (STB_LOCAL)
ffffffff81e7062b-ffffffff81e70640: auto_movable_can_online_movable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool auto_movable_can_online_movable(int nid, struct memory_group *group, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:780
Inline: False
Direct callers:
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
```
**Symbols:**

```
ffffffff813f0f00-ffffffff813f10b3: auto_movable_can_online_movable (STB_LOCAL)
ffffffff8206576a-ffffffff8206577f: auto_movable_can_online_movable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool auto_movable_can_online_movable(int nid, struct memory_group *group, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:774
Inline: False
Direct callers:
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
```
**Symbols:**

```
ffffffff81424a40-ffffffff81424bf3: auto_movable_can_online_movable (STB_LOCAL)
ffffffff820e4f5b-ffffffff820e4f70: auto_movable_can_online_movable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool auto_movable_can_online_movable(int nid, struct memory_group *group, long unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:843
Inline: False
Direct callers:
  - mm/memory_hotplug.c:zone_for_pfn_range
  - mm/memory_hotplug.c:zone_for_pfn_range
```
**Symbols:**

```
ffffffff814519e0-ffffffff81451b93: auto_movable_can_online_movable (STB_LOCAL)
ffffffff821c1c32-ffffffff821c1c47: auto_movable_can_online_movable.cold (STB_LOCAL)
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
