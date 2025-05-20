# Function: <code>rio_get_comptag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct rio_dev *rio_get_comptag(u32 comp_tag, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81458620)
Location: drivers/rapidio/rio.c:547
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff81458620-ffffffff81458692: rio_get_comptag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct rio_dev *rio_get_comptag(u32 comp_tag, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff814a5fd0)
Location: drivers/rapidio/rio.c:852
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff814a5fd0-ffffffff814a6043: rio_get_comptag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct rio_dev *rio_get_comptag(u32 comp_tag, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff814c80e0)
Location: drivers/rapidio/rio.c:852
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff814c80e0-ffffffff814c8153: rio_get_comptag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct rio_dev *rio_get_comptag(u32 comp_tag, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff814d3f20)
Location: drivers/rapidio/rio.c:849
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff814d3f20-ffffffff814d3f92: rio_get_comptag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct rio_dev *rio_get_comptag(u32 comp_tag, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815143b0)
Location: drivers/rapidio/rio.c:849
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff815143b0-ffffffff81514422: rio_get_comptag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct rio_dev *rio_get_comptag(u32 comp_tag, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff8154bbf0)
Location: drivers/rapidio/rio.c:844
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff8154bbf0-ffffffff8154bc62: rio_get_comptag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct rio_dev *rio_get_comptag(u32 comp_tag, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81562f80)
Location: drivers/rapidio/rio.c:844
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff81562f80-ffffffff81562ff2: rio_get_comptag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct rio_dev *rio_get_comptag(u32 comp_tag, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81593360)
Location: drivers/rapidio/rio.c:840
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff81593360-ffffffff815933bf: rio_get_comptag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct rio_dev *rio_get_comptag(u32 comp_tag, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815b45e0)
Location: drivers/rapidio/rio.c:840
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff815b45e0-ffffffff815b463f: rio_get_comptag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct rio_dev *rio_get_comptag(u32 comp_tag, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff8165ee56)
Location: drivers/rapidio/rio.c:840
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff8165dcb0-ffffffff8165dd0f: rio_get_comptag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct rio_dev *rio_get_comptag(u32 comp_tag, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81680206)
Location: drivers/rapidio/rio.c:840
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff8167f3d0-ffffffff8167f42f: rio_get_comptag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct rio_dev *rio_get_comptag(u32 comp_tag, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff816625a8)
Location: drivers/rapidio/rio.c:840
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff81662c60-ffffffff81662cbf: rio_get_comptag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct rio_dev *rio_get_comptag(u32 comp_tag, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff816d53d8)
Location: drivers/rapidio/rio.c:840
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff816d5b40-ffffffff816d5b9f: rio_get_comptag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct rio_dev *rio_get_comptag(u32 comp_tag, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff817ff5f1)
Location: drivers/rapidio/rio.c:840
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff817fc8a0-ffffffff817fc909: rio_get_comptag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct rio_dev *rio_get_comptag(u32 comp_tag, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff8192c921)
Location: drivers/rapidio/rio.c:840
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff819297d0-ffffffff81929839: rio_get_comptag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct rio_dev *rio_get_comptag(u32 comp_tag, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff81970bb1)
Location: drivers/rapidio/rio.c:840
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff8196da40-ffffffff8196daa9: rio_get_comptag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct rio_dev *rio_get_comptag(u32 comp_tag, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff819bac21)
Location: drivers/rapidio/rio.c:840
Inline: True
Inline callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff819b7930-ffffffff819b7999: rio_get_comptag (STB_GLOBAL)
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
struct rio_dev *rio_get_comptag(u32 comp_tag, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffff80001073c5f0)
Location: drivers/rapidio/rio.c:840
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffff80001073c5f0-ffff80001073c6dc: rio_get_comptag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rio_dev *rio_get_comptag(u32 comp_tag, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (c08bfa68)
Location: drivers/rapidio/rio.c:840
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
c08bfa68-c08bfb18: rio_get_comptag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rio_dev *rio_get_comptag(u32 comp_tag, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (c0000000008960f0)
Location: drivers/rapidio/rio.c:840
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
c0000000008960f0-c00000000089623c: rio_get_comptag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct rio_dev *rio_get_comptag(u32 comp_tag, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffe0004ec4aa)
Location: drivers/rapidio/rio.c:840
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffe0004ec4aa-ffffffe0004ec558: rio_get_comptag (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct rio_dev *rio_get_comptag(u32 comp_tag, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815a8850)
Location: drivers/rapidio/rio.c:840
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff815a8850-ffffffff815a88af: rio_get_comptag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct rio_dev *rio_get_comptag(u32 comp_tag, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815979f0)
Location: drivers/rapidio/rio.c:840
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff815979f0-ffffffff81597a4f: rio_get_comptag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct rio_dev *rio_get_comptag(u32 comp_tag, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815a8de0)
Location: drivers/rapidio/rio.c:840
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff815a8de0-ffffffff815a8e3f: rio_get_comptag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct rio_dev *rio_get_comptag(u32 comp_tag, struct rio_dev *from);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rapidio/rio.c (ffffffff815c0b90)
Location: drivers/rapidio/rio.c:840
Inline: False
Direct callers:
  - drivers/rapidio/rio.c:rio_inb_pwrite_handler
```
**Symbols:**

```
ffffffff815c0b90-ffffffff815c0c03: rio_get_comptag (STB_GLOBAL)
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
