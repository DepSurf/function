# Function: <code>init_vdso_image</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void init_vdso_image(const struct vdso_image *image);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81f5ccbf)
Location: arch/x86/entry/vdso/vma.c:28
Inline: True
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vdso32-setup.c:sysenter_setup
```
**Symbols:**

```
ffffffff81f5ccbf-ffffffff81f5cd48: init_vdso_image (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void init_vdso_image(const struct vdso_image *image);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81f84c7a)
Location: arch/x86/entry/vdso/vma.c:29
Inline: True
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vdso32-setup.c:sysenter_setup
```
**Symbols:**

```
ffffffff81f84c7a-ffffffff81f84ca4: init_vdso_image (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void init_vdso_image(const struct vdso_image *image);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff81fc008b)
Location: arch/x86/entry/vdso/vma.c:29
Inline: True
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vdso32-setup.c:sysenter_setup
```
**Symbols:**

```
ffffffff81fc008b-ffffffff81fc00b5: init_vdso_image (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void init_vdso_image(const struct vdso_image *image);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff820a0244)
Location: arch/x86/entry/vdso/vma.c:31
Inline: True
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vdso32-setup.c:sysenter_setup
```
**Symbols:**

```
ffffffff820a0244-ffffffff820a0273: init_vdso_image (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void init_vdso_image(const struct vdso_image *image);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff826a6244)
Location: arch/x86/entry/vdso/vma.c:31
Inline: True
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vdso32-setup.c:sysenter_setup
```
**Symbols:**

```
ffffffff826a6244-ffffffff826a6273: init_vdso_image (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void init_vdso_image(const struct vdso_image *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff826cf404)
Location: arch/x86/entry/vdso/vma.c:31
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vdso32-setup.c:sysenter_setup
```
**Symbols:**

```
ffffffff826cf404-ffffffff826cf433: init_vdso_image (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void init_vdso_image(const struct vdso_image *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff82885452)
Location: arch/x86/entry/vdso/vma.c:31
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vdso32-setup.c:sysenter_setup
```
**Symbols:**

```
ffffffff82885452-ffffffff82885481: init_vdso_image (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void init_vdso_image(const struct vdso_image *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff8289c4af)
Location: arch/x86/entry/vdso/vma.c:31
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vdso32-setup.c:sysenter_setup
```
**Symbols:**

```
ffffffff8289c4af-ffffffff8289c4de: init_vdso_image (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void init_vdso_image(const struct vdso_image *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff8289f49f)
Location: arch/x86/entry/vdso/vma.c:31
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vdso32-setup.c:sysenter_setup
```
**Symbols:**

```
ffffffff8289f49f-ffffffff8289f4ce: init_vdso_image (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void init_vdso_image(const struct vdso_image *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff82cc592a)
Location: arch/x86/entry/vdso/vma.c:47
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vdso32-setup.c:sysenter_setup
```
**Symbols:**

```
ffffffff82cc592a-ffffffff82cc5959: init_vdso_image (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void init_vdso_image(const struct vdso_image *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff82fb121e)
Location: arch/x86/entry/vdso/vma.c:47
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vdso32-setup.c:sysenter_setup
```
**Symbols:**

```
ffffffff82fb121e-ffffffff82fb124d: init_vdso_image (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void init_vdso_image(const struct vdso_image *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff831bb3a9)
Location: arch/x86/entry/vdso/vma.c:47
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vdso32-setup.c:sysenter_setup
```
**Symbols:**

```
ffffffff831bb3a9-ffffffff831bb3d8: init_vdso_image (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void init_vdso_image(const struct vdso_image *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff8329b8b1)
Location: arch/x86/entry/vdso/vma.c:47
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vdso32-setup.c:sysenter_setup
```
**Symbols:**

```
ffffffff8329b8b1-ffffffff8329b8e0: init_vdso_image (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void init_vdso_image(const struct vdso_image *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff8344a08b)
Location: arch/x86/entry/vdso/vma.c:47
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vdso32-setup.c:sysenter_setup
```
**Symbols:**

```
ffffffff8344a08b-ffffffff8344a0c6: init_vdso_image (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void init_vdso_image(const struct vdso_image *image);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff83e64625)
Location: arch/x86/entry/vdso/vma.c:47
Inline: True
Inline callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
Direct callers:
  - arch/x86/entry/vdso/vdso32-setup.c:sysenter_setup
```
**Symbols:**

```
ffffffff83e64680-ffffffff83e646bb: init_vdso_image (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int init_vdso_image(const struct vdso_image *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff83684cb0)
Location: arch/x86/entry/vdso/vma.c:47
Inline: False
Direct callers:
  - debian/build/build-generic/arch/x86/entry/vdso/vdso-image-64.c:init_vdso_image_64
  - debian/build/build-generic/arch/x86/entry/vdso/vdso-image-32.c:init_vdso_image_32
```
**Symbols:**

```
ffffffff83684cb0-ffffffff83684ceb: init_vdso_image (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int init_vdso_image(const struct vdso_image *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff838b3e50)
Location: arch/x86/entry/vdso/vma.c:47
Inline: False
Direct callers:
  - debian/build/build-generic/arch/x86/entry/vdso/vdso-image-64.c:init_vdso_image_64
  - debian/build/build-generic/arch/x86/entry/vdso/vdso-image-32.c:init_vdso_image_32
```
**Symbols:**

```
ffffffff838b3e50-ffffffff838b3e8b: init_vdso_image (STB_GLOBAL)
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
In <code>ppc64el</code>: Absent ⚠️
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
void init_vdso_image(const struct vdso_image *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff8288d49f)
Location: arch/x86/entry/vdso/vma.c:31
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vdso32-setup.c:sysenter_setup
```
**Symbols:**

```
ffffffff8288d49f-ffffffff8288d4ce: init_vdso_image (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void init_vdso_image(const struct vdso_image *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff8288b41c)
Location: arch/x86/entry/vdso/vma.c:31
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vdso32-setup.c:sysenter_setup
```
**Symbols:**

```
ffffffff8288b41c-ffffffff8288b44b: init_vdso_image (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void init_vdso_image(const struct vdso_image *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff828a049f)
Location: arch/x86/entry/vdso/vma.c:31
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vdso32-setup.c:sysenter_setup
```
**Symbols:**

```
ffffffff828a049f-ffffffff828a04ce: init_vdso_image (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void init_vdso_image(const struct vdso_image *image);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/entry/vdso/vma.c (ffffffff828a04a4)
Location: arch/x86/entry/vdso/vma.c:31
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/entry/vdso/vdso32-setup.c:sysenter_setup
```
**Symbols:**

```
ffffffff828a04a4-ffffffff828a04d3: init_vdso_image (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
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
