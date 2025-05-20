# Function: <code>sgx_reclaimer_block</code>

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
void sgx_reclaimer_block(struct sgx_epc_page *epc_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81067d10)
Location: arch/x86/kernel/cpu/sgx/main.c:96
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff81067d10-ffffffff81067f1d: sgx_reclaimer_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sgx_reclaimer_block(struct sgx_epc_page *epc_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068280)
Location: arch/x86/kernel/cpu/sgx/main.c:115
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff81068280-ffffffff81068485: sgx_reclaimer_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void sgx_reclaimer_block(struct sgx_epc_page *epc_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: arch/x86/kernel/cpu/sgx/main.c:114
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff81072700-ffffffff8107293c: sgx_reclaimer_block (STB_LOCAL)
ffffffff81c9ce70-ffffffff81c9ce8a: sgx_reclaimer_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void sgx_reclaimer_block(struct sgx_epc_page *epc_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (0)
Location: arch/x86/kernel/cpu/sgx/main.c:135
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff810809e0-ffffffff81080c33: sgx_reclaimer_block (STB_LOCAL)
ffffffff81e4c203-ffffffff81e4c21e: sgx_reclaimer_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81094080)
Location: arch/x86/kernel/cpu/sgx/main.c:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109700a)
Location: arch/x86/kernel/cpu/sgx/main.c:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e57a)
Location: arch/x86/kernel/cpu/sgx/main.c:141
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
