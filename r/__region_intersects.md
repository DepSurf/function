# Function: <code>__region_intersects</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ac690)
Location: kernel/resource.c:505
Inline: False
Direct callers:
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:region_intersects
```
**Symbols:**

```
ffffffff810ac690-ffffffff810ac71a: __region_intersects (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810be210)
Location: kernel/resource.c:505
Inline: False
Direct callers:
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:region_intersects
```
**Symbols:**

```
ffffffff810be210-ffffffff810be29a: __region_intersects (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __region_intersects(resource_size_t start, size_t size, long unsigned int flags, long unsigned int desc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d5290)
Location: kernel/resource.c:492
Inline: False
Direct callers:
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:region_intersects
```
**Symbols:**

```
ffffffff810d5290-ffffffff810d534e: __region_intersects (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/resource.c (ffffffff810f4ad0)
Location: kernel/resource.c:492
Inline: True
Direct callers:
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:region_intersects
```
**Symbols:**

```
ffffffff810f4ad0-ffffffff810f4b8a: __region_intersects.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/resource.c (ffffffff81100f00)
Location: kernel/resource.c:492
Inline: True
Direct callers:
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:region_intersects
```
**Symbols:**

```
ffffffff81100f00-ffffffff81100fba: __region_intersects.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/resource.c (ffffffff8110a710)
Location: kernel/resource.c:547
Inline: True
Direct callers:
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:region_intersects
```
**Symbols:**

```
ffffffff8110a710-ffffffff8110a7ca: __region_intersects.isra.0 (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
