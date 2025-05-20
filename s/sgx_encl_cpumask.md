# Function: <code>sgx_encl_cpumask</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const cpumask_t *sgx_encl_cpumask(struct sgx_encl *encl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108fcc0)
Location: arch/x86/kernel/cpu/sgx/encl.c:903
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
**Symbols:**

```
ffffffff8108fcc0-ffffffff8108fd97: sgx_encl_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const cpumask_t *sgx_encl_cpumask(struct sgx_encl *encl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81092bd0)
Location: arch/x86/kernel/cpu/sgx/encl.c:905
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
**Symbols:**

```
ffffffff81092bd0-ffffffff81092cad: sgx_encl_cpumask (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const cpumask_t *sgx_encl_cpumask(struct sgx_encl *encl);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a010)
Location: arch/x86/kernel/cpu/sgx/encl.c:925
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_etrack
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
**Symbols:**

```
ffffffff8109a010-ffffffff8109a0ed: sgx_encl_cpumask (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
