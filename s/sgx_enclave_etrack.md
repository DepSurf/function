# Function: <code>sgx_enclave_etrack</code>

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
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sgx_enclave_etrack(struct sgx_encl *encl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:693
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_modify_types
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_restrict_permissions
```
**Symbols:**

```
ffffffff81091e30-ffffffff81091f73: sgx_enclave_etrack (STB_LOCAL)
ffffffff820537de-ffffffff82053813: sgx_enclave_etrack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sgx_enclave_etrack(struct sgx_encl *encl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:693
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_modify_types
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_restrict_permissions
```
**Symbols:**

```
ffffffff81094d70-ffffffff81094eb3: sgx_enclave_etrack (STB_LOCAL)
ffffffff820d1dc9-ffffffff820d1dfe: sgx_enclave_etrack.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sgx_enclave_etrack(struct sgx_encl *encl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:693
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_modify_types
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_restrict_permissions
```
**Symbols:**

```
ffffffff8109c280-ffffffff8109c3c3: sgx_enclave_etrack (STB_LOCAL)
ffffffff821aca2d-ffffffff821aca62: sgx_enclave_etrack.cold (STB_LOCAL)
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
