# Function: <code>klp_init_object_loaded</code>

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
In kernel/livepatch/core.c (ffffffff810e8d20)
Location: kernel/livepatch/core.c:700
Inline: True
Direct callers:
  - kernel/livepatch/core.c:klp_register_patch
```
**Symbols:**

```
ffffffff810e8d20-ffffffff810e8ee2: klp_init_object_loaded.isra.11 (STB_LOCAL)
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
In kernel/livepatch/core.c (ffffffff810f01ee)
Location: kernel/livepatch/core.c:767
Inline: True
Inline callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_register_patch
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_register_patch
```
**Symbols:**

```
ffffffff810ef7e0-ffffffff810ef831: klp_init_object_loaded.isra.13.part.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int klp_init_object_loaded(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810f6d00)
Location: kernel/livepatch/core.c:768
Inline: True
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_register_patch
```
**Symbols:**

```
ffffffff810f6d00-ffffffff810f6f0c: klp_init_object_loaded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int klp_init_object_loaded(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810f7e30)
Location: kernel/livepatch/core.c:629
Inline: True
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_register_patch
```
**Symbols:**

```
ffffffff810f7e30-ffffffff810f807e: klp_init_object_loaded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int klp_init_object_loaded(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811020e0)
Location: kernel/livepatch/core.c:643
Inline: True
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_register_patch
```
**Symbols:**

```
ffffffff811020e0-ffffffff8110232e: klp_init_object_loaded (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int klp_init_object_loaded(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:705
Inline: True
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_register_patch
```
**Symbols:**

```
ffffffff8110a4c0-ffffffff8110a6be: klp_init_object_loaded (STB_LOCAL)
ffffffff8110ad77-ffffffff8110adc9: klp_init_object_loaded.cold.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int klp_init_object_loaded(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81115db0)
Location: kernel/livepatch/core.c:705
Inline: True
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_register_patch
```
**Symbols:**

```
ffffffff81115c90-ffffffff81115e8e: klp_init_object_loaded (STB_LOCAL)
ffffffff81116567-ffffffff811165b9: klp_init_object_loaded.cold.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int klp_init_object_loaded(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8111f9d2)
Location: kernel/livepatch/core.c:716
Inline: True
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff8111f8a0-ffffffff8111fae6: klp_init_object_loaded (STB_LOCAL)
ffffffff8112056b-ffffffff811205ce: klp_init_object_loaded.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int klp_init_object_loaded(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8112c122)
Location: kernel/livepatch/core.c:716
Inline: True
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff8112bff0-ffffffff8112c23d: klp_init_object_loaded (STB_LOCAL)
ffffffff8112cc74-ffffffff8112ccc6: klp_init_object_loaded.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int klp_init_object_loaded(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:772
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_init_object
```
**Symbols:**

```
ffffffff8113a820-ffffffff8113a930: klp_init_object_loaded (STB_LOCAL)
ffffffff8113b438-ffffffff8113b46a: klp_init_object_loaded.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int klp_init_object_loaded(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:772
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_init_object
```
**Symbols:**

```
ffffffff81135310-ffffffff81135420: klp_init_object_loaded (STB_LOCAL)
ffffffff81be3147-ffffffff81be3179: klp_init_object_loaded.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int klp_init_object_loaded(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:771
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_init_object
```
**Symbols:**

```
ffffffff811361f0-ffffffff81136300: klp_init_object_loaded (STB_LOCAL)
ffffffff81bd4ee9-ffffffff81bd4f1b: klp_init_object_loaded.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int klp_init_object_loaded(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:771
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_init_object
```
**Symbols:**

```
ffffffff81158da0-ffffffff81158ebf: klp_init_object_loaded (STB_LOCAL)
ffffffff81cafa4c-ffffffff81cafa93: klp_init_object_loaded.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int klp_init_object_loaded(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:771
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_init_object
```
**Symbols:**

```
ffffffff811822e0-ffffffff81182411: klp_init_object_loaded (STB_LOCAL)
ffffffff81e606e5-ffffffff81e60724: klp_init_object_loaded.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int klp_init_object_loaded(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:796
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_init_object
```
**Symbols:**

```
ffffffff811bcf60-ffffffff811bd0d3: klp_init_object_loaded (STB_LOCAL)
ffffffff8205a4e4-ffffffff8205a4f9: klp_init_object_loaded.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int klp_init_object_loaded(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:824
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_init_object
```
**Symbols:**

```
ffffffff811cf7e0-ffffffff811cf8e8: klp_init_object_loaded (STB_LOCAL)
ffffffff820d8ce9-ffffffff820d8cfe: klp_init_object_loaded.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int klp_init_object_loaded(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:824
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
  - kernel/livepatch/core.c:klp_init_object
```
**Symbols:**

```
ffffffff811e4430-ffffffff811e4538: klp_init_object_loaded (STB_LOCAL)
ffffffff821b4422-ffffffff821b4437: klp_init_object_loaded.cold (STB_LOCAL)
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
int klp_init_object_loaded(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (c0000000001efea0)
Location: kernel/livepatch/core.c:716
Inline: True
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
c0000000001efea0-c0000000001f03d8: klp_init_object_loaded (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int klp_init_object_loaded(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81124702)
Location: kernel/livepatch/core.c:716
Inline: True
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff811245d0-ffffffff8112481d: klp_init_object_loaded (STB_LOCAL)
ffffffff81125254-ffffffff811252a6: klp_init_object_loaded.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int klp_init_object_loaded(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81117162)
Location: kernel/livepatch/core.c:716
Inline: True
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff81117030-ffffffff8111727d: klp_init_object_loaded (STB_LOCAL)
ffffffff81117cb4-ffffffff81117d06: klp_init_object_loaded.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int klp_init_object_loaded(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811225f2)
Location: kernel/livepatch/core.c:716
Inline: True
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff811224c0-ffffffff8112270d: klp_init_object_loaded (STB_LOCAL)
ffffffff81123144-ffffffff81123196: klp_init_object_loaded.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int klp_init_object_loaded(struct klp_patch *patch, struct klp_object *obj);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (ffffffff8112ec02)
Location: kernel/livepatch/core.c:716
Inline: True
Direct callers:
  - kernel/livepatch/core.c:klp_module_coming
```
**Symbols:**

```
ffffffff8112ead0-ffffffff8112ed1d: klp_init_object_loaded (STB_LOCAL)
ffffffff8112f754-ffffffff8112f7a6: klp_init_object_loaded.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
