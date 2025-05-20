# Function: <code>mhp_range_allowed</code>

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
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool mhp_range_allowed(u64 start, u64 size, bool need_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:1419
Inline: False
Direct callers:
  - mm/memory_hotplug.c:register_memory_resource
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff81bda52a-ffffffff81bda546: mhp_range_allowed.cold (STB_LOCAL)
ffffffff812c7310-ffffffff812c7358: mhp_range_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool mhp_range_allowed(u64 start, u64 size, bool need_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:1585
Inline: False
Direct callers:
  - mm/memory_hotplug.c:register_memory_resource
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff81cbe754-ffffffff81cbe770: mhp_range_allowed.cold (STB_LOCAL)
ffffffff8130c090-ffffffff8130c0d8: mhp_range_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool mhp_range_allowed(u64 start, u64 size, bool need_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:1553
Inline: False
Direct callers:
  - mm/memory_hotplug.c:register_memory_resource
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff81e70744-ffffffff81e70760: mhp_range_allowed.cold (STB_LOCAL)
ffffffff81375080-ffffffff813750d8: mhp_range_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool mhp_range_allowed(u64 start, u64 size, bool need_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff813f2a50)
Location: mm/memory_hotplug.c:1551
Inline: False
Direct callers:
  - mm/memory_hotplug.c:register_memory_resource
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff813f2a50-ffffffff813f2ac8: mhp_range_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool mhp_range_allowed(u64 start, u64 size, bool need_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81426490)
Location: mm/memory_hotplug.c:1526
Inline: False
Direct callers:
  - mm/memory_hotplug.c:register_memory_resource
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff81426490-ffffffff81426508: mhp_range_allowed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool mhp_range_allowed(u64 start, u64 size, bool need_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81453650)
Location: mm/memory_hotplug.c:1708
Inline: False
Direct callers:
  - mm/memory_hotplug.c:register_memory_resource
  - mm/memremap.c:pagemap_range
```
**Symbols:**

```
ffffffff81453650-ffffffff814536c8: mhp_range_allowed (STB_GLOBAL)
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
