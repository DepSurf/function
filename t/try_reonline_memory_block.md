# Function: <code>try_reonline_memory_block</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int try_reonline_memory_block(struct memory_block *mem, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:1829
Inline: False
```
**Symbols:**

```
ffffffff812eb330-ffffffff812eb37c: try_reonline_memory_block (STB_LOCAL)
ffffffff81be99d1-ffffffff81be99ee: try_reonline_memory_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int try_reonline_memory_block(struct memory_block *mem, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:2113
Inline: False
```
**Symbols:**

```
ffffffff812c5fb0-ffffffff812c5ffc: try_reonline_memory_block (STB_LOCAL)
ffffffff81bda475-ffffffff81bda492: try_reonline_memory_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int try_reonline_memory_block(struct memory_block *mem, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:2285
Inline: False
```
**Symbols:**

```
ffffffff8130a9b0-ffffffff8130a9fc: try_reonline_memory_block (STB_LOCAL)
ffffffff81cbe61b-ffffffff81cbe638: try_reonline_memory_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int try_reonline_memory_block(struct memory_block *mem, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:2207
Inline: False
```
**Symbols:**

```
ffffffff813735c0-ffffffff81373620: try_reonline_memory_block (STB_LOCAL)
ffffffff81e7060e-ffffffff81e7062b: try_reonline_memory_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int try_reonline_memory_block(struct memory_block *mem, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff813f0d50)
Location: mm/memory_hotplug.c:2203
Inline: False
```
**Symbols:**

```
ffffffff813f0d50-ffffffff813f0dc3: try_reonline_memory_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int try_reonline_memory_block(struct memory_block *mem, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81424890)
Location: mm/memory_hotplug.c:2176
Inline: False
```
**Symbols:**

```
ffffffff81424890-ffffffff81424903: try_reonline_memory_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int try_reonline_memory_block(struct memory_block *mem, void *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff814516c0)
Location: mm/memory_hotplug.c:2369
Inline: False
```
**Symbols:**

```
ffffffff814516c0-ffffffff81451733: try_reonline_memory_block (STB_LOCAL)
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
