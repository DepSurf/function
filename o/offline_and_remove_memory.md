# Function: <code>offline_and_remove_memory</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int offline_and_remove_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812e08b0)
Location: mm/memory_hotplug.c:1844
Inline: False
```
**Symbols:**

```
ffffffff812e08b0-ffffffff812e096b: offline_and_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int offline_and_remove_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:1853
Inline: False
```
**Symbols:**

```
ffffffff81be99ee-ffffffff81be9a08: offline_and_remove_memory.cold (STB_LOCAL)
ffffffff812ebe40-ffffffff812ebf6f: offline_and_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int offline_and_remove_memory(int nid, u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:2137
Inline: False
```
**Symbols:**

```
ffffffff81bda4ab-ffffffff81bda4c5: offline_and_remove_memory.cold (STB_LOCAL)
ffffffff812c67b0-ffffffff812c68df: offline_and_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int offline_and_remove_memory(u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:2309
Inline: False
```
**Symbols:**

```
ffffffff81cbe666-ffffffff81cbe680: offline_and_remove_memory.cold (STB_LOCAL)
ffffffff8130b230-ffffffff8130b359: offline_and_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int offline_and_remove_memory(u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:2231
Inline: False
```
**Symbols:**

```
ffffffff81e70659-ffffffff81e70673: offline_and_remove_memory.cold (STB_LOCAL)
ffffffff81373cd0-ffffffff81373e0b: offline_and_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int offline_and_remove_memory(u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff813f1440)
Location: mm/memory_hotplug.c:2227
Inline: False
```
**Symbols:**

```
ffffffff813f1440-ffffffff813f158d: offline_and_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int offline_and_remove_memory(u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81424f80)
Location: mm/memory_hotplug.c:2200
Inline: False
```
**Symbols:**

```
ffffffff81424f80-ffffffff814250cd: offline_and_remove_memory (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int offline_and_remove_memory(u64 start, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff814521c0)
Location: mm/memory_hotplug.c:2393
Inline: False
```
**Symbols:**

```
ffffffff814521c0-ffffffff8145230d: offline_and_remove_memory (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int nid</code>
</li>
<li>
<b>Param reordered. </b>
<code>nid, start, size</code> ➡️ <code>start, size</code>
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
