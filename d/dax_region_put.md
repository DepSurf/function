# Function: <code>dax_region_put</code>

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
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void dax_region_put(struct dax_region *dax_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81740335)
Location: drivers/dax/bus.c:213
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:dax_region_unregister
```
**Symbols:**

```
ffffffff81740370-ffffffff81740394: dax_region_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void dax_region_put(struct dax_region *dax_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81764535)
Location: drivers/dax/bus.c:213
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:dax_region_unregister
```
**Symbols:**

```
ffffffff81764570-ffffffff81764594: dax_region_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void dax_region_put(struct dax_region *dax_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff818243fe)
Location: drivers/dax/bus.c:213
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:alloc_dax_region
```
**Symbols:**

```
ffffffff81824340-ffffffff81824378: dax_region_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void dax_region_put(struct dax_region *dax_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81833d7c)
Location: drivers/dax/bus.c:528
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:alloc_dax_region
```
**Symbols:**

```
ffffffff81833c80-ffffffff81833cb8: dax_region_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dax_region_put(struct dax_region *dax_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81816f6c)
Location: drivers/dax/bus.c:529
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:alloc_dax_region
```
**Symbols:**

```
ffffffff81816e70-ffffffff81816ea8: dax_region_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dax_region_put(struct dax_region *dax_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff818a15bc)
Location: drivers/dax/bus.c:527
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
```
**Symbols:**

```
ffffffff818a14c0-ffffffff818a14f8: dax_region_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dax_region_put(struct dax_region *dax_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff819eaccc)
Location: drivers/dax/bus.c:557
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:alloc_dax_region
```
**Symbols:**

```
ffffffff819eab90-ffffffff819eabec: dax_region_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dax_region_put(struct dax_region *dax_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81b677dc)
Location: drivers/dax/bus.c:557
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:alloc_dax_region
```
**Symbols:**

```
ffffffff81b67680-ffffffff81b676dc: dax_region_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81bba3ed)
Location: drivers/dax/bus.c:457
Inline: True
Inline callers:
  - drivers/dax/bus.c:dax_region_unregister
  - drivers/dax/bus.c:__free_dev_dax_id
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81c0e7bd)
Location: drivers/dax/bus.c:458
Inline: True
Inline callers:
  - drivers/dax/bus.c:dax_region_unregister
  - drivers/dax/bus.c:__free_dev_dax_id
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
void dax_region_put(struct dax_region *dax_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffff800010963d30)
Location: drivers/dax/bus.c:213
Inline: False
Direct callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:dax_region_unregister
```
**Symbols:**

```
ffff800010963d30-ffff800010963d6c: dax_region_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dax_region_put(struct dax_region *dax_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (c0a3a988)
Location: drivers/dax/bus.c:213
Inline: False
Direct callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:dax_region_unregister
```
**Symbols:**

```
c0a3a988-c0a3a9bc: dax_region_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dax_region_put(struct dax_region *dax_region);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (c000000000a1a4c0)
Location: drivers/dax/bus.c:213
Inline: False
Direct callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:dax_region_unregister
```
**Symbols:**

```
c000000000a1a4c0-c000000000a1a51c: dax_region_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void dax_region_put(struct dax_region *dax_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffe0005d111a)
Location: drivers/dax/bus.c:213
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:dax_region_unregister
```
**Symbols:**

```
ffffffe0005d1708-ffffffe0005d174e: dax_region_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void dax_region_put(struct dax_region *dax_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81718c25)
Location: drivers/dax/bus.c:213
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:dax_region_unregister
```
**Symbols:**

```
ffffffff81718c60-ffffffff81718c84: dax_region_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void dax_region_put(struct dax_region *dax_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff816f1155)
Location: drivers/dax/bus.c:213
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:dax_region_unregister
Direct callers:
  - drivers/dax/pmem/core.c:__dax_pmem_probe
```
**Symbols:**

```
ffffffff816f1190-ffffffff816f11b4: dax_region_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void dax_region_put(struct dax_region *dax_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff817579f5)
Location: drivers/dax/bus.c:213
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:dax_region_unregister
```
**Symbols:**

```
ffffffff81757a30-ffffffff81757a54: dax_region_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void dax_region_put(struct dax_region *dax_region);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81772e95)
Location: drivers/dax/bus.c:213
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:dax_region_unregister
```
**Symbols:**

```
ffffffff81772ed0-ffffffff81772ef4: dax_region_put (STB_GLOBAL)
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
