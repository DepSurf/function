# Function: <code>uv_bios_get_pci_topology</code>

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
s64 uv_bios_get_pci_topology(u64 size, u64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff81099020)
Location: arch/x86/platform/uv/bios_uv.c:223
Inline: False
```
**Symbols:**

```
ffffffff81099020-ffffffff8109907c: uv_bios_get_pci_topology (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
s64 uv_bios_get_pci_topology(u64 size, u64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff81099840)
Location: arch/x86/platform/uv/bios_uv.c:223
Inline: False
```
**Symbols:**

```
ffffffff81099840-ffffffff8109989c: uv_bios_get_pci_topology (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
s64 uv_bios_get_pci_topology(u64 size, u64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff810a9860)
Location: arch/x86/platform/uv/bios_uv.c:223
Inline: False
```
**Symbols:**

```
ffffffff810a9860-ffffffff810a98bc: uv_bios_get_pci_topology (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
s64 uv_bios_get_pci_topology(u64 size, u64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff810bf160)
Location: arch/x86/platform/uv/bios_uv.c:223
Inline: False
```
**Symbols:**

```
ffffffff810bf160-ffffffff810bf1cc: uv_bios_get_pci_topology (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
s64 uv_bios_get_pci_topology(u64 size, u64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff810daea0)
Location: arch/x86/platform/uv/bios_uv.c:223
Inline: False
```
**Symbols:**

```
ffffffff810daea0-ffffffff810daf0c: uv_bios_get_pci_topology (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
s64 uv_bios_get_pci_topology(u64 size, u64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff810e6430)
Location: arch/x86/platform/uv/bios_uv.c:223
Inline: False
```
**Symbols:**

```
ffffffff810e6430-ffffffff810e649c: uv_bios_get_pci_topology (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
s64 uv_bios_get_pci_topology(u64 size, u64 *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/uv/bios_uv.c (ffffffff810ee7b0)
Location: arch/x86/platform/uv/bios_uv.c:223
Inline: False
```
**Symbols:**

```
ffffffff810ee7b0-ffffffff810ee81c: uv_bios_get_pci_topology (STB_GLOBAL)
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
