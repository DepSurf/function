# Function: <code>get_vm_area</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct vm_struct *get_vm_area(long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811cebb0)
Location: mm/vmalloc.c:1389
Inline: False
```
**Symbols:**

```
ffffffff811cebb0-ffffffff811cebf6: get_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct vm_struct *get_vm_area(long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811ebd50)
Location: mm/vmalloc.c:1413
Inline: False
```
**Symbols:**

```
ffffffff811ebd50-ffffffff811ebd97: get_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct vm_struct *get_vm_area(long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff811fcf80)
Location: mm/vmalloc.c:1396
Inline: False
```
**Symbols:**

```
ffffffff811fcf80-ffffffff811fcfc7: get_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct vm_struct *get_vm_area(long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81207c90)
Location: mm/vmalloc.c:1447
Inline: False
```
**Symbols:**

```
ffffffff81207c90-ffffffff81207ccb: get_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct vm_struct *get_vm_area(long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81220d80)
Location: mm/vmalloc.c:1445
Inline: False
```
**Symbols:**

```
ffffffff81220d80-ffffffff81220dbb: get_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct vm_struct *get_vm_area(long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81242c20)
Location: mm/vmalloc.c:1432
Inline: False
```
**Symbols:**

```
ffffffff81242c20-ffffffff81242c5b: get_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct vm_struct *get_vm_area(long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81256820)
Location: mm/vmalloc.c:1433
Inline: False
```
**Symbols:**

```
ffffffff81256820-ffffffff8125685b: get_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct vm_struct *get_vm_area(long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126a370)
Location: mm/vmalloc.c:2096
Inline: False
```
**Symbols:**

```
ffffffff8126a370-ffffffff8126a3ab: get_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct vm_struct *get_vm_area(long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81279280)
Location: mm/vmalloc.c:2102
Inline: False
```
**Symbols:**

```
ffffffff81279280-ffffffff812792bb: get_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct vm_struct *get_vm_area(long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812aa1f0)
Location: mm/vmalloc.c:2147
Inline: False
```
**Symbols:**

```
ffffffff812aa1f0-ffffffff812aa24b: get_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct vm_struct *get_vm_area(long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b5320)
Location: mm/vmalloc.c:2129
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_valloc
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
```
**Symbols:**

```
ffffffff812b5320-ffffffff812b537b: get_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct vm_struct *get_vm_area(long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ba710)
Location: mm/vmalloc.c:2403
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_valloc
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
```
**Symbols:**

```
ffffffff812ba710-ffffffff812ba76b: get_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct vm_struct *get_vm_area(long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812fcd10)
Location: mm/vmalloc.c:2455
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_valloc
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
```
**Symbols:**

```
ffffffff812fcd10-ffffffff812fcd6b: get_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct vm_struct *get_vm_area(long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81363ef0)
Location: mm/vmalloc.c:2495
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_valloc
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
```
**Symbols:**

```
ffffffff81363ef0-ffffffff81363f52: get_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct vm_struct *get_vm_area(long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff813e0010)
Location: mm/vmalloc.c:2557
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_valloc
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
```
**Symbols:**

```
ffffffff813e0010-ffffffff813e0072: get_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct vm_struct *get_vm_area(long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81414d50)
Location: mm/vmalloc.c:2637
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_valloc
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
```
**Symbols:**

```
ffffffff81414d50-ffffffff81414db2: get_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct vm_struct *get_vm_area(long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff814417f0)
Location: mm/vmalloc.c:2637
Inline: False
Direct callers:
  - arch/x86/xen/grant-table.c:arch_gnttab_valloc
  - drivers/xen/xenbus/xenbus_client.c:xenbus_map_ring_pv
```
**Symbols:**

```
ffffffff814417f0-ffffffff81441852: get_vm_area (STB_GLOBAL)
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
struct vm_struct *get_vm_area(long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffff80001030fc78)
Location: mm/vmalloc.c:2102
Inline: False
```
**Symbols:**

```
ffff80001030fc78-ffff80001030fcdc: get_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct vm_struct *get_vm_area(long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c052c1a4)
Location: mm/vmalloc.c:2102
Inline: False
```
**Symbols:**

```
c052c1a4-c052c204: get_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct vm_struct *get_vm_area(long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (c0000000003e0f10)
Location: mm/vmalloc.c:2102
Inline: False
```
**Symbols:**

```
c0000000003e0f10-c0000000003e0f50: get_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct vm_struct *get_vm_area(long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffe000218212)
Location: mm/vmalloc.c:2102
Inline: False
```
**Symbols:**

```
ffffffe000218212-ffffffe00021825e: get_vm_area (STB_GLOBAL)
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
struct vm_struct *get_vm_area(long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812718d0)
Location: mm/vmalloc.c:2102
Inline: False
```
**Symbols:**

```
ffffffff812718d0-ffffffff8127190b: get_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct vm_struct *get_vm_area(long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff81263840)
Location: mm/vmalloc.c:2102
Inline: False
```
**Symbols:**

```
ffffffff81263840-ffffffff8126387b: get_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct vm_struct *get_vm_area(long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8126f670)
Location: mm/vmalloc.c:2102
Inline: False
```
**Symbols:**

```
ffffffff8126f670-ffffffff8126f6ab: get_vm_area (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct vm_struct *get_vm_area(long unsigned int size, long unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff8127f090)
Location: mm/vmalloc.c:2102
Inline: False
```
**Symbols:**

```
ffffffff8127f090-ffffffff8127f0cb: get_vm_area (STB_GLOBAL)
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
