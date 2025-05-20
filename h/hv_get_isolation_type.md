# Function: <code>hv_get_isolation_type</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
enum hv_isolation_type hv_get_isolation_type();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81031155)
Location: arch/x86/hyperv/hv_init.c:612
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_is_isolation_supported
```
**Symbols:**

```
ffffffff81031120-ffffffff81031141: hv_get_isolation_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
enum hv_isolation_type hv_get_isolation_type();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81036a65)
Location: arch/x86/hyperv/hv_init.c:557
Inline: True
Inline callers:
  - arch/x86/hyperv/hv_init.c:hv_is_isolation_supported
```
**Symbols:**

```
ffffffff810363c0-ffffffff810363e1: hv_get_isolation_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
enum hv_isolation_type hv_get_isolation_type();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff8103f219)
Location: arch/x86/hyperv/ivm.c:238
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_is_isolation_supported
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
**Symbols:**

```
ffffffff8103ed80-ffffffff8103eda5: hv_get_isolation_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
enum hv_isolation_type hv_get_isolation_type();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff81048357)
Location: arch/x86/hyperv/ivm.c:238
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_is_isolation_supported
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
**Symbols:**

```
ffffffff81047da0-ffffffff81047dc5: hv_get_isolation_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
enum hv_isolation_type hv_get_isolation_type();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff81048707)
Location: arch/x86/hyperv/ivm.c:382
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_is_isolation_supported
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
**Symbols:**

```
ffffffff81048150-ffffffff81048175: hv_get_isolation_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
enum hv_isolation_type hv_get_isolation_type();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff8104f7f7)
Location: arch/x86/hyperv/ivm.c:674
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_is_isolation_supported
  - arch/x86/hyperv/ivm.c:hv_vtom_init
Direct callers:
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
  - arch/x86/kernel/cpu/mshyperv.c:ms_hyperv_init_platform
```
**Symbols:**

```
ffffffff8104e970-ffffffff8104e995: hv_get_isolation_type (STB_GLOBAL)
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
