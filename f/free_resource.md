# Function: <code>free_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void free_resource(struct resource *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810867b0)
Location: kernel/resource.c:173
Inline: True
Direct callers:
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
```
**Symbols:**

```
ffffffff810867b0-ffffffff81086843: free_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void free_resource(struct resource *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810897f0)
Location: kernel/resource.c:182
Inline: True
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff810897f0-ffffffff810898a0: free_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void free_resource(struct resource *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108e740)
Location: kernel/resource.c:182
Inline: True
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff8108e740-ffffffff8108e7e8: free_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void free_resource(struct resource *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8108b730)
Location: kernel/resource.c:182
Inline: True
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff8108b730-ffffffff8108b7dc: free_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void free_resource(struct resource *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810924b0)
Location: kernel/resource.c:182
Inline: True
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff810924b0-ffffffff8109255c: free_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void free_resource(struct resource *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81095ea0)
Location: kernel/resource.c:149
Inline: True
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff81095ea0-ffffffff81095f4b: free_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void free_resource(struct resource *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff8109e210)
Location: kernel/resource.c:149
Inline: True
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff8109e210-ffffffff8109e2bb: free_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void free_resource(struct resource *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2770)
Location: kernel/resource.c:150
Inline: True
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff810a2770-ffffffff810a2822: free_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void free_resource(struct resource *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a8d40)
Location: kernel/resource.c:150
Inline: True
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff810a8d40-ffffffff810a8df2: free_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void free_resource(struct resource *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810b0170)
Location: kernel/resource.c:150
Inline: True
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:__reserve_region_with_split
  - kernel/resource.c:__reserve_region_with_split
```
**Symbols:**

```
ffffffff810b0170-ffffffff810b0229: free_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void free_resource(struct resource *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810ab890)
Location: kernel/resource.c:150
Inline: True
Direct callers:
  - kernel/resource.c:merge_system_ram_resource
  - kernel/resource.c:merge_system_ram_resource
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:__reserve_region_with_split
  - kernel/resource.c:__reserve_region_with_split
```
**Symbols:**

```
ffffffff810ab890-ffffffff810ab949: free_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void free_resource(struct resource *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810acc10)
Location: kernel/resource.c:149
Inline: True
Direct callers:
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:merge_system_ram_resource
  - kernel/resource.c:merge_system_ram_resource
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff810acc10-ffffffff810accc9: free_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void free_resource(struct resource *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810be780)
Location: kernel/resource.c:149
Inline: True
Direct callers:
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:merge_system_ram_resource
  - kernel/resource.c:merge_system_ram_resource
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff810be780-ffffffff810be839: free_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/resource.c (ffffffff810d61d4)
Location: kernel/resource.c:153
Inline: True
Inline callers:
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:merge_system_ram_resource
  - kernel/resource.c:merge_system_ram_resource
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
Direct callers:
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:__request_free_mem_region
  - kernel/resource.c:merge_system_ram_resource
  - kernel/resource.c:merge_system_ram_resource
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff810d5cd0-ffffffff810d5db2: free_resource.part.0 (STB_LOCAL)
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
In kernel/resource.c (ffffffff810f58b2)
Location: kernel/resource.c:153
Inline: True
Inline callers:
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:merge_system_ram_resource
  - kernel/resource.c:merge_system_ram_resource
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
Direct callers:
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:merge_system_ram_resource
  - kernel/resource.c:merge_system_ram_resource
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff810f4f80-ffffffff810f505f: free_resource.part.0 (STB_LOCAL)
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
In kernel/resource.c (ffffffff81101d7a)
Location: kernel/resource.c:153
Inline: True
Inline callers:
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:merge_system_ram_resource
  - kernel/resource.c:merge_system_ram_resource
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
Direct callers:
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:merge_system_ram_resource
  - kernel/resource.c:merge_system_ram_resource
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff811013b0-ffffffff8110149d: free_resource.part.0 (STB_LOCAL)
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
In kernel/resource.c (ffffffff8110b4f9)
Location: kernel/resource.c:153
Inline: True
Inline callers:
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:merge_system_ram_resource
  - kernel/resource.c:merge_system_ram_resource
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
Direct callers:
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:get_free_mem_region
  - kernel/resource.c:merge_system_ram_resource
  - kernel/resource.c:merge_system_ram_resource
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff8110aae0-ffffffff8110abb8: free_resource.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void free_resource(struct resource *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffff800010100070)
Location: kernel/resource.c:150
Inline: True
Direct callers:
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffff800010100070-ffff800010100168: free_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void free_resource(struct resource *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c035cc3c)
Location: kernel/resource.c:150
Inline: True
Direct callers:
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
c035cc3c-c035ccdc: free_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void free_resource(struct resource *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (c000000000147c70)
Location: kernel/resource.c:150
Inline: True
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
c000000000147c70-c000000000147d9c: free_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void free_resource(struct resource *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffe0000c8006)
Location: kernel/resource.c:150
Inline: True
Direct callers:
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffe0000c8006-ffffffe0000c80da: free_resource (STB_LOCAL)
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
void free_resource(struct resource *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2660)
Location: kernel/resource.c:150
Inline: True
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff810a2660-ffffffff810a2712: free_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void free_resource(struct resource *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff81091040)
Location: kernel/resource.c:150
Inline: True
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff81091040-ffffffff810910f2: free_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void free_resource(struct resource *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810a2610)
Location: kernel/resource.c:150
Inline: True
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff810a2610-ffffffff810a26c2: free_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void free_resource(struct resource *res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/resource.c (ffffffff810aa650)
Location: kernel/resource.c:150
Inline: True
Direct callers:
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:release_mem_region_adjustable
  - kernel/resource.c:__release_region
  - kernel/resource.c:__request_region
  - kernel/resource.c:reserve_region_with_split
  - kernel/resource.c:reserve_region_with_split
```
**Symbols:**

```
ffffffff810aa650-ffffffff810aa700: free_resource (STB_LOCAL)
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
