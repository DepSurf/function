# Function: <code>klp_is_object_loaded</code>

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
In kernel/livepatch/core.c (ffffffff810e8d53)
Location: kernel/livepatch/core.c:85
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_enable_object
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
In kernel/livepatch/core.c (ffffffff810efaa3)
Location: kernel/livepatch/core.c:87
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_enable_object
  - kernel/livepatch/core.c:klp_write_object_relocations
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
In kernel/livepatch/core.c (ffffffff810f7173)
Location: kernel/livepatch/core.c:87
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_register_patch
  - kernel/livepatch/core.c:klp_enable_object
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
In kernel/livepatch/core.c (ffffffff810f82fe)
Location: kernel/livepatch/core.c:57
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_register_patch
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811025a3)
Location: kernel/livepatch/core.h:9
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_register_patch
```
```
In kernel/livepatch/transition.c (ffffffff811032f1)
Location: kernel/livepatch/core.h:9
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8110a920)
Location: kernel/livepatch/core.h:9
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_register_patch
```
```
In kernel/livepatch/transition.c (ffffffff8110b97f)
Location: kernel/livepatch/core.h:9
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
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
In kernel/livepatch/core.c (ffffffff811160e5)
Location: kernel/livepatch/core.h:9
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_register_patch
```
```
In kernel/livepatch/transition.c (ffffffff8111716f)
Location: kernel/livepatch/core.h:9
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
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
In kernel/livepatch/core.c (ffffffff8111f8f1)
Location: kernel/livepatch/core.h:20
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff8112145d)
Location: kernel/livepatch/core.h:20
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
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
In kernel/livepatch/core.c (ffffffff8112c041)
Location: kernel/livepatch/core.h:20
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff8112da7d)
Location: kernel/livepatch/core.h:20
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
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
In kernel/livepatch/core.c (ffffffff8113b2d8)
Location: kernel/livepatch/core.h:21
Inline: True
Inline callers:
  - kernel/livepatch/core.c:__klp_enable_patch
  - kernel/livepatch/core.c:klp_init_object
```
```
In kernel/livepatch/transition.c (ffffffff8113c6f9)
Location: kernel/livepatch/core.h:21
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
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
In kernel/livepatch/core.c (ffffffff81be2fe7)
Location: kernel/livepatch/core.h:21
Inline: True
Inline callers:
  - kernel/livepatch/core.c:__klp_enable_patch
  - kernel/livepatch/core.c:klp_init_object
```
```
In kernel/livepatch/transition.c (ffffffff81136e09)
Location: kernel/livepatch/core.h:21
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
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
In kernel/livepatch/core.c (ffffffff81bd4f97)
Location: kernel/livepatch/core.h:21
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_init_object
```
```
In kernel/livepatch/transition.c (ffffffff81137ad9)
Location: kernel/livepatch/core.h:21
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
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
In kernel/livepatch/core.c (ffffffff81cafb8c)
Location: kernel/livepatch/core.h:21
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_init_object
```
```
In kernel/livepatch/transition.c (ffffffff8115a809)
Location: kernel/livepatch/core.h:21
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
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
In kernel/livepatch/core.c (ffffffff81e607a6)
Location: kernel/livepatch/core.h:21
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_init_object
```
```
In kernel/livepatch/transition.c (ffffffff811840a4)
Location: kernel/livepatch/core.h:21
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
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
In kernel/livepatch/core.c (ffffffff811bd6da)
Location: kernel/livepatch/core.h:21
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_init_object
```
```
In kernel/livepatch/transition.c (ffffffff811bf2b5)
Location: kernel/livepatch/core.h:21
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
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
In kernel/livepatch/core.c (ffffffff811cfee5)
Location: kernel/livepatch/core.h:21
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_init_object
```
```
In kernel/livepatch/transition.c (ffffffff811d1d25)
Location: kernel/livepatch/core.h:21
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
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
In kernel/livepatch/core.c (ffffffff811e4b35)
Location: kernel/livepatch/core.h:21
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_init_object
```
```
In kernel/livepatch/transition.c (ffffffff811e69a5)
Location: kernel/livepatch/core.h:21
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
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
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (c0000000001eff0c)
Location: kernel/livepatch/core.h:20
Inline: True
```
```
In kernel/livepatch/transition.c (c0000000001f2800)
Location: kernel/livepatch/core.h:20
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/livepatch/core.c (ffffffff81124621)
Location: kernel/livepatch/core.h:20
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff8112605d)
Location: kernel/livepatch/core.h:20
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
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
In kernel/livepatch/core.c (ffffffff81117081)
Location: kernel/livepatch/core.h:20
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff81118abd)
Location: kernel/livepatch/core.h:20
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
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
In kernel/livepatch/core.c (ffffffff81122511)
Location: kernel/livepatch/core.h:20
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff81123f4d)
Location: kernel/livepatch/core.h:20
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
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
In kernel/livepatch/core.c (ffffffff8112eb21)
Location: kernel/livepatch/core.h:20
Inline: True
```
```
In kernel/livepatch/transition.c (ffffffff8113058c)
Location: kernel/livepatch/core.h:20
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
```
</details>
</li>
</ul>

## Differences
