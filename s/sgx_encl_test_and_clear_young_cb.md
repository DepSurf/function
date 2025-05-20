# Function: <code>sgx_encl_test_and_clear_young_cb</code>

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
int sgx_encl_test_and_clear_young_cb(pte_t *ptep, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81065890)
Location: arch/x86/kernel/cpu/sgx/encl.c:628
Inline: False
```
**Symbols:**

```
ffffffff81065890-ffffffff810658c4: sgx_encl_test_and_clear_young_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sgx_encl_test_and_clear_young_cb(pte_t *ptep, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81065f60)
Location: arch/x86/kernel/cpu/sgx/encl.c:620
Inline: False
```
**Symbols:**

```
ffffffff81065f60-ffffffff81065f94: sgx_encl_test_and_clear_young_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sgx_encl_test_and_clear_young_cb(pte_t *ptep, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81070080)
Location: arch/x86/kernel/cpu/sgx/encl.c:661
Inline: False
```
**Symbols:**

```
ffffffff81070080-ffffffff810700b4: sgx_encl_test_and_clear_young_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sgx_encl_test_and_clear_young_cb(pte_t *ptep, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107d9a0)
Location: arch/x86/kernel/cpu/sgx/encl.c:857
Inline: False
```
**Symbols:**

```
ffffffff8107d9a0-ffffffff8107d9fe: sgx_encl_test_and_clear_young_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sgx_encl_test_and_clear_young_cb(pte_t *ptep, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108ef20)
Location: arch/x86/kernel/cpu/sgx/encl.c:1088
Inline: False
```
**Symbols:**

```
ffffffff8108ef20-ffffffff8108ef7e: sgx_encl_test_and_clear_young_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sgx_encl_test_and_clear_young_cb(pte_t *ptep, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81091e10)
Location: arch/x86/kernel/cpu/sgx/encl.c:1090
Inline: False
```
**Symbols:**

```
ffffffff81091e10-ffffffff81091e6e: sgx_encl_test_and_clear_young_cb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sgx_encl_test_and_clear_young_cb(pte_t *ptep, long unsigned int addr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81099450)
Location: arch/x86/kernel/cpu/sgx/encl.c:1110
Inline: False
```
**Symbols:**

```
ffffffff81099450-ffffffff8109948d: sgx_encl_test_and_clear_young_cb (STB_LOCAL)
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
