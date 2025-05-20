# Function: <code>ima_get_kexec_buffer</code>

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
int ima_get_kexec_buffer(void **addr, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff83e74180)
Location: arch/x86/kernel/setup.c:385
Inline: False
Direct callers:
  - security/integrity/ima/ima_kexec.c:ima_load_kexec_buffer
```
**Symbols:**

```
ffffffff83e74180-ffffffff83e741c8: ima_get_kexec_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ima_get_kexec_buffer(void **addr, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff83695c50)
Location: arch/x86/kernel/setup.c:379
Inline: False
Direct callers:
  - security/integrity/ima/ima_kexec.c:ima_load_kexec_buffer
```
**Symbols:**

```
ffffffff83695c50-ffffffff83695c98: ima_get_kexec_buffer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ima_get_kexec_buffer(void **addr, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff838c5890)
Location: arch/x86/kernel/setup.c:372
Inline: False
Direct callers:
  - security/integrity/ima/ima_kexec.c:ima_load_kexec_buffer
```
**Symbols:**

```
ffffffff838c5890-ffffffff838c58d8: ima_get_kexec_buffer (STB_GLOBAL)
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
int ima_get_kexec_buffer(void **addr, size_t *size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/ima_kexec.c (c0000000000728b0)
Location: arch/powerpc/kernel/ima_kexec.c:56
Inline: False
Direct callers:
  - security/integrity/ima/ima_kexec.c:ima_load_kexec_buffer
```
**Symbols:**

```
c0000000000728b0-c00000000007297c: ima_get_kexec_buffer (STB_GLOBAL)
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
