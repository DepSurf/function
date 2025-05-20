# Function: <code>xenbus_map_ring_valloc_pv</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xenbus_map_ring_valloc_pv(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, void **vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff814cc780)
Location: drivers/xen/xenbus/xenbus_client.c:541
Inline: False
```
**Symbols:**

```
ffffffff814cc780-ffffffff814cc976: xenbus_map_ring_valloc_pv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xenbus_map_ring_valloc_pv(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, void **vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8151d2f0)
Location: drivers/xen/xenbus/xenbus_client.c:541
Inline: False
```
**Symbols:**

```
ffffffff8151d2f0-ffffffff8151d4e4: xenbus_map_ring_valloc_pv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xenbus_map_ring_valloc_pv(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, void **vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815494f0)
Location: drivers/xen/xenbus/xenbus_client.c:541
Inline: False
```
**Symbols:**

```
ffffffff815494f0-ffffffff815496e4: xenbus_map_ring_valloc_pv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int xenbus_map_ring_valloc_pv(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, void **vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8155d130)
Location: drivers/xen/xenbus/xenbus_client.c:522
Inline: False
```
**Symbols:**

```
ffffffff8155d130-ffffffff8155d31b: xenbus_map_ring_valloc_pv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int xenbus_map_ring_valloc_pv(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, void **vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815c1430)
Location: drivers/xen/xenbus/xenbus_client.c:671
Inline: False
```
**Symbols:**

```
ffffffff815c1430-ffffffff815c161b: xenbus_map_ring_valloc_pv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int xenbus_map_ring_valloc_pv(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, void **vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: drivers/xen/xenbus/xenbus_client.c:671
Inline: False
```
**Symbols:**

```
ffffffff815f9c60-ffffffff815f9e33: xenbus_map_ring_valloc_pv (STB_LOCAL)
ffffffff815fa09a-ffffffff815fa0b5: xenbus_map_ring_valloc_pv.cold.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int xenbus_map_ring_valloc_pv(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, void **vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: drivers/xen/xenbus/xenbus_client.c:669
Inline: False
```
**Symbols:**

```
ffffffff81614f60-ffffffff81615132: xenbus_map_ring_valloc_pv (STB_LOCAL)
ffffffff8161514d-ffffffff81615168: xenbus_map_ring_valloc_pv.cold.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int xenbus_map_ring_valloc_pv(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, void **vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: drivers/xen/xenbus/xenbus_client.c:669
Inline: False
```
**Symbols:**

```
ffffffff81648bb0-ffffffff81648d86: xenbus_map_ring_valloc_pv (STB_LOCAL)
ffffffff81648e72-ffffffff81648e8d: xenbus_map_ring_valloc_pv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int xenbus_map_ring_valloc_pv(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, void **vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: drivers/xen/xenbus/xenbus_client.c:669
Inline: False
```
**Symbols:**

```
ffffffff8166b050-ffffffff8166b226: xenbus_map_ring_valloc_pv (STB_LOCAL)
ffffffff8166b312-ffffffff8166b32d: xenbus_map_ring_valloc_pv.cold (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int xenbus_map_ring_valloc_pv(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, void **vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: drivers/xen/xenbus/xenbus_client.c:669
Inline: False
```
**Symbols:**

```
ffffffff81630ec0-ffffffff81631096: xenbus_map_ring_valloc_pv (STB_LOCAL)
ffffffff81631182-ffffffff8163119d: xenbus_map_ring_valloc_pv.cold (STB_LOCAL)
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
int xenbus_map_ring_valloc_pv(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, void **vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: drivers/xen/xenbus/xenbus_client.c:669
Inline: False
```
**Symbols:**

```
ffffffff8165ee90-ffffffff8165f066: xenbus_map_ring_valloc_pv (STB_LOCAL)
ffffffff8165f152-ffffffff8165f16d: xenbus_map_ring_valloc_pv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int xenbus_map_ring_valloc_pv(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, void **vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: drivers/xen/xenbus/xenbus_client.c:669
Inline: False
```
**Symbols:**

```
ffffffff816790c0-ffffffff81679294: xenbus_map_ring_valloc_pv (STB_LOCAL)
ffffffff81679750-ffffffff8167976b: xenbus_map_ring_valloc_pv.cold (STB_LOCAL)
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
