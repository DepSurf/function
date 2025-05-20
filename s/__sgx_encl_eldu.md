# Function: <code>__sgx_encl_eldu</code>

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
int __sgx_encl_eldu(struct sgx_encl_page *encl_page, struct sgx_epc_page *epc_page, struct sgx_epc_page *secs_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810660f0)
Location: arch/x86/kernel/cpu/sgx/encl.c:19
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
```
**Symbols:**

```
ffffffff810660f0-ffffffff810663ab: __sgx_encl_eldu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __sgx_encl_eldu(struct sgx_encl_page *encl_page, struct sgx_epc_page *epc_page, struct sgx_epc_page *secs_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066550)
Location: arch/x86/kernel/cpu/sgx/encl.c:19
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
```
**Symbols:**

```
ffffffff81066550-ffffffff81066802: __sgx_encl_eldu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int __sgx_encl_eldu(struct sgx_encl_page *encl_page, struct sgx_epc_page *epc_page, struct sgx_epc_page *secs_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: arch/x86/kernel/cpu/sgx/encl.c:43
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
```
**Symbols:**

```
ffffffff81070670-ffffffff81070aa0: __sgx_encl_eldu (STB_LOCAL)
ffffffff81c9cdea-ffffffff81c9ce06: __sgx_encl_eldu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __sgx_encl_eldu(struct sgx_encl_page *encl_page, struct sgx_epc_page *epc_page, struct sgx_epc_page *secs_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: arch/x86/kernel/cpu/sgx/encl.c:129
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
```
**Symbols:**

```
ffffffff8107dbe0-ffffffff8107e334: __sgx_encl_eldu (STB_LOCAL)
ffffffff81e4c162-ffffffff81e4c199: __sgx_encl_eldu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __sgx_encl_eldu(struct sgx_encl_page *encl_page, struct sgx_epc_page *epc_page, struct sgx_epc_page *secs_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: arch/x86/kernel/cpu/sgx/encl.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
```
**Symbols:**

```
ffffffff8108f180-ffffffff8108f812: __sgx_encl_eldu (STB_LOCAL)
ffffffff82053772-ffffffff8205378e: __sgx_encl_eldu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __sgx_encl_eldu(struct sgx_encl_page *encl_page, struct sgx_epc_page *epc_page, struct sgx_epc_page *secs_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: arch/x86/kernel/cpu/sgx/encl.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
```
**Symbols:**

```
ffffffff81092080-ffffffff8109271b: __sgx_encl_eldu (STB_LOCAL)
ffffffff820d1d65-ffffffff820d1d81: __sgx_encl_eldu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __sgx_encl_eldu(struct sgx_encl_page *encl_page, struct sgx_epc_page *epc_page, struct sgx_epc_page *secs_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: arch/x86/kernel/cpu/sgx/encl.c:132
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
```
**Symbols:**

```
ffffffff810994a0-ffffffff81099b2f: __sgx_encl_eldu (STB_LOCAL)
ffffffff821ac9c9-ffffffff821ac9e5: __sgx_encl_eldu.cold (STB_LOCAL)
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
