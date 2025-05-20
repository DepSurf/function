# Function: <code>mhp_get_pluggable_range</code>

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
struct range mhp_get_pluggable_range(bool need_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812c72a0)
Location: mm/memory_hotplug.c:1399
Inline: False
Direct callers:
  - mm/memory_hotplug.c:mhp_range_allowed
```
**Symbols:**

```
ffffffff812c72a0-ffffffff812c730f: mhp_get_pluggable_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct range mhp_get_pluggable_range(bool need_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8130c020)
Location: mm/memory_hotplug.c:1565
Inline: False
Direct callers:
  - mm/memory_hotplug.c:mhp_range_allowed
```
**Symbols:**

```
ffffffff8130c020-ffffffff8130c08f: mhp_get_pluggable_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct range mhp_get_pluggable_range(bool need_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81375000)
Location: mm/memory_hotplug.c:1533
Inline: False
Direct callers:
  - mm/memory_hotplug.c:mhp_range_allowed
  - drivers/xen/unpopulated-alloc.c:fill_list
```
**Symbols:**

```
ffffffff81375000-ffffffff81375073: mhp_get_pluggable_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct range mhp_get_pluggable_range(bool need_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff813f29c0)
Location: mm/memory_hotplug.c:1531
Inline: False
Direct callers:
  - mm/memory_hotplug.c:mhp_range_allowed
  - drivers/xen/unpopulated-alloc.c:fill_list
```
**Symbols:**

```
ffffffff813f29c0-ffffffff813f2a33: mhp_get_pluggable_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct range mhp_get_pluggable_range(bool need_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81426400)
Location: mm/memory_hotplug.c:1506
Inline: False
Direct callers:
  - mm/memory_hotplug.c:mhp_range_allowed
  - drivers/xen/unpopulated-alloc.c:fill_list
```
**Symbols:**

```
ffffffff81426400-ffffffff81426473: mhp_get_pluggable_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct range mhp_get_pluggable_range(bool need_mapping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff814535c0)
Location: mm/memory_hotplug.c:1688
Inline: False
Direct callers:
  - mm/memory_hotplug.c:mhp_range_allowed
  - drivers/xen/unpopulated-alloc.c:fill_list
```
**Symbols:**

```
ffffffff814535c0-ffffffff81453633: mhp_get_pluggable_range (STB_GLOBAL)
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
