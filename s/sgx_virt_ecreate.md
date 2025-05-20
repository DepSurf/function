# Function: <code>sgx_virt_ecreate</code>

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
int sgx_virt_ecreate(struct sgx_pageinfo *pageinfo, void *secs, int *trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81069440)
Location: arch/x86/kernel/cpu/sgx/virt.c:276
Inline: False
```
**Symbols:**

```
ffffffff81069440-ffffffff8106949f: sgx_virt_ecreate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sgx_virt_ecreate(struct sgx_pageinfo *pageinfo, void *secs, int *trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81073af0)
Location: arch/x86/kernel/cpu/sgx/virt.c:276
Inline: False
```
**Symbols:**

```
ffffffff81073af0-ffffffff81073b4f: sgx_virt_ecreate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sgx_virt_ecreate(struct sgx_pageinfo *pageinfo, void *secs, int *trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81082170)
Location: arch/x86/kernel/cpu/sgx/virt.c:331
Inline: False
```
**Symbols:**

```
ffffffff81082170-ffffffff810821ef: sgx_virt_ecreate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sgx_virt_ecreate(struct sgx_pageinfo *pageinfo, void *secs, int *trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81094ba0)
Location: arch/x86/kernel/cpu/sgx/virt.c:331
Inline: False
```
**Symbols:**

```
ffffffff81094ba0-ffffffff81094c1f: sgx_virt_ecreate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sgx_virt_ecreate(struct sgx_pageinfo *pageinfo, void *secs, int *trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81097ae0)
Location: arch/x86/kernel/cpu/sgx/virt.c:334
Inline: False
```
**Symbols:**

```
ffffffff81097ae0-ffffffff81097b47: sgx_virt_ecreate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sgx_virt_ecreate(struct sgx_pageinfo *pageinfo, void *secs, int *trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f050)
Location: arch/x86/kernel/cpu/sgx/virt.c:334
Inline: False
```
**Symbols:**

```
ffffffff8109f050-ffffffff8109f0b7: sgx_virt_ecreate (STB_GLOBAL)
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
