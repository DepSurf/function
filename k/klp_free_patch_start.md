# Function: <code>klp_free_patch_start</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void klp_free_patch_start(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8111f840)
Location: kernel/livepatch/core.c:635
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_replaced_patches
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
ffffffff8111f840-ffffffff8111f884: klp_free_patch_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void klp_free_patch_start(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8112bf90)
Location: kernel/livepatch/core.c:635
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_replaced_patches
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
ffffffff8112bf90-ffffffff8112bfd4: klp_free_patch_start (STB_GLOBAL)
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
In kernel/livepatch/core.c (ffffffff8113ad4c)
Location: kernel/livepatch/core.c:657
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_replaced_patches_async
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
In kernel/livepatch/core.c (ffffffff8113583c)
Location: kernel/livepatch/core.c:657
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_replaced_patches_async
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
In kernel/livepatch/core.c (ffffffff811366e6)
Location: kernel/livepatch/core.c:656
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_replaced_patches_async
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
In kernel/livepatch/core.c (ffffffff81159304)
Location: kernel/livepatch/core.c:656
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_replaced_patches_async
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
In kernel/livepatch/core.c (ffffffff81182898)
Location: kernel/livepatch/core.c:656
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_replaced_patches_async
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
In kernel/livepatch/core.c (ffffffff811bd599)
Location: kernel/livepatch/core.c:681
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_replaced_patches_async
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
In kernel/livepatch/core.c (ffffffff811cfda4)
Location: kernel/livepatch/core.c:696
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_replaced_patches_async
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
In kernel/livepatch/core.c (ffffffff811e49f4)
Location: kernel/livepatch/core.c:696
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_replaced_patches_async
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
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void klp_free_patch_start(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (c0000000001efe20)
Location: kernel/livepatch/core.c:635
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_replaced_patches
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
c0000000001efe20-c0000000001efe88: klp_free_patch_start (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void klp_free_patch_start(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81124570)
Location: kernel/livepatch/core.c:635
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_replaced_patches
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
ffffffff81124570-ffffffff811245b4: klp_free_patch_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void klp_free_patch_start(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81116fd0)
Location: kernel/livepatch/core.c:635
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_replaced_patches
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
ffffffff81116fd0-ffffffff81117014: klp_free_patch_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void klp_free_patch_start(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81122460)
Location: kernel/livepatch/core.c:635
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_replaced_patches
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
ffffffff81122460-ffffffff811224a4: klp_free_patch_start (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void klp_free_patch_start(struct klp_patch *patch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8112ea70)
Location: kernel/livepatch/core.c:635
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_replaced_patches
  - kernel/livepatch/transition.c:klp_try_complete_transition
```
**Symbols:**

```
ffffffff8112ea70-ffffffff8112eab4: klp_free_patch_start (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
