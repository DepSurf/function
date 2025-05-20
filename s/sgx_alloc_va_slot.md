# Function: <code>sgx_alloc_va_slot</code>

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
unsigned int sgx_alloc_va_slot(struct sgx_va_page *va_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066bb0)
Location: arch/x86/kernel/cpu/sgx/encl.c:712
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
**Symbols:**

```
ffffffff81066bb0-ffffffff81066bed: sgx_alloc_va_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int sgx_alloc_va_slot(struct sgx_va_page *va_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066970)
Location: arch/x86/kernel/cpu/sgx/encl.c:704
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
**Symbols:**

```
ffffffff81066970-ffffffff810669ac: sgx_alloc_va_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int sgx_alloc_va_slot(struct sgx_va_page *va_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070bf0)
Location: arch/x86/kernel/cpu/sgx/encl.c:745
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
**Symbols:**

```
ffffffff81070bf0-ffffffff81070c2c: sgx_alloc_va_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int sgx_alloc_va_slot(struct sgx_va_page *va_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107eb90)
Location: arch/x86/kernel/cpu/sgx/encl.c:941
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
**Symbols:**

```
ffffffff8107eb90-ffffffff8107ebcd: sgx_alloc_va_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int sgx_alloc_va_slot(struct sgx_va_page *va_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810903e0)
Location: arch/x86/kernel/cpu/sgx/encl.c:1249
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
**Symbols:**

```
ffffffff810903e0-ffffffff8109041d: sgx_alloc_va_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int sgx_alloc_va_slot(struct sgx_va_page *va_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81093310)
Location: arch/x86/kernel/cpu/sgx/encl.c:1251
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
**Symbols:**

```
ffffffff81093310-ffffffff8109334d: sgx_alloc_va_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int sgx_alloc_va_slot(struct sgx_va_page *va_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a780)
Location: arch/x86/kernel/cpu/sgx/encl.c:1271
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
**Symbols:**

```
ffffffff8109a780-ffffffff8109a7bd: sgx_alloc_va_slot (STB_GLOBAL)
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
