# Function: <code>find_first_swap</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int find_first_swap(dev_t *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812c9dd0)
Location: mm/swapfile.c:1842
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_swap_check
```
**Symbols:**

```
ffffffff812c9dd0-ffffffff812c9e50: find_first_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int find_first_swap(dev_t *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff812d0840)
Location: mm/swapfile.c:1841
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff812d0840-ffffffff812d08c0: find_first_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int find_first_swap(dev_t *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81315e70)
Location: mm/swapfile.c:1828
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff81315e70-ffffffff81315f16: find_first_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int find_first_swap(dev_t *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81381fe0)
Location: mm/swapfile.c:1703
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff81381fe0-ffffffff8138208d: find_first_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int find_first_swap(dev_t *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff814007c0)
Location: mm/swapfile.c:1690
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff814007c0-ffffffff8140086d: find_first_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int find_first_swap(dev_t *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff81433660)
Location: mm/swapfile.c:1672
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff81433660-ffffffff8143370d: find_first_swap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int find_first_swap(dev_t *device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swapfile.c (ffffffff8146ca50)
Location: mm/swapfile.c:1672
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff8146ca50-ffffffff8146cafd: find_first_swap (STB_GLOBAL)
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
