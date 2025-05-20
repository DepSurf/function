# Function: <code>nd_label_gen_id</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
char *nd_label_gen_id(struct nd_label_id *label_id, u8 *uuid, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8159f540)
Location: drivers/nvdimm/label.c:246
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
  - drivers/nvdimm/label.c:__blk_label_update
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
```
**Symbols:**

```
ffffffff8159f540-ffffffff8159f589: nd_label_gen_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
char *nd_label_gen_id(struct nd_label_id *label_id, u8 *uuid, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff815f5d77)
Location: drivers/nvdimm/label.c:246
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
```
**Symbols:**

```
ffffffff815f5570-ffffffff815f55b9: nd_label_gen_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
char *nd_label_gen_id(struct nd_label_id *label_id, u8 *uuid, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816245d8)
Location: drivers/nvdimm/label.c:246
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
```
**Symbols:**

```
ffffffff81623230-ffffffff81623279: nd_label_gen_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
char *nd_label_gen_id(struct nd_label_id *label_id, u8 *uuid, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8163971a)
Location: drivers/nvdimm/label.c:311
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
```
**Symbols:**

```
ffffffff81637f40-ffffffff81637f8a: nd_label_gen_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
char *nd_label_gen_id(struct nd_label_id *label_id, u8 *uuid, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816a1df8)
Location: drivers/nvdimm/label.c:313
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:nd_pmem_namespace_label_update
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
```
**Symbols:**

```
ffffffff816a0640-ffffffff816a068a: nd_label_gen_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
char *nd_label_gen_id(struct nd_label_id *label_id, u8 *uuid, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816dd7ac)
Location: drivers/nvdimm/label.c:322
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
```
**Symbols:**

```
ffffffff816dc940-ffffffff816dc98e: nd_label_gen_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
char *nd_label_gen_id(struct nd_label_id *label_id, u8 *uuid, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816ffb0c)
Location: drivers/nvdimm/label.c:330
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
```
**Symbols:**

```
ffffffff816fe510-ffffffff816fe55e: nd_label_gen_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
char *nd_label_gen_id(struct nd_label_id *label_id, u8 *uuid, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff817398e7)
Location: drivers/nvdimm/label.c:324
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
```
**Symbols:**

```
ffffffff817386b0-ffffffff81738702: nd_label_gen_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
char *nd_label_gen_id(struct nd_label_id *label_id, u8 *uuid, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8175d637)
Location: drivers/nvdimm/label.c:324
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
```
**Symbols:**

```
ffffffff8175c390-ffffffff8175c3e2: nd_label_gen_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
char *nd_label_gen_id(struct nd_label_id *label_id, u8 *uuid, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8181cf7c)
Location: drivers/nvdimm/label.c:324
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:__nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size
```
**Symbols:**

```
ffffffff8181bba0-ffffffff8181bbf6: nd_label_gen_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
char *nd_label_gen_id(struct nd_label_id *label_id, u8 *uuid, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8182bfdf)
Location: drivers/nvdimm/label.c:324
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:__nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size
```
**Symbols:**

```
ffffffff8182abf0-ffffffff8182ac46: nd_label_gen_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
char *nd_label_gen_id(struct nd_label_id *label_id, u8 *uuid, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8180f2e7)
Location: drivers/nvdimm/label.c:324
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size
```
**Symbols:**

```
ffffffff8180dec0-ffffffff8180df16: nd_label_gen_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
char *nd_label_gen_id(struct nd_label_id *label_id, u8 *uuid, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81899877)
Location: drivers/nvdimm/label.c:324
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size
```
**Symbols:**

```
ffffffff818984b0-ffffffff81898506: nd_label_gen_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
char *nd_label_gen_id(struct nd_label_id *label_id, const uuid_t *uuid, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff819e31fe)
Location: drivers/nvdimm/label.c:332
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
```
**Symbols:**

```
ffffffff819e23b0-ffffffff819e2407: nd_label_gen_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
char *nd_label_gen_id(struct nd_label_id *label_id, const uuid_t *uuid, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81b5ee65)
Location: drivers/nvdimm/label.c:332
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
```
**Symbols:**

```
ffffffff81b5e000-ffffffff81b5e057: nd_label_gen_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
char *nd_label_gen_id(struct nd_label_id *label_id, const uuid_t *uuid, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81bb2404)
Location: drivers/nvdimm/label.c:332
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
```
**Symbols:**

```
ffffffff81bb15c0-ffffffff81bb1617: nd_label_gen_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
char *nd_label_gen_id(struct nd_label_id *label_id, const uuid_t *uuid, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81c068f4)
Location: drivers/nvdimm/label.c:332
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
```
**Symbols:**

```
ffffffff81c05ab0-ffffffff81c05b07: nd_label_gen_id (STB_GLOBAL)
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
char *nd_label_gen_id(struct nd_label_id *label_id, u8 *uuid, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffff80001095ed78)
Location: drivers/nvdimm/label.c:324
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
```
**Symbols:**

```
ffff80001095da88-ffff80001095db14: nd_label_gen_id (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
char *nd_label_gen_id(struct nd_label_id *label_id, u8 *uuid, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (c000000000a11184)
Location: drivers/nvdimm/label.c:324
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size
```
**Symbols:**

```
c000000000a0f590-c000000000a0f634: nd_label_gen_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
char *nd_label_gen_id(struct nd_label_id *label_id, u8 *uuid, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffe0005ccbb8)
Location: drivers/nvdimm/label.c:324
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_size
```
**Symbols:**

```
ffffffe0005cbba6-ffffffe0005cbc1e: nd_label_gen_id (STB_GLOBAL)
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
char *nd_label_gen_id(struct nd_label_id *label_id, u8 *uuid, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81711d27)
Location: drivers/nvdimm/label.c:324
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
```
**Symbols:**

```
ffffffff81710a80-ffffffff81710ad2: nd_label_gen_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
char *nd_label_gen_id(struct nd_label_id *label_id, u8 *uuid, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff816e57a7)
Location: drivers/nvdimm/label.c:324
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
```
**Symbols:**

```
ffffffff816e4500-ffffffff816e4552: nd_label_gen_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
char *nd_label_gen_id(struct nd_label_id *label_id, u8 *uuid, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff81750af7)
Location: drivers/nvdimm/label.c:324
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
```
**Symbols:**

```
ffffffff8174f850-ffffffff8174f8a2: nd_label_gen_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
char *nd_label_gen_id(struct nd_label_id *label_id, u8 *uuid, u32 flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/label.c (ffffffff8176bf77)
Location: drivers/nvdimm/label.c:324
Inline: True
Inline callers:
  - drivers/nvdimm/label.c:__blk_label_update
  - drivers/nvdimm/label.c:__pmem_label_update
  - drivers/nvdimm/label.c:nd_label_reserve_dpa
Direct callers:
  - drivers/nvdimm/namespace_devs.c:nsblk_add_resource
  - drivers/nvdimm/namespace_devs.c:dpa_extents_show
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:namespace_update_uuid
  - drivers/nvdimm/namespace_devs.c:__size_store
  - drivers/nvdimm/namespace_devs.c:nd_namespace_pmem_set_resource
  - drivers/nvdimm/namespace_devs.c:nd_namespace_blk_validate
```
**Symbols:**

```
ffffffff8176acd0-ffffffff8176ad22: nd_label_gen_id (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>u8 *uuid</code> ➡️ <code>const uuid_t *uuid</code>
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
