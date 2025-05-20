# Function: <code>crypto_exit_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void crypto_exit_ops(struct crypto_tfm *tfm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff8139c1e0)
Location: crypto/api.c:309
Inline: True
Direct callers:
  - crypto/api.c:crypto_create_tfm
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:__crypto_alloc_tfm
```
**Symbols:**

```
ffffffff8139c1e0-ffffffff8139c224: crypto_exit_ops (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void crypto_exit_ops(struct crypto_tfm *tfm);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In crypto/api.c (ffffffff813d90d0)
Location: crypto/api.c:309
Inline: True
Direct callers:
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_create_tfm
  - crypto/api.c:__crypto_alloc_tfm
```
**Symbols:**

```
ffffffff813d90d0-ffffffff813d9114: crypto_exit_ops (STB_LOCAL)
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
In crypto/api.c (ffffffff813f0df7)
Location: crypto/api.c:309
Inline: True
Inline callers:
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_create_tfm
  - crypto/api.c:__crypto_alloc_tfm
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
In crypto/api.c (ffffffff813fd02a)
Location: crypto/api.c:309
Inline: True
Inline callers:
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_create_tfm
  - crypto/api.c:__crypto_alloc_tfm
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
In crypto/api.c (ffffffff8142559a)
Location: crypto/api.c:310
Inline: True
Inline callers:
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_create_tfm
  - crypto/api.c:__crypto_alloc_tfm
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
In crypto/api.c (ffffffff814583da)
Location: crypto/api.c:319
Inline: True
Inline callers:
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_create_tfm
  - crypto/api.c:__crypto_alloc_tfm
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
In crypto/api.c (ffffffff81475a2a)
Location: crypto/api.c:319
Inline: True
Inline callers:
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_create_tfm
  - crypto/api.c:__crypto_alloc_tfm
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
In crypto/api.c (ffffffff814a390b)
Location: crypto/api.c:314
Inline: True
Inline callers:
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_create_tfm
  - crypto/api.c:__crypto_alloc_tfm
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
In crypto/api.c (ffffffff814be52b)
Location: crypto/api.c:316
Inline: True
Inline callers:
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_create_tfm
  - crypto/api.c:__crypto_alloc_tfm
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
In crypto/api.c (ffffffff8151eb47)
Location: crypto/api.c:303
Inline: True
Inline callers:
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_create_tfm
  - crypto/api.c:__crypto_alloc_tfm
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
In crypto/api.c (ffffffff8153b9a7)
Location: crypto/api.c:303
Inline: True
Inline callers:
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_create_tfm_node
  - crypto/api.c:__crypto_alloc_tfm
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
In crypto/api.c (ffffffff81544687)
Location: crypto/api.c:303
Inline: True
Inline callers:
  - crypto/api.c:crypto_create_tfm_node
  - crypto/api.c:__crypto_alloc_tfm
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
In crypto/api.c (ffffffff815a4e27)
Location: crypto/api.c:303
Inline: True
Inline callers:
  - crypto/api.c:crypto_create_tfm_node
  - crypto/api.c:__crypto_alloc_tfm
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
In crypto/api.c (ffffffff8164b2b3)
Location: crypto/api.c:358
Inline: True
Inline callers:
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_create_tfm_node
  - crypto/api.c:__crypto_alloc_tfm
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
In crypto/api.c (ffffffff817044d3)
Location: crypto/api.c:357
Inline: True
Inline callers:
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_create_tfm_node
  - crypto/api.c:__crypto_alloc_tfm
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
In crypto/api.c (ffffffff8173e88a)
Location: crypto/api.c:348
Inline: True
Inline callers:
  - crypto/api.c:crypto_create_tfm_node
  - crypto/api.c:__crypto_alloc_tfmgfp
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
In crypto/api.c (ffffffff8177f70a)
Location: crypto/api.c:348
Inline: True
Inline callers:
  - crypto/api.c:crypto_create_tfm_node
  - crypto/api.c:__crypto_alloc_tfmgfp
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
In crypto/api.c (ffff8000105b7334)
Location: crypto/api.c:316
Inline: True
Inline callers:
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_create_tfm
  - crypto/api.c:__crypto_alloc_tfm
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
In crypto/api.c (c0766210)
Location: crypto/api.c:316
Inline: True
Inline callers:
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_create_tfm
  - crypto/api.c:__crypto_alloc_tfm
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
In crypto/api.c (c00000000073bf68)
Location: crypto/api.c:316
Inline: True
Inline callers:
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_create_tfm
  - crypto/api.c:__crypto_alloc_tfm
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
In crypto/api.c (ffffffe0003fdd1e)
Location: crypto/api.c:316
Inline: True
Inline callers:
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_create_tfm
  - crypto/api.c:__crypto_alloc_tfm
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
In crypto/api.c (ffffffff814b6b0b)
Location: crypto/api.c:316
Inline: True
Inline callers:
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_create_tfm
  - crypto/api.c:__crypto_alloc_tfm
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
In crypto/api.c (ffffffff814a752b)
Location: crypto/api.c:316
Inline: True
Inline callers:
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_create_tfm
  - crypto/api.c:__crypto_alloc_tfm
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
In crypto/api.c (ffffffff814b2b9b)
Location: crypto/api.c:316
Inline: True
Inline callers:
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_create_tfm
  - crypto/api.c:__crypto_alloc_tfm
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
In crypto/api.c (ffffffff814cb61b)
Location: crypto/api.c:316
Inline: True
Inline callers:
  - crypto/api.c:crypto_destroy_tfm
  - crypto/api.c:crypto_create_tfm
  - crypto/api.c:__crypto_alloc_tfm
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
</ul>
