# Function: <code>__eremove</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8106873b)
Location: arch/x86/kernel/cpu/sgx/encls.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_free_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:sgx_sanitize_section
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066a0f)
Location: arch/x86/kernel/cpu/sgx/encls.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_free_epc_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068a19)
Location: arch/x86/kernel/cpu/sgx/encls.h:185
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81069515)
Location: arch/x86/kernel/cpu/sgx/encls.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_free_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070ca3)
Location: arch/x86/kernel/cpu/sgx/encls.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_free_epc_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810737db)
Location: arch/x86/kernel/cpu/sgx/encls.h:185
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81073c49)
Location: arch/x86/kernel/cpu/sgx/encls.h:185
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_free_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107ec46)
Location: arch/x86/kernel/cpu/sgx/encls.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_free_epc_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81081b6b)
Location: arch/x86/kernel/cpu/sgx/encls.h:159
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff810826bb)
Location: arch/x86/kernel/cpu/sgx/encls.h:159
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_free_page
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810904c6)
Location: arch/x86/kernel/cpu/sgx/encls.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_free_epc_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81094597)
Location: arch/x86/kernel/cpu/sgx/encls.h:167
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109513b)
Location: arch/x86/kernel/cpu/sgx/encls.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_free_page
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810933f2)
Location: arch/x86/kernel/cpu/sgx/encls.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_free_epc_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81097537)
Location: arch/x86/kernel/cpu/sgx/encls.h:167
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff810980bb)
Location: arch/x86/kernel/cpu/sgx/encls.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_free_page
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
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a862)
Location: arch/x86/kernel/cpu/sgx/encls.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_free_epc_page
```
```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109eaa7)
Location: arch/x86/kernel/cpu/sgx/encls.h:167
Inline: True
```
```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f65b)
Location: arch/x86/kernel/cpu/sgx/encls.h:167
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_free_page
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
