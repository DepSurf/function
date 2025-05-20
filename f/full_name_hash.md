# Function: <code>full_name_hash</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
unsigned int full_name_hash(const unsigned char *name, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81218010)
Location: fs/namei.c:1806
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len
  - fs/dcache.c:d_alloc_name
  - fs/dcache.c:d_hash_and_lookup
  - fs/fat/namei_vfat.c:vfat_hash
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dev.c:fuse_notify
  - fs/fuse/dir.c:fuse_readdir
  - security/smack/smack_access.c:smk_insert_entry
  - security/smack/smack_access.c:smk_find_entry
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/util.c:tomoyo_fill_path_info
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:dev_change_name
```
**Symbols:**

```
ffffffff81218010-ffffffff81218063: full_name_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
unsigned int full_name_hash(const void *salt, const char *name, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123efc0)
Location: fs/namei.c:1909
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/dcache.c:d_hash_and_lookup
  - fs/fat/namei_vfat.c:vfat_hash
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/smack/smack_access.c:smk_find_entry
  - security/smack/smack_access.c:smk_insert_entry
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/util.c:tomoyo_fill_path_info
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
**Symbols:**

```
ffffffff8123efc0-ffffffff8123f04c: full_name_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
unsigned int full_name_hash(const void *salt, const char *name, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81251d90)
Location: fs/namei.c:1902
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/dcache.c:d_hash_and_lookup
  - fs/fat/namei_vfat.c:vfat_hash
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/smack/smack_access.c:smk_find_entry
  - security/smack/smack_access.c:smk_insert_entry
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/util.c:tomoyo_fill_path_info
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
**Symbols:**

```
ffffffff81251d90-ffffffff81251e1c: full_name_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
unsigned int full_name_hash(const void *salt, const char *name, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125da50)
Location: fs/namei.c:1912
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/dcache.c:d_hash_and_lookup
  - fs/fat/namei_vfat.c:vfat_hash
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/smack/smack_access.c:smk_find_entry
  - security/smack/smack_access.c:smk_insert_entry
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/util.c:tomoyo_fill_path_info
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
**Symbols:**

```
ffffffff8125da50-ffffffff8125dae0: full_name_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
unsigned int full_name_hash(const void *salt, const char *name, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8127fda0)
Location: fs/namei.c:1910
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one_len
  - fs/dcache.c:d_hash_and_lookup
  - fs/fat/namei_vfat.c:vfat_hash
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/smack/smack_access.c:smk_find_entry
  - security/smack/smack_access.c:smk_insert_entry
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/util.c:tomoyo_fill_path_info
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
**Symbols:**

```
ffffffff8127fda0-ffffffff8127fe30: full_name_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
unsigned int full_name_hash(const void *salt, const char *name, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a6330)
Location: fs/namei.c:1897
Inline: False
Direct callers:
  - fs/dcache.c:d_hash_and_lookup
  - fs/fat/namei_vfat.c:vfat_hash
  - fs/fuse/dir.c:fuse_readdir
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/smack/smack_access.c:smk_find_entry
  - security/smack/smack_access.c:smk_insert_entry
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/util.c:tomoyo_fill_path_info
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
**Symbols:**

```
ffffffff812a6330-ffffffff812a63c3: full_name_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int full_name_hash(const void *salt, const char *name, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bb3c0)
Location: fs/namei.c:1938
Inline: False
Direct callers:
  - fs/dcache.c:d_hash_and_lookup
  - fs/fat/namei_vfat.c:vfat_hash
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/readdir.c:fuse_readdir
  - security/smack/smack_access.c:smk_find_entry
  - security/smack/smack_access.c:smk_insert_entry
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/util.c:tomoyo_fill_path_info
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
**Symbols:**

```
ffffffff812bb3c0-ffffffff812bb453: full_name_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int full_name_hash(const void *salt, const char *name, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d8000)
Location: fs/namei.c:1936
Inline: False
Direct callers:
  - fs/dcache.c:d_hash_and_lookup
  - fs/ext4/dir.c:ext4_d_hash
  - fs/fat/namei_vfat.c:vfat_hash
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/smack/smack_access.c:smk_find_entry
  - security/smack/smack_access.c:smk_insert_entry
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/util.c:tomoyo_fill_path_info
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
**Symbols:**

```
ffffffff812d8000-ffffffff812d8093: full_name_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int full_name_hash(const void *salt, const char *name, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e9b70)
Location: fs/namei.c:1929
Inline: False
Direct callers:
  - fs/dcache.c:d_hash_and_lookup
  - fs/ext4/dir.c:ext4_d_hash
  - fs/fat/namei_vfat.c:vfat_hash
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/smack/smack_access.c:smk_find_entry
  - security/smack/smack_access.c:smk_insert_entry
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/util.c:tomoyo_fill_path_info
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
**Symbols:**

```
ffffffff812e9b70-ffffffff812e9c03: full_name_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int full_name_hash(const void *salt, const char *name, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81321c00)
Location: fs/namei.c:1975
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_common
  - fs/dcache.c:d_hash_and_lookup
  - fs/ext4/dir.c:ext4_d_hash
  - fs/fat/namei_vfat.c:vfat_hash
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/ss/context.c:context_compute_hash
  - security/smack/smack_access.c:smk_find_entry
  - security/smack/smack_access.c:smk_insert_entry
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/util.c:tomoyo_fill_path_info
  - net/core/dev.c:netdev_name_node_alt_create
  - net/core/dev.c:netdev_name_node_lookup_rcu
  - net/core/dev.c:netdev_name_node_lookup
```
**Symbols:**

```
ffffffff81321c00-ffffffff81321c94: full_name_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int full_name_hash(const void *salt, const char *name, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132d1c0)
Location: fs/namei.c:1971
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_common
  - fs/dcache.c:d_hash_and_lookup
  - fs/fat/namei_vfat.c:vfat_hash
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/ss/context.c:context_compute_hash
  - security/smack/smack_access.c:smk_find_entry
  - security/smack/smack_access.c:smk_insert_entry
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/util.c:tomoyo_fill_path_info
  - net/core/dev.c:netdev_name_node_alt_create
  - net/core/dev.c:netdev_name_node_lookup_rcu
  - net/core/dev.c:netdev_name_node_lookup
```
**Symbols:**

```
ffffffff8132d1c0-ffffffff8132d254: full_name_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int full_name_hash(const void *salt, const char *name, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81332cb0)
Location: fs/namei.c:2057
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_common
  - fs/dcache.c:d_hash_and_lookup
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_name_event
  - fs/notify/fanotify/fanotify.c:fanotify_encode_fh
  - fs/fat/namei_vfat.c:vfat_hash
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/ss/context.c:context_compute_hash
  - security/smack/smack_access.c:smk_find_entry
  - security/smack/smack_access.c:smk_insert_entry
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/util.c:tomoyo_fill_path_info
  - net/core/dev.c:netdev_name_node_alt_create
  - net/core/dev.c:netdev_name_node_lookup_rcu
  - net/core/dev.c:netdev_name_node_lookup
```
**Symbols:**

```
ffffffff81332cb0-ffffffff81332d48: full_name_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int full_name_hash(const void *salt, const char *name, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81380440)
Location: fs/namei.c:2085
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_common
  - fs/dcache.c:d_hash_and_lookup
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_name_event
  - fs/notify/fanotify/fanotify.c:fanotify_encode_fh
  - fs/fat/namei_vfat.c:vfat_hash
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/ss/context.c:context_compute_hash
  - security/smack/smack_access.c:smk_find_entry
  - security/smack/smack_access.c:smk_insert_entry
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/util.c:tomoyo_fill_path_info
  - net/core/dev.c:netdev_name_node_alt_create
  - net/core/dev.c:netdev_name_node_lookup_rcu
  - net/core/dev.c:netdev_name_node_lookup
```
**Symbols:**

```
ffffffff81380440-ffffffff813804d8: full_name_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int full_name_hash(const void *salt, const char *name, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814003c0)
Location: fs/namei.c:2131
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_common
  - fs/dcache.c:d_hash_and_lookup
  - fs/notify/fanotify/fanotify.c:fanotify_encode_fh
  - fs/fat/namei_vfat.c:vfat_hash
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/ss/context.c:context_compute_hash
  - security/smack/smack_access.c:smk_find_entry
  - security/smack/smack_access.c:smk_insert_entry
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/util.c:tomoyo_fill_path_info
  - net/core/dev.c:dev_get_mac_address
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_create
  - net/core/dev.c:netdev_name_node_lookup
```
**Symbols:**

```
ffffffff814003c0-ffffffff81400486: full_name_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int full_name_hash(const void *salt, const char *name, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81489840)
Location: fs/namei.c:2108
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_common
  - fs/dcache.c:d_hash_and_lookup
  - fs/notify/fanotify/fanotify.c:fanotify_encode_fh
  - fs/fat/namei_vfat.c:vfat_hash
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/ss/context.c:context_compute_hash
  - security/smack/smack_access.c:smk_find_entry
  - security/smack/smack_access.c:smk_insert_entry
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/util.c:tomoyo_fill_path_info
  - net/core/dev.c:dev_get_mac_address
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_create
  - net/core/dev.c:netdev_name_node_lookup
```
**Symbols:**

```
ffffffff81489840-ffffffff814898e5: full_name_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int full_name_hash(const void *salt, const char *name, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814be770)
Location: fs/namei.c:2113
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_common
  - fs/dcache.c:d_hash_and_lookup
  - fs/notify/fanotify/fanotify.c:fanotify_encode_fh
  - fs/fat/namei_vfat.c:vfat_hash
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/ss/context.c:context_compute_hash
  - security/smack/smack_access.c:smk_find_entry
  - security/smack/smack_access.c:smk_insert_entry
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/util.c:tomoyo_fill_path_info
  - net/core/dev.c:default_device_exit_net
  - net/core/dev.c:dev_get_mac_address
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:netdev_get_by_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_create
```
**Symbols:**

```
ffffffff814be770-ffffffff814be815: full_name_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int full_name_hash(const void *salt, const char *name, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f0bf0)
Location: fs/namei.c:2120
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_common
  - fs/dcache.c:d_hash_and_lookup
  - fs/notify/fanotify/fanotify.c:fanotify_encode_fh
  - fs/fat/namei_vfat.c:vfat_hash
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/selinux/ss/policydb.c:filenametr_hash
  - security/selinux/ss/context.c:context_compute_hash
  - security/smack/smack_access.c:smk_find_entry
  - security/smack/smack_access.c:smk_insert_entry
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/util.c:tomoyo_fill_path_info
  - net/core/dev.c:default_device_exit_net
  - net/core/dev.c:dev_get_mac_address
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:netdev_get_by_name
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:list_netdevice
  - net/core/dev.c:netdev_name_node_alt_create
```
**Symbols:**

```
ffffffff814f0bf0-ffffffff814f0c95: full_name_hash (STB_GLOBAL)
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
unsigned int full_name_hash(const void *salt, const char *name, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010391bb0)
Location: fs/namei.c:1929
Inline: False
Direct callers:
  - fs/dcache.c:d_hash_and_lookup
  - fs/ext4/dir.c:ext4_d_hash
  - fs/fat/namei_vfat.c:vfat_hash
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/readdir.c:parse_dirplusfile
  - security/smack/smack_access.c:smk_find_entry
  - security/smack/smack_access.c:smk_insert_entry
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/util.c:tomoyo_fill_path_info
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
**Symbols:**

```
ffff800010391bb0-ffff800010391c90: full_name_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int full_name_hash(const void *salt, const char *name, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c05782fc)
Location: fs/namei.c:1929
Inline: False
Direct callers:
  - fs/dcache.c:d_hash_and_lookup
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/ext4/dir.c:ext4_d_hash
  - fs/fat/namei_vfat.c:vfat_hash
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/readdir.c:parse_dirplusfile
  - security/smack/smack_access.c:smk_find_entry
  - security/smack/smack_access.c:smk_insert_entry
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/util.c:tomoyo_fill_path_info
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
**Symbols:**

```
c05782fc-c05783a8: full_name_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int full_name_hash(const void *salt, const char *name, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000489b30)
Location: fs/namei.c:1929
Inline: False
Direct callers:
  - fs/dcache.c:d_hash_and_lookup
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/ext4/dir.c:ext4_d_hash
  - fs/fat/namei_vfat.c:vfat_hash
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/readdir.c:parse_dirplusfile
  - security/smack/smack_access.c:smk_find_entry
  - security/smack/smack_access.c:smk_insert_entry
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/util.c:tomoyo_fill_path_info
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
**Symbols:**

```
c000000000489b30-c000000000489c30: full_name_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
unsigned int full_name_hash(const void *salt, const char *name, unsigned int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe0002633ba)
Location: fs/namei.c:2006
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len_common
Direct callers:
  - fs/dcache.c:d_hash_and_lookup
  - fs/proc/proc_sysctl.c:proc_sys_fill_cache
  - fs/ext4/dir.c:ext4_d_hash
  - fs/fat/namei_vfat.c:vfat_hash
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - fs/fuse/readdir.c:fuse_readdir_uncached
  - security/smack/smack_access.c:smk_find_entry
  - security/smack/smack_access.c:smk_insert_entry
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/util.c:tomoyo_fill_path_info
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
**Symbols:**

```
ffffffe000260e96-ffffffe000260f02: full_name_hash (STB_GLOBAL)
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
unsigned int full_name_hash(const void *salt, const char *name, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e2150)
Location: fs/namei.c:1929
Inline: False
Direct callers:
  - fs/dcache.c:d_hash_and_lookup
  - fs/ext4/dir.c:ext4_d_hash
  - fs/fat/namei_vfat.c:vfat_hash
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/smack/smack_access.c:smk_find_entry
  - security/smack/smack_access.c:smk_insert_entry
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/util.c:tomoyo_fill_path_info
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
**Symbols:**

```
ffffffff812e2150-ffffffff812e21e3: full_name_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int full_name_hash(const void *salt, const char *name, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d2d90)
Location: fs/namei.c:1929
Inline: False
Direct callers:
  - fs/dcache.c:d_hash_and_lookup
  - fs/ext4/dir.c:ext4_d_hash
  - fs/fat/namei_vfat.c:vfat_hash
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/smack/smack_access.c:smk_find_entry
  - security/smack/smack_access.c:smk_insert_entry
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/util.c:tomoyo_fill_path_info
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
**Symbols:**

```
ffffffff812d2d90-ffffffff812d2e23: full_name_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int full_name_hash(const void *salt, const char *name, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dff60)
Location: fs/namei.c:1929
Inline: False
Direct callers:
  - fs/dcache.c:d_hash_and_lookup
  - fs/fat/namei_vfat.c:vfat_hash
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/smack/smack_access.c:smk_find_entry
  - security/smack/smack_access.c:smk_insert_entry
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/util.c:tomoyo_fill_path_info
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
**Symbols:**

```
ffffffff812dff60-ffffffff812dfff3: full_name_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int full_name_hash(const void *salt, const char *name, unsigned int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f1700)
Location: fs/namei.c:1929
Inline: False
Direct callers:
  - fs/dcache.c:d_hash_and_lookup
  - fs/ext4/dir.c:ext4_d_hash
  - fs/fat/namei_vfat.c:vfat_hash
  - fs/fuse/dir.c:fuse_reverse_inval_entry
  - security/smack/smack_access.c:smk_find_entry
  - security/smack/smack_access.c:smk_insert_entry
  - security/tomoyo/memory.c:tomoyo_get_name
  - security/tomoyo/util.c:tomoyo_fill_path_info
  - net/core/dev.c:dev_change_name
  - net/core/dev.c:dev_get_by_name_rcu
  - net/core/dev.c:__dev_get_by_name
  - net/core/dev.c:list_netdevice
```
**Symbols:**

```
ffffffff812f1700-ffffffff812f1793: full_name_hash (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const void *salt</code>
</li>
<li>
<b>Param reordered. </b>
<code>name, len</code> ➡️ <code>salt, name, len</code>
</li>
<li>
<b>Param type changed. </b>
<code>const unsigned char *name</code> ➡️ <code>const char *name</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
