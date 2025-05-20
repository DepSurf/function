# Function: <code>__pcpu_chunk_move</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk *chunk, int slot, bool move_front);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8123cdb0)
Location: mm/percpu.c:525
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_chunk_relocate
```
**Symbols:**

```
ffffffff8123cdb0-ffffffff8123ce0c: __pcpu_chunk_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk *chunk, int slot, bool move_front);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8124b200)
Location: mm/percpu.c:525
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_chunk_relocate
```
**Symbols:**

```
ffffffff8124b200-ffffffff8124b25c: __pcpu_chunk_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk *chunk, int slot, bool move_front);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81279430)
Location: mm/percpu.c:499
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_chunk_relocate
```
**Symbols:**

```
ffffffff81279430-ffffffff81279489: __pcpu_chunk_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk *chunk, int slot, bool move_front);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81282e10)
Location: mm/percpu.c:505
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_chunk_relocate
```
**Symbols:**

```
ffffffff81282e10-ffffffff81282e81: __pcpu_chunk_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk *chunk, int slot, bool move_front);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81287f30)
Location: mm/percpu.c:506
Inline: False
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_chunk_relocate
```
**Symbols:**

```
ffffffff81287f30-ffffffff81287fa2: __pcpu_chunk_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk *chunk, int slot, bool move_front);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812c8320)
Location: mm/percpu.c:530
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_chunk_relocate
```
**Symbols:**

```
ffffffff812c8320-ffffffff812c8379: __pcpu_chunk_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk *chunk, int slot, bool move_front);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81325c30)
Location: mm/percpu.c:530
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_chunk_relocate
```
**Symbols:**

```
ffffffff81325c30-ffffffff81325ca5: __pcpu_chunk_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk *chunk, int slot, bool move_front);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8139a730)
Location: mm/percpu.c:526
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_chunk_relocate
```
**Symbols:**

```
ffffffff8139a730-ffffffff8139a7a5: __pcpu_chunk_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk *chunk, int slot, bool move_front);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813cd7c0)
Location: mm/percpu.c:526
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_chunk_relocate
```
**Symbols:**

```
ffffffff813cd7c0-ffffffff813cd835: __pcpu_chunk_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk *chunk, int slot, bool move_front);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff813f8130)
Location: mm/percpu.c:526
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_chunk_relocate
```
**Symbols:**

```
ffffffff813f8130-ffffffff813f81a5: __pcpu_chunk_move (STB_LOCAL)
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
In mm/percpu.c (ffff8000102e35b0)
Location: mm/percpu.c:525
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_chunk_relocate
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c050768c)
Location: mm/percpu.c:525
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_chunk_relocate
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (c0000000003a2ea4)
Location: mm/percpu.c:525
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_chunk_relocate
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffe0001f98f6)
Location: mm/percpu.c:525
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_chunk_relocate
  - mm/percpu.c:pcpu_chunk_relocate
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk *chunk, int slot, bool move_front);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81243850)
Location: mm/percpu.c:525
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_chunk_relocate
```
**Symbols:**

```
ffffffff81243850-ffffffff812438ac: __pcpu_chunk_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk *chunk, int slot, bool move_front);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81236820)
Location: mm/percpu.c:525
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_chunk_relocate
```
**Symbols:**

```
ffffffff81236820-ffffffff8123687c: __pcpu_chunk_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk *chunk, int slot, bool move_front);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff812415f0)
Location: mm/percpu.c:525
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_chunk_relocate
```
**Symbols:**

```
ffffffff812415f0-ffffffff8124164c: __pcpu_chunk_move (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __pcpu_chunk_move(struct pcpu_chunk *chunk, int slot, bool move_front);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff81250d70)
Location: mm/percpu.c:525
Inline: True
Direct callers:
  - mm/percpu.c:pcpu_alloc
  - mm/percpu.c:pcpu_chunk_relocate
```
**Symbols:**

```
ffffffff81250d70-ffffffff81250dcc: __pcpu_chunk_move (STB_LOCAL)
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
