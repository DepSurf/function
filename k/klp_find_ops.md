# Function: <code>klp_find_ops</code>

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
In kernel/livepatch/core.c (ffffffff810e87f8)
Location: kernel/livepatch/core.c:65
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_disable_func
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
In kernel/livepatch/core.c (ffffffff810efc12)
Location: kernel/livepatch/core.c:67
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_object
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
In kernel/livepatch/core.c (ffffffff810f67f2)
Location: kernel/livepatch/core.c:67
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_object
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct klp_ops *klp_find_ops(long unsigned int old_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff810f896b)
Location: kernel/livepatch/patch.c:36
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_unpatch_object
```
**Symbols:**

```
ffffffff810f8790-ffffffff810f87cd: klp_find_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct klp_ops *klp_find_ops(long unsigned int old_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81102bab)
Location: kernel/livepatch/patch.c:37
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_unpatch_object
Direct callers:
  - kernel/livepatch/transition.c:klp_try_switch_task
```
**Symbols:**

```
ffffffff811029c0-ffffffff811029fd: klp_find_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct klp_ops *klp_find_ops(long unsigned int old_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff8110b1b6)
Location: kernel/livepatch/patch.c:37
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_unpatch_object
Direct callers:
  - kernel/livepatch/transition.c:klp_try_switch_task
```
**Symbols:**

```
ffffffff8110afa0-ffffffff8110afdd: klp_find_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct klp_ops *klp_find_ops(long unsigned int old_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff811169a6)
Location: kernel/livepatch/patch.c:37
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:klp_unpatch_object
Direct callers:
  - kernel/livepatch/transition.c:klp_try_switch_task
```
**Symbols:**

```
ffffffff81116790-ffffffff811167cd: klp_find_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct klp_ops *klp_find_ops(void *old_func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81120c06)
Location: kernel/livepatch/patch.c:25
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
**Symbols:**

```
ffffffff81120b50-ffffffff81120b85: klp_find_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct klp_ops *klp_find_ops(void *old_func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff8112d2d6)
Location: kernel/livepatch/patch.c:25
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
**Symbols:**

```
ffffffff8112d220-ffffffff8112d255: klp_find_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct klp_ops *klp_find_ops(void *old_func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff8113b89f)
Location: kernel/livepatch/patch.c:25
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
  - kernel/livepatch/patch.c:klp_unpatch_func
```
**Symbols:**

```
ffffffff8113b9d0-ffffffff8113ba05: klp_find_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct klp_ops *klp_find_ops(void *old_func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff8113603f)
Location: kernel/livepatch/patch.c:25
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
  - kernel/livepatch/patch.c:klp_unpatch_func
```
**Symbols:**

```
ffffffff81136170-ffffffff811361a5: klp_find_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct klp_ops *klp_find_ops(void *old_func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81136e3f)
Location: kernel/livepatch/patch.c:25
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
  - kernel/livepatch/patch.c:klp_unpatch_func
```
**Symbols:**

```
ffffffff81136f70-ffffffff81136fa5: klp_find_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct klp_ops *klp_find_ops(void *old_func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81159965)
Location: kernel/livepatch/patch.c:25
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/livepatch/patch.c:klp_patch_func
```
**Symbols:**

```
ffffffff81159c60-ffffffff81159c95: klp_find_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct klp_ops *klp_find_ops(void *old_func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81183137)
Location: kernel/livepatch/patch.c:25
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
  - kernel/livepatch/patch.c:klp_unpatch_func
```
**Symbols:**

```
ffffffff81183270-ffffffff811832b5: klp_find_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct klp_ops *klp_find_ops(void *old_func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff811be1b7)
Location: kernel/livepatch/patch.c:25
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_func
  - kernel/livepatch/patch.c:klp_unpatch_func
```
**Symbols:**

```
ffffffff811be390-ffffffff811be3d5: klp_find_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct klp_ops *klp_find_ops(void *old_func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff811d0a35)
Location: kernel/livepatch/patch.c:25
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/livepatch/patch.c:klp_patch_func
```
**Symbols:**

```
ffffffff811d0dc0-ffffffff811d0e05: klp_find_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct klp_ops *klp_find_ops(void *old_func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff811e5685)
Location: kernel/livepatch/patch.c:25
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:__klp_unpatch_object
  - kernel/livepatch/patch.c:klp_patch_func
```
**Symbols:**

```
ffffffff811e5a40-ffffffff811e5a85: klp_find_ops (STB_GLOBAL)
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
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct klp_ops *klp_find_ops(void *old_func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (c0000000001f1cf8)
Location: kernel/livepatch/patch.c:25
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
**Symbols:**

```
c0000000001f1bb0-c0000000001f1c1c: klp_find_ops (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct klp_ops *klp_find_ops(void *old_func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff811258b6)
Location: kernel/livepatch/patch.c:25
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
**Symbols:**

```
ffffffff81125800-ffffffff81125835: klp_find_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct klp_ops *klp_find_ops(void *old_func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81118316)
Location: kernel/livepatch/patch.c:25
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
**Symbols:**

```
ffffffff81118260-ffffffff81118295: klp_find_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct klp_ops *klp_find_ops(void *old_func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff811237a6)
Location: kernel/livepatch/patch.c:25
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
**Symbols:**

```
ffffffff811236f0-ffffffff81123725: klp_find_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct klp_ops *klp_find_ops(void *old_func);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff8112fdc6)
Location: kernel/livepatch/patch.c:25
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
  - kernel/livepatch/patch.c:__klp_unpatch_object
```
**Symbols:**

```
ffffffff8112fd10-ffffffff8112fd45: klp_find_ops (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>void *old_func</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int old_addr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
