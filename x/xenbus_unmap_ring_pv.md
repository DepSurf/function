# Function: <code>xenbus_unmap_ring_pv</code>

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
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int xenbus_unmap_ring_pv(struct xenbus_device *dev, void *vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: drivers/xen/xenbus/xenbus_client.c:736
Inline: False
```
**Symbols:**

```
ffffffff8171af40-ffffffff8171b102: xenbus_unmap_ring_pv (STB_LOCAL)
ffffffff8171b2fe-ffffffff8171b347: xenbus_unmap_ring_pv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int xenbus_unmap_ring_pv(struct xenbus_device *dev, void *vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: drivers/xen/xenbus/xenbus_client.c:744
Inline: False
```
**Symbols:**

```
ffffffff817380b0-ffffffff81738272: xenbus_unmap_ring_pv (STB_LOCAL)
ffffffff81c054a1-ffffffff81c054ea: xenbus_unmap_ring_pv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int xenbus_unmap_ring_pv(struct xenbus_device *dev, void *vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: drivers/xen/xenbus/xenbus_client.c:744
Inline: False
```
**Symbols:**

```
ffffffff8171bae0-ffffffff8171bca2: xenbus_unmap_ring_pv (STB_LOCAL)
ffffffff81bf7106-ffffffff81bf714f: xenbus_unmap_ring_pv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xenbus_unmap_ring_pv(struct xenbus_device *dev, void *vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: drivers/xen/xenbus/xenbus_client.c:740
Inline: False
```
**Symbols:**

```
ffffffff8179a710-ffffffff8179a9c2: xenbus_unmap_ring_pv (STB_LOCAL)
ffffffff81cf5f3c-ffffffff81cf5ff3: xenbus_unmap_ring_pv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xenbus_unmap_ring_pv(struct xenbus_device *dev, void *vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (0)
Location: drivers/xen/xenbus/xenbus_client.c:782
Inline: False
```
**Symbols:**

```
ffffffff818d2a90-ffffffff818d2db9: xenbus_unmap_ring_pv (STB_LOCAL)
ffffffff81ebdfa4-ffffffff81ebe04c: xenbus_unmap_ring_pv.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xenbus_unmap_ring_pv(struct xenbus_device *dev, void *vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a24af0)
Location: drivers/xen/xenbus/xenbus_client.c:785
Inline: False
```
**Symbols:**

```
ffffffff81a24af0-ffffffff81a24f06: xenbus_unmap_ring_pv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xenbus_unmap_ring_pv(struct xenbus_device *dev, void *vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81a6e030)
Location: drivers/xen/xenbus/xenbus_client.c:785
Inline: False
```
**Symbols:**

```
ffffffff81a6e030-ffffffff81a6e4bd: xenbus_unmap_ring_pv (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xenbus_unmap_ring_pv(struct xenbus_device *dev, void *vaddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_client.c (ffffffff81ac00d0)
Location: drivers/xen/xenbus/xenbus_client.c:797
Inline: False
```
**Symbols:**

```
ffffffff81ac00d0-ffffffff81ac055d: xenbus_unmap_ring_pv (STB_LOCAL)
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
