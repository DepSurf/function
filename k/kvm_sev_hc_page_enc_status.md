# Function: <code>kvm_sev_hc_page_enc_status</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kvm_sev_hc_page_enc_status(long unsigned int pfn, int npages, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff8109e8f0)
Location: arch/x86/kernel/kvm.c:932
Inline: False
```
**Symbols:**

```
ffffffff8109e8f0-ffffffff8109e92a: kvm_sev_hc_page_enc_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kvm_sev_hc_page_enc_status(long unsigned int pfn, int npages, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810b6030)
Location: arch/x86/kernel/kvm.c:925
Inline: False
```
**Symbols:**

```
ffffffff810b6030-ffffffff810b606a: kvm_sev_hc_page_enc_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kvm_sev_hc_page_enc_status(long unsigned int pfn, int npages, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810b9130)
Location: arch/x86/kernel/kvm.c:925
Inline: False
```
**Symbols:**

```
ffffffff810b9130-ffffffff810b916a: kvm_sev_hc_page_enc_status (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kvm_sev_hc_page_enc_status(long unsigned int pfn, int npages, bool enc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kvm.c (ffffffff810c0570)
Location: arch/x86/kernel/kvm.c:926
Inline: False
```
**Symbols:**

```
ffffffff810c0570-ffffffff810c05aa: kvm_sev_hc_page_enc_status (STB_LOCAL)
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
