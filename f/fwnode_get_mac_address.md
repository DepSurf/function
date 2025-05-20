# Function: <code>fwnode_get_mac_address</code>

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
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void *fwnode_get_mac_address(struct fwnode_handle *fwnode, char *addr, int alen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81689780)
Location: drivers/base/property.c:1290
Inline: True
Direct callers:
  - drivers/base/property.c:device_get_mac_address
```
**Symbols:**

```
ffffffff81689780-ffffffff816897e5: fwnode_get_mac_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void *fwnode_get_mac_address(struct fwnode_handle *fwnode, char *addr, int alen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a9040)
Location: drivers/base/property.c:813
Inline: True
Direct callers:
  - drivers/base/property.c:device_get_mac_address
```
**Symbols:**

```
ffffffff816a9040-ffffffff816a90a5: fwnode_get_mac_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void *fwnode_get_mac_address(struct fwnode_handle *fwnode, char *addr, int alen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816e2610)
Location: drivers/base/property.c:837
Inline: True
Direct callers:
  - drivers/base/property.c:device_get_mac_address
```
**Symbols:**

```
ffffffff816e2610-ffffffff816e2677: fwnode_get_mac_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *fwnode_get_mac_address(struct fwnode_handle *fwnode, char *addr, int alen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817067c0)
Location: drivers/base/property.c:837
Inline: True
Direct callers:
  - drivers/base/property.c:device_get_mac_address
```
**Symbols:**

```
ffffffff817067c0-ffffffff81706827: fwnode_get_mac_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *fwnode_get_mac_address(struct fwnode_handle *fwnode, char *addr, int alen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817c0d35)
Location: drivers/base/property.c:916
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
```
**Symbols:**

```
ffffffff817c11c0-ffffffff817c1292: fwnode_get_mac_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *fwnode_get_mac_address(struct fwnode_handle *fwnode, char *addr, int alen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817d5ae8)
Location: drivers/base/property.c:968
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
```
**Symbols:**

```
ffffffff817d5e50-ffffffff817d5f22: fwnode_get_mac_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *fwnode_get_mac_address(struct fwnode_handle *fwnode, char *addr, int alen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff817b9508)
Location: drivers/base/property.c:974
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
```
**Symbols:**

```
ffffffff817b9870-ffffffff817b9942: fwnode_get_mac_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *fwnode_get_mac_address(struct fwnode_handle *fwnode, char *addr, int alen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81843168)
Location: drivers/base/property.c:972
Inline: True
Inline callers:
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
```
**Symbols:**

```
ffffffff818434f0-ffffffff818435c2: fwnode_get_mac_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fwnode_get_mac_address(struct fwnode_handle *fwnode, char *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81c939b0)
Location: net/ethernet/eth.c:613
Inline: False
Direct callers:
  - net/ethernet/eth.c:device_get_ethdev_address
```
**Symbols:**

```
ffffffff81c939b0-ffffffff81c93a59: fwnode_get_mac_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fwnode_get_mac_address(struct fwnode_handle *fwnode, char *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81e4f0f0)
Location: net/ethernet/eth.c:610
Inline: False
Direct callers:
  - net/ethernet/eth.c:device_get_ethdev_address
```
**Symbols:**

```
ffffffff81e4f0f0-ffffffff81e4f199: fwnode_get_mac_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fwnode_get_mac_address(struct fwnode_handle *fwnode, char *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81eaa790)
Location: net/ethernet/eth.c:610
Inline: False
Direct callers:
  - net/ethernet/eth.c:device_get_ethdev_address
```
**Symbols:**

```
ffffffff81eaa790-ffffffff81eaa839: fwnode_get_mac_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fwnode_get_mac_address(struct fwnode_handle *fwnode, char *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethernet/eth.c (ffffffff81f6d240)
Location: net/ethernet/eth.c:610
Inline: False
Direct callers:
  - net/ethernet/eth.c:device_get_ethdev_address
```
**Symbols:**

```
ffffffff81f6d240-ffffffff81f6d2e9: fwnode_get_mac_address (STB_GLOBAL)
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
void *fwnode_get_mac_address(struct fwnode_handle *fwnode, char *addr, int alen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffff8000108f37e0)
Location: drivers/base/property.c:837
Inline: True
Direct callers:
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
```
**Symbols:**

```
ffff8000108f37e0-ffff8000108f3868: fwnode_get_mac_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *fwnode_get_mac_address(struct fwnode_handle *fwnode, char *addr, int alen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c09e00b8)
Location: drivers/base/property.c:837
Inline: True
Direct callers:
  - drivers/base/property.c:device_get_mac_address
```
**Symbols:**

```
c09e00b8-c09e0130: fwnode_get_mac_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void *fwnode_get_mac_address(struct fwnode_handle *fwnode, char *addr, int alen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (c00000000098d6c0)
Location: drivers/base/property.c:837
Inline: True
Direct callers:
  - drivers/base/property.c:device_get_mac_address
  - drivers/base/property.c:device_get_mac_address
```
**Symbols:**

```
c00000000098d6c0-c00000000098d780: fwnode_get_mac_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void *fwnode_get_mac_address(struct fwnode_handle *fwnode, char *addr, int alen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffe000584f0c)
Location: drivers/base/property.c:837
Inline: True
Direct callers:
  - drivers/base/property.c:device_get_mac_address
```
**Symbols:**

```
ffffffe000584f0c-ffffffe000584f80: fwnode_get_mac_address (STB_GLOBAL)
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
void *fwnode_get_mac_address(struct fwnode_handle *fwnode, char *addr, int alen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816cbf10)
Location: drivers/base/property.c:837
Inline: True
Direct callers:
  - drivers/base/property.c:device_get_mac_address
```
**Symbols:**

```
ffffffff816cbf10-ffffffff816cbf77: fwnode_get_mac_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *fwnode_get_mac_address(struct fwnode_handle *fwnode, char *addr, int alen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816a7240)
Location: drivers/base/property.c:837
Inline: True
Direct callers:
  - drivers/base/property.c:device_get_mac_address
```
**Symbols:**

```
ffffffff816a7240-ffffffff816a72a7: fwnode_get_mac_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *fwnode_get_mac_address(struct fwnode_handle *fwnode, char *addr, int alen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff816fa480)
Location: drivers/base/property.c:837
Inline: True
Direct callers:
  - drivers/base/property.c:device_get_mac_address
```
**Symbols:**

```
ffffffff816fa480-ffffffff816fa4e7: fwnode_get_mac_address (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *fwnode_get_mac_address(struct fwnode_handle *fwnode, char *addr, int alen);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/property.c (ffffffff81714d20)
Location: drivers/base/property.c:837
Inline: True
Direct callers:
  - drivers/base/property.c:device_get_mac_address
```
**Symbols:**

```
ffffffff81714d20-ffffffff81714d87: fwnode_get_mac_address (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int alen</code>
</li>
<li>
<b>Return type changed. </b>
<code>void *</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
