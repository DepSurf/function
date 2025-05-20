# Function: <code>swap_names</code>

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
In fs/dcache.c (ffffffff81224a9d)
Location: fs/dcache.c:2466
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff8124ca87)
Location: fs/dcache.c:2636
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff8125fa77)
Location: fs/dcache.c:2645
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff8126d38d)
Location: fs/dcache.c:2675
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff8128fcad)
Location: fs/dcache.c:2687
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff812b58e6)
Location: fs/dcache.c:2707
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff812cac04)
Location: fs/dcache.c:2661
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff812e7622)
Location: fs/dcache.c:2731
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff812f9194)
Location: fs/dcache.c:2731
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff81332135)
Location: fs/dcache.c:2752
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff8133db55)
Location: fs/dcache.c:2759
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff81343e53)
Location: fs/dcache.c:2786
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff81391783)
Location: fs/dcache.c:2787
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void swap_names(struct dentry *dentry, struct dentry *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81411500)
Location: fs/dcache.c:2812
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff81411500-ffffffff814115c1: swap_names (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void swap_names(struct dentry *dentry, struct dentry *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:2867
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff8149c6c0-ffffffff8149c82f: swap_names (STB_LOCAL)
ffffffff820688cb-ffffffff820688f5: swap_names.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void swap_names(struct dentry *dentry, struct dentry *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:2867
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff814d1a40-ffffffff814d1bb3: swap_names (STB_LOCAL)
ffffffff820e81e4-ffffffff820e820e: swap_names.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void swap_names(struct dentry *dentry, struct dentry *target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/dcache.c (0)
Location: fs/dcache.c:2691
Inline: False
Direct callers:
  - fs/dcache.c:__d_move
```
**Symbols:**

```
ffffffff81504410-ffffffff81504583: swap_names (STB_LOCAL)
ffffffff821c4f21-ffffffff821c4f4b: swap_names.cold (STB_LOCAL)
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
In fs/dcache.c (ffff8000103a856c)
Location: fs/dcache.c:2731
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (c0589300)
Location: fs/dcache.c:2731
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (c0000000004a1df8)
Location: fs/dcache.c:2731
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffe00026dcdc)
Location: fs/dcache.c:2731
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff812f1774)
Location: fs/dcache.c:2731
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff812e23a4)
Location: fs/dcache.c:2731
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff812ef584)
Location: fs/dcache.c:2731
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
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
In fs/dcache.c (ffffffff81300890)
Location: fs/dcache.c:2731
Inline: True
Inline callers:
  - fs/dcache.c:__d_move
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
