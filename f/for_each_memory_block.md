# Function: <code>for_each_memory_block</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int for_each_memory_block(void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8171d630)
Location: drivers/base/memory.c:884
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_offline_node
```
**Symbols:**

```
ffffffff8171d630-ffffffff8171d683: for_each_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int for_each_memory_block(void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817d94e0)
Location: drivers/base/memory.c:824
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_offline_node
```
**Symbols:**

```
ffffffff817d94e0-ffffffff817d9533: for_each_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int for_each_memory_block(void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817ede80)
Location: drivers/base/memory.c:815
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_offline_node
```
**Symbols:**

```
ffffffff817ede80-ffffffff817eded3: for_each_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int for_each_memory_block(void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817d27d0)
Location: drivers/base/memory.c:884
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_offline_node
```
**Symbols:**

```
ffffffff817d27d0-ffffffff817d2823: for_each_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int for_each_memory_block(void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8185d920)
Location: drivers/base/memory.c:906
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_offline_node
```
**Symbols:**

```
ffffffff8185d920-ffffffff8185d973: for_each_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int for_each_memory_block(void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff819a4d90)
Location: drivers/base/memory.c:1002
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_offline_node
```
**Symbols:**

```
ffffffff819a4d90-ffffffff819a4def: for_each_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int for_each_memory_block(void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81b16e90)
Location: drivers/base/memory.c:1009
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_offline_node
```
**Symbols:**

```
ffffffff81b16e90-ffffffff81b16eef: for_each_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int for_each_memory_block(void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81b65c00)
Location: drivers/base/memory.c:1004
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_offline_node
```
**Symbols:**

```
ffffffff81b65c00-ffffffff81b65c5f: for_each_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int for_each_memory_block(void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81bb9a80)
Location: drivers/base/memory.c:1057
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_offline_node
```
**Symbols:**

```
ffffffff81bb9a80-ffffffff81bb9adf: for_each_memory_block (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int for_each_memory_block(void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffff800010911320)
Location: drivers/base/memory.c:884
Inline: False
```
**Symbols:**

```
ffff800010911320-ffff800010911394: for_each_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int for_each_memory_block(void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (c0000000009b27c0)
Location: drivers/base/memory.c:884
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_offline_node
```
**Symbols:**

```
c0000000009b27c0-c0000000009b2844: for_each_memory_block (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int for_each_memory_block(void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816e3960)
Location: drivers/base/memory.c:884
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_offline_node
```
**Symbols:**

```
ffffffff816e3960-ffffffff816e39b3: for_each_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int for_each_memory_block(void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816bdfa0)
Location: drivers/base/memory.c:884
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_offline_node
```
**Symbols:**

```
ffffffff816bdfa0-ffffffff816bdff3: for_each_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int for_each_memory_block(void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81710af0)
Location: drivers/base/memory.c:884
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_offline_node
```
**Symbols:**

```
ffffffff81710af0-ffffffff81710b43: for_each_memory_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int for_each_memory_block(void *arg, walk_memory_blocks_func_t func);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8172bc50)
Location: drivers/base/memory.c:884
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_offline_node
```
**Symbols:**

```
ffffffff8172bc50-ffffffff8172bca3: for_each_memory_block (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
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
