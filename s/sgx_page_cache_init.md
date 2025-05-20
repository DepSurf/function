# Function: <code>sgx_page_cache_init</code>

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
bool sgx_page_cache_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff82fc44be)
Location: arch/x86/kernel/cpu/sgx/main.c:664
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
```
**Symbols:**

```
ffffffff82fc44be-ffffffff82fc46c0: sgx_page_cache_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool sgx_page_cache_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff831ceb5b)
Location: arch/x86/kernel/cpu/sgx/main.c:673
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
```
**Symbols:**

```
ffffffff831ceb5b-ffffffff831cee03: sgx_page_cache_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool sgx_page_cache_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff832b0e01)
Location: arch/x86/kernel/cpu/sgx/main.c:673
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
```
**Symbols:**

```
ffffffff832b0e01-ffffffff832b10eb: sgx_page_cache_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool sgx_page_cache_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff83461f85)
Location: arch/x86/kernel/cpu/sgx/main.c:829
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
```
**Symbols:**

```
ffffffff83461f85-ffffffff83462318: sgx_page_cache_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool sgx_page_cache_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff83e841f0)
Location: arch/x86/kernel/cpu/sgx/main.c:787
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
```
**Symbols:**

```
ffffffff83e841f0-ffffffff83e845fd: sgx_page_cache_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool sgx_page_cache_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff836a7740)
Location: arch/x86/kernel/cpu/sgx/main.c:787
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
```
**Symbols:**

```
ffffffff836a7740-ffffffff836a7b4d: sgx_page_cache_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool sgx_page_cache_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff838d7c80)
Location: arch/x86/kernel/cpu/sgx/main.c:787
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_init
```
**Symbols:**

```
ffffffff838d7c80-ffffffff838d8092: sgx_page_cache_init (STB_LOCAL)
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
