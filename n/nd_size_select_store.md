# Function: <code>nd_size_select_store</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t nd_size_select_store(struct device *dev, const char *buf, long unsigned int *current_size, const long unsigned int *supported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81695950)
Location: drivers/nvdimm/core.c:295
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:align_store
```
**Symbols:**

```
ffffffff81695950-ffffffff816959fa: nd_size_select_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t nd_size_select_store(struct device *dev, const char *buf, long unsigned int *current_size, const long unsigned int *supported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff816d1a00)
Location: drivers/nvdimm/core.c:295
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:align_store
```
**Symbols:**

```
ffffffff816d1a00-ffffffff816d1aa9: nd_size_select_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t nd_size_select_store(struct device *dev, const char *buf, long unsigned int *current_size, const long unsigned int *supported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff816f3090)
Location: drivers/nvdimm/core.c:295
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:align_store
```
**Symbols:**

```
ffffffff816f3090-ffffffff816f3139: nd_size_select_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t nd_size_select_store(struct device *dev, const char *buf, long unsigned int *current_size, const long unsigned int *supported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8172c5d0)
Location: drivers/nvdimm/core.c:287
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:align_store
```
**Symbols:**

```
ffffffff8172c5d0-ffffffff8172c66c: nd_size_select_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t nd_size_select_store(struct device *dev, const char *buf, long unsigned int *current_size, const long unsigned int *supported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81750810)
Location: drivers/nvdimm/core.c:287
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:align_store
```
**Symbols:**

```
ffffffff81750810-ffffffff817508ac: nd_size_select_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t nd_size_select_store(struct device *dev, const char *buf, long unsigned int *current_size, const long unsigned int *supported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8180f070)
Location: drivers/nvdimm/core.c:287
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:align_store
```
**Symbols:**

```
ffffffff8180f070-ffffffff8180f10c: nd_size_select_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t nd_size_select_store(struct device *dev, const char *buf, long unsigned int *current_size, const long unsigned int *supported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8181dfe0)
Location: drivers/nvdimm/core.c:287
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:align_store
```
**Symbols:**

```
ffffffff8181dfe0-ffffffff8181e07c: nd_size_select_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t nd_size_select_store(struct device *dev, const char *buf, long unsigned int *current_size, const long unsigned int *supported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81801330)
Location: drivers/nvdimm/core.c:287
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:align_store
```
**Symbols:**

```
ffffffff81801330-ffffffff818013cc: nd_size_select_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ssize_t nd_size_select_store(struct device *dev, const char *buf, long unsigned int *current_size, const long unsigned int *supported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8188b760)
Location: drivers/nvdimm/core.c:287
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:align_store
```
**Symbols:**

```
ffffffff8188b760-ffffffff8188b7fc: nd_size_select_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t nd_size_select_store(struct device *dev, const char *buf, long unsigned int *current_size, const long unsigned int *supported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff819d4a00)
Location: drivers/nvdimm/core.c:256
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:align_store
```
**Symbols:**

```
ffffffff819d4a00-ffffffff819d4aaf: nd_size_select_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t nd_size_select_store(struct device *dev, const char *buf, long unsigned int *current_size, const long unsigned int *supported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81b4f2d0)
Location: drivers/nvdimm/core.c:256
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:align_store
```
**Symbols:**

```
ffffffff81b4f2d0-ffffffff81b4f37f: nd_size_select_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t nd_size_select_store(struct device *dev, const char *buf, long unsigned int *current_size, const long unsigned int *supported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81ba2720)
Location: drivers/nvdimm/core.c:256
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:align_store
```
**Symbols:**

```
ffffffff81ba2720-ffffffff81ba27cf: nd_size_select_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t nd_size_select_store(struct device *dev, const char *buf, long unsigned int *current_size, const long unsigned int *supported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81bf68e0)
Location: drivers/nvdimm/core.c:256
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:align_store
```
**Symbols:**

```
ffffffff81bf68e0-ffffffff81bf698f: nd_size_select_store (STB_GLOBAL)
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
ssize_t nd_size_select_store(struct device *dev, const char *buf, long unsigned int *current_size, const long unsigned int *supported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffff8000109506c8)
Location: drivers/nvdimm/core.c:287
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
**Symbols:**

```
ffff8000109506c8-ffff800010950790: nd_size_select_store (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t nd_size_select_store(struct device *dev, const char *buf, long unsigned int *current_size, const long unsigned int *supported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (c0000000009fd070)
Location: drivers/nvdimm/core.c:287
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:align_store
```
**Symbols:**

```
c0000000009fd070-c0000000009fd1a8: nd_size_select_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t nd_size_select_store(struct device *dev, const char *buf, long unsigned int *current_size, const long unsigned int *supported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffe0005c08a4)
Location: drivers/nvdimm/core.c:287
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
```
**Symbols:**

```
ffffffe0005c08a4-ffffffe0005c0926: nd_size_select_store (STB_GLOBAL)
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
ssize_t nd_size_select_store(struct device *dev, const char *buf, long unsigned int *current_size, const long unsigned int *supported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81704f00)
Location: drivers/nvdimm/core.c:287
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:align_store
```
**Symbols:**

```
ffffffff81704f00-ffffffff81704f9c: nd_size_select_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t nd_size_select_store(struct device *dev, const char *buf, long unsigned int *current_size, const long unsigned int *supported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff816d8980)
Location: drivers/nvdimm/core.c:287
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:align_store
```
**Symbols:**

```
ffffffff816d8980-ffffffff816d8a1c: nd_size_select_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t nd_size_select_store(struct device *dev, const char *buf, long unsigned int *current_size, const long unsigned int *supported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff81743cd0)
Location: drivers/nvdimm/core.c:287
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:align_store
```
**Symbols:**

```
ffffffff81743cd0-ffffffff81743d6c: nd_size_select_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t nd_size_select_store(struct device *dev, const char *buf, long unsigned int *current_size, const long unsigned int *supported);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/core.c (ffffffff8175f120)
Location: drivers/nvdimm/core.c:287
Inline: False
Direct callers:
  - drivers/nvdimm/namespace_devs.c:sector_size_store
  - drivers/nvdimm/btt_devs.c:sector_size_store
  - drivers/nvdimm/pfn_devs.c:align_store
```
**Symbols:**

```
ffffffff8175f120-ffffffff8175f1bc: nd_size_select_store (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
