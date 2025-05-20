# Function: <code>free_unnecessary_pages</code>

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
In kernel/power/snapshot.c (ffffffff810d1938)
Location: kernel/power/snapshot.c:1456
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
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
In kernel/power/snapshot.c (ffffffff810d669a)
Location: kernel/power/snapshot.c:1558
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
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
In kernel/power/snapshot.c (ffffffff810dd20b)
Location: kernel/power/snapshot.c:1580
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
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
In kernel/power/snapshot.c (ffffffff810dc326)
Location: kernel/power/snapshot.c:1582
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
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
In kernel/power/snapshot.c (ffffffff810e4546)
Location: kernel/power/snapshot.c:1584
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
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
In kernel/power/snapshot.c (ffffffff810ed581)
Location: kernel/power/snapshot.c:1584
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
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
In kernel/power/snapshot.c (ffffffff810f8be6)
Location: kernel/power/snapshot.c:1585
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
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
In kernel/power/snapshot.c (ffffffff81101260)
Location: kernel/power/snapshot.c:1592
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
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
In kernel/power/snapshot.c (ffffffff8110d697)
Location: kernel/power/snapshot.c:1599
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int free_unnecessary_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811184e6)
Location: kernel/power/snapshot.c:1596
Inline: False
Direct callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
**Symbols:**

```
ffffffff811184e6-ffffffff811185e0: free_unnecessary_pages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int free_unnecessary_pages();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81bdf980)
Location: kernel/power/snapshot.c:1638
Inline: False
Direct callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
```
**Symbols:**

```
ffffffff81bdf980-ffffffff81bdfa7a: free_unnecessary_pages (STB_LOCAL)
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
In kernel/power/snapshot.c (ffffffff81bd1d07)
Location: kernel/power/snapshot.c:1638
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
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
In kernel/power/snapshot.c (ffffffff81caa9c1)
Location: kernel/power/snapshot.c:1631
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
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
In kernel/power/snapshot.c (ffffffff81e5ade3)
Location: kernel/power/snapshot.c:1635
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
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
In kernel/power/snapshot.c (ffffffff8118724e)
Location: kernel/power/snapshot.c:1635
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
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
In kernel/power/snapshot.c (ffffffff811983be)
Location: kernel/power/snapshot.c:1687
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
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
In kernel/power/snapshot.c (ffffffff811a7223)
Location: kernel/power/snapshot.c:1731
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
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
In kernel/power/snapshot.c (c03c0370)
Location: kernel/power/snapshot.c:1599
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
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
In kernel/power/snapshot.c (ffffffff811058b7)
Location: kernel/power/snapshot.c:1598
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
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
In kernel/power/snapshot.c (ffffffff810f6b57)
Location: kernel/power/snapshot.c:1599
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
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
In kernel/power/snapshot.c (ffffffff81103b67)
Location: kernel/power/snapshot.c:1599
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
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
In kernel/power/snapshot.c (ffffffff8110ef57)
Location: kernel/power/snapshot.c:1599
Inline: True
Inline callers:
  - kernel/power/snapshot.c:hibernate_preallocate_memory
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
