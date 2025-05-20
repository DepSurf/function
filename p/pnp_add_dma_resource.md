# Function: <code>pnp_add_dma_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_dma_resource(struct pnp_dev *dev, int dma, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff814b9380)
Location: drivers/pnp/resource.c:546
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff814b9380-ffffffff814b942f: pnp_add_dma_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_dma_resource(struct pnp_dev *dev, int dma, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff81508df0)
Location: drivers/pnp/resource.c:546
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff81508df0-ffffffff81508e9f: pnp_add_dma_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_dma_resource(struct pnp_dev *dev, int dma, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff8152d010)
Location: drivers/pnp/resource.c:546
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff8152d010-ffffffff8152d0bf: pnp_add_dma_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_dma_resource(struct pnp_dev *dev, int dma, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff815400f0)
Location: drivers/pnp/resource.c:546
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff815400f0-ffffffff81540196: pnp_add_dma_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_dma_resource(struct pnp_dev *dev, int dma, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff815a3210)
Location: drivers/pnp/resource.c:547
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff815a3210-ffffffff815a32b6: pnp_add_dma_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_dma_resource(struct pnp_dev *dev, int dma, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff815dae80)
Location: drivers/pnp/resource.c:547
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff815dae80-ffffffff815daf26: pnp_add_dma_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_dma_resource(struct pnp_dev *dev, int dma, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff815f46f0)
Location: drivers/pnp/resource.c:547
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff815f46f0-ffffffff815f4769: pnp_add_dma_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_dma_resource(struct pnp_dev *dev, int dma, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:547
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff81626600-ffffffff8162665b: pnp_add_dma_resource.cold (STB_LOCAL)
ffffffff816264b0-ffffffff816264de: pnp_add_dma_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_dma_resource(struct pnp_dev *dev, int dma, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:547
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff816480f0-ffffffff8164814b: pnp_add_dma_resource.cold (STB_LOCAL)
ffffffff81647fa0-ffffffff81647fce: pnp_add_dma_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_dma_resource(struct pnp_dev *dev, int dma, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:547
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_dma
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff816f6f80-ffffffff816f6ffa: pnp_add_dma_resource.cold (STB_LOCAL)
ffffffff816f6dd0-ffffffff816f6e0f: pnp_add_dma_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_dma_resource(struct pnp_dev *dev, int dma, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:547
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_dma
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff81c03ab4-ffffffff81c03b2e: pnp_add_dma_resource.cold (STB_LOCAL)
ffffffff81713e10-ffffffff81713e4f: pnp_add_dma_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_dma_resource(struct pnp_dev *dev, int dma, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:547
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff81bf5447-ffffffff81bf54c1: pnp_add_dma_resource.cold (STB_LOCAL)
ffffffff816f51c0-ffffffff816f51ff: pnp_add_dma_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_dma_resource(struct pnp_dev *dev, int dma, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:547
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff81cf29a5-ffffffff81cf2a1f: pnp_add_dma_resource.cold (STB_LOCAL)
ffffffff8176f780-ffffffff8176f7bf: pnp_add_dma_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_dma_resource(struct pnp_dev *dev, int dma, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:547
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff81ebaadb-ffffffff81ebab61: pnp_add_dma_resource.cold (STB_LOCAL)
ffffffff818a4b70-ffffffff818a4baf: pnp_add_dma_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_dma_resource(struct pnp_dev *dev, int dma, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff819ee6e0)
Location: drivers/pnp/resource.c:548
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff819ee6e0-ffffffff819ee792: pnp_add_dma_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_dma_resource(struct pnp_dev *dev, int dma, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff81a36e50)
Location: drivers/pnp/resource.c:548
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff81a36e50-ffffffff81a36f18: pnp_add_dma_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_dma_resource(struct pnp_dev *dev, int dma, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff81a82550)
Location: drivers/pnp/resource.c:548
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff81a82550-ffffffff81a82647: pnp_add_dma_resource (STB_GLOBAL)
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
struct pnp_resource *pnp_add_dma_resource(struct pnp_dev *dev, int dma, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffff8000107b5338)
Location: drivers/pnp/resource.c:547
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffff8000107b5338-ffff8000107b53c8: pnp_add_dma_resource (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_dma_resource(struct pnp_dev *dev, int dma, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:547
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff8160e150-ffffffff8160e1ab: pnp_add_dma_resource.cold (STB_LOCAL)
ffffffff8160e000-ffffffff8160e02e: pnp_add_dma_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_dma_resource(struct pnp_dev *dev, int dma, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:547
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff816026a0-ffffffff816026fb: pnp_add_dma_resource.cold (STB_LOCAL)
ffffffff81602550-ffffffff8160257e: pnp_add_dma_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_dma_resource(struct pnp_dev *dev, int dma, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:547
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff8163bf30-ffffffff8163bf8b: pnp_add_dma_resource.cold (STB_LOCAL)
ffffffff8163bde0-ffffffff8163be0e: pnp_add_dma_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_dma_resource(struct pnp_dev *dev, int dma, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:547
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
  - drivers/pnp/pnpacpi/rsparser.c:pnpacpi_allocated_resource
```
**Symbols:**

```
ffffffff81656280-ffffffff816562db: pnp_add_dma_resource.cold (STB_LOCAL)
ffffffff81656130-ffffffff8165615e: pnp_add_dma_resource (STB_GLOBAL)
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
