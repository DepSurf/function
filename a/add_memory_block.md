# Function: <code>add_memory_block</code>

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
In drivers/base/memory.c (ffffffff81fad1e0)
Location: drivers/base/memory.c:631
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81fd9d15)
Location: drivers/base/memory.c:663
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff82017969)
Location: drivers/base/memory.c:664
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
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
In drivers/base/memory.c (ffffffff820f9730)
Location: drivers/base/memory.c:672
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
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
In drivers/base/memory.c (ffffffff82702f15)
Location: drivers/base/memory.c:683
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
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
In drivers/base/memory.c (ffffffff8272cc9f)
Location: drivers/base/memory.c:691
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
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
In drivers/base/memory.c (ffffffff828e562b)
Location: drivers/base/memory.c:678
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
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
In drivers/base/memory.c (0)
Location: drivers/base/memory.c:684
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
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
In drivers/base/memory.c (0)
Location: drivers/base/memory.c:656
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int add_memory_block(long unsigned int base_section_nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817d9533)
Location: drivers/base/memory.c:601
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_dev_init
```
**Symbols:**

```
ffffffff817d9533-ffffffff817d95d5: add_memory_block (STB_LOCAL)
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
In drivers/base/memory.c (0)
Location: drivers/base/memory.c:593
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
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
In drivers/base/memory.c (0)
Location: drivers/base/memory.c:661
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
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
In drivers/base/memory.c (0)
Location: drivers/base/memory.c:676
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int add_memory_block(long unsigned int block_id, long unsigned int state, long unsigned int nr_vmemmap_pages, struct memory_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff819a4220)
Location: drivers/base/memory.c:721
Inline: False
Direct callers:
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:add_boot_memory_block
```
**Symbols:**

```
ffffffff819a4220-ffffffff819a43f4: add_memory_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int add_memory_block(long unsigned int block_id, long unsigned int state, long unsigned int nr_vmemmap_pages, struct memory_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81b16240)
Location: drivers/base/memory.c:733
Inline: False
Direct callers:
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:add_boot_memory_block
```
**Symbols:**

```
ffffffff81b16240-ffffffff81b16414: add_memory_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int add_memory_block(long unsigned int block_id, long unsigned int state, long unsigned int nr_vmemmap_pages, struct memory_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81b64fb0)
Location: drivers/base/memory.c:728
Inline: False
Direct callers:
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:add_boot_memory_block
```
**Symbols:**

```
ffffffff81b64fb0-ffffffff81b65184: add_memory_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int add_memory_block(long unsigned int block_id, long unsigned int state, struct vmem_altmap *altmap, struct memory_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81bb8d10)
Location: drivers/base/memory.c:778
Inline: False
Direct callers:
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:add_boot_memory_block
```
**Symbols:**

```
ffffffff81bb8d10-ffffffff81bb8f13: add_memory_block (STB_LOCAL)
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
In drivers/base/memory.c (0)
Location: drivers/base/memory.c:656
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
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
In drivers/base/memory.c (0)
Location: drivers/base/memory.c:656
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
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
In drivers/base/memory.c (0)
Location: drivers/base/memory.c:656
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
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
In drivers/base/memory.c (0)
Location: drivers/base/memory.c:656
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
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
In drivers/base/memory.c (0)
Location: drivers/base/memory.c:656
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
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
In drivers/base/memory.c (0)
Location: drivers/base/memory.c:656
Inline: True
Inline callers:
  - drivers/base/memory.c:memory_dev_init
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vmem_altmap *altmap</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int nr_vmemmap_pages</code>
</li>
</ul>
</details>
</li>
</ul>
