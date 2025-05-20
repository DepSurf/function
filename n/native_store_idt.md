# Function: <code>native_store_idt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
void native_store_idt(struct desc_ptr *dtr);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101b980)
Location: arch/x86/include/asm/desc.h:231
Inline: False
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064740)
Location: arch/x86/include/asm/desc.h:231
Inline: False
```
**Symbols:**

```
ffffffff8101b980-ffffffff8101b989: native_store_idt (STB_LOCAL)
ffffffff81064740-ffffffff81064749: native_store_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate ⚠️</summary>

```c
void native_store_idt(struct desc_ptr *dtr);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101ad70)
Location: arch/x86/include/asm/desc.h:231
Inline: False
```
```
In arch/x86/kernel/paravirt.c (ffffffff81064390)
Location: arch/x86/include/asm/desc.h:231
Inline: False
```
**Symbols:**

```
ffffffff8101ad70-ffffffff8101ad79: native_store_idt (STB_LOCAL)
ffffffff81064390-ffffffff81064399: native_store_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate ⚠️</summary>

```c
void native_store_idt(struct desc_ptr *dtr);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101b4a0)
Location: arch/x86/include/asm/desc.h:231
Inline: False
```
```
In arch/x86/kernel/paravirt.c (ffffffff81067860)
Location: arch/x86/include/asm/desc.h:231
Inline: False
```
**Symbols:**

```
ffffffff8101b4a0-ffffffff8101b4a9: native_store_idt (STB_LOCAL)
ffffffff81067860-ffffffff81067869: native_store_idt (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate ⚠️</summary>

```c
void native_store_idt(struct desc_ptr *dtr);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8101e590)
Location: arch/x86/include/asm/desc.h:251
Inline: False
```
```
In arch/x86/kernel/paravirt.c (ffffffff81066af0)
Location: arch/x86/include/asm/desc.h:251
Inline: False
```
**Symbols:**

```
ffffffff8101e590-ffffffff8101e599: native_store_idt (STB_LOCAL)
ffffffff81066af0-ffffffff81066af9: native_store_idt (STB_LOCAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
</ul>
