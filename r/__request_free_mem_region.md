# Function: <code>__request_free_mem_region</code>

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
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/resource.c (ffffffff810a9270)
Location: kernel/resource.c:1647
Inline: True
Direct callers:
  - kernel/resource.c:request_free_mem_region
  - kernel/resource.c:devm_request_free_mem_region
```
**Symbols:**

```
ffffffff810a9270-ffffffff810a934d: __request_free_mem_region.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct resource *__request_free_mem_region(struct device *dev, struct resource *base, long unsigned int size, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810b08d0)
Location: kernel/resource.c:1652
Inline: False
Direct callers:
  - kernel/resource.c:request_free_mem_region
  - kernel/resource.c:devm_request_free_mem_region
```
**Symbols:**

```
ffffffff810b08d0-ffffffff810b09d3: __request_free_mem_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct resource *__request_free_mem_region(struct device *dev, struct resource *base, long unsigned int size, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ac000)
Location: kernel/resource.c:1725
Inline: False
Direct callers:
  - kernel/resource.c:request_free_mem_region
  - kernel/resource.c:devm_request_free_mem_region
```
**Symbols:**

```
ffffffff810ac000-ffffffff810ac103: __request_free_mem_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct resource *__request_free_mem_region(struct device *dev, struct resource *base, long unsigned int size, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ad440)
Location: kernel/resource.c:1778
Inline: False
Direct callers:
  - kernel/resource.c:request_free_mem_region
  - kernel/resource.c:devm_request_free_mem_region
```
**Symbols:**

```
ffffffff810ad440-ffffffff810ad5e7: __request_free_mem_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct resource *__request_free_mem_region(struct device *dev, struct resource *base, long unsigned int size, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810befc0)
Location: kernel/resource.c:1778
Inline: False
Direct callers:
  - kernel/resource.c:request_free_mem_region
  - kernel/resource.c:devm_request_free_mem_region
```
**Symbols:**

```
ffffffff810befc0-ffffffff810bf16e: __request_free_mem_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct resource *__request_free_mem_region(struct device *dev, struct resource *base, long unsigned int size, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d60e0)
Location: kernel/resource.c:1777
Inline: False
Direct callers:
  - kernel/resource.c:request_free_mem_region
  - kernel/resource.c:devm_request_free_mem_region
```
**Symbols:**

```
ffffffff810d60e0-ffffffff810d62da: __request_free_mem_region (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/resource.c (c0000000001485b0)
Location: kernel/resource.c:1647
Inline: True
Direct callers:
  - kernel/resource.c:request_free_mem_region
  - kernel/resource.c:devm_request_free_mem_region
```
**Symbols:**

```
c0000000001485b0-c00000000014872c: __request_free_mem_region.isra.0 (STB_LOCAL)
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

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/resource.c (ffffffff810a2b90)
Location: kernel/resource.c:1647
Inline: True
Direct callers:
  - kernel/resource.c:request_free_mem_region
  - kernel/resource.c:devm_request_free_mem_region
```
**Symbols:**

```
ffffffff810a2b90-ffffffff810a2c6d: __request_free_mem_region.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/resource.c (ffffffff81091570)
Location: kernel/resource.c:1647
Inline: True
Direct callers:
  - kernel/resource.c:request_free_mem_region
  - kernel/resource.c:devm_request_free_mem_region
```
**Symbols:**

```
ffffffff81091570-ffffffff8109164d: __request_free_mem_region.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/resource.c (ffffffff810a2b40)
Location: kernel/resource.c:1647
Inline: True
Direct callers:
  - kernel/resource.c:request_free_mem_region
  - kernel/resource.c:devm_request_free_mem_region
```
**Symbols:**

```
ffffffff810a2b40-ffffffff810a2c1d: __request_free_mem_region.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/resource.c (ffffffff810aabc0)
Location: kernel/resource.c:1647
Inline: True
Direct callers:
  - kernel/resource.c:request_free_mem_region
  - kernel/resource.c:devm_request_free_mem_region
```
**Symbols:**

```
ffffffff810aabc0-ffffffff810aac9d: __request_free_mem_region.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
