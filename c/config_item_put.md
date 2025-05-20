# Function: <code>config_item_put</code>

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
void config_item_put(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff812e1c60)
Location: fs/configfs/item.c:178
Inline: False
Direct callers:
  - fs/configfs/file.c:configfs_release
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:configfs_remove_default_groups
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/item.c:config_item_put
  - fs/configfs/item.c:config_item_put
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop
```
**Symbols:**

```
ffffffff812e1c60-ffffffff812e1d00: config_item_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void config_item_put(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff813066a7)
Location: fs/configfs/item.c:178
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
  - fs/configfs/item.c:config_item_release
Direct callers:
  - fs/configfs/file.c:configfs_release
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:configfs_remove_default_groups
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop
```
**Symbols:**

```
ffffffff81306710-ffffffff8130673a: config_item_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void config_item_put(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff813346a7)
Location: fs/configfs/item.c:178
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
  - fs/configfs/item.c:config_item_release
Direct callers:
  - fs/configfs/file.c:configfs_release
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:configfs_remove_default_groups
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop
```
**Symbols:**

```
ffffffff81334710-ffffffff8133473b: config_item_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void config_item_put(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff8134b9c7)
Location: fs/configfs/item.c:162
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
  - fs/configfs/item.c:config_item_release
Direct callers:
  - fs/configfs/file.c:configfs_release
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:configfs_remove_default_groups
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop
```
**Symbols:**

```
ffffffff8134ba30-ffffffff8134ba5b: config_item_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void config_item_put(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff81374382)
Location: fs/configfs/item.c:148
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
  - fs/configfs/item.c:config_item_release
Direct callers:
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:configfs_remove_default_groups
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop
```
**Symbols:**

```
ffffffff813743f0-ffffffff81374419: config_item_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void config_item_put(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff8138c602)
Location: fs/configfs/item.c:148
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
  - fs/configfs/item.c:config_item_release
Direct callers:
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:configfs_remove_default_groups
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop
```
**Symbols:**

```
ffffffff8138c670-ffffffff8138c699: config_item_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void config_item_put(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff813d79f2)
Location: fs/configfs/item.c:148
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
Direct callers:
  - fs/configfs/file.c:__configfs_open_file
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_group
  - fs/configfs/dir.c:unlink_group
  - fs/configfs/dir.c:configfs_remove_default_groups
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop
```
**Symbols:**

```
ffffffff813d7a80-ffffffff813d7abe: config_item_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void config_item_put(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff813e9692)
Location: fs/configfs/item.c:148
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
Direct callers:
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_group
  - fs/configfs/dir.c:unlink_group
  - fs/configfs/dir.c:configfs_remove_default_groups
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop
```
**Symbols:**

```
ffffffff813e9720-ffffffff813e975e: config_item_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void config_item_put(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff813f01f2)
Location: fs/configfs/item.c:146
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
Direct callers:
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_group
  - fs/configfs/dir.c:unlink_group
  - fs/configfs/dir.c:configfs_remove_default_groups
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffff813f0280-ffffffff813f02be: config_item_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void config_item_put(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff814420df)
Location: fs/configfs/item.c:146
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
Direct callers:
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:client_drop_item
  - fs/configfs/dir.c:unlink_group
  - fs/configfs/dir.c:unlink_group
  - fs/configfs/dir.c:configfs_remove_default_groups
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
```
**Symbols:**

```
ffffffff81442170-ffffffff814421ae: config_item_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void config_item_put(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/configfs/item.c (ffffffff814bde0d)
Location: fs/configfs/item.c:146
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
Direct callers:
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_group
  - fs/configfs/dir.c:unlink_group
  - fs/configfs/dir.c:configfs_remove_default_groups
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
```
**Symbols:**

```
ffffffff814bdd50-ffffffff814bddac: config_item_put.part.0 (STB_LOCAL)
ffffffff814bde50-ffffffff814bdebe: config_item_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void config_item_put(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/configfs/item.c (ffffffff81555b8d)
Location: fs/configfs/item.c:146
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
Direct callers:
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_group
  - fs/configfs/dir.c:unlink_group
  - fs/configfs/dir.c:configfs_remove_default_groups
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
```
**Symbols:**

```
ffffffff81555ac0-ffffffff81555b1c: config_item_put.part.0 (STB_LOCAL)
ffffffff81555be0-ffffffff81555c4e: config_item_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void config_item_put(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/configfs/item.c (ffffffff8158d92d)
Location: fs/configfs/item.c:146
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
Direct callers:
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_group
  - fs/configfs/dir.c:unlink_group
  - fs/configfs/dir.c:configfs_remove_default_groups
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop
```
**Symbols:**

```
ffffffff8158d860-ffffffff8158d8bc: config_item_put.part.0 (STB_LOCAL)
ffffffff8158d980-ffffffff8158d9ee: config_item_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void config_item_put(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/configfs/item.c (ffffffff815c666d)
Location: fs/configfs/item.c:146
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
Direct callers:
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_group
  - fs/configfs/dir.c:unlink_group
  - fs/configfs/dir.c:configfs_remove_default_groups
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop
```
**Symbols:**

```
ffffffff815c65a0-ffffffff815c65fc: config_item_put.part.0 (STB_LOCAL)
ffffffff815c66c0-ffffffff815c672e: config_item_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void config_item_put(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/configfs/item.c (ffff80001045e0d0)
Location: fs/configfs/item.c:148
Inline: True
Direct callers:
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:configfs_remove_default_groups
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop
```
**Symbols:**

```
ffff80001045e0d0-ffff80001045e19c: config_item_put.part.0 (STB_LOCAL)
ffff80001045e1a0-ffff80001045e1d0: config_item_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void config_item_put(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/configfs/item.c (c061eb6c)
Location: fs/configfs/item.c:148
Inline: True
Direct callers:
  - fs/configfs/file.c:__configfs_open_file
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:configfs_remove_default_groups
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop
```
**Symbols:**

```
c061eb6c-c061ec38: config_item_put.part.0 (STB_LOCAL)
c061ec38-c061ec5c: config_item_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void config_item_put(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (c000000000579c60)
Location: fs/configfs/item.c:148
Inline: False
Direct callers:
  - fs/configfs/file.c:__configfs_open_file
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:client_drop_item
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:configfs_remove_default_groups
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/item.c:config_item_put
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop
```
**Symbols:**

```
c000000000579c60-c000000000579dc4: config_item_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void config_item_put(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffe0002ede5e)
Location: fs/configfs/item.c:148
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
Direct callers:
  - fs/configfs/file.c:__configfs_open_file
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:configfs_remove_default_groups
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop
```
**Symbols:**

```
ffffffe0002eded4-ffffffe0002edf1c: config_item_put (STB_GLOBAL)
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
void config_item_put(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff81384be2)
Location: fs/configfs/item.c:148
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
  - fs/configfs/item.c:config_item_release
Direct callers:
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:configfs_remove_default_groups
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop
```
**Symbols:**

```
ffffffff81384c50-ffffffff81384c79: config_item_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void config_item_put(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff81375672)
Location: fs/configfs/item.c:148
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
  - fs/configfs/item.c:config_item_release
Direct callers:
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:configfs_remove_default_groups
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop
```
**Symbols:**

```
ffffffff813756e0-ffffffff81375709: config_item_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void config_item_put(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff813826b2)
Location: fs/configfs/item.c:148
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
  - fs/configfs/item.c:config_item_release
Direct callers:
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:configfs_remove_default_groups
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop
```
**Symbols:**

```
ffffffff81382720-ffffffff81382749: config_item_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void config_item_put(struct config_item *item);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff813961d2)
Location: fs/configfs/item.c:148
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
  - fs/configfs/item.c:config_item_release
Direct callers:
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_rmdir
  - fs/configfs/dir.c:configfs_mkdir
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:unlink_obj
  - fs/configfs/dir.c:configfs_remove_default_groups
  - fs/configfs/symlink.c:configfs_unlink
  - fs/configfs/symlink.c:configfs_symlink
  - fs/configfs/symlink.c:configfs_symlink
  - drivers/pci/endpoint/pci-ep-cfs.c:pci_epf_drop
```
**Symbols:**

```
ffffffff81396240-ffffffff81396269: config_item_put (STB_GLOBAL)
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
