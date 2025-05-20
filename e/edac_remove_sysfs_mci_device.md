# Function: <code>edac_remove_sysfs_mci_device</code>

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
void edac_remove_sysfs_mci_device(struct mem_ctl_info *mci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc_sysfs.c (ffffffff8175ed20)
Location: drivers/edac/edac_mc_sysfs.c:1033
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
```
**Symbols:**

```
ffffffff8175ed20-ffffffff8175ed6d: edac_remove_sysfs_mci_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void edac_remove_sysfs_mci_device(struct mem_ctl_info *mci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc_sysfs.c (ffffffff817d0d80)
Location: drivers/edac/edac_mc_sysfs.c:1033
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
```
**Symbols:**

```
ffffffff817d0d80-ffffffff817d0dcd: edac_remove_sysfs_mci_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void edac_remove_sysfs_mci_device(struct mem_ctl_info *mci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc_sysfs.c (ffffffff81819af0)
Location: drivers/edac/edac_mc_sysfs.c:1011
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
```
**Symbols:**

```
ffffffff81819af0-ffffffff81819b3c: edac_remove_sysfs_mci_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void edac_remove_sysfs_mci_device(struct mem_ctl_info *mci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc_sysfs.c (ffffffff81845310)
Location: drivers/edac/edac_mc_sysfs.c:987
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
```
**Symbols:**

```
ffffffff81845310-ffffffff8184535c: edac_remove_sysfs_mci_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void edac_remove_sysfs_mci_device(struct mem_ctl_info *mci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc_sysfs.c (ffffffff818880e0)
Location: drivers/edac/edac_mc_sysfs.c:997
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
```
**Symbols:**

```
ffffffff818880e0-ffffffff8188812c: edac_remove_sysfs_mci_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void edac_remove_sysfs_mci_device(struct mem_ctl_info *mci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc_sysfs.c (ffffffff818ba090)
Location: drivers/edac/edac_mc_sysfs.c:981
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
```
**Symbols:**

```
ffffffff818ba090-ffffffff818ba0dc: edac_remove_sysfs_mci_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void edac_remove_sysfs_mci_device(struct mem_ctl_info *mci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc_sysfs.c (ffffffff8198a827)
Location: drivers/edac/edac_mc_sysfs.c:951
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffff8198a610-ffffffff8198a66f: edac_remove_sysfs_mci_device.part.0 (STB_LOCAL)
ffffffff8198a850-ffffffff8198a867: edac_remove_sysfs_mci_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void edac_remove_sysfs_mci_device(struct mem_ctl_info *mci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc_sysfs.c (ffffffff8198e467)
Location: drivers/edac/edac_mc_sysfs.c:963
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffff8198e250-ffffffff8198e2af: edac_remove_sysfs_mci_device.part.0 (STB_LOCAL)
ffffffff8198e490-ffffffff8198e4a7: edac_remove_sysfs_mci_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void edac_remove_sysfs_mci_device(struct mem_ctl_info *mci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc_sysfs.c (ffffffff81972af7)
Location: drivers/edac/edac_mc_sysfs.c:963
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffff819728e0-ffffffff8197293f: edac_remove_sysfs_mci_device.part.0 (STB_LOCAL)
ffffffff81972b20-ffffffff81972b37: edac_remove_sysfs_mci_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void edac_remove_sysfs_mci_device(struct mem_ctl_info *mci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc_sysfs.c (ffffffff81a1b805)
Location: drivers/edac/edac_mc_sysfs.c:963
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffff81a1b5e0-ffffffff81a1b63f: edac_remove_sysfs_mci_device.part.0 (STB_LOCAL)
ffffffff81a1b820-ffffffff81a1b837: edac_remove_sysfs_mci_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void edac_remove_sysfs_mci_device(struct mem_ctl_info *mci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc_sysfs.c (ffffffff81b84713)
Location: drivers/edac/edac_mc_sysfs.c:963
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffff81b844d0-ffffffff81b8454e: edac_remove_sysfs_mci_device.part.0 (STB_LOCAL)
ffffffff81b84740-ffffffff81b84763: edac_remove_sysfs_mci_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void edac_remove_sysfs_mci_device(struct mem_ctl_info *mci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc_sysfs.c (ffffffff81d23543)
Location: drivers/edac/edac_mc_sysfs.c:987
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffff81d232b0-ffffffff81d2332e: edac_remove_sysfs_mci_device.part.0 (STB_LOCAL)
ffffffff81d23580-ffffffff81d235a3: edac_remove_sysfs_mci_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void edac_remove_sysfs_mci_device(struct mem_ctl_info *mci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc_sysfs.c (ffffffff81d8c743)
Location: drivers/edac/edac_mc_sysfs.c:987
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffff81d8c4b0-ffffffff81d8c52e: edac_remove_sysfs_mci_device.part.0 (STB_LOCAL)
ffffffff81d8c780-ffffffff81d8c7a3: edac_remove_sysfs_mci_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void edac_remove_sysfs_mci_device(struct mem_ctl_info *mci);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/edac/edac_mc_sysfs.c (ffffffff81e43ff3)
Location: drivers/edac/edac_mc_sysfs.c:987
Inline: True
Inline callers:
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
  - drivers/edac/edac_mc_sysfs.c:edac_create_sysfs_mci_device
```
**Symbols:**

```
ffffffff81e43d60-ffffffff81e43dde: edac_remove_sysfs_mci_device.part.0 (STB_LOCAL)
ffffffff81e44030-ffffffff81e44053: edac_remove_sysfs_mci_device (STB_GLOBAL)
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
void edac_remove_sysfs_mci_device(struct mem_ctl_info *mci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc_sysfs.c (ffff800010b123b0)
Location: drivers/edac/edac_mc_sysfs.c:981
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
```
**Symbols:**

```
ffff800010b123b0-ffff800010b12408: edac_remove_sysfs_mci_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void edac_remove_sysfs_mci_device(struct mem_ctl_info *mci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc_sysfs.c (c0bf0598)
Location: drivers/edac/edac_mc_sysfs.c:981
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
```
**Symbols:**

```
c0bf0598-c0bf05ec: edac_remove_sysfs_mci_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void edac_remove_sysfs_mci_device(struct mem_ctl_info *mci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc_sysfs.c (c000000000c06860)
Location: drivers/edac/edac_mc_sysfs.c:981
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
```
**Symbols:**

```
c000000000c06860-c000000000c068ec: edac_remove_sysfs_mci_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void edac_remove_sysfs_mci_device(struct mem_ctl_info *mci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc_sysfs.c (ffffffe0006ff008)
Location: drivers/edac/edac_mc_sysfs.c:981
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
```
**Symbols:**

```
ffffffe0006ff008-ffffffe0006ff060: edac_remove_sysfs_mci_device (STB_GLOBAL)
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
void edac_remove_sysfs_mci_device(struct mem_ctl_info *mci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc_sysfs.c (ffffffff8185ff10)
Location: drivers/edac/edac_mc_sysfs.c:981
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
```
**Symbols:**

```
ffffffff8185ff10-ffffffff8185ff5c: edac_remove_sysfs_mci_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void edac_remove_sysfs_mci_device(struct mem_ctl_info *mci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc_sysfs.c (ffffffff818274e0)
Location: drivers/edac/edac_mc_sysfs.c:981
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
```
**Symbols:**

```
ffffffff818274e0-ffffffff8182752c: edac_remove_sysfs_mci_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void edac_remove_sysfs_mci_device(struct mem_ctl_info *mci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc_sysfs.c (ffffffff818af540)
Location: drivers/edac/edac_mc_sysfs.c:981
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
```
**Symbols:**

```
ffffffff818af540-ffffffff818af58c: edac_remove_sysfs_mci_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void edac_remove_sysfs_mci_device(struct mem_ctl_info *mci);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc_sysfs.c (ffffffff818cb7d0)
Location: drivers/edac/edac_mc_sysfs.c:981
Inline: False
Direct callers:
  - drivers/edac/edac_mc.c:edac_mc_del_mc
```
**Symbols:**

```
ffffffff818cb7d0-ffffffff818cb81c: edac_remove_sysfs_mci_device (STB_GLOBAL)
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
