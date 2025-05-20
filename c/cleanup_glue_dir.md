# Function: <code>cleanup_glue_dir</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/core.c (ffffffff81546d60)
Location: drivers/base/core.c:839
Inline: True
Inline callers:
  - drivers/base/core.c:cleanup_device_parent
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
Direct callers:
  - drivers/base/core.c:cleanup_device_parent
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
```
**Symbols:**

```
ffffffff81546d60-ffffffff81546d90: cleanup_glue_dir.isra.14.part.15 (STB_LOCAL)
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
In drivers/base/core.c (ffffffff81599bc8)
Location: drivers/base/core.c:839
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:cleanup_device_parent
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:cleanup_device_parent
```
**Symbols:**

```
ffffffff815989e0-ffffffff81598a10: cleanup_glue_dir.isra.14.part.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void cleanup_glue_dir(struct device *dev, struct kobject *glue_dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c6710)
Location: drivers/base/core.c:1427
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff815c6710-ffffffff815c6762: cleanup_glue_dir (STB_LOCAL)
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
In drivers/base/core.c (ffffffff815dce18)
Location: drivers/base/core.c:1425
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff815db440-ffffffff815db470: cleanup_glue_dir.part.19 (STB_LOCAL)
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
In drivers/base/core.c (ffffffff81643e18)
Location: drivers/base/core.c:1560
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81642460-ffffffff81642490: cleanup_glue_dir.part.21 (STB_LOCAL)
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
In drivers/base/core.c (ffffffff8167f33a)
Location: drivers/base/core.c:1602
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff8167d780-ffffffff8167d7b0: cleanup_glue_dir.part.24 (STB_LOCAL)
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
In drivers/base/core.c (ffffffff8169f77a)
Location: drivers/base/core.c:1676
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff8169d100-ffffffff8169d155: cleanup_glue_dir.part.25 (STB_LOCAL)
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
In drivers/base/core.c (ffffffff816d7efc)
Location: drivers/base/core.c:1824
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff816d5f40-ffffffff816d5fa4: cleanup_glue_dir.part.0 (STB_LOCAL)
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
In drivers/base/core.c (ffffffff816fbffc)
Location: drivers/base/core.c:1861
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff816f9f80-ffffffff816f9fe4: cleanup_glue_dir.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cleanup_glue_dir(struct device *dev, struct kobject *glue_dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b2eb0)
Location: drivers/base/core.c:2341
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff817b2eb0-ffffffff817b2f3e: cleanup_glue_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cleanup_glue_dir(struct device *dev, struct kobject *glue_dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c7910)
Location: drivers/base/core.c:2750
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff817c7910-ffffffff817c799e: cleanup_glue_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cleanup_glue_dir(struct device *dev, struct kobject *glue_dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817aad80)
Location: drivers/base/core.c:2968
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff817aad80-ffffffff817aae0e: cleanup_glue_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cleanup_glue_dir(struct device *dev, struct kobject *glue_dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81833f20)
Location: drivers/base/core.c:3036
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81833f20-ffffffff81833fae: cleanup_glue_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cleanup_glue_dir(struct device *dev, struct kobject *glue_dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff819757e0)
Location: drivers/base/core.c:3071
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff819757e0-ffffffff81975894: cleanup_glue_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cleanup_glue_dir(struct device *dev, struct kobject *glue_dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae1380)
Location: drivers/base/core.c:3269
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81ae1380-ffffffff81ae1434: cleanup_glue_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cleanup_glue_dir(struct device *dev, struct kobject *glue_dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b2f5d0)
Location: drivers/base/core.c:3292
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81b2f5d0-ffffffff81b2f699: cleanup_glue_dir (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void cleanup_glue_dir(struct device *dev, struct kobject *glue_dir);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b86dd0)
Location: drivers/base/core.c:3305
Inline: True
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81b86dd0-ffffffff81b86e99: cleanup_glue_dir (STB_LOCAL)
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
In drivers/base/core.c (ffff8000108e68c0)
Location: drivers/base/core.c:1861
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffff8000108e4718-ffff8000108e47ac: cleanup_glue_dir.part.0 (STB_LOCAL)
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
In drivers/base/core.c (c09d4f2c)
Location: drivers/base/core.c:1861
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
c09d3148-c09d31f0: cleanup_glue_dir.part.0 (STB_LOCAL)
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
In drivers/base/core.c (c00000000097c7d0)
Location: drivers/base/core.c:1861
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
c000000000979ab0-c000000000979ba8: cleanup_glue_dir.part.0 (STB_LOCAL)
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
In drivers/base/core.c (ffffffe00057b29a)
Location: drivers/base/core.c:1861
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffe000579612-ffffffe000579684: cleanup_glue_dir.part.0 (STB_LOCAL)
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
In drivers/base/core.c (ffffffff816c17ec)
Location: drivers/base/core.c:1861
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff816bf770-ffffffff816bf7d4: cleanup_glue_dir.part.0 (STB_LOCAL)
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
In drivers/base/core.c (ffffffff8169ca9c)
Location: drivers/base/core.c:1861
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff8169aa20-ffffffff8169aa84: cleanup_glue_dir.part.0 (STB_LOCAL)
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
In drivers/base/core.c (ffffffff816efcbc)
Location: drivers/base/core.c:1861
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff816edc40-ffffffff816edca4: cleanup_glue_dir.part.0 (STB_LOCAL)
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
In drivers/base/core.c (ffffffff8170a4fc)
Location: drivers/base/core.c:1861
Inline: True
Inline callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
Direct callers:
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_move
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_add
```
**Symbols:**

```
ffffffff81708480-ffffffff817084e4: cleanup_glue_dir.part.0 (STB_LOCAL)
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
