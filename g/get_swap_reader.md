# Function: <code>get_swap_reader</code>

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
In kernel/power/swap.c (ffffffff810d4d19)
Location: kernel/power/swap.c:949
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_read
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
In kernel/power/swap.c (ffffffff810d9b3a)
Location: kernel/power/swap.c:968
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_read
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
In kernel/power/swap.c (ffffffff810e061a)
Location: kernel/power/swap.c:968
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_read
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
In kernel/power/swap.c (ffffffff810df77a)
Location: kernel/power/swap.c:968
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_read
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
In kernel/power/swap.c (ffffffff810e7a0a)
Location: kernel/power/swap.c:963
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_read
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
In kernel/power/swap.c (ffffffff810eee3f)
Location: kernel/power/swap.c:963
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_read
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
In kernel/power/swap.c (ffffffff810fa4e7)
Location: kernel/power/swap.c:963
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_read
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
In kernel/power/swap.c (ffffffff81102b9e)
Location: kernel/power/swap.c:961
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_read
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
In kernel/power/swap.c (ffffffff8110efee)
Location: kernel/power/swap.c:961
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_read
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_swap_reader(struct swap_map_handle *handle, unsigned int *flags_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81119990)
Location: kernel/power/swap.c:961
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
```
**Symbols:**

```
ffffffff81119990-ffffffff81119b53: get_swap_reader (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_swap_reader(struct swap_map_handle *handle, unsigned int *flags_p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff811153a0)
Location: kernel/power/swap.c:971
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_read
```
**Symbols:**

```
ffffffff811153a0-ffffffff81115563: get_swap_reader (STB_LOCAL)
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
In kernel/power/swap.c (ffffffff8111624e)
Location: kernel/power/swap.c:971
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_read
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
In kernel/power/swap.c (ffffffff811364ee)
Location: kernel/power/swap.c:971
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_read
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
In kernel/power/swap.c (ffffffff811589bc)
Location: kernel/power/swap.c:972
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_read
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
In kernel/power/swap.c (ffffffff8118ab09)
Location: kernel/power/swap.c:970
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_read
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
In kernel/power/swap.c (ffffffff8119c269)
Location: kernel/power/swap.c:970
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_read
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
In kernel/power/swap.c (ffffffff811ab3b1)
Location: kernel/power/swap.c:971
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_read
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
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (c03c2974)
Location: kernel/power/swap.c:961
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_read
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff8110757e)
Location: kernel/power/swap.c:1028
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_read
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
In kernel/power/swap.c (ffffffff810f84ae)
Location: kernel/power/swap.c:961
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_read
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
In kernel/power/swap.c (ffffffff811054be)
Location: kernel/power/swap.c:961
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_read
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
In kernel/power/swap.c (ffffffff8111089e)
Location: kernel/power/swap.c:961
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_read
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
