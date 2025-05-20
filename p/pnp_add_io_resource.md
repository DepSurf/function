# Function: <code>pnp_add_io_resource</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_io_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff814b9430)
Location: drivers/pnp/resource.c:567
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff814b9430-ffffffff814b94eb: pnp_add_io_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_io_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff81508ea0)
Location: drivers/pnp/resource.c:567
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff81508ea0-ffffffff81508f5b: pnp_add_io_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_io_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff8152d0c0)
Location: drivers/pnp/resource.c:567
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff8152d0c0-ffffffff8152d17b: pnp_add_io_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_io_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff815401a0)
Location: drivers/pnp/resource.c:567
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff815401a0-ffffffff81540250: pnp_add_io_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_io_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff815a32c0)
Location: drivers/pnp/resource.c:568
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff815a32c0-ffffffff815a3370: pnp_add_io_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_io_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff815daf30)
Location: drivers/pnp/resource.c:568
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff815daf30-ffffffff815dafe0: pnp_add_io_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_io_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff815f4770)
Location: drivers/pnp/resource.c:568
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff815f4770-ffffffff815f47f0: pnp_add_io_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_io_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:568
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff8162665b-ffffffff816266b8: pnp_add_io_resource.cold (STB_LOCAL)
ffffffff816264e0-ffffffff81626512: pnp_add_io_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_io_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:568
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff8164814b-ffffffff816481a8: pnp_add_io_resource.cold (STB_LOCAL)
ffffffff81647fd0-ffffffff81648002: pnp_add_io_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_io_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:568
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_port
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff816f6ffa-ffffffff816f7079: pnp_add_io_resource.cold (STB_LOCAL)
ffffffff816f6e10-ffffffff816f6e54: pnp_add_io_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_io_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:568
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_port
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff81c03b2e-ffffffff81c03bad: pnp_add_io_resource.cold (STB_LOCAL)
ffffffff81713e50-ffffffff81713e94: pnp_add_io_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_io_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:568
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff81bf54c1-ffffffff81bf5540: pnp_add_io_resource.cold (STB_LOCAL)
ffffffff816f5200-ffffffff816f5244: pnp_add_io_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_io_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:568
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff81cf2a1f-ffffffff81cf2a9e: pnp_add_io_resource.cold (STB_LOCAL)
ffffffff8176f7c0-ffffffff8176f804: pnp_add_io_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_io_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:568
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff81ebab61-ffffffff81ebabec: pnp_add_io_resource.cold (STB_LOCAL)
ffffffff818a4bb0-ffffffff818a4bf4: pnp_add_io_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_io_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff819ee7b0)
Location: drivers/pnp/resource.c:569
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff819ee7b0-ffffffff819ee86c: pnp_add_io_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_io_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff81a36f30)
Location: drivers/pnp/resource.c:569
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff81a36f30-ffffffff81a37004: pnp_add_io_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pnp_resource *pnp_add_io_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffffffff81a82660)
Location: drivers/pnp/resource.c:569
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff81a82660-ffffffff81a82763: pnp_add_io_resource (STB_GLOBAL)
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
struct pnp_resource *pnp_add_io_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pnp/resource.c (ffff8000107b53c8)
Location: drivers/pnp/resource.c:568
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffff8000107b53c8-ffff8000107b5468: pnp_add_io_resource (STB_GLOBAL)
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
struct pnp_resource *pnp_add_io_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:568
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff8160e1ab-ffffffff8160e208: pnp_add_io_resource.cold (STB_LOCAL)
ffffffff8160e030-ffffffff8160e062: pnp_add_io_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_io_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:568
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff816026fb-ffffffff81602758: pnp_add_io_resource.cold (STB_LOCAL)
ffffffff81602580-ffffffff816025b2: pnp_add_io_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_io_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:568
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff8163bf8b-ffffffff8163bfe8: pnp_add_io_resource.cold (STB_LOCAL)
ffffffff8163be10-ffffffff8163be42: pnp_add_io_resource (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct pnp_resource *pnp_add_io_resource(struct pnp_dev *dev, resource_size_t start, resource_size_t end, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pnp/resource.c (0)
Location: drivers/pnp/resource.c:568
Inline: False
Direct callers:
  - drivers/pnp/manager.c:pnp_assign_resources
  - drivers/pnp/interface.c:resources_store
```
**Symbols:**

```
ffffffff816562db-ffffffff81656338: pnp_add_io_resource.cold (STB_LOCAL)
ffffffff81656160-ffffffff81656192: pnp_add_io_resource (STB_GLOBAL)
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
