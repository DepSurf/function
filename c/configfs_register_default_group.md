# Function: <code>configfs_register_default_group</code>

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
struct config_group *configfs_register_default_group(struct config_group *parent_group, const char *name, struct config_item_type *item_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff812e0690)
Location: fs/configfs/dir.c:1811
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group
```
**Symbols:**

```
ffffffff812e0690-ffffffff812e071e: configfs_register_default_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct config_group *configfs_register_default_group(struct config_group *parent_group, const char *name, const struct config_item_type *item_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81305010)
Location: fs/configfs/dir.c:1811
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group
```
**Symbols:**

```
ffffffff81305010-ffffffff8130509e: configfs_register_default_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct config_group *configfs_register_default_group(struct config_group *parent_group, const char *name, const struct config_item_type *item_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81333190)
Location: fs/configfs/dir.c:1822
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group
```
**Symbols:**

```
ffffffff81333190-ffffffff8133321e: configfs_register_default_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct config_group *configfs_register_default_group(struct config_group *parent_group, const char *name, const struct config_item_type *item_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8134a580)
Location: fs/configfs/dir.c:1822
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group
```
**Symbols:**

```
ffffffff8134a580-ffffffff8134a60e: configfs_register_default_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct config_group *configfs_register_default_group(struct config_group *parent_group, const char *name, const struct config_item_type *item_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81372dc0)
Location: fs/configfs/dir.c:1874
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group
```
**Symbols:**

```
ffffffff81372dc0-ffffffff81372e48: configfs_register_default_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct config_group *configfs_register_default_group(struct config_group *parent_group, const char *name, const struct config_item_type *item_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8138b1c0)
Location: fs/configfs/dir.c:1831
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group
```
**Symbols:**

```
ffffffff8138b1c0-ffffffff8138b248: configfs_register_default_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct config_group *configfs_register_default_group(struct config_group *parent_group, const char *name, const struct config_item_type *item_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813d68e0)
Location: fs/configfs/dir.c:1832
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group
```
**Symbols:**

```
ffffffff813d68e0-ffffffff813d6964: configfs_register_default_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct config_group *configfs_register_default_group(struct config_group *parent_group, const char *name, const struct config_item_type *item_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813e85b0)
Location: fs/configfs/dir.c:1833
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group
```
**Symbols:**

```
ffffffff813e85b0-ffffffff813e8634: configfs_register_default_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct config_group *configfs_register_default_group(struct config_group *parent_group, const char *name, const struct config_item_type *item_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813ef360)
Location: fs/configfs/dir.c:1832
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group
```
**Symbols:**

```
ffffffff813ef360-ffffffff813ef3e4: configfs_register_default_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct config_group *configfs_register_default_group(struct config_group *parent_group, const char *name, const struct config_item_type *item_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81441250)
Location: fs/configfs/dir.c:1815
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group
```
**Symbols:**

```
ffffffff81441250-ffffffff814412d4: configfs_register_default_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct config_group *configfs_register_default_group(struct config_group *parent_group, const char *name, const struct config_item_type *item_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff814bcdf0)
Location: fs/configfs/dir.c:1815
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group
```
**Symbols:**

```
ffffffff814bcdf0-ffffffff814bce87: configfs_register_default_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct config_group *configfs_register_default_group(struct config_group *parent_group, const char *name, const struct config_item_type *item_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81554980)
Location: fs/configfs/dir.c:1817
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group
```
**Symbols:**

```
ffffffff81554980-ffffffff81554a17: configfs_register_default_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct config_group *configfs_register_default_group(struct config_group *parent_group, const char *name, const struct config_item_type *item_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff8158c700)
Location: fs/configfs/dir.c:1812
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group
```
**Symbols:**

```
ffffffff8158c700-ffffffff8158c797: configfs_register_default_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct config_group *configfs_register_default_group(struct config_group *parent_group, const char *name, const struct config_item_type *item_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff815c53d0)
Location: fs/configfs/dir.c:1812
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group
```
**Symbols:**

```
ffffffff815c53d0-ffffffff815c5495: configfs_register_default_group (STB_GLOBAL)
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
struct config_group *configfs_register_default_group(struct config_group *parent_group, const char *name, const struct config_item_type *item_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffff80001045c2c0)
Location: fs/configfs/dir.c:1831
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group
```
**Symbols:**

```
ffff80001045c2c0-ffff80001045c35c: configfs_register_default_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct config_group *configfs_register_default_group(struct config_group *parent_group, const char *name, const struct config_item_type *item_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c061d46c)
Location: fs/configfs/dir.c:1831
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group
```
**Symbols:**

```
c061d46c-c061d4f0: configfs_register_default_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct config_group *configfs_register_default_group(struct config_group *parent_group, const char *name, const struct config_item_type *item_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (c000000000577ab0)
Location: fs/configfs/dir.c:1831
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group
```
**Symbols:**

```
c000000000577ab0-c000000000577bc4: configfs_register_default_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct config_group *configfs_register_default_group(struct config_group *parent_group, const char *name, const struct config_item_type *item_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffe0002ec6b0)
Location: fs/configfs/dir.c:1831
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group
```
**Symbols:**

```
ffffffe0002ec6b0-ffffffe0002ec72e: configfs_register_default_group (STB_GLOBAL)
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
struct config_group *configfs_register_default_group(struct config_group *parent_group, const char *name, const struct config_item_type *item_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff813837a0)
Location: fs/configfs/dir.c:1831
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group
```
**Symbols:**

```
ffffffff813837a0-ffffffff81383828: configfs_register_default_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct config_group *configfs_register_default_group(struct config_group *parent_group, const char *name, const struct config_item_type *item_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81374230)
Location: fs/configfs/dir.c:1831
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group
```
**Symbols:**

```
ffffffff81374230-ffffffff813742b8: configfs_register_default_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct config_group *configfs_register_default_group(struct config_group *parent_group, const char *name, const struct config_item_type *item_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81381270)
Location: fs/configfs/dir.c:1831
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group
```
**Symbols:**

```
ffffffff81381270-ffffffff813812f8: configfs_register_default_group (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct config_group *configfs_register_default_group(struct config_group *parent_group, const char *name, const struct config_item_type *item_type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/dir.c (ffffffff81394d30)
Location: fs/configfs/dir.c:1831
Inline: False
Direct callers:
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_init
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_ep_cfs_add_epf_group
```
**Symbols:**

```
ffffffff81394d30-ffffffff81394db8: configfs_register_default_group (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct config_item_type *item_type</code> ➡️ <code>const struct config_item_type *item_type</code>
</li>
</ul>
</details>
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
