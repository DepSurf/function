# Function: <code>sgx_virt_einit</code>

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
int sgx_virt_einit(void *sigstruct, void *token, void *secs, u64 *lepubkeyhash, int *trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff810697a0)
Location: arch/x86/kernel/cpu/sgx/virt.c:350
Inline: False
```
**Symbols:**

```
ffffffff810697a0-ffffffff81069804: sgx_virt_einit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sgx_virt_einit(void *sigstruct, void *token, void *secs, u64 *lepubkeyhash, int *trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81073bc0)
Location: arch/x86/kernel/cpu/sgx/virt.c:350
Inline: False
```
**Symbols:**

```
ffffffff81073bc0-ffffffff81073c24: sgx_virt_einit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sgx_virt_einit(void *sigstruct, void *token, void *secs, u64 *lepubkeyhash, int *trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81082390)
Location: arch/x86/kernel/cpu/sgx/virt.c:405
Inline: False
```
**Symbols:**

```
ffffffff81082390-ffffffff81082417: sgx_virt_einit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sgx_virt_einit(void *sigstruct, void *token, void *secs, u64 *lepubkeyhash, int *trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81094df0)
Location: arch/x86/kernel/cpu/sgx/virt.c:405
Inline: False
```
**Symbols:**

```
ffffffff81094df0-ffffffff81094e77: sgx_virt_einit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sgx_virt_einit(void *sigstruct, void *token, void *secs, u64 *lepubkeyhash, int *trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81097ce0)
Location: arch/x86/kernel/cpu/sgx/virt.c:408
Inline: False
```
**Symbols:**

```
ffffffff81097ce0-ffffffff81097d67: sgx_virt_einit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sgx_virt_einit(void *sigstruct, void *token, void *secs, u64 *lepubkeyhash, int *trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff8109f250)
Location: arch/x86/kernel/cpu/sgx/virt.c:408
Inline: False
```
**Symbols:**

```
ffffffff8109f250-ffffffff8109f2d7: sgx_virt_einit (STB_GLOBAL)
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
