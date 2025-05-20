# Function: <code>fb_deferred_io_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fb_deferred_io_fault(struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_defio.c (ffffffff81473630)
Location: drivers/video/fbdev/core/fb_defio.c:40
Inline: False
```
**Symbols:**

```
ffffffff81473630-ffffffff81473723: fb_deferred_io_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int fb_deferred_io_fault(struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814c1c00)
Location: drivers/video/fbdev/core/fb_defio.c:40
Inline: True
```
**Symbols:**

```
ffffffff814c1c00-ffffffff814c1cc9: fb_deferred_io_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int fb_deferred_io_fault(struct vm_area_struct *vma, struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814e3bf0)
Location: drivers/video/fbdev/core/fb_defio.c:40
Inline: True
```
**Symbols:**

```
ffffffff814e3bf0-ffffffff814e3cb9: fb_deferred_io_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int fb_deferred_io_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_defio.c (ffffffff814ef950)
Location: drivers/video/fbdev/core/fb_defio.c:40
Inline: False
```
**Symbols:**

```
ffffffff814ef950-ffffffff814efa03: fb_deferred_io_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int fb_deferred_io_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_defio.c (ffffffff815244d0)
Location: drivers/video/fbdev/core/fb_defio.c:40
Inline: False
```
**Symbols:**

```
ffffffff815244d0-ffffffff81524583: fb_deferred_io_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: drivers/video/fbdev/core/fb_defio.c:40
Inline: False
```
**Symbols:**

```
ffffffff8155a230-ffffffff8155a2d5: fb_deferred_io_fault (STB_LOCAL)
ffffffff8155a546-ffffffff8155a55b: fb_deferred_io_fault.cold.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: drivers/video/fbdev/core/fb_defio.c:40
Inline: False
```
**Symbols:**

```
ffffffff81571b40-ffffffff81571be5: fb_deferred_io_fault (STB_LOCAL)
ffffffff81571e56-ffffffff81571e6b: fb_deferred_io_fault.cold.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: drivers/video/fbdev/core/fb_defio.c:40
Inline: False
```
**Symbols:**

```
ffffffff815a2020-ffffffff815a20c4: fb_deferred_io_fault (STB_LOCAL)
ffffffff815a232f-ffffffff815a2345: fb_deferred_io_fault.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: drivers/video/fbdev/core/fb_defio.c:40
Inline: False
```
**Symbols:**

```
ffffffff815c2ea0-ffffffff815c2f44: fb_deferred_io_fault (STB_LOCAL)
ffffffff815c31af-ffffffff815c31c5: fb_deferred_io_fault.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: drivers/video/fbdev/core/fb_defio.c:40
Inline: False
```
**Symbols:**

```
ffffffff8166d0d0-ffffffff8166d1a6: fb_deferred_io_fault (STB_LOCAL)
ffffffff8166d543-ffffffff8166d558: fb_deferred_io_fault.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: drivers/video/fbdev/core/fb_defio.c:40
Inline: False
```
**Symbols:**

```
ffffffff8168d7f0-ffffffff8168d8c6: fb_deferred_io_fault (STB_LOCAL)
ffffffff81bff019-ffffffff81bff02e: fb_deferred_io_fault.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: drivers/video/fbdev/core/fb_defio.c:40
Inline: False
```
**Symbols:**

```
ffffffff816704e0-ffffffff816705b6: fb_deferred_io_fault (STB_LOCAL)
ffffffff81bf0b98-ffffffff81bf0bad: fb_deferred_io_fault.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: drivers/video/fbdev/core/fb_defio.c:40
Inline: False
```
**Symbols:**

```
ffffffff816e47b0-ffffffff816e4886: fb_deferred_io_fault (STB_LOCAL)
ffffffff81cec6a7-ffffffff81cec6bc: fb_deferred_io_fault.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: drivers/video/fbdev/core/fb_defio.c:94
Inline: False
```
**Symbols:**

```
ffffffff8180f0d0-ffffffff8180f1ef: fb_deferred_io_fault (STB_LOCAL)
ffffffff81eb3af6-ffffffff81eb3b0b: fb_deferred_io_fault.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_defio.c (ffffffff8193dde0)
Location: drivers/video/fbdev/core/fb_defio.c:94
Inline: False
```
**Symbols:**

```
ffffffff8193dde0-ffffffff8193df15: fb_deferred_io_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_defio.c (ffffffff819821c0)
Location: drivers/video/fbdev/core/fb_defio.c:94
Inline: False
```
**Symbols:**

```
ffffffff819821c0-ffffffff819822f8: fb_deferred_io_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_defio.c (ffffffff819c99d0)
Location: drivers/video/fbdev/core/fb_defio.c:94
Inline: False
```
**Symbols:**

```
ffffffff819c99d0-ffffffff819c9b05: fb_deferred_io_fault (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_defio.c (ffff80001074c1f8)
Location: drivers/video/fbdev/core/fb_defio.c:40
Inline: False
```
**Symbols:**

```
ffff80001074c1f8-ffff80001074c2fc: fb_deferred_io_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_defio.c (c08ce884)
Location: drivers/video/fbdev/core/fb_defio.c:40
Inline: True
```
**Symbols:**

```
c08ce884-c08ce944: fb_deferred_io_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_defio.c (c0000000008ade40)
Location: drivers/video/fbdev/core/fb_defio.c:40
Inline: False
```
**Symbols:**

```
c0000000008ade40-c0000000008adf40: fb_deferred_io_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/fbdev/core/fb_defio.c (ffffffe0004f9bc6)
Location: drivers/video/fbdev/core/fb_defio.c:40
Inline: True
```
**Symbols:**

```
ffffffe0004f9bc6-ffffffe0004f9c8c: fb_deferred_io_fault (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: drivers/video/fbdev/core/fb_defio.c:40
Inline: False
```
**Symbols:**

```
ffffffff815b6ff0-ffffffff815b7094: fb_deferred_io_fault (STB_LOCAL)
ffffffff815b72ff-ffffffff815b7315: fb_deferred_io_fault.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: drivers/video/fbdev/core/fb_defio.c:40
Inline: False
```
**Symbols:**

```
ffffffff815a5dd0-ffffffff815a5e74: fb_deferred_io_fault (STB_LOCAL)
ffffffff815a60df-ffffffff815a60f5: fb_deferred_io_fault.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: drivers/video/fbdev/core/fb_defio.c:40
Inline: False
```
**Symbols:**

```
ffffffff815b7580-ffffffff815b7624: fb_deferred_io_fault (STB_LOCAL)
ffffffff815b788f-ffffffff815b78a5: fb_deferred_io_fault.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
vm_fault_t fb_deferred_io_fault(struct vm_fault *vmf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/video/fbdev/core/fb_defio.c (0)
Location: drivers/video/fbdev/core/fb_defio.c:40
Inline: False
```
**Symbols:**

```
ffffffff815d0ff0-ffffffff815d1094: fb_deferred_io_fault (STB_LOCAL)
ffffffff815d12fa-ffffffff815d1310: fb_deferred_io_fault.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, vmf</code> ➡️ <code>vmf</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>vm_fault_t</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
