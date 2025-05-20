# Function: <code>sev_es_active</code>

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
bool sev_es_active();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff81c385e0)
Location: arch/x86/mm/mem_encrypt.c:388
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/kernel/sev-es.c:sev_es_efi_map_ghcbs
  - arch/x86/kernel/sev-es.c:sev_es_init_vc_handling
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
```
**Symbols:**

```
ffffffff81c385e0-ffffffff81c385ee: sev_es_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool sev_es_active();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff81c2a9f0)
Location: arch/x86/mm/mem_encrypt.c:387
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
```
**Symbols:**

```
ffffffff81c2a9f0-ffffffff81c2a9fe: sev_es_active (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool sev_es_active();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff81d48fd0)
Location: arch/x86/mm/mem_encrypt.c:388
Inline: False
Direct callers:
  - arch/x86/realmode/init.c:setup_real_mode
  - arch/x86/kernel/sev.c:sev_es_efi_map_ghcbs
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_init
```
**Symbols:**

```
ffffffff81d48fd0-ffffffff81d48fde: sev_es_active (STB_GLOBAL)
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
</ul>
