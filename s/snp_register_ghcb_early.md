# Function: <code>snp_register_ghcb_early</code>

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
void snp_register_ghcb_early(long unsigned int paddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810a4d50)
Location: arch/x86/kernel/sev-shared.c:124
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:setup_ghcb
```
**Symbols:**

```
ffffffff810a4d50-ffffffff810a4db3: snp_register_ghcb_early (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void snp_register_ghcb_early(long unsigned int paddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810bd440)
Location: arch/x86/kernel/sev-shared.c:124
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:setup_ghcb
```
**Symbols:**

```
ffffffff810bd440-ffffffff810bd4a3: snp_register_ghcb_early (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void snp_register_ghcb_early(long unsigned int paddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c0ab0)
Location: arch/x86/kernel/sev-shared.c:127
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:setup_ghcb
```
**Symbols:**

```
ffffffff810c0ab0-ffffffff810c0b13: snp_register_ghcb_early (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void snp_register_ghcb_early(long unsigned int paddr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff810c7f10)
Location: arch/x86/kernel/sev-shared.c:127
Inline: False
Direct callers:
  - arch/x86/kernel/sev.c:setup_ghcb
  - arch/x86/kernel/sev.c:setup_ghcb
```
**Symbols:**

```
ffffffff810c7f10-ffffffff810c7f73: snp_register_ghcb_early (STB_LOCAL)
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
