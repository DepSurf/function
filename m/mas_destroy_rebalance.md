# Function: <code>mas_destroy_rebalance</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mas_destroy_rebalance(struct ma_state *mas, unsigned char end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/maple_tree.c (0)
Location: lib/maple_tree.c:3168
Inline: False
Direct callers:
  - lib/maple_tree.c:mas_destroy
```
**Symbols:**

```
ffffffff82030e80-ffffffff82032329: mas_destroy_rebalance (STB_LOCAL)
ffffffff820b7549-ffffffff820b75fb: mas_destroy_rebalance.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mas_destroy_rebalance(struct ma_state *mas, unsigned char end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/maple_tree.c (0)
Location: lib/maple_tree.c:3205
Inline: False
Direct callers:
  - lib/maple_tree.c:mas_destroy
```
**Symbols:**

```
ffffffff820aff90-ffffffff820b12ee: mas_destroy_rebalance (STB_LOCAL)
ffffffff821389e9-ffffffff82138b02: mas_destroy_rebalance.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mas_destroy_rebalance(struct ma_state *mas, unsigned char end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff82184240)
Location: lib/maple_tree.c:3017
Inline: False
Direct callers:
  - lib/maple_tree.c:mas_destroy
```
**Symbols:**

```
ffffffff82184240-ffffffff821854d2: mas_destroy_rebalance (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
