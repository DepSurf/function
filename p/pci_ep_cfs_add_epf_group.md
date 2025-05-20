# Function: <code>pci_ep_cfs_add_epf_group</code>

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
struct config_group *pci_ep_cfs_add_epf_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff814d13c0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:408
Inline: False
```
**Symbols:**

```
ffffffff814d13c0-ffffffff814d140f: pci_ep_cfs_add_epf_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct config_group *pci_ep_cfs_add_epf_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff81511670)
Location: drivers/pci/endpoint/pci-ep-cfs.c:411
Inline: False
```
**Symbols:**

```
ffffffff81511670-ffffffff815116bf: pci_ep_cfs_add_epf_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_ep_cfs_add_epf_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:440
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
```
**Symbols:**

```
ffffffff81547114-ffffffff81547128: pci_ep_cfs_add_epf_group.cold.2 (STB_LOCAL)
ffffffff81546810-ffffffff8154684c: pci_ep_cfs_add_epf_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_ep_cfs_add_epf_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:464
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
```
**Symbols:**

```
ffffffff8155d766-ffffffff8155d77a: pci_ep_cfs_add_epf_group.cold.2 (STB_LOCAL)
ffffffff8155ce90-ffffffff8155cecc: pci_ep_cfs_add_epf_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_ep_cfs_add_epf_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:464
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
```
**Symbols:**

```
ffffffff8158da42-ffffffff8158da56: pci_ep_cfs_add_epf_group.cold (STB_LOCAL)
ffffffff8158d040-ffffffff8158d07e: pci_ep_cfs_add_epf_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_ep_cfs_add_epf_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:464
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
```
**Symbols:**

```
ffffffff815af662-ffffffff815af676: pci_ep_cfs_add_epf_group.cold (STB_LOCAL)
ffffffff815aec60-ffffffff815aec9e: pci_ep_cfs_add_epf_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_ep_cfs_add_epf_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:448
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
```
**Symbols:**

```
ffffffff816588ac-ffffffff816588c0: pci_ep_cfs_add_epf_group.cold (STB_LOCAL)
ffffffff81657f10-ffffffff81657f4e: pci_ep_cfs_add_epf_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_ep_cfs_add_epf_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:448
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
```
**Symbols:**

```
ffffffff81bfdd05-ffffffff81bfdd19: pci_ep_cfs_add_epf_group.cold (STB_LOCAL)
ffffffff81678370-ffffffff816783ae: pci_ep_cfs_add_epf_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_ep_cfs_add_epf_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:618
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
```
**Symbols:**

```
ffffffff81befc31-ffffffff81befc45: pci_ep_cfs_add_epf_group.cold (STB_LOCAL)
ffffffff8165abb0-ffffffff8165abee: pci_ep_cfs_add_epf_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_ep_cfs_add_epf_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:642
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
```
**Symbols:**

```
ffffffff81ceb037-ffffffff81ceb04b: pci_ep_cfs_add_epf_group.cold (STB_LOCAL)
ffffffff816ccd30-ffffffff816ccd6e: pci_ep_cfs_add_epf_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_ep_cfs_add_epf_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:630
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
```
**Symbols:**

```
ffffffff81eb247d-ffffffff81eb2491: pci_ep_cfs_add_epf_group.cold (STB_LOCAL)
ffffffff817f5500-ffffffff817f5546: pci_ep_cfs_add_epf_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct config_group *pci_ep_cfs_add_epf_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff81920d00)
Location: drivers/pci/endpoint/pci-ep-cfs.c:630
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
```
**Symbols:**

```
ffffffff81920d00-ffffffff81920d63: pci_ep_cfs_add_epf_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct config_group *pci_ep_cfs_add_epf_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff819646f0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:667
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
```
**Symbols:**

```
ffffffff819646f0-ffffffff81964753: pci_ep_cfs_add_epf_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct config_group *pci_ep_cfs_add_epf_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffff819adda0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:667
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
```
**Symbols:**

```
ffffffff819adda0-ffffffff819ade03: pci_ep_cfs_add_epf_group (STB_GLOBAL)
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
struct config_group *pci_ep_cfs_add_epf_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffff80001071a188)
Location: drivers/pci/endpoint/pci-ep-cfs.c:464
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
```
**Symbols:**

```
ffff80001071a188-ffff80001071a1ec: pci_ep_cfs_add_epf_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct config_group *pci_ep_cfs_add_epf_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (c08a3edc)
Location: drivers/pci/endpoint/pci-ep-cfs.c:464
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
```
**Symbols:**

```
c08a3edc-c08a3f38: pci_ep_cfs_add_epf_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct config_group *pci_ep_cfs_add_epf_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (c00000000088a170)
Location: drivers/pci/endpoint/pci-ep-cfs.c:464
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
```
**Symbols:**

```
c00000000088a170-c00000000088a1f8: pci_ep_cfs_add_epf_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct config_group *pci_ep_cfs_add_epf_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (ffffffe0004e1d26)
Location: drivers/pci/endpoint/pci-ep-cfs.c:464
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
```
**Symbols:**

```
ffffffe0004e1d26-ffffffe0004e1d82: pci_ep_cfs_add_epf_group (STB_GLOBAL)
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
struct config_group *pci_ep_cfs_add_epf_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:464
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
```
**Symbols:**

```
ffffffff815a2e22-ffffffff815a2e36: pci_ep_cfs_add_epf_group.cold (STB_LOCAL)
ffffffff815a2420-ffffffff815a245e: pci_ep_cfs_add_epf_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_ep_cfs_add_epf_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:464
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
```
**Symbols:**

```
ffffffff81591fc2-ffffffff81591fd6: pci_ep_cfs_add_epf_group.cold (STB_LOCAL)
ffffffff815915c0-ffffffff815915fe: pci_ep_cfs_add_epf_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_ep_cfs_add_epf_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:464
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
```
**Symbols:**

```
ffffffff815a33b2-ffffffff815a33c6: pci_ep_cfs_add_epf_group.cold (STB_LOCAL)
ffffffff815a29b0-ffffffff815a29ee: pci_ep_cfs_add_epf_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct config_group *pci_ep_cfs_add_epf_group(const char *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/endpoint/pci-ep-cfs.c (0)
Location: drivers/pci/endpoint/pci-ep-cfs.c:464
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-epf-core.c:__pci_epf_register_driver
```
**Symbols:**

```
ffffffff815bd7b2-ffffffff815bd7c6: pci_ep_cfs_add_epf_group.cold (STB_LOCAL)
ffffffff815bcdb0-ffffffff815bcdee: pci_ep_cfs_add_epf_group (STB_GLOBAL)
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
