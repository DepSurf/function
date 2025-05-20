# Function: <code>fwnode_get_mac_addr</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *fwnode_get_mac_addr(struct fwnode_handle *fwnode, const char *name, char *addr, int alen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81688c10)
Location: drivers/base/property.c:1256
Inline: False
```
**Symbols:**

```
ffffffff81688c10-ffffffff81688c5b: fwnode_get_mac_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *fwnode_get_mac_addr(struct fwnode_handle *fwnode, const char *name, char *addr, int alen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a8910)
Location: drivers/base/property.c:779
Inline: False
```
**Symbols:**

```
ffffffff816a8910-ffffffff816a895b: fwnode_get_mac_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *fwnode_get_mac_addr(struct fwnode_handle *fwnode, const char *name, char *addr, int alen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e1d00)
Location: drivers/base/property.c:803
Inline: False
```
**Symbols:**

```
ffffffff816e1d00-ffffffff816e1d4b: fwnode_get_mac_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *fwnode_get_mac_addr(struct fwnode_handle *fwnode, const char *name, char *addr, int alen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81705eb0)
Location: drivers/base/property.c:803
Inline: False
```
**Symbols:**

```
ffffffff81705eb0-ffffffff81705efb: fwnode_get_mac_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c0d35)
Location: drivers/base/property.c:882
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d5ae8)
Location: drivers/base/property.c:934
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b9508)
Location: drivers/base/property.c:940
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81843168)
Location: drivers/base/property.c:938
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81c939b5)
Location: net/ethernet/eth.c:577
Inline: True
Inline callers:
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81e4f0f5)
Location: net/ethernet/eth.c:574
Inline: True
Inline callers:
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81eaa795)
Location: net/ethernet/eth.c:574
Inline: True
Inline callers:
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81f6d245)
Location: net/ethernet/eth.c:574
Inline: True
Inline callers:
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
  - net/ethernet/eth.c:fwnode_get_mac_address
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
void *fwnode_get_mac_addr(struct fwnode_handle *fwnode, const char *name, char *addr, int alen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f2af0)
Location: drivers/base/property.c:803
Inline: False
```
**Symbols:**

```
ffff8000108f2af0-ffff8000108f2b6c: fwnode_get_mac_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *fwnode_get_mac_addr(struct fwnode_handle *fwnode, const char *name, char *addr, int alen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09df730)
Location: drivers/base/property.c:803
Inline: False
```
**Symbols:**

```
c09df730-c09df7a8: fwnode_get_mac_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void *fwnode_get_mac_addr(struct fwnode_handle *fwnode, const char *name, char *addr, int alen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098d610)
Location: drivers/base/property.c:803
Inline: True
```
**Symbols:**

```
c00000000098d610-c00000000098d6bc: fwnode_get_mac_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void *fwnode_get_mac_addr(struct fwnode_handle *fwnode, const char *name, char *addr, int alen);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe000584e90)
Location: drivers/base/property.c:803
Inline: True
```
**Symbols:**

```
ffffffe000584e90-ffffffe000584f0c: fwnode_get_mac_addr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *fwnode_get_mac_addr(struct fwnode_handle *fwnode, const char *name, char *addr, int alen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cb600)
Location: drivers/base/property.c:803
Inline: False
```
**Symbols:**

```
ffffffff816cb600-ffffffff816cb64b: fwnode_get_mac_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *fwnode_get_mac_addr(struct fwnode_handle *fwnode, const char *name, char *addr, int alen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a6930)
Location: drivers/base/property.c:803
Inline: False
```
**Symbols:**

```
ffffffff816a6930-ffffffff816a697b: fwnode_get_mac_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *fwnode_get_mac_addr(struct fwnode_handle *fwnode, const char *name, char *addr, int alen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816f9b70)
Location: drivers/base/property.c:803
Inline: False
```
**Symbols:**

```
ffffffff816f9b70-ffffffff816f9bbb: fwnode_get_mac_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *fwnode_get_mac_addr(struct fwnode_handle *fwnode, const char *name, char *addr, int alen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81714410)
Location: drivers/base/property.c:803
Inline: False
```
**Symbols:**

```
ffffffff81714410-ffffffff8171445b: fwnode_get_mac_addr (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
