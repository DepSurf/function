# Function: <code>mt_destroy_walk</code>

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
<summary>In <code>6.2</code>: ✅</summary>

```c
void mt_destroy_walk(struct maple_enode *enode, unsigned char ma_flags, bool free);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/maple_tree.c (ffffffff82027c20)
Location: lib/maple_tree.c:5531
Inline: False
Direct callers:
  - lib/maple_tree.c:mtree_destroy
  - lib/maple_tree.c:mtree_destroy
```
**Symbols:**

```
ffffffff82027c20-ffffffff820280c8: mt_destroy_walk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/maple_tree.c (ffffffff820a7f00)
Location: lib/maple_tree.c:5365
Inline: True
Direct callers:
  - lib/maple_tree.c:mtree_destroy
  - lib/maple_tree.c:mtree_destroy
  - lib/maple_tree.c:mas_wmb_replace
  - lib/maple_tree.c:mas_wmb_replace
```
**Symbols:**

```
ffffffff820a7f00-ffffffff820a838c: mt_destroy_walk.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/maple_tree.c (ffffffff82180e60)
Location: lib/maple_tree.c:5242
Inline: True
Direct callers:
  - lib/maple_tree.c:mtree_destroy
  - lib/maple_tree.c:mtree_destroy
  - lib/maple_tree.c:mas_topiary_replace
```
**Symbols:**

```
ffffffff82180e60-ffffffff821812e2: mt_destroy_walk.isra.0 (STB_LOCAL)
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
</ul>
