# Function: <code>sgx_encl_ewb</code>

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
void sgx_encl_ewb(struct sgx_epc_page *epc_page, struct sgx_backing *backing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810680e0)
Location: arch/x86/kernel/cpu/sgx/main.c:206
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_write
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_write
```
**Symbols:**

```
ffffffff810680e0-ffffffff810682f8: sgx_encl_ewb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sgx_encl_ewb(struct sgx_epc_page *epc_page, struct sgx_backing *backing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068650)
Location: arch/x86/kernel/cpu/sgx/main.c:225
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff81068650-ffffffff81068866: sgx_encl_ewb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void sgx_encl_ewb(struct sgx_epc_page *epc_page, struct sgx_backing *backing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: arch/x86/kernel/cpu/sgx/main.c:224
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff81072b80-ffffffff81072ed1: sgx_encl_ewb (STB_LOCAL)
ffffffff81c9ce8a-ffffffff81c9cec5: sgx_encl_ewb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void sgx_encl_ewb(struct sgx_epc_page *epc_page, struct sgx_backing *backing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: arch/x86/kernel/cpu/sgx/main.c:247
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff81081020-ffffffff810812c5: sgx_encl_ewb (STB_LOCAL)
ffffffff81e4c21e-ffffffff81e4c259: sgx_encl_ewb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void sgx_encl_ewb(struct sgx_epc_page *epc_page, struct sgx_backing *backing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: arch/x86/kernel/cpu/sgx/main.c:197
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff810936f0-ffffffff81093995: sgx_encl_ewb (STB_LOCAL)
ffffffff82053870-ffffffff820538ab: sgx_encl_ewb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void sgx_encl_ewb(struct sgx_epc_page *epc_page, struct sgx_backing *backing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: arch/x86/kernel/cpu/sgx/main.c:197
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff81096670-ffffffff81096915: sgx_encl_ewb (STB_LOCAL)
ffffffff820d1e5b-ffffffff820d1e96: sgx_encl_ewb.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void sgx_encl_ewb(struct sgx_epc_page *epc_page, struct sgx_backing *backing);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: arch/x86/kernel/cpu/sgx/main.c:197
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff8109dbe0-ffffffff8109de85: sgx_encl_ewb (STB_LOCAL)
ffffffff821acabf-ffffffff821acafa: sgx_encl_ewb.cold (STB_LOCAL)
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
