# Function: <code>nvmem_bin_attr_get_umode</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/nvmem/core.c (ffffffff819db3cb)
Location: drivers/nvmem/core.c:194
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_bin_attr_is_visible
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
In drivers/nvmem/core.c (ffffffff819daa11)
Location: drivers/nvmem/core.c:284
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_bin_attr_is_visible
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
In drivers/nvmem/core.c (ffffffff819c05e8)
Location: drivers/nvmem/core.c:284
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_register
  - drivers/nvmem/core.c:nvmem_bin_attr_is_visible
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
umode_t nvmem_bin_attr_get_umode(struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81a6f1fe)
Location: drivers/nvmem/core.c:285
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_bin_attr_is_visible
Direct callers:
  - drivers/nvmem/core.c:nvmem_register
```
**Symbols:**

```
ffffffff81a6e9f0-ffffffff81a6ea7a: nvmem_bin_attr_get_umode (STB_LOCAL)
ffffffff81d34455-ffffffff81d34485: nvmem_bin_attr_get_umode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
umode_t nvmem_bin_attr_get_umode(struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81be03de)
Location: drivers/nvmem/core.c:290
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_bin_attr_is_visible
Direct callers:
  - drivers/nvmem/core.c:nvmem_register
```
**Symbols:**

```
ffffffff81bdf850-ffffffff81bdf8ee: nvmem_bin_attr_get_umode (STB_LOCAL)
ffffffff81f007af-ffffffff81f007df: nvmem_bin_attr_get_umode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
umode_t nvmem_bin_attr_get_umode(struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81d8c23e)
Location: drivers/nvmem/core.c:290
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_bin_attr_is_visible
Direct callers:
  - drivers/nvmem/core.c:nvmem_register
```
**Symbols:**

```
ffffffff81d8af60-ffffffff81d8affe: nvmem_bin_attr_get_umode (STB_LOCAL)
ffffffff820aa6c5-ffffffff820aa6f5: nvmem_bin_attr_get_umode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
umode_t nvmem_bin_attr_get_umode(struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81dfa8be)
Location: drivers/nvmem/core.c:298
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_bin_attr_is_visible
Direct callers:
  - drivers/nvmem/core.c:nvmem_register
```
**Symbols:**

```
ffffffff81df96e0-ffffffff81df977e: nvmem_bin_attr_get_umode (STB_LOCAL)
ffffffff8212bbd3-ffffffff8212bc03: nvmem_bin_attr_get_umode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
umode_t nvmem_bin_attr_get_umode(struct nvmem_device *nvmem);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/nvmem/core.c (ffffffff81eb0cee)
Location: drivers/nvmem/core.c:272
Inline: True
Inline callers:
  - drivers/nvmem/core.c:nvmem_bin_attr_is_visible
Direct callers:
  - drivers/nvmem/core.c:nvmem_register
```
**Symbols:**

```
ffffffff81eafd60-ffffffff81eafdfe: nvmem_bin_attr_get_umode (STB_LOCAL)
ffffffff8220d868-ffffffff8220d898: nvmem_bin_attr_get_umode.cold (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
