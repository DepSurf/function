# Function: <code>add_kmmio_fault_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8107354e)
Location: arch/x86/mm/kmmio.c:357
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81074b39)
Location: arch/x86/mm/kmmio.c:374
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810786b9)
Location: arch/x86/mm/kmmio.c:374
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81076fd8)
Location: arch/x86/mm/kmmio.c:374
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8107d31e)
Location: arch/x86/mm/kmmio.c:375
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81080275)
Location: arch/x86/mm/kmmio.c:380
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81086db5)
Location: arch/x86/mm/kmmio.c:380
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8108a993)
Location: arch/x86/mm/kmmio.c:380
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8108b603)
Location: arch/x86/mm/kmmio.c:380
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int add_kmmio_fault_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810928a0)
Location: arch/x86/mm/kmmio.c:375
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
**Symbols:**

```
ffffffff810928a0-ffffffff810929cd: add_kmmio_fault_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int add_kmmio_fault_page(long unsigned int addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81091f30)
Location: arch/x86/mm/kmmio.c:375
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
**Symbols:**

```
ffffffff81091f30-ffffffff8109205d: add_kmmio_fault_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81092b42)
Location: arch/x86/mm/kmmio.c:375
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810a28ac)
Location: arch/x86/mm/kmmio.c:375
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810b6ee3)
Location: arch/x86/mm/kmmio.c:375
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
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
In arch/x86/mm/kmmio.c (ffffffff810d226c)
Location: arch/x86/mm/kmmio.c:378
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
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
In arch/x86/mm/kmmio.c (ffffffff810d56dc)
Location: arch/x86/mm/kmmio.c:378
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
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
In arch/x86/mm/kmmio.c (ffffffff810ddeac)
Location: arch/x86/mm/kmmio.c:378
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8108a5c3)
Location: arch/x86/mm/kmmio.c:380
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81078e93)
Location: arch/x86/mm/kmmio.c:380
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8108a573)
Location: arch/x86/mm/kmmio.c:380
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8108c813)
Location: arch/x86/mm/kmmio.c:380
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
