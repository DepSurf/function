# Function: <code>dma_direct_map_resource</code>

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
dma_addr_t dma_direct_map_resource(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81122db0)
Location: kernel/dma/direct.c:373
Inline: False
```
**Symbols:**

```
ffffffff81122db0-ffffffff81122e0f: dma_direct_map_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
dma_addr_t dma_direct_map_resource(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8112f1f0)
Location: kernel/dma/direct.c:373
Inline: False
```
**Symbols:**

```
ffffffff8112f1f0-ffffffff8112f244: dma_direct_map_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
dma_addr_t dma_direct_map_resource(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:460
Inline: False
```
**Symbols:**

```
ffffffff8113e55e-ffffffff8113e587: dma_direct_map_resource.cold (STB_LOCAL)
ffffffff8113dbf0-ffffffff8113dc79: dma_direct_map_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
dma_addr_t dma_direct_map_resource(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:417
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_map_resource
```
**Symbols:**

```
ffffffff81be35e9-ffffffff81be3619: dma_direct_map_resource.cold (STB_LOCAL)
ffffffff81139590-ffffffff8113961a: dma_direct_map_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
dma_addr_t dma_direct_map_resource(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:417
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_map_resource
```
**Symbols:**

```
ffffffff81bd54a4-ffffffff81bd54d4: dma_direct_map_resource.cold (STB_LOCAL)
ffffffff8113a660-ffffffff8113a6ed: dma_direct_map_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
dma_addr_t dma_direct_map_resource(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:457
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_map_resource
```
**Symbols:**

```
ffffffff81cb0437-ffffffff81cb0480: dma_direct_map_resource.cold (STB_LOCAL)
ffffffff8115d570-ffffffff8115d61f: dma_direct_map_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
dma_addr_t dma_direct_map_resource(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:489
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_map_resource
```
**Symbols:**

```
ffffffff81e61081-ffffffff81e610c9: dma_direct_map_resource.cold (STB_LOCAL)
ffffffff81187460-ffffffff81187522: dma_direct_map_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
dma_addr_t dma_direct_map_resource(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:520
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_map_resource
```
**Symbols:**

```
ffffffff8205a7e4-ffffffff8205a801: dma_direct_map_resource.cold (STB_LOCAL)
ffffffff811c3000-ffffffff811c30eb: dma_direct_map_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
dma_addr_t dma_direct_map_resource(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:519
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_map_resource
```
**Symbols:**

```
ffffffff820d9058-ffffffff820d9075: dma_direct_map_resource.cold (STB_LOCAL)
ffffffff811d5b40-ffffffff811d5c2b: dma_direct_map_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
dma_addr_t dma_direct_map_resource(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/dma/direct.c (0)
Location: kernel/dma/direct.c:508
Inline: False
Direct callers:
  - kernel/dma/mapping.c:dma_map_resource
```
**Symbols:**

```
ffffffff821b4899-ffffffff821b48b6: dma_direct_map_resource.cold (STB_LOCAL)
ffffffff811eaac0-ffffffff811eabab: dma_direct_map_resource (STB_GLOBAL)
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
dma_addr_t dma_direct_map_resource(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffff800010194be8)
Location: kernel/dma/direct.c:373
Inline: False
```
**Symbols:**

```
ffff800010194be8-ffff800010194c80: dma_direct_map_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
dma_addr_t dma_direct_map_resource(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c03e18b4)
Location: kernel/dma/direct.c:373
Inline: False
```
**Symbols:**

```
c03e18b4-c03e193c: dma_direct_map_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
dma_addr_t dma_direct_map_resource(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (c0000000001f4f20)
Location: kernel/dma/direct.c:373
Inline: False
```
**Symbols:**

```
c0000000001f4f20-c0000000001f4fb8: dma_direct_map_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
dma_addr_t dma_direct_map_resource(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffe000126a88)
Location: kernel/dma/direct.c:373
Inline: False
```
**Symbols:**

```
ffffffe000126a88-ffffffe000126af8: dma_direct_map_resource (STB_GLOBAL)
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
dma_addr_t dma_direct_map_resource(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811277d0)
Location: kernel/dma/direct.c:373
Inline: False
```
**Symbols:**

```
ffffffff811277d0-ffffffff81127824: dma_direct_map_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
dma_addr_t dma_direct_map_resource(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff8111a230)
Location: kernel/dma/direct.c:373
Inline: False
```
**Symbols:**

```
ffffffff8111a230-ffffffff8111a284: dma_direct_map_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
dma_addr_t dma_direct_map_resource(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff811256c0)
Location: kernel/dma/direct.c:373
Inline: False
```
**Symbols:**

```
ffffffff811256c0-ffffffff81125714: dma_direct_map_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
dma_addr_t dma_direct_map_resource(struct device *dev, phys_addr_t paddr, size_t size, enum dma_data_direction dir, long unsigned int attrs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/dma/direct.c (ffffffff81131d00)
Location: kernel/dma/direct.c:373
Inline: False
```
**Symbols:**

```
ffffffff81131d00-ffffffff81131d54: dma_direct_map_resource (STB_GLOBAL)
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
