# Function: <code>__sgx_alloc_epc_page_from_node</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sgx_epc_page *__sgx_alloc_epc_page_from_node(int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810690d0)
Location: arch/x86/kernel/cpu/sgx/main.c:460
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
**Symbols:**

```
ffffffff810690d0-ffffffff81069147: __sgx_alloc_epc_page_from_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sgx_epc_page *__sgx_alloc_epc_page_from_node(int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81073410)
Location: arch/x86/kernel/cpu/sgx/main.c:460
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
**Symbols:**

```
ffffffff81073410-ffffffff81073487: __sgx_alloc_epc_page_from_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sgx_epc_page *__sgx_alloc_epc_page_from_node(int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81080880)
Location: arch/x86/kernel/cpu/sgx/main.c:483
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
**Symbols:**

```
ffffffff81080880-ffffffff81080902: __sgx_alloc_epc_page_from_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sgx_epc_page *__sgx_alloc_epc_page_from_node(int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093420)
Location: arch/x86/kernel/cpu/sgx/main.c:441
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
**Symbols:**

```
ffffffff81093420-ffffffff810934a2: __sgx_alloc_epc_page_from_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sgx_epc_page *__sgx_alloc_epc_page_from_node(int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096380)
Location: arch/x86/kernel/cpu/sgx/main.c:441
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
**Symbols:**

```
ffffffff81096380-ffffffff81096402: __sgx_alloc_epc_page_from_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sgx_epc_page *__sgx_alloc_epc_page_from_node(int nid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109d8f0)
Location: arch/x86/kernel/cpu/sgx/main.c:441
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:__sgx_alloc_epc_page
```
**Symbols:**

```
ffffffff8109d8f0-ffffffff8109d972: __sgx_alloc_epc_page_from_node (STB_LOCAL)
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
