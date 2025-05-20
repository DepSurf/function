# Function: <code>sgx_encl_init</code>

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
int sgx_encl_init(struct sgx_encl *encl, struct sgx_sigstruct *sigstruct, void *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81066f30)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:494
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_init
```
**Symbols:**

```
ffffffff81066f30-ffffffff810671ba: sgx_encl_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sgx_encl_init(struct sgx_encl *encl, struct sgx_sigstruct *sigstruct, void *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810674d0)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:495
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
```
**Symbols:**

```
ffffffff810674d0-ffffffff81067725: sgx_encl_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sgx_encl_init(struct sgx_encl *encl, struct sgx_sigstruct *sigstruct, void *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:495
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
```
**Symbols:**

```
ffffffff81071880-ffffffff81071b0d: sgx_encl_init (STB_LOCAL)
ffffffff81c9ce3a-ffffffff81c9ce4e: sgx_encl_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sgx_encl_init(struct sgx_encl *encl, struct sgx_sigstruct *sigstruct, void *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:495
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioctl
```
**Symbols:**

```
ffffffff8107f910-ffffffff8107fbe4: sgx_encl_init (STB_LOCAL)
ffffffff81e4c1d5-ffffffff81e4c1e9: sgx_encl_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sgx_encl_init(struct sgx_encl *encl, struct sgx_sigstruct *sigstruct, void *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:484
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_init
```
**Symbols:**

```
ffffffff81091a00-ffffffff81091cd4: sgx_encl_init (STB_LOCAL)
ffffffff820537ca-ffffffff820537de: sgx_encl_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sgx_encl_init(struct sgx_encl *encl, struct sgx_sigstruct *sigstruct, void *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:484
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_init
```
**Symbols:**

```
ffffffff81094930-ffffffff81094c1d: sgx_encl_init (STB_LOCAL)
ffffffff820d1db5-ffffffff820d1dc9: sgx_encl_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sgx_encl_init(struct sgx_encl *encl, struct sgx_sigstruct *sigstruct, void *token);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:484
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_init
```
**Symbols:**

```
ffffffff8109be10-ffffffff8109c0fd: sgx_encl_init (STB_LOCAL)
ffffffff821aca19-ffffffff821aca2d: sgx_encl_init.cold (STB_LOCAL)
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
