# Function: <code>validate_slab_node</code>

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
In mm/slub.c (ffffffff811ecf54)
Location: mm/slub.c:4123
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff8120c6b4)
Location: mm/slub.c:4350
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff8121e714)
Location: mm/slub.c:4319
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff8122a2a4)
Location: mm/slub.c:4361
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff81245454)
Location: mm/slub.c:4377
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff8126955b)
Location: mm/slub.c:4379
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff8127c633)
Location: mm/slub.c:4431
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff81298205)
Location: mm/slub.c:4422
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff812a8065)
Location: mm/slub.c:4440
Inline: True
Inline callers:
  - mm/slub.c:validate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int validate_slab_node(struct kmem_cache *s, struct kmem_cache_node *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:4509
Inline: False
Direct callers:
  - mm/slub.c:validate_store
```
**Symbols:**

```
ffffffff812dd400-ffffffff812dd4cb: validate_slab_node (STB_LOCAL)
ffffffff812e0125-ffffffff812e015b: validate_slab_node.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int validate_slab_node(struct kmem_cache *s, struct kmem_cache_node *n);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:4558
Inline: False
Direct callers:
  - mm/slub.c:validate_store
```
**Symbols:**

```
ffffffff812e61f0-ffffffff812e62bb: validate_slab_node (STB_LOCAL)
ffffffff81be97f0-ffffffff81be9826: validate_slab_node.cold (STB_LOCAL)
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
In mm/slub.c (ffffffff812eda0c)
Location: mm/slub.c:4639
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff81335d87)
Location: mm/slub.c:4995
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_cache
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
In mm/slub.c (ffffffff813a75a7)
Location: mm/slub.c:5027
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_cache
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
In mm/slub.c (ffffffff8142b3d7)
Location: mm/slub.c:5143
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_cache
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
In mm/slub.c (ffffffff81460934)
Location: mm/slub.c:5158
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_cache
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
In mm/slub.c (ffffffff814588f4)
Location: mm/slub.c:5769
Inline: True
Inline callers:
  - mm/slub.c:validate_slab_cache
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
In mm/slub.c (ffff8000103496bc)
Location: mm/slub.c:4440
Inline: True
Inline callers:
  - mm/slub.c:validate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (c054d820)
Location: mm/slub.c:4440
Inline: True
Inline callers:
  - mm/slub.c:validate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (c0000000004283c4)
Location: mm/slub.c:4440
Inline: True
Inline callers:
  - mm/slub.c:validate_store
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffe00023b3a8)
Location: mm/slub.c:4440
Inline: True
Inline callers:
  - mm/slub.c:validate_store
```
</details>
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
In mm/slub.c (ffffffff812a0645)
Location: mm/slub.c:4440
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff81292155)
Location: mm/slub.c:4440
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff8129e455)
Location: mm/slub.c:4440
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
In mm/slub.c (ffffffff812ae505)
Location: mm/slub.c:4440
Inline: True
Inline callers:
  - mm/slub.c:validate_store
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
