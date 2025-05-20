# Function: <code>ratelimit_state_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81f9617b)
Location: include/linux/ratelimit.h:34
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff812fcd9c)
Location: include/linux/ratelimit.h:34
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810ddcef)
Location: include/linux/ratelimit.h:39
Inline: True
```
```
In fs/ext4/super.c (ffffffff812ed3fe)
Location: include/linux/ratelimit.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff81330a56)
Location: include/linux/ratelimit.h:39
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e42ff)
Location: include/linux/ratelimit.h:39
Inline: True
```
```
In fs/ext4/super.c (ffffffff813037ff)
Location: include/linux/ratelimit.h:39
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff813467a6)
Location: include/linux/ratelimit.h:39
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ratelimit_state_init(struct ratelimit_state *rs, int interval, int burst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e257f)
Location: include/linux/ratelimit.h:39
Inline: True
```
```
In fs/ext4/super.c (ffffffff81339047)
Location: include/linux/ratelimit.h:39
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff8135b1a8)
Location: include/linux/ratelimit.h:39
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/iommu/amd_iommu.c (ffffffff815c97f7)
Location: include/linux/ratelimit.h:39
Inline: True
```
**Symbols:**

```
ffffffff81339047-ffffffff8133906f: ratelimit_state_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ratelimit_state_init(struct ratelimit_state *rs, int interval, int burst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810ea35f)
Location: include/linux/ratelimit.h:40
Inline: True
```
```
In fs/ext4/super.c (ffffffff8135cd67)
Location: include/linux/ratelimit.h:40
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff8137fea8)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/iommu/amd_iommu.c (ffffffff8162feff)
Location: include/linux/ratelimit.h:40
Inline: True
```
**Symbols:**

```
ffffffff8135cd67-ffffffff8135cd8f: ratelimit_state_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ratelimit_state_init(struct ratelimit_state *rs, int interval, int burst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff8109bf77)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff810f290b)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/ext4/super.c (ffffffff8137d860)
Location: include/linux/ratelimit.h:40
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff813ae727)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/iommu/amd_iommu.c (ffffffff8166abf6)
Location: include/linux/ratelimit.h:40
Inline: True
```
**Symbols:**

```
ffffffff8137d860-ffffffff8137d88c: ratelimit_state_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ratelimit_state_init(struct ratelimit_state *rs, int interval, int burst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810a4177)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff810fdf4b)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/ext4/super.c (ffffffff81396010)
Location: include/linux/ratelimit.h:40
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff813c7921)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/iommu/amd_iommu.c (ffffffff81689300)
Location: include/linux/ratelimit.h:40
Inline: True
```
**Symbols:**

```
ffffffff81396010-ffffffff8139603c: ratelimit_state_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ratelimit_state_init(struct ratelimit_state *rs, int interval, int burst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810a8e57)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff8110667b)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/ext4/super.c (ffffffff813bffc0)
Location: include/linux/ratelimit.h:40
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff813f24e8)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/iommu/amd_iommu.c (ffffffff816c05de)
Location: include/linux/ratelimit.h:40
Inline: True
```
**Symbols:**

```
ffffffff813bffc0-ffffffff813bffed: ratelimit_state_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ratelimit_state_init(struct ratelimit_state *rs, int interval, int burst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810af427)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff81112a0b)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/ext4/super.c (ffffffff813d9290)
Location: include/linux/ratelimit.h:40
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff8140c3eb)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/iommu/amd_iommu.c (ffffffff816e362b)
Location: include/linux/ratelimit.h:40
Inline: True
```
**Symbols:**

```
ffffffff813d9290-ffffffff813d92bd: ratelimit_state_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ratelimit_state_init(struct ratelimit_state *rs, int interval, int burst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810b7137)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff8111e2cd)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/ext4/super.c (ffffffff81425cd0)
Location: include/linux/ratelimit.h:40
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff8145a49b)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/iommu/amd/iommu.c (ffffffff817957e2)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:alloc_dev_data
```
**Symbols:**

```
ffffffff81425cd0-ffffffff81425cfe: ratelimit_state_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ratelimit_state_init(struct ratelimit_state *rs, int interval, int burst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810b22f7)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff81118d5b)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/ext4/super.c (ffffffff8143d550)
Location: include/linux/ratelimit.h:9
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff814767eb)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/iommu/amd/iommu.c (ffffffff817a3d62)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:alloc_dev_data
```
**Symbols:**

```
ffffffff8143d550-ffffffff8143d57e: ratelimit_state_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ratelimit_state_init(struct ratelimit_state *rs, int interval, int burst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810b3937)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff8111930b)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/ext4/super.c (ffffffff81443390)
Location: include/linux/ratelimit.h:9
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff8147c25b)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/iommu/amd/iommu.c (ffffffff81787f9d)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff81443390-ffffffff814433be: ratelimit_state_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ratelimit_state_init(struct ratelimit_state *rs, int interval, int burst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff832ace8b)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:sld_state_setup
```
```
In kernel/user.c (ffffffff810c5b03)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff811396cb)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/ext4/super.c (ffffffff81497000)
Location: include/linux/ratelimit.h:9
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff814d395b)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/iommu/amd/iommu.c (ffffffff8180eb6d)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff81497000-ffffffff8149702e: ratelimit_state_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ratelimit_state_init(struct ratelimit_state *rs, int interval, int burst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8345dc42)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:sld_state_setup
```
```
In kernel/user.c (ffffffff810dd0fb)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff8115c19b)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/ext4/super.c (ffffffff815223d0)
Location: include/linux/ratelimit.h:9
Inline: True
Direct callers:
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff81560b9e)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/iommu/amd/iommu.c (ffffffff81950b96)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff815223d0-ffffffff81522408: ratelimit_state_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ratelimit_state_init(struct ratelimit_state *rs, int interval, int burst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff83e7ec39)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:sld_state_setup
```
```
In kernel/user.c (ffffffff810fd41b)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff8118ec2b)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/ext4/super.c (ffffffff83ecd715)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_fs
Direct callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff81602e5e)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/iommu/amd/iommu.c (ffffffff81ab5446)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff815bf1d0-ffffffff815bf208: ratelimit_state_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ratelimit_state_init(struct ratelimit_state *rs, int interval, int burst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff836a1999)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:sld_state_setup
```
```
In kernel/user.c (ffffffff8110944b)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff811a03bb)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/ext4/super.c (ffffffff836f27b5)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_fs
Direct callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff8163ad7e)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b01596)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff815f60d0-ffffffff815f6108: ratelimit_state_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ratelimit_state_init(struct ratelimit_state *rs, int interval, int burst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff838d1a99)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:sld_state_setup
```
```
In kernel/user.c (ffffffff81112de3)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff811af3db)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/ext4/super.c (ffffffff83925955)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_fs
Direct callers:
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff816742dd)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/iommu/amd/iommu.c (ffffffff81b54653)
Location: include/linux/ratelimit.h:9
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:iommu_init_device
```
**Symbols:**

```
ffffffff8162e9f0-ffffffff8162ea28: ratelimit_state_init (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ratelimit_state_init(struct ratelimit_state *rs, int interval, int burst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffff80001010a578)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffff8000101732b0)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/ext4/super.c (ffff8000104ac948)
Location: include/linux/ratelimit.h:40
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffff8000104ed2b4)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
ffff8000104ac948-ffff8000104ac95c: ratelimit_state_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ratelimit_state_init(struct ratelimit_state *rs, int interval, int burst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user.c (c0363560)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (c03c5690)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/ext4/super.c (c0674f64)
Location: include/linux/ratelimit.h:40
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (c06aae28)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
c0674f64-c0674f94: ratelimit_state_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ratelimit_state_init(struct ratelimit_state *rs, int interval, int burst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user.c (c00000000015156c)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (c0000000001cdbc0)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/ext4/super.c (c0000000005e48c0)
Location: include/linux/ratelimit.h:40
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (c00000000062be30)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
**Symbols:**

```
c0000000005e48c0-c0000000005e48e4: ratelimit_state_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffe0000ccfa8)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffe00010f136)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/ext4/super.c (ffffffe000022214)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffe00035d6e0)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ratelimit_state_init(struct ratelimit_state *rs, int interval, int burst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810a9797)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff8110afeb)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/ext4/super.c (ffffffff813d1870)
Location: include/linux/ratelimit.h:40
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff814049cb)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/iommu/amd_iommu.c (ffffffff816a907b)
Location: include/linux/ratelimit.h:40
Inline: True
```
**Symbols:**

```
ffffffff813d1870-ffffffff813d189d: ratelimit_state_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ratelimit_state_init(struct ratelimit_state *rs, int interval, int burst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff81098151)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff810fbe7b)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/ext4/super.c (ffffffff813c22f0)
Location: include/linux/ratelimit.h:40
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff813f544b)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/iommu/amd_iommu.c (ffffffff81686a6b)
Location: include/linux/ratelimit.h:40
Inline: True
```
**Symbols:**

```
ffffffff813c22f0-ffffffff813c231d: ratelimit_state_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ratelimit_state_init(struct ratelimit_state *rs, int interval, int burst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810a8cf7)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff81108edb)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/ext4/super.c (ffffffff813ced00)
Location: include/linux/ratelimit.h:40
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff81401d4b)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/iommu/amd_iommu.c (ffffffff816d72eb)
Location: include/linux/ratelimit.h:40
Inline: True
```
**Symbols:**

```
ffffffff813ced00-ffffffff813ced2d: ratelimit_state_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void ratelimit_state_init(struct ratelimit_state *rs, int interval, int burst);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810b0de7)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff8111410b)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/ext4/super.c (ffffffff813e3f50)
Location: include/linux/ratelimit.h:40
Inline: False
Direct callers:
  - fs/ext4/super.c:ext4_init_fs
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
```
```
In fs/fat/inode.c (ffffffff81417d1b)
Location: include/linux/ratelimit.h:40
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
```
```
In drivers/iommu/amd_iommu.c (ffffffff816f189b)
Location: include/linux/ratelimit.h:40
Inline: True
```
**Symbols:**

```
ffffffff813e3f50-ffffffff813e3f7d: ratelimit_state_init (STB_LOCAL)
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
