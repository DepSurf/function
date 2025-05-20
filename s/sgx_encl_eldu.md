# Function: <code>sgx_encl_eldu</code>

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
struct sgx_epc_page *sgx_encl_eldu(struct sgx_encl_page *encl_page, struct sgx_epc_page *secs_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810663b0)
Location: arch/x86/kernel/cpu/sgx/encl.c:66
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page
```
**Symbols:**

```
ffffffff810663b0-ffffffff81066475: sgx_encl_eldu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sgx_epc_page *sgx_encl_eldu(struct sgx_encl_page *encl_page, struct sgx_epc_page *secs_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066a70)
Location: arch/x86/kernel/cpu/sgx/encl.c:66
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page
```
**Symbols:**

```
ffffffff81066a70-ffffffff81066b35: sgx_encl_eldu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sgx_epc_page *sgx_encl_eldu(struct sgx_encl_page *encl_page, struct sgx_epc_page *secs_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070d30)
Location: arch/x86/kernel/cpu/sgx/encl.c:107
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page
```
**Symbols:**

```
ffffffff81070d30-ffffffff81070df5: sgx_encl_eldu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sgx_epc_page *sgx_encl_eldu(struct sgx_encl_page *encl_page, struct sgx_epc_page *secs_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107ed00)
Location: arch/x86/kernel/cpu/sgx/encl.c:208
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page
```
**Symbols:**

```
ffffffff8107ed00-ffffffff8107edda: sgx_encl_eldu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sgx_epc_page *sgx_encl_eldu(struct sgx_encl_page *encl_page, struct sgx_epc_page *secs_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81090590)
Location: arch/x86/kernel/cpu/sgx/encl.c:211
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_load_page
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_load_page
```
**Symbols:**

```
ffffffff81090590-ffffffff8109066a: sgx_encl_eldu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sgx_epc_page *sgx_encl_eldu(struct sgx_encl_page *encl_page, struct sgx_epc_page *secs_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810934a0)
Location: arch/x86/kernel/cpu/sgx/encl.c:211
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_load_page
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_load_page
```
**Symbols:**

```
ffffffff810934a0-ffffffff8109357a: sgx_encl_eldu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sgx_epc_page *sgx_encl_eldu(struct sgx_encl_page *encl_page, struct sgx_epc_page *secs_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a910)
Location: arch/x86/kernel/cpu/sgx/encl.c:211
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_load_page
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_load_page
```
**Symbols:**

```
ffffffff8109a910-ffffffff8109a9ea: sgx_encl_eldu (STB_LOCAL)
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
