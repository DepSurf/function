# Function: <code>pci_ep_cfs_add_epc_group</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct config_group *pci_ep_cfs_add_epc_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff814d1b60)
Location: drivers/pci/endpoint/pci-ep-cfs.c:159
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
```
**Symbols:**

```
ffffffff814d1b60-ffffffff814d1c0f: pci_ep_cfs_add_epc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct config_group *pci_ep_cfs_add_epc_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff81511e10)
Location: drivers/pci/endpoint/pci-ep-cfs.c:162
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
```
**Symbols:**

```
ffffffff81511e10-ffffffff81511ebf: pci_ep_cfs_add_epc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_ep_cfs_add_epc_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:153
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
```
**Symbols:**

```
ffffffff81547128-ffffffff8154713c: pci_ep_cfs_add_epc_group.cold.3 (STB_LOCAL)
ffffffff81546f30-ffffffff81546fdc: pci_ep_cfs_add_epc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_ep_cfs_add_epc_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:153
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
```
**Symbols:**

```
ffffffff8155d752-ffffffff8155d766: pci_ep_cfs_add_epc_group.cold.1 (STB_LOCAL)
ffffffff8155cde0-ffffffff8155ce8c: pci_ep_cfs_add_epc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_ep_cfs_add_epc_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:153
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
```
**Symbols:**

```
ffffffff8158da2e-ffffffff8158da42: pci_ep_cfs_add_epc_group.cold (STB_LOCAL)
ffffffff8158cf90-ffffffff8158d03a: pci_ep_cfs_add_epc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_ep_cfs_add_epc_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:153
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
```
**Symbols:**

```
ffffffff815af64e-ffffffff815af662: pci_ep_cfs_add_epc_group.cold (STB_LOCAL)
ffffffff815aebb0-ffffffff815aec5a: pci_ep_cfs_add_epc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_ep_cfs_add_epc_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:137
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
```
**Symbols:**

```
ffffffff816588e0-ffffffff816588f4: pci_ep_cfs_add_epc_group.cold (STB_LOCAL)
ffffffff816587f0-ffffffff81658891: pci_ep_cfs_add_epc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_ep_cfs_add_epc_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:137
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
```
**Symbols:**

```
ffffffff81bfdd39-ffffffff81bfdd4d: pci_ep_cfs_add_epc_group.cold (STB_LOCAL)
ffffffff81678c50-ffffffff81678cf1: pci_ep_cfs_add_epc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_ep_cfs_add_epc_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:261
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
```
**Symbols:**

```
ffffffff81befc45-ffffffff81befc59: pci_ep_cfs_add_epc_group.cold (STB_LOCAL)
ffffffff8165b390-ffffffff8165b431: pci_ep_cfs_add_epc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_ep_cfs_add_epc_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:261
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
```
**Symbols:**

```
ffffffff81ceb0ea-ffffffff81ceb0fe: pci_ep_cfs_add_epc_group.cold (STB_LOCAL)
ffffffff816cd780-ffffffff816cd821: pci_ep_cfs_add_epc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_ep_cfs_add_epc_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:259
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
```
**Symbols:**

```
ffffffff81eb2552-ffffffff81eb2566: pci_ep_cfs_add_epc_group.cold (STB_LOCAL)
ffffffff817f60f0-ffffffff817f61b3: pci_ep_cfs_add_epc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct config_group *pci_ep_cfs_add_epc_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff81921af0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:259
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
```
**Symbols:**

```
ffffffff81921af0-ffffffff81921bc0: pci_ep_cfs_add_epc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct config_group *pci_ep_cfs_add_epc_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff81965540)
Location: drivers/pci/endpoint/pci-ep-cfs.c:263
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
```
**Symbols:**

```
ffffffff81965540-ffffffff81965610: pci_ep_cfs_add_epc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct config_group *pci_ep_cfs_add_epc_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff819aebf0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:263
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
```
**Symbols:**

```
ffffffff819aebf0-ffffffff819aecf1: pci_ep_cfs_add_epc_group (STB_GLOBAL)
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
struct config_group *pci_ep_cfs_add_epc_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffff80001071a0b0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:153
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
```
**Symbols:**

```
ffff80001071a0b0-ffff80001071a188: pci_ep_cfs_add_epc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct config_group *pci_ep_cfs_add_epc_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (c08a3e1c)
Location: drivers/pci/endpoint/pci-ep-cfs.c:153
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
```
**Symbols:**

```
c08a3e1c-c08a3edc: pci_ep_cfs_add_epc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct config_group *pci_ep_cfs_add_epc_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (c00000000088ada0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:153
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
```
**Symbols:**

```
c00000000088ada0-c00000000088aeb0: pci_ep_cfs_add_epc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct config_group *pci_ep_cfs_add_epc_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffe0004e1c64)
Location: drivers/pci/endpoint/pci-ep-cfs.c:153
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
```
**Symbols:**

```
ffffffe0004e1c64-ffffffe0004e1d26: pci_ep_cfs_add_epc_group (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_ep_cfs_add_epc_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:153
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
```
**Symbols:**

```
ffffffff815a2e0e-ffffffff815a2e22: pci_ep_cfs_add_epc_group.cold (STB_LOCAL)
ffffffff815a2370-ffffffff815a241a: pci_ep_cfs_add_epc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_ep_cfs_add_epc_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:153
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
```
**Symbols:**

```
ffffffff81591fae-ffffffff81591fc2: pci_ep_cfs_add_epc_group.cold (STB_LOCAL)
ffffffff81591510-ffffffff815915ba: pci_ep_cfs_add_epc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_ep_cfs_add_epc_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:153
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
```
**Symbols:**

```
ffffffff815a339e-ffffffff815a33b2: pci_ep_cfs_add_epc_group.cold (STB_LOCAL)
ffffffff815a2900-ffffffff815a29aa: pci_ep_cfs_add_epc_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_ep_cfs_add_epc_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:153
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epc-core.c:__pci_epc_create
```
**Symbols:**

```
ffffffff815bd79e-ffffffff815bd7b2: pci_ep_cfs_add_epc_group.cold (STB_LOCAL)
ffffffff815bcd00-ffffffff815bcdaa: pci_ep_cfs_add_epc_group (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
