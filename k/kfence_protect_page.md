# Function: <code>kfence_protect_page</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff8133bdfc)
Location: arch/x86/include/asm/kfence.h:41
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_unprotect
  - mm/kfence/core.c:kfence_protect
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool kfence_protect_page(long unsigned int addr, bool protect);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff813ae9f0)
Location: arch/x86/include/asm/kfence.h:41
Inline: False
Direct callers:
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_init_pool
  - mm/kfence/core.c:kfence_init_pool
  - mm/kfence/core.c:kfence_init_pool
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
```
**Symbols:**

```
ffffffff813ae9f0-ffffffff813aeac0: kfence_protect_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool kfence_protect_page(long unsigned int addr, bool protect);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff8142ef20)
Location: arch/x86/include/asm/kfence.h:41
Inline: False
Direct callers:
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_init_pool
  - mm/kfence/core.c:kfence_init_pool
  - mm/kfence/core.c:kfence_init_pool
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
```
**Symbols:**

```
ffffffff8142ef20-ffffffff8142eff4: kfence_protect_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool kfence_protect_page(long unsigned int addr, bool protect);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff81464748)
Location: arch/x86/include/asm/kfence.h:41
Inline: True
Inline callers:
  - mm/kfence/core.c:kfence_init_pool
Direct callers:
  - mm/kfence/core.c:kfence_handle_page_fault
```
**Symbols:**

```
ffffffff81464b40-ffffffff81464c14: kfence_protect_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool kfence_protect_page(long unsigned int addr, bool protect);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/kfence/core.c (ffffffff81493880)
Location: arch/x86/include/asm/kfence.h:41
Inline: True
Direct callers:
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_handle_page_fault
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_free
  - mm/kfence/core.c:kfence_guarded_alloc
```
**Symbols:**

```
ffffffff81493880-ffffffff81493954: kfence_protect_page (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
