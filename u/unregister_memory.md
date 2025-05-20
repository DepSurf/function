# Function: <code>unregister_memory</code>

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
In drivers/base/memory.c (ffffffff81561add)
Location: drivers/base/memory.c:686
Inline: True
Inline callers:
  - drivers/base/memory.c:unregister_memory_section
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
In drivers/base/memory.c (ffffffff815b63c7)
Location: drivers/base/memory.c:729
Inline: True
Inline callers:
  - drivers/base/memory.c:unregister_memory_section
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
In drivers/base/memory.c (ffffffff815e56e7)
Location: drivers/base/memory.c:730
Inline: True
Inline callers:
  - drivers/base/memory.c:unregister_memory_section
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
In drivers/base/memory.c (ffffffff815fa177)
Location: drivers/base/memory.c:727
Inline: True
Inline callers:
  - drivers/base/memory.c:unregister_memory_section
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
In drivers/base/memory.c (ffffffff81662317)
Location: drivers/base/memory.c:738
Inline: True
Inline callers:
  - drivers/base/memory.c:unregister_memory_section
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
In drivers/base/memory.c (ffffffff8169dae2)
Location: drivers/base/memory.c:746
Inline: True
Inline callers:
  - drivers/base/memory.c:unregister_memory_section
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
In drivers/base/memory.c (ffffffff816be252)
Location: drivers/base/memory.c:731
Inline: True
Inline callers:
  - drivers/base/memory.c:unregister_memory_section
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void unregister_memory(struct memory_block *memory);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816f8530)
Location: drivers/base/memory.c:705
Inline: False
Direct callers:
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
ffffffff816f8530-ffffffff816f8563: unregister_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void unregister_memory(struct memory_block *memory);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8171c910)
Location: drivers/base/memory.c:677
Inline: False
Direct callers:
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
ffffffff8171c910-ffffffff8171c943: unregister_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void unregister_memory(struct memory_block *memory);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817d8a20)
Location: drivers/base/memory.c:618
Inline: False
Direct callers:
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
ffffffff817d8a20-ffffffff817d8a70: unregister_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void unregister_memory(struct memory_block *memory);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817ed3c0)
Location: drivers/base/memory.c:609
Inline: False
Direct callers:
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
ffffffff817ed3c0-ffffffff817ed410: unregister_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void unregister_memory(struct memory_block *memory);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff817d1c50)
Location: drivers/base/memory.c:677
Inline: False
Direct callers:
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
ffffffff817d1c50-ffffffff817d1ca0: unregister_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void unregister_memory(struct memory_block *memory);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8185ca40)
Location: drivers/base/memory.c:692
Inline: False
Direct callers:
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
ffffffff8185ca40-ffffffff8185cae0: unregister_memory (STB_LOCAL)
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
void unregister_memory(struct memory_block *memory);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffff800010910658)
Location: drivers/base/memory.c:677
Inline: False
Direct callers:
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
ffff800010910658-ffff8000109106b8: unregister_memory (STB_LOCAL)
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
void unregister_memory(struct memory_block *memory);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (c0000000009b1420)
Location: drivers/base/memory.c:677
Inline: False
Direct callers:
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
c0000000009b1420-c0000000009b1488: unregister_memory (STB_LOCAL)
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
void unregister_memory(struct memory_block *memory);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816e2c40)
Location: drivers/base/memory.c:677
Inline: False
Direct callers:
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
ffffffff816e2c40-ffffffff816e2c73: unregister_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void unregister_memory(struct memory_block *memory);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff816bd280)
Location: drivers/base/memory.c:677
Inline: False
Direct callers:
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
ffffffff816bd280-ffffffff816bd2b3: unregister_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void unregister_memory(struct memory_block *memory);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8170fdd0)
Location: drivers/base/memory.c:677
Inline: False
Direct callers:
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
ffffffff8170fdd0-ffffffff8170fe03: unregister_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void unregister_memory(struct memory_block *memory);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/memory.c (ffffffff8172af30)
Location: drivers/base/memory.c:677
Inline: False
Direct callers:
  - drivers/base/memory.c:remove_memory_block_devices
  - drivers/base/memory.c:create_memory_block_devices
```
**Symbols:**

```
ffffffff8172af30-ffffffff8172af63: unregister_memory (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
