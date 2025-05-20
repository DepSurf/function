# Function: <code>assoc_array_destroy_subtree</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void assoc_array_destroy_subtree(struct assoc_array_ptr *root, const struct assoc_array_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff81404ec0)
Location: lib/assoc_array.c:360
Inline: False
Direct callers:
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
  - lib/assoc_array.c:assoc_array_gc
```
**Symbols:**

```
ffffffff81404ec0-ffffffff81404fef: assoc_array_destroy_subtree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void assoc_array_destroy_subtree(struct assoc_array_ptr *root, const struct assoc_array_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff8144ca60)
Location: lib/assoc_array.c:360
Inline: False
Direct callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
```
**Symbols:**

```
ffffffff8144ca60-ffffffff8144cb99: assoc_array_destroy_subtree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void assoc_array_destroy_subtree(struct assoc_array_ptr *root, const struct assoc_array_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff8146b420)
Location: lib/assoc_array.c:360
Inline: False
Direct callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
```
**Symbols:**

```
ffffffff8146b420-ffffffff8146b559: assoc_array_destroy_subtree (STB_LOCAL)
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
In lib/assoc_array.c (ffffffff814723bc)
Location: lib/assoc_array.c:360
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
Direct callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
```
**Symbols:**

```
ffffffff81470cf0-ffffffff81470e2c: assoc_array_destroy_subtree.part.4 (STB_LOCAL)
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
In lib/assoc_array.c (ffffffff8149eb0f)
Location: lib/assoc_array.c:360
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
Direct callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
```
**Symbols:**

```
ffffffff8149d4b0-ffffffff8149d5e9: assoc_array_destroy_subtree.part.4 (STB_LOCAL)
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
In lib/assoc_array.c (ffffffff814d3d53)
Location: lib/assoc_array.c:347
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
Direct callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
```
**Symbols:**

```
ffffffff814d2720-ffffffff814d2859: assoc_array_destroy_subtree.part.3 (STB_LOCAL)
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
In lib/assoc_array.c (ffffffff814e8631)
Location: lib/assoc_array.c:347
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
Direct callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
```
**Symbols:**

```
ffffffff814e7060-ffffffff814e7199: assoc_array_destroy_subtree.part.3 (STB_LOCAL)
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
In lib/assoc_array.c (ffffffff81515071)
Location: lib/assoc_array.c:343
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
Direct callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
```
**Symbols:**

```
ffffffff81513950-ffffffff81513a89: assoc_array_destroy_subtree.part.0 (STB_LOCAL)
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
In lib/assoc_array.c (ffffffff81535ab1)
Location: lib/assoc_array.c:343
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
Direct callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
```
**Symbols:**

```
ffffffff81534390-ffffffff815344c9: assoc_array_destroy_subtree.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/assoc_array.c (ffffffff81599f41)
Location: lib/assoc_array.c:343
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
Direct callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
```
**Symbols:**

```
ffffffff815986a0-ffffffff815987da: assoc_array_destroy_subtree.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/assoc_array.c (ffffffff815b5950)
Location: lib/assoc_array.c:343
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
Direct callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
```
**Symbols:**

```
ffffffff815b40a0-ffffffff815b41d6: assoc_array_destroy_subtree.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/assoc_array.c (ffffffff815c0784)
Location: lib/assoc_array.c:343
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
Direct callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
```
**Symbols:**

```
ffffffff815bef10-ffffffff815bf046: assoc_array_destroy_subtree.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/assoc_array.c (ffffffff81628200)
Location: lib/assoc_array.c:343
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
Direct callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
```
**Symbols:**

```
ffffffff81626440-ffffffff81626595: assoc_array_destroy_subtree.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/assoc_array.c (ffffffff816f8fbf)
Location: lib/assoc_array.c:343
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
Direct callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
```
**Symbols:**

```
ffffffff816f7000-ffffffff816f715b: assoc_array_destroy_subtree.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/assoc_array.c (ffffffff817eb85f)
Location: lib/assoc_array.c:343
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
Direct callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
```
**Symbols:**

```
ffffffff817e97d0-ffffffff817e992b: assoc_array_destroy_subtree.part.0 (STB_LOCAL)
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
In lib/assoc_array.c (ffffffff8182ba82)
Location: lib/assoc_array.c:343
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
Direct callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
```
**Symbols:**

```
ffffffff818297a0-ffffffff818298fb: assoc_array_destroy_subtree.part.0 (STB_LOCAL)
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
In lib/assoc_array.c (ffffffff8187d660)
Location: lib/assoc_array.c:343
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
Direct callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
```
**Symbols:**

```
ffffffff8187b1b0-ffffffff8187b30b: assoc_array_destroy_subtree.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/assoc_array.c (ffff800010642254)
Location: lib/assoc_array.c:343
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
Direct callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
```
**Symbols:**

```
ffff800010640cd8-ffff800010640e24: assoc_array_destroy_subtree.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/assoc_array.c (c07e7bb4)
Location: lib/assoc_array.c:343
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
Direct callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
```
**Symbols:**

```
c07e66a0-c07e67ec: assoc_array_destroy_subtree.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/assoc_array.c (c0000000007ecfc8)
Location: lib/assoc_array.c:343
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
Direct callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
```
**Symbols:**

```
c0000000007eb350-c0000000007eb53c: assoc_array_destroy_subtree.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/assoc_array.c (ffffffe00046e620)
Location: lib/assoc_array.c:343
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
Direct callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
```
**Symbols:**

```
ffffffe00046d478-ffffffe00046d58a: assoc_array_destroy_subtree.part.0 (STB_LOCAL)
```
</details>
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
In lib/assoc_array.c (ffffffff8152e091)
Location: lib/assoc_array.c:343
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
Direct callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
```
**Symbols:**

```
ffffffff8152c970-ffffffff8152caa9: assoc_array_destroy_subtree.part.0 (STB_LOCAL)
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
In lib/assoc_array.c (ffffffff8151e371)
Location: lib/assoc_array.c:343
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
Direct callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
```
**Symbols:**

```
ffffffff8151cc50-ffffffff8151cd89: assoc_array_destroy_subtree.part.0 (STB_LOCAL)
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
In lib/assoc_array.c (ffffffff8152a121)
Location: lib/assoc_array.c:343
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
Direct callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
```
**Symbols:**

```
ffffffff81528a00-ffffffff81528b39: assoc_array_destroy_subtree.part.0 (STB_LOCAL)
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
In lib/assoc_array.c (ffffffff81543b01)
Location: lib/assoc_array.c:343
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
Direct callers:
  - lib/assoc_array.c:assoc_array_gc
  - lib/assoc_array.c:assoc_array_rcu_cleanup
  - lib/assoc_array.c:assoc_array_destroy
```
**Symbols:**

```
ffffffff815423e0-ffffffff81542519: assoc_array_destroy_subtree.part.0 (STB_LOCAL)
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
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
