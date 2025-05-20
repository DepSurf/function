# Function: <code>hv_ghcb_hypercall</code>

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
u64 hv_ghcb_hypercall(u64 control, void *input, void *output, u32 input_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff8103f000)
Location: arch/x86/hyperv/ivm.c:58
Inline: False
```
**Symbols:**

```
ffffffff8103f000-ffffffff8103f117: hv_ghcb_hypercall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
u64 hv_ghcb_hypercall(u64 control, void *input, void *output, u32 input_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff81d7cf60)
Location: arch/x86/hyperv/ivm.c:58
Inline: False
```
**Symbols:**

```
ffffffff82051f34-ffffffff82051f49: hv_ghcb_hypercall.cold (STB_LOCAL)
ffffffff81048080-ffffffff8104821d: hv_ghcb_hypercall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
u64 hv_ghcb_hypercall(u64 control, void *input, void *output, u32 input_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff81deb130)
Location: arch/x86/hyperv/ivm.c:61
Inline: False
```
**Symbols:**

```
ffffffff820d042a-ffffffff820d043f: hv_ghcb_hypercall.cold (STB_LOCAL)
ffffffff81048430-ffffffff810485ca: hv_ghcb_hypercall (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
u64 hv_ghcb_hypercall(u64 control, void *input, void *output, u32 input_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff81ea13a0)
Location: arch/x86/hyperv/ivm.c:69
Inline: False
```
**Symbols:**

```
ffffffff821aae7e-ffffffff821aae93: hv_ghcb_hypercall.cold (STB_LOCAL)
ffffffff8104ee10-ffffffff8104efaa: hv_ghcb_hypercall (STB_GLOBAL)
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
