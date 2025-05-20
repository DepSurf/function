# Function: <code>duplicate_memory_bitmap</code>

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
In kernel/power/snapshot.c (ffffffff810d239a)
Location: kernel/power/snapshot.c:2039
Inline: True
Inline callers:
  - kernel/power/snapshot.c:snapshot_write_next
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810d54f0)
Location: kernel/power/snapshot.c:2105
Inline: True
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff810d54f0-ffffffff810d5564: duplicate_memory_bitmap.constprop.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810dc090)
Location: kernel/power/snapshot.c:2127
Inline: True
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff810dc090-ffffffff810dc104: duplicate_memory_bitmap.constprop.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810db200)
Location: kernel/power/snapshot.c:2128
Inline: True
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff810db200-ffffffff810db274: duplicate_memory_bitmap.constprop.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810e3270)
Location: kernel/power/snapshot.c:2129
Inline: True
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff810e3270-ffffffff810e32e4: duplicate_memory_bitmap.constprop.38 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810eb730)
Location: kernel/power/snapshot.c:2127
Inline: True
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff810eb730-ffffffff810eb7a4: duplicate_memory_bitmap.constprop.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810f6db0)
Location: kernel/power/snapshot.c:2128
Inline: True
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff810f6db0-ffffffff810f6e24: duplicate_memory_bitmap.constprop.40 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810ff300)
Location: kernel/power/snapshot.c:2135
Inline: True
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff810ff300-ffffffff810ff370: duplicate_memory_bitmap.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (ffffffff8110b760)
Location: kernel/power/snapshot.c:2142
Inline: True
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff8110b760-ffffffff8110b7d0: duplicate_memory_bitmap.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/power/snapshot.c (ffffffff811176cf)
Location: kernel/power/snapshot.c:2140
Inline: True
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
In kernel/power/snapshot.c (ffffffff81113b0f)
Location: kernel/power/snapshot.c:2182
Inline: True
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
In kernel/power/snapshot.c (ffffffff81114420)
Location: kernel/power/snapshot.c:2182
Inline: True
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
In kernel/power/snapshot.c (ffffffff81134560)
Location: kernel/power/snapshot.c:2175
Inline: True
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
In kernel/power/snapshot.c (ffffffff8115670c)
Location: kernel/power/snapshot.c:2179
Inline: True
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
In kernel/power/snapshot.c (ffffffff81186d2c)
Location: kernel/power/snapshot.c:2179
Inline: True
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
In kernel/power/snapshot.c (ffffffff81197e9c)
Location: kernel/power/snapshot.c:2231
Inline: True
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
In kernel/power/snapshot.c (ffffffff811a6b98)
Location: kernel/power/snapshot.c:2291
Inline: True
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
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (c03bdcf0)
Location: kernel/power/snapshot.c:2142
Inline: True
```
**Symbols:**

```
c03bdcf0-c03bdd64: duplicate_memory_bitmap.constprop.0 (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81103980)
Location: kernel/power/snapshot.c:2141
Inline: True
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff81103980-ffffffff811039f0: duplicate_memory_bitmap.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (ffffffff810f4c20)
Location: kernel/power/snapshot.c:2142
Inline: True
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff810f4c20-ffffffff810f4c90: duplicate_memory_bitmap.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (ffffffff81101c30)
Location: kernel/power/snapshot.c:2142
Inline: True
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff81101c30-ffffffff81101ca0: duplicate_memory_bitmap.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/power/snapshot.c (ffffffff8110d000)
Location: kernel/power/snapshot.c:2142
Inline: True
Direct callers:
  - kernel/power/snapshot.c:snapshot_write_next
  - kernel/power/snapshot.c:snapshot_write_next
```
**Symbols:**

```
ffffffff8110d000-ffffffff8110d070: duplicate_memory_bitmap.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
