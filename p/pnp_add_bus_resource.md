# Function: <code>pnp_add_bus_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_bus_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff814b95b0)
Location: drivers/pnp/resource.c:615
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff814b95b0-ffffffff814b965f: pnp_add_bus_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_bus_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff81509020)
Location: drivers/pnp/resource.c:615
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff81509020-ffffffff815090cf: pnp_add_bus_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_bus_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff8152d240)
Location: drivers/pnp/resource.c:615
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff8152d240-ffffffff8152d2ef: pnp_add_bus_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_bus_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff81540300)
Location: drivers/pnp/resource.c:615
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff81540300-ffffffff815403a6: pnp_add_bus_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_bus_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff815a3420)
Location: drivers/pnp/resource.c:616
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff815a3420-ffffffff815a34c6: pnp_add_bus_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_bus_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff815db090)
Location: drivers/pnp/resource.c:616
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff815db090-ffffffff815db136: pnp_add_bus_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_bus_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff815f4870)
Location: drivers/pnp/resource.c:616
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff815f4870-ffffffff815f48e3: pnp_add_bus_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_bus_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:616
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff81626715-ffffffff8162676e: pnp_add_bus_resource.cold (STB_LOCAL)
ffffffff81626560-ffffffff8162658e: pnp_add_bus_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_bus_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:616
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff81648205-ffffffff8164825e: pnp_add_bus_resource.cold (STB_LOCAL)
ffffffff81648050-ffffffff8164807e: pnp_add_bus_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_bus_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:616
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff816f70f8-ffffffff816f7170: pnp_add_bus_resource.cold (STB_LOCAL)
ffffffff816f6eb0-ffffffff816f6eef: pnp_add_bus_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_bus_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:616
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff81c03c2c-ffffffff81c03ca4: pnp_add_bus_resource.cold (STB_LOCAL)
ffffffff81713ef0-ffffffff81713f2f: pnp_add_bus_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_bus_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:616
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff81bf55bf-ffffffff81bf5637: pnp_add_bus_resource.cold (STB_LOCAL)
ffffffff816f52a0-ffffffff816f52df: pnp_add_bus_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_bus_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:616
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff81cf2b1d-ffffffff81cf2b95: pnp_add_bus_resource.cold (STB_LOCAL)
ffffffff8176f860-ffffffff8176f89f: pnp_add_bus_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_bus_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:616
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff81ebac77-ffffffff81ebacfb: pnp_add_bus_resource.cold (STB_LOCAL)
ffffffff818a4c50-ffffffff818a4c8f: pnp_add_bus_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_bus_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff819ee950)
Location: drivers/pnp/resource.c:617
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff819ee950-ffffffff819eea02: pnp_add_bus_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_bus_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff81a37110)
Location: drivers/pnp/resource.c:617
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff81a37110-ffffffff81a371d8: pnp_add_bus_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_bus_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff81a828a0)
Location: drivers/pnp/resource.c:617
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff81a828a0-ffffffff81a82997: pnp_add_bus_resource (STB_GLOBAL)
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
struct pnp_resource *pnp_add_bus_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffff8000107b5508)
Location: drivers/pnp/resource.c:616
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffff8000107b5508-ffff8000107b5598: pnp_add_bus_resource (STB_GLOBAL)
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
struct pnp_resource *pnp_add_bus_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:616
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff8160e265-ffffffff8160e2be: pnp_add_bus_resource.cold (STB_LOCAL)
ffffffff8160e0b0-ffffffff8160e0de: pnp_add_bus_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_bus_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:616
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff816027b5-ffffffff8160280e: pnp_add_bus_resource.cold (STB_LOCAL)
ffffffff81602600-ffffffff8160262e: pnp_add_bus_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_bus_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:616
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff8163c045-ffffffff8163c09e: pnp_add_bus_resource.cold (STB_LOCAL)
ffffffff8163be90-ffffffff8163bebe: pnp_add_bus_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_bus_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:616
Inline: False
Direct callers:
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff81656395-ffffffff816563ee: pnp_add_bus_resource.cold (STB_LOCAL)
ffffffff816561e0-ffffffff8165620e: pnp_add_bus_resource (STB_GLOBAL)
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
