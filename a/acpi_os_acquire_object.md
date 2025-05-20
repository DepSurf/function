# Function: <code>acpi_os_acquire_object</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_acquire_object(struct kmem_cache *cache);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff8149c204)
Location: include/acpi/platform/aclinuxex.h:99
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff814a23b5)
Location: include/acpi/platform/aclinuxex.h:99
Inline: False
Direct callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/utobject.c (ffffffff814a91c4)
Location: include/acpi/platform/aclinuxex.h:99
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff814a9e54)
Location: include/acpi/platform/aclinuxex.h:99
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
**Symbols:**

```
ffffffff814a23b5-ffffffff814a23e4: acpi_os_acquire_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_acquire_object(struct kmem_cache *cache);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff814eb284)
Location: include/acpi/platform/aclinuxex.h:99
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff814f16e2)
Location: include/acpi/platform/aclinuxex.h:99
Inline: False
Direct callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/utobject.c (ffffffff814f845a)
Location: include/acpi/platform/aclinuxex.h:99
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff814f90fe)
Location: include/acpi/platform/aclinuxex.h:99
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
**Symbols:**

```
ffffffff814f16e2-ffffffff814f1711: acpi_os_acquire_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_acquire_object(struct kmem_cache *cache);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff8150db0c)
Location: include/acpi/platform/aclinuxex.h:99
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff81514143)
Location: include/acpi/platform/aclinuxex.h:99
Inline: False
Direct callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8151ae68)
Location: include/acpi/platform/aclinuxex.h:99
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff8151bb15)
Location: include/acpi/platform/aclinuxex.h:99
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
**Symbols:**

```
ffffffff81514143-ffffffff81514172: acpi_os_acquire_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_acquire_object(struct kmem_cache *cache);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff8151e1b8)
Location: include/acpi/platform/aclinuxex.h:99
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff815248df)
Location: include/acpi/platform/aclinuxex.h:99
Inline: False
Direct callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8152b683)
Location: include/acpi/platform/aclinuxex.h:99
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff8152c329)
Location: include/acpi/platform/aclinuxex.h:99
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
**Symbols:**

```
ffffffff815248df-ffffffff8152490e: acpi_os_acquire_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_acquire_object(struct kmem_cache *cache);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff8156f784)
Location: include/acpi/platform/aclinuxex.h:99
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff8157a528)
Location: include/acpi/platform/aclinuxex.h:99
Inline: False
Direct callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/utobject.c (ffffffff815856e1)
Location: include/acpi/platform/aclinuxex.h:99
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff81586b09)
Location: include/acpi/platform/aclinuxex.h:99
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
**Symbols:**

```
ffffffff8157a528-ffffffff8157a557: acpi_os_acquire_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_acquire_object(struct kmem_cache *cache);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff815a645f)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff815b161c)
Location: include/acpi/platform/aclinuxex.h:65
Inline: False
Direct callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/utobject.c (ffffffff815bc897)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff815bdcb2)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
**Symbols:**

```
ffffffff815b161c-ffffffff815b164b: acpi_os_acquire_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_acquire_object(struct kmem_cache *cache);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff815bf1a4)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff815ca75c)
Location: include/acpi/platform/aclinuxex.h:65
Inline: False
Direct callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/utobject.c (ffffffff815d5cdd)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff815d70fd)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
**Symbols:**

```
ffffffff815ca75c-ffffffff815ca78b: acpi_os_acquire_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_acquire_object(struct kmem_cache *cache);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff815f0e00)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff815fbf0b)
Location: include/acpi/platform/aclinuxex.h:65
Inline: False
Direct callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/utobject.c (ffffffff81607680)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff81608ae1)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
**Symbols:**

```
ffffffff815fbf0b-ffffffff815fbf3a: acpi_os_acquire_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_acquire_object(struct kmem_cache *cache);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff8161228e)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff8161d3b5)
Location: include/acpi/platform/aclinuxex.h:65
Inline: False
Direct callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/utobject.c (ffffffff81628b1b)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff81629f86)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
**Symbols:**

```
ffffffff8161d3b5-ffffffff8161d3e4: acpi_os_acquire_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_acquire_object(struct kmem_cache *cache);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff816be7bb)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff816c993e)
Location: include/acpi/platform/aclinuxex.h:65
Inline: False
Direct callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/utobject.c (ffffffff816d53c4)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff816d6765)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
**Symbols:**

```
ffffffff816c993e-ffffffff816c996d: acpi_os_acquire_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_acquire_object(struct kmem_cache *cache);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff816dc329)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff816e7964)
Location: include/acpi/platform/aclinuxex.h:65
Inline: False
Direct callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/utobject.c (ffffffff816f3380)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff816f4710)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
**Symbols:**

```
ffffffff816e7964-ffffffff816e7993: acpi_os_acquire_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_acquire_object(struct kmem_cache *cache);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff816be201)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff816c9827)
Location: include/acpi/platform/aclinuxex.h:65
Inline: False
Direct callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/utobject.c (ffffffff816d513f)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff816d65ae)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
**Symbols:**

```
ffffffff816c9827-ffffffff816c9856: acpi_os_acquire_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_acquire_object(struct kmem_cache *cache);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff81735490)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff81740bc9)
Location: include/acpi/platform/aclinuxex.h:65
Inline: False
Direct callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8174cb66)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff8174e11a)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
**Symbols:**

```
ffffffff81740bc9-ffffffff81740bf8: acpi_os_acquire_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_acquire_object(struct kmem_cache *cache);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff818664d1)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff81872563)
Location: include/acpi/platform/aclinuxex.h:65
Inline: False
Direct callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8187f27b)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff8188098e)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
**Symbols:**

```
ffffffff81872563-ffffffff81872599: acpi_os_acquire_object (STB_LOCAL)
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
In drivers/acpi/acpica/nsalloc.c (ffffffff819a49d3)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff819b340a)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/utobject.c (ffffffff819c3148)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff819c4e85)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
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
In drivers/acpi/acpica/nsalloc.c (ffffffff819eb6a3)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff819fa30a)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/utobject.c (ffffffff81a0a4e8)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff81a0c285)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
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
In drivers/acpi/acpica/nsalloc.c (ffffffff81a36463)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff81a4515a)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/utobject.c (ffffffff81a55488)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff81a57255)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
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
void *acpi_os_acquire_object(struct kmem_cache *cache);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffff80001078c188)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffff800010793d04)
Location: include/acpi/platform/aclinuxex.h:65
Inline: False
Direct callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/utobject.c (ffff80001079d5c8)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffff80001079e59c)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
**Symbols:**

```
ffff800010793d04-ffff800010793d34: acpi_os_acquire_object (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_acquire_object(struct kmem_cache *cache);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff815f25da)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff815f9185)
Location: include/acpi/platform/aclinuxex.h:65
Inline: False
Direct callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/utobject.c (ffffffff81600466)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff816010d7)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
**Symbols:**

```
ffffffff815f9185-ffffffff815f91b4: acpi_os_acquire_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_acquire_object(struct kmem_cache *cache);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff815ddb6d)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff815e46c4)
Location: include/acpi/platform/aclinuxex.h:65
Inline: False
Direct callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/utobject.c (ffffffff815eb933)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff815ec597)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
**Symbols:**

```
ffffffff815e46c4-ffffffff815e46ee: acpi_os_acquire_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_acquire_object(struct kmem_cache *cache);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff8160656e)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff81611695)
Location: include/acpi/platform/aclinuxex.h:65
Inline: False
Direct callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/utobject.c (ffffffff8161cdfb)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff8161e266)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
**Symbols:**

```
ffffffff81611695-ffffffff816116c4: acpi_os_acquire_object (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void *acpi_os_acquire_object(struct kmem_cache *cache);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/acpi/acpica/nsalloc.c (ffffffff8162041e)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/nsalloc.c:acpi_ns_create_node
```
```
In drivers/acpi/acpica/psutils.c (ffffffff8162b545)
Location: include/acpi/platform/aclinuxex.h:65
Inline: False
Direct callers:
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
  - drivers/acpi/acpica/psutils.c:acpi_ps_alloc_op
```
```
In drivers/acpi/acpica/utobject.c (ffffffff81636cab)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utobject.c:acpi_ut_allocate_object_desc_dbg
```
```
In drivers/acpi/acpica/utstate.c (ffffffff81638116)
Location: include/acpi/platform/aclinuxex.h:65
Inline: True
Inline callers:
  - drivers/acpi/acpica/utstate.c:acpi_ut_create_generic_state
```
**Symbols:**

```
ffffffff8162b545-ffffffff8162b574: acpi_os_acquire_object (STB_LOCAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
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
