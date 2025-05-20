# Function: <code>release_mem_region_adjustable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int release_mem_region_adjustable(struct resource *parent, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81087780)
Location: kernel/resource.c:1180
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff81087780-ffffffff81087925: release_mem_region_adjustable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int release_mem_region_adjustable(struct resource *parent, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108a670)
Location: kernel/resource.c:1248
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff8108a670-ffffffff8108a821: release_mem_region_adjustable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int release_mem_region_adjustable(struct resource *parent, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108f5c0)
Location: kernel/resource.c:1248
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff8108f5c0-ffffffff8108f771: release_mem_region_adjustable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int release_mem_region_adjustable(struct resource *parent, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108c570)
Location: kernel/resource.c:1248
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff8108c570-ffffffff8108c719: release_mem_region_adjustable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int release_mem_region_adjustable(struct resource *parent, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810932b0)
Location: kernel/resource.c:1266
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff810932b0-ffffffff81093459: release_mem_region_adjustable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int release_mem_region_adjustable(struct resource *parent, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81096ce0)
Location: kernel/resource.c:1236
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff81096ce0-ffffffff81096e8c: release_mem_region_adjustable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int release_mem_region_adjustable(struct resource *parent, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109f000)
Location: kernel/resource.c:1230
Inline: False
Direct callers:
  - mm/memory_hotplug.c:__remove_pages
```
**Symbols:**

```
ffffffff8109f000-ffffffff8109f1b7: release_mem_region_adjustable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int release_mem_region_adjustable(struct resource *parent, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a3620)
Location: kernel/resource.c:1253
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
```
**Symbols:**

```
ffffffff810a3620-ffffffff810a37eb: release_mem_region_adjustable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int release_mem_region_adjustable(struct resource *parent, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a9c50)
Location: kernel/resource.c:1253
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
```
**Symbols:**

```
ffffffff810a9c50-ffffffff810a9e1b: release_mem_region_adjustable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int release_mem_region_adjustable(struct resource *parent, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810b17f0)
Location: kernel/resource.c:1258
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
```
**Symbols:**

```
ffffffff810b17f0-ffffffff810b19bb: release_mem_region_adjustable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void release_mem_region_adjustable(resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810acf50)
Location: kernel/resource.c:1264
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
```
**Symbols:**

```
ffffffff810acf50-ffffffff810ad123: release_mem_region_adjustable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void release_mem_region_adjustable(resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ae150)
Location: kernel/resource.c:1317
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
```
**Symbols:**

```
ffffffff810ae150-ffffffff810ae323: release_mem_region_adjustable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void release_mem_region_adjustable(resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810bfcd0)
Location: kernel/resource.c:1317
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
```
**Symbols:**

```
ffffffff810bfcd0-ffffffff810bfea3: release_mem_region_adjustable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void release_mem_region_adjustable(resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810d71b0)
Location: kernel/resource.c:1304
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
```
**Symbols:**

```
ffffffff810d71b0-ffffffff810d73f4: release_mem_region_adjustable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void release_mem_region_adjustable(resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810f6bf0)
Location: kernel/resource.c:1310
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
```
**Symbols:**

```
ffffffff810f6bf0-ffffffff810f6e27: release_mem_region_adjustable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void release_mem_region_adjustable(resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81103000)
Location: kernel/resource.c:1310
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
```
**Symbols:**

```
ffffffff81103000-ffffffff81103237: release_mem_region_adjustable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void release_mem_region_adjustable(resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8110c930)
Location: kernel/resource.c:1365
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
```
**Symbols:**

```
ffffffff8110c930-ffffffff8110cb99: release_mem_region_adjustable (STB_GLOBAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int release_mem_region_adjustable(struct resource *parent, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c0000000001494a0)
Location: kernel/resource.c:1253
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
```
**Symbols:**

```
c0000000001494a0-c0000000001496e4: release_mem_region_adjustable (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int release_mem_region_adjustable(struct resource *parent, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a3570)
Location: kernel/resource.c:1253
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
```
**Symbols:**

```
ffffffff810a3570-ffffffff810a373b: release_mem_region_adjustable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int release_mem_region_adjustable(struct resource *parent, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81091f50)
Location: kernel/resource.c:1253
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
```
**Symbols:**

```
ffffffff81091f50-ffffffff8109211b: release_mem_region_adjustable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int release_mem_region_adjustable(struct resource *parent, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a3520)
Location: kernel/resource.c:1253
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
```
**Symbols:**

```
ffffffff810a3520-ffffffff810a36eb: release_mem_region_adjustable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int release_mem_region_adjustable(struct resource *parent, resource_size_t start, resource_size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ab5d0)
Location: kernel/resource.c:1253
Inline: False
Direct callers:
  - mm/memory_hotplug.c:try_remove_memory
```
**Symbols:**

```
ffffffff810ab5d0-ffffffff810ab7a0: release_mem_region_adjustable (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct resource *parent</code>
</li>
<li>
<b>Param reordered. </b>
<code>parent, start, size</code> ➡️ <code>start, size</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
