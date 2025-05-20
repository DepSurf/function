# Function: <code>memory_block_change_state</code>

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
In drivers/base/memory.c (ffffffff81560ee3)
Location: drivers/base/memory.c:254
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_online
  - drivers/base/memory.c:memory_subsys_offline
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int memory_block_change_state(struct memory_block *mem, long unsigned int to_state, long unsigned int from_state_req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff815b57fd)
Location: drivers/base/memory.c:254
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_online
Direct callers:
  - mm/memory_hotplug.c:online_memory_block
```
**Symbols:**

```
ffffffff815b60b0-ffffffff815b60fe: memory_block_change_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int memory_block_change_state(struct memory_block *mem, long unsigned int to_state, long unsigned int from_state_req);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff815e4add)
Location: drivers/base/memory.c:252
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_online
Direct callers:
  - mm/memory_hotplug.c:online_memory_block
```
**Symbols:**

```
ffffffff815e53d0-ffffffff815e541e: memory_block_change_state (STB_GLOBAL)
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
In drivers/base/memory.c (ffffffff815f94e1)
Location: drivers/base/memory.c:256
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81661f4f)
Location: drivers/base/memory.c:257
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8169d6b1)
Location: drivers/base/memory.c:261
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816bde51)
Location: drivers/base/memory.c:260
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_online
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816f8d4f)
Location: drivers/base/memory.c:272
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_online
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
In drivers/base/memory.c (ffffffff8171cf90)
Location: drivers/base/memory.c:241
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
In drivers/base/memory.c (ffffffff817d8e38)
Location: drivers/base/memory.c:203
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
In drivers/base/memory.c (ffffffff817ed808)
Location: drivers/base/memory.c:202
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
In drivers/base/memory.c (ffffffff817d2032)
Location: drivers/base/memory.c:270
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
In drivers/base/memory.c (ffffffff8185d142)
Location: drivers/base/memory.c:277
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
In drivers/base/memory.c (ffffffff819a4422)
Location: drivers/base/memory.c:282
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
In drivers/base/memory.c (ffffffff81b16452)
Location: drivers/base/memory.c:294
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
In drivers/base/memory.c (ffffffff81b651c2)
Location: drivers/base/memory.c:289
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
In drivers/base/memory.c (ffffffff81bb8f63)
Location: drivers/base/memory.c:329
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
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffff800010910ca0)
Location: drivers/base/memory.c:241
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_subsys_offline
  - drivers/base/memory.c:memory_subsys_online
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
In drivers/base/memory.c (c0000000009b1d80)
Location: drivers/base/memory.c:241
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
In drivers/base/memory.c (ffffffff816e32c0)
Location: drivers/base/memory.c:241
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
In drivers/base/memory.c (ffffffff816bd900)
Location: drivers/base/memory.c:241
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
In drivers/base/memory.c (ffffffff81710450)
Location: drivers/base/memory.c:241
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
In drivers/base/memory.c (ffffffff8172b5b0)
Location: drivers/base/memory.c:241
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
</ul>
