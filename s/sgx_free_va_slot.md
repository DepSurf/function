# Function: <code>sgx_free_va_slot</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void sgx_free_va_slot(struct sgx_va_page *va_page, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810663f6)
Location: arch/x86/kernel/cpu/sgx/encl.c:729
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
**Symbols:**

```
ffffffff81066bf0-ffffffff81066c04: sgx_free_va_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void sgx_free_va_slot(struct sgx_va_page *va_page, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066ab6)
Location: arch/x86/kernel/cpu/sgx/encl.c:721
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
**Symbols:**

```
ffffffff810669b0-ffffffff810669c4: sgx_free_va_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void sgx_free_va_slot(struct sgx_va_page *va_page, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070d76)
Location: arch/x86/kernel/cpu/sgx/encl.c:762
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
**Symbols:**

```
ffffffff81070c30-ffffffff81070c44: sgx_free_va_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sgx_free_va_slot(struct sgx_va_page *va_page, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107ebd0)
Location: arch/x86/kernel/cpu/sgx/encl.c:958
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
**Symbols:**

```
ffffffff8107ebd0-ffffffff8107ebec: sgx_free_va_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sgx_free_va_slot(struct sgx_va_page *va_page, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81090430)
Location: arch/x86/kernel/cpu/sgx/encl.c:1266
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
**Symbols:**

```
ffffffff81090430-ffffffff8109044c: sgx_free_va_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sgx_free_va_slot(struct sgx_va_page *va_page, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81093360)
Location: arch/x86/kernel/cpu/sgx/encl.c:1268
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
**Symbols:**

```
ffffffff81093360-ffffffff8109337c: sgx_free_va_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sgx_free_va_slot(struct sgx_va_page *va_page, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a7d0)
Location: arch/x86/kernel/cpu/sgx/encl.c:1288
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
**Symbols:**

```
ffffffff8109a7d0-ffffffff8109a7ec: sgx_free_va_slot (STB_GLOBAL)
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
