# Function: <code>hv_free_hyperv_page</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void hv_free_hyperv_page(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102d7e0)
Location: arch/x86/hyperv/hv_init.c:56
Inline: False
```
**Symbols:**

```
ffffffff8102d7e0-ffffffff8102d7f2: hv_free_hyperv_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hv_free_hyperv_page(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102fa00)
Location: arch/x86/hyperv/hv_init.c:71
Inline: False
```
**Symbols:**

```
ffffffff8102fa00-ffffffff8102fa12: hv_free_hyperv_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hv_free_hyperv_page(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81030630)
Location: arch/x86/hyperv/hv_init.c:74
Inline: False
```
**Symbols:**

```
ffffffff81030630-ffffffff81030642: hv_free_hyperv_page (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void hv_free_hyperv_page(void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hv/hv_common.c (ffffffff83731e05)
Location: drivers/hv/hv_common.c:118
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:hv_common_free
  - drivers/hv/hv_common.c:hv_common_init
```
**Symbols:**

```
ffffffff81deb3a0-ffffffff81deb3ba: hv_free_hyperv_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void hv_free_hyperv_page(void *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/hv/hv_common.c (ffffffff83966295)
Location: drivers/hv/hv_common.c:119
Inline: True
Inline callers:
  - drivers/hv/hv_common.c:hv_common_free
  - drivers/hv/hv_common.c:hv_common_init
```
**Symbols:**

```
ffffffff81ea1640-ffffffff81ea165a: hv_free_hyperv_page (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void hv_free_hyperv_page(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102d940)
Location: arch/x86/hyperv/hv_init.c:56
Inline: False
```
**Symbols:**

```
ffffffff8102d940-ffffffff8102d952: hv_free_hyperv_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void hv_free_hyperv_page(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8101d010)
Location: arch/x86/hyperv/hv_init.c:56
Inline: False
```
**Symbols:**

```
ffffffff8101d010-ffffffff8101d022: hv_free_hyperv_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void hv_free_hyperv_page(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102d7a0)
Location: arch/x86/hyperv/hv_init.c:56
Inline: False
```
**Symbols:**

```
ffffffff8102d7a0-ffffffff8102d7b2: hv_free_hyperv_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void hv_free_hyperv_page(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102e590)
Location: arch/x86/hyperv/hv_init.c:56
Inline: False
```
**Symbols:**

```
ffffffff8102e590-ffffffff8102e5a2: hv_free_hyperv_page (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
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
