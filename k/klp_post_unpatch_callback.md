# Function: <code>klp_post_unpatch_callback</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811028a1)
Location: kernel/livepatch/core.h:38
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
```
In kernel/livepatch/transition.c (ffffffff8110330b)
Location: kernel/livepatch/core.h:38
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
In kernel/livepatch/core.c (ffffffff8110aeed)
Location: kernel/livepatch/core.h:38
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
```
In kernel/livepatch/transition.c (ffffffff8110b994)
Location: kernel/livepatch/core.h:38
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
In kernel/livepatch/core.c (ffffffff811166dd)
Location: kernel/livepatch/core.h:38
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
```
In kernel/livepatch/transition.c (ffffffff81117184)
Location: kernel/livepatch/core.h:38
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
In kernel/livepatch/core.c (ffffffff8112078c)
Location: kernel/livepatch/core.h:49
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
```
In kernel/livepatch/transition.c (ffffffff8112141a)
Location: kernel/livepatch/core.h:49
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
In kernel/livepatch/core.c (ffffffff8112cf00)
Location: kernel/livepatch/core.h:49
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
```
In kernel/livepatch/transition.c (ffffffff8112da3a)
Location: kernel/livepatch/core.h:49
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void klp_post_unpatch_callback(struct klp_object *obj);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8113b1cc)
Location: kernel/livepatch/core.h:50
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
```
In kernel/livepatch/transition.c (ffffffff8113c72e)
Location: kernel/livepatch/core.h:50
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
```
**Symbols:**

```
ffffffff8113b1cc-ffffffff8113b1ef: klp_post_unpatch_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void klp_post_unpatch_callback(struct klp_object *obj);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81be2edb)
Location: kernel/livepatch/core.h:50
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
```
In kernel/livepatch/transition.c (ffffffff81136e3e)
Location: kernel/livepatch/core.h:50
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
```
**Symbols:**

```
ffffffff81be2edb-ffffffff81be2efe: klp_post_unpatch_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void klp_post_unpatch_callback(struct klp_object *obj);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81bd4d85)
Location: kernel/livepatch/core.h:50
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
```
In kernel/livepatch/transition.c (ffffffff81137b0e)
Location: kernel/livepatch/core.h:50
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
```
**Symbols:**

```
ffffffff81bd4d85-ffffffff81bd4da8: klp_post_unpatch_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void klp_post_unpatch_callback(struct klp_object *obj);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81caf842)
Location: kernel/livepatch/core.h:50
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
```
In kernel/livepatch/transition.c (ffffffff8115a840)
Location: kernel/livepatch/core.h:50
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
```
**Symbols:**

```
ffffffff81caf842-ffffffff81caf886: klp_post_unpatch_callback (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void klp_post_unpatch_callback(struct klp_object *obj);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81e604dc)
Location: kernel/livepatch/core.h:50
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
```
In kernel/livepatch/transition.c (ffffffff811840db)
Location: kernel/livepatch/core.h:50
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
```
**Symbols:**

```
ffffffff81e604dc-ffffffff81e6052a: klp_post_unpatch_callback (STB_LOCAL)
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
In kernel/livepatch/core.c (ffffffff811bdbf8)
Location: kernel/livepatch/core.h:50
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
```
In kernel/livepatch/transition.c (ffffffff811bf2f3)
Location: kernel/livepatch/core.h:50
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
In kernel/livepatch/core.c (ffffffff811d05d8)
Location: kernel/livepatch/core.h:50
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
```
In kernel/livepatch/transition.c (ffffffff811d1d63)
Location: kernel/livepatch/core.h:50
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
In kernel/livepatch/core.c (ffffffff811e5228)
Location: kernel/livepatch/core.h:50
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
```
In kernel/livepatch/transition.c (ffffffff811e69e3)
Location: kernel/livepatch/core.h:50
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
In kernel/livepatch/core.c (c0000000001f164c)
Location: kernel/livepatch/core.h:49
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
```
In kernel/livepatch/transition.c (c0000000001f2828)
Location: kernel/livepatch/core.h:49
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
In kernel/livepatch/core.c (ffffffff811254e0)
Location: kernel/livepatch/core.h:49
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
```
In kernel/livepatch/transition.c (ffffffff8112601a)
Location: kernel/livepatch/core.h:49
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
In kernel/livepatch/core.c (ffffffff81117f40)
Location: kernel/livepatch/core.h:49
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
```
In kernel/livepatch/transition.c (ffffffff81118a7a)
Location: kernel/livepatch/core.h:49
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
In kernel/livepatch/core.c (ffffffff811233d0)
Location: kernel/livepatch/core.h:49
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
```
In kernel/livepatch/transition.c (ffffffff81123f0a)
Location: kernel/livepatch/core.h:49
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
In kernel/livepatch/core.c (ffffffff8112f9e0)
Location: kernel/livepatch/core.h:49
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
```
In kernel/livepatch/transition.c (ffffffff81130549)
Location: kernel/livepatch/core.h:49
Inline: True
Inline callers:
  - kernel/livepatch/transition.c:klp_complete_transition
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
</ul>
