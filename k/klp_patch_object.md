# Function: <code>klp_patch_object</code>

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
int klp_patch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff810f8950)
Location: kernel/livepatch/patch.c:249
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff810f8950-ffffffff810f8bba: klp_patch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int klp_patch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81102b80)
Location: kernel/livepatch/patch.c:250
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff81102b80-ffffffff81102dee: klp_patch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int klp_patch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:250
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff8110b36a-ffffffff8110b401: klp_patch_object.cold.5 (STB_LOCAL)
ffffffff8110b160-ffffffff8110b328: klp_patch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int klp_patch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:250
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff81116b5a-ffffffff81116bf1: klp_patch_object.cold.4 (STB_LOCAL)
ffffffff81116950-ffffffff81116b18: klp_patch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int klp_patch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:259
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff81120dfa-ffffffff81120ee1: klp_patch_object.cold (STB_LOCAL)
ffffffff81120bb0-ffffffff81120d4b: klp_patch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int klp_patch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:259
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff8112d475-ffffffff8112d50e: klp_patch_object.cold (STB_LOCAL)
ffffffff8112d280-ffffffff8112d437: klp_patch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int klp_patch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff8113ba70)
Location: kernel/livepatch/patch.c:260
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:__klp_enable_patch
```
**Symbols:**

```
ffffffff8113ba70-ffffffff8113bb38: klp_patch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int klp_patch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81136210)
Location: kernel/livepatch/patch.c:267
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:__klp_enable_patch
```
**Symbols:**

```
ffffffff81136210-ffffffff811362d8: klp_patch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int klp_patch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81137010)
Location: kernel/livepatch/patch.c:267
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff81137010-ffffffff811370d8: klp_patch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int klp_patch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:267
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff81caff7f-ffffffff81caff93: klp_patch_object.cold (STB_LOCAL)
ffffffff81159cc0-ffffffff81159d58: klp_patch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int klp_patch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:252
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff81e60b8f-ffffffff81e60ba3: klp_patch_object.cold (STB_LOCAL)
ffffffff811832e0-ffffffff81183390: klp_patch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int klp_patch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:252
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff8205a634-ffffffff8205a648: klp_patch_object.cold (STB_LOCAL)
ffffffff811be420-ffffffff811be4d0: klp_patch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int klp_patch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:252
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff820d8ea8-ffffffff820d8ebc: klp_patch_object.cold (STB_LOCAL)
ffffffff811d0e50-ffffffff811d0f00: klp_patch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int klp_patch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:252
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_enable_patch
```
**Symbols:**

```
ffffffff821b45e1-ffffffff821b45f5: klp_patch_object.cold (STB_LOCAL)
ffffffff811e5ad0-ffffffff811e5b80: klp_patch_object (STB_GLOBAL)
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
int klp_patch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (c0000000001f1c40)
Location: kernel/livepatch/patch.c:259
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
c0000000001f1c40-c0000000001f1f98: klp_patch_object (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int klp_patch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:259
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff81125a55-ffffffff81125aee: klp_patch_object.cold (STB_LOCAL)
ffffffff81125860-ffffffff81125a17: klp_patch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int klp_patch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:259
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff811184b5-ffffffff8111854e: klp_patch_object.cold (STB_LOCAL)
ffffffff811182c0-ffffffff81118477: klp_patch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int klp_patch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:259
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff81123945-ffffffff811239de: klp_patch_object.cold (STB_LOCAL)
ffffffff81123750-ffffffff81123907: klp_patch_object (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int klp_patch_object(struct klp_object *obj);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:259
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff8112ff65-ffffffff8112fffe: klp_patch_object.cold (STB_LOCAL)
ffffffff8112fd70-ffffffff8112ff27: klp_patch_object (STB_GLOBAL)
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
