# Function: <code>ima_free_kexec_buffer</code>

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
int ima_free_kexec_buffer();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff83e74110)
Location: arch/x86/kernel/setup.c:367
Inline: False
Direct callers:
  - security/integrity/ima/ima_kexec.c:ima_load_kexec_buffer
```
**Symbols:**

```
ffffffff83e74110-ffffffff83e74163: ima_free_kexec_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ima_free_kexec_buffer();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff83695be0)
Location: arch/x86/kernel/setup.c:361
Inline: False
Direct callers:
  - security/integrity/ima/ima_kexec.c:ima_load_kexec_buffer
```
**Symbols:**

```
ffffffff83695be0-ffffffff83695c33: ima_free_kexec_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ima_free_kexec_buffer();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff838c5820)
Location: arch/x86/kernel/setup.c:358
Inline: False
Direct callers:
  - security/integrity/ima/ima_kexec.c:ima_load_kexec_buffer
```
**Symbols:**

```
ffffffff838c5820-ffffffff838c5871: ima_free_kexec_buffer (STB_GLOBAL)
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
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ima_free_kexec_buffer();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/ima_kexec.c (c000000000072980)
Location: arch/powerpc/kernel/ima_kexec.c:80
Inline: False
Direct callers:
  - security/integrity/ima/ima_kexec.c:ima_load_kexec_buffer
```
**Symbols:**

```
c000000000072980-c000000000072a5c: ima_free_kexec_buffer (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
