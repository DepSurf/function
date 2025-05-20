# Function: <code>ptdump_hole</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ptdump_hole(long unsigned int addr, long unsigned int next, int depth, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ptdump.c (ffffffff8130cba0)
Location: mm/ptdump.c:121
Inline: False
```
**Symbols:**

```
ffffffff8130cba0-ffffffff8130cbbe: ptdump_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ptdump_hole(long unsigned int addr, long unsigned int next, int depth, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ptdump.c (ffffffff81318ae0)
Location: mm/ptdump.c:124
Inline: False
```
**Symbols:**

```
ffffffff81318ae0-ffffffff81318afe: ptdump_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ptdump_hole(long unsigned int addr, long unsigned int next, int depth, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ptdump.c (ffffffff8131ecd0)
Location: mm/ptdump.c:124
Inline: False
```
**Symbols:**

```
ffffffff8131ecd0-ffffffff8131ecee: ptdump_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ptdump_hole(long unsigned int addr, long unsigned int next, int depth, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ptdump.c (ffffffff8136c0b0)
Location: mm/ptdump.c:124
Inline: False
```
**Symbols:**

```
ffffffff8136c0b0-ffffffff8136c0ce: ptdump_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ptdump_hole(long unsigned int addr, long unsigned int next, int depth, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ptdump.c (ffffffff813ea320)
Location: mm/ptdump.c:132
Inline: False
```
**Symbols:**

```
ffffffff813ea320-ffffffff813ea34a: ptdump_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ptdump_hole(long unsigned int addr, long unsigned int next, int depth, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ptdump.c (ffffffff81472400)
Location: mm/ptdump.c:132
Inline: False
```
**Symbols:**

```
ffffffff81472400-ffffffff8147242a: ptdump_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ptdump_hole(long unsigned int addr, long unsigned int next, int depth, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ptdump.c (ffffffff814a6b60)
Location: mm/ptdump.c:132
Inline: False
```
**Symbols:**

```
ffffffff814a6b60-ffffffff814a6b8a: ptdump_hole (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ptdump_hole(long unsigned int addr, long unsigned int next, int depth, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ptdump.c (ffffffff814d7b60)
Location: mm/ptdump.c:132
Inline: False
```
**Symbols:**

```
ffffffff814d7b60-ffffffff814d7b8a: ptdump_hole (STB_LOCAL)
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
