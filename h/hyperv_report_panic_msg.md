# Function: <code>hyperv_report_panic_msg</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void hyperv_report_panic_msg(phys_addr_t pa, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102b470)
Location: arch/x86/hyperv/hv_init.c:461
Inline: False
```
**Symbols:**

```
ffffffff8102b470-ffffffff8102b503: hyperv_report_panic_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void hyperv_report_panic_msg(phys_addr_t pa, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102d1e0)
Location: arch/x86/hyperv/hv_init.c:387
Inline: False
```
**Symbols:**

```
ffffffff8102d1e0-ffffffff8102d273: hyperv_report_panic_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void hyperv_report_panic_msg(phys_addr_t pa, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102daf0)
Location: arch/x86/hyperv/hv_init.c:399
Inline: False
```
**Symbols:**

```
ffffffff8102daf0-ffffffff8102db83: hyperv_report_panic_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void hyperv_report_panic_msg(phys_addr_t pa, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102fc70)
Location: arch/x86/hyperv/hv_init.c:490
Inline: False
```
**Symbols:**

```
ffffffff8102fc70-ffffffff8102fd03: hyperv_report_panic_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void hyperv_report_panic_msg(phys_addr_t pa, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff810308a0)
Location: arch/x86/hyperv/hv_init.c:517
Inline: False
```
**Symbols:**

```
ffffffff810308a0-ffffffff81030933: hyperv_report_panic_msg (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void hyperv_report_panic_msg(phys_addr_t pa, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102dc50)
Location: arch/x86/hyperv/hv_init.c:399
Inline: False
```
**Symbols:**

```
ffffffff8102dc50-ffffffff8102dce3: hyperv_report_panic_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void hyperv_report_panic_msg(phys_addr_t pa, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8101d290)
Location: arch/x86/hyperv/hv_init.c:399
Inline: False
```
**Symbols:**

```
ffffffff8101d290-ffffffff8101d38c: hyperv_report_panic_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void hyperv_report_panic_msg(phys_addr_t pa, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102dab0)
Location: arch/x86/hyperv/hv_init.c:399
Inline: False
```
**Symbols:**

```
ffffffff8102dab0-ffffffff8102db43: hyperv_report_panic_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void hyperv_report_panic_msg(phys_addr_t pa, size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8102e8a0)
Location: arch/x86/hyperv/hv_init.c:399
Inline: False
```
**Symbols:**

```
ffffffff8102e8a0-ffffffff8102e933: hyperv_report_panic_msg (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
