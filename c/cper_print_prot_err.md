# Function: <code>cper_print_prot_err</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cper_print_prot_err(const char *pfx, const struct cper_sec_prot_err *prot_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper_cxl.c (ffffffff81d65db0)
Location: drivers/firmware/efi/cper_cxl.c:48
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81d65db0-ffffffff81d66142: cper_print_prot_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cper_print_prot_err(const char *pfx, const struct cper_sec_prot_err *prot_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper_cxl.c (ffffffff81dd0ee0)
Location: drivers/firmware/efi/cper_cxl.c:58
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81dd0ee0-ffffffff81dd1254: cper_print_prot_err (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cper_print_prot_err(const char *pfx, const struct cper_sec_prot_err *prot_err);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/cper_cxl.c (ffffffff81e89c90)
Location: drivers/firmware/efi/cper_cxl.c:58
Inline: False
Direct callers:
  - drivers/firmware/efi/cper.c:cper_estatus_print_section
```
**Symbols:**

```
ffffffff81e89c90-ffffffff81e8a004: cper_print_prot_err (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
