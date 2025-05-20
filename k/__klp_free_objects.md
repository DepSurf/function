# Function: <code>__klp_free_objects</code>

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
void __klp_free_objects(struct klp_patch *patch, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8111f050)
Location: kernel/livepatch/core.c:603
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
  - kernel/livepatch/core.c:klp_free_patch_start
```
**Symbols:**

```
ffffffff8111f050-ffffffff8111f176: __klp_free_objects (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __klp_free_objects(struct klp_patch *patch, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8112b790)
Location: kernel/livepatch/core.c:603
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
  - kernel/livepatch/core.c:klp_free_patch_start
```
**Symbols:**

```
ffffffff8112b790-ffffffff8112b8b6: __klp_free_objects (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __klp_free_objects(struct klp_patch *patch, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81139ec0)
Location: kernel/livepatch/core.c:625
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_replaced_patches_async
```
**Symbols:**

```
ffffffff81139ec0-ffffffff81139ff4: __klp_free_objects (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __klp_free_objects(struct klp_patch *patch, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811349b0)
Location: kernel/livepatch/core.c:625
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_replaced_patches_async
```
**Symbols:**

```
ffffffff811349b0-ffffffff81134ae4: __klp_free_objects (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __klp_free_objects(struct klp_patch *patch, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81135880)
Location: kernel/livepatch/core.c:624
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_replaced_patches_async
```
**Symbols:**

```
ffffffff81135880-ffffffff811359b4: __klp_free_objects (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __klp_free_objects(struct klp_patch *patch, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:624
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_replaced_patches_async
```
**Symbols:**

```
ffffffff81158480-ffffffff811585ce: __klp_free_objects (STB_LOCAL)
ffffffff81caf91e-ffffffff81caf956: __klp_free_objects.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __klp_free_objects(struct klp_patch *patch, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:624
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_replaced_patches_async
```
**Symbols:**

```
ffffffff81181970-ffffffff81181ae5: __klp_free_objects (STB_LOCAL)
ffffffff81e605c1-ffffffff81e605f1: __klp_free_objects.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __klp_free_objects(struct klp_patch *patch, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:649
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_replaced_patches_async
```
**Symbols:**

```
ffffffff811bc250-ffffffff811bc3c5: __klp_free_objects (STB_LOCAL)
ffffffff8205a398-ffffffff8205a3c8: __klp_free_objects.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __klp_free_objects(struct klp_patch *patch, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:664
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_replaced_patches_async
```
**Symbols:**

```
ffffffff811cebf0-ffffffff811ced65: __klp_free_objects (STB_LOCAL)
ffffffff820d8bc6-ffffffff820d8bf6: __klp_free_objects.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __klp_free_objects(struct klp_patch *patch, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:664
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
  - kernel/livepatch/core.c:klp_enable_patch
  - kernel/livepatch/core.c:klp_free_replaced_patches_async
```
**Symbols:**

```
ffffffff811e37d0-ffffffff811e3945: __klp_free_objects (STB_LOCAL)
ffffffff821b42ff-ffffffff821b432f: __klp_free_objects.cold (STB_LOCAL)
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
void __klp_free_objects(struct klp_patch *patch, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (c0000000001eea90)
Location: kernel/livepatch/core.c:603
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
  - kernel/livepatch/core.c:klp_free_patch_start
```
**Symbols:**

```
c0000000001eea90-c0000000001eec0c: __klp_free_objects (STB_LOCAL)
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
void __klp_free_objects(struct klp_patch *patch, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81123d70)
Location: kernel/livepatch/core.c:603
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
  - kernel/livepatch/core.c:klp_free_patch_start
```
**Symbols:**

```
ffffffff81123d70-ffffffff81123e96: __klp_free_objects (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __klp_free_objects(struct klp_patch *patch, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811167d0)
Location: kernel/livepatch/core.c:603
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
  - kernel/livepatch/core.c:klp_free_patch_start
```
**Symbols:**

```
ffffffff811167d0-ffffffff811168f6: __klp_free_objects (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __klp_free_objects(struct klp_patch *patch, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81121c60)
Location: kernel/livepatch/core.c:603
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
  - kernel/livepatch/core.c:klp_free_patch_start
```
**Symbols:**

```
ffffffff81121c60-ffffffff81121d86: __klp_free_objects (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __klp_free_objects(struct klp_patch *patch, bool nops_only);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8112e270)
Location: kernel/livepatch/core.c:603
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_discard_nops
  - kernel/livepatch/core.c:klp_free_patch_start
```
**Symbols:**

```
ffffffff8112e270-ffffffff8112e396: __klp_free_objects (STB_LOCAL)
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
