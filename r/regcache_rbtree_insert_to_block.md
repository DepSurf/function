# Function: <code>regcache_rbtree_insert_to_block</code>

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
In drivers/base/regmap/regcache-rbtree.c (ffffffff81568a5f)
Location: drivers/base/regmap/regcache-rbtree.c:277
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
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
In drivers/base/regmap/regcache-rbtree.c (ffffffff815bd623)
Location: drivers/base/regmap/regcache-rbtree.c:277
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
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
In drivers/base/regmap/regcache-rbtree.c (ffffffff815eca33)
Location: drivers/base/regmap/regcache-rbtree.c:277
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
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
In drivers/base/regmap/regcache-rbtree.c (ffffffff81601281)
Location: drivers/base/regmap/regcache-rbtree.c:276
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
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
In drivers/base/regmap/regcache-rbtree.c (ffffffff81669601)
Location: drivers/base/regmap/regcache-rbtree.c:276
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
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
In drivers/base/regmap/regcache-rbtree.c (ffffffff816a4fbf)
Location: drivers/base/regmap/regcache-rbtree.c:276
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
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
In drivers/base/regmap/regcache-rbtree.c (ffffffff816c5b02)
Location: drivers/base/regmap/regcache-rbtree.c:266
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
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
In drivers/base/regmap/regcache-rbtree.c (ffffffff81700c4f)
Location: drivers/base/regmap/regcache-rbtree.c:262
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
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
In drivers/base/regmap/regcache-rbtree.c (ffffffff81724f9f)
Location: drivers/base/regmap/regcache-rbtree.c:262
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int regcache_rbtree_insert_to_block(struct regmap *map, struct regcache_rbtree_node *rbnode, unsigned int base_reg, unsigned int top_reg, unsigned int reg, unsigned int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache-rbtree.c (ffffffff817e0f20)
Location: drivers/base/regmap/regcache-rbtree.c:262
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
**Symbols:**

```
ffffffff817e0f20-ffffffff817e10ba: regcache_rbtree_insert_to_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int regcache_rbtree_insert_to_block(struct regmap *map, struct regcache_rbtree_node *rbnode, unsigned int base_reg, unsigned int top_reg, unsigned int reg, unsigned int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache-rbtree.c (ffffffff817f5c70)
Location: drivers/base/regmap/regcache-rbtree.c:262
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
**Symbols:**

```
ffffffff817f5c70-ffffffff817f5e0a: regcache_rbtree_insert_to_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int regcache_rbtree_insert_to_block(struct regmap *map, struct regcache_rbtree_node *rbnode, unsigned int base_reg, unsigned int top_reg, unsigned int reg, unsigned int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache-rbtree.c (ffffffff817da420)
Location: drivers/base/regmap/regcache-rbtree.c:262
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
**Symbols:**

```
ffffffff817da420-ffffffff817da5b5: regcache_rbtree_insert_to_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int regcache_rbtree_insert_to_block(struct regmap *map, struct regcache_rbtree_node *rbnode, unsigned int base_reg, unsigned int top_reg, unsigned int reg, unsigned int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81865c60)
Location: drivers/base/regmap/regcache-rbtree.c:262
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
**Symbols:**

```
ffffffff81865c60-ffffffff81865dd6: regcache_rbtree_insert_to_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int regcache_rbtree_insert_to_block(struct regmap *map, struct regcache_rbtree_node *rbnode, unsigned int base_reg, unsigned int top_reg, unsigned int reg, unsigned int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache-rbtree.c (ffffffff819ae130)
Location: drivers/base/regmap/regcache-rbtree.c:262
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
**Symbols:**

```
ffffffff819ae130-ffffffff819ae2c1: regcache_rbtree_insert_to_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int regcache_rbtree_insert_to_block(struct regmap *map, struct regcache_rbtree_node *rbnode, unsigned int base_reg, unsigned int top_reg, unsigned int reg, unsigned int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81b21e40)
Location: drivers/base/regmap/regcache-rbtree.c:262
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
**Symbols:**

```
ffffffff81b21e40-ffffffff81b21fd1: regcache_rbtree_insert_to_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int regcache_rbtree_insert_to_block(struct regmap *map, struct regcache_rbtree_node *rbnode, unsigned int base_reg, unsigned int top_reg, unsigned int reg, unsigned int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81b710e0)
Location: drivers/base/regmap/regcache-rbtree.c:262
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
**Symbols:**

```
ffffffff81b710e0-ffffffff81b712ae: regcache_rbtree_insert_to_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int regcache_rbtree_insert_to_block(struct regmap *map, struct regcache_rbtree_node *rbnode, unsigned int base_reg, unsigned int top_reg, unsigned int reg, unsigned int value);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/regmap/regcache-rbtree.c (ffffffff81bc4de0)
Location: drivers/base/regmap/regcache-rbtree.c:262
Inline: False
Direct callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
```
**Symbols:**

```
ffffffff81bc4de0-ffffffff81bc4fae: regcache_rbtree_insert_to_block (STB_LOCAL)
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
In drivers/base/regmap/regcache-rbtree.c (ffff800010919c8c)
Location: drivers/base/regmap/regcache-rbtree.c:262
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
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
In drivers/base/regmap/regcache-rbtree.c (c09ff8a8)
Location: drivers/base/regmap/regcache-rbtree.c:262
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
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
In drivers/base/regmap/regcache-rbtree.c (c0000000009bdbb4)
Location: drivers/base/regmap/regcache-rbtree.c:262
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
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
In drivers/base/regmap/regcache-rbtree.c (ffffffe000599dc4)
Location: drivers/base/regmap/regcache-rbtree.c:262
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
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
In drivers/base/regmap/regcache-rbtree.c (ffffffff816eb2cf)
Location: drivers/base/regmap/regcache-rbtree.c:262
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
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
In drivers/base/regmap/regcache-rbtree.c (ffffffff816c590f)
Location: drivers/base/regmap/regcache-rbtree.c:262
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
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
In drivers/base/regmap/regcache-rbtree.c (ffffffff8171845f)
Location: drivers/base/regmap/regcache-rbtree.c:262
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
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
In drivers/base/regmap/regcache-rbtree.c (ffffffff817337bf)
Location: drivers/base/regmap/regcache-rbtree.c:262
Inline: True
Inline callers:
  - drivers/base/regmap/regcache-rbtree.c:regcache_rbtree_write
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
