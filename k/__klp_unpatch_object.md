# Function: <code>__klp_unpatch_object</code>

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
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __klp_unpatch_object(struct klp_object *obj, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:237
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:__klp_unpatch_objects
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
ffffffff81120900-ffffffff81120ae6: __klp_unpatch_object (STB_LOCAL)
ffffffff81120d85-ffffffff81120dfa: __klp_unpatch_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __klp_unpatch_object(struct klp_object *obj, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff8112cff0)
Location: kernel/livepatch/patch.c:237
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:__klp_unpatch_objects
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
ffffffff8112cff0-ffffffff8112d1bf: __klp_unpatch_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __klp_unpatch_object(struct klp_object *obj, bool nops_only);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff8113babf)
Location: kernel/livepatch/patch.c:238
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
Direct callers:
  - kernel/livepatch/patch.c:klp_unpatch_objects_dynamic
  - kernel/livepatch/patch.c:klp_unpatch_objects
```
**Symbols:**

```
ffffffff8113b7e0-ffffffff8113b869: __klp_unpatch_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __klp_unpatch_object(struct klp_object *obj, bool nops_only);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff8113625f)
Location: kernel/livepatch/patch.c:245
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
Direct callers:
  - kernel/livepatch/patch.c:klp_unpatch_objects_dynamic
  - kernel/livepatch/patch.c:klp_unpatch_objects
```
**Symbols:**

```
ffffffff81135f80-ffffffff81136009: __klp_unpatch_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __klp_unpatch_object(struct klp_object *obj, bool nops_only);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff8113705f)
Location: kernel/livepatch/patch.c:245
Inline: True
Inline callers:
  - kernel/livepatch/patch.c:klp_patch_object
Direct callers:
  - kernel/livepatch/patch.c:klp_unpatch_objects_dynamic
  - kernel/livepatch/patch.c:klp_unpatch_objects
```
**Symbols:**

```
ffffffff81136d80-ffffffff81136e09: __klp_unpatch_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __klp_unpatch_object(struct klp_object *obj, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:245
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_unpatch_objects_dynamic
  - kernel/livepatch/patch.c:klp_unpatch_objects
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
ffffffff811598d0-ffffffff81159ad6: __klp_unpatch_object (STB_LOCAL)
ffffffff81cafe23-ffffffff81cafed1: __klp_unpatch_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __klp_unpatch_object(struct klp_object *obj, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:230
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_unpatch_objects_dynamic
  - kernel/livepatch/patch.c:klp_unpatch_objects
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
ffffffff81183020-ffffffff811830ed: __klp_unpatch_object (STB_LOCAL)
ffffffff81e60aa9-ffffffff81e60ae7: __klp_unpatch_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __klp_unpatch_object(struct klp_object *obj, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:230
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_unpatch_objects_dynamic
  - kernel/livepatch/patch.c:klp_unpatch_objects
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
ffffffff811be090-ffffffff811be15d: __klp_unpatch_object (STB_LOCAL)
ffffffff8205a5e1-ffffffff8205a61f: __klp_unpatch_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __klp_unpatch_object(struct klp_object *obj, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:230
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_unpatch_objects_dynamic
  - kernel/livepatch/patch.c:klp_unpatch_objects
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
ffffffff811d0960-ffffffff811d0b87: __klp_unpatch_object (STB_LOCAL)
ffffffff820d8e07-ffffffff820d8e93: __klp_unpatch_object.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __klp_unpatch_object(struct klp_object *obj, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/patch.c (0)
Location: kernel/livepatch/patch.c:230
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:klp_unpatch_objects_dynamic
  - kernel/livepatch/patch.c:klp_unpatch_objects
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
ffffffff811e55b0-ffffffff811e57d7: __klp_unpatch_object (STB_LOCAL)
ffffffff821b4540-ffffffff821b45cc: __klp_unpatch_object.cold (STB_LOCAL)
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
void __klp_unpatch_object(struct klp_object *obj, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (c0000000001f1840)
Location: kernel/livepatch/patch.c:237
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:__klp_unpatch_objects
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
c0000000001f1840-c0000000001f1af8: __klp_unpatch_object (STB_LOCAL)
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
void __klp_unpatch_object(struct klp_object *obj, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff811255d0)
Location: kernel/livepatch/patch.c:237
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:__klp_unpatch_objects
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
ffffffff811255d0-ffffffff8112579f: __klp_unpatch_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __klp_unpatch_object(struct klp_object *obj, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff81118030)
Location: kernel/livepatch/patch.c:237
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:__klp_unpatch_objects
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
ffffffff81118030-ffffffff811181ff: __klp_unpatch_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __klp_unpatch_object(struct klp_object *obj, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff811234c0)
Location: kernel/livepatch/patch.c:237
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:__klp_unpatch_objects
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
ffffffff811234c0-ffffffff8112368f: __klp_unpatch_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __klp_unpatch_object(struct klp_object *obj, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/patch.c (ffffffff8112fae0)
Location: kernel/livepatch/patch.c:237
Inline: False
Direct callers:
  - kernel/livepatch/patch.c:__klp_unpatch_objects
  - kernel/livepatch/patch.c:klp_patch_object
```
**Symbols:**

```
ffffffff8112fae0-ffffffff8112fcaf: __klp_unpatch_object (STB_LOCAL)
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
