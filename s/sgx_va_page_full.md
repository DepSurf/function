# Function: <code>sgx_va_page_full</code>

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
bool sgx_va_page_full(struct sgx_va_page *va_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066c10)
Location: arch/x86/kernel/cpu/sgx/encl.c:740
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
**Symbols:**

```
ffffffff81066c10-ffffffff81066c31: sgx_va_page_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool sgx_va_page_full(struct sgx_va_page *va_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810669d0)
Location: arch/x86/kernel/cpu/sgx/encl.c:732
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
**Symbols:**

```
ffffffff810669d0-ffffffff810669f1: sgx_va_page_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool sgx_va_page_full(struct sgx_va_page *va_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070c50)
Location: arch/x86/kernel/cpu/sgx/encl.c:773
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
**Symbols:**

```
ffffffff81070c50-ffffffff81070c71: sgx_va_page_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool sgx_va_page_full(struct sgx_va_page *va_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107ebf0)
Location: arch/x86/kernel/cpu/sgx/encl.c:969
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
**Symbols:**

```
ffffffff8107ebf0-ffffffff8107ec19: sgx_va_page_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool sgx_va_page_full(struct sgx_va_page *va_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81090460)
Location: arch/x86/kernel/cpu/sgx/encl.c:1277
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
**Symbols:**

```
ffffffff81090460-ffffffff81090489: sgx_va_page_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool sgx_va_page_full(struct sgx_va_page *va_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81093390)
Location: arch/x86/kernel/cpu/sgx/encl.c:1279
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
**Symbols:**

```
ffffffff81093390-ffffffff810933b9: sgx_va_page_full (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool sgx_va_page_full(struct sgx_va_page *va_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a800)
Location: arch/x86/kernel/cpu/sgx/encl.c:1299
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_encl_ewb
```
**Symbols:**

```
ffffffff8109a800-ffffffff8109a829: sgx_va_page_full (STB_GLOBAL)
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
