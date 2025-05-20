# Function: <code>zone_for_memory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int zone_for_memory(int nid, u64 start, u64 size, int zone_default, bool for_device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff811f0180)
Location: mm/memory_hotplug.c:1221
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_add_memory
```
**Symbols:**

```
ffffffff811f0180-ffffffff811f01c1: zone_for_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int zone_for_memory(int nid, u64 start, u64 size, int zone_default, bool for_device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8120f4a0)
Location: mm/memory_hotplug.c:1331
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_add_memory
```
**Symbols:**

```
ffffffff8120f4a0-ffffffff8120f4e1: zone_for_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int zone_for_memory(int nid, u64 start, u64 size, int zone_default, bool for_device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812215a0)
Location: mm/memory_hotplug.c:1323
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:arch_add_memory
```
**Symbols:**

```
ffffffff812215a0-ffffffff812215e1: zone_for_memory (STB_GLOBAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
