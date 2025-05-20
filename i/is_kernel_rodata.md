# Function: <code>is_kernel_rodata</code>

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
In mm/util.c (ffffffff811abbf6)
Location: mm/util.c:20
Inline: True
Inline callers:
  - mm/util.c:kfree_const
  - mm/util.c:kstrdup_const
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
In mm/util.c (ffffffff811c4705)
Location: mm/util.c:20
Inline: True
Inline callers:
  - mm/util.c:kstrdup_const
  - mm/util.c:kfree_const
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
In mm/util.c (ffffffff811d47f5)
Location: mm/util.c:20
Inline: True
Inline callers:
  - mm/util.c:kstrdup_const
  - mm/util.c:kfree_const
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
In mm/util.c (ffffffff811dd5a5)
Location: mm/util.c:23
Inline: True
Inline callers:
  - mm/util.c:kstrdup_const
  - mm/util.c:kfree_const
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
In mm/util.c (ffffffff811f3025)
Location: mm/util.c:23
Inline: True
Inline callers:
  - mm/util.c:kstrdup_const
  - mm/util.c:kfree_const
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
In mm/util.c (ffffffff81214315)
Location: mm/util.c:23
Inline: True
Inline callers:
  - mm/util.c:kstrdup_const
  - mm/util.c:kfree_const
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812271e5)
Location: include/asm-generic/sections.h:152
Inline: True
Inline callers:
  - mm/util.c:kstrdup_const
  - mm/util.c:kfree_const
```
```
In drivers/base/devres.c (ffffffff816a6e35)
Location: include/asm-generic/sections.h:152
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_kstrdup_const
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81236ce5)
Location: include/asm-generic/sections.h:166
Inline: True
Inline callers:
  - mm/util.c:kstrdup_const
  - mm/util.c:kfree_const
```
```
In drivers/base/devres.c (ffffffff816dff05)
Location: include/asm-generic/sections.h:166
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_kstrdup_const
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81244ea5)
Location: include/asm-generic/sections.h:166
Inline: True
Inline callers:
  - mm/util.c:kstrdup_const
  - mm/util.c:kfree_const
```
```
In drivers/base/devres.c (ffffffff81704145)
Location: include/asm-generic/sections.h:166
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_kstrdup_const
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff81272b55)
Location: include/asm-generic/sections.h:169
Inline: True
Inline callers:
  - mm/util.c:kstrdup_const
  - mm/util.c:kfree_const
```
```
In drivers/base/devres.c (ffffffff817be575)
Location: include/asm-generic/sections.h:169
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_kstrdup_const
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8127d205)
Location: include/asm-generic/sections.h:169
Inline: True
Inline callers:
  - mm/util.c:kstrdup_const
  - mm/util.c:kfree_const
```
```
In drivers/base/devres.c (ffffffff817d32d5)
Location: include/asm-generic/sections.h:169
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_kstrdup_const
  - drivers/base/devres.c:devm_krealloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bfff7)
Location: include/asm-generic/sections.h:169
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_check_vprintf
```
```
In mm/util.c (ffffffff81282395)
Location: include/asm-generic/sections.h:169
Inline: True
Inline callers:
  - mm/util.c:kstrdup_const
  - mm/util.c:kfree_const
```
```
In drivers/base/devres.c (ffffffff817b6ce5)
Location: include/asm-generic/sections.h:169
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_kstrdup_const
  - drivers/base/devres.c:devm_krealloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811ea9d9)
Location: include/asm-generic/sections.h:169
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_check_vprintf
```
```
In mm/util.c (ffffffff812c0405)
Location: include/asm-generic/sections.h:169
Inline: True
Inline callers:
  - mm/util.c:kstrdup_const
  - mm/util.c:kfree_const
```
```
In drivers/base/devres.c (ffffffff81840fb5)
Location: include/asm-generic/sections.h:169
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_kfree
  - drivers/base/devres.c:devm_kstrdup_const
  - drivers/base/devres.c:devm_krealloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8122285f)
Location: include/asm-generic/sections.h:177
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_check_vprintf
```
```
In mm/util.c (ffffffff8131ced5)
Location: include/asm-generic/sections.h:177
Inline: True
Inline callers:
  - mm/util.c:kstrdup_const
  - mm/util.c:kfree_const
```
```
In drivers/base/devres.c (ffffffff81984345)
Location: include/asm-generic/sections.h:177
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_kfree
  - drivers/base/devres.c:devm_kstrdup_const
  - drivers/base/devres.c:devm_krealloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8126d8c2)
Location: include/asm-generic/sections.h:177
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_check_vprintf
```
```
In mm/util.c (ffffffff81390fa5)
Location: include/asm-generic/sections.h:177
Inline: True
Inline callers:
  - mm/util.c:kstrdup_const
  - mm/util.c:kfree_const
```
```
In drivers/base/devres.c (ffffffff81af2485)
Location: include/asm-generic/sections.h:177
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_kfree
  - drivers/base/devres.c:devm_kstrdup_const
  - drivers/base/devres.c:devm_krealloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81284ac8)
Location: include/asm-generic/sections.h:177
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_check_vprintf
```
```
In mm/util.c (ffffffff813c38b5)
Location: include/asm-generic/sections.h:177
Inline: True
Inline callers:
  - mm/util.c:kstrdup_const
  - mm/util.c:kfree_const
```
```
In drivers/base/devres.c (ffffffff81b3fa55)
Location: include/asm-generic/sections.h:177
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_kstrdup_const
  - drivers/base/devres.c:devm_krealloc
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8129fbc8)
Location: include/asm-generic/sections.h:177
Inline: True
Inline callers:
  - kernel/trace/trace.c:trace_check_vprintf
```
```
In mm/util.c (ffffffff813ee475)
Location: include/asm-generic/sections.h:177
Inline: True
Inline callers:
  - mm/util.c:kstrdup_const
  - mm/util.c:kfree_const
```
```
In drivers/base/devres.c (ffffffff81b978d5)
Location: include/asm-generic/sections.h:177
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_kstrdup_const
  - drivers/base/devres.c:devm_krealloc
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffff8000102d7e8c)
Location: include/asm-generic/sections.h:166
Inline: True
Inline callers:
  - mm/util.c:kstrdup_const
  - mm/util.c:kfree_const
```
```
In drivers/base/devres.c (ffff8000108efc6c)
Location: include/asm-generic/sections.h:166
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_kstrdup_const
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (c04ff2f4)
Location: include/asm-generic/sections.h:166
Inline: True
Inline callers:
  - mm/util.c:kstrdup_const
  - mm/util.c:kfree_const
```
```
In drivers/base/devres.c (c09dd51c)
Location: include/asm-generic/sections.h:166
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_kstrdup_const
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (c000000000397970)
Location: include/asm-generic/sections.h:166
Inline: True
Inline callers:
  - mm/util.c:kstrdup_const
  - mm/util.c:kfree_const
```
```
In drivers/base/devres.c (c000000000989c20)
Location: include/asm-generic/sections.h:166
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_kfree
  - drivers/base/devres.c:devm_kstrdup_const
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffe0001f271a)
Location: include/asm-generic/sections.h:166
Inline: True
Inline callers:
  - mm/util.c:kstrdup_const
  - mm/util.c:kfree_const
```
```
In drivers/base/devres.c (ffffffe0005825ae)
Location: include/asm-generic/sections.h:166
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_kstrdup_const
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123d4f5)
Location: include/asm-generic/sections.h:166
Inline: True
Inline callers:
  - mm/util.c:kstrdup_const
  - mm/util.c:kfree_const
```
```
In drivers/base/devres.c (ffffffff816c9895)
Location: include/asm-generic/sections.h:166
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_kstrdup_const
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff812304f5)
Location: include/asm-generic/sections.h:166
Inline: True
Inline callers:
  - mm/util.c:kstrdup_const
  - mm/util.c:kfree_const
```
```
In drivers/base/devres.c (ffffffff816a4bc5)
Location: include/asm-generic/sections.h:166
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_kstrdup_const
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8123b295)
Location: include/asm-generic/sections.h:166
Inline: True
Inline callers:
  - mm/util.c:kstrdup_const
  - mm/util.c:kfree_const
```
```
In drivers/base/devres.c (ffffffff816f7e05)
Location: include/asm-generic/sections.h:166
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_kstrdup_const
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/util.c (ffffffff8124a9a5)
Location: include/asm-generic/sections.h:166
Inline: True
Inline callers:
  - mm/util.c:kstrdup_const
  - mm/util.c:kfree_const
```
```
In drivers/base/devres.c (ffffffff817126a5)
Location: include/asm-generic/sections.h:166
Inline: True
Inline callers:
  - drivers/base/devres.c:devm_kstrdup_const
```
</details>
</li>
</ul>

## Differences
