# Function: <code>check_hotplug_memory_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int check_hotplug_memory_range(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff811ef2f0)
Location: mm/memory_hotplug.c:1184
Inline: False
Direct callers:
  - mm/memory_hotplug.c:add_memory_resource
  - mm/memory_hotplug.c:remove_memory
```
**Symbols:**

```
ffffffff811ef2f0-ffffffff811ef333: check_hotplug_memory_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int check_hotplug_memory_range(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8120e5c0)
Location: mm/memory_hotplug.c:1294
Inline: False
Direct callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff8120e5c0-ffffffff8120e602: check_hotplug_memory_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int check_hotplug_memory_range(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81220600)
Location: mm/memory_hotplug.c:1286
Inline: False
Direct callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff81220600-ffffffff81220642: check_hotplug_memory_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int check_hotplug_memory_range(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8122c2a0)
Location: mm/memory_hotplug.c:1115
Inline: False
Direct callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff8122c2a0-ffffffff8122c2e2: check_hotplug_memory_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int check_hotplug_memory_range(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81247a70)
Location: mm/memory_hotplug.c:1103
Inline: False
Direct callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff81247a70-ffffffff81247ab2: check_hotplug_memory_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int check_hotplug_memory_range(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:1088
Inline: False
Direct callers:
  - mm/memory_hotplug.c:remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff8126b5f0-ffffffff8126b639: check_hotplug_memory_range (STB_LOCAL)
ffffffff8126c7dd-ffffffff8126c7fc: check_hotplug_memory_range.cold.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int check_hotplug_memory_range(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory_hotplug.c (0)
Location: mm/memory_hotplug.c:1065
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff8127fe80-ffffffff8127fec9: check_hotplug_memory_range (STB_LOCAL)
ffffffff812810f4-ffffffff81281113: check_hotplug_memory_range.cold.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int check_hotplug_memory_range(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8129bdd0)
Location: mm/memory_hotplug.c:1046
Inline: True
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff8129bdd0-ffffffff8129be2d: check_hotplug_memory_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int check_hotplug_memory_range(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812abb50)
Location: mm/memory_hotplug.c:1021
Inline: True
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff812abb50-ffffffff812abbad: check_hotplug_memory_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int check_hotplug_memory_range(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812e0620)
Location: mm/memory_hotplug.c:1003
Inline: True
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff812e0620-ffffffff812e067d: check_hotplug_memory_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int check_hotplug_memory_range(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812eb430)
Location: mm/memory_hotplug.c:1008
Inline: True
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff812eb430-ffffffff812eb48d: check_hotplug_memory_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int check_hotplug_memory_range(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812c6000)
Location: mm/memory_hotplug.c:1136
Inline: True
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff812c6000-ffffffff812c605d: check_hotplug_memory_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int check_hotplug_memory_range(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff8130aba0)
Location: mm/memory_hotplug.c:1292
Inline: True
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff8130aba0-ffffffff8130abfd: check_hotplug_memory_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int check_hotplug_memory_range(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81373620)
Location: mm/memory_hotplug.c:1258
Inline: True
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff81373620-ffffffff81373687: check_hotplug_memory_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int check_hotplug_memory_range(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff813f0de0)
Location: mm/memory_hotplug.c:1256
Inline: True
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff813f0de0-ffffffff813f0e47: check_hotplug_memory_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int check_hotplug_memory_range(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81424920)
Location: mm/memory_hotplug.c:1231
Inline: True
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff81424920-ffffffff81424987: check_hotplug_memory_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int check_hotplug_memory_range(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff814517c0)
Location: mm/memory_hotplug.c:1309
Inline: True
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff814517c0-ffffffff81451827: check_hotplug_memory_range (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffff800010d9d27c)
Location: mm/memory_hotplug.c:1021
Inline: True
Inline callers:
  - mm/memory_hotplug.c:add_memory_resource
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int check_hotplug_memory_range(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (c00000000042d830)
Location: mm/memory_hotplug.c:1021
Inline: True
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
c00000000042d830-c00000000042d8d0: check_hotplug_memory_range (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int check_hotplug_memory_range(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812a4130)
Location: mm/memory_hotplug.c:1021
Inline: True
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff812a4130-ffffffff812a418d: check_hotplug_memory_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int check_hotplug_memory_range(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff81295c00)
Location: mm/memory_hotplug.c:1021
Inline: True
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff81295c00-ffffffff81295c5d: check_hotplug_memory_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int check_hotplug_memory_range(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812a1f40)
Location: mm/memory_hotplug.c:1021
Inline: True
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff812a1f40-ffffffff812a1f9d: check_hotplug_memory_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int check_hotplug_memory_range(u64 start, u64 size);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory_hotplug.c (ffffffff812b2100)
Location: mm/memory_hotplug.c:1021
Inline: True
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
  - mm/memory_hotplug.c:add_memory_resource
```
**Symbols:**

```
ffffffff812b2100-ffffffff812b215d: check_hotplug_memory_range (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
