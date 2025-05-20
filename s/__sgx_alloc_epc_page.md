# Function: <code>__sgx_alloc_epc_page</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sgx_epc_page *__sgx_alloc_epc_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068570)
Location: arch/x86/kernel/cpu/sgx/main.c:486
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
```
**Symbols:**

```
ffffffff81068570-ffffffff8106863a: __sgx_alloc_epc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sgx_epc_page *__sgx_alloc_epc_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81069150)
Location: arch/x86/kernel/cpu/sgx/main.c:491
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
```
**Symbols:**

```
ffffffff81069150-ffffffff810691b4: __sgx_alloc_epc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sgx_epc_page *__sgx_alloc_epc_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81073490)
Location: arch/x86/kernel/cpu/sgx/main.c:491
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
```
**Symbols:**

```
ffffffff81073490-ffffffff810734f4: __sgx_alloc_epc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sgx_epc_page *__sgx_alloc_epc_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81081300)
Location: arch/x86/kernel/cpu/sgx/main.c:515
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
```
**Symbols:**

```
ffffffff81081300-ffffffff81081375: __sgx_alloc_epc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sgx_epc_page *__sgx_alloc_epc_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093b70)
Location: arch/x86/kernel/cpu/sgx/main.c:473
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
```
**Symbols:**

```
ffffffff81093b70-ffffffff81093c1b: __sgx_alloc_epc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sgx_epc_page *__sgx_alloc_epc_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096b00)
Location: arch/x86/kernel/cpu/sgx/main.c:473
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
```
**Symbols:**

```
ffffffff81096b00-ffffffff81096bab: __sgx_alloc_epc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sgx_epc_page *__sgx_alloc_epc_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e070)
Location: arch/x86/kernel/cpu/sgx/main.c:473
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:sgx_alloc_epc_page
```
**Symbols:**

```
ffffffff8109e070-ffffffff8109e11b: __sgx_alloc_epc_page (STB_GLOBAL)
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
