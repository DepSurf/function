# Function: <code>elf_kcore_store_hdr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void elf_kcore_store_hdr(char *bufp, int nphdr, int dataoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff812869e0)
Location: fs/proc/kcore.c:319
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
```
**Symbols:**

```
ffffffff812869e0-ffffffff81286cc7: elf_kcore_store_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void elf_kcore_store_hdr(char *bufp, int nphdr, int dataoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff812b3bb0)
Location: fs/proc/kcore.c:319
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
```
**Symbols:**

```
ffffffff812b3bb0-ffffffff812b3e96: elf_kcore_store_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void elf_kcore_store_hdr(char *bufp, int nphdr, int dataoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff812c9440)
Location: fs/proc/kcore.c:319
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
```
**Symbols:**

```
ffffffff812c9440-ffffffff812c9726: elf_kcore_store_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void elf_kcore_store_hdr(char *bufp, int nphdr, int dataoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff812d69b0)
Location: fs/proc/kcore.c:320
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
```
**Symbols:**

```
ffffffff812d69b0-ffffffff812d6e02: elf_kcore_store_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void elf_kcore_store_hdr(char *bufp, int nphdr, int dataoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff812fb200)
Location: fs/proc/kcore.c:321
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
```
**Symbols:**

```
ffffffff812fb200-ffffffff812fb585: elf_kcore_store_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void elf_kcore_store_hdr(char *bufp, int nphdr, int dataoff);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff813287c0)
Location: fs/proc/kcore.c:330
Inline: False
Direct callers:
  - fs/proc/kcore.c:read_kcore
```
**Symbols:**

```
ffffffff813287c0-ffffffff81328b5c: elf_kcore_store_hdr (STB_LOCAL)
```
</details>
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
</ul>
