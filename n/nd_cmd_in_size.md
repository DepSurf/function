# Function: <code>nd_cmd_in_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
u32 nd_cmd_in_size(struct nvdimm *nvdimm, int cmd, const struct nd_cmd_desc *desc, int idx, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff815978b0)
Location: drivers/nvdimm/bus.c:408
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
```
**Symbols:**

```
ffffffff815978b0-ffffffff81597902: nd_cmd_in_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 nd_cmd_in_size(struct nvdimm *nvdimm, int cmd, const struct nd_cmd_desc *desc, int idx, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff815ed855)
Location: drivers/nvdimm/bus.c:687
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
```
**Symbols:**

```
ffffffff815ec960-ffffffff815ec9af: nd_cmd_in_size.part.9 (STB_LOCAL)
ffffffff815ec9b0-ffffffff815ec9dc: nd_cmd_in_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 nd_cmd_in_size(struct nvdimm *nvdimm, int cmd, const struct nd_cmd_desc *desc, int idx, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8161a655)
Location: drivers/nvdimm/bus.c:689
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
```
**Symbols:**

```
ffffffff81619740-ffffffff8161978f: nd_cmd_in_size.part.11 (STB_LOCAL)
ffffffff81619790-ffffffff816197bc: nd_cmd_in_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 nd_cmd_in_size(struct nvdimm *nvdimm, int cmd, const struct nd_cmd_desc *desc, int idx, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8162e74e)
Location: drivers/nvdimm/bus.c:752
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
```
**Symbols:**

```
ffffffff8162d670-ffffffff8162d6b1: nd_cmd_in_size.part.9 (STB_LOCAL)
ffffffff8162d6c0-ffffffff8162d6ec: nd_cmd_in_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 nd_cmd_in_size(struct nvdimm *nvdimm, int cmd, const struct nd_cmd_desc *desc, int idx, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81696f09)
Location: drivers/nvdimm/bus.c:752
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
```
**Symbols:**

```
ffffffff81695e20-ffffffff81695e61: nd_cmd_in_size.part.9 (STB_LOCAL)
ffffffff81695e70-ffffffff81695e9c: nd_cmd_in_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 nd_cmd_in_size(struct nvdimm *nvdimm, int cmd, const struct nd_cmd_desc *desc, int idx, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816d3070)
Location: drivers/nvdimm/bus.c:760
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
```
**Symbols:**

```
ffffffff816d1ee0-ffffffff816d1f21: nd_cmd_in_size.part.11 (STB_LOCAL)
ffffffff816d1f30-ffffffff816d1f5b: nd_cmd_in_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 nd_cmd_in_size(struct nvdimm *nvdimm, int cmd, const struct nd_cmd_desc *desc, int idx, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816f4799)
Location: drivers/nvdimm/bus.c:789
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
```
**Symbols:**

```
ffffffff816f3570-ffffffff816f35b1: nd_cmd_in_size.part.11 (STB_LOCAL)
ffffffff816f35c0-ffffffff816f35eb: nd_cmd_in_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 nd_cmd_in_size(struct nvdimm *nvdimm, int cmd, const struct nd_cmd_desc *desc, int idx, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8172dd65)
Location: drivers/nvdimm/bus.c:820
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
```
**Symbols:**

```
ffffffff8172caa0-ffffffff8172cae1: nd_cmd_in_size.part.0 (STB_LOCAL)
ffffffff8172caf0-ffffffff8172cb1f: nd_cmd_in_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 nd_cmd_in_size(struct nvdimm *nvdimm, int cmd, const struct nd_cmd_desc *desc, int idx, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81752005)
Location: drivers/nvdimm/bus.c:818
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
```
**Symbols:**

```
ffffffff81750cc0-ffffffff81750d01: nd_cmd_in_size.part.0 (STB_LOCAL)
ffffffff81750d10-ffffffff81750d3f: nd_cmd_in_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u32 nd_cmd_in_size(struct nvdimm *nvdimm, int cmd, const struct nd_cmd_desc *desc, int idx, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8180f5c0)
Location: drivers/nvdimm/bus.c:850
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
```
**Symbols:**

```
ffffffff8180f5c0-ffffffff8180f60e: nd_cmd_in_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u32 nd_cmd_in_size(struct nvdimm *nvdimm, int cmd, const struct nd_cmd_desc *desc, int idx, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8181e500)
Location: drivers/nvdimm/bus.c:847
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
```
**Symbols:**

```
ffffffff8181e500-ffffffff8181e54e: nd_cmd_in_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u32 nd_cmd_in_size(struct nvdimm *nvdimm, int cmd, const struct nd_cmd_desc *desc, int idx, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81801840)
Location: drivers/nvdimm/bus.c:842
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
```
**Symbols:**

```
ffffffff81801840-ffffffff8180188e: nd_cmd_in_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u32 nd_cmd_in_size(struct nvdimm *nvdimm, int cmd, const struct nd_cmd_desc *desc, int idx, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff8188bce0)
Location: drivers/nvdimm/bus.c:859
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
```
**Symbols:**

```
ffffffff8188bce0-ffffffff8188bdb4: nd_cmd_in_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 nd_cmd_in_size(struct nvdimm *nvdimm, int cmd, const struct nd_cmd_desc *desc, int idx, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff819d4b50)
Location: drivers/nvdimm/bus.c:850
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
```
**Symbols:**

```
ffffffff819d4b50-ffffffff819d4c6b: nd_cmd_in_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 nd_cmd_in_size(struct nvdimm *nvdimm, int cmd, const struct nd_cmd_desc *desc, int idx, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81b4f450)
Location: drivers/nvdimm/bus.c:863
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
```
**Symbols:**

```
ffffffff81b4f450-ffffffff81b4f56b: nd_cmd_in_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 nd_cmd_in_size(struct nvdimm *nvdimm, int cmd, const struct nd_cmd_desc *desc, int idx, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81ba28a0)
Location: drivers/nvdimm/bus.c:863
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
```
**Symbols:**

```
ffffffff81ba28a0-ffffffff81ba29bb: nd_cmd_in_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 nd_cmd_in_size(struct nvdimm *nvdimm, int cmd, const struct nd_cmd_desc *desc, int idx, void *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81bf6a60)
Location: drivers/nvdimm/bus.c:863
Inline: False
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
```
**Symbols:**

```
ffffffff81bf6a60-ffffffff81bf6b7b: nd_cmd_in_size (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 nd_cmd_in_size(struct nvdimm *nvdimm, int cmd, const struct nd_cmd_desc *desc, int idx, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffff8000109527e0)
Location: drivers/nvdimm/bus.c:818
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
```
**Symbols:**

```
ffff800010950e20-ffff800010950ebc: nd_cmd_in_size.part.0 (STB_LOCAL)
ffff800010950ec0-ffff800010950f60: nd_cmd_in_size (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
u32 nd_cmd_in_size(struct nvdimm *nvdimm, int cmd, const struct nd_cmd_desc *desc, int idx, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (c0000000009fdbb0)
Location: drivers/nvdimm/bus.c:818
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
```
**Symbols:**

```
c0000000009fdbb0-c0000000009fdc30: nd_cmd_in_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
u32 nd_cmd_in_size(struct nvdimm *nvdimm, int cmd, const struct nd_cmd_desc *desc, int idx, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffe0005c0e9e)
Location: drivers/nvdimm/bus.c:818
Inline: True
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
```
**Symbols:**

```
ffffffe0005c0e9e-ffffffe0005c0f2e: nd_cmd_in_size (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 nd_cmd_in_size(struct nvdimm *nvdimm, int cmd, const struct nd_cmd_desc *desc, int idx, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff817066f5)
Location: drivers/nvdimm/bus.c:818
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
```
**Symbols:**

```
ffffffff817053b0-ffffffff817053f1: nd_cmd_in_size.part.0 (STB_LOCAL)
ffffffff81705400-ffffffff8170542f: nd_cmd_in_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 nd_cmd_in_size(struct nvdimm *nvdimm, int cmd, const struct nd_cmd_desc *desc, int idx, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff816da175)
Location: drivers/nvdimm/bus.c:818
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
Direct callers:
  - drivers/acpi/nfit/core.c:acpi_nfit_ctl
  - drivers/nvdimm/bus.c:__nd_ioctl
```
**Symbols:**

```
ffffffff816d8e30-ffffffff816d8e71: nd_cmd_in_size.part.0 (STB_LOCAL)
ffffffff816d8e80-ffffffff816d8eaf: nd_cmd_in_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 nd_cmd_in_size(struct nvdimm *nvdimm, int cmd, const struct nd_cmd_desc *desc, int idx, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff817454c5)
Location: drivers/nvdimm/bus.c:818
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
```
**Symbols:**

```
ffffffff81744180-ffffffff817441c1: nd_cmd_in_size.part.0 (STB_LOCAL)
ffffffff817441d0-ffffffff817441ff: nd_cmd_in_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
u32 nd_cmd_in_size(struct nvdimm *nvdimm, int cmd, const struct nd_cmd_desc *desc, int idx, void *buf);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/bus.c (ffffffff81760905)
Location: drivers/nvdimm/bus.c:818
Inline: True
Inline callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
Direct callers:
  - drivers/nvdimm/bus.c:__nd_ioctl
```
**Symbols:**

```
ffffffff8175f5d0-ffffffff8175f611: nd_cmd_in_size.part.0 (STB_LOCAL)
ffffffff8175f620-ffffffff8175f64f: nd_cmd_in_size (STB_GLOBAL)
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
