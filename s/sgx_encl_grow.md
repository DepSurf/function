# Function: <code>sgx_encl_grow</code>

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
struct sgx_va_page *sgx_encl_grow(struct sgx_encl *encl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81067330)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:19
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
```
**Symbols:**

```
ffffffff81067330-ffffffff810673c7: sgx_encl_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sgx_va_page *sgx_encl_grow(struct sgx_encl *encl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81067730)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:20
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
```
**Symbols:**

```
ffffffff81067730-ffffffff810677c6: sgx_encl_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sgx_va_page *sgx_encl_grow(struct sgx_encl *encl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81071b10)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:20
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
```
**Symbols:**

```
ffffffff81071b10-ffffffff81071ba6: sgx_encl_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sgx_va_page *sgx_encl_grow(struct sgx_encl *encl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8107fbf0)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:20
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
```
**Symbols:**

```
ffffffff8107fbf0-ffffffff8107fc86: sgx_encl_grow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sgx_va_page *sgx_encl_grow(struct sgx_encl *encl, bool reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81092500)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:20
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
```
**Symbols:**

```
ffffffff81092500-ffffffff810925a1: sgx_encl_grow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sgx_va_page *sgx_encl_grow(struct sgx_encl *encl, bool reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81095430)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:20
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
```
**Symbols:**

```
ffffffff81095430-ffffffff810954d1: sgx_encl_grow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sgx_va_page *sgx_encl_grow(struct sgx_encl *encl, bool reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109c940)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:20
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
```
**Symbols:**

```
ffffffff8109c940-ffffffff8109ca1d: sgx_encl_grow (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool reclaim</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
