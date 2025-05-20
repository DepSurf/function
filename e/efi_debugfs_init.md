# Function: <code>efi_debugfs_init</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void efi_debugfs_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff82d291be)
Location: drivers/firmware/efi/efi.c:301
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff82d291be-ffffffff82d29332: efi_debugfs_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void efi_debugfs_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff830178d6)
Location: drivers/firmware/efi/efi.c:305
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff830178d6-ffffffff83017a4a: efi_debugfs_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void efi_debugfs_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff832227ae)
Location: drivers/firmware/efi/efi.c:305
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff832227ae-ffffffff83222922: efi_debugfs_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void efi_debugfs_init();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8330c47a)
Location: drivers/firmware/efi/efi.c:305
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
**Symbols:**

```
ffffffff8330c47a-ffffffff8330c686: efi_debugfs_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff834c6446)
Location: drivers/firmware/efi/efi.c:311
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff83f0720a)
Location: drivers/firmware/efi/efi.c:296
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8372d2bd)
Location: drivers/firmware/efi/efi.c:322
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff83961697)
Location: drivers/firmware/efi/efi.c:342
Inline: True
Inline callers:
  - drivers/firmware/efi/efi.c:efisubsys_init
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
