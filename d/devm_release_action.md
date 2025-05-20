# Function: <code>devm_release_action</code>

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
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void devm_release_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/devres.c (ffffffff816e098a)
Location: drivers/base/devres.c:771
Inline: True
Direct callers:
  - mm/memremap.c:devm_memunmap_pages
```
**Symbols:**

```
ffffffff816e098a-ffffffff816e099d: devm_release_action.cold (STB_LOCAL)
ffffffff816e07e0-ffffffff816e0839: devm_release_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void devm_release_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81704a90)
Location: drivers/base/devres.c:771
Inline: True
Direct callers:
  - mm/memremap.c:devm_memunmap_pages
```
**Symbols:**

```
ffffffff81704a90-ffffffff81704ae9: devm_release_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void devm_release_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817befc0)
Location: drivers/base/devres.c:771
Inline: True
Direct callers:
  - mm/memremap.c:devm_memunmap_pages
```
**Symbols:**

```
ffffffff817befc0-ffffffff817bf08e: devm_release_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void devm_release_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817d3c10)
Location: drivers/base/devres.c:787
Inline: True
Direct callers:
  - mm/memremap.c:devm_memunmap_pages
  - drivers/dax/bus.c:dev_dax_shrink
  - drivers/dax/bus.c:delete_store
```
**Symbols:**

```
ffffffff817d3c10-ffffffff817d3cde: devm_release_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void devm_release_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817b7620)
Location: drivers/base/devres.c:787
Inline: True
Direct callers:
  - mm/memremap.c:devm_memunmap_pages
  - drivers/dax/bus.c:dev_dax_shrink
  - drivers/dax/bus.c:delete_store
```
**Symbols:**

```
ffffffff817b7620-ffffffff817b76ee: devm_release_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devm_release_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81840f20)
Location: drivers/base/devres.c:776
Inline: False
Direct callers:
  - mm/memremap.c:devm_memunmap_pages
  - drivers/dax/bus.c:dev_dax_shrink
  - drivers/dax/bus.c:delete_store
```
**Symbols:**

```
ffffffff81840f20-ffffffff81840fa2: devm_release_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devm_release_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff819842b0)
Location: drivers/base/devres.c:776
Inline: False
Direct callers:
  - mm/memremap.c:devm_memunmap_pages
  - drivers/dax/bus.c:dev_dax_shrink
  - drivers/dax/bus.c:delete_store
```
**Symbols:**

```
ffffffff819842b0-ffffffff81984340: devm_release_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devm_release_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81af23e0)
Location: drivers/base/devres.c:781
Inline: False
Direct callers:
  - kernel/resource.c:get_free_mem_region
  - mm/memremap.c:devm_memunmap_pages
  - drivers/dax/bus.c:dev_dax_shrink
  - drivers/dax/bus.c:delete_store
```
**Symbols:**

```
ffffffff81af23e0-ffffffff81af2470: devm_release_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devm_release_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b40590)
Location: drivers/base/devres.c:782
Inline: False
Direct callers:
  - kernel/resource.c:get_free_mem_region
  - mm/memremap.c:devm_memunmap_pages
  - drivers/dax/bus.c:dev_dax_shrink
  - drivers/dax/bus.c:delete_store
```
**Symbols:**

```
ffffffff81b40590-ffffffff81b40620: devm_release_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devm_release_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b98430)
Location: drivers/base/devres.c:782
Inline: False
Direct callers:
  - kernel/resource.c:get_free_mem_region
  - mm/memremap.c:devm_memunmap_pages
  - drivers/dax/bus.c:dev_dax_shrink
  - drivers/dax/bus.c:delete_store
```
**Symbols:**

```
ffffffff81b98430-ffffffff81b984c0: devm_release_action (STB_GLOBAL)
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
void devm_release_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffff8000108f0918)
Location: drivers/base/devres.c:771
Inline: True
```
**Symbols:**

```
ffff8000108f0918-ffff8000108f09a0: devm_release_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void devm_release_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c09ddb8c)
Location: drivers/base/devres.c:771
Inline: True
```
**Symbols:**

```
c09ddb8c-c09ddc28: devm_release_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devm_release_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c000000000989d90)
Location: drivers/base/devres.c:771
Inline: False
Direct callers:
  - mm/memremap.c:devm_memunmap_pages
```
**Symbols:**

```
c000000000989d90-c000000000989e1c: devm_release_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void devm_release_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffe000582e68)
Location: drivers/base/devres.c:771
Inline: True
```
**Symbols:**

```
ffffffe000582e68-ffffffe000582ecc: devm_release_action (STB_GLOBAL)
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
void devm_release_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816ca1e0)
Location: drivers/base/devres.c:771
Inline: True
Direct callers:
  - mm/memremap.c:devm_memunmap_pages
```
**Symbols:**

```
ffffffff816ca1e0-ffffffff816ca239: devm_release_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void devm_release_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a5510)
Location: drivers/base/devres.c:771
Inline: True
Direct callers:
  - mm/memremap.c:devm_memunmap_pages
```
**Symbols:**

```
ffffffff816a5510-ffffffff816a5569: devm_release_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void devm_release_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816f8750)
Location: drivers/base/devres.c:771
Inline: True
Direct callers:
  - mm/memremap.c:devm_memunmap_pages
```
**Symbols:**

```
ffffffff816f8750-ffffffff816f87a9: devm_release_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void devm_release_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81712ff0)
Location: drivers/base/devres.c:771
Inline: True
Direct callers:
  - mm/memremap.c:devm_memunmap_pages
```
**Symbols:**

```
ffffffff81712ff0-ffffffff81713049: devm_release_action (STB_GLOBAL)
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
