# Function: <code>klp_unpatch_object</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void klp_unpatch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff810f87d0)
Location: kernel/livepatch/patch.c:238
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_going
  - kernel/livepatch/patch.c:klp_unpatch_objects
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
ffffffff810f87d0-ffffffff810f8945: klp_unpatch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void klp_unpatch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81102a00)
Location: kernel/livepatch/patch.c:239
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
  - kernel/livepatch/patch.c:klp_unpatch_objects
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
ffffffff81102a00-ffffffff81102b78: klp_unpatch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void klp_unpatch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff8110afe0)
Location: kernel/livepatch/patch.c:239
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
  - kernel/livepatch/patch.c:klp_unpatch_objects
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
ffffffff8110afe0-ffffffff8110b158: klp_unpatch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void klp_unpatch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff811167d0)
Location: kernel/livepatch/patch.c:239
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
  - kernel/livepatch/patch.c:klp_unpatch_objects
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
ffffffff811167d0-ffffffff81116948: klp_unpatch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void klp_unpatch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81120d38)
Location: kernel/livepatch/patch.c:254
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
Direct callers:
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
**Symbols:**

```
ffffffff81120b90-ffffffff81120ba2: klp_unpatch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void klp_unpatch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff8112d40a)
Location: kernel/livepatch/patch.c:254
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
Direct callers:
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
**Symbols:**

```
ffffffff8112d260-ffffffff8112d272: klp_unpatch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void klp_unpatch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff8113babf)
Location: kernel/livepatch/patch.c:255
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
Direct callers:
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
**Symbols:**

```
ffffffff8113ba10-ffffffff8113ba6e: klp_unpatch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void klp_unpatch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff8113625f)
Location: kernel/livepatch/patch.c:262
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
Direct callers:
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
**Symbols:**

```
ffffffff811361b0-ffffffff8113620e: klp_unpatch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void klp_unpatch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff8113705f)
Location: kernel/livepatch/patch.c:262
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
Direct callers:
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
**Symbols:**

```
ffffffff81136fb0-ffffffff8113700e: klp_unpatch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void klp_unpatch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81159d1e)
Location: kernel/livepatch/patch.c:262
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
Direct callers:
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
**Symbols:**

```
ffffffff81159ca0-ffffffff81159cb2: klp_unpatch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void klp_unpatch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff8118333e)
Location: kernel/livepatch/patch.c:247
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
Direct callers:
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
**Symbols:**

```
ffffffff811832c0-ffffffff811832da: klp_unpatch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void klp_unpatch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff811be47e)
Location: kernel/livepatch/patch.c:247
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
Direct callers:
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
**Symbols:**

```
ffffffff811be3f0-ffffffff811be40a: klp_unpatch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void klp_unpatch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff811d0eae)
Location: kernel/livepatch/patch.c:247
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
Direct callers:
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
**Symbols:**

```
ffffffff811d0e20-ffffffff811d0e3a: klp_unpatch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void klp_unpatch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff811e5b2e)
Location: kernel/livepatch/patch.c:247
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
Direct callers:
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
**Symbols:**

```
ffffffff811e5aa0-ffffffff811e5aba: klp_unpatch_object (STB_GLOBAL)
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
void klp_unpatch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (c0000000001f1f04)
Location: kernel/livepatch/patch.c:254
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
Direct callers:
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
**Symbols:**

```
c0000000001f1c20-c0000000001f1c38: klp_unpatch_object (STB_GLOBAL)
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
void klp_unpatch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff811259ea)
Location: kernel/livepatch/patch.c:254
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
Direct callers:
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
**Symbols:**

```
ffffffff81125840-ffffffff81125852: klp_unpatch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void klp_unpatch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff8111844a)
Location: kernel/livepatch/patch.c:254
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
Direct callers:
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
**Symbols:**

```
ffffffff811182a0-ffffffff811182b2: klp_unpatch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void klp_unpatch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff811238da)
Location: kernel/livepatch/patch.c:254
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
Direct callers:
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
**Symbols:**

```
ffffffff81123730-ffffffff81123742: klp_unpatch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void klp_unpatch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff8112fefa)
Location: kernel/livepatch/patch.c:254
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
Direct callers:
  - kernel/livepatch/core.c:klp_cleanup_module_patches_limited
```
**Symbols:**

```
ffffffff8112fd50-ffffffff8112fd62: klp_unpatch_object (STB_GLOBAL)
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
