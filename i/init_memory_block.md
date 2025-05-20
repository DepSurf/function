# Function: <code>init_memory_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int init_memory_block(struct memory_block **memory, struct mem_section *section, long unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81561830)
Location: drivers/base/memory.c:604
Inline: False
Direct callers:
  - drivers/base/memory.c:register_new_memory
  - drivers/base/memory.c:memory_dev_init
```
**Symbols:**

```
ffffffff81561830-ffffffff81561912: init_memory_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int init_memory_block(struct memory_block **memory, struct mem_section *section, long unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff815b6110)
Location: drivers/base/memory.c:637
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:register_new_memory
```
**Symbols:**

```
ffffffff815b6110-ffffffff815b61ef: init_memory_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int init_memory_block(struct memory_block **memory, struct mem_section *section, long unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff815e5430)
Location: drivers/base/memory.c:638
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:register_new_memory
```
**Symbols:**

```
ffffffff815e5430-ffffffff815e550f: init_memory_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int init_memory_block(struct memory_block **memory, struct mem_section *section, long unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff815f9ec0)
Location: drivers/base/memory.c:646
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:register_new_memory
```
**Symbols:**

```
ffffffff815f9ec0-ffffffff815f9f9f: init_memory_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int init_memory_block(struct memory_block **memory, struct mem_section *section, long unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81662060)
Location: drivers/base/memory.c:657
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:register_new_memory
```
**Symbols:**

```
ffffffff81662060-ffffffff8166213f: init_memory_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int init_memory_block(struct memory_block **memory, struct mem_section *section, long unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8169d830)
Location: drivers/base/memory.c:665
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:hotplug_memory_register
```
**Symbols:**

```
ffffffff8169d830-ffffffff8169d92e: init_memory_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int init_memory_block(struct memory_block **memory, struct mem_section *section, long unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816bdfd0)
Location: drivers/base/memory.c:652
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:hotplug_memory_register
```
**Symbols:**

```
ffffffff816bdfd0-ffffffff816be0ce: init_memory_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int init_memory_block(struct memory_block **memory, long unsigned int block_id, long unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816f8e50)
Location: drivers/base/memory.c:656
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
ffffffff816f8e50-ffffffff816f8f70: init_memory_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int init_memory_block(struct memory_block **memory, long unsigned int block_id, long unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8171d1d0)
Location: drivers/base/memory.c:628
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
ffffffff8171d1d0-ffffffff8171d2ee: init_memory_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int init_memory_block(struct memory_block **memory, long unsigned int block_id, long unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817d9050)
Location: drivers/base/memory.c:573
Inline: False
Direct callers:
  - drivers/base/memory.c:create_memory_block_devices
  - drivers/base/memory.c:add_memory_block
```
**Symbols:**

```
ffffffff817d9050-ffffffff817d91c1: init_memory_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int init_memory_block(long unsigned int block_id, long unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817ed600)
Location: drivers/base/memory.c:570
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
ffffffff817ed600-ffffffff817ed76f: init_memory_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int init_memory_block(long unsigned int block_id, long unsigned int state, long unsigned int nr_vmemmap_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817d1e90)
Location: drivers/base/memory.c:636
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
ffffffff817d1e90-ffffffff817d2009: init_memory_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int init_memory_block(long unsigned int block_id, long unsigned int state, long unsigned int nr_vmemmap_pages, struct memory_group *group);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8185cf50)
Location: drivers/base/memory.c:644
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
ffffffff8185cf50-ffffffff8185d120: init_memory_block (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int init_memory_block(struct memory_block **memory, long unsigned int block_id, long unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffff800010910e10)
Location: drivers/base/memory.c:628
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
ffff800010910e10-ffff800010910f34: init_memory_block (STB_LOCAL)
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
int init_memory_block(struct memory_block **memory, long unsigned int block_id, long unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (c0000000009b20e0)
Location: drivers/base/memory.c:628
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
c0000000009b20e0-c0000000009b227c: init_memory_block (STB_LOCAL)
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
int init_memory_block(struct memory_block **memory, long unsigned int block_id, long unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816e3500)
Location: drivers/base/memory.c:628
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
ffffffff816e3500-ffffffff816e361e: init_memory_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int init_memory_block(struct memory_block **memory, long unsigned int block_id, long unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816bdb40)
Location: drivers/base/memory.c:628
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
ffffffff816bdb40-ffffffff816bdc5e: init_memory_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int init_memory_block(struct memory_block **memory, long unsigned int block_id, long unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81710690)
Location: drivers/base/memory.c:628
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
ffffffff81710690-ffffffff817107ae: init_memory_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int init_memory_block(struct memory_block **memory, long unsigned int block_id, long unsigned int state);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8172b7f0)
Location: drivers/base/memory.c:628
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
ffffffff8172b7f0-ffffffff8172b90e: init_memory_block (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int block_id</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mem_section *section</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct memory_block **memory</code>
</li>
<li>
<b>Param reordered. </b>
<code>memory, block_id, state</code> ➡️ <code>block_id, state</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int nr_vmemmap_pages</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct memory_group *group</code>
</li>
</ul>
</details>
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
