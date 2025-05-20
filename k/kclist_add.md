# Function: <code>kclist_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void kclist_add(struct kcore_list *new, void *addr, size_t size, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff81f90f63)
Location: fs/proc/kcore.c:64
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
```
**Symbols:**

```
ffffffff81287440-ffffffff8128748a: kclist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void kclist_add(struct kcore_list *new, void *addr, size_t size, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff81fbb8c2)
Location: fs/proc/kcore.c:64
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
```
**Symbols:**

```
ffffffff812b4720-ffffffff812b476a: kclist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void kclist_add(struct kcore_list *new, void *addr, size_t size, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff81ff82dc)
Location: fs/proc/kcore.c:64
Inline: True
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
```
**Symbols:**

```
ffffffff812c9fb0-ffffffff812c9ffa: kclist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void kclist_add(struct kcore_list *new, void *addr, size_t size, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff820db385)
Location: fs/proc/kcore.c:65
Inline: True
Inline callers:
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
```
**Symbols:**

```
ffffffff812d7470-ffffffff812d74ba: kclist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void kclist_add(struct kcore_list *new, void *addr, size_t size, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff826e401a)
Location: fs/proc/kcore.c:66
Inline: True
Inline callers:
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
```
**Symbols:**

```
ffffffff812fbb50-ffffffff812fbb9a: kclist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void kclist_add(struct kcore_list *new, void *addr, size_t size, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff8270e5f4)
Location: fs/proc/kcore.c:66
Inline: True
Inline callers:
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
```
**Symbols:**

```
ffffffff813291a0-ffffffff813291ea: kclist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void kclist_add(struct kcore_list *new, void *addr, size_t size, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff828c57d7)
Location: fs/proc/kcore.c:58
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
```
**Symbols:**

```
ffffffff828c57d7-ffffffff828c5809: kclist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void kclist_add(struct kcore_list *new, void *addr, size_t size, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff828ded2c)
Location: fs/proc/kcore.c:80
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
```
**Symbols:**

```
ffffffff828ded2c-ffffffff828ded5e: kclist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void kclist_add(struct kcore_list *new, void *addr, size_t size, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff828e7704)
Location: fs/proc/kcore.c:81
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
```
**Symbols:**

```
ffffffff828e7704-ffffffff828e7736: kclist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void kclist_add(struct kcore_list *new, void *addr, size_t size, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff82d01e51)
Location: fs/proc/kcore.c:81
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:add_modules_range
```
**Symbols:**

```
ffffffff82d01e51-ffffffff82d01e83: kclist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void kclist_add(struct kcore_list *new, void *addr, size_t size, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff82fef140)
Location: fs/proc/kcore.c:81
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:add_modules_range
```
**Symbols:**

```
ffffffff82fef140-ffffffff82fef172: kclist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void kclist_add(struct kcore_list *new, void *addr, size_t size, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff831f99ff)
Location: fs/proc/kcore.c:81
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
```
**Symbols:**

```
ffffffff831f99ff-ffffffff831f9a31: kclist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kclist_add(struct kcore_list *new, void *addr, size_t size, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff832e0937)
Location: fs/proc/kcore.c:81
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
```
**Symbols:**

```
ffffffff832e0937-ffffffff832e0969: kclist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kclist_add(struct kcore_list *new, void *addr, size_t size, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff83496994)
Location: fs/proc/kcore.c:81
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
```
**Symbols:**

```
ffffffff83496994-ffffffff834969d4: kclist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void kclist_add(struct kcore_list *new, void *addr, size_t size, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff83ecbb43)
Location: fs/proc/kcore.c:80
Inline: True
Inline callers:
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
```
**Symbols:**

```
ffffffff83ecbcd0-ffffffff83ecbd10: kclist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void kclist_add(struct kcore_list *new, void *addr, size_t size, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff836f0bc3)
Location: fs/proc/kcore.c:80
Inline: True
Inline callers:
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
```
**Symbols:**

```
ffffffff836f0d50-ffffffff836f0d90: kclist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void kclist_add(struct kcore_list *new, void *addr, size_t size, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff83923c63)
Location: fs/proc/kcore.c:80
Inline: True
Inline callers:
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
```
**Symbols:**

```
ffffffff83923df0-ffffffff83923e30: kclist_add (STB_GLOBAL)
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
void kclist_add(struct kcore_list *new, void *addr, size_t size, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffff800011461288)
Location: fs/proc/kcore.c:81
Inline: False
Direct callers:
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
```
**Symbols:**

```
ffff800011461288-ffff8000114612e4: kclist_add (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void kclist_add(struct kcore_list *new, void *addr, size_t size, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (c00000000138ccfc)
Location: fs/proc/kcore.c:81
Inline: False
Direct callers:
  - fs/proc/kcore.c:proc_kcore_init
```
**Symbols:**

```
c00000000138ccfc-c00000000138cd3c: kclist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void kclist_add(struct kcore_list *new, void *addr, size_t size, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffe00001dc20)
Location: fs/proc/kcore.c:81
Inline: False
Direct callers:
  - fs/proc/kcore.c:proc_kcore_init
```
**Symbols:**

```
ffffffe00001dc20-ffffffe00001dc70: kclist_add (STB_GLOBAL)
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
void kclist_add(struct kcore_list *new, void *addr, size_t size, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff828d05b8)
Location: fs/proc/kcore.c:81
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
```
**Symbols:**

```
ffffffff828d05b8-ffffffff828d05ea: kclist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void kclist_add(struct kcore_list *new, void *addr, size_t size, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff828c8cd4)
Location: fs/proc/kcore.c:81
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
```
**Symbols:**

```
ffffffff828c8cd4-ffffffff828c8d06: kclist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void kclist_add(struct kcore_list *new, void *addr, size_t size, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff828e3338)
Location: fs/proc/kcore.c:81
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
```
**Symbols:**

```
ffffffff828e3338-ffffffff828e336a: kclist_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void kclist_add(struct kcore_list *new, void *addr, size_t size, int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff828e874e)
Location: fs/proc/kcore.c:81
Inline: False
Direct callers:
  - arch/x86/mm/init_64.c:mem_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
  - fs/proc/kcore.c:proc_kcore_init
```
**Symbols:**

```
ffffffff828e874e-ffffffff828e8780: kclist_add (STB_GLOBAL)
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
