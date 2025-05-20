# Function: <code>arch_get_mappable_range</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct range arch_get_mappable_range();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812c7280)
Location: mm/memory_hotplug.c:1390
Inline: False
Direct callers:
  - mm/memory_hotplug.c:mhp_get_pluggable_range
```
**Symbols:**

```
ffffffff812c7280-ffffffff812c7294: arch_get_mappable_range (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct range arch_get_mappable_range();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8130c000)
Location: mm/memory_hotplug.c:1556
Inline: False
Direct callers:
  - mm/memory_hotplug.c:mhp_get_pluggable_range
```
**Symbols:**

```
ffffffff8130c000-ffffffff8130c014: arch_get_mappable_range (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct range arch_get_mappable_range();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81374fe0)
Location: mm/memory_hotplug.c:1524
Inline: False
Direct callers:
  - mm/memory_hotplug.c:mhp_get_pluggable_range
```
**Symbols:**

```
ffffffff81374fe0-ffffffff81374ff8: arch_get_mappable_range (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct range arch_get_mappable_range();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff813f2990)
Location: mm/memory_hotplug.c:1522
Inline: False
Direct callers:
  - mm/memory_hotplug.c:mhp_get_pluggable_range
```
**Symbols:**

```
ffffffff813f2990-ffffffff813f29a8: arch_get_mappable_range (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct range arch_get_mappable_range();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff814263d0)
Location: mm/memory_hotplug.c:1497
Inline: False
Direct callers:
  - mm/memory_hotplug.c:mhp_get_pluggable_range
```
**Symbols:**

```
ffffffff814263d0-ffffffff814263e8: arch_get_mappable_range (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct range arch_get_mappable_range();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81453590)
Location: mm/memory_hotplug.c:1679
Inline: False
Direct callers:
  - mm/memory_hotplug.c:mhp_get_pluggable_range
```
**Symbols:**

```
ffffffff81453590-ffffffff814535a8: arch_get_mappable_range (STB_WEAK)
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
