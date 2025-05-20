# Function: <code>sgx_encl_put_backing</code>

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
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void sgx_encl_put_backing(struct sgx_backing *backing, bool do_write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810662ac)
Location: arch/x86/kernel/cpu/sgx/encl.c:617
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_write
```
**Symbols:**

```
ffffffff81066870-ffffffff81066944: sgx_encl_put_backing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void sgx_encl_put_backing(struct sgx_backing *backing, bool do_write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066703)
Location: arch/x86/kernel/cpu/sgx/encl.c:609
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff81066810-ffffffff810668e4: sgx_encl_put_backing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void sgx_encl_put_backing(struct sgx_backing *backing, bool do_write);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810708cc)
Location: arch/x86/kernel/cpu/sgx/encl.c:650
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff81070aa0-ffffffff81070b6e: sgx_encl_put_backing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void sgx_encl_put_backing(struct sgx_backing *backing);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8107defb)
Location: arch/x86/kernel/cpu/sgx/encl.c:851
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff8107e9a0-ffffffff8107eaeb: sgx_encl_put_backing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void sgx_encl_put_backing(struct sgx_backing *backing);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8108f3e3)
Location: arch/x86/kernel/cpu/sgx/encl.c:1082
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff8108ffd0-ffffffff81090119: sgx_encl_put_backing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void sgx_encl_put_backing(struct sgx_backing *backing);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff810922e3)
Location: arch/x86/kernel/cpu/sgx/encl.c:1084
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff81092ee0-ffffffff8109302a: sgx_encl_put_backing (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void sgx_encl_put_backing(struct sgx_backing *backing);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81099703)
Location: arch/x86/kernel/cpu/sgx/encl.c:1104
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_eldu
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff8109a320-ffffffff8109a464: sgx_encl_put_backing (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool do_write</code>
</li>
</ul>
</details>
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
