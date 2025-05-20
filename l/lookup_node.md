# Function: <code>lookup_node</code>

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
In mm/mempolicy.c (ffffffff811e10e2)
Location: mm/mempolicy.c:816
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
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
In mm/mempolicy.c (ffffffff811ffa98)
Location: mm/mempolicy.c:848
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
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
In mm/mempolicy.c (ffffffff8121133d)
Location: mm/mempolicy.c:850
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_get_mempolicy
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
In mm/mempolicy.c (ffffffff8121cc7c)
Location: mm/mempolicy.c:783
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_get_mempolicy
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
In mm/mempolicy.c (ffffffff81237e2c)
Location: mm/mempolicy.c:825
Inline: True
Inline callers:
  - mm/mempolicy.c:SYSC_get_mempolicy
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
In mm/mempolicy.c (ffffffff8125b329)
Location: mm/mempolicy.c:800
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
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
In mm/mempolicy.c (ffffffff8126fad6)
Location: mm/mempolicy.c:826
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
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
In mm/mempolicy.c (ffffffff8128b0d6)
Location: mm/mempolicy.c:853
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
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
In mm/mempolicy.c (ffffffff8129ac46)
Location: mm/mempolicy.c:854
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int lookup_node(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812cb8f0)
Location: mm/mempolicy.c:923
Inline: False
Direct callers:
  - mm/mempolicy.c:do_get_mempolicy
```
**Symbols:**

```
ffffffff812cb8f0-ffffffff812cb9d6: lookup_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int lookup_node(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff812d7fb0)
Location: mm/mempolicy.c:922
Inline: False
Direct callers:
  - mm/mempolicy.c:do_get_mempolicy
```
**Symbols:**

```
ffffffff812d7fb0-ffffffff812d80b1: lookup_node (STB_LOCAL)
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
In mm/mempolicy.c (ffffffff812e06a8)
Location: mm/mempolicy.c:932
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int lookup_node(struct mm_struct *mm, long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81326d40)
Location: mm/mempolicy.c:903
Inline: False
Direct callers:
  - mm/mempolicy.c:do_get_mempolicy
```
**Symbols:**

```
ffffffff81326d40-ffffffff81326e2e: lookup_node (STB_LOCAL)
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
In mm/mempolicy.c (ffffffff81396bc1)
Location: mm/mempolicy.c:902
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
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
In mm/mempolicy.c (ffffffff81416751)
Location: mm/mempolicy.c:916
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
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
In mm/mempolicy.c (ffffffff81449c5e)
Location: mm/mempolicy.c:921
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
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
In mm/mempolicy.c (ffffffff814836de)
Location: mm/mempolicy.c:875
Inline: True
Inline callers:
  - mm/mempolicy.c:do_get_mempolicy
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
In mm/mempolicy.c (ffff800010339a40)
Location: mm/mempolicy.c:854
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
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
In mm/mempolicy.c (c000000000413fc0)
Location: mm/mempolicy.c:854
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
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
In mm/mempolicy.c (ffffffff81293226)
Location: mm/mempolicy.c:854
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
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
In mm/mempolicy.c (ffffffff81284e36)
Location: mm/mempolicy.c:854
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
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
In mm/mempolicy.c (ffffffff81291036)
Location: mm/mempolicy.c:854
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
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
In mm/mempolicy.c (ffffffff812a0e4c)
Location: mm/mempolicy.c:854
Inline: True
Inline callers:
  - mm/mempolicy.c:kernel_get_mempolicy
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
