# Function: <code>get_free_mem_region</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct resource *get_free_mem_region(struct device *dev, struct resource *base, resource_size_t size, const long unsigned int align, const char *name, const long unsigned int desc, const long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f57c0)
Location: kernel/resource.c:1821
Inline: False
Direct callers:
  - kernel/resource.c:alloc_free_mem_region
  - kernel/resource.c:request_free_mem_region
  - kernel/resource.c:devm_request_free_mem_region
```
**Symbols:**

```
ffffffff810f57c0-ffffffff810f5b07: get_free_mem_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct resource *get_free_mem_region(struct device *dev, struct resource *base, resource_size_t size, const long unsigned int align, const char *name, const long unsigned int desc, const long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81101c00)
Location: kernel/resource.c:1821
Inline: False
Direct callers:
  - kernel/resource.c:alloc_free_mem_region
  - kernel/resource.c:request_free_mem_region
  - kernel/resource.c:devm_request_free_mem_region
```
**Symbols:**

```
ffffffff81101c00-ffffffff81101f52: get_free_mem_region (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct resource *get_free_mem_region(struct device *dev, struct resource *base, resource_size_t size, const long unsigned int align, const char *name, const long unsigned int desc, const long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110b350)
Location: kernel/resource.c:1875
Inline: False
Direct callers:
  - kernel/resource.c:alloc_free_mem_region
  - kernel/resource.c:request_free_mem_region
  - kernel/resource.c:devm_request_free_mem_region
```
**Symbols:**

```
ffffffff8110b350-ffffffff8110b6e1: get_free_mem_region (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
