# Function: <code>vmalloc_sync_all</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void vmalloc_sync_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106b8b0)
Location: arch/x86/mm/fault.c:357
Inline: False
Direct callers:
  - kernel/notifier.c:register_die_notifier
```
**Symbols:**

```
ffffffff8106b8b0-ffffffff8106b8d6: vmalloc_sync_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void vmalloc_sync_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106b780)
Location: arch/x86/mm/fault.c:414
Inline: False
Direct callers:
  - kernel/notifier.c:register_die_notifier
```
**Symbols:**

```
ffffffff8106b780-ffffffff8106b7b3: vmalloc_sync_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void vmalloc_sync_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106f3a0)
Location: arch/x86/mm/fault.c:414
Inline: False
Direct callers:
  - kernel/notifier.c:register_die_notifier
```
**Symbols:**

```
ffffffff8106f3a0-ffffffff8106f3d1: vmalloc_sync_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void vmalloc_sync_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106eaf0)
Location: arch/x86/mm/fault.c:425
Inline: False
Direct callers:
  - kernel/notifier.c:register_die_notifier
```
**Symbols:**

```
ffffffff8106eaf0-ffffffff8106eb21: vmalloc_sync_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void vmalloc_sync_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81073b80)
Location: arch/x86/mm/fault.c:408
Inline: False
Direct callers:
  - kernel/notifier.c:register_die_notifier
```
**Symbols:**

```
ffffffff81073b80-ffffffff81073bb1: vmalloc_sync_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void vmalloc_sync_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810764d0)
Location: arch/x86/mm/fault.c:407
Inline: False
Direct callers:
  - kernel/notifier.c:register_die_notifier
```
**Symbols:**

```
ffffffff810764d0-ffffffff81076501: vmalloc_sync_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void vmalloc_sync_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107c780)
Location: arch/x86/mm/fault.c:340
Inline: False
Direct callers:
  - kernel/notifier.c:register_die_notifier
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
**Symbols:**

```
ffffffff8107c780-ffffffff8107c7b1: vmalloc_sync_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void vmalloc_sync_all();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810800a0)
Location: arch/x86/mm/fault.c:321
Inline: False
Direct callers:
  - kernel/notifier.c:register_die_notifier
  - mm/vmalloc.c:__purge_vmap_area_lazy
  - drivers/acpi/apei/ghes.c:ghes_estatus_pool_init
```
**Symbols:**

```
ffffffff810800a0-ffffffff810800d1: vmalloc_sync_all (STB_GLOBAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
</ul>
