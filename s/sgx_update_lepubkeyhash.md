# Function: <code>sgx_update_lepubkeyhash</code>

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
void sgx_update_lepubkeyhash(u64 *lepubkeyhash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810693c0)
Location: arch/x86/kernel/cpu/sgx/main.c:738
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_einit
```
**Symbols:**

```
ffffffff810693c0-ffffffff810693fe: sgx_update_lepubkeyhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sgx_update_lepubkeyhash(u64 *lepubkeyhash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81073a70)
Location: arch/x86/kernel/cpu/sgx/main.c:738
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_einit
```
**Symbols:**

```
ffffffff81073a70-ffffffff81073aae: sgx_update_lepubkeyhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sgx_update_lepubkeyhash(u64 *lepubkeyhash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81082020)
Location: arch/x86/kernel/cpu/sgx/main.c:900
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_einit
```
**Symbols:**

```
ffffffff81082020-ffffffff81082094: sgx_update_lepubkeyhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sgx_update_lepubkeyhash(u64 *lepubkeyhash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81094a30)
Location: arch/x86/kernel/cpu/sgx/main.c:858
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_einit
```
**Symbols:**

```
ffffffff81094a30-ffffffff81094aa4: sgx_update_lepubkeyhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sgx_update_lepubkeyhash(u64 *lepubkeyhash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810979d0)
Location: arch/x86/kernel/cpu/sgx/main.c:858
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_einit
```
**Symbols:**

```
ffffffff810979d0-ffffffff81097a44: sgx_update_lepubkeyhash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sgx_update_lepubkeyhash(u64 *lepubkeyhash);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109ef40)
Location: arch/x86/kernel/cpu/sgx/main.c:858
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_init
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_virt_einit
```
**Symbols:**

```
ffffffff8109ef40-ffffffff8109efb4: sgx_update_lepubkeyhash (STB_GLOBAL)
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
