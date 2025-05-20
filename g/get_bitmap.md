# Function: <code>get_bitmap</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int get_bitmap(long unsigned int *mask, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81326ae0)
Location: mm/mempolicy.c:1355
Inline: False
Direct callers:
  - mm/mempolicy.c:get_nodes
  - mm/mempolicy.c:get_nodes
```
**Symbols:**

```
ffffffff81326ae0-ffffffff81326b7e: get_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int get_bitmap(long unsigned int *mask, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81396155)
Location: mm/mempolicy.c:1348
Inline: True
Inline callers:
  - mm/mempolicy.c:get_nodes
Direct callers:
  - mm/mempolicy.c:get_nodes
```
**Symbols:**

```
ffffffff81395060-ffffffff813950f4: get_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int get_bitmap(long unsigned int *mask, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81415bd5)
Location: mm/mempolicy.c:1363
Inline: True
Inline callers:
  - mm/mempolicy.c:get_nodes
Direct callers:
  - mm/mempolicy.c:get_nodes
```
**Symbols:**

```
ffffffff81414a80-ffffffff81414b14: get_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int get_bitmap(long unsigned int *mask, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81449035)
Location: mm/mempolicy.c:1380
Inline: True
Inline callers:
  - mm/mempolicy.c:get_nodes
Direct callers:
  - mm/mempolicy.c:get_nodes
```
**Symbols:**

```
ffffffff81448040-ffffffff814480d4: get_bitmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int get_bitmap(long unsigned int *mask, const long unsigned int *nmask, long unsigned int maxnode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81482a05)
Location: mm/mempolicy.c:1364
Inline: True
Inline callers:
  - mm/mempolicy.c:get_nodes
Direct callers:
  - mm/mempolicy.c:get_nodes
```
**Symbols:**

```
ffffffff81481a40-ffffffff81481ad4: get_bitmap (STB_LOCAL)
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
