# Function: <code>hv_ghcb_terminate</code>

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
void hv_ghcb_terminate(unsigned int set, unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff8103f120)
Location: arch/x86/hyperv/ivm.c:130
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff8103f120-ffffffff8103f14e: hv_ghcb_terminate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void hv_ghcb_terminate(unsigned int set, unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff81048230)
Location: arch/x86/hyperv/ivm.c:130
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff81048230-ffffffff8104825e: hv_ghcb_terminate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void hv_ghcb_terminate(unsigned int set, unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff810485e0)
Location: arch/x86/hyperv/ivm.c:133
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff810485e0-ffffffff8104860e: hv_ghcb_terminate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void hv_ghcb_terminate(unsigned int set, unsigned int reason);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/hyperv/ivm.c (ffffffff8104efc0)
Location: arch/x86/hyperv/ivm.c:141
Inline: False
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
**Symbols:**

```
ffffffff8104efc0-ffffffff8104efee: hv_ghcb_terminate (STB_GLOBAL)
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
