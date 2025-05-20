# Function: <code>wr_ghcb_msr</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void wr_ghcb_msr(u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff8103f166)
Location: arch/x86/hyperv/ivm.c:106
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol
  - arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol
Direct callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_terminate
```
**Symbols:**

```
ffffffff8103ed60-ffffffff8103ed7e: wr_ghcb_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void wr_ghcb_msr(u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff81048286)
Location: arch/x86/hyperv/ivm.c:106
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol
  - arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol
Direct callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_terminate
```
**Symbols:**

```
ffffffff81047d70-ffffffff81047d8e: wr_ghcb_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void wr_ghcb_msr(u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff81048636)
Location: arch/x86/hyperv/ivm.c:109
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol
  - arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol
Direct callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_terminate
```
**Symbols:**

```
ffffffff81048060-ffffffff8104807e: wr_ghcb_msr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void wr_ghcb_msr(u64 val);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff8104f016)
Location: arch/x86/hyperv/ivm.c:117
Inline: True
Inline callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol
  - arch/x86/hyperv/ivm.c:hv_ghcb_negotiate_protocol
Direct callers:
  - arch/x86/hyperv/ivm.c:hv_ghcb_terminate
```
**Symbols:**

```
ffffffff8104e880-ffffffff8104e89e: wr_ghcb_msr (STB_LOCAL)
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
