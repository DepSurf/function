# Function: <code>mark_swapfiles</code>

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
In kernel/power/swap.c (ffffffff810d530f)
Location: kernel/power/swap.c:294
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
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
In kernel/power/swap.c (ffffffff810da0b8)
Location: kernel/power/swap.c:306
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
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
In kernel/power/swap.c (ffffffff810e0b98)
Location: kernel/power/swap.c:306
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
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
In kernel/power/swap.c (ffffffff810dfd59)
Location: kernel/power/swap.c:306
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
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
In kernel/power/swap.c (ffffffff810e7fe9)
Location: kernel/power/swap.c:307
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
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
In kernel/power/swap.c (ffffffff810f047d)
Location: kernel/power/swap.c:307
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
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
In kernel/power/swap.c (ffffffff810fbb0b)
Location: kernel/power/swap.c:307
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
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
In kernel/power/swap.c (ffffffff811041ab)
Location: kernel/power/swap.c:305
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
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
In kernel/power/swap.c (ffffffff8111058f)
Location: kernel/power/swap.c:305
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mark_swapfiles(struct swap_map_handle *handle, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff811190e0)
Location: kernel/power/swap.c:305
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff811190e0-ffffffff811191e5: mark_swapfiles (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mark_swapfiles(struct swap_map_handle *handle, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81be000e)
Location: kernel/power/swap.c:316
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff81be000e-ffffffff81be0111: mark_swapfiles (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mark_swapfiles(struct swap_map_handle *handle, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81bd201b)
Location: kernel/power/swap.c:316
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff81bd201b-ffffffff81bd211e: mark_swapfiles (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mark_swapfiles(struct swap_map_handle *handle, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81caacce)
Location: kernel/power/swap.c:316
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff81caacce-ffffffff81caadd1: mark_swapfiles (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mark_swapfiles(struct swap_map_handle *handle, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81e5b102)
Location: kernel/power/swap.c:316
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff81e5b102-ffffffff81e5b223: mark_swapfiles (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mark_swapfiles(struct swap_map_handle *handle, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81188540)
Location: kernel/power/swap.c:315
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff81188540-ffffffff81188667: mark_swapfiles (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mark_swapfiles(struct swap_map_handle *handle, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81199700)
Location: kernel/power/swap.c:315
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff81199700-ffffffff81199827: mark_swapfiles (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mark_swapfiles(struct swap_map_handle *handle, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff811a8760)
Location: kernel/power/swap.c:316
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff811a8760-ffffffff811a8887: mark_swapfiles (STB_LOCAL)
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
In kernel/power/swap.c (c03c31e0)
Location: kernel/power/swap.c:305
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
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
In kernel/power/swap.c (ffffffff81108b52)
Location: kernel/power/swap.c:369
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
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
In kernel/power/swap.c (ffffffff810f9a4f)
Location: kernel/power/swap.c:305
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
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
In kernel/power/swap.c (ffffffff81106a5f)
Location: kernel/power/swap.c:305
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
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
In kernel/power/swap.c (ffffffff81111e1f)
Location: kernel/power/swap.c:305
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
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
