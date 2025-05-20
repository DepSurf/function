# Function: <code>hv_is_isolation_supported</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool hv_is_isolation_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81031150)
Location: arch/x86/hyperv/hv_init.c:620
Inline: False
```
**Symbols:**

```
ffffffff81031150-ffffffff81031170: hv_is_isolation_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool hv_is_isolation_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81036a60)
Location: arch/x86/hyperv/hv_init.c:565
Inline: False
```
**Symbols:**

```
ffffffff81036a60-ffffffff81036a80: hv_is_isolation_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool hv_is_isolation_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff8103f200)
Location: arch/x86/hyperv/ivm.c:250
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/ivm.c:hv_set_mem_host_visibility
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/mm/pat/set_memory.c:set_memory_decrypted
  - arch/x86/mm/pat/set_memory.c:set_memory_encrypted
```
**Symbols:**

```
ffffffff8103f200-ffffffff8103f23a: hv_is_isolation_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool hv_is_isolation_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff81048330)
Location: arch/x86/hyperv/ivm.c:250
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
  - arch/x86/hyperv/ivm.c:hv_set_mem_host_visibility
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/mm/pat/set_memory.c:set_memory_decrypted
  - arch/x86/mm/pat/set_memory.c:set_memory_encrypted
```
**Symbols:**

```
ffffffff81048330-ffffffff81048370: hv_is_isolation_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool hv_is_isolation_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff810486e0)
Location: arch/x86/hyperv/ivm.c:394
Inline: False
Direct callers:
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_overwrite_state
  - drivers/hv/hv_common.c:hv_common_init
```
**Symbols:**

```
ffffffff810486e0-ffffffff81048720: hv_is_isolation_supported (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool hv_is_isolation_supported();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff8104f7d0)
Location: arch/x86/hyperv/ivm.c:686
Inline: False
Direct callers:
  - arch/x86/hyperv/ivm.c:hv_mark_gpa_visibility
  - arch/x86/kernel/cpu/mtrr/generic.c:mtrr_overwrite_state
  - drivers/hv/hv_common.c:hv_common_init
```
**Symbols:**

```
ffffffff8104f7d0-ffffffff8104f810: hv_is_isolation_supported (STB_GLOBAL)
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
