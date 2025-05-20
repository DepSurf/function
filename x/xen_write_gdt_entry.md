# Function: <code>xen_write_gdt_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void xen_write_gdt_entry(struct desc_struct *dt, int entry, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101cb20)
Location: arch/x86/xen/enlighten.c:902
Inline: True
```
**Symbols:**

```
ffffffff8101cb20-ffffffff8101cbc5: xen_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void xen_write_gdt_entry(struct desc_struct *dt, int entry, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101bee0)
Location: arch/x86/xen/enlighten.c:906
Inline: True
```
**Symbols:**

```
ffffffff8101bee0-ffffffff8101bf7e: xen_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void xen_write_gdt_entry(struct desc_struct *dt, int entry, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten.c (ffffffff8101c6f0)
Location: arch/x86/xen/enlighten.c:908
Inline: True
```
**Symbols:**

```
ffffffff8101c6f0-ffffffff8101c78e: xen_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void xen_write_gdt_entry(struct desc_struct *dt, int entry, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8101f460)
Location: arch/x86/xen/enlighten_pv.c:723
Inline: True
```
**Symbols:**

```
ffffffff8101f460-ffffffff8101f4ff: xen_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void xen_write_gdt_entry(struct desc_struct *dt, int entry, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8101fce0)
Location: arch/x86/xen/enlighten_pv.c:773
Inline: True
```
**Symbols:**

```
ffffffff8101fce0-ffffffff8101fd82: xen_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void xen_write_gdt_entry(struct desc_struct *dt, int entry, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff810207b0)
Location: arch/x86/xen/enlighten_pv.c:749
Inline: True
```
**Symbols:**

```
ffffffff810207b0-ffffffff81020852: xen_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void xen_write_gdt_entry(struct desc_struct *dt, int entry, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81020220)
Location: arch/x86/xen/enlighten_pv.c:771
Inline: True
```
**Symbols:**

```
ffffffff81020220-ffffffff810202c2: xen_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void xen_write_gdt_entry(struct desc_struct *dt, int entry, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81021ea0)
Location: arch/x86/xen/enlighten_pv.c:771
Inline: True
```
**Symbols:**

```
ffffffff81021ea0-ffffffff81021f41: xen_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void xen_write_gdt_entry(struct desc_struct *dt, int entry, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff810227e0)
Location: arch/x86/xen/enlighten_pv.c:779
Inline: True
```
**Symbols:**

```
ffffffff810227e0-ffffffff81022881: xen_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xen_write_gdt_entry(struct desc_struct *dt, int entry, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81025030)
Location: arch/x86/xen/enlighten_pv.c:811
Inline: False
```
**Symbols:**

```
ffffffff81025030-ffffffff810250d2: xen_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xen_write_gdt_entry(struct desc_struct *dt, int entry, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff810256c0)
Location: arch/x86/xen/enlighten_pv.c:786
Inline: False
```
**Symbols:**

```
ffffffff810256c0-ffffffff8102574d: xen_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xen_write_gdt_entry(struct desc_struct *dt, int entry, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81027790)
Location: arch/x86/xen/enlighten_pv.c:808
Inline: False
```
**Symbols:**

```
ffffffff81027790-ffffffff8102781d: xen_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xen_write_gdt_entry(struct desc_struct *dt, int entry, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8102bd70)
Location: arch/x86/xen/enlighten_pv.c:782
Inline: False
```
**Symbols:**

```
ffffffff8102bd70-ffffffff8102bdfa: xen_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xen_write_gdt_entry(struct desc_struct *dt, int entry, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81030860)
Location: arch/x86/xen/enlighten_pv.c:788
Inline: False
```
**Symbols:**

```
ffffffff81030860-ffffffff81030938: xen_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xen_write_gdt_entry(struct desc_struct *dt, int entry, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81037ea0)
Location: arch/x86/xen/enlighten_pv.c:800
Inline: False
```
**Symbols:**

```
ffffffff81037ea0-ffffffff81037f78: xen_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xen_write_gdt_entry(struct desc_struct *dt, int entry, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff810380a0)
Location: arch/x86/xen/enlighten_pv.c:855
Inline: False
```
**Symbols:**

```
ffffffff810380a0-ffffffff81038178: xen_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xen_write_gdt_entry(struct desc_struct *dt, int entry, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff8103e410)
Location: arch/x86/xen/enlighten_pv.c:881
Inline: False
```
**Symbols:**

```
ffffffff8103e410-ffffffff8103e4e8: xen_write_gdt_entry (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void xen_write_gdt_entry(struct desc_struct *dt, int entry, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81022940)
Location: arch/x86/xen/enlighten_pv.c:779
Inline: True
```
**Symbols:**

```
ffffffff81022940-ffffffff810229e1: xen_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void xen_write_gdt_entry(struct desc_struct *dt, int entry, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff810227a0)
Location: arch/x86/xen/enlighten_pv.c:779
Inline: True
```
**Symbols:**

```
ffffffff810227a0-ffffffff81022841: xen_write_gdt_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void xen_write_gdt_entry(struct desc_struct *dt, int entry, const void *desc, int type);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/xen/enlighten_pv.c (ffffffff81022ae0)
Location: arch/x86/xen/enlighten_pv.c:779
Inline: True
```
**Symbols:**

```
ffffffff81022ae0-ffffffff81022bbb: xen_write_gdt_entry (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
<b>Arch</b>
<ul>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
