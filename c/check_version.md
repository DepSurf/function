# Function: <code>check_version</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff81105d40)
Location: kernel/module.c:1264
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
Direct callers:
  - kernel/module.c:layout_and_allocate
```
```
In drivers/md/dm-ioctl.c (ffffffff816a9df7)
Location: drivers/md/dm-ioctl.c:1642
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff81105d40-ffffffff81105e1d: check_version.isra.25.part.26 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (ffffffff8110f06f)
Location: kernel/module.c:1269
Inline: True
Inline callers:
  - kernel/module.c:layout_and_allocate
Direct callers:
  - kernel/module.c:layout_and_allocate
```
```
In drivers/md/dm-ioctl.c (ffffffff8170a247)
Location: drivers/md/dm-ioctl.c:1652
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff8110d620-ffffffff8110d6f9: check_version.isra.27.part.28 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1338
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff8173c117)
Location: drivers/md/dm-ioctl.c:1652
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1357
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff817559da)
Location: drivers/md/dm-ioctl.c:1671
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1365
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff817c7c7a)
Location: drivers/md/dm-ioctl.c:1679
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1364
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff8180f83b)
Location: drivers/md/dm-ioctl.c:1680
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1365
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff8183b81b)
Location: drivers/md/dm-ioctl.c:1680
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1361
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff8187f3e2)
Location: drivers/md/dm-ioctl.c:1680
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1375
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff818b1262)
Location: drivers/md/dm-ioctl.c:1706
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1378
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff8198133e)
Location: drivers/md/dm-ioctl.c:1706
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1332
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:resolve_symbol
```
```
In drivers/md/dm-ioctl.c (ffffffff8198595e)
Location: drivers/md/dm-ioctl.c:1707
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff8115df50-ffffffff8115e024: check_version.constprop.0 (STB_LOCAL)
ffffffff81be3f19-ffffffff81be3f3e: check_version.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1240
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:resolve_symbol
```
```
In drivers/md/dm-ioctl.c (ffffffff8196929e)
Location: drivers/md/dm-ioctl.c:1784
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff8115ef80-ffffffff8115f054: check_version.constprop.0 (STB_LOCAL)
ffffffff81bd5dca-ffffffff81bd5def: check_version.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1240
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:resolve_symbol
```
```
In drivers/md/dm-ioctl.c (ffffffff81a114be)
Location: drivers/md/dm-ioctl.c:1799
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff811842d0-ffffffff811843b4: check_version.constprop.0 (STB_LOCAL)
ffffffff81cb249e-ffffffff81cb24d7: check_version.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int check_version(const struct load_info *info, const char *symname, struct module *mod, const s32 *crc);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module/version.c (0)
Location: kernel/module/version.c:13
Inline: False
Direct callers:
  - kernel/module/main.c:resolve_symbol
  - kernel/module/version.c:check_modstruct_version
```
```
In drivers/md/dm-ioctl.c (ffffffff81b79bfe)
Location: drivers/md/dm-ioctl.c:1807
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff81e61c99-ffffffff81e61cae: check_version.cold (STB_LOCAL)
ffffffff81192e50-ffffffff81192f6e: check_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int check_version(const struct load_info *info, const char *symname, struct module *mod, const s32 *crc);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module/version.c (0)
Location: kernel/module/version.c:13
Inline: False
Direct callers:
  - kernel/module/main.c:resolve_symbol
  - kernel/module/version.c:check_modstruct_version
```
```
In drivers/md/dm-ioctl.c (ffffffff81d1808e)
Location: drivers/md/dm-ioctl.c:1814
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff8205ac7a-ffffffff8205ac8f: check_version.cold (STB_LOCAL)
ffffffff811d0640-ffffffff811d077b: check_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int check_version(const struct load_info *info, const char *symname, struct module *mod, const s32 *crc);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module/version.c (0)
Location: kernel/module/version.c:13
Inline: False
Direct callers:
  - kernel/module/main.c:resolve_symbol
  - kernel/module/main.c:resolve_symbol
  - kernel/module/version.c:check_modstruct_version
```
```
In drivers/md/dm-ioctl.c (ffffffff81d8135c)
Location: drivers/md/dm-ioctl.c:1879
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff820d9514-ffffffff820d9529: check_version.cold (STB_LOCAL)
ffffffff811e48c0-ffffffff811e49fb: check_version (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int check_version(const struct load_info *info, const char *symname, struct module *mod, const s32 *crc);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/module/version.c (0)
Location: kernel/module/version.c:13
Inline: False
Direct callers:
  - kernel/module/main.c:resolve_symbol
  - kernel/module/version.c:check_modstruct_version
```
```
In drivers/md/dm-ioctl.c (ffffffff81e389cc)
Location: drivers/md/dm-ioctl.c:1884
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff821b4d95-ffffffff821b4daa: check_version.cold (STB_LOCAL)
ffffffff811fa610-ffffffff811fa74b: check_version (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1375
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffff800010b09198)
Location: drivers/md/dm-ioctl.c:1706
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1375
Inline: True
```
```
In drivers/md/dm-ioctl.c (c0be79b4)
Location: drivers/md/dm-ioctl.c:1706
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1375
Inline: True
```
```
In drivers/md/dm-ioctl.c (c000000000bfacf8)
Location: drivers/md/dm-ioctl.c:1706
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1375
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffe0006f7862)
Location: drivers/md/dm-ioctl.c:1706
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1375
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff818570e2)
Location: drivers/md/dm-ioctl.c:1706
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1375
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff8181e6f2)
Location: drivers/md/dm-ioctl.c:1706
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1375
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff818a6712)
Location: drivers/md/dm-ioctl.c:1706
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (0)
Location: kernel/module.c:1375
Inline: True
```
```
In drivers/md/dm-ioctl.c (ffffffff818c2952)
Location: drivers/md/dm-ioctl.c:1706
Inline: True
Inline callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
