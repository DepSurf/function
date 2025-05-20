# Function: <code>get_swap_writer</code>

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
In kernel/power/swap.c (ffffffff810d50ab)
Location: kernel/power/swap.c:391
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
In kernel/power/swap.c (ffffffff810d9ebb)
Location: kernel/power/swap.c:410
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
In kernel/power/swap.c (ffffffff810e099b)
Location: kernel/power/swap.c:410
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
In kernel/power/swap.c (ffffffff810dfaeb)
Location: kernel/power/swap.c:410
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
In kernel/power/swap.c (ffffffff810e7d7b)
Location: kernel/power/swap.c:411
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
In kernel/power/swap.c (ffffffff810ef1d2)
Location: kernel/power/swap.c:411
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
In kernel/power/swap.c (ffffffff810fa862)
Location: kernel/power/swap.c:411
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
In kernel/power/swap.c (ffffffff81102ef1)
Location: kernel/power/swap.c:409
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
In kernel/power/swap.c (ffffffff8110f341)
Location: kernel/power/swap.c:409
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int get_swap_writer(struct swap_map_handle *handle);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/power/swap.c (0)
Location: kernel/power/swap.c:409
Inline: False
Direct callers:
  - kernel/power/swap.c:swsusp_write
```
**Symbols:**

```
ffffffff8111a500-ffffffff8111a647: get_swap_writer (STB_LOCAL)
ffffffff8111b7a8-ffffffff8111b7b9: get_swap_writer.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/swap.c (ffffffff81115f7e)
Location: kernel/power/swap.c:417
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
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
In kernel/power/swap.c (ffffffff81116674)
Location: kernel/power/swap.c:417
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
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
In kernel/power/swap.c (ffffffff81136924)
Location: kernel/power/swap.c:417
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
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
In kernel/power/swap.c (ffffffff81158e5d)
Location: kernel/power/swap.c:421
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
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
In kernel/power/swap.c (ffffffff8118afdd)
Location: kernel/power/swap.c:419
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
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
In kernel/power/swap.c (ffffffff8119c72d)
Location: kernel/power/swap.c:419
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
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
In kernel/power/swap.c (ffffffff811ab87d)
Location: kernel/power/swap.c:420
Inline: True
Inline callers:
  - kernel/power/swap.c:swsusp_write
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
In kernel/power/swap.c (c03c2eb8)
Location: kernel/power/swap.c:409
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
In kernel/power/swap.c (ffffffff811078e1)
Location: kernel/power/swap.c:488
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
In kernel/power/swap.c (ffffffff810f8801)
Location: kernel/power/swap.c:409
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
In kernel/power/swap.c (ffffffff81105811)
Location: kernel/power/swap.c:409
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
In kernel/power/swap.c (ffffffff81110bf1)
Location: kernel/power/swap.c:409
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
</ul>
