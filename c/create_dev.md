# Function: <code>create_dev</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int create_dev(char *name, dev_t dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81f5a74e)
Location: init/do_mounts.h:16
Inline: True
Inline callers:
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_rd.c (ffffffff81002e6d)
Location: init/do_mounts.h:16
Inline: False
Direct callers:
  - init/do_mounts_rd.c:rd_load_disk
  - init/do_mounts_rd.c:rd_load_disk
```
```
In init/do_mounts_initrd.c (ffffffff81f5b019)
Location: init/do_mounts.h:16
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff81f5b698)
Location: init/do_mounts.h:16
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_setup_drive
  - init/do_mounts_md.c:md_run_setup
```
**Symbols:**

```
ffffffff81002e6d-ffffffff81002ea9: create_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
int create_dev(char *name, dev_t dev);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff81002ee3)
Location: init/do_mounts.h:16
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_rd.c (ffffffff81002f23)
Location: init/do_mounts.h:16
Inline: False
Direct callers:
  - init/do_mounts_rd.c:rd_load_disk
  - init/do_mounts_rd.c:rd_load_disk
```
```
In init/do_mounts_initrd.c (ffffffff81f82fc3)
Location: init/do_mounts.h:16
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff81f839d7)
Location: init/do_mounts.h:16
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
**Symbols:**

```
ffffffff81002ee3-ffffffff81002f23: create_dev.constprop.5 (STB_LOCAL)
ffffffff81002f23-ffffffff81002f60: create_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff81002e83)
Location: init/do_mounts.h:16
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_initrd.c (ffffffff81fbe85d)
Location: init/do_mounts.h:16
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff81fbefec)
Location: init/do_mounts.h:16
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
**Symbols:**

```
ffffffff81002e83-ffffffff81002ec3: create_dev.constprop.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff810027a0)
Location: init/do_mounts.h:16
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_initrd.c (ffffffff8209e999)
Location: init/do_mounts.h:16
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff8209f11e)
Location: init/do_mounts.h:16
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
**Symbols:**

```
ffffffff810027a0-ffffffff810027e0: create_dev.constprop.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff810027d0)
Location: init/do_mounts.h:17
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_initrd.c (ffffffff826a4996)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff826a511b)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
**Symbols:**

```
ffffffff810027d0-ffffffff81002810: create_dev.constprop.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff81002efa)
Location: init/do_mounts.h:17
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_initrd.c (ffffffff826cdaa0)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff826ce2a4)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
**Symbols:**

```
ffffffff81002efa-ffffffff81002f4c: create_dev.constprop.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff81002f87)
Location: init/do_mounts.h:17
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_initrd.c (ffffffff82883ae3)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff828842e7)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
**Symbols:**

```
ffffffff81002f87-ffffffff81002fd9: create_dev.constprop.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff810030b4)
Location: init/do_mounts.h:17
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_initrd.c (ffffffff8289ab10)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff8289b338)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
**Symbols:**

```
ffffffff810030b4-ffffffff81003107: create_dev.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff810030a4)
Location: init/do_mounts.h:17
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_initrd.c (ffffffff8289daf5)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff8289e31d)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
**Symbols:**

```
ffffffff810030a4-ffffffff810030f7: create_dev.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff81004279)
Location: init/do_mounts.h:17
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_initrd.c (ffffffff82cc40c5)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff8100436f)
Location: init/do_mounts.h:17
Inline: True
Direct callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
**Symbols:**

```
ffffffff81004279-ffffffff810042cc: create_dev.constprop.0 (STB_LOCAL)
ffffffff8100436f-ffffffff810043be: create_dev.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff82fafc6d)
Location: init/do_mounts.h:17
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_initrd.c (ffffffff82fb01ef)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
**Symbols:**

```
ffffffff82fafc6d-ffffffff82fafcae: create_dev.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff831b9cd1)
Location: init/do_mounts.h:17
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_initrd.c (ffffffff831ba252)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
**Symbols:**

```
ffffffff831b9cd1-ffffffff831b9d11: create_dev.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff8329a170)
Location: init/do_mounts.h:17
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_initrd.c (ffffffff8329a710)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
**Symbols:**

```
ffffffff8329a170-ffffffff8329a1b0: create_dev.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff83448292)
Location: init/do_mounts.h:17
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_initrd.c (ffffffff83448a20)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
**Symbols:**

```
ffffffff83448292-ffffffff834482dc: create_dev.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff83e626f9)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_initrd.c (ffffffff83e629ad)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff83682b60)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_initrd.c (ffffffff83682f5d)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff838b1c10)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_initrd.c (ffffffff838b203d)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffff8000100856f8)
Location: init/do_mounts.h:17
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_initrd.c (ffff800011431c94)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffff8000114324bc)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
**Symbols:**

```
ffff8000100856f8-ffff800010085758: create_dev.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (c0303eac)
Location: init/do_mounts.h:17
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_initrd.c (c1501cd0)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (c150251c)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
**Symbols:**

```
c0303eac-c0303f08: create_dev.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (c000000000011344)
Location: init/do_mounts.h:17
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_initrd.c (c0000000013451d0)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (c000000001345ca8)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
**Symbols:**

```
c000000000011344-c0000000000113d4: create_dev.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffe0000b4aa2)
Location: init/do_mounts.h:17
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_initrd.c (ffffffe00000191e)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffe00000208c)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
**Symbols:**

```
ffffffe0000b4aa2-ffffffe0000b4b0e: create_dev.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff810030a4)
Location: init/do_mounts.h:17
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_initrd.c (ffffffff8288baf5)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff8288c31d)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
**Symbols:**

```
ffffffff810030a4-ffffffff810030f7: create_dev.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff81001584)
Location: init/do_mounts.h:17
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_initrd.c (ffffffff82889a72)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff8288a29a)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
**Symbols:**

```
ffffffff81001584-ffffffff810015d7: create_dev.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff810030a4)
Location: init/do_mounts.h:17
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_initrd.c (ffffffff8289eaf5)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff8289f31d)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
**Symbols:**

```
ffffffff810030a4-ffffffff810030f7: create_dev.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (ffffffff810030f4)
Location: init/do_mounts.h:17
Inline: True
Direct callers:
  - init/do_mounts.c:prepare_namespace
  - init/do_mounts.c:mount_root
```
```
In init/do_mounts_initrd.c (ffffffff8289eafa)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:initrd_load
```
```
In init/do_mounts_md.c (ffffffff8289f322)
Location: init/do_mounts.h:17
Inline: True
Inline callers:
  - init/do_mounts_md.c:md_run_setup
  - init/do_mounts_md.c:md_setup_drive
```
**Symbols:**

```
ffffffff810030f4-ffffffff81003147: create_dev.constprop.0 (STB_LOCAL)
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
</ul>
