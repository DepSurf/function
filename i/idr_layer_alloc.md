# Function: <code>idr_layer_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct idr_layer *idr_layer_alloc(gfp_t gfp_mask, struct idr *layer_idr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff813ea5d0)
Location: lib/idr.c:94
Inline: True
Direct callers:
  - lib/idr.c:idr_get_empty_slot
  - lib/idr.c:idr_get_empty_slot
  - lib/idr.c:idr_get_empty_slot
```
**Symbols:**

```
ffffffff813ea5d0-ffffffff813ea64e: idr_layer_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct idr_layer *idr_layer_alloc(gfp_t gfp_mask, struct idr *layer_idr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff81430980)
Location: lib/idr.c:94
Inline: True
Direct callers:
  - lib/idr.c:idr_get_empty_slot
  - lib/idr.c:idr_get_empty_slot
  - lib/idr.c:idr_get_empty_slot
```
**Symbols:**

```
ffffffff81430980-ffffffff81430a01: idr_layer_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct idr_layer *idr_layer_alloc(gfp_t gfp_mask, struct idr *layer_idr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/idr.c (ffffffff8144cb50)
Location: lib/idr.c:94
Inline: True
Direct callers:
  - lib/idr.c:idr_get_empty_slot
  - lib/idr.c:idr_get_empty_slot
  - lib/idr.c:idr_get_empty_slot
```
**Symbols:**

```
ffffffff8144cb50-ffffffff8144cbd1: idr_layer_alloc (STB_LOCAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
