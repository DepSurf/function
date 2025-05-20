# Function: <code>print_mem_encrypt_feature_info</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff82fd64d5)
Location: arch/x86/mm/mem_encrypt.c:443
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff831e0f36)
Location: arch/x86/mm/mem_encrypt.c:442
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff832c4650)
Location: arch/x86/mm/mem_encrypt.c:443
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void print_mem_encrypt_feature_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff81e51bd3)
Location: arch/x86/mm/mem_encrypt.c:42
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
```
**Symbols:**

```
ffffffff81e51bd3-ffffffff81e51c84: print_mem_encrypt_feature_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void print_mem_encrypt_feature_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff810d51f0)
Location: arch/x86/mm/mem_encrypt.c:42
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
```
**Symbols:**

```
ffffffff810d51f0-ffffffff810d52b5: print_mem_encrypt_feature_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void print_mem_encrypt_feature_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff810d86e0)
Location: arch/x86/mm/mem_encrypt.c:42
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
```
**Symbols:**

```
ffffffff810d86e0-ffffffff810d87a5: print_mem_encrypt_feature_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void print_mem_encrypt_feature_info();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff810e0f60)
Location: arch/x86/mm/mem_encrypt.c:43
Inline: False
Direct callers:
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
```
**Symbols:**

```
ffffffff810e0f60-ffffffff810e1025: print_mem_encrypt_feature_info (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
