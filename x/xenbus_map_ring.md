# Function: <code>xenbus_map_ring</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int xenbus_map_ring(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, grant_handle_t *handles, long unsigned int *vaddrs, bool *leaked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff814cc000)
Location: drivers/xen/xenbus/xenbus_client.c:710
Inline: False
```
**Symbols:**

```
ffffffff814cc000-ffffffff814cc08e: xenbus_map_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int xenbus_map_ring(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, grant_handle_t *handles, long unsigned int *vaddrs, bool *leaked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8151cbe0)
Location: drivers/xen/xenbus/xenbus_client.c:710
Inline: False
```
**Symbols:**

```
ffffffff8151cbe0-ffffffff8151cc6e: xenbus_map_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int xenbus_map_ring(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, grant_handle_t *handles, long unsigned int *vaddrs, bool *leaked);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815490b0)
Location: drivers/xen/xenbus/xenbus_client.c:710
Inline: False
```
**Symbols:**

```
ffffffff815490b0-ffffffff8154913e: xenbus_map_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_map_ring(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, grant_handle_t *handles, long unsigned int *vaddrs, bool *leaked);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8155ce20)
Location: drivers/xen/xenbus/xenbus_client.c:691
Inline: True
```
**Symbols:**

```
ffffffff8155ce20-ffffffff8155ce9c: xenbus_map_ring.part.6 (STB_LOCAL)
ffffffff8155cea0-ffffffff8155cebb: xenbus_map_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_map_ring(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, grant_handle_t *handles, long unsigned int *vaddrs, bool *leaked);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815c1120)
Location: drivers/xen/xenbus/xenbus_client.c:633
Inline: True
```
**Symbols:**

```
ffffffff815c1120-ffffffff815c119c: xenbus_map_ring.part.6 (STB_LOCAL)
ffffffff815c11a0-ffffffff815c11bb: xenbus_map_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_map_ring(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, grant_handle_t *handles, long unsigned int *vaddrs, bool *leaked);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff815f93e0)
Location: drivers/xen/xenbus/xenbus_client.c:633
Inline: True
```
**Symbols:**

```
ffffffff815f93e0-ffffffff815f9459: xenbus_map_ring.part.7 (STB_LOCAL)
ffffffff815f9460-ffffffff815f947b: xenbus_map_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_map_ring(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, grant_handle_t *handles, long unsigned int *vaddrs, bool *leaked);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81614490)
Location: drivers/xen/xenbus/xenbus_client.c:631
Inline: True
```
**Symbols:**

```
ffffffff81614490-ffffffff81614509: xenbus_map_ring.part.7 (STB_LOCAL)
ffffffff81614510-ffffffff8161452b: xenbus_map_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_map_ring(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, grant_handle_t *handles, long unsigned int *vaddrs, bool *leaked);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81648180)
Location: drivers/xen/xenbus/xenbus_client.c:631
Inline: True
```
**Symbols:**

```
ffffffff81648180-ffffffff816481f7: xenbus_map_ring.part.0 (STB_LOCAL)
ffffffff81648200-ffffffff8164821b: xenbus_map_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_map_ring(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, grant_handle_t *handles, long unsigned int *vaddrs, bool *leaked);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8166a620)
Location: drivers/xen/xenbus/xenbus_client.c:631
Inline: True
```
**Symbols:**

```
ffffffff8166a620-ffffffff8166a697: xenbus_map_ring.part.0 (STB_LOCAL)
ffffffff8166a6a0-ffffffff8166a6bb: xenbus_map_ring (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_map_ring(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, grant_handle_t *handles, long unsigned int *vaddrs, bool *leaked);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffff800010835158)
Location: drivers/xen/xenbus/xenbus_client.c:631
Inline: True
```
**Symbols:**

```
ffff800010835158-ffff800010835220: xenbus_map_ring.part.0 (STB_LOCAL)
ffff800010835220-ffff800010835294: xenbus_map_ring (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_map_ring(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, grant_handle_t *handles, long unsigned int *vaddrs, bool *leaked);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81630490)
Location: drivers/xen/xenbus/xenbus_client.c:631
Inline: True
```
**Symbols:**

```
ffffffff81630490-ffffffff81630507: xenbus_map_ring.part.0 (STB_LOCAL)
ffffffff81630510-ffffffff8163052b: xenbus_map_ring (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_map_ring(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, grant_handle_t *handles, long unsigned int *vaddrs, bool *leaked);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff8165e460)
Location: drivers/xen/xenbus/xenbus_client.c:631
Inline: True
```
**Symbols:**

```
ffffffff8165e460-ffffffff8165e4d7: xenbus_map_ring.part.0 (STB_LOCAL)
ffffffff8165e4e0-ffffffff8165e4fb: xenbus_map_ring (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int xenbus_map_ring(struct xenbus_device *dev, grant_ref_t *gnt_refs, unsigned int nr_grefs, grant_handle_t *handles, long unsigned int *vaddrs, bool *leaked);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81678dc0)
Location: drivers/xen/xenbus/xenbus_client.c:631
Inline: True
```
**Symbols:**

```
ffffffff81678dc0-ffffffff81678e37: xenbus_map_ring.part.0 (STB_LOCAL)
ffffffff81678e40-ffffffff81678e5b: xenbus_map_ring (STB_GLOBAL)
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
