# Function: <code>memory_block_action</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81560f14)
Location: drivers/base/memory.c:225
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_online
  - drivers/base/memory.c:memory_subsys_offline
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int memory_block_action(long unsigned int phys_index, long unsigned int action, int online_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff815b5600)
Location: drivers/base/memory.c:225
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_subsys_online
```
**Symbols:**

```
ffffffff815b5600-ffffffff815b57d5: memory_block_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int memory_block_action(long unsigned int phys_index, long unsigned int action, int online_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff815e48e0)
Location: drivers/base/memory.c:225
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_subsys_online
```
**Symbols:**

```
ffffffff815e48e0-ffffffff815e4ab2: memory_block_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff815f9512)
Location: drivers/base/memory.c:229
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int memory_block_action(long unsigned int phys_index, long unsigned int action, int online_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81661d40)
Location: drivers/base/memory.c:230
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_subsys_online
```
**Symbols:**

```
ffffffff81661d40-ffffffff81661ecd: memory_block_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int memory_block_action(long unsigned int phys_index, long unsigned int action, int online_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8169d4f0)
Location: drivers/base/memory.c:234
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_online
```
**Symbols:**

```
ffffffff8169d4f0-ffffffff8169d6a0: memory_block_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int memory_block_action(long unsigned int phys_index, long unsigned int action, int online_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816bdca0)
Location: drivers/base/memory.c:233
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_online
```
**Symbols:**

```
ffffffff816bdca0-ffffffff816bde38: memory_block_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int memory_block_action(long unsigned int start_section_nr, long unsigned int action, int online_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816f8ba0)
Location: drivers/base/memory.c:244
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_online
```
**Symbols:**

```
ffffffff816f8ba0-ffffffff816f8d24: memory_block_action (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8171cfa3)
Location: drivers/base/memory.c:213
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817d8e50)
Location: drivers/base/memory.c:178
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817ed820)
Location: drivers/base/memory.c:177
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817d2052)
Location: drivers/base/memory.c:250
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8185d157)
Location: drivers/base/memory.c:257
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff819a4437)
Location: drivers/base/memory.c:262
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81b16467)
Location: drivers/base/memory.c:274
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81b651d7)
Location: drivers/base/memory.c:269
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81bb8f83)
Location: drivers/base/memory.c:309
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_online
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
int memory_block_action(long unsigned int start_section_nr, long unsigned int action, int online_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffff800010910ad8)
Location: drivers/base/memory.c:213
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_online
```
**Symbols:**

```
ffff800010910ad8-ffff800010910c78: memory_block_action (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (c0000000009b1da0)
Location: drivers/base/memory.c:213
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_online
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816e32d3)
Location: drivers/base/memory.c:213
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816bd913)
Location: drivers/base/memory.c:213
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81710463)
Location: drivers/base/memory.c:213
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8172b5c3)
Location: drivers/base/memory.c:213
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int start_section_nr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int phys_index</code>
</li>
</ul>
</details>
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
