# Function: <code>xenbus_map_ring_valloc_hvm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xenbus_map_ring_valloc_hvm(struct xenbus_device *dev, grant_ref_t *gnt_ref, unsigned int nr_grefs, void **vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff814cc090)
Location: drivers/xen/xenbus/xenbus_client.c:622
Inline: False
```
**Symbols:**

```
ffffffff814cc090-ffffffff814cc2b2: xenbus_map_ring_valloc_hvm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xenbus_map_ring_valloc_hvm(struct xenbus_device *dev, grant_ref_t *gnt_ref, unsigned int nr_grefs, void **vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8151cc70)
Location: drivers/xen/xenbus/xenbus_client.c:622
Inline: False
```
**Symbols:**

```
ffffffff8151cc70-ffffffff8151ce93: xenbus_map_ring_valloc_hvm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xenbus_map_ring_valloc_hvm(struct xenbus_device *dev, grant_ref_t *gnt_ref, unsigned int nr_grefs, void **vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81549140)
Location: drivers/xen/xenbus/xenbus_client.c:622
Inline: False
```
**Symbols:**

```
ffffffff81549140-ffffffff81549363: xenbus_map_ring_valloc_hvm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xenbus_map_ring_valloc_hvm(struct xenbus_device *dev, grant_ref_t *gnt_ref, unsigned int nr_grefs, void **vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8155cec0)
Location: drivers/xen/xenbus/xenbus_client.c:603
Inline: False
```
**Symbols:**

```
ffffffff8155cec0-ffffffff8155d0e9: xenbus_map_ring_valloc_hvm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xenbus_map_ring_valloc_hvm(struct xenbus_device *dev, grant_ref_t *gnt_ref, unsigned int nr_grefs, void **vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815c11c0)
Location: drivers/xen/xenbus/xenbus_client.c:545
Inline: False
```
**Symbols:**

```
ffffffff815c11c0-ffffffff815c13f0: xenbus_map_ring_valloc_hvm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int xenbus_map_ring_valloc_hvm(struct xenbus_device *dev, grant_ref_t *gnt_ref, unsigned int nr_grefs, void **vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: drivers/xen/xenbus/xenbus_client.c:545
Inline: False
```
**Symbols:**

```
ffffffff815f94c0-ffffffff815f96df: xenbus_map_ring_valloc_hvm (STB_LOCAL)
ffffffff815fa07f-ffffffff815fa09a: xenbus_map_ring_valloc_hvm.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int xenbus_map_ring_valloc_hvm(struct xenbus_device *dev, grant_ref_t *gnt_ref, unsigned int nr_grefs, void **vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: drivers/xen/xenbus/xenbus_client.c:543
Inline: False
```
**Symbols:**

```
ffffffff81614570-ffffffff81614797: xenbus_map_ring_valloc_hvm (STB_LOCAL)
ffffffff81615132-ffffffff8161514d: xenbus_map_ring_valloc_hvm.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xenbus_map_ring_valloc_hvm(struct xenbus_device *dev, grant_ref_t *gnt_ref, unsigned int nr_grefs, void **vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: drivers/xen/xenbus/xenbus_client.c:543
Inline: False
```
**Symbols:**

```
ffffffff81648260-ffffffff8164847c: xenbus_map_ring_valloc_hvm (STB_LOCAL)
ffffffff81648e0d-ffffffff81648e29: xenbus_map_ring_valloc_hvm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xenbus_map_ring_valloc_hvm(struct xenbus_device *dev, grant_ref_t *gnt_ref, unsigned int nr_grefs, void **vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: drivers/xen/xenbus/xenbus_client.c:543
Inline: False
```
**Symbols:**

```
ffffffff8166a700-ffffffff8166a91c: xenbus_map_ring_valloc_hvm (STB_LOCAL)
ffffffff8166b2ad-ffffffff8166b2c9: xenbus_map_ring_valloc_hvm.cold (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int xenbus_map_ring_valloc_hvm(struct xenbus_device *dev, grant_ref_t *gnt_ref, unsigned int nr_grefs, void **vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffff8000108352e8)
Location: drivers/xen/xenbus/xenbus_client.c:543
Inline: False
```
**Symbols:**

```
ffff8000108352e8-ffff8000108355a8: xenbus_map_ring_valloc_hvm (STB_LOCAL)
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
int xenbus_map_ring_valloc_hvm(struct xenbus_device *dev, grant_ref_t *gnt_ref, unsigned int nr_grefs, void **vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: drivers/xen/xenbus/xenbus_client.c:543
Inline: False
```
**Symbols:**

```
ffffffff81630570-ffffffff8163078c: xenbus_map_ring_valloc_hvm (STB_LOCAL)
ffffffff8163111d-ffffffff81631139: xenbus_map_ring_valloc_hvm.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int xenbus_map_ring_valloc_hvm(struct xenbus_device *dev, grant_ref_t *gnt_ref, unsigned int nr_grefs, void **vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: drivers/xen/xenbus/xenbus_client.c:543
Inline: False
```
**Symbols:**

```
ffffffff8165e540-ffffffff8165e75c: xenbus_map_ring_valloc_hvm (STB_LOCAL)
ffffffff8165f0ed-ffffffff8165f109: xenbus_map_ring_valloc_hvm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xenbus_map_ring_valloc_hvm(struct xenbus_device *dev, grant_ref_t *gnt_ref, unsigned int nr_grefs, void **vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: drivers/xen/xenbus/xenbus_client.c:543
Inline: False
```
**Symbols:**

```
ffffffff81678ea0-ffffffff816790ba: xenbus_map_ring_valloc_hvm (STB_LOCAL)
ffffffff81679734-ffffffff81679750: xenbus_map_ring_valloc_hvm.cold (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
