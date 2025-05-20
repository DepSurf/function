# Function: <code>get_memory_block_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int get_memory_block_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81561770)
Location: drivers/base/memory.c:91
Inline: False
Direct callers:
  - drivers/base/memory.c:print_block_size
  - drivers/base/memory.c:memory_dev_init
```
**Symbols:**

```
ffffffff81561770-ffffffff815617a7: get_memory_block_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int get_memory_block_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff815b6000)
Location: drivers/base/memory.c:91
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:print_block_size
```
**Symbols:**

```
ffffffff815b6000-ffffffff815b6037: get_memory_block_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int get_memory_block_size();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff815e5320)
Location: drivers/base/memory.c:91
Inline: False
Direct callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:print_block_size
```
**Symbols:**

```
ffffffff815e5320-ffffffff815e5357: get_memory_block_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long unsigned int get_memory_block_size();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff815f9e10)
Location: drivers/base/memory.c:91
Inline: True
Direct callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:print_block_size
```
**Symbols:**

```
ffffffff815f9e10-ffffffff815f9e3a: get_memory_block_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long unsigned int get_memory_block_size();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff81661fb0)
Location: drivers/base/memory.c:92
Inline: True
Direct callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:print_block_size
```
**Symbols:**

```
ffffffff81661fb0-ffffffff81661fda: get_memory_block_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long unsigned int get_memory_block_size();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8169d780)
Location: drivers/base/memory.c:92
Inline: True
Direct callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:print_block_size
```
**Symbols:**

```
ffffffff8169d780-ffffffff8169d7aa: get_memory_block_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long unsigned int get_memory_block_size();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816bdf20)
Location: drivers/base/memory.c:92
Inline: True
Direct callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:block_size_bytes_show
```
**Symbols:**

```
ffffffff816bdf20-ffffffff816bdf4a: get_memory_block_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int get_memory_block_size();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/memory.c (ffffffff816f92d1)
Location: drivers/base/memory.c:103
Inline: True
Direct callers:
  - drivers/base/memory.c:memory_dev_init
  - drivers/base/memory.c:block_size_bytes_show
```
**Symbols:**

```
ffffffff816f87d0-ffffffff816f87f9: get_memory_block_size (STB_LOCAL)
ffffffff816f92d1-ffffffff816f92e9: get_memory_block_size.cold (STB_LOCAL)
```
</details>
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
</ul>
