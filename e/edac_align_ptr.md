# Function: <code>edac_align_ptr</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void *edac_align_ptr(void **p, unsigned int size, int n_elems);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff8175d16f)
Location: drivers/edac/edac_mc.c:239
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
Direct callers:
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
```
**Symbols:**

```
ffffffff8175d7b0-ffffffff8175d812: edac_align_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void *edac_align_ptr(void **p, unsigned int size, int n_elems);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff817cf1df)
Location: drivers/edac/edac_mc.c:239
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
Direct callers:
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
```
**Symbols:**

```
ffffffff817cf820-ffffffff817cf882: edac_align_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void *edac_align_ptr(void **p, unsigned int size, int n_elems);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81817d58)
Location: drivers/edac/edac_mc.c:241
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
Direct callers:
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
```
**Symbols:**

```
ffffffff81818350-ffffffff818183b2: edac_align_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void *edac_align_ptr(void **p, unsigned int size, int n_elems);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff818435ea)
Location: drivers/edac/edac_mc.c:239
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
Direct callers:
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
```
**Symbols:**

```
ffffffff81843c00-ffffffff81843c62: edac_align_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void *edac_align_ptr(void **p, unsigned int size, int n_elems);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81886448)
Location: drivers/edac/edac_mc.c:239
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
Direct callers:
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
```
**Symbols:**

```
ffffffff818869c0-ffffffff81886a22: edac_align_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *edac_align_ptr(void **p, unsigned int size, int n_elems);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff818b8408)
Location: drivers/edac/edac_mc.c:239
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
Direct callers:
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
```
**Symbols:**

```
ffffffff818b8980-ffffffff818b89e2: edac_align_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *edac_align_ptr(void **p, unsigned int size, int n_elems);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff8198904e)
Location: drivers/edac/edac_mc.c:186
Inline: True
Direct callers:
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
```
**Symbols:**

```
ffffffff81989200-ffffffff81989262: edac_align_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *edac_align_ptr(void **p, unsigned int size, int n_elems);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff8198cfee)
Location: drivers/edac/edac_mc.c:190
Inline: True
Direct callers:
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
```
**Symbols:**

```
ffffffff8198d1a0-ffffffff8198d202: edac_align_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void *edac_align_ptr(void **p, unsigned int size, int n_elems);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff819715ac)
Location: drivers/edac/edac_mc.c:190
Inline: True
Direct callers:
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
```
**Symbols:**

```
ffffffff81971860-ffffffff819718c2: edac_align_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void *edac_align_ptr(void **p, unsigned int size, int n_elems);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81a1a194)
Location: drivers/edac/edac_mc.c:193
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
Direct callers:
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
```
**Symbols:**

```
ffffffff81a1a510-ffffffff81a1a572: edac_align_ptr (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void *edac_align_ptr(void **p, unsigned int size, int n_elems);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffff800010b10608)
Location: drivers/edac/edac_mc.c:239
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
Direct callers:
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
```
**Symbols:**

```
ffff800010b10b68-ffff800010b10bfc: edac_align_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *edac_align_ptr(void **p, unsigned int size, int n_elems);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (c0beea14)
Location: drivers/edac/edac_mc.c:239
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
Direct callers:
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
```
**Symbols:**

```
c0beeff0-c0bef06c: edac_align_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void *edac_align_ptr(void **p, unsigned int size, int n_elems);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (c000000000c041c8)
Location: drivers/edac/edac_mc.c:239
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
Direct callers:
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
```
**Symbols:**

```
c000000000c04890-c000000000c0492c: edac_align_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void *edac_align_ptr(void **p, unsigned int size, int n_elems);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffe0006fd66a)
Location: drivers/edac/edac_mc.c:239
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
Direct callers:
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
```
**Symbols:**

```
ffffffe0006fdb22-ffffffe0006fdb98: edac_align_ptr (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void *edac_align_ptr(void **p, unsigned int size, int n_elems);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff8185e288)
Location: drivers/edac/edac_mc.c:239
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
Direct callers:
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
```
**Symbols:**

```
ffffffff8185e800-ffffffff8185e862: edac_align_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *edac_align_ptr(void **p, unsigned int size, int n_elems);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff81825858)
Location: drivers/edac/edac_mc.c:239
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
Direct callers:
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
```
**Symbols:**

```
ffffffff81825dd0-ffffffff81825e32: edac_align_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *edac_align_ptr(void **p, unsigned int size, int n_elems);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff818ad8b8)
Location: drivers/edac/edac_mc.c:239
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
Direct callers:
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
```
**Symbols:**

```
ffffffff818ade30-ffffffff818ade92: edac_align_ptr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *edac_align_ptr(void **p, unsigned int size, int n_elems);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/edac/edac_mc.c (ffffffff818c9b48)
Location: drivers/edac/edac_mc.c:239
Inline: True
Inline callers:
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
  - drivers/edac/edac_mc.c:edac_mc_alloc
Direct callers:
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_device.c:edac_device_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
  - drivers/edac/edac_pci.c:edac_pci_alloc_ctl_info
```
**Symbols:**

```
ffffffff818ca0c0-ffffffff818ca122: edac_align_ptr (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
