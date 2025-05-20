# Function: <code>assoc_array_insert_into_terminal_node</code>

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
In lib/assoc_array.c (ffffffff81405722)
Location: lib/assoc_array.c:491
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_insert
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
In lib/assoc_array.c (ffffffff8144d2d8)
Location: lib/assoc_array.c:491
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_insert
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
In lib/assoc_array.c (ffffffff8146bc98)
Location: lib/assoc_array.c:491
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_insert
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
In lib/assoc_array.c (ffffffff81471371)
Location: lib/assoc_array.c:491
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_insert
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
In lib/assoc_array.c (ffffffff8149db41)
Location: lib/assoc_array.c:491
Inline: True
Inline callers:
  - lib/assoc_array.c:assoc_array_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool assoc_array_insert_into_terminal_node(struct assoc_array_edit *edit, const struct assoc_array_ops *ops, const void *index_key, struct assoc_array_walk_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff814d28d0)
Location: lib/assoc_array.c:478
Inline: False
Direct callers:
  - lib/assoc_array.c:assoc_array_insert
```
**Symbols:**

```
ffffffff814d28d0-ffffffff814d2f5b: assoc_array_insert_into_terminal_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool assoc_array_insert_into_terminal_node(struct assoc_array_edit *edit, const struct assoc_array_ops *ops, const void *index_key, struct assoc_array_walk_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff814e7210)
Location: lib/assoc_array.c:478
Inline: False
Direct callers:
  - lib/assoc_array.c:assoc_array_insert
```
**Symbols:**

```
ffffffff814e7210-ffffffff814e78b9: assoc_array_insert_into_terminal_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool assoc_array_insert_into_terminal_node(struct assoc_array_edit *edit, const struct assoc_array_ops *ops, const void *index_key, struct assoc_array_walk_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff81513b20)
Location: lib/assoc_array.c:474
Inline: False
Direct callers:
  - lib/assoc_array.c:assoc_array_insert
```
**Symbols:**

```
ffffffff81513b20-ffffffff81514225: assoc_array_insert_into_terminal_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool assoc_array_insert_into_terminal_node(struct assoc_array_edit *edit, const struct assoc_array_ops *ops, const void *index_key, struct assoc_array_walk_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff81534560)
Location: lib/assoc_array.c:474
Inline: False
Direct callers:
  - lib/assoc_array.c:assoc_array_insert
```
**Symbols:**

```
ffffffff81534560-ffffffff81534c65: assoc_array_insert_into_terminal_node (STB_LOCAL)
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
In lib/assoc_array.c (ffffffff815989e0)
Location: lib/assoc_array.c:474
Inline: True
Direct callers:
  - lib/assoc_array.c:assoc_array_insert
```
**Symbols:**

```
ffffffff815989e0-ffffffff815990b9: assoc_array_insert_into_terminal_node.isra.0 (STB_LOCAL)
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
In lib/assoc_array.c (ffffffff815b43e0)
Location: lib/assoc_array.c:474
Inline: True
Direct callers:
  - lib/assoc_array.c:assoc_array_insert
```
**Symbols:**

```
ffffffff815b43e0-ffffffff815b4ab3: assoc_array_insert_into_terminal_node.isra.0 (STB_LOCAL)
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
In lib/assoc_array.c (ffffffff815bf250)
Location: lib/assoc_array.c:474
Inline: True
Direct callers:
  - lib/assoc_array.c:assoc_array_insert
```
**Symbols:**

```
ffffffff815bf250-ffffffff815bf8f3: assoc_array_insert_into_terminal_node.isra.0 (STB_LOCAL)
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
In lib/assoc_array.c (ffffffff81626620)
Location: lib/assoc_array.c:474
Inline: True
Direct callers:
  - lib/assoc_array.c:assoc_array_insert
```
**Symbols:**

```
ffffffff81626620-ffffffff81627221: assoc_array_insert_into_terminal_node.isra.0 (STB_LOCAL)
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
In lib/assoc_array.c (ffffffff816f71e0)
Location: lib/assoc_array.c:474
Inline: True
Direct callers:
  - lib/assoc_array.c:assoc_array_insert
```
**Symbols:**

```
ffffffff816f71e0-ffffffff816f7d39: assoc_array_insert_into_terminal_node.isra.0 (STB_LOCAL)
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
In lib/assoc_array.c (ffffffff817e99d0)
Location: lib/assoc_array.c:474
Inline: True
Direct callers:
  - lib/assoc_array.c:assoc_array_insert
```
**Symbols:**

```
ffffffff817e99d0-ffffffff817ea529: assoc_array_insert_into_terminal_node.isra.0 (STB_LOCAL)
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
In lib/assoc_array.c (ffffffff818299a0)
Location: lib/assoc_array.c:474
Inline: True
Direct callers:
  - lib/assoc_array.c:assoc_array_insert
```
**Symbols:**

```
ffffffff818299a0-ffffffff8182a6b3: assoc_array_insert_into_terminal_node.isra.0 (STB_LOCAL)
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
In lib/assoc_array.c (ffffffff8187b3b0)
Location: lib/assoc_array.c:474
Inline: True
Direct callers:
  - lib/assoc_array.c:assoc_array_insert
```
**Symbols:**

```
ffffffff8187b3b0-ffffffff8187c121: assoc_array_insert_into_terminal_node.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool assoc_array_insert_into_terminal_node(struct assoc_array_edit *edit, const struct assoc_array_ops *ops, const void *index_key, struct assoc_array_walk_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffff800010640ec0)
Location: lib/assoc_array.c:474
Inline: False
Direct callers:
  - lib/assoc_array.c:assoc_array_insert
```
**Symbols:**

```
ffff800010640ec0-ffff800010641544: assoc_array_insert_into_terminal_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool assoc_array_insert_into_terminal_node(struct assoc_array_edit *edit, const struct assoc_array_ops *ops, const void *index_key, struct assoc_array_walk_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (c07e6874)
Location: lib/assoc_array.c:474
Inline: False
Direct callers:
  - lib/assoc_array.c:assoc_array_insert
```
**Symbols:**

```
c07e6874-c07e6f74: assoc_array_insert_into_terminal_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool assoc_array_insert_into_terminal_node(struct assoc_array_edit *edit, const struct assoc_array_ops *ops, const void *index_key, struct assoc_array_walk_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (c0000000007eb640)
Location: lib/assoc_array.c:474
Inline: False
Direct callers:
  - lib/assoc_array.c:assoc_array_insert
```
**Symbols:**

```
c0000000007eb640-c0000000007ebe7c: assoc_array_insert_into_terminal_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool assoc_array_insert_into_terminal_node(struct assoc_array_edit *edit, const struct assoc_array_ops *ops, const void *index_key, struct assoc_array_walk_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffe00046d64a)
Location: lib/assoc_array.c:474
Inline: False
Direct callers:
  - lib/assoc_array.c:assoc_array_insert
```
**Symbols:**

```
ffffffe00046d64a-ffffffe00046db4e: assoc_array_insert_into_terminal_node (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool assoc_array_insert_into_terminal_node(struct assoc_array_edit *edit, const struct assoc_array_ops *ops, const void *index_key, struct assoc_array_walk_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff8152cb40)
Location: lib/assoc_array.c:474
Inline: False
Direct callers:
  - lib/assoc_array.c:assoc_array_insert
```
**Symbols:**

```
ffffffff8152cb40-ffffffff8152d245: assoc_array_insert_into_terminal_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool assoc_array_insert_into_terminal_node(struct assoc_array_edit *edit, const struct assoc_array_ops *ops, const void *index_key, struct assoc_array_walk_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff8151ce20)
Location: lib/assoc_array.c:474
Inline: False
Direct callers:
  - lib/assoc_array.c:assoc_array_insert
```
**Symbols:**

```
ffffffff8151ce20-ffffffff8151d525: assoc_array_insert_into_terminal_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool assoc_array_insert_into_terminal_node(struct assoc_array_edit *edit, const struct assoc_array_ops *ops, const void *index_key, struct assoc_array_walk_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff81528bd0)
Location: lib/assoc_array.c:474
Inline: False
Direct callers:
  - lib/assoc_array.c:assoc_array_insert
```
**Symbols:**

```
ffffffff81528bd0-ffffffff815292d5: assoc_array_insert_into_terminal_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool assoc_array_insert_into_terminal_node(struct assoc_array_edit *edit, const struct assoc_array_ops *ops, const void *index_key, struct assoc_array_walk_result *result);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/assoc_array.c (ffffffff815425b0)
Location: lib/assoc_array.c:474
Inline: False
Direct callers:
  - lib/assoc_array.c:assoc_array_insert
```
**Symbols:**

```
ffffffff815425b0-ffffffff81542cb5: assoc_array_insert_into_terminal_node (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
