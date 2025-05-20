# Function: <code>__sgx_encl_add_page</code>

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
int __sgx_encl_add_page(struct sgx_encl *encl, struct sgx_encl_page *encl_page, struct sgx_epc_page *epc_page, struct sgx_secinfo *secinfo, long unsigned int src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81066d20)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:229
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
**Symbols:**

```
ffffffff81066d20-ffffffff81066ed1: __sgx_encl_add_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sgx_encl_add_page(struct sgx_encl *encl, struct sgx_encl_page *encl_page, struct sgx_epc_page *epc_page, struct sgx_secinfo *secinfo, long unsigned int src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810672d0)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:230
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
**Symbols:**

```
ffffffff810672d0-ffffffff8106747d: __sgx_encl_add_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __sgx_encl_add_page(struct sgx_encl *encl, struct sgx_encl_page *encl_page, struct sgx_epc_page *epc_page, struct sgx_secinfo *secinfo, long unsigned int src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81071640)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:230
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
**Symbols:**

```
ffffffff81071640-ffffffff81071830: __sgx_encl_add_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __sgx_encl_add_page(struct sgx_encl *encl, struct sgx_encl_page *encl_page, struct sgx_epc_page *epc_page, struct sgx_secinfo *secinfo, long unsigned int src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107f670)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:230
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
**Symbols:**

```
ffffffff8107f670-ffffffff8107f901: __sgx_encl_add_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __sgx_encl_add_page(struct sgx_encl *encl, struct sgx_encl_page *encl_page, struct sgx_epc_page *epc_page, struct sgx_secinfo *secinfo, long unsigned int src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81091790)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:199
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
**Symbols:**

```
ffffffff81091790-ffffffff810919e3: __sgx_encl_add_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __sgx_encl_add_page(struct sgx_encl *encl, struct sgx_encl_page *encl_page, struct sgx_epc_page *epc_page, struct sgx_secinfo *secinfo, long unsigned int src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810946d0)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:199
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
**Symbols:**

```
ffffffff810946d0-ffffffff81094918: __sgx_encl_add_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __sgx_encl_add_page(struct sgx_encl *encl, struct sgx_encl_page *encl_page, struct sgx_epc_page *epc_page, struct sgx_secinfo *secinfo, long unsigned int src);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109bbb0)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:199
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
**Symbols:**

```
ffffffff8109bbb0-ffffffff8109bdf5: __sgx_encl_add_page (STB_LOCAL)
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
