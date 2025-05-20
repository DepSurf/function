# Function: <code>sgx_vepc_init</code>

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
int sgx_vepc_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff831ceee3)
Location: arch/x86/kernel/cpu/sgx/virt.c:250
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
```
**Symbols:**

```
ffffffff831ceee3-ffffffff831cef35: sgx_vepc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sgx_vepc_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff832b1206)
Location: arch/x86/kernel/cpu/sgx/virt.c:250
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
```
**Symbols:**

```
ffffffff832b1206-ffffffff832b1258: sgx_vepc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sgx_vepc_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8346243d)
Location: arch/x86/kernel/cpu/sgx/virt.c:305
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
```
**Symbols:**

```
ffffffff8346243d-ffffffff834624a3: sgx_vepc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sgx_vepc_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff83e84770)
Location: arch/x86/kernel/cpu/sgx/virt.c:305
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
```
**Symbols:**

```
ffffffff83e84770-ffffffff83e847d6: sgx_vepc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sgx_vepc_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff836a7cc0)
Location: arch/x86/kernel/cpu/sgx/virt.c:308
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
```
**Symbols:**

```
ffffffff836a7cc0-ffffffff836a7d26: sgx_vepc_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sgx_vepc_init();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff838d8210)
Location: arch/x86/kernel/cpu/sgx/virt.c:308
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
```
**Symbols:**

```
ffffffff838d8210-ffffffff838d8276: sgx_vepc_init (STB_GLOBAL)
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
